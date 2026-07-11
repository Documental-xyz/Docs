# Criando uma história

Para publicar uma história na plataforma da Documental 2.0, selecione o botão "Novo" no canto superior direito da tela. Primeiramente, preencha os campos "Título da história e o "Link da página", e é importante que esses dois campos tenham valores únicos em relação às outras geohistórias, pois informações duplicadas podem causar erros na plataforma. Abaixo desses campos, encontram-se as seções `Configurações da Página`, `Tema da Página`, `Configurações do Mapbox` e, por fim, a aba `Componentes`, onde serão inseridos os blocos que formam o conteúdo da página.

<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>



### Configurações da página

Em configurações da página, você define o Idioma da página. Para disponibilizá-la em outro idioma, crie uma nova versão no idioma desejado e selecione a opção correspondente. Quando há mais de um idioma, as opções aparecem no menu lateral da página publicada. No campo Link, indique o endereço da página em cada idioma.

<figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

Nessa aba também é possível controlar a exibição das animações dos blocos, ajustar o alinhamento do texto e configurar os parâmetros de SEO (otimização para mecanismos de busca), que aprimoram a visibilidade da página em resultados de pesquisa e compartilhamentos.

<figure><img src="../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

####

### Tema da página

No campo Tema da Página, você configura a paleta de cores que compõe a sua página. Há uma fonte padrão aplicada, mas é possível personalizá-la [inserindo uma fonte do Google Fonts](fontes-personalizadas.md). Também é possível ajustar o espaçamento entre linhas do texto.

<figure><img src="../.gitbook/assets/image (37).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption></figcaption></figure>

####

### Configurações do Mapbox

Os blocos de mapas são a essência da construção de narrativas baseadas em mapas no Documental. Na seção Configurações do Mapbox você insere as configurações básicas para integrar o mapa do Mapbox a Documental (não é possível criar uma história na Documental sem configurar um mapa do Mapbox). Depois, é nessa mesma seção que você configura todas as vistas de mapas que irão aparecer na página. E somente na seção de Componentes, você insere essas vistas na geohistória através do componente Map.

Depois de copiar o Map Style e o Map Token no Mapbox, insira essas informações nos respectivos campos da Documental. Depois disso, será necessário definir qual a visualização inicial ou "ponto de partida" no mapa, através de algumas configurações básicas que compõem uma **vista** do Mapbox na Documental:

* Localização do ponto central do mapa, através da latitude e longitude;
* Nível de zoom do mapa;
* Duração da transição entre os blocos, em milissegundos<mark style="color:red;">\*</mark>;
* [Bearing](https://docs.mapbox.com/help/glossary/bearing/): a rotação da câmera na horizontal<mark style="color:red;">\*</mark>;
* Pitch: a rotação da câmera na vertical<mark style="color:red;">\*</mark>;
* Layers do Mapbox que devem ser exibidos. É possível fazer [filtros para que apenas determinados dados (feições) apareçam](_filtros-de-layers.md);

<mark style="color:red;">\*A duração da transição entre os blocos, o bearing e o pitch são configurações opcionais que não afetam a implementação dos mapas.</mark>

<figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

**Vistas do Mapa**

Depois de configurar a primeira vista, você verá o campo para adicionar as demais vistas que irão compor a página. Cada vista tem um identificador (ID) **único**, que não deve ser repetido em outra vista, e não deve conter espaços e caracteres especiais. Preencha a localização do mapa (longitude e latitude). O campo do zoom é apropriado para o funcionamento do mapa em notebooks e outros desktops, é recomendado verificar um zoom apropriado para mobile e tablet também. E em seguida, ajuste duração, bearing, pitch e as layers, todos os parâmetros voltados para essa vista específica.

<figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

Existe também um campo para definir a legenda de cada vista. Nele você define rótulos explicativos para os dados, podendo incluir um título e uma descrição se quiser. Ao abrir a aba, escolha o campo que será exibido na legenda e se quiser, [defina um ícone personalizado via Google Icons](icones-de-legendas.md), selecione sua cor e indique se o ícone será preenchido ou apenas contornado.

<figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>



### Componentes

É através da seção Componentes que o conteúdo da página é montado. Em "Adicionar componentes" existem 4 tipos de blocos principais que podem ser utilizados: Group, Map, CTA e Spacer.

<figure><img src="../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

O bloco principal Group é um tipo genérico que reúne outros blocos. Ele permite definir cores diferentes para o fundo e o texto, e acaba sendo utilizado para separar capítulos de conteúdo. O bloco principal Map deve ser utilizado sempre que você quiser inserir um mapa na página, é por meio dele que são adicionadas as Mapviews. O bloco CTA (Call to Action) serve para direcionar o visitante a uma ação específica, como clicar em um botão. Já o bloco Spacer tem a função simples de adicionar espaçamento entre os elementos da página.&#x20;

<figure><img src="../.gitbook/assets/image (44).png" alt=""><figcaption><p>Bloco Mapa</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (45).png" alt=""><figcaption><p>Bloco CTA (Call to Action)</p></figcaption></figure>

Cada bloco precisa ter um ID único, sem espaços ou caracteres especiais, além de um Short Title, que aparece no menu de Componentes no painel de administração da página, e um Long Title, exibido no menu lateral da página publicada.

O bloco Group oferece nas configurações iniciais a opção de adicionar uma Background media, que pode ser um vídeo ou uma imagem armazenada no repositório de arquivos da Documental. Essa mídia pode receber uma camada de overlay com cor personalizável.&#x20;

No final dos blocos Group e Map, vemos o botão Add Components, onde conseguimos inserir os blocos que formatam a página. A composição das páginas da Documental é formada pela combinação desses blocos, e abaixo estão dois exemplos que ilustram como as páginas podem ser montadas:

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

No primeiro grupo, foi utilizado o bloco Column Sticky, que pode servir como capa da página. Dentro dele foram inseridas informações de texto com o bloco Text, e a posição dos textos foi ajustada com os blocos Spacer. No segundo grupo, o conteúdo foi estruturado em formato de texto corrido com o bloco Column, que reúne dois blocos Text e no final um bloco Pullquote para destacar uma citação.

A página [Biblioteca de blocos](biblioteca-de-blocos.md) apresenta uma relação completa de todos os blocos disponíveis e suas respectivas funções.

