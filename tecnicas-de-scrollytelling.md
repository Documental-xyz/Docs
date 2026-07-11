# Técnicas de scrollytelling

### O que é scrollytelling?

Baseado nos termos "scroll" (rolagem) e "storytelling" (contação de histórias), scrollytelling designa recursos utilizados em páginas web, onde a rolagem de tela controla a narrativa. Esta prática ganhou destaque inicial em publicações online do chamado "long form journalism" ou "jornalismo forma longa", porém, os mesmos esquemas narrativos e tecnologias também podem ser utilizados de forma mais ampla.

A rolagem de tela é uma da formas mais intuitivas de experiência do usuário durante a utilização de dispositivos eletrônicos, sejam eles tablets, computadores desktop ou celulares. Mesmo pessoas leigas ou crianças pequenas são capazes de reproduzir este gesto em celulares, por exemplo. Com o scrollytelling, este ato simples pode controlar a aparição de textos, fotos, vídeos ou a navegação por um mapa, como implementa o Documental, além de outras possibilidades, como a transição entre diferentes formas de visualizar dados sobre um mesmo tema.

### Softwares e plataformas

#### Plataformas

Até o momento, não existem muitas opções gratuitas de plataformas que forneçam uma interface gráfica para a construção de narrativas com scrollyteling. A alternativa mais conhecida é o [Flourish.Studio](https://help.flourish.studio/article/21-controlling-stories-with-scrollytelling), que já publicou um artigo específico sobre este recurso. O Documental destaca-se por uma solução de código aberto que, a partir do Sveltia e do Mapbox, fornece uma interface gráfica para controle do scrollyteling e inclusão dos conteúdos que formam a narrativa.

Existem, porém, diversas opções gratuitas ou de código aberto disponíveis atualmente para implementar páginas com recursos de _scrolytelling_ "do zero". No caso do _scrollytelling_, em [artigo de janeiro de 2017](https://pudding.cool/process/how-to-implement-scrollytelling/), Russell Goldenberg elenca seis alternativas para construir uma página com scrollyteling "do zero", junto com demonstrações de seus códigos em funcionamento. A elas, foram adicionadas outras referências (entre elas a própria biblioteca mantida pelo autor, criada em outubro de 2017) e comentários próprios. As opções estão listadas de acordo com a contribuição mais recente feita em seus respectivos repositórios.

* [JEO](https://github.com/InfoAmazonia/jeo-plugin): Solução para WordPress criada pelo InfoAmazônia que permite inserir blocos de mapa interativos no editor Gutenberg.
* [Scrollama](https://github.com/russellgoldenberg/scrollama): biblioteca criada por Russel Goldenberg. Conta com uma [página com diferentes modelos prontos para uso](https://russellgoldenberg.github.io/scrollama/basic/). É uma opção relativamente acessível, mesmo para quem tem apenas conhecimentos básicos de JavaScript. O [vídeo tutorial de Jonathan Soma](https://www.youtube.com/watch?v=d7wTA9F-l8c) apresenta um bom passo a passo da implementação de uma página do tipo. Para trabalhar com mapas, vale conferir o repositório feito pelo Mapbox, com base no Scrollama.
* [Scrollmagic](http://scrollmagic.io/): recomendada por Goldenberg para casos que exigem bastante personalização da interação. ([repositório](https://github.com/janpaepke/ScrollMagic)).
* [Scrollstory](http://sjwilliams.github.io/scrollstory/): plugin em jQuery utilizado em algumas histórias do The New York Times. É recomendado por Goldenberg para iniciantes que utilizam jQuery ([repositório](https://github.com/sjwilliams/scrollstory)).
* [graph-scroll](https://1wheel.github.io/graph-scroll/): é plugin baseado na biblioteca D3 que fornece recursos simples para scrollytelling. Recomendável especialmente para visualizações de dados que também façam uso de D3 ([repositório](https://github.com/1wheel/graph-scroll)).

O artigo de Goldenberg também cita duas bibliotecas que estão há mais tempo inativas, como o [Waypoints](http://imakewebthings.com/waypoints/), cuja última atualização do [repositório](https://github.com/imakewebthings/waypoints) é de setembro de 2016, e o [in-view.js](https://github.com/camwiegert/in-view), que está oficialmente inativo.

Além das alternativas acima, há a opção de se utilizar o [Svelte](https://svelte.dev/). Neste caso, vale a pena conferir o [modelo (template) do The Pudding](https://github.com/the-pudding/svelte-starter), que conta com um componente específico para este tipo de visualização interativa, e o [tutorial escrito por Connor Rothschild](https://www.connorrothschild.com/post/svelte-scrollytelling) mostrando como implementar scrollytelling com o Svelte.



### Métodos de scrollytelling

Em seu artigo '[Responsive scrollytelling best practices](https://pudding.cool/process/responsive-scrollytelling/)', publicando no The Pudding, Russell Goldenberg destaca duas abordagens principais para uma narrativas com scrollytelling. Uma delas é simplesmente empilhar textos, imagens, cartografias ou gráficos diversos. A outra consiste na rolagem de elementos sobre um fundo, em geral uma visualização de dados ou um mapa. No artigo, Goldenberg cita ainda outras abordagens possíveis, como usar o clique ou a função de deslizar, mas não as recomenda.

A Documental é uma solução que permite trabalhar com estas duas abordagens. É possível inclusive mesclar ambas, alternando rolagem sobre um fundo (no caso, um mapa, [representado pelos `Mapas`](criando-uma-historia/biblioteca-de-blocos.md#mapa)) e seções com textos ou imagens fixas, empilhadas (como o elemento [`Duas Colunas`](criando-uma-historia/biblioteca-de-blocos.md#duas-colunas)).

#### Textos e narrativas

Em artigo sobre design cartográfico como uma forma de "storytelling" visual, Robert E. Roth recomenda que sejam selecionados elementos para garantir uma linearidade durante uma narrativa. Ele menciona a estrutura em três atos como a abordagem mais tradicional e também cita a tipologia proposta por Phillips (2012) com oitos arcos narrativos comumente utilizados nas geociências e geografia.

A narrativa clássica, em três atos, é baseada em 3 etapas: set-up ou introdução, conflito e resolução. Ao longo deste processo, são apresentados personagens (que podem ser pessoas, mas também regiões geográficas, por exemplo), informações contextuais sobre um problema e outras informações.

No início da narrativa, em geral, apresentam-se os personagens, ambientes e o contexto do problema em questão. Para scrollytelling baseados em mapas, é especialmente importante determinar uma ou mais localidades (onde?) e temporalidades (quando?). Também recomenda-se a inserção de uma "isca" (teaser ou click-bait) para capturar a atenção da pessoa leitora e gerar interesse na narrativa.

No segundo ato, o conflito, Roth enfatiza a criação incremental de uma tensão e o desenvolvimento dos personagens, a fim de gerar um maior interesse da audiência. Ele sugere a criação de "pontos narrativos", que podem ser pontos distintos em um mesmo mapa ou uma sequência de mapas e gráficos, para construir pausas e ritmos dentro de uma narrativa linear.

O pesquisador destaca os oito arcos narrativos identificadas por Philips (2012) para narrativas baseadas em mapas. Eles dividem-se em dois grupos. Quatro destes arcos são baseados em um único protagonista (um local ou região, onde o conflito surge de forças internas ou externas). Estes quatro arcos narrativos são: a destruição, a gênese, a emergência ou a metamorfose. Os outros quatros baseiam-se no conflito entre duas ou mais forças ou personagens, que pode resultar em uma nova situação. Estes outros quatro arcos são: causa e efeito, convergência, divergência e oscilação.

![Fonte: Reprodução da "Figura 1" do artigo 'Cartographic Design as Visual Storytelling: Synthesis and Review of Map-Based Narratives, Genres, and Tropes'](https://3665796612-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F5CzhNylOYIcqlWOt9qG1%2Fuploads%2Fgit-blob-a18fb086c0b130f7ed0a8a27ef715d235e62cc3d%2Fscrolly.png?alt=media)

Por fim, na resolução, o ato final da estrutura narrativa em três etapas, chega-se ao climax. Esta conclusão pode se dar tanto com a convergência dos personagens, problemas e ambientações criadas por uma determinada solução, quanto deixando a carga da audiência preencher as lacunas de sentido com suas próprias experiências.

Como Roth, destaca muitos profissionais consideram este esquema super-simplificado e adotam estruturas não-lineares ou paralelas para contar histórias. De todo modo, ainda assim, estes elementos e estruturas básicas podem estimular novas práticas e abordagens para contar histórias com mapas.

#### Definição da camada base

A camada base serve como a principal camada de localização espacial, a partir da qual serão posicionadas outras camadas de informações ou dados. Esta camada base pode ser uma imagem de satélite ou marcações vetoriais. No primeiro caso, temos um efeito mais realista, que visa transmistir a sensação de deslocamento em um espaço real. As imagens de satélite como a camada base de um mapa também permitem que objetos e entidades (prédios, marcas de desmatamento ou cidades, por exemplo) apareçam no mapa "tal como" são na realidade.

![Base com imagem de satélite](https://3665796612-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F5CzhNylOYIcqlWOt9qG1%2Fuploads%2Fgit-blob-7b3208e35be83c6a5576a2325dc3febea0a9b189%2Fsatelite.png?alt=media)

Por outro lado, um mapa base vetorial abstrai qualquer informação visual desnecessária para representar apenas alguns elementos. Deste modo, esta abordagem é muitas vezes utilizada para visualizações de dados geográficos, uma vez que com a camada vetorial podemos escolher o que será exibido (como fronteiras, nomes de rua, etc).

![Base com camada vetorial](https://3665796612-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F5CzhNylOYIcqlWOt9qG1%2Fuploads%2Fgit-blob-b15d2806e736ff86efecbf052d6f5b0601fef798%2Fvetor.png?alt=media)

#### Movimentos de câmera sobre mapas

**Aproximar ou afastar (Zoom in/out)**

O movimento de aproximar ou afastar a visão sobre o mapa ajuda as narrativas a alternarem entre uma dimensão "macro" (uma visão mais ampla para situar geograficamente o leitor ou um mapa cloroplético, por exemplo) e "micro" (pontos no mapa relacionados a fotos ou uma subdivisão fronteiriça como os municípios dentro de um estado). O movimento de "zoom in" pode ser uma estratégia para abordar algo mais específico depois de tratar questões mais gerais (dedução), enquanto o contrário "zoom out" permite generalizar (indução) ou contrapor uma experiência em específica com uma visão mais ampla. Este efeito é obtido criando dois blocos [Mapa](organizando-geodados-no-mapbox.md#criando-um-novo-mapa) onde o sucessor tem um valor de "_zoom_" diferente (maior ou menor para _zoom in_ ou _zoom out_, respectivamente) que o anterior.

**Panorâmica (panning)**

Este movimento permite "passear" por um mapa. É útil para detalhar trajetórias ou tratar de uma sequência de acontecimentos/localizações relevantes para a narrativa. Este movimento pode ser alcançado usando diferentes coordenadas geográficas para latitude e longitude em diferentes blocos Mapa.

**Bearing e pitching**

O [Mapbox oferece opções de controle de câmera ](organizando-geodados-no-mapbox.md#personalizando-um-mapa)que permitem também ajustar a rotação e posição do observador em relação ao mapa. Este recurso dá a impressão de uma navegação em 3 dimensões e é útil para buscar reproduzir uma determinada perspectiva/visão (como a de uma foto) no mapa, por exemplo.

**Sobreposição de imagens**

O Documental também dá suporte a comparações de imagens no estilo antes/depois. Este recurso é útil especialmente para mostrar transformações temporais em um dado território, permitindo ao visitante comparar facilmente duas imagens. Neste caso, os mapas devem ser salvos como imagens e enviados usando a opção [`Comparativo de Imagens`](criando-uma-historia/biblioteca-de-blocos.md#comparativo-de-imagens).
