# Organizando geodados no Mapbox

O Mapbox Studio consiste numa plataforma em que você fará o upload dos dados geográficos que você quiser trabalhar, ele funciona como um "Photoshop para mapas", segundo o site oficial da empresa. Então, existe um fluxo de trabalho de criar os dados, organizar os dados, e depois exportá-los para a plataforma.&#x20;

Atualmente, o Mapbox Studio aceita o formatos GeoTIFF para arquivos em malha (raster) e diversos outros para dados vetoriais (MBTiles, KML, GPX, GeoJSON, Shapefile zipado ou tabelas CSV). Você pode usar uma solução online e de código aberto como o [QGIS](https://qgis.org) ou [Mapshaper](https://mapshaper.org/) para criar os seus dados geográficos ou para fazer conversão de formatos. Você também pode criar os seus dados diretamente dentro do Mapbox, através da criação de um Dataset, porém softwares como o QGIS são mais completos em termos de ferramentas para a criação e edição desses dados. &#x20;

### Organizando geodados

Antes de iniciar o trabalho com o Mapbox, vale a pena relembrar algumas boas práticas ao trabalhar com dados geográficos, que irão ajudar no desenvolvimento do seu projeto.

A versão gratuita do Mapbox só permite que você realize o upload de 15 [Tilesets](https://docs.mapbox.com/help/glossary/tileset/), mas seu mapa não está restrito a apenas 15 dados, um tileset corresponde a uma **coleção** de dados. E o Mapbox só permite que você faça o upload de um tipo de geometria por tileset (Por exemplo, uma camada shapefile exportada para um tileset com vários **polígonos**, outra camada exportada que só contém **pontos**, e outra só com **vetores**).

Outra boa prática consiste em verificar se todos os dados geográficos estão numa mesma projeção geográfica. E adotar um padrão consistente para nomear os arquivos poderá facilitar a manipulação de muitos dados de uma vez só.

Depois de organizar os seus dados, crie uma conta no [Mapbox ](https://www.mapbox.com/)e realize o upload deles no campo Tilesets.

<figure><img src=".gitbook/assets/image (47).png" alt=""><figcaption><p>Aba de Tilesets do Mapbox. "New tileset" é o campo em que você realiza o upload de arquivos</p></figcaption></figure>

### Criando um novo mapa

Para criar um novo mapa no Mapbox você deve configurar antes o estilo do mapa base do seu projeto. Esta será a camada que, em geral, irá ficar abaixo das demais, para servir como referência. Você pode configurar um estilo novo através do botão azul "New Style" ou duplicar um estilo existente.

<figure><img src=".gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

Ao criar um novo estilo você pode usar o estilo do **Mapbox Standard** que tem um mapa bem completo com cores diferentes para diferentes tipos de vias, nomes de lougradouros, etc... Ou você pode **criar um estilo novo do zero**.&#x20;

Utilizar o Mapbox Standard seria ótimo, a questão é que ao usar esse mapa Standard, uma funcionalidade importante da Documental fica comprometida, a funcionalidade dos Filtros dos Layers (essa é uma limitação do próprio Mapbox).

Mas fique tranquilo, se você não quiser configurar os componentes de um mapa todo do zero, existem dois modelos disponibilizados no Mapbox da autônoma que estão públicos e podem ser copiados por você, para que você crie a sua história por cima, o Monochrome Style e o Dark Style:

[Monochrome Style URL](mapbox://styles/studio-autonoma/cmdgcs27u019101sa29ytbsps), [Dark Style URL](mapbox://styles/studio-autonoma/cmdgcp72i003701qw07pk8bo3) e [documentação do Mapbox ensinando como copiar um estilo de outra conta para a sua](https://docs.mapbox.com/help/dive-deeper/transfer-styles-between-accounts/).

<figure><img src=".gitbook/assets/image (49).png" alt=""><figcaption><p>Opções para criar um estilo novo: Mapbox Standard, criar um estilo novo (Start from scratch) e fazer o upload de um estilo existente em JSON (Upload).</p></figcaption></figure>

### Personalizando um mapa

Um mapa do Mapbox configurado tem mais ou menos essa cara. A barra à esquerda contém as camadas de dados do projeto, você acrescenta geodados no projeto através do ícone de `+`.&#x20;

Na barra cinza inferior você tem informações sobre o zoom da tela e as coordenadas do centro da vista. São esses mesmos dados que você insere nos campos Zoom, Latitude e Longitude da Documental,  depois de enquadrar no Mapbox a vista do mapa que você deseja reproduzir na Documental.

<figure><img src=".gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>



Voltando para a inserção de geodados no projeto, quando você clica no ícone `+` , uma nova camada é criada, e você adiciona o geodado em Source, dentro do campo Select data.&#x20;

Você pode aplicar um filtro  ao selecionar o dado, o filtro pode ser aplicado em cima dos Atributos associados ao geodado, atributos que você pode inserir, manipular dentro do QGIS por exemplo. A ferramenta de filtragem do Mapbox é útil para individualizar elementos em camadas, tendo em vista que você tem um limite de upload de 15 tilesets no Mapbox, mas cuidado para não abusar, o Mapbox não funciona bem com muitas camadas. Bom lembrar que além desse mecanismo de filtro do Mapbox, você também consegue fazer filtros em layers dentro da Documental. Ambos mecanismos são úteis para narrativas complexas com muitos dados.

<figure><img src=".gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

&#x20;Depois de escolher o geodado, você move para a aba Syle e configura o estilo de sua preferência para a sua camada. Confira a [documentação do Mapbox](https://docs.mapbox.com/studio-manual/reference/styles/) para mais orientações sobre esta etapa.

<figure><img src=".gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>



### Compartilhando o mapa

Para conectar a Documental a sua conta do Mapbox, você irá precisar destas duas informações:

**Mapbox** **Style**: um caminho do estilo criado no sistema do Mapbox. Por exemplo: `mapbox://styles/usuaria/ckcb6q2pe2b3149s11kk9zr9u`

**Mapbox Access Token**: é uma longa sequência aleatória de caracteres, que serve como senha para acessar seus dados no Mapbox. Por exemplo: `pk.eyJ1IjoibWFybUXQjwiwiYS31IjlmYlhtaEkif2.vMxORYorRKnueDl3c5idQQ`

Você encontra esses dados ao clicar no botão "**Share**", localizado no lado superior direito do Mapbox. Um quadro irá abrir, e ambas informações estão na seção "**Developer resources**".

