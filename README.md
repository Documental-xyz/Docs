<span class="c20 c152">DOCUMENTAL</span>

<span class="c175 c126">Plataforma aberta de geohistórias</span>

<span class="c28 c238">Guia de instalação e uso</span>

<span class="c175 c192">Da criação da conta à publicação da sua
geohistória na internet.</span>

<span class="c43 c175">Documental </span>

<span class="c43 c175">Agência Autônoma · MediaLab UFRJ</span>

<span class="c43 c175">documental.xyz</span>

-----

<span class="c0"></span>

# <span class="c20 c95">Sumário</span>

<span class="c28">1. A Documental  
</span><span class="c0"> 1.1 O que você encontra neste guia  
1.2 Para quem esta documentação se destina  
1.3 Preciso pagar?  
1.4 Como creditar o projeto  
1.5 Glossário</span>

<span class="c28">2. Primeiro acesso  
</span><span class="c0"> 2.1 Instale o aplicativo  
2.2 Crie sua conta e seu repositório no GitHub  
2.3 Criando o seu ambiente de trabalho  
2.4 Trabalhando offline</span>

<span class="c28">3. Preparando o mapa no Mapbox  
</span><span class="c0"> 3.1 Boas práticas na organização dos dados  
3.2 Enviando seus dados para o Mapbox  
3.3 Criando um novo mapa  
3.4 Personalizando um mapa  
3.5 Conectando o mapa à Documental</span>

<span class="c28">4. Criando uma história  
</span><span class="c0"> 4.1 Criando a página  
4.2 Project \[Projeto\]  
4.3 Page Settings \[Configurações da Página\]  
4.4 Page Theme \[Tema da Página\]  
4.5 Page Include \[Inclusão de página\]  
4.6 Modules \[Módulos\]  
4.7 Components \[Componentes\]  
4.8 Biblioteca de blocos-filhos  
4.9 Recursos complementares</span>

<span class="c28">5. Publicando uma história  
</span><span class="c0"> 5.1 GitHub Pages  
5.2 Servidor próprio  
5.3 Site da Documental</span>

<span class="c28">6. Técnicas de scrollytelling  
</span><span class="c0"> 6.1 O que é scrollytelling?  
6.2 Métodos de scrollytelling  
6.3 Textos e narrativas  
6.4 Definição da camada base  
6.5 Movimentos de câmera sobre mapas  
6.6 Outras plataformas e bibliotecas</span>

<span class="c24 c1">7. Problemas comuns</span>

<span class="c24 c1">8. Como colaborar</span>

<span class="c24 c1">9. Referências e recursos</span>

<span class="c24 c1">10. Equipe</span>

<span class="c24 c1"></span>

-----

<span class="c0"></span>

# <span class="c20 c95">1. A Documental</span>

<span class="c1">[Documental](https://www.google.com/url?q=https://documental.xyz&sa=D&source=editors&ust=1786675075220360&usg=AOvVaw2zYlkF3HYfswNdC8jkGGPQ)</span><span class="c1"> é
uma ferramenta para a construção de narrativas visuais baseadas em
mapas, que faz uso de recursos de
</span><span class="c38 c1">scrollytelling</span><span class="c1"> (interações
a partir da rolagem de página) para conduzir o leitor pela
história.</span>

<span class="c1">A rolagem é o que move a narrativa inteira, e não
apenas o mapa. À medida que a pessoa avança pelo texto, o mapa se
desloca, aproxima, revela camadas e destaca lugares; mas também entram
vídeos, fotografias, imagens de satélite, gráficos, linhas do tempo e
depoimentos, cada elemento aparecendo no momento em que a narrativa
pede. O mapa é o fio condutor espacial; o restante do material é o que
dá densidade, prova e contexto ao que está sendo contado.</span>

<span class="c1">A plataforma opera a partir
</span><span>do</span><span class="c1"> aplicativo</span><span> da
Documental </span><span class="c1">(compatível com Linux, Windows e
macOS), que integra o sistema de publicação Sveltia, um
</span><span class="c38 c1">Content Management
System</span><span class="c1"> (CMS), ao serviço de mapas
online</span><span> </span><span class="c76">[Mapbox](https://www.google.com/url?q=https://www.mapbox.com/&sa=D&source=editors&ust=1786675075223701&usg=AOvVaw3H7KDFUlsvBaRi2k3fFOQ5)</span><span class="c1">.</span>

<span>O código da Documental fica armazenado no
</span><span class="c76">[GitHub](https://www.google.com/url?q=https://github.com/&sa=D&source=editors&ust=1786675075224248&usg=AOvVaw2CH22tFKJspSQWdEodRDsa)</span><span class="c0">,
plataforma que hospeda e versiona projetos de software. É de lá que os
arquivos da plataforma são copiados para um repositório seu – por isso,
para usar a Documental, você precisa ter uma conta e um repositório no
GitHub. É nesse repositório que a sua história fica salva, com o
registro de todas as alterações feitas ao longo do trabalho. </span>

<span>Depois de pronta, a página pode ser publicada de duas formas. A
primeira é pelo </span><span class="c76">[GitHub
Pages](https://www.google.com/url?q=https://docs.github.com/pt/pages/getting-started-with-github-pages/what-is-github-pages&sa=D&source=editors&ust=1786675075225892&usg=AOvVaw07fRyLAUWrQNGqVKTP7TFu)</span><span> (ver
</span><span class="c28">seção 5.1 Github
Pages</span><span>)</span><span class="c0">, serviço gratuito do próprio
GitHub que transforma os arquivos do seu repositório em um site
acessível na internet: você não contrata hospedagem, não configura
servidor e não paga nada. O endereço da sua história fica no formato
https://seu-usuario.github.io/nome-do-repositorio/, e depois é possível
trocá-lo por um domínio próprio. A segunda forma é hospedar a página em
um servidor da sua organização. </span>

<span>Há ainda uma terceira forma de publicar: em colaboração com a
Agência Autônoma, em nossos servidores. Nessa modalidade, fornecemos a
infraestrutura digital e o suporte técnico necessários para colocar a
história no ar. Ela é voltada principalmente a movimentos sociais,
</span><span>organizações</span><span> de base e agências cívicas. Se
você tem um projeto que gostaria de publicar conosco, escreva para
autonoma@autonoma.xyz.</span><sup>[\[a\]](#cmnt1)[\[b\]](#cmnt2)</sup>

<span>Em todos os</span><span class="c0"> casos, as páginas são
compatíveis com diferentes dispositivos, incluindo desktop, tablet e
mobile, mediante configuração. </span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 285.00px;">![](images/image42.png)</span>

<span class="c39 c38">Página inicial da geohistória
</span><span class="c117 c38">[Nhanderekoa](https://www.google.com/url?q=https://documental.xyz/nhanderekoa/&sa=D&source=editors&ust=1786675075229335&usg=AOvVaw1NnC3v-xqTAIvmAjNs9JDx)</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image44.png)</span>

<span class="c39 c38">Trecho de narrativa através de mapas da
geohistória
</span><span class="c38 c117">[Expulsions](https://www.google.com/url?q=https://documental.xyz/expulsions/&sa=D&source=editors&ust=1786675075230059&usg=AOvVaw0hVDprqb8ZPohT0M8qrhmR)</span>

## <span class="c24 c108"></span>

## <span class="c2">1.1 O que você encontra neste guia</span>

<span class="c0"> </span>

|                                                             |                                                                                                                                      |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| <span class="c32 c43 c28 c47">Capítulo</span>               | <span class="c32 c43 c28 c47">Conteúdo</span>                                                                                        |
| <span class="c24 c43">1. A Documental</span>                | <span class="c29">Introdução à plataforma e ao guia</span>                                                                           |
| <span class="c24 c43">2. Primeiro acesso</span>             | <span class="c29">Instalação do aplicativo, criação da conta e do repositório no GitHub, e montagem do ambiente de trabalho</span>   |
| <span class="c24 c43">3. Preparando o mapa no Mapbox</span> | <span class="c29">Organização e envio dos dados geográficos, criação e personalização do mapa, e sua conexão com a Documental</span> |
| <span class="c24 c43">4. Criando uma história</span>        | <span class="c29">Configuração da página, das vistas de mapa e montagem do conteúdo, com a biblioteca completa de blocos</span>      |
| <span class="c24 c43">5. Publicando uma história</span>     | <span class="c29">Publicação pelo GitHub Pages, por servidor próprio ou no site da Documental</span>                                 |
| <span class="c24 c43">6. Técnicas de scrollytelling</span>  | <span class="c29">Alternativas, tecnologias e estratégias para narrativas com scrollytelling baseadas em mapas</span>                |
| <span class="c24 c43">7. Problemas comuns</span>            | <span class="c29">Problemas frequentes e como resolvê-los</span>                                                                     |
| <span class="c24 c43">8. Como colaborar</span>              | <span class="c29">Informações para quem quiser contribuir com o projeto</span>                                                       |
| <span class="c24 c43">9. Referências e recursos</span>      | <span class="c29">Compilado de materiais externos úteis</span>                                                                       |
| <span class="c24 c43">10. Equipe</span>                     | <span class="c29">Pessoas e organizações envolvidas com a Documental</span>                                                          |

<span> </span>

## <span class="c2">1.2 Para quem esta documentação se destina</span>

<span class="c1">Qualquer pessoa interessada pode ler a documentação
sobre a ferramenta. Porém, para implementar uma instância da plataforma
"do zero" e publicar uma história usando os recursos da Documental, é
recomendável que uma ou mais pessoas tenham conhecimento técnico sobre
noções básicas de manipulação de dados geográficos.</span>

<span class="c1">A plataforma foi elaborada para atender à comunidade de
direitos humanos </span><span>–</span><span class="c1"> movimentos
sociais, organizações civis, agências jornalísticas e ONGs
</span><span>–</span><span class="c1">, não necessariamente
familiarizada com programação web.</span>

## <span class="c2">1.3 Preciso pagar?</span>

<span class="c1">A Documental é uma solução baseada em softwares de
código aberto. Para executar a plataforma localmente é necessário
instalar o aplicativo da Documental, que executa o Sveltia (CMS) no seu
computador, criar uma conta gratuita no GitHub e uma conta gratuita no
Mapbox. Para publicar uma página, você configura uma hospedagem gratuita
através do GitHub Pages, embora também possa contratar um
servidor.</span>

<span class="c1">O Mapbox adota um modelo
</span><span class="c38 c1">freemium</span><span class="c1">, em que é
possível usufruir de certas soluções com uma conta gratuita, mas é
preciso assinar um serviço pago para obter recursos mais avançados. Os
recursos gratuitos ou de código aberto são suficientes para configurar
uma instância da plataforma</span><span> e</span><span class="c1"> a
versão gratuita do Mapbox serve para a maioria dos casos.
P</span><span class="c0">ara criar uma conta, você vai precisar inserir
seus dados de cobrança – não se preocupe –, você só será cobrado caso
ultrapasse 50 mil acessos ao mapa. </span>

<span class="c0"></span>

<span class="c43 c28 c47">Características</span>

<span class="c43 c28 c47">Mapbox</span>

<span class="c43 c28">Plano gratuito</span>

<span class="c43">Até 50 mil visualizações do mapa por mês</span>

<span class="c43 c28">Valor do plano pago</span>

<span class="c43">A partir de 50 dólares por mês, ou sob demanda,
dependendo dos serviços utilizados e da quantidade de acessos</span>

<span class="c43 c28">Funcionalidades pagas</span>

<span class="c43">Mais camadas, mais visualizações de mapas, suporte,
entre outras</span>

<span class="c0"></span>

<span class="c1">Para mais informações sobre os recursos pagos, confira
a página do
</span><span class="c76">[Mapbox](https://www.google.com/url?q=https://www.mapbox.com/pricing&sa=D&source=editors&ust=1786675075250525&usg=AOvVaw1Mwn7RWygzI-WKYAZG4lmy)</span><span>,
e p</span><span>ara maiores informações sobre cobranças, acesse o
</span><span class="c76">[FAQ](https://www.google.com/url?q=https://docs.mapbox.com/accounts/faq/how-does-pay-as-you-go-billing-work/&sa=D&source=editors&ust=1786675075250985&usg=AOvVaw3wopsGNUDW5Hw8y0ondfuS)</span><span class="c0">.</span>

## <span class="c2">1.4 Como creditar o projeto</span>

<span class="c1">Solicitamos que projetos que façam uso da plataforma
incluam a seguinte menção, como forma de apoiar o desenvolvimento da
plataforma:</span>

<span class="c12">powered by Documental.xyz</span>

<span class="c0"></span>

## <span class="c24 c95">1.5 Glossário</span>

<span class="c0">Alguns termos aparecem ao longo de todo o guia. Vale
conhecê-los uma vez – você pode voltar a esta página sempre que
precisar.</span>

<span class="c0"> </span>

### <span class="c23">Código-fonte</span>

<span class="c0">O conjunto de arquivos que compõem um programa,
escritos em linguagem de programação. É a receita a partir da qual o
software funciona. Dizer que a Documental é de código aberto significa
que esses arquivos são públicos: qualquer pessoa pode lê-los, copiá-los,
modificá-los e redistribuí-los.</span>

### <span class="c124 c28">Repositório Template</span>

<span>Um repositório git com a estrutura mínima para você criar seu
próprio ambiente de trabalho Documental e armazenar e publicar seus
conteúdos.</span>

### <span class="c23">GitHub</span>

<span class="c0">Plataforma online onde ficam armazenados os códigos.
Funciona como um serviço de nuvem, com uma diferença importante: guarda
todas as versões de cada arquivo, registrando o que mudou, quando e por
quem. É onde o código da Documental está publicado e onde a sua história
fica salva.</span>

### <span class="c23">Repositório</span>

<span class="c0">A pasta de um projeto dentro do GitHub. Cada ambiente
de trabalho da Documental corresponde a um repositório seu. Ele pode ser
público, visível para qualquer pessoa, ou privado, restrito a você e a
quem você convidar.</span>

### <span class="c23">GitHub Pages</span>

<span class="c0">Serviço gratuito do GitHub que transforma os arquivos
de um repositório em um site acessível na internet. Você não contrata
hospedagem, não configura servidor e não paga nada: o GitHub monta a
página e a coloca no ar. O endereço segue o formato
https://seu-usuario.github.io/nome-do-repositorio/, e é possível
contratar um domínio próprio para utilizar no lugar.</span>

### <span class="c23">Ambiente de trabalho</span>

<span class="c0">A sua área de trabalho na Documental, criada em dois
lugares ao mesmo tempo: uma pasta no seu computador, onde você edita, e
um repositório no GitHub, onde tudo fica guardado e versionado. Dentro
de um mesmo ambiente é possível ter várias geohistórias.</span>

### <span class="c23">Aplicativo Documental</span>

<span>É a maneira mais simples de usar a plataforma Documental. Com o
aplicativo você pode criar sua conta GitHub, criar e gerenciar seus
repositórios e ambientes de trabalho e publicar seus conteúdos. Uma vez
criado seu ambiente de trabalho, o aplicativo permite que você possa
trabalhar sem internet.</span>

### <span class="c23">Mapbox</span>

<span class="c0">Serviço online de mapas utilizado pela Documental. É
onde você sobe os seus dados geográficos, monta as camadas e define o
estilo visual do mapa. A Documental se conecta a ele por meio de duas
informações: o estilo do mapa e um token de acesso.</span>

-----

<span class="c0"></span>

# <span class="c20 c95">2. Primeiro acesso</span>

<span>A Documental é baseada em uma filosofia de código aberto:
</span><span>seu funcionamento parte da cópia do template do projeto
para o seu repositório pessoal no GitHub</span><span class="c0">, e, a
partir dessa cópia, é possível modificar o conteúdo e a estrutura das
páginas, adaptando-as às necessidades de cada narrativa.</span>

<span class="c0">O GitHub consiste numa plataforma online que permite
armazenar, versionar e publicar códigos de forma colaborativa. Ao
carregar arquivos no GitHub, você os armazena num repositório Git, que
tem suas alterações monitoradas pela plataforma.</span>

<span>Você não precisa aprender a usar o GitHub para trabalhar com a
Documental. Quem conversa com ele é o aplicativo que você instala no seu
computador: é ele que cria a sua conta e o repositório, </span><span>faz
uma cópia do template da Documental</span><span>, cria um arquivo da
Documental no seu computador, registra cada alteração e faz upload
online da história quando você decide publicar. </span>

<span>E</span><span>xistem três caminhos para publicar uma história da
Documental: através do GitHub Pages, de um servidor próprio, ou no
servidor da agência autônoma em projetos de colaboração. Essas
informações estão detalhadas no capítulo 5,
</span><span class="c24 c1">Publicando uma história.</span>

<span class="c24 c1">As seções a seguir percorrem o caminho completo
dentro do aplicativo, da instalação à criação do seu primeiro
projeto.</span>

<span class="c0"></span>

|                                                                                                                                                                                                                                                                                                          |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c4">Em resumo, o caminho é este: </span><span class="c13">instalar o aplicativo → criar ou conectar sua conta do GitHub, pelo próprio aplicativo → criar o ambiente de trabalho, escolhendo o repositório e a pasta local → escrever a história → publicar.</span><span class="c0"> </span> |

<span class="c0"></span>

## <span class="c2">2.1 Instale o aplicativo</span>

<span class="c1">Para começar a usar a Documental, é necessário instalar
o aplicativo que executa o Sveltia em seu computador. O
</span><span class="c1">link para download</span><span class="c1"> está
disponível
</span><span class="c76 c1">[aqui](https://www.google.com/url?q=http://documental.xyz/download&sa=D&source=editors&ust=1786675075267363&usg=AOvVaw0pD5_cHi7R1r1Ba726vQBH)</span><span class="c1"> e
na </span><span class="c1">[página inicial da
Documental](https://www.google.com/url?q=https://documental.xyz/&sa=D&source=editors&ust=1786675075267667&usg=AOvVaw0ogDNh9N-vZhNdF2Fg4rCS)</span><span class="c0">.
Depois de fazer o download, execute o arquivo.</span>

### <span class="c124 c28">Observações por sistema operacional</span>

<span>O aplicativo não possui assinatura digital paga, o que faz com que
Windows e macOS exibam avisos de segurança na primeira execução. Não é
sinal de problema com o arquivo, é o comportamento padrão desses
sistemas para qualquer programa distribuído fora das lojas oficiais.
Veja abaixo como proceder em cada sistema – depois de autorizado uma
vez, o aplicativo abre normalmente.</span>

<span class="c0"></span>

<span class="c43 c28 c47">Sistema</span>

<span class="c43 c28 c47">O que pode aparecer</span>

<span class="c43 c28 c47">O que fazer</span>

<span class="c43 c28">Windows</span>

<span class="c43">Tela azul "O Windows protegeu o computador"</span>

<span class="c43">Clique em "Mais informações" e depois em "Executar
assim mesmo"</span>

<span class="c43 c28">macOS</span>

<span class="c43">Aviso de "desenvolvedor não identificado" ou de que o
app não pôde ser verificado</span>

<span class="c43">Tente abrir o aplicativo uma vez e feche o aviso.
Depois vá em </span><span class="c43 c28">Ajustes do Sistema ›
Privacidade e Segurança</span><span class="c43">, role até a seção
</span><span class="c43 c28">Segurança</span><span class="c43"> e clique
em </span><span class="c43 c28">"Abrir mesmo
assim"</span><span class="c29">. Em versões mais antigas do macOS,
também funciona clicar no aplicativo com o botão direito (ou Control +
clique) e escolher "Abrir"</span>

<span class="c43 c28">Linux</span>

<span class="c43">O arquivo AppImage não executa</span>

<span class="c43">No terminal, torne-o executável com chmod +x antes de
rodar</span>

<span class="c0"></span>

<span>Em seguida, s</span><span>iga os passos indicados pelo aplicativo.
Você vai precisar conectar a sua conta do GitHub e autorizar a
instalação de algumas dependências para que o aplicativo
funcione.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 320.00px;">![](images/image43.png)</span><sup>[\[c\]](#cmnt3)[\[d\]](#cmnt4)</sup>

<span class="c39 c38">Tela de abertura do aplicativo.</span>

<span class="c0"></span>

## <span class="c2">2.2 Crie sua conta e seu repositório no GitHub</span>

<span>Para construir uma geohistória, você precisa de uma conta e de um
repositório no GitHub. O repositório é a pasta do seu projeto dentro do
GitHub: é para lá que o </span><span>template</span><span> da Documental
é copiado, e é lá que a sua história fica guardada, com o histórico de
alterações. Isso vale mesmo que você opte depois por publicar as páginas
em outro serviço.</span>

<span>Ao abrir o aplicativo pela primeira vez, ele conduz você por toda
a configuração inicial: criar ou conectar a conta do GitHub, autorizar o
acesso e instalar as dependências necessárias para o funcionamento da
plataforma. </span><span>Basta seguir os passos indicados na
tela:</span><sup>[\[e\]](#cmnt5)[\[f\]](#cmnt6)</sup>

<span>Se você ainda não tem conta no GitHub, o próprio aplicativo abre o
cadastro – é gratuito e leva poucos minutos, exigindo apenas um e-mail e
uma senha. Se já tem, é só conectá-la neste mesmo passo.  
</span>

|                                                                                                                                                                                                                                                                                                                                                                                    |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c4 c38">Sobre segurança: </span><span class="c32 c90 c13 c36">a credencial de acesso é guardada no cofre de senhas do seu sistema operacional – Chaveiro no macOS, Gerenciador de Credenciais no Windows, keyring no Linux –, nunca em arquivo de texto aberto. Você pode revogar o acesso a qualquer momento em github.com, na seção Settings › Applications.</span> |

<span class="c30 c1 c36 c90"></span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><span class="c4 c38">Após logar com sua conta pela primeira vez: </span><span class="c13">quando você entrar de novo no aplicativo, você não precisará mais logar novamente. Mas, caso queira acessar o aplicativo com outra conta Github, fecha o aplicativo, e, com ele fechado,  remova a </span><span class="c28 c13">pasta de configuração</span><span class="c32 c90 c13 c36">. Em cada sistema operacional há um caminho diferente. Veja abaixo:</span></p>
<p><span class="c32 c90 c13 c36"></span></p>
<p><span class="c28 c13">MacOS</span><span class="c13"><br />
~/Library/Application Support/Documental<br />
<br />
</span><span class="c38 c13">OBS:</span><span class="c90 c38 c13 c196"> </span><span class="c13">~/Library</span><span class="c38 c13"> é uma pasta oculta no Finder.  Para acessá-la, pressione </span><span class="c28 c38 c13">⌘ + Shift + G</span><span class="c30 c90 c13 c36"> e digite: ~/Library/Application Support/</span></p>
<p><span class="c32 c90 c13 c36"></span></p>
<p><span class="c24 c13">Windows</span></p>
<p><span class="c13">C:\\Usuários\&lt;seu_usuário&gt;\AppData\Roaming\Documental<br />
<br />
</span><span class="c38 c13">OBS: AppData é uma pasta oculta no explorer. Para acessá-la:<br />
</span><span class="c28 c38 c13">Windows 11:</span><span class="c38 c13"> </span><span class="c28 c38 c13">Exibir → Mostrar → Itens ocultos</span><span class="c30 c90 c13 c36">.</span></p>
<p><span class="c28 c38 c13">Windows 10:</span><span class="c38 c13"> guia </span><span class="c28 c13 c38">Exibir</span><span class="c38 c13"> → marque </span><span class="c28 c38 c13">Itens ocultos</span><span class="c30 c90 c13 c36">.</span></p>
<p><span class="c13"><br />
</span><span class="c28 c13">LINUX</span><span class="c32 c90 c13 c36"><br />
- ~/.config/Documental</span></p>
<p><span class="c38 c13"><br />
OBS: .config é uma pasta oculta no Linux por padrão. Na maioria dos gerenciadores de arquivo basta pressionar </span><span class="c28 c38 c13">CRTL+h</span><span class="c30 c90 c13 c36"> para visualizar ou ocultar</span></p></td>
</tr>
</tbody>
</table>

## <span class="c24 c108"></span>

## <span class="c2">2.3 Criando o </span><span class="c28 c36">seu ambiente de trabalho</span>

<span class="c0">Depois de concluir a configuração inicial, você acessa
a página de edição da Documental, com três caminhos possíveis: Criar
Novo Ambiente de Trabalho; Abrir Pasta e Abrir Recente:</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 362.67px;">![](images/image24.png)</span>

<span class="c39 c38">Tela de criação de novo ambiente de trabalho no
aplicativo</span><sup>[\[g\]](#cmnt7)</sup>

<span class="c16"></span>

<span>Como este é o seu primeiro acesso, clique em
</span><span class="c28">Criar Novo Projeto</span><span class="c0"> – é
por aí que se cria o seu ambiente de trabalho.</span>

<span class="c0"></span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><span class="c32 c4">O que é o ambiente de trabalho</span></p>
<p><span class="c13">O ambiente de trabalho é a sua pasta de trabalho na Documental.</span><span class="c13"> Ele é criado em dois lugares ao mesmo tempo: numa pasta do seu computador e dentro do seu repositório no GitHub, onde tudo fica guardado e versionado. São as duas faces da mesma coisa, e o aplicativo mantém as duas em sincronia.</span></p>
<p><span class="c32 c90 c13 c36">Dentro de um mesmo ambiente você pode ter várias geohistórias – não é preciso criar um ambiente novo a cada história.</span></p>
<p><span class="c13">Ao criar o ambiente, o</span><span class="c13"> aplicativo faz uma cópia do template da Documental para o seu repositório. </span><span class="c13">É essa cópia que traz a estrutura pronta da plataforma, que você vai preencher com o seu conteúdo.</span></p></td>
</tr>
</tbody>
</table>

<span class="c0"></span>

### <span class="c23">Escolhendo o repositório</span>

<span class="c0">O aplicativo pede que você indique o repositório do
GitHub onde a documentação será salva e publicada.</span>

<span class="c0"></span>

<span class="c0"></span>

<span class="c0"></span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 364.00px;">![](images/image25.png)</span><sup>[\[h\]](#cmnt8)[\[i\]](#cmnt9)</sup>

<span class="c16">Tela de escolha do repositório, com os filtros de
busca e a opção de criar uma cópia do template da Documental.</span>

<span class="c0"></span>

<span class="c0">A tela lista os repositórios da sua conta do GitHub e
traz três filtros:</span>

|                                             |                                                                                                                                               |
| ------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c32 c43 c28 c47">Filtro</span> | <span class="c32 c43 c28 c47">O que faz</span>                                                                                                |
| <span class="c24 c43">Documental</span>     | <span class="c29">Mostra apenas repositórios da Documental. Deixe ligado se você já tem um ambiente criado e quer encontrá-lo na lista</span> |
| <span class="c24 c43">Privado</span>        | <span class="c29">Inclui na busca os repositórios privados</span>                                                                             |
| <span class="c24 c43">Pessoais</span>       | <span class="c29">Restringe a busca aos repositórios da sua conta pessoal</span>                                                              |

<span class="c0"></span>

<span>No primeiro acesso, nenhum repositório aparece – é esperado, você
ainda não tem nenhum. Use o botão </span><span class="c28">Criar
novo</span><span>.</span><span> </span>

<span>Com o repositório selecionado, clique em
</span><span class="c28">Continuar</span><span class="c0">. Em seguida,
o aplicativo pede o nome do ambiente e a pasta do seu computador onde os
arquivos ficarão.</span>

<span class="c23"></span>

### <span class="c32 c20 c244">Definindo os detalhes do ambiente</span>

<span>O aplicativo abre a tela </span><span class="c28">Criar Novo
Ambiente de Trabalho,</span><span class="c0"> onde você define como e
onde o ambiente será criado.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 365.33px;">![](images/image60.png)</span><sup>[\[j\]](#cmnt10)[\[k\]](#cmnt11)</sup>

<span class="c16">Tela de criação do ambiente de trabalho.</span>

<span class="c0"></span>

|                                                                                |                                                                                                                                                   |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c32 c43 c28 c47">Campo</span>                                     | <span class="c32 c43 c28 c47">O que informar</span>                                                                                               |
| <span class="c24 c43">Nome do Ambiente</span>                                  | <span class="c29">O nome do seu ambiente de trabalho. Logo abaixo do campo, o aplicativo mostra como a pasta será criada </span>                  |
| <span class="c24 c43">URL do repositório do GitHub</span>                      | <span class="c29">O endereço do repositório que você selecionou ou criou no passo anterior. O campo já vem preenchido automaticamente</span>      |
| <span class="c24 c43">Pasta onde o novo ambiente de trabalho será salvo</span> | <span class="c29">A pasta do seu computador onde os arquivos ficarão. Use o botão select para escolher</span>                                     |
| <span class="c24 c43">Destino do novo repositório</span>                       | <span class="c29">Onde a cópia do repositório da Documental será criada: na sua conta pessoal ou em uma organização da qual você participa</span> |

<span class="c0"> </span>

|                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <span class="c4">Escolha bem a pasta local: </span><span class="c32 c90 c13 c36">é nela que sua história estará armazenada enquanto você trabalha. Vale incluí-la nos seus backups e evitar pastas sincronizadas automaticamente por outros serviços de nuvem, como Dropbox ou Google Drive, que podem entrar em conflito com o controle de versões do Git.</span> |

<span class="c0"></span>

<span class="c0"></span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><span class="c4">A escolha do seu repositório: </span><span>v</span><span>ale a pena consultar mais informações sobre </span><span class="c76"><a href="https://www.google.com/url?q=https://docs.github.com/pt/repositories/creating-and-managing-repositories/about-repositories%23about-repository-ownership&amp;sa=D&amp;source=editors&amp;ust=1786675075310994&amp;usg=AOvVaw3kduBpeVKMrHh10db9iUi5" class="c49">onde criar o seu repositório no GitHub</a></span><span>. Ele pode ser vinculado diretamente à sua conta pessoal, pode ser criado dentro de uma organização, ou ser organizado dentro de subpastas. Essa escolha é importante para organizar suas geohistórias na plataforma, e também pode influenciar no endereço do site, caso você opte por publicá-las por meio do GitHub Pages.</span></p>
<p><span class="c32 c90 c13 c36"></span></p></td>
</tr>
</tbody>
</table>

<span class="c0"></span>

<span class="c0">Abaixo dos campos há duas chaves de
configuração:</span>

|                                                  |                                                                                                                                                                                                                        |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c32 c43 c28 c47">Opção</span>       | <span class="c32 c43 c28 c47">O que faz</span>                                                                                                                                                                         |
| <span class="c24 c43">Repositório Privado</span> | <span class="c29">Deixa o repositório fechado, visível apenas para você e para quem você convidar</span>                                                                                                               |
| <span class="c24 c43">Ativar GitHub Pages</span> | <span class="c29">Deixa a publicação do site já configurada. Com a chave ligada, o GitHub monta e coloca a página no ar sozinho a cada publicação, sem que você precise mexer nas configurações do repositório.</span> |

<span class="c0"> </span>

<span class="c28">Sobre a chave Ativar GitHub
Pages:</span><span class="c0"> o GitHub Pages é o serviço gratuito que
transforma os arquivos do seu repositório em um site acessível na
internet. Com a chave ligada, o aplicativo já deixa tudo preparado, e a
cada vez que você publicar o GitHub monta o site sozinho e o coloca no
ar. É o mesmo resultado do passo a passo descrito no capítulo 5, feito
automaticamente para você.</span>

<span>Desligar a chave não impede nada do seu trabalho – o ambiente
funciona igual e você escreve normalmente. O que muda é que o site não
vai ao ar até que você configure a publicação à mão, ou opte por
hospedar a história em servidor próprio. Na dúvida, deixe ligada: é
sempre possível desativar depois.</span>

<span class="c0"> </span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><span class="c4">Atenção ao combinar as duas: </span><span class="c13">em contas gratuitas do GitHub, repositórios privados não podem ser publicados pelo GitHub Pages. No plano gratuito, portanto, publicar significa necessariamente deixar os arquivos da história visíveis.</span></p>
<p><span class="c4">O que "repositório público" significa na prática:</span><span class="c32 c90 c13 c36"> não se trata apenas de alguém digitar o endereço certo. Repositórios públicos aparecem na busca do GitHub e são indexados por buscadores; o histórico completo de alterações fica visível, inclusive trechos e arquivos que você tenha apagado depois; e, como o ambiente é criado a partir de um template, ele aparece na lista pública de cópias do repositório da Documental.</span></p>
<p><span class="c13">Nada disso impede o trabalho – a maioria das geohistórias é feita justamente para circular. Mas se houver material sensível antes da publicação, como nomes de fontes, localizações precisas ou documentos ainda não verificados, vale considerar um plano pago do GitHub, hospedagem em servidor próprio, ou simplesmente manter esse material fora do repositório até a hora de publicar.</span></p></td>
</tr>
</tbody>
</table>

<span class="c0"> </span>

<span>Por fim, clique em </span><span class="c28">Criar
Ambiente</span><span class="c0">. A primeira criação leva alguns
minutos: é quando o aplicativo faz a cópia do template da Documental
para seu repositório, ou seja, copia automaticamente os arquivos para a
sua pasta e prepara o ambiente de edição.</span>

### <span class="c23">Voltando ao aplicativo depois</span>

<span class="c0">Criado o ambiente, os outros dois caminhos da página
inicial passam a fazer sentido:</span>

|                                              |                                                                                                                       |
| -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| <span class="c32 c43 c28 c47">Caminho</span> | <span class="c32 c43 c28 c47">Quando usar</span>                                                                      |
| <span class="c24 c43">Abrir Pasta</span>     | <span class="c29">O ambiente já está no seu computador e você quer localizá-lo manualmente, escolhendo a pasta</span> |
| <span class="c24 c43">Abrir Recente</span>   | <span class="c29">Você quer voltar rapidamente a um ambiente em que já estava trabalhando</span>                      |

<span class="c0"> </span>

<span>Abaixo dos três cartões fica a lista
</span><span class="c28">Ambientes Recentes</span><span class="c0">, com
os três ambientes mais recentes. Cada item mostra o nome, o repositório
do GitHub ao qual está ligado e o caminho da pasta no seu computador. O
“X” à direita apenas remove o item da lista — não apaga nada, nem na
sua máquina nem no GitHub.</span>

<span>Você também usa </span><span class="c28">Criar Novo Ambiente
</span><span>quando quiser montar um ambiente para um repositório que já
existe, ao trocar de computador, por
exemplo.</span><span class="c0"> Nesse caso, em vez de criar um novo
template, basta selecionar o repositório na lista — deixando o filtro
Documental ligado para encontrá-lo mais facilmente. </span>

<span>Para os próximos passos sobre como criar uma história, veja
a</span><span class="c24 c1"> seção 4. Criando uma história.</span>

<span class="c0"></span>

<span class="c2">2.4 Trabalhando offline</span>

<span class="c1">Depois que o </span><span>ambiente de
trabalho</span><span class="c1"> é criado, você não precisa mais de
internet para escrever. Tudo o que você faz
</span><span>–</span><span class="c1"> texto, imagens, ajustes de mapa
</span><span>– </span><span class="c1">é gravado nos arquivos da pasta
local do seu computador.</span><span class="c1"> A conexão volta a ser
necessária em </span><span>dois</span><span class="c1"> momentos:</span>

  - <span class="c0">Para </span><span>fazer upload ou modificações nos
    mapas</span><span class="c0">,</span><span> acessando o site do
    Mapbox</span><span>;</span>
  - <span class="c0">Na hora de publicar.</span>

<span class="c0">Isso torna a plataforma viável em situações de campo,
conexão instável ou trabalho em territórios com pouca infraestrutura:
você produz a história onde estiver e publica quando encontrar
rede.</span>

<span class="c0"></span>

<span class="c0"></span>

-----

<span class="c0"></span>

# <span class="c20 c95">3. Preparando o mapa no Mapbox</span>

<span class="c1">O </span><span class="c28 c1">Mapbox
Studio</span><span class="c1"> consiste numa plataforma em que você fará
o upload dos dados geográficos </span><span>com os
quais</span><span class="c1"> quiser trabalhar. Ele funciona como um
"Photoshop para mapas", segundo o site oficial da empresa. Existe,
então, um fluxo de trabalho de criar os dados, organizar os dados, e
depois exportá-los para a plataforma.</span>

<span class="c1">Atualmente, o Mapbox Studio aceita o
formato</span><span class="c28 c1"> </span><span class="c1">GeoTIFF para
arquivos em malha (raster) e diversos outros para dados vetoriais
(MBTiles, KML, GPX, GeoJSON, Shapefile zipado ou tabelas CSV). Você pode
usar uma solução online e de código aberto como o
</span><span class="c1">[QGIS](https://www.google.com/url?q=https://qgis.org&sa=D&source=editors&ust=1786675075331630&usg=AOvVaw0mjtDvxgHvr2HjnkDabtLc)</span><span class="c1"> ou
o
</span><span class="c1">[Mapshaper](https://www.google.com/url?q=https://mapshaper.org/&sa=D&source=editors&ust=1786675075331955&usg=AOvVaw2HLKy5ohiQDveTREYEQTw6)</span><span class="c1"> para
criar os seus </span><span>geodado</span><span class="c0">s ou para
fazer conversão de formatos.</span>

<span class="c1">Você também pode criar os seus dados diretamente dentro
do Mapbox, através da criação de um Dataset
</span><span>–</span><span class="c1"> porém softwares como o QGIS são
mais completos em termos de ferramentas para a criação e edição desses
dados.</span>

## <span class="c24 c108">3.1 Boas práticas na organização dos dados</span>

<span class="c0">Antes de enviar qualquer coisa para o Mapbox, vale
organizar os dados. Algumas decisões tomadas nesta etapa evitam bastante
retrabalho depois.</span>

<span>O Mapbox guarda os dados geográficos
em</span><span>[ ](https://www.google.com/url?q=https://docs.mapbox.com/console-tools/data-workbench/&sa=D&source=editors&ust=1786675075334150&usg=AOvVaw0bIR9Qga5uaQf7LphPCA4j)</span><span class="c134">[Data
Workbench](https://www.google.com/url?q=https://docs.mapbox.com/console-tools/data-workbench/&sa=D&source=editors&ust=1786675075334417&usg=AOvVaw1VAeFAXBKjhAGJapqHphs7)</span><span>,
e os intitula de
</span><span class="c76">[tilesets](https://www.google.com/url?q=https://docs.mapbox.com/help/glossary/tileset/&sa=D&source=editors&ust=1786675075334704&usg=AOvVaw1F1SLEowbXe-W0uETGsfQe)</span><span class="c0">.
Um tileset é um conjunto de dados recortado em pequenos quadrados em
vários níveis de zoom, de modo que o mapa carregue apenas os pedaços da
área visível – o que o deixa rápido no navegador e no celular.</span>

<span class="c0">Duas restrições do Mapbox orientam a forma de organizar
o material:</span>

<span>•</span><span class="c77">    </span><span class="c0">A versão
gratuita permite o upload de 15 tilesets por mapa. Isso não significa
apenas 15 dados: um tileset é uma coleção e pode reunir mais de um
geodado.</span>

<span>•</span><span class="c77">    </span><span class="c0">Cada tileset
aceita um único tipo de geometria. Na prática, isso significa separar o
material em tilesets distintos – um com polígonos, outro só com pontos,
outro só com linhas.</span>

<span class="c0">Duas boas práticas ajudam bastante daqui em
diante:</span>

<span>•</span><span class="c77">    </span><span class="c0">Verifique se
todos os dados geográficos estão numa mesma projeção geográfica.</span>

<span>•</span><span class="c77">    </span><span class="c0">Adote um
padrão consistente para nomear os arquivos. Isso facilita a manipulação
quando há muitos dados de uma vez só. Inclusive, considere utilizar a
nomenclatura para diferenciar os tilesets por projeto, pois os tilesets
de todos os seus projetos do Mapbox estarão juntos na mesma
pasta.</span>

<span class="c0"></span>

## <span class="c24 c108">3.2 Enviando seus dados para o Mapbox</span>

<span>Com os dados organizados, crie uma conta gratuita
no</span><span>[ ](https://www.google.com/url?q=https://www.mapbox.com/&sa=D&source=editors&ust=1786675075338640&usg=AOvVaw3ChICFTsh4un_xQGAKt9MS)</span><span class="c134">[Mapbox](https://www.google.com/url?q=https://www.mapbox.com/&sa=D&source=editors&ust=1786675075338822&usg=AOvVaw0CNPV5mMmTcxXhmPTLO2KA)</span><span class="c0"> e
faça o upload deles.</span>

<span>No Mapbox Studio, abra a aba </span><span class="c28">Data
Workbench</span><span> e clique no botão
</span><span class="c28">Upload</span><span class="c0"> – uma janela se
abre para você selecionar o arquivo no seu computador. O Mapbox processa
o arquivo e, ao terminar, ele passa a aparecer na sua lista de dados,
pronto para ser usado nos mapas.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 288.00px;">![](images/image38.png)</span>

<span class="c39 c38">Aba de Data Workbench do Mapbox.
</span><span class="c39 c28 c38">Upload</span><span class="c16"> é o
botão em que você realiza o upload de arquivos.</span>

<span class="c16"></span>

## <span class="c2">3.</span><span class="c28 c36">3</span><span class="c2"> Criando um novo mapa</span>

<span>Com os dados organizados e enviados, o próximo passo é montar o
mapa. Ele começa pelo estilo do mapa base – a camada que, em geral, fica
abaixo das demais e serve de referência visual. No Mapbox Studio, você
pode criar um estilo novo pelo botão azul </span><span class="c28">New
style</span><span> ou duplicar um estilo já existente.  
</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 288.00px;">![](images/image23.png)</span>

<span class="c39 c38">Criação de um novo estilo de mapa no Mapbox
Studio.</span>

### <span class="c23">Três caminhos para o estilo base</span>

<span class="c0">Você tem três opções. A ordem abaixo vai da mais
simples à mais trabalhosa – e a última traz uma limitação
importante.</span>

#### <span class="c20 c176">1. Copiar um dos estilos da agência autônoma (recomendado)</span>

<span>A agência autônoma possui dois estilos públicos,</span><span> já
configurados para funcionar bem com a Documental: o
</span><span class="c28">Monochrome Style</span><span> e o
</span><span class="c28">Dark Style</span><span class="c0">. Você copia
um deles para a sua conta e monta o seu mapa por cima, adicionando as
suas camadas de dados ao estilo já pronto – sem começar do zero e sem
abrir mão de nenhum recurso da plataforma. É o caminho mais rápido para
quem está começando.</span>

|                                             |                                                                                                                                                                                                                                                                                               |
| ------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c32 c43 c28 c47">Estilo</span> | <span class="c32 c43 c28 c47">URL</span>                                                                                                                                                                                                                                                      |
| <span class="c29">Monochrome Style</span>   | <span class="c43">https://api.mapbox.com/styles/v1/studio-autonoma/cmdgcs27u019101sa29ytbsps.html?title=copy\&access\_token=pk.eyJ1Ijoic3R1ZGlvLWF1dG9ub21hIiwiYSI6ImNtY3V2d3dtMTA0ZXgycnB4OW01cjlqb2QifQ.3NMaRt1maLlqTv6nlVqVHA\&zoomwheel=true\&fresh=true\#9/37.78/-122.4241</span>        |
| <span class="c29">Dark Style</span>         | <span class="c43">https://api.mapbox.com/styles/v1/studio-autonoma/cmdgcp72i003701qw07pk8bo3.html?title=copy\&access\_token=pk.eyJ1Ijoic3R1ZGlvLWF1dG9ub21hIiwiYSI6ImNtY3V2d3dtMTA0ZXgycnB4OW01cjlqb2QifQ.3NMaRt1maLlqTv6nlVqVHA\&zoomwheel=true\&fresh=true\#13.11/-3.57334/-78.46903</span> |

<span>   
Consulte
a</span><span>[ ](https://www.google.com/url?q=https://docs.mapbox.com/help/dive-deeper/transfer-styles-between-accounts/&sa=D&source=editors&ust=1786675075349837&usg=AOvVaw1A8cc_xPjrtmJLDYpAZ1mC)</span><span class="c134">[documentação
do Mapbox sobre como copiar um estilo de outra conta para a
sua](https://www.google.com/url?q=https://docs.mapbox.com/help/dive-deeper/transfer-styles-between-accounts/&sa=D&source=editors&ust=1786675075350397&usg=AOvVaw15UehisdsLbj7ysr_kRaZA)</span><span class="c0">.  
</span>

#### <span class="c32 c20 c1">2. Criar do zero (Start from scratch)</span>

<span class="c0">Você monta o mapa camada por camada, escolhendo o que
aparece e como aparece. Obtém controle total sobre o resultado e mantém
todos os recursos da Documental funcionando, mas exige mais tempo e
alguma familiaridade com o Mapbox Studio.</span>

#### <span class="c32 c20 c1">3. Mapbox Standard</span>

<span>É o estilo pronto da própria Mapbox e vem com outros elementos não
disponíveis no estilo da </span><span>autônoma</span><span class="c0">,
como edifícios em três dimensões, relevo e variações de iluminação. É
uma opção rápida para ter um mapa bonito sem configurar nada.</span>

<span>A contrapartida é que as camadas do Standard vêm empacotadas pela
Mapbox e não podem ser manipuladas uma a uma, então, não é possível
editar as camadas que constituem o mapa Standard do Mapbox, como é
possível editar através do mapa básico disponibilizado
pela</span><span> autônoma</span><span class="c0">, ou desenvolvido do
zero. Além disso, o uso do Mapbox Standard compromete algumas
funcionalidades de produção de mapas da Documental, como a filtragem de
layers. Se os seus mapas forem mais complexos e você quiser fazer uso de
atributos para definir qual camada aparecerá no seu mapa naquele
momento, essa funcionalidade da Documental estará comprometida. É uma
limitação do próprio Mapbox, não da Documental.</span>

<span class="c0">Vale a pena considerar essa opção se a sua narrativa é
composta de estruturas de camadas mais simples, e não depende da
filtragem de camadas através dos seus atributos.</span>

<span class="c0"> </span>

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c4">O que são filtros: </span><span class="c32 c90 c13 c36">um geodado não é apenas um desenho – cada elemento dentro dele, cada ponto ou polígono, carrega atributos, como nome, ano, área ou categoria. Filtrar é usar esses atributos para escolher o que aparece: de um tileset com todos os municípios do país, exibir apenas os de um estado; de uma camada com registros de vários anos, mostrar só os de 2024. Os atributos vêm dos próprios dados e podem ser criados e editados no QGIS antes do envio ao Mapbox.</span> |

<span> </span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 283.00px;">![](images/image56.png)</span>

<span class="c39 c38">Opções para criar um estilo novo: Mapbox Standard,
criar um estilo do zero (Start from scratch) e fazer o upload de um
estilo existente em JSON (Upload).</span>

## <span class="c2">3.</span><span class="c28 c36">4</span><span class="c2"> Personalizando um mapa</span>

<span>Com o estilo base escolhido, é hora de trazer os seus dados para o
mapa. Eles já estão na sua conta do Mapbox, enviados como tilesets na
etapa 3.2 – mas guardar um dado e exibi-lo em um mapa são coisas
distintas. O tileset é o arquivo armazenado na sua conta; a camada
(</span><span class="c38">layer</span><span>) é a decisão de mostrar
aquele arquivo
</span><span class="c28">neste</span><span class="c0"> mapa, com
determinada cor, espessura e ordem de sobreposição. Um mesmo tileset
pode virar camada em vários mapas diferentes, com aparências distintas
em cada um.</span>

<span>O editor do Mapbox Studio se divide em três áreas, como se pode
ver na imagem abaixo. À esquerda fica a lista de camadas: cada linha é
um conjunto de dados desenhado sobre o mapa, e a ordem da lista define o
que aparece por cima do quê. No centro fica o mapa em si, que mostra o
resultado em tempo real, à medida que você edita. Na barra cinza
inferior ficam as informações de enquadramento – o nível de zoom e as
coordenadas do centro da vista.</span>

<span>Essa barra inferior merece atenção especial, porque é dela que
saem os valores que você vai informar na Documental. Sempre que quiser
reproduzir um enquadramento na sua narrativa, posicione o mapa como
deseja aqui no Studio e anote o zoom, a latitude e a longitude que
aparecem ali.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image52.png)</span>

<span class="c39 c38">Interface do Mapbox Studio: camadas à esquerda,
zoom e coordenadas na barra inferior.</span>

<span>Para exibir um novo dado no mapa, clique no ícone
</span><span class="c28">+</span><span> acima da lista de camadas. Uma
nova camada é criada, e você escolhe qual tileset ela vai mostrar
em</span><span> </span><span class="c28">Source</span><span>, no campo
</span><span class="c28">Select data</span><span>.</span>

<span>Você pode aplicar um filtro ao selecionar o dado. </span><span>O
filtro pode ser aplicado sobre os atributos associados ao geodado –
atributos que você pode inserir e manipular dentro do QGIS, por exemplo.
</span><span class="c0">A ferramenta de filtragem do Mapbox é útil para
individualizar elementos em camadas, tendo em vista que você tem um
limite de upload de 15 tilesets. Mas cuidado para não abusar: o Mapbox
não funciona bem com muitas camadas.</span>

<span>Vale lembrar que, além desse mecanismo de filtro do Mapbox, você
também consegue fazer filtros em layers dentro da Documental. Ambos os
mecanismos são úteis para narrativas complexas com muitos dados. É
importante mencionar que o mecanismo de filtragem, dentro do Mapbox e
dentro da Documental, não irá funcionar caso seu mapa base for do tipo
Mapbox Standard, como já foi explicado na </span><span class="c28">seção
3.3 Criando um novo mapa</span><span class="c0">.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image54.png)</span>

<span class="c39 c38">Seleção do geodado em Source, dentro do campo
Select data.</span>

<span class="c1">Depois de escolher o geodado, você passa para a aba
</span><span class="c28 c1">Style</span><span class="c1"> e configura o
estilo de sua preferência para a camada. Confira a
</span><span class="c76 c1">[documentação](https://www.google.com/url?q=https://docs.mapbox.com/studio-manual/reference/styles/&sa=D&source=editors&ust=1786675075366645&usg=AOvVaw1mc7JGR-0jnLV6iLeb1tFT)</span><span class="c1">[ do
Mapbox](https://www.google.com/url?q=https://docs.mapbox.com/studio-manual/reference/styles/&sa=D&source=editors&ust=1786675075366921&usg=AOvVaw3NrEj7Coc2pvfiJC0YCDjX)</span><span class="c1"> para
mais orientações sobre esta etapa.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image57.png)</span>

<span class="c39 c38">Configuração de estilo da camada.</span>

## <span class="c2">3.</span><span class="c28 c36">5</span><span class="c2"> </span><span class="c28 c36">Conectando o mapa à Documental</span>

<span>Quando o mapa estiver pronto no Mapbox, falta somente dizer à
Documental onde encontrá-lo, e </span><span>isso é feito com duas
informações</span><span> que</span><span> você vai copiar e colar na
página de edição da sua geohistória da Documental, no item
</span><span class="c28">Mapbox</span><span> (ver
</span><span class="c28">seção 4.6 Modules</span><span>).</span>

<span class="c0"></span>

<span class="c43 c28 c47">Informação</span>

<span class="c43 c28 c47">O que é e exemplo</span>

<span class="c43 c28">Mapbox Style</span>

<span class="c43">Um caminho do estilo criado no sistema do
Mapbox.</span>

<span class="c12">mapbox://styles/usuaria/ckcb6q2pe2b3149s11kk9zr9u</span>

<span class="c43 c28">Mapbox Access Token</span>

<span class="c43">Uma longa sequência aleatória de caracteres, que serve
como senha para acessar seus dados no Mapbox.</span>

<span class="c12">pk.eyJ1IjoibWFybUXQjwiwiYS31IjlmYlhtaEkif2.vMxORYorRKnueDl3c5idQQ</span>

<span class="c0"></span>

<span>São necessárias as duas porque cada uma responde a uma pergunta
diferente: o style diz </span><span class="c28">qual</span><span> mapa
carregar, e o token diz </span><span class="c28">de
quem</span><span class="c0"> ele é. É pelo token que o Mapbox
contabiliza as visualizações na sua conta – as tais 50 mil mensais do
plano gratuito. Se qualquer uma das duas faltar ou estiver errada, o
mapa aparece em branco na página publicada.</span>

### <span class="c23">Onde encontrar as duas</span>

<span>Clique no botão </span><span class="c28">Share</span><span>, no
canto superior direito do editor do Mapbox Studio. Um quadro se abre, e
ambas as informações estão na seção </span><span class="c28">Developer
resources</span><span class="c0">.</span>

<span class="c0"> </span>

|                                                                                                                                                                                                                                                                                                                                                                                                           |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c4">Sobre o token: </span><span class="c32 c90 c13 c36">o token que começa com pk. é público, e é feito justamente para ficar visível no código do site – não é uma senha, apesar de parecer uma. O Mapbox também permite criar tokens secretos, que começam com sk. e dão acesso de escrita à sua conta. Esses nunca devem ser usados na Documental, nem publicados em lugar nenhum.</span> |

<span class="c0"></span>

<span class="c0"> </span>

<span class="c0"></span>

<span class="c0"></span>

-----

<span class="c0"></span>

# <span class="c20 c95">4. Criando uma história</span>

<span>Depois de ter criado o ambiente de trabalho (conforme a
</span><span class="c28">seção</span><span> </span><span class="c28">2.
Primeiro acesso</span><span>), você será direcionado para a página de
boas-vindas do app. No menu superior, escolha o modo "edição", no ícone
do lápis, para começar a criar sua história. Clique em
</span><span class="c28">Work with Local Repository \[Trabalhar com seu
repositório local\] </span><span class="c0">e selecione a pasta raiz do
repositório quando solicitado. </span>

<span>Toda criação de conteúdo permanece em seu computador até que faça
uma publicação. Ao publicar, o app irá sincronizar o conteúdo local em
seu computador com o </span><span>repositório</span><span> em sua conta
GitHub, tornando-o acessiveis para edição por outros colaboradores que
acesso ao repositório, ou até mesmo para
</span><span>visualização</span><span> final como site no GitHub Pages
ou em seu serviço de hospedagem caso tenha configurado.</span>

<sup>[\[l\]](#cmnt12)</sup>

<span class="c0"></span>

### <span class="c23">Modos de visualização</span>

<span class="c0">Ainda no menu superior, você escolhe como quer
acompanhar o trabalho. São três modos:</span>

|                                           |                                                                                          |
| ----------------------------------------- | ---------------------------------------------------------------------------------------- |
| <span class="c32 c43 c28 c47">Modo</span> | <span class="c32 c43 c28 c47">O que mostra</span>                                        |
| <span class="c29">Edição</span>           | <span class="c29">Apenas o painel de edição</span>                                       |
| <span class="c29">Geohistória</span>      | <span class="c29">Apenas a página da história, como o leitor vai vê-la</span>            |
| <span class="c29">Tela dividida</span>    | <span class="c29">Os dois lado a lado, para acompanhar o resultado enquanto edita</span> |

<span class="c0"> </span>

|                                                                                                                                                                                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c28 c13 c110">As mudanças não aparecem sozinhas: </span><span class="c13">mesmo com a tela dividida, a página da geohistória não se atualiza automaticamente conforme você digita. É preciso salvar a história para ver as alterações refletidas na visualização.</span> |

<span class="c0"></span>

<span> </span>

<span class="c0"></span>

<sup>[\[m\]](#cmnt13)[\[n\]](#cmnt14)</sup>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 364.00px;">![](images/image1.png)</span>

<span class="c30 c80">Tela inicial do Sveltia CMS – escolha "Work with
Local Repository" para começar.</span>

## <span class="c28 c36">4.1 Criando a página</span>

<span>Você vai ser direcionado para a página do seu ambiente de
trabalho</span><span class="c0">, onde você vai encontrar todas as suas
histórias (caso já tenha criado ou começado alguma), assim como a
biblioteca de arquivos do seu ambiente de trabalho, onde seu material
audiovisual deverá ser armazenado. </span>

<span class="c0">No canto superior direito, você pode acessar as
configurações do modo de edição, onde poderá escolher o modo claro ou
escuro, assim como outras preferências.</span>

<span class="c0"></span>

<sup>[\[o\]](#cmnt15)[\[p\]](#cmnt16)</sup>

<span>As páginas da sua geohistória da Documental podem ser organizadas
por seções. Se a sua história for muito grande (maior do que 15
componentes – </span><span>ver seção</span><span class="c28"> 4.7
Components</span><span>)</span><span>, ela precisará ser dividida em
subpáginas. Elas estarão todas dentro da mesma seção, conforme a imagem
acima que mostra o projeto Nhanderekoa dividido em 3 páginas de edição.
Para mais informações sobre a divisão de páginas, </span><span>veja a
próxima
</span><span class="c28">seção</span><span> </span><span class="c28">4.2.
Project</span><span>.</span>

<span>Para criar uma nova história, selecione o botão
</span><span class="c28">Novo</span><span class="c0"> no canto superior
direito da tela. Isso abrirá uma tela de edição de geohistórias. </span>

<span class="c0"></span>

<sup>[\[q\]](#cmnt17)[\[r\]](#cmnt18)</sup>

<span>Preencha os campos </span><span class="c28">"Title"</span><span> e
</span><span class="c28">"Slug"</span><span class="c28"> </span><span>(este
é o endereço que aparece no final da sua URL da documental quando você
cria o repositório =
documental.xyz/</span><span class="c38">slug</span><span>)</span><span> </span><span>–
é importante que esses dois campos tenham valores únicos em relação às
outras geohistórias, pois informações duplicadas podem causar erros na
plataforma.</span>

<span class="c1">Abaixo desses campos, encontram-se as
seções</span><span class="c28 c1"> </span><span class="c28">Project,
Page Settings, Page Theme, Page Include,
Modules</span><span> </span><span class="c1">e, por fim, a aba
</span><span class="c28 c1">Components</span><span class="c1">, onde
serão inseridos os blocos que formam o conteúdo da
página</span><span class="c0">. </span>

<span class="c0"></span>

|                                                                                                                                                                                                                                                                       |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c4">O que é o slug: </span><span class="c32 c90 c13 c36">é uma versão do título simplificado, sem espaços, caracteres especiais, acentuação e de preferencia, tudo minúsculo. Exemplo: O slug de "População Ribeirinha" é "populacao-ribeirinha".</span> |

<span class="c0"></span>

<span class="c0"></span>

## <span class="c28 c36">4.2 Project</span><span class="c28 c36"> \[Projeto\]</span>

## <span class="c1 c36">Esse campo é utilizado quando desejar dividir uma página da Documental em subpáginas, ou quando sua geohistória for extensa e precisar de mais de 15 componentes. Para manter a página principal e as subpáginas juntas num grupo só, você preenche o campo </span><span class="c28 c1 c36">Project</span><span class="c1 c36"> com o nome desejado para o agrupamento. Esse agrupamento aparecerá na tela de escolha de páginas da Documental, com o nome da página principal e das subpáginas que estão dentro do agrupamento, depois que você também configurar o campo</span><span class="c28 c1 c36"> Page Include</span><span class="c1 c36">, na </span><span class="c28 c1 c36">seção 4.5</span><span class="c0">. </span>

<span class="c0"></span>

<sup>[\[s\]](#cmnt19)</sup>

<span>Caso não deseje nem precise dividir sua história em subpáginas,
você pode deixar o campo
</span><span class="c28">Project</span><span class="c0"> vazio. </span>

<span class="c0"></span>

## <span class="c2">4.</span><span class="c28 c36">3</span><span class="c2"> </span><span class="c28 c36">Page Settings \[Configurações da Página\]</span>

## <span class="c0">Este campo reúne as definições gerais da página: idioma, animações, alinhamento do texto e parâmetros de SEO.</span>

### <span class="c23">Idioma</span>

## <span class="c1 c36">Você pode disponibilizar uma geohistória em mais de um idioma, mas para isso deve duplicar a página no idioma original, traduzi-la, e atribuir um slug diferente. </span><span class="c1 c36">Para disponibilizá-la em outro idioma, selecione no campo </span><span class="c28 c1 c36">Idioma</span><span class="c1 c36"> a opção em uma das </span><span class="c1 c36">linguagens</span><span class="c1 c36"> disponíveis </span><span class="c1 c36">(PT - Português, EN - Inglês e ES - Espanhol) e </span><span class="c1 c36">indique o slug da página correspondente.</span><span class="c0"> Recomendamos que o slug nas páginas em outros idiomas seja o mesmo da página do idioma original mas adicionando um sufixo relacionado. Exemplo: Página principal em português: “nhanderekoa”; Página respectivamente em inglês e espanhol: “nhanderekoa-en”, “nhanderekoa-es”.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image61.png)</span>

<span class="c39 c38">Campo Configurações da Página.</span>

### <span class="c23">Animações, alinhamento e SEO</span>

<span>Os blocos da Documental possuem animações em suas configurações,
para que apareçam gradativamente durante a rolagem da página. Também é
possível desativar essa opção e deixar todos os blocos “estáticos”.
Nesse item, </span><span>é possível controlar se os blocos terão essa
animação ou </span><span>não,  
  
</span><span class="c0">Há também os parâmetros de SEO (otimização para
mecanismos de busca), que definem como a sua história aparece nos
resultados de pesquisa e quando o link é compartilhado em redes sociais
e aplicativos de mensagem – o título, a descrição e a imagem que
acompanham o endereço. Vale preenchê-los: é o que faz a diferença entre
um link que convida à leitura e um endereço sem contexto.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 285.00px;">![](images/image63.png)</span>

<span class="c39 c38">Parâmetros de animação, alinhamento e SEO.</span>

## <span class="c2">4.</span><span class="c28 c36">4</span><span class="c2"> </span><span class="c28 c36">Page Theme \[Tema da Página\]</span>

<span class="c1">No campo </span><span class="c28 c1">Tema da
Página</span><span class="c1">, v</span><span class="c1">ocê configura
a paleta de cores que compõe a sua
</span><span>geohistória</span><span class="c1">. </span>

<span class="c1">Há uma fonte padrão aplicada, mas é possível
personalizá-la inserindo uma fonte do
</span><span class="c28 c1">Google Fonts </span><span class="c1">(ver
</span><span class="c28 c1">seção 4.</span><span class="c28">9 Recursos
Complementares</span><span class="c1">).</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image66.png)</span>

<span class="c39 c38">Configuração da paleta de cores.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image67.png)</span>

<span class="c39 c38">Configuração de fonte e espaçamento entre
linhas.</span>

## <span class="c24 c108">4.5 Page Include \[Inclusão de página\]</span>

<span class="c24 c1"></span>

### <span class="c23">Por que ele existe</span>

<span>O projeto</span><span class="c0"> publicado pode ter o tamanho que
a sua geohistória pedir. O que tem limite é a página de edição: cada
página aceita até 15 componentes, para que o editor não fique
pesado.</span>

<span>Quando a história precisa de mais que isso, divide-se o conteúdo
em várias páginas de edição, e o componente
</span><span class="c28">Page Include </span><span class="c0">costura
tudo de volta em uma só na publicação. O leitor não percebe a divisão –
para ele, a narrativa é contínua.</span>

### <span class="c23">Como funciona</span>

<span class="c0">O Page Include é um componente como os outros, mas não
traz conteúdo próprio: ele chama o conteúdo de outra página. No lugar
onde você o insere, entra tudo o que estiver naquela página.</span>

<span>Há duas formas de organizar essa
divisão.</span><span class="c0">  
</span>

<span>  
</span><span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 443.06px; height: 480.60px;">![](images/image65.png)</span>

<span class="c16">As duas formas de usar o Page Include: uma página
principal que inclui todas as demais, ou páginas encadeadas em que cada
uma inclui a seguinte.</span>

<span class="c0"></span>

### <span class="c23">Método 1 – uma página principal que reúne as demais</span>

<span>Você cria uma página inicial que carrega as configurações da
história – </span><span class="c28">Page Settings, Page Theme
</span><span>e </span><span class="c28">Modules: Mapbox</span><span> – e
cujos componentes são apenas os </span><span class="c28">Page
Includes</span><span class="c0"> das outras páginas:</span>

<span class="c88 c12 c36">- Page Settings</span>

<span class="c88 c12 c36">- Page Theme</span>

<span class="c88 c12 c36">- Modules: Mapbox</span>

<span class="c88 c12 c36">- Components:</span>

<span class="c88 c12 c36">        - Page Include: 'pagina1'</span>

<span class="c88 c12 c36">    - Page Include: 'pagina2'</span>

<span class="c0">Cada página incluída pode ter até 15 componentes. É a
organização indicada quando a história tem capítulos bem definidos: a
página principal funciona como um índice, e permite ver a estrutura
inteira em uma tela e reordenar capítulos.</span>

### <span class="c23">Método 2 – páginas encadeadas</span>

<span class="c0">Aqui cada página aponta para a seguinte. A primeira
recebe até 14 componentes e, no último lugar, um Page Include indicando
onde a história continua:</span>

<span class="c12 c36 c88">- Page Settings</span>

<span class="c88 c12 c36">- Page Theme</span>

<span class="c88 c12 c36">- Modules: Mapbox</span>

<span class="c88 c12 c36">- Components:</span>

<span class="c88 c12 c36">        - Group 1</span>

<span class="c88 c12 c36">        ...</span>

<span class="c88 c12 c36">        - Group 14</span>

<span class="c88 c12 c36">    - Page Include: 'pagina2'</span>

<span class="c0">São 14, e não 15, porque o próprio Page Include ocupa a
última vaga. É a organização mais próxima da leitura linear, mas não
oferece visão geral: para saber o que vem depois, é preciso abrir a
página seguinte.</span>

### <span class="c124 c28">Qual método escolher</span>

|                                          |                                                                                                     |                                                                                  |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| <span class="c0"> </span>                | <span class="c32 c43 c28 c47">Método 1</span>                                                       | <span class="c32 c43 c28 c47">Método 2</span>                                    |
| <span class="c24 c43">Estrutura</span>   | <span class="c29">Uma página índice mais as páginas de conteúdo</span>                              | <span class="c29">Páginas em sequência, cada uma apontando para a próxima</span> |
| <span class="c24 c43">Vantagem</span>    | <span class="c29">Visão geral da história em uma tela, e facilidade para reordenar capítulos</span> | <span class="c29">Segue a ordem natural da leitura e da escrita</span>           |
| <span class="c24 c43">Quando usar</span> | <span class="c29">Histórias com capítulos bem definidos desde o início</span>                       | <span class="c29">Histórias que cresceram e precisaram ser divididas</span>      |

<span class="c0"> </span>

### <span class="c23">Reaproveitando um trecho em várias páginas</span>

<span class="c0">O Page Include serve também para não repetir conteúdo.
Se um mesmo bloco precisa aparecer em mais de um lugar – uma chamada
para ação, os créditos, uma régua de logos –, coloque-o em uma página
própria e inclua-a onde for necessário.</span>

<span>É o que mostra o diagrama acima: nos dois métodos, o bloco
</span><span class="c28">CTA</span><span> (ver
</span><span class="c28">seção 4.7 Components</span><span class="c0">)
está em uma página separada e é chamado por duas páginas diferentes. Ao
editar essa página, a alteração aparece em todos os lugares de uma
vez.</span>

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c4">As páginas incluídas herdam as configurações: </span><span class="c13">só a primeira página precisa das configurações da história – </span><span class="c28 c13">Page Settings, Page Theme</span><span class="c13"> e </span><span class="c28 c13">Modules: Mapbox.</span><span class="c13"> As páginas incluídas herdam tudo isso e não repetem nada. Nelas, basta inserir o componente </span><span class="c28 c13">Map</span><span class="c32 c90 c13 c36"> onde você quiser que o mapa apareça.</span> |

<span class="c0"> </span>

<span>  
</span>

## <span class="c2">4.</span><span class="c28 c36">6</span><span class="c2"> Modules</span><span class="c2"> \[M</span><span class="c28 c36">ódulos\]</span>

<span>O mapa é o eixo da narrativa na Documental e é nesse campo que
você inclui seus mapas na geohistória. Ao clicar em
</span><span class="c28">adicionar Module</span><span>, selecione a
opção </span><span class="c28">Mapbox</span><span class="c0">.</span>

### <span class="c23">Duas etapas separadas</span>

<span class="c0">Vale entender, primeiramente, como a plataforma
organiza os mapas, detalhada a seguir:</span>

<span>•</span><span class="c77">    </span><span>E</span><span>m
</span><span class="c28">Mapbox</span><span>, você insere as
configurações principais para conectar o seu mapa desenvolvido no
Mapbox, e </span><span class="c28">define</span><span class="c0"> as
vistas – cada enquadramento que o mapa vai assumir ao longo da
história.</span>

<span>•</span><span class="c77">    </span><span>Depois, no campo
</span><span class="c28">Components</span><span>, você
</span><span class="c28">usa</span><span> essas vistas,
</span><span>inserindo</span><span>-</span><span>as
na</span><span> narrativa por meio do bloco
</span><span class="c28">Map</span><span class="c28"> </span><span>(</span><span>mais
detalhado na </span><span class="c28">seção 4.7
Components</span><span>)</span><span class="c0">.</span>

<span>  
Definir uma vista não a faz aparecer na página: ela só entra na história
quando é chamada por um bloco </span><span class="c28">Map</span><span>.
</span><span>A vantagem é poder reaproveitar a mesma vista em vários
pontos da narrativa, sem reconfigurá-la, ou poder definir todas as
vistas numa página principal, e desenvolver a
</span><span>geohistória</span><span> através dos componentes em
subpáginas, deixando a sua geohistória de modo geral mais
leve.</span><span class="c0">  
</span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><span class="c32 c4">O que é uma vista</span></p>
<p><span class="c13">Uma vista (</span><span class="c38 c13">mapview</span><span class="c32 c90 c13 c36">) é uma fotografia do mapa: um ponto central, um nível de zoom, uma inclinação e um conjunto de camadas visíveis. Quando o leitor rola a página e passa de um bloco para o seguinte, o mapa transita suavemente de uma vista para a outra — é daí que vem o efeito de scrollytelling.</span></p></td>
</tr>
</tbody>
</table>

<span class="c0"> </span>

### <span class="c23">Conectando a sua conta</span>

<span>Comece colando o </span><span class="c28">Map Style</span><span> e
o </span><span class="c28">Map Token</span><span> que você copiou do
Mapbox (</span><span class="c28">seção 3.5 Conectando o mapa à
Documental</span><span class="c0">) nos respectivos campos.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 252.00px;">![](images/image68.png)</span><sup>[\[t\]](#cmnt20)[\[u\]](#cmnt21)</sup>

<span class="c16">Campos de configuração do Mapbox na Documental.</span>

<span class="c16"></span>

### <span class="c23">A vista inicial</span>

### <span class="c0">Em seguida, defina a visualização inicial, o "ponto de partida" do mapa. Os parâmetros são os mesmos de todas as vistas que você criar depois:</span>

### <span class="c23"> </span>

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><h3 id="parâmetro" class="c57 c104"><span class="c32 c43 c28 c47">Parâmetro</span></h3></td>
<td><h3 id="o-que-define" class="c57 c104"><span class="c32 c43 c28 c47">O que define</span></h3></td>
</tr>
<tr class="even">
<td><h3 id="latitude-e-longitude" class="c10"><span class="c24 c43">Latitude e longitude</span></h3></td>
<td><h3 id="a-localização-do-ponto-central-do-mapa" class="c10"><span class="c29">A localização do ponto central do mapa</span></h3></td>
</tr>
<tr class="odd">
<td><h3 id="zoom" class="c10"><span class="c24 c43">Zoom</span></h3></td>
<td><h3 id="o-nível-de-aproximação" class="c10"><span class="c29">O nível de aproximação</span></h3></td>
</tr>
<tr class="even">
<td><h3 id="layers" class="c10"><span class="c24 c43">Layers</span></h3></td>
<td><h3 id="quais-camadas-do-mapbox-ficam-visíveis-nessa-vista.-é-possível-filtrar-para-que-apenas-determinadas-feições-apareçam-ver-seção-4.9.-recursos-complementares" class="c10"><span class="c43 c36">Quais camadas do Mapbox ficam visíveis nessa vista. É possível filtrar para que apenas determinadas feições apareçam (ver </span><span class="c43 c28 c36">seção 4.9. Recursos Complementares</span><span class="c29">)</span></h3></td>
</tr>
<tr class="odd">
<td><h3 id="duração-opcional" class="c10"><span class="c24 c43">Duração (opcional)</span></h3></td>
<td><h3 id="o-tempo-da-transição-entre-os-blocos-em-milissegundos" class="c10"><span class="c29">O tempo da transição entre os blocos, em milissegundos</span></h3></td>
</tr>
<tr class="even">
<td><h3 id="bearing-opcional" class="c10"><span class="c24 c43">Bearing (opcional)</span></h3></td>
<td><h3 id="a-rotação-da-câmera-na-horizontal" class="c10"><span class="c29">A rotação da câmera na horizontal</span></h3></td>
</tr>
<tr class="odd">
<td><h3 id="pitch-opcional" class="c10"><span class="c24 c43">Pitch (opcional)</span></h3></td>
<td><h3 id="a-rotação-da-câmera-na-vertical" class="c10"><span class="c29">A rotação da câmera na vertical</span></h3></td>
</tr>
</tbody>
</table>

### <span class="c23"> </span>

### <span class="c1 c36">Os três parâmetros opcionais não afetam o funcionamento do mapa – servem para refinar o movimento e dar sensação de tridimensionalidade. Sobre o </span><span class="c28 c1 c36">bearing</span><span class="c1 c36"> e o </span><span class="c28 c1 c36">pitch</span><span class="c1 c36">, consulte o</span><span class="c76 c1">[ glossário do Mapbox](https://www.google.com/url?q=https://docs.mapbox.com/help/glossary/bearing/&sa=D&source=editors&ust=1786675075445397&usg=AOvVaw1ZFj-mxEYvjlZnGZtW8rtb)</span><span class="c0">.</span>

### <span class="c7"></span>

|                                                                                                                                                                                                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| <span class="c4">De onde vêm os números: </span><span class="c13">latitude, longitude e zoom saem da barra cinza inferior do Mapbox Studio (</span><span class="c28 c13">seção 3.4</span><span class="c32 c90 c13 c36">). Enquadre o mapa como deseja lá e anote os valores que aparecem.</span> |

<span> </span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image37.png)</span>

<span class="c39 c38">Configuração da vista inicial do
mapa.</span><sup>[\[v\]](#cmnt22)[\[w\]](#cmnt23)</sup>

### <span class="c23"></span>

### <span class="c124 c28">Vistas do mapa</span>

<span class="c1">Depois de configurar a primeira vista, você verá o
campo para adicionar as demais vistas que irão compor a página. Cada
vista tem um identificador (ID)
</span><span class="c28 c1">único</span><span class="c1">, que não deve
ser repetido em outra vista e não deve conter espaços nem caracteres
especiais (</span><span>por exemplo, “vista\_secao\_1” está correto,
“vista seção 1\!@” está incorreto e pode dar erro na
página)</span><span class="c1">.</span>

<span class="c1">Preencha a localização do mapa (longitude e latitude).
O campo do zoom é apropriado para o funcionamento do mapa em notebooks e
outros desktops</span><span>, mas </span><span class="c1">é recomendado
verificar um zoom apropriado para mobile e tablet
também</span><span>.</span><span class="c1"> </span><span>A</span><span> melhor
forma para definir consiste em abrir o mapa em um dispositivo
mobile/tablet e ir ajustando o zoom e outros parâmetros até que o mapa
esteja com a visualização
adequada</span><span class="c1">.</span><span class="c1"> Em seguida,
ajuste duração,</span><span class="c28 c1"> bearing, pitch e as
layers</span><span class="c1">, todos os parâmetros voltados para essa
vista específica.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image29.png)</span>

<span class="c39 c38">Adição de novas vistas do mapa.</span>

<span class="c1">Existe também um campo para definir a legenda de cada
vista </span><span>do mapa</span><span class="c1">. Nele você define
rótulos explicativos para os dados, podendo incluir um título e uma
descrição, se quiser. </span><span class="c1">Ao abrir a aba de
co</span><span>nfiguração de legenda</span><span class="c1">,
</span><span>escreva o texto </span><span class="c1">que será exibido na
legenda</span><span class="c1">, se quiser,
</span><span class="c1">defina um ícone personalizado </span><span>para
a legenda</span><span class="c1"> via </span><span class="c28 c1">Google
Icons</span><span class="c1"> </span><span class="c1">(</span><span class="c1">ver
</span><span class="c28 c1">seção 4.</span><span class="c28">9 Recursos
Complementares</span><span class="c1">)</span><span> e
</span><span class="c1">selecione sua cor.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 269.00px;">![](images/image2.png)</span>

<span class="c39 c38">Configuração da legenda de uma vista.</span>

## <span class="c2">4.</span><span class="c28 c36">7</span><span class="c2"> Components</span><span class="c2"> \[Componente</span><span class="c28 c36">s\]</span>

<span class="c1">É através da seção
</span><span class="c28 c1">Componentes</span><span class="c1"> que o
conteúdo </span><span>da</span><span class="c1"> página é montado.
</span><span>C</span><span class="c1">ada trecho de texto, cada imagem,
cada gráfico e </span><span class="c1">cada movimento do mapa é um
componente, ou
</span><span class="c28 c1">bloco</span><span class="c28"> de
conteúdo</span><span class="c1">. A plataforma reúne
</span><span class="c1">2</span><span>8</span><span class="c1"> blocos
diferentes</span><span class="c0">, e é da combinação deles que nasce a
sua história: você escolhe quais usar e em que ordem, conforme o que
precisa mostrar e o tipo de narrativa que quer construir.</span>

<span>Os blocos seguem uma hierarquia, dividida em dois
tipos:</span><span class="c28"> blocos-raíz</span><span> e
</span><span class="c28">blocos-filho</span><span class="c0">. Os
blocos-raíz funcionam como ponto de entrada, é a partir deles que os
blocos-filho podem ser chamados e inseridos no conteúdo da
página.</span>

<span class="c0"></span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><span class="c32 c4">O que são os blocos</span></p>
<p><span class="c32 c90 c13 c36">Componentes, ou blocos, são estruturas prontas para receber conteúdo. Cada uma já vem com a diagramação, o comportamento e a adaptação a diferentes tamanhos de tela programados de antemão. Você não precisa desenhar e diagramar como as coisas aparecem: escolhe o bloco adequado e preenche os campos que ele pede, e ele já monta o conteúdo no design escolhido.</span></p>
<p><span class="c13">Cada tipo de bloco espera um tipo de material. O bloco </span><span class="c28 c13">Texto</span><span class="c13"> pede um texto; o </span><span class="c28 c13">Comparativo de Imagens</span><span class="c13"> pede duas imagens do mesmo lugar; a </span><span class="c28 c13">Linha do Tempo</span><span class="c13"> pede uma sequência de datas; o </span><span class="c28 c13">Gráfico de Barras</span><span class="c32 c90 c13 c36"> pede números e rótulos.</span></p>
<p><span class="c32 c90 c13 c36">Por isso, a escolha do bloco é, na prática, uma decisão narrativa: você não está escolhendo somente um formato visual, está escolhendo a forma de mostrar aquele conteúdo específico.</span></p></td>
</tr>
</tbody>
</table>

<span class="c0"> </span>

### <span class="c23">Os quatro blocos-raíz (root blocks)</span>

<span>Em</span><span class="c28"> Adicionar componentes</span><span>,
quatro tipos de </span><span>blocos</span><span class="c0">-raíz, que
devem ser primeiramente implementados, estão disponíveis. Cada um atende
a um objetivo específico:</span>

<span class="c0"></span>

#### <span class="c20">Group</span>

<span>O bloco-raíz do tipo </span><span class="c28">Group</span><span>,
é um tipo genérico utilizado para chamar os blocos que efetivamente
irão aparecer na página. Através dele, você também consegue
personalizar a paleta de cores definida em </span><span class="c28">Page
Theme</span><span> para o background e para o texto. Esse grupo também
acaba sendo utilizado para separar capítulos de conteúdo na sua
geohistória – existe uma opção para definir se esse grupo irá
configurar como um capítulo na
</span><span>geohistória</span><span class="c0"> ou não, se sim, o
título do grupo aparecerá no menu- hambúrguer da sua
geohistória.</span>

#### <span class="c20">Map</span>

<span>O bloco-raíz </span><span class="c28">Map</span><span>, é
utilizado sempre que você quiser inserir um mapa na sua geohistória. É
por meio dele que são adicionadas as Mapviews. Também é possível inserir
imagens, vídeos embed e timeline dentro do scrolltelling dos mapas,
então, esses componentes –</span><span> Text, Image, Video Embed e
Timeline </span><span>explicados na</span><span class="c28"> seção 4.8.
Biblioteca de blocos</span><span> – </span><span class="c0">também ficam
disponíveis para manipulação dentro do bloco-raíz Map.</span>

<span class="c20 c38">Call to Action</span>

<span>O</span><span class="c28"> Call to Action </span><span>não tem a
funcionalidade de hospedar outros blocos dentro dele, e configura como
um bloco-raíz por aspectos técnicos. Ele constitui num grande bloco de
design, que tem a função de direcionar o visitante para uma ação
específica, como ver um cartaz e clicar num botão que irá direcioná-lo
para outra página. Ele cumpre a função literal de “Call to Action”, de
chamar atenção do visitante para um ação e realizar um direcionamento,
que poderia ser para a assinatura de uma petição, doação, leitura de um
documento, etc. </span>

#### <span class="c20">Espaçador</span>

<span>O </span><span class="c28">Espaçador</span><span> insere um espaço
vazio entre dois blocos. O valor é informado em pixels. Serve para dar
respiro à página e para ajustar o ritmo da rolagem. É um espaçador do
tipo bloco-raíz, para ser aplicado entre outros
blocos-</span><span>raíz</span><span>, por exemplo, para dar um espaço
entre dois blocos
</span><span class="c28">Group</span><span class="c0">. </span>

#### <span class="c20">I</span><span class="c20">nclude</span>

<span>O bloco-raíz
</span><span class="c28">Include</span><span class="c0"> é utilizado
para inserir uma sub-página dentro da geo-história, no ponto exato em
que ela deve aparecer. Antes de usá-lo, você precisa ter criado as
sub-páginas desejadas e atribuído a elas um Project em comum (que
agrupa na página de edição, todas as sub-páginas relacionadas).</span>

<span class="c0">Para usá-lo: no momento da geo-história em que a
sub-página deve aparecer, insira o componente Include e selecione a
sub-página que você quer referenciar. O conteúdo dela será chamado ali,
na sequência da narrativa. Depois de inserir um Include, você pode
seguir chamando outros componentes normalmente — inclusive um novo
Include, para trazer outra sub-página em outro ponto da história.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image30.png)</span><sup>[\[x\]](#cmnt24)</sup>

<span class="c39 c38">Seção Componentes, com os quatro
blocos-raíz.</span>

<span class="c0"></span>

<span class="c43 c28 c47">Bloco principal</span>

<span class="c43 c28 c47">Função</span>

<span class="c43 c28">Group</span>

<span class="c43">Permite a inserção dos blocos de design da Documental.
</span><span class="c43">Pode funcionar como um capítulo da narrativa.
Permite definir cor de fundo, cor de texto personalizadas, e mídia de
fundo – é o bloco que dá unidade visual a um trecho da
história</span><span class="c0"> </span>

<span class="c43 c28">Map</span>

<span class="c43">Permite a inserção de mapas na
</span><span class="c43">geohistória</span><span class="c43"> - é por
meio dele que são adicionadas as Mapviews. Também possui alguns outros
blocos de design disponíveis no seu catálogo (Image, Video Embed e
Timeline) que podem aparecer dentro dos
mapas</span><span class="c43">.</span>

<span class="c43 c28">Call to Action</span>

<span class="c43">Funciona como uma chamada para atenção. Direciona o
leitor a uma ação específica, como clicar em um botão ou acessar um link
</span>

<span class="c43 c28">Spacer</span>

<span class="c43">Adiciona espaçamento entre os elementos da
página</span>

<span class="c0"></span>

<span>Na prática, uma página da Documental é uma sequência de blocos
</span><span class="c28">Groups</span><span> e
</span><span class="c28">Maps</span><span>, cada um com o seu conteúdo
dentro, intercalados aqui e ali por um Call to Action ou um
Spacer.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 293.33px;">![](images/image34.png)</span>

<span class="c39 c38">Exemplo de Bloco Map composto com blocos de texto
e imagem</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 274.00px;">![](images/image31.png)</span><sup>[\[y\]](#cmnt25)[\[z\]](#cmnt26)</sup>

<span class="c39 c38">Exemplo de Bloco CTA (Call to Action).</span>

### <span class="c23">Identificação dos blocos</span>

<span>Cada bloco precisa ter um </span><span class="c28">ID
único</span><span>,</span><span> sem espaços ou caracteres especiais, e
um </span><span class="c28">Short Title</span><span>, também
obrigatório. O </span><span class="c28">Long Title</span><span> é
opcional e, quando preenchido, é usado como rótulo do bloco no menu
lateral da página publicada. O campo
</span><span class="c28">Description</span><span> também é
opcional.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 352.00px;">![](images/image13.png)</span>

<span class="c30 c80">Campos de identificação de um bloco Group. Os
campos marcados com asterisco vermelho são obrigatórios, e cada um traz
abaixo uma nota explicando sua função.</span>

### <span class="c124 c28">Configurações de fundo do Group</span>

<span>O bloco </span><span class="c28">Group</span><span> oferece, nas
configurações iniciais, a escolha da cor de fundo – entre as cores do
tema da página (Primary, Secondary, Highlight) ou uma cor personalizada,
com controle de opacidade. Também é possível adicionar uma
</span><span class="c28">Background
media</span><span> </span><span class="c1">, </span><span>que pode ser
um vídeo ou uma imagem armazenada no repositório de arquivos da
Documental, e aplicar sobre ela um
</span><span class="c28">overlay</span><span> claro ou escuro, para que
o texto por cima continue legível.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 352.00px;">![](images/image47.png)</span>

<span class="c30 c80">Configurações de fundo do bloco Group: cor de
fundo, mídia de fundo e camada de overlay. Ao final, o botão Add
Components é onde entram os blocos que formam o conteúdo.  
</span>

### <span class="c23"> </span>

### <span class="c23">Montando a página</span>

<span class="c1">No final do</span><span> conjunto
de</span><span class="c1"> blocos
</span><span class="c28 c1">Group</span><span class="c1"> e
</span><span class="c28 c1">Map</span><span class="c1">, vemos o botão
</span><span class="c28 c1">Add Components</span><span class="c1">, onde
conseguimos inserir </span><span>outros</span><span class="c1"> blocos
</span><span>para formar o conteúdo</span><span class="c1">. Chamamos
eles de blocos-filhos. A composição das páginas da Documental
</span><span>nasce da</span><span class="c1"> combinação </span><span>de
blocos filhos dentro de
blocos-raíz</span><span class="c1">.</span><span class="c1"> </span>

<span>Nos dois exemplos abaixo, no primeiro grupo de blocos foi
utilizado o bloco </span><span class="c28">Coluna Fixa</span><span>, que
pode servir como capa da página. Dentro dele foram inseridas informações
de texto com o bloco </span><span class="c28">Texto</span><span>, e a
posição dos textos foi ajustada com os blocos
</span><span class="c28">Espaçador</span><span class="c0">. </span>

<span>No segundo grupo, o conteúdo foi estruturado em formato de texto
corrido com o bloco </span><span class="c28">Coluna</span><span>, que
reúne dois blocos </span><span class="c28">Texto</span><span> e, no
final, um bloco
</span><span class="c28">Citação</span><span class="c0"> para
destacar uma passagem.</span>

<span>A relação completa dos blocos-filhos, com descrição e exemplo de
cada um, está na </span><span class="c24 c1">seção 4.8 abaixo.</span>

<span class="c30 c80"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 370.65px; height: 475.19px;">![](images/image32.png)</span>

<span class="c39 c38">Dois exemplos de montagem de página.</span>

<span>  
</span>

## <span class="c2">4.</span><span class="c28 c36">8</span><span class="c2"> Biblioteca de blocos-fi</span><span class="c28 c36">lhos</span>

<span class="c0">Esta seção apresenta a relação completa de todos os
blocos-filhos disponíveis e suas respectivas funções.</span>

<span>Montar uma página é, na prática, encaixar blocos-filhos
</span><span>dentro dos blocos-raíz
</span><span class="c28">Group</span><span> e
</span><span class="c28">Map</span><span>, vistos na seção
anterior.</span><span class="c0"> A Documental possui blocos de
formatação de página, texto, imagem e vídeo, timeline, destaques
numéricos, interação e redirecionamento, além do bloco para viabilizar
a inserção de vistas do mapa. </span>

<span>Entre os blocos-filhos há dois comportamentos. Alguns aceitam
outros blocos dentro de si: é o caso dos blocos de formatação, como o
</span><span class="c28">Two Columns</span><span> \[Duas Colunas\], que
divide o conteúdo em duas partes e recebe, em cada uma delas, blocos de
texto, imagem ou vídeo. Outros são simples e não aceitam composição – o
bloco </span><span class="c28">Text</span><span class="c0"> \[Texto\],
por exemplo, carrega o seu próprio conteúdo e nada mais.</span>

<span>Assim, ao convocar o bloco-raíz
</span><span class="c28">Group</span><span> para montar um capítulo de
uma </span><span>geohistória</span><span>, você provavelmente vai
começar por um bloco-filho de formatação de página, e, dentro dele,
acrescentar blocos com funcionalidades mais específicas.</span>

<span class="c0">Abaixo, você encontra dois esquemas representativos da
relação entre blocos-raíz e tipos blocos-filhos, assim como suas
funcionalidades, que serão explicadas em mais detalhes a seguir.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 536.00px; height: 499.00px;">![](images/image50.png)</span>

<span class="c30 c80">Esquema representativo da relação entre
blocos-raíz e os tipos de conteúdo possíveis a serem editados em cada
um a partir da inclusão de blocos-filhos.  
</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 310.67px;">![](images/image4.png)</span>

<span class="c112 c38">Blocos-filhos e suas funcionalidades</span>

<span class="c0"></span>

<span>A</span><span class="c0">baixo, você encontra a relação de cada
bloco-filho, sua descrição e recomendações de aplicação. </span>

<span>Se quiser visualizar os blocos aplicados, acesse a página de
exemplos dos layouts através do seguinte link:
</span><span class="c76">[https://documental.xyz/exemplo/](https://www.google.com/url?q=https://documental.xyz/exemplo/&sa=D&source=editors&ust=1786675075500265&usg=AOvVaw1gr3cvc1A3hPByTSgIPd19)</span><span> </span><span class="c42">  
</span>

### <span class="c50 c28">→ </span><span class="c50 c28">Formatação e texto</span><span class="c28 c124">  
</span><span class="c43 c28 c175">  
</span><span class="c30 c20 c1">Fixed Column / Title Column \[Coluna Fixa\]</span>

<span>Bloco de coluna fixa, geralmente usado como capa e título da
página: enquanto o leitor rola, o conteúdo permanece na tela. Traz um
campo próprio para o título e um botão para acrescentar outros blocos
que formam o corpo do texto. Há dois estilos de
composição,</span><span class="c38"> text-bigger e
title-bottom</span><span class="c0">, que mudam a proporção entre título
e texto e a posição do título dentro do bloco. Também é possível ativar
um espaçamento padrão acima e abaixo.</span>

<span class="c32 c20 c1"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 306.00px;">![](images/image33.png)</span><span class="c30 c80">Exemplo
de bloco Coluna Fixa usado como capa da página, com mídia de fundo e
overlay escuro.</span>

<span class="c0"></span>

#### <span class="c20">Central Column \[Coluna Central\]</span>

<span class="c0">Organiza os blocos em uma única coluna, centralizada na
página e com largura limitada para facilitar a leitura. É o bloco de uso
mais corrente na Documental: serve para o texto corrido da narrativa e
para tudo o que o acompanha – imagens, vídeos, gráficos. Também é
possível ativar um espaçamento padrão acima e abaixo.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 599.80px; height: 282.91px;">![](images/image39.png)</span><span>  
</span><span class="c38 c112">Exemplo de bloco Coluna Centralizada, com
um bloco Texto e, abaixo, um bloco Imagem.</span>

<span class="c0"></span>

#### <span class="c20">Two Columns \[Duas Colunas\]</span>

<span class="c0">Distribui os blocos em duas colunas lado a lado. Elas
não têm a mesma largura: você escolhe se a maior fica à esquerda ou à
direita, e a menor acompanha ao lado. É o bloco indicado para pôr dois
conteúdos em relação – um texto ao lado de uma linha do tempo, uma
imagem ao lado da sua explicação, um gráfico ao lado do parágrafo que o
interpreta. Também é possível ativar um espaçamento padrão acima e
abaixo.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 272.00px;">![](images/image35.png)</span>

<span class="c30 c80">Exemplo de bloco Duas Colunas, com blocos de Texto
na coluna maior, à esquerda, e um bloco Linha do Tempo na coluna menor,
à direita.</span>

#### <span class="c32 c20 c1"></span>

#### <span class="c30 c20 c1">Inner Columns \[Colunas Internas\]</span>

#### <span class="c0">Subdivide o conteúdo de uma coluna em duas colunas menores. Aceita somente blocos de texto, e serve para trechos em que dois parágrafos devem correr lado a lado, como um contraponto ou uma nota em paralelo ao texto principal.</span>

#### <span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 450.67px; height: 116.00px;">![](images/image22.jpg)</span>

#### <span class="c16">Exemplo de bloco Colunas Internas, com dois blocos de texto lado a lado.</span>

#### <span class="c30 c20 c1"></span>

#### <span class="c1 c20">Text \[Texto\]</span>

<span>Bloco de texto corrido, com formatação básica: negrito, itálico,
links, títulos e listas. É o bloco mais usado da
plataforma</span><span class="c1">.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 591.00px; height: 340.00px;">![](images/image36.png)</span>

<span class="c16">Exemplo de bloco Texto.</span>

<span class="c0"></span>

#### <span class="c20">Pull Quote \[Citação\]</span>

<span class="c0">Exibe uma passagem em destaque, com tratamento
tipográfico diferente do texto corrido. Útil para depoimentos, trechos
de documentos e falas que devem interromper o fluxo da leitura.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 220.00px;">![](images/image14.png)</span>

<span class="c39 c38">Exemplo de bloco Citação.</span>

<span class="c0"></span>

#### <span class="c20">Espaçador</span>

<span>Insere um espaço vazio entre dois blocos. O valor é informado em
pixels. Serve para dar respiro à página e para ajustar o ritmo da
rolagem. Diferente do espaçador bloco-raíz, é um espaçador do tipo
bloco-filho, para ser aplicado </span><span class="c28">entre outros
blocos-filho</span><span> –  entre capas, em transições entre vistas de
mapa ou dentro de blocos de formatação, como
o</span><span class="c28"> Two Columns</span><span class="c0">, para
trazer um dinamismo visual à página. </span>

<span class="c0"></span>

### <span class="c50 c28">→ Imagem e vídeo</span>

#### <span class="c20 c1 c30">Image \[Imagem\]</span>

<span class="c0">Exibe uma imagem armazenada no repositório de arquivos
da Documental, com campo para legenda.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 518.53px; height: 226.50px;">![](images/image3.jpg)</span>

<span class="c16">Exemplo de bloco Imagem, com legenda abaixo.</span>

<span class="c0"></span>

#### <span class="c20 c1">V</span><span class="c20">id</span><span class="c20 c1">eo Embed  </span>

<span>Incorpora um vídeo hospedado em plataforma externa, como YouTube
ou Vimeo. O arquivo não fica no seu repositório: é carregado do serviço
de origem.</span><span> </span><span>Veja como obter o link
n</span><span>a </span><span class="c28">seção 4.9 Recursos
Complementares.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 209.00px;">![](images/image15.png)</span>

<span class="c39 c38">Bloco Vídeo Embed em composição com um bloco Text.
Ambos estão dentro do bloco Two Columns.</span>

#### <span class="c20">  
</span><span class="c20 c1">HTML Embed</span>

<span class="c0">Permite inserir um trecho de código HTML na página, o
que possibilita incorporar conteúdo de outras plataformas – um gráfico
interativo, um formulário, um player de áudio. É o bloco a usar quando
nenhum outro dá conta.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 218.00px;">![](images/image16.png)</span><sup>[\[aa\]](#cmnt27)</sup>

<span class="c16">Exemplo de bloco HTML Embed.</span>

<span class="c0"></span>

#### <span class="c20">Image Slider \[Slider de Imagens\]</span>

<span class="c0">Exibe um conjunto de imagens em carrossel, uma de cada
vez, com navegação lateral. Indicado para sequências em que a ordem
importa.  
</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 284.00px;">![](images/image17.png)</span>

<span class="c16">Exemplo de bloco Slider de Imagens.</span>

<span class="c0"></span>

#### <span class="c20">Image Gallery \[Galeria de Imagens\]</span>

<span class="c0">Reúne um grupo de imagens em miniaturas. Ao ser
clicada, a imagem é ampliada. Indicado para conjuntos em que o leitor
escolhe o que quer ver de perto.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 224.00px;">![](images/image18.png)</span>

<span class="c16">Exemplo de bloco Galeria, com as imagens em
miniatura.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 283.00px;">![](images/image19.png)</span>

<span class="c16">A mesma galeria com uma imagem ampliada, após o
clique.</span>

<span class="c0"></span>

#### <span class="c20">Image Compare \[Comparativo de Imagens\]</span>

<span class="c0">Sobrepõe duas imagens do mesmo lugar com uma barra
deslizante, que o leitor arrasta para revelar uma ou outra. É o bloco
indicado para mostrar transformações no território – antes e depois de
um desmatamento, de uma obra, de um despejo.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 298.00px;">![](images/image20.png)</span>

<span class="c16">Exemplo de bloco Comparativo de Imagens.</span>

<span class="c0"></span>

### <span class="c50 c28">→ Linha do tempo</span><span class="c126">  
</span><span class="c20">  
</span><span class="c30 c20 c1">Timeline \[Linha do Tempo\]</span>

<span class="c0">Cria uma sequência cronológica de marcos ao longo de
uma linha. Além dos pontos, aceita blocos de imagem e vídeo embed, o que
permite ilustrar momentos específicos da cronologia.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 268.00px;">![](images/image21.png)</span><sup>[\[ab\]](#cmnt28)[\[ac\]](#cmnt29)</sup>

<span class="c16">Exemplo de bloco Linha do Tempo.</span>

<span class="c24 c1"></span>

#### <span class="c20">Timeline Event Bullet \[</span><span class="c30 c20 c1">Ponto da Linha do Tempo\]</span>

<span class="c0">Cada marco da cronologia, com data e descrição. Só pode
ser usado dentro de um bloco Linha do Tempo.</span>

<span class="c0"></span>

<sup>[\[ad\]](#cmnt30)</sup>

<span class="c0"></span>

<span class="c0"></span>

### <span class="c28 c50">→ Mapa</span>

#### <span class="c30 c20 c1">Map \[Mapa\]</span>

<span>Insere um mapa na página e
</span><span>organiza</span><span class="c0">, dentro dele, os blocos
que acompanham a narrativa cartográfica. Além das vistas do mapa, aceita
blocos de texto, linha do tempo, imagem e vídeo, que rolam sobre o mapa
enquanto ele se move.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 289.33px;">![](images/image41.png)</span>

<span class="c39 c38">Exemplo de bloco Mapa composto com bloco Linha do
Tempo \[contexto Texto e Imagem\]</span><span class="c28">  
</span>

<span class="c32 c28 c171 c1"></span>

<span class="c30 c20 c1">Mapview \[Vista do Mapa\]</span>

<span class="c1 c36">Indica uma mudança de enquadramento no mapa,
chamando uma das vistas já criadas nas
c</span><span class="c1 c36">onfigurações do
Mapbox</span><span class="c1 c36"> (</span><span class="c28 c1 c36">seção
4.6 Modules</span><span class="c0">). É o bloco que dispara o movimento
do mapa conforme o leitor rola a página.</span>

### <span class="c124 c28">  
</span><span class="c32 c50 c28">→ Destaques numéricos</span>

#### <span class="c20">  
Bar Chart \[</span><span class="c20 c1">Gráfico de Barras\]</span>

<span class="c0">Exibe um conjunto de dados em barras, com rótulos e
valores. Indicado para comparar grandezas entre categorias.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 270.00px;">![](images/image5.png)</span>

<span class="c16">Exemplo de bloco Gráfico de Barras.</span>

<span class="c0"></span>

#### <span class="c20">Percentage Chart \[</span><span class="c20 c1">Gráfico de Porcentagem\]</span>

<span class="c0">Mostra a divisão proporcional de um total, para
relações de parte e todo.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 220.00px;">![](images/image6.png)</span>

<span class="c16">Exemplo de bloco Gráfico de Porcentagem.</span>

<span class="c0"></span>

#### <span class="c20">Big Numbers \[</span><span class="c20 c1">Números Grandes\]</span>

<span class="c0">Destaca números isolados em corpo grande, acompanhados
de um rótulo. Útil para dar escala a uma informação: quantos hectares,
quantas famílias, quantos anos.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 225.00px;">![](images/image7.png)</span>

<span class="c16">Exemplo de bloco Números Grandes.</span>

<span class="c0"></span>

### <span class="c50 c28">→ Interação e créditos</span>

<span class="c0"></span>

#### <span class="c20">Button \[</span><span class="c20 c1">Botão\]</span>

<span class="c1">Insere um botão que direciona para um link. Pode
receber um ícone e possui variações de alinhamento.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 141.00px;">![](images/image8.png)</span>

<span class="c16">Exemplo de bloco Botão.</span>

<span class="c0"></span>

#### <span class="c20">Action </span><span class="c20">Cards \[</span><span class="c20 c1">Cart</span><span class="c20">ões de Ação\]</span>

<span class="c0">Cria um cartão de destaque, que pode levar a um link e
receber um ícone. Serve para chamar atenção a um conteúdo dentro do
fluxo da página.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 166.00px;">![](images/image9.png)</span>

<span class="c39 c38">Exemplo de bloco Cartões.</span>

<span class="c0"></span>

<span class="c0"></span>

#### <span class="c20">Logos Strip \[</span><span class="c20 c1">Régua de Logos\]</span>

<span class="c0">Exibe uma fileira de imagens com links, normalmente
usada para creditar organizações parceiras e financiadoras ao pé da
página.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 251.00px;">![](images/image10.png)</span>

<span class="c16">Exemplo de bloco Régua de Logos.</span>

<span class="c0"></span>

#### <span class="c20">Image</span><span class="c20"> Cards \[</span><span class="c20 c1">Cartões de </span><span class="c20">Imagem</span><span class="c20 c1">\]</span>

<span class="c0">Conjunto de cartões que remetem a outros conteúdos.
Usado com frequência ao final da página, como "veja também" ou chamada
para outras geohistórias.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 234.00px;">![](images/image11.png)</span>

<span class="c16">Exemplo de bloco Cartões de Chamada.</span>

## <span class="c24 c108"></span>

## <span class="c2">4.</span><span class="c28 c36">9</span><span class="c2"> Recursos complementares</span>

### <span class="c92 c28">Filtros de layers</span>

<span>Na seção </span><span class="c28">4.6
Modules</span><span> explicamos os parâmetros que compõem uma Mapview
(vista do mapa). Entre eles estão os
</span><span class="c28">Layers</span><span class="c0"> – as camadas do
Mapbox que ficam visíveis naquela vista. Esta seção trata do mecanismo
de filtragem dessas camadas.</span>

### <span class="c23">Como listar as camadas</span>

<span>Para definir as camadas de uma vista, preencha o campo
</span><span class="c28">View Layers </span><span>com o nome de cada
uma, </span><span class="c28">uma por linha</span><span class="c0">.
Abaixo, o exemplo de uma vista montada a partir das camadas
listadas:</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 241.33px;">![](images/image40.png)</span>

<span class="c38 c131">campo Layers preenchido com uma camada por
linha\]</span><span class="c0"> </span>

### <span class="c23">Por que filtrar</span>

<span class="c0">Uma camada não corresponde necessariamente a um único
geodado: ela pode reunir vários. Dependendo da complexidade do mapa,
você vai querer exibir apenas um deles em determinada vista – e não a
camada inteira. É para isso que serve a filtragem: ela permite
evidenciar um geodado específico pelo seu atributo.</span>

<span class="c0">Se o geodado não tiver atributos, não há como
filtrá-lo. Os atributos precisam ser inseridos antes, em software de
GIS, na etapa de preparação dos dados.</span>

<span class="c0"></span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><span class="c4 c32">O que é um atributo</span></p>
<p><span class="c32 c90 c13 c36">Atributo é cada informação associada a um elemento do geodado. Um ponto que marca uma manifestação pode carregar a data, o município, o número de participantes e a pauta; um polígono de desmatamento pode carregar o ano, a área em hectares e o bioma.</span></p>
<p><span class="c13">São esses campos, e os valores que guardam, que tornam a filtragem possível. Atributos são criados e editados em softwares como o QGIS, antes de os dados irem para o Mapbox. </span></p></td>
</tr>
</tbody>
</table>

<span class="c0"></span>

### <span class="c23">Como escrever o filtro</span>

<span class="c0">No exemplo abaixo, algumas camadas aparecem por inteiro
e duas recebem filtro:</span>

<span class="c0"></span>

<span> </span><span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 601.70px; height: 241.33px;">![](images/image26.png)</span>

<span class="c88 c12 c36">nomeDaLayer\[propriedade==valor\]</span>

<span class="c88 c12 c36">locais-manifestacoes\[fid==8\]</span>

<span>Escreva o nome da camada, abra colchetes, informe a propriedade do
atributo, o sinal
</span><span class="c43 c90 c140">==</span><span class="c0"> e o valor
desejado.</span>

### <span class="c23">Quando você vai precisar disso</span>

<span>O Mapbox permite o upload de apenas 15 tilesets por estilo de mapa
</span><span class="c28">(ver seção 3.1)</span><span class="c0">. Em
mapas mais robustos, isso obriga a agrupar vários geodados dentro de um
mesmo tileset – e a filtragem passa a ser a única forma de exibi-los
separadamente. É o que permite mostrar apenas os registros de um
determinado ano, município ou categoria sem precisar de um tileset para
cada recorte.</span>

<span class="c0"></span>

|                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c28 c13 c110">Mapbox Standard não permite filtrar: </span><span class="c13">como mencionado na </span><span class="c28 c13">seção 3.3</span><span class="c32 c90 c13 c36">, a filtragem de layers não funciona se o mapa estiver usando o Mapbox Standard como mapa base. Nesse estilo, as camadas vêm empacotadas pela Mapbox e não podem ser manipuladas individualmente – o que impede o filtro de operar.</span> |

<span class="c0"> </span>

<span class="c0"></span>

### <span class="c92 c28">Fontes personalizadas</span>

<span>Para inserir fontes personalizadas na Documental, entre
n</span><span class="c1">o site do </span><span class="c76 c1">[Google
Fonts](https://www.google.com/url?q=https://fonts.google.com/&sa=D&source=editors&ust=1786675075551713&usg=AOvVaw2Ah1fgDo-_J3aqVj8jUrbn)</span><span> e
</span><span class="c1">clique na fonte desejada, depois
</span><span>clique</span><span class="c1"> em
</span><span class="c28 c1">Get font</span><span class="c1"> e em
</span><span class="c28 c1">Get embed
code</span><span class="c1">.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 286.00px;">![](images/image12.png)</span>

<span class="c16">No Google Fonts, escolha a fonte desejada e clique em
Get font, depois em Get embed code.</span>

<span class="c0"></span>

<span class="c0"></span>

<span class="c1">Configure o estilo da fonte e copie a URL disponível em
</span><span class="c28 c1">Embed code in the \<head\> of your
html</span><span class="c1">. Copie a URL que está entre aspas, dentro
de </span><span class="c28 c1">link href</span><span>, conforme mostra
abaixo:</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 286.00px;">![](images/image46.png)</span>

<span class="c39 c38">Copie apenas a URL que está entre aspas, dentro de
link href.</span>

<span class="c0"></span>

<span class="c1">Insira essa URL no </span><span class="c1">campo de
definição de fonte da Documental
</span><sup>[\[ae\]](#cmnt31)[\[af\]](#cmnt32)</sup><span class="c1">e
sua fonte personalizada estará configurada.</span>

### <span class="c23"></span>

### <span class="c92 c28">Ícones de legendas</span>

<span>Na seção </span><span class="c28">4.6 Modules</span><span>, ao
tratar das vistas do mapa, mencionamos a possibilidade de inserir ícones
personalizados nas legendas. O ícone personalizado é definido pelo nome
do ícone no </span><span class="c28">Google
Icons</span><span class="c0">, que você informa no campo Icon, dentro da
configuração de legenda de cada vista.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 269.00px;">![](images/image2.png)</span>

<span class="c39 c38">Configuração da legenda de uma vista.</span>

### <span class="c23">Como encontrar o nome do ícone</span>

<span>1.</span><span class="c77">    </span><span>No site
do</span><span>[ ](https://www.google.com/url?q=https://fonts.google.com/icons&sa=D&source=editors&ust=1786675075557721&usg=AOvVaw2BIY1WFL3ebQN9h14CXnRm)</span><span class="c134">[Google
Icons](https://www.google.com/url?q=https://fonts.google.com/icons&sa=D&source=editors&ust=1786675075557986&usg=AOvVaw0joyOKWThUOdMK1GFuopRp)</span><span>,
clique no ícone desejado.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 283.00px;">![](images/image48.png)</span>

<span class="c16">Biblioteca do Google Icons.</span>

<span class="c0"></span>

<span>1.</span><span class="c77">    </span><span>Role a aba lateral que
se abre até encontrar o campo </span><span class="c28">Icon
name</span><span class="c0">.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 285.00px;">![](images/image49.png)</span>

<span class="c16">O campo Icon name, na aba lateral do ícone
selecionado.</span>

<span class="c0"></span>

<span>1.</span><span class="c77">    </span><span>Copie esse nome e cole
no campo </span><span class="c28">Icon</span><span class="c0">, na
configuração de legenda da Documental.  
</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 274.00px;">![](images/image51.png)</span>

<span class="c16">O nome do ícone colado no campo Icon.</span>

<span class="c0"> </span>

|                                                                                                                                                                                                                                                                            |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c4">Copie o nome exatamente como aparece: </span><span class="c32 c90 c13 c36">os nomes do Google Icons usam letras minúsculas e sublinhados, como location\_on ou warning. Qualquer variação impede o ícone de carregar, e a legenda aparece sem ele.</span> |

<span class="c0"> </span>

<span class="c0">Ainda na configuração da legenda, é possível escolher a
cor do ícone e indicar se ele será exibido preenchido ou apenas
contornado.</span>

<span class="c0"></span>

### <span class="c28 c92">Incorporação de vídeos externos</span>

<span class="c1">Você consegue incorporar um vídeo externo na Documental
através do bloco </span><span class="c28 c1">Vídeo
Embed</span><span class="c1">.</span>

<span class="c1">Primeir</span><span>o,</span><span class="c1"> navegue
até a plataforma com o vídeo que você deseja incorporar (como YouTube ou
Vimeo) e clique em </span><span class="c28 c1">Compartilhar ›
Incorporar</span><span class="c1">.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 495.00px; height: 340.00px;">![](images/image53.png)</span>

<span class="c16">Na plataforma onde o vídeo está hospedado, clique em
Compartilhar.</span>

<span class="c0"></span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 489.00px; height: 340.00px;">![](images/image55.png)</span>

<span class="c16">Em seguida, clique em Incorporar.</span>

<span class="c0"></span>

<span>  
</span><span class="c1">Ao clicar em
</span><span class="c28 c1">Incorporar</span><span class="c1">, um
quadro irá se abrir. Copie o link da caixa de texto indicada abaixo
</span><span>–</span><span class="c1"> note que ele possui "embed" no
meio da URL.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 225.00px;">![](images/image58.png)</span>

<span class="c16">Copie o link indicado – note que ele traz "embed" no
meio da URL.</span>

<span class="c0"></span>

<span>  
</span><span class="c1">Depois cole o link
em</span><span class="c28 c1"> Video URL</span><span class="c1">, dentro
do bloco</span><span class="c28 c1"> Vídeo
Embed</span><span class="c1">, e seu vídeo será incorporado à
plataforma.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 175.00px;">![](images/image59.png)</span>

<span class="c16">Cole o link no campo Video URL, dentro do bloco Vídeo
Embed.</span>

<span class="c0"></span>

-----

<span class="c0"></span>

# <span class="c20 c95">5. Publicando uma história</span>

<span class="c1">A plataforma da Documental foi montada pensando em que
os usuários conseguissem, de forma fácil e gratuita, publicar suas
páginas através do </span><span class="c28 c1">GitHub
Pages</span><span class="c0">. Mas, se você for um usuário avançado,
também pode hospedar a página num servidor privado.</span>

<span>Ao terminar de editar sua geohistória, clique em "publicar", no
canto direito superior da tela para salvar e sincronizar o conteúdo no
seu repositório GitHub. Se você deixou o GitHub Pages ativado, sua
história será publicada automaticamente como
</span><span>um</span><span> site
</span><span>acessível</span><span> pelo seu repositório GitHub. Caso
não esteja ativado, siga abaixo os passos para publicar sua história
manualmente através do GitHub Pages.</span><span class="c0"> </span>

<span>Feito isso, sua história está publicada em seu repositório\! O
formato do seu endereço URL ou domínio será algo como
\<seu\_usuário\>.</span><span class="c76">[github.io/](https://www.google.com/url?q=http://github.io/&sa=D&source=editors&ust=1786675075571275&usg=AOvVaw2dWzIB0q9DJmGjAplDJ3IQ)</span><span class="c0">\<seu\_repositório\>
, e você pode divulgar esse link para compartilhar seu projeto. </span>

<span>Para ter um
</span><span>domínio</span><span class="c0"> personalizado, é
necessário ter a assinatura de um plano pago do GitHub ou configurar
uma integração com um serviço de hospedagem próprio.  </span>

<span class="c0">Sempre que uma história é publicada pela Documental,
pedimos que seja mencionada a frase abaixo, como forma de apoiar o
desenvolvimento da plataforma:</span>

<span class="c12">powered by Documental.xyz</span>

## <span class="c2">5.1 GitHub Pages</span>

<span class="c1">O </span><span class="c1">[GitHub
Pages](https://www.google.com/url?q=https://docs.github.com/pt/pages/getting-started-with-github-pages/what-is-github-pages&sa=D&source=editors&ust=1786675075573200&usg=AOvVaw3RCw-35uGznhGyr07JloYq)</span><span class="c1"> é
um serviço de hospedagem de sites estáticos que utiliza os arquivos de
um repositório no GitHub (como HTML, CSS e JavaScript) para publicar um
site. É possível publicar um site vinculado ao nome de uma conta, de uma
organização, ou vinculado a uma subpasta de uma conta ou
organização.</span>

<span class="c1">Por padrão, o endereço do site reproduz o nome da
conta, da organização ou da subpasta escolhida, mas é possível
configurar um </span><span class="c1">[domínio personalizado para o
site](https://www.google.com/url?q=https://docs.github.com/pt/pages/configuring-a-custom-domain-for-your-github-pages-site&sa=D&source=editors&ust=1786675075574632&usg=AOvVaw2ccYRR40sgdtX7KSfdDcFw)</span><span class="c1">.</span>

|                                                                                                                                                                                                                                                                                                                                                                |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c4">Talvez você já tenha feito isso: </span><span class="c32 c90 c13 c36">se você deixou a chave "Ativar GitHub Pages" ligada ao criar o ambiente de trabalho (seção 2.3) no aplicativo, a publicação já está configurada e você pode pular os passos abaixo. Eles servem para quem desligou a opção, ou para conferir se está tudo certo.</span> |

<span class="c0"> </span>

<span class="c1">Para publicar uma página através do GitHub Pages,
</span><span>em sua conta do Github, </span><span class="c1">vá até a
aba </span><span class="c28 c1">Repositórios</span><span class="c1"> e
clique no repositório com o site que você deseja publicar.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 285.00px;">![](images/image62.png)</span>

<span class="c16">Na aba Repositórios da sua conta, clique no
repositório do site que você deseja publicar.</span>

<span class="c0"></span>

<span class="c1">Clique em
</span><span class="c28 c1">Settings</span><span class="c1">. No menu
lateral esquerdo, clique em
</span><span class="c28 c1">Pages</span><span class="c1">.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 575.00px; height: 340.00px;">![](images/image64.png)</span>

<span class="c16">Em Settings, clique em Pages no menu lateral esquerdo.
Na seção Build and deployment, selecione GitHub Actions.</span>

<span class="c0"></span>

<span class="c1">Na seção </span><span class="c28 c1">Build and
deployment</span><span class="c1">, em
</span><span class="c28 c1">Source</span><span class="c1">, selecione
</span><span class="c28 c1">GitHub Actions</span><span class="c1">. A
página do GitHub vai atualizar e o link do seu site vai
aparecer.</span><span class="c0">  
</span>

|                                                                                                                                                                                                                                             |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="c4">A publicação leva alguns minutos: </span><span class="c13">depois de configurado, o GitHub monta o site automaticamente a cada envio de alterações. Você pode acompanhar o andamento na aba Actions do repositório.</span> |

<span class="c0"></span>

## <span class="c2">5.2 Servidor próprio</span>

<span class="c1">Se você for um usuário avançado, pode usar o seu
próprio servidor para hospedar a Documental, seguindo os passos
deste</span><span> </span><span class="c76 c1">[manual
técnico](https://www.google.com/url?q=https://github.com/thiagopaixao/astro_sveltia/blob/main/docs/DEPLOY-ACTIONS_pt-br.md&sa=D&source=editors&ust=1786675075581338&usg=AOvVaw24qzy7YdvqtEjrDqgJ_7G-)</span><span class="c1">.
Esse manual também possui informações avançadas sobre publicação através
do GitHub Pages.</span>

<span class="c1">Como o site gerado é estático, o servidor não precisa
de banco de dados nem de linguagem de programação rodando: basta um
servidor web comum servindo arquivos.</span>

## <span class="c2">5.3 Site da Documental</span>

<span class="c1">Você também pode </span><span>propor uma colaboração e
submeter</span><span class="c1"> a sua história para ser publicada no
site oficial da
</span><span class="c1">[Documental](https://www.google.com/url?q=https://documental.xyz/&sa=D&source=editors&ust=1786675075583322&usg=AOvVaw2EHMo5HX5cs9e5KTQUcWJv)</span><span>.
Para entrar em contato, envie </span><span class="c1">um e-mail para a
</span><span>a</span><span class="c1">[gência](https://www.google.com/url?q=https://www.advocacia.autonoma.xyz/&sa=D&source=editors&ust=1786675075583793&usg=AOvVaw2a0Nat80IHBvoePczkbnnw)
</span><span>[a](https://www.google.com/url?q=https://www.advocacia.autonoma.xyz/&sa=D&source=editors&ust=1786675075583962&usg=AOvVaw0POwerbcW5ytNNQ7xYYxIE)</span><span class="c1">[utônoma](https://www.google.com/url?q=https://www.advocacia.autonoma.xyz/&sa=D&source=editors&ust=1786675075584131&usg=AOvVaw1xlEvioizLSmGT1WZkPoyz)</span><span> em
</span><span>autonoma@autonoma.xyz.</span><sup>[\[ag\]](#cmnt33)</sup>

-----

<span class="c0"></span>

# <span class="c20 c95">6. Técnicas de scrollytelling</span>

## <span class="c2">6.1 O que é scrollytelling?</span>

<span class="c1">Baseado nos termos
</span><span class="c38 c1">scroll</span><span class="c1"> (rolagem) e
</span><span class="c38 c1">storytelling</span><span class="c1"> (contação
de histórias), scrollytelling designa recursos utilizados em páginas web
onde a rolagem de tela controla a narrativa. Esta prática ganhou
destaque inicial em publicações online do chamado
</span><span class="c38 c1">long form
journalism</span><span class="c1">, ou jornalismo de forma longa. Porém,
os mesmos esquemas narrativos e tecnologias também podem ser utilizados
de forma mais ampla.</span>

<span class="c1">A rolagem de tela é uma das formas mais intuitivas de
experiência do usuário durante a utilização de dispositivos eletrônicos,
sejam eles tablets, computadores desktop ou celulares. Mesmo pessoas
leigas ou crianças pequenas são capazes de reproduzir este gesto. Com o
scrollytelling, este ato simples pode controlar a aparição de textos,
fotos, vídeos ou a navegação por um mapa, como
</span><span class="c1">implementa</span><span class="c1"> a Documental,
além de outras possibilidades, como a transição entre diferentes formas
de visualizar dados sobre um mesmo tema.</span>

## <span class="c2">6.2 Métodos de scrollytelling</span>

<span class="c1">Em seu artigo
</span><span class="c76 c38 c1">[Responsive scrollytelling best
practices](https://www.google.com/url?q=https://pudding.cool/process/responsive-scrollytelling/&sa=D&source=editors&ust=1786675075589178&usg=AOvVaw0_sFO7U_kxgZ56PpTdfd6O)</span><span class="c1">,
publicado no The Pudding, Russell Goldenberg destaca duas abordagens
principais para narrativas com scrollytelling. Uma delas é simplesmente
empilhar textos, imagens, cartografias ou gráficos diversos. A outra
consiste na rolagem de elementos sobre um fundo, em geral uma
visualização de dados ou um mapa. No artigo, Goldenberg cita ainda
outras abordagens possíveis, como usar o clique ou a função de deslizar,
mas não as recomenda.</span>

<span class="c1">A Documental é uma solução que permite trabalhar com
estas duas abordagens. É possível inclusive mesclar ambas, alternando
rolagem sobre um fundo (no caso, um mapa, representado pelo bloco
Mapa</span><span>,</span><span class="c1"> e seções com textos ou
imagens fixas, empilhadas</span><span>, </span><span class="c1">como o
bloco Duas Colunas</span><span> (ver seção </span><span class="c28">4.8
Biblioteca de blocos</span><span class="c0">)</span>

## <span class="c2">6.3 Textos e narrativas</span>

<span class="c1">Em artigo sobre design cartográfico como forma de
storytelling visual, Robert E. Roth recomenda que sejam selecionados
elementos para garantir uma linearidade durante a narrativa. Ele
menciona a estrutura em três atos como a abordagem mais tradicional e
também cita a tipologia proposta por </span><span class="c1">Phillips
(2012),</span><span class="c1"> com oito arcos narrativos comumente
utilizados nas geociências e na geografia.</span>

<span class="c1">A narrativa clássica, em três atos, é baseada em três
etapas: set-up ou introdução, conflito e resolução. Ao longo deste
processo, são apresentados personagens (que podem ser pessoas, mas
também regiões geográficas, por exemplo), informações contextuais sobre
um problema e outras informações.</span>

<span class="c1">No início da narrativa, em geral, apresentam-se os
personagens, ambientes e o contexto do problema em questão. Para
scrollytelling baseado em mapas, é especialmente importante determinar
uma ou mais localidades (onde?) e temporalidades (quando?). Também se
recomenda a inserção de uma "isca" (teaser) para capturar a atenção da
pessoa leitora e gerar interesse na narrativa.</span>

<span class="c1">No segundo ato, o conflito, Roth enfatiza a criação
incremental de uma tensão e o desenvolvimento dos personagens, a fim de
gerar maior interesse da audiência. Ele sugere a criação de "pontos
narrativos", que podem ser pontos distintos em um mesmo mapa ou uma
sequência de mapas e gráficos, para construir pausas e ritmos dentro de
uma narrativa linear.</span>

<span class="c1">O pesquisador destaca os oito arcos narrativos
identificados por Phillips (2012) para narrativas baseadas em mapas.
Eles se dividem em dois grupos. Quatro destes arcos são baseados em um
único protagonista (um local ou região, onde o conflito surge de forças
internas ou externas): a destruição, a gênese, a emergência e a
metamorfose. Os outros quatro baseiam-se no conflito entre duas ou mais
forças ou personagens, que pode resultar em uma nova situação: causa e
efeito, convergência, divergência e oscilação.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 359.00px; height: 380.00px;">![](images/image45.png)</span>

<span class="c39 c38">Reprodução da "Figura 1" do artigo Cartographic
Design as Visual Storytelling: Synthesis and Review of Map-Based
Narratives, Genres, and Tropes.</span>

<span class="c1">Por fim, na resolução
</span><span>–</span><span class="c1"> o ato final da estrutura
narrativa em três etapas </span><span>–</span><span class="c1"> chega-se
ao clímax. Esta conclusão pode se dar tanto com a convergência dos
personagens, problemas e ambientações criadas por uma determinada
solução, quanto deixando a cargo da audiência preencher as lacunas de
sentido com suas próprias experiências.</span>

<span class="c1">Como Roth destaca, muitos profissionais consideram este
esquema simplificado demais e adotam estruturas não lineares ou
paralelas para contar histórias. De todo modo, estes elementos e
estruturas básicas podem estimular novas práticas e abordagens para
contar histórias com mapas.</span>

## <span class="c2">6.4 Definição da camada base</span>

<span class="c1">A camada base serve como a principal camada de
localização espacial, a partir da qual serão posicionadas outras
camadas de informações ou dados. Esta camada base pode ser uma imagem de
satélite ou marcações vetoriais.</span>

<span class="c1">No primeiro caso, temos um efeito mais realista, que
visa transmitir a sensação de deslocamento em um espaço real. As imagens
de satélite como camada base também permitem que objetos e entidades
</span><span>–</span><span class="c1"> prédios, marcas de desmatamento
ou cidades, por exemplo </span><span>–</span><span class="c1"> apareçam
no mapa "tal como" são na realidade.</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 228.00px;">![](images/image27.png)</span>

<span class="c38 c39">Base com imagem de satélite.</span>

<span class="c1">Por outro lado, um mapa base vetorial abstrai qualquer
informação visual desnecessária para representar apenas alguns
elementos. Deste modo, esta abordagem é muitas vezes utilizada para
visualizações de dados geográficos, uma vez que com a camada vetorial
podemos escolher o que será exibido (como fronteiras, nomes de rua e
assim por diante).</span>

<span style="overflow: hidden; display: inline-block; margin: 0.00px 0.00px; border: 0.00px solid #000000; transform: rotate(0.00rad) translateZ(0px); -webkit-transform: rotate(0.00rad) translateZ(0px); width: 600.00px; height: 228.00px;">![](images/image28.png)</span>

<span class="c39 c38">Base com camada vetorial.</span>

## <span class="c2">6.5 Movimentos de câmera sobre mapas</span>

### <span class="c124 c28">Aproximar ou afastar (zoom in/out)</span>

<span class="c1">O movimento de aproximar ou afastar a visão sobre o
mapa ajuda as narrativas a alternarem entre uma dimensão "macro" (uma
visão mais ampla para situar geograficamente o leitor, ou um mapa
coroplético, por exemp</span><span>lo</span><span class="c1">) e
"micro" (pontos no mapa relacionados a fotos, ou uma subdivisão como os
municípios dentro de um estado).</span>

<span class="c1">O movimento de zoom in pode ser uma estratégia para
abordar algo mais específico depois de tratar questões mais gerais
(dedução), enquanto o contrário, zoom out, permite generalizar
(indução) ou contrapor uma experiência específica com uma visão mais
ampla. Este efeito é obtido criando dois blocos
</span><span class="c28 c1">Map</span><span class="c1"> em que o
sucessor tem um valor de zoom diferente do anterior.</span>

### <span class="c124 c28">Panorâmica (panning)</span>

<span class="c1">Este movimento permite "passear" por um mapa. É útil
para detalhar trajetórias ou tratar de uma sequência de acontecimentos e
localizações relevantes para a narrativa. Pode ser alcançado usando
diferentes coordenadas geográficas para latitude e longitude em
diferentes blocos
</span><span class="c1 c28">Map</span><span class="c1">.</span>

### <span class="c124 c28">Bearing e pitch</span>

<span class="c1">O Mapbox oferece </span><span class="c28 c1">opções de
controle de câmera</span><span class="c1"> (ver
</span><span class="c28 c1">seç</span><span class="c28">ão 4. Criando
uma história</span><span>) </span><span class="c1">que permitem também
ajustar a rotação e a posição do observador em relação ao mapa. Este
recurso dá a impressão de uma navegação em três dimensões e é útil para
reproduzir uma determinada perspectiva no mapa
</span><span>–</span><span class="c1"> a de uma fotografia, por
exemplo.</span>

### <span class="c124 c28">Sobreposição de imagens</span>

<span class="c1">A Documental também dá suporte a comparações de imagens
no estilo antes/depois. Este recurso é útil especialmente para mostrar
transformações temporais em um dado território, permitindo ao visitante
comparar facilmente duas imagens. Neste caso, os mapas devem ser salvos
como imagens e enviados usando o bloco
</span><span class="c28 c1">Comparativo de Imagens
</span><span class="c1">(</span><span class="c1">ver
</span><span class="c28 c1">seç</span><span class="c28">ão
4.8</span><span class="c28"> Biblioteca de
Blocos)</span><span class="c28 c1">.</span>

## <span class="c2">6.6 Outras plataformas e bibliotecas</span>

<span class="c1">Até o momento, não existem muitas opções gratuitas de
plataformas que forneçam uma interface gráfica para a construção de
narrativas com scrollytelling. A alternativa mais conhecida é o
</span><span class="c76 c1">[Flourish.Studio](https://www.google.com/url?q=https://help.flourish.studio/article/21-controlling-stories-with-scrollytelling&sa=D&source=editors&ust=1786675075613348&usg=AOvVaw1wHfAQkNgh9ytDeNTh-K1Y)</span><span>,
que já publicou um artigo específico sobre este
recurso</span><span class="c1">. A Documental destaca-se por ser uma
solução de código aberto que, a partir do Sveltia e do Mapbox, fornece
uma interface gráfica para controle do scrollytelling e inclusão dos
conteúdos que formam a narrativa.</span>

<span class="c1">Existem, porém, diversas opções gratuitas ou de código
aberto disponíveis para implementar páginas com recursos de
scrollytelling "do zero". Em </span><span class="c1">[artigo de janeiro
de 2017](https://www.google.com/url?q=https://pudding.cool/process/how-to-implement-scrollytelling/&sa=D&source=editors&ust=1786675075614767&usg=AOvVaw0mPoK_AmKp4sTqAxXVUsqi)</span><span class="c1">,
Russell Goldenberg elenca seis alternativas, junto com demonstrações de
seus códigos em funcionamento. As opções abaixo estão listadas de acordo
com a contribuição mais recente feita em seus respectivos
repositórios.</span>

  - <span class="c76 c79 c1">[JEO](https://www.google.com/url?q=https://github.com/InfoAmazonia/jeo-plugin&sa=D&source=editors&ust=1786675075615851&usg=AOvVaw3in4MNNXfotKa5snwatw0l)</span><span class="c0">:
    solução para WordPress criada pelo InfoAmazônia que permite inserir
    blocos de mapa interativos no editor Gutenberg.</span>
  - <span class="c76 c79 c1">[Scrollama](https://www.google.com/url?q=https://github.com/russellgoldenberg/scrollama&sa=D&source=editors&ust=1786675075616613&usg=AOvVaw3YQWoter0v8w3GQqqFssHI)</span><span class="c0">:
    biblioteca criada por Russell Goldenberg. Conta com uma
    </span><span class="c76 c79 c1">[página com diferentes modelos
    prontos para
    uso](https://www.google.com/url?q=https://russellgoldenberg.github.io/scrollama/basic/&sa=D&source=editors&ust=1786675075617223&usg=AOvVaw2zpoolBXES1jheaDv4G-OR)</span><span class="c0">.
    É uma opção relativamente acessível, mesmo para quem tem apenas
    conhecimentos básicos de JavaScript. O
    </span><span class="c76 c79 c1">[vídeo
    tutorial](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Dd7wTA9F-l8c&sa=D&source=editors&ust=1786675075617813&usg=AOvVaw1TkaGFBPhKNvmd_-tedVEQ)</span><span class="c0">[ de
    Jonathan
    Soma](https://www.google.com/url?q=https://www.youtube.com/watch?v%3Dd7wTA9F-l8c&sa=D&source=editors&ust=1786675075618065&usg=AOvVaw131v3wgPBjgBoaQqpawB7u)</span><span class="c0"> apresenta
    um bom passo a passo.</span>
  - <span class="c76 c79 c1">[ScrollMagic](https://www.google.com/url?q=http://scrollmagic.io/&sa=D&source=editors&ust=1786675075618475&usg=AOvVaw3Lk8-8iS0JrdmbwrwN_cy_)</span><span class="c0">:
    recomendada por Goldenberg para casos que exigem bastante
    personalização da interação.</span>
  - <span class="c76 c79 c1">[ScrollStory](https://www.google.com/url?q=http://sjwilliams.github.io/scrollstory/&sa=D&source=editors&ust=1786675075619057&usg=AOvVaw0DSX2lf9B0Pd1ywV9fvukD)</span><span class="c0">:
    plugin em jQuery utilizado em algumas histórias do The New York
    Times. Recomendado para iniciantes que utilizam jQuery.</span>
  - <span class="c76 c79 c1">[graph-scroll](https://www.google.com/url?q=https://1wheel.github.io/graph-scroll/&sa=D&source=editors&ust=1786675075619818&usg=AOvVaw0a8ov24jGVsJeIwTdT-g4u)</span><span class="c0">:
    plugin baseado na biblioteca D3 que fornece recursos simples para
    scrollytelling. Recomendável especialmente para visualizações de
    dados que também façam uso de D3.</span>

<span class="c1">O artigo de Goldenberg também cita duas bibliotecas há
mais tempo inativas: o
</span><span class="c1">[Waypoints](https://www.google.com/url?q=http://imakewebthings.com/waypoints/&sa=D&source=editors&ust=1786675075620974&usg=AOvVaw2BQXIFed6rVnZURPAlkxbf)</span><span class="c1">,
cuja última atualização é de setembro de 2016, e o
</span><span class="c1">[in-view.js](https://www.google.com/url?q=https://github.com/camwiegert/in-view&sa=D&source=editors&ust=1786675075621401&usg=AOvVaw1Us94P8nz5ZugyPV4a8cxl)</span><span class="c1">,
oficialmente inativo.</span>

<span class="c1">Além das alternativas acima, há a opção de utilizar o
</span><span class="c76 c1">[Svelte](https://www.google.com/url?q=https://svelte.dev/&sa=D&source=editors&ust=1786675075622006&usg=AOvVaw1bX0G_RszHHlAaQtpwl7e8)</span><span class="c1">.
Neste caso, vale conferir o </span><span class="c1">[modelo
do](https://www.google.com/url?q=https://github.com/the-pudding/svelte-starter&sa=D&source=editors&ust=1786675075622386&usg=AOvVaw2EJdmKHJXyRdKPW3a4gzqu)
</span><span class="c76 c1">[The
Pudding](https://www.google.com/url?q=https://github.com/the-pudding/svelte-starter&sa=D&source=editors&ust=1786675075622614&usg=AOvVaw1CXqhNP9tDdxJOBP5C6eyq)</span><span class="c1">,
que conta com um componente específico para este tipo de visualização
interativa, e o </span><span class="c76 c1">[tutorial escrito por Connor
Rothschild](https://www.google.com/url?q=https://www.connorrothschild.com/post/svelte-scrollytelling&sa=D&source=editors&ust=1786675075623216&usg=AOvVaw3vFQPdB_Pc9T0ctxMHTIgs)</span><span class="c1">.</span>

-----

<span class="c0"></span>

# <span class="c20 c95">7. Problemas comuns</span>

<span class="c0"></span>

<span class="c43 c28 c47">Sintoma</span>

<span class="c43 c28 c47">Causa provável</span>

<span class="c43 c28 c47">Solução</span>

<span class="c29">O aplicativo não abre no macOS e diz que é de
"desenvolvedor não identificado"        </span>

<span class="c29">O aplicativo não tem assinatura digital paga e o
sistema bloqueia a primeira execução</span>

<span class="c29">Ajustes do Sistema › Privacidade e Segurança ›
Segurança › "Abrir mesmo assim"</span>

<span class="c43">O Windows bloqueia o instalador</span>

<span class="c43">O aplicativo não tem assinatura digital paga</span>

<span class="c43">Clique em "Mais informações" e depois em "Executar
assim mesmo"</span>

<span class="c43">O mapa aparece em branco</span>

<span class="c43">Access Token ou Map Style ausente, incorreto, ou falta
de internet</span>

<span class="c43">Confira os dois campos nas Configurações do Mapbox. O
token deve começar com pk.</span>

<span class="c43">Os filtros de layers não funcionam</span>

<span class="c43">O estilo de mapa usado é o Mapbox Standard ou você
aplicou os filtros das layers de forma errada.</span>

<span class="c43">Troque por um estilo criado do zero ou por um dos
modelos da Autônoma (</span><span class="c43 c28">seção
3.3</span><span class="c43">)</span>

<span class="c43">A página apresenta erros ou comportamento
estranho</span>

<span class="c43">IDs, títulos ou links duplicados entre histórias ou
entre vistas</span>

<span class="c43">Verifique se todos os IDs de blocos e de vistas são
únicos, sem espaços ou caracteres especiais</span>

<span class="c43">O site não aparece depois de publicar</span>

<span class="c43">A publicação leva alguns minutos, ou o GitHub Pages
não foi configurado</span>

<span class="c43">Aguarde e confira Settings › Pages e a aba Actions do
repositório</span>

<span class="c43">A publicação falhou (marca vermelha na aba
Actions)</span>

<span class="c43">Erro na construção do site</span>

<span class="c43">Abra a execução na aba Actions e leia a mensagem de
erro</span>

<span class="c43">As imagens não aparecem no site publicado</span>

<span class="c43">Arquivos de mídia não foram enviados</span>

<span class="c43">Verifique se as imagens estão no repositório de
arquivos da Documental e foram incluídas no envio</span>

<span class="c43">O mapa fica lento, sobretudo no celular</span>

<span class="c43">Camadas demais ou dados geográficos muito
pesados</span>

<span class="c43">Reduza o número de camadas e simplifique a geometria
dos dados no QGIS antes de subir ao Mapbox</span>

<span class="c43">O zoom fica bom no computador mas ruim no
celular</span>

<span class="c43">O zoom foi ajustado apenas para desktop</span>

<span class="c43">Verifique e ajuste um zoom apropriado para mobile e
tablet em cada vista</span>

-----

<span class="c0"></span>

# <span class="c20 c95">8. Como colaborar</span><span class="c20 c95"> </span>

<span class="c1">Para colaborar com o código da Documental, use o
repositório:
</span><span class="c76 c1">[github.com/Documental-XYZ/](https://www.google.com/url?q=http://github.com/Plataforma-Documental-XYZ/Documental-2.0&sa=D&source=editors&ust=1786675075642661&usg=AOvVaw3QNJ12dbI9mlts7EBAT8S0)</span><span class="c76">[Core](https://www.google.com/url?q=http://github.com/Plataforma-Documental-XYZ/Documental-2.0&sa=D&source=editors&ust=1786675075642952&usg=AOvVaw1enGIxtHpbDaQhA031-FEm)</span>

<span class="c1">Para colaborar ou aperfeiçoar nossa documentação, use o
repositório:
</span><span class="c76">[github.com/Documental-XYZ/](https://www.google.com/url?q=http://github.com/Plataforma-Documental-XYZ/Documental-2.0&sa=D&source=editors&ust=1786675075643631&usg=AOvVaw1DS__9Zq-VAboBomLQVx-3)</span><span class="c76">[Docs](https://www.google.com/url?q=http://github.com/medialabufrj/documental_docs&sa=D&source=editors&ust=1786675075643837&usg=AOvVaw3GbR43HtMpSmOTeWiUmLPO)</span>

<span class="c0"></span>

<span class="c1">Caso tenha uma sugestão de melhoria no código ou na
documentação, use a função de </span><span class="c38 c1">pull
request</span><span class="c1"> para enviar sua proposta. Caso queira
compartilhar novas sugestões ou comentários em geral sobre a plataforma,
você também pode abrir uma
</span><span class="c38 c1">issue</span><span class="c1">.</span>

## <span class="c2">Como creditar o projeto</span>

<span class="c1">Solicitamos que projetos que façam uso da plataforma
incluam a seguinte menção, como forma de apoiar o desenvolvimento da
plataforma:</span>

<span class="c12">powered by Documental.xyz</span>

# <span class="c20 c95">9. Referências e recursos</span>

  - <span class="c76 c79 c1">[GitHub
    Docs](https://www.google.com/url?q=https://docs.github.com/pt&sa=D&source=editors&ust=1786675075646562&usg=AOvVaw3xhV4PT48CIGFU6LZu6k51)</span><span class="c0"> </span><span>–</span><span class="c0"> documentação
    técnica do GitHub</span>
  - <span class="c76 c79 c1">[Mapbox
    Docs](https://www.google.com/url?q=https://docs.mapbox.com/&sa=D&source=editors&ust=1786675075647068&usg=AOvVaw0kyLH4g4oI0aZAmSy9J9u1)</span><span class="c0"> </span><span>–</span><span class="c0"> documentação
    técnica do Mapbox</span>
  - <span class="c76 c79 c1">[Manual
    técnico](https://www.google.com/url?q=https://github.com/thiagopaixao/astro_sveltia/blob/main/docs/DEPLOY-ACTIONS_pt-br.md&sa=D&source=editors&ust=1786675075647544&usg=AOvVaw2n7kACwBN8P6Tz_xBq65rk)</span><span class="c0"> </span><span>–</span><span class="c0"> hospedagem
    da Documental em servidor privado e no GitHub Pages</span>
  - <span class="c76 c1 c79">[Geodados: uma introdução
    gentil](https://www.google.com/url?q=https://gis.escoladedados.org&sa=D&source=editors&ust=1786675075648142&usg=AOvVaw37XJ7jw9Jnk66-Vv8SyTE6)
    </span><span class="c0">— ebook da Escola de Dados sobre geodados e
    QGIS</span>

<span class="c0"></span>

<span class="c1">Roth, Robert E. (2020). Cartographic Design as Visual
Storytelling: Synthesis and Review of Map-Based Narratives, Genres, and
Tropes. The Cartographic Journal. DOI:
10.1080/00087041.2019.1633103</span>

<span class="c1">Phillips, J. (2012). Storytelling in Earth Sciences:
The Eight Basic Plots. Earth-Science Reviews, 115(3), pp. 153–162. DOI:
10.1016/j.earscirev.2012.09.005</span>

# <span class="c20 c95">10. Equipe</span>

## <span class="c2">Agência Autônoma</span>

  - <span class="c0">Paulo Tavares
    </span><span>–</span><span class="c0"> dire</span><span>ção</span>
  - <span class="c0">Paula Marujo
    </span><span>–</span><span class="c0"> coordenação</span>
  - <span class="c0">Julia Veras
    </span><span>–</span><span class="c0"> implementação </span>

## <span class="c2">MediaLab UFRJ</span>

  - <span class="c0">Fernanda Bruno
    </span><span>–</span><span class="c0"> direção</span>
  - <span class="c0">Adriano Belisario </span><span>–
    </span><span class="c0">implementação e
    documentação</span><sup>[\[ah\]](#cmnt34)</sup>

## <span class="c2">Desenvolvimento de software</span>

<span class="c28 c1">Documental 2.0:</span>

  - <span class="c0">Thiago Paixão
    </span><span>–</span><span class="c0"> back-end</span>
  - <span class="c0">Atonal </span><span>–
    </span><span class="c0">front-end</span>

<span class="c24 c1">Documental 1.0:</span>

  - <span class="c0">[Marlus
    Araújo](https://www.google.com/url?q=https://github.com/sulram&sa=D&source=editors&ust=1786675075651475&usg=AOvVaw10EcfCuZ8RBlvLnLQHXtFO)</span>
  - <span class="c0">[Rafael
    Bantu](https://www.google.com/url?q=https://github.com/rafaelbantu&sa=D&source=editors&ust=1786675075651695&usg=AOvVaw30lSPubdCyf2UUBgYtImA6)</span><span class="c0"> </span><span>–</span><span class="c0"> atualização
    e publicação do starter kit em código
    aberto</span><sup>[\[ai\]](#cmnt35)</sup>

## <span class="c2">Apoio</span>

  - <span class="c0">Fundação Ford</span>
  - <span class="c0">Fundação Carlos Chagas Filho de Amparo à Pesquisa
    do Estado do Rio de Janeiro
    (FAPERJ)</span><sup>[\[aj\]](#cmnt36)</sup>

<span class="c0"></span>

<span class="c1">[documental.xyz](https://www.google.com/url?q=https://documental.xyz&sa=D&source=editors&ust=1786675075652808&usg=AOvVaw16NPczsdX4kzAzSbn012eI)</span><span class="c1"> 
 ·   </span><span>a</span><span class="c1">gência
</span><span>a</span><span class="c1">utônoma:
</span><span class="c76">[advocacia.autonoma.xyz](https://www.google.com/url?q=https://www.advocacia.autonoma.xyz/&sa=D&source=editors&ust=1786675075653178&usg=AOvVaw0UBGZZm4QrP47ODlgLIP54)</span><span> 
</span><span class="c76 c1">[@aautonoma](https://www.google.com/url?q=https://www.instagram.com/aautonoma/&sa=D&source=editors&ust=1786675075653449&usg=AOvVaw0FTTXIQm1ir_MgA5XYp1mK)</span><span class="c1"> ·
</span><span> </span><span class="c1">MediaLab UFRJ:
</span><span class="c1">[medialabufrj.net](https://www.google.com/url?q=https://medialabufrj.net&sa=D&source=editors&ust=1786675075653885&usg=AOvVaw0Xi9hQQX9Pr530xI6OSPIA)</span><span> 
</span><span class="c76">[@medialabufrj](https://www.google.com/url?q=https://www.instagram.com/medialabufrj/&sa=D&source=editors&ust=1786675075654164&usg=AOvVaw2FmCQY5nhwlF-wh9aOghfl)</span>

<span class="c0"></span>

<div>

<span class="c175 c216">Documental — Guia de instalação e uso   ·  
</span>

</div>

<div class="c54">

[\[a\]](#cmnt_ref1)<span class="c65 c1 c36">definir um email</span>

</div>

<div class="c54">

[\[b\]](#cmnt_ref2)<span class="c65 c1 c36">documental@autonoma.xyz
?</span>

</div>

<div class="c54">

[\[c\]](#cmnt_ref3)<span class="c65 c1 c36">substituir imagem</span>

</div>

<div class="c54">

[\[d\]](#cmnt_ref4)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[e\]](#cmnt_ref5)<span class="c65 c1 c36">incluir prints</span>

</div>

<div class="c54">

[\[f\]](#cmnt_ref6)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[g\]](#cmnt_ref7)<span class="c65 c1 c36">substituir para página nova
em que está "criar novo ambiente de trabalho"
@thiago.apaixao@gmail.com</span>

<span class="c65 c1 c36">\_Atribuído a thiago.apaixao@gmail.com\_</span>

</div>

<div class="c54">

[\[h\]](#cmnt_ref8)<span class="c65 c1 c36">trocar, não vai mais ter
fork</span>

</div>

<div class="c54">

[\[i\]](#cmnt_ref9)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[j\]](#cmnt_ref10)<span class="c65 c1 c36">atualizar print</span>

</div>

<div class="c54">

[\[k\]](#cmnt_ref11)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[l\]](#cmnt_ref12)<span class="c65 c1 c36">inserir print página boas
vindas @thiago.apaixao@gmail.com</span>

<span class="c65 c1 c36">\_Atribuído a thiago.apaixao@gmail.com\_</span>

</div>

<div class="c54">

[\[m\]](#cmnt_ref13)<span class="c65 c1 c36">inserir os prints ref. a
cada modo de visualização:  ambiente de trabalho, sveltia, tela
dividida</span>

</div>

<div class="c54">

[\[n\]](#cmnt_ref14)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[o\]](#cmnt_ref15)<span class="c65 c1 c36">incluir esse print do
app</span>

</div>

<div class="c54">

[\[p\]](#cmnt_ref16)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[q\]](#cmnt_ref17)<span class="c65 c1 c36">print</span>

</div>

<div class="c54">

[\[r\]](#cmnt_ref18)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[s\]](#cmnt_ref19)<span class="c65 c1 c36">inserir print
@thiago.apaixao@gmail.com</span>

<span class="c65 c1 c36">\_Atribuído a thiago.apaixao@gmail.com\_</span>

</div>

<div class="c54">

[\[t\]](#cmnt_ref20)<span class="c65 c1 c36">lat e long já aparecem
aqui</span>

</div>

<div class="c54">

[\[u\]](#cmnt_ref21)<span class="c65 c1 c36">não entendi</span>

</div>

<div class="c54">

[\[v\]](#cmnt_ref22)<span class="c65 c1 c36">é esse o print certo? nao
precisa ter a lat long?</span>

</div>

<div class="c54">

[\[w\]](#cmnt_ref23)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[x\]](#cmnt_ref24)<span class="c65 c1 c36">substituir com page include
@thiago.apaixao@gmail.com</span>

<span class="c65 c1 c36">\_Atribuído a thiago.apaixao@gmail.com\_</span>

</div>

<div class="c54">

[\[y\]](#cmnt_ref25)<span class="c1 c36 c65">usar exemplos concretos -
landing page?</span>

</div>

<div class="c54">

[\[z\]](#cmnt_ref26)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[aa\]](#cmnt_ref27)<span class="c65 c1 c36">não da pra entender muito
bem esse exemplo</span>

</div>

<div class="c54">

[\[ab\]](#cmnt_ref28)<span class="c65 c1 c36">seria bom um exemplo com
fotos</span>

</div>

<div class="c54">

[\[ac\]](#cmnt_ref29)<span class="c65 c1 c36">@jcgveras@gmail.com
@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[ad\]](#cmnt_ref30)<span class="c65 c1 c36">imagem de exemplo?
@jcgveras@gmail.com @thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[ae\]](#cmnt_ref31)<span class="c65 c1 c36">inserir captura de
tela</span>

</div>

<div class="c54">

[\[af\]](#cmnt_ref32)<span class="c65 c1 c36">@thiago.apaixao@gmail.com</span>

</div>

<div class="c54">

[\[ag\]](#cmnt_ref33)<span class="c65 c1 c36">deixamos assim?</span>

</div>

<div class="c54">

[\[ah\]](#cmnt_ref34)<span class="c65 c1 c36">como creditar?</span>

</div>

<div class="c54">

[\[ai\]](#cmnt_ref35)<span class="c65 c1 c36">fizeram a 1.0, como
creditar?</span>

</div>

<div class="c54">

[\[aj\]](#cmnt_ref36)<span class="c65 c1 c36">mantém?</span>

</div>
