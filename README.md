# Projeto Coffe Bernally

## Integrantes da dupla
- Gabrielly Santos Vieira
- Bernado Tavares

## Descrição do caso escolhido
O caso escolhido foi a Coffee Bernally, uma cafeteria que oferece cafés, bebidas especiais, salgados e sobremesas em um ambiente acolhedor e tranquilo. O diferencial do estabelecimento está na presença de gatos no espaço, proporcionando conforto e uma experiência agradável aos clientes. A proposta da cafeteria é criar um ambiente relaxante, onde as pessoas possam apreciar produtos de qualidade enquanto desfrutam de momentos de descanso, estudo, trabalho ou lazer na companhia dos gatos.

## Necessidade identificada
O estabelecimento precisa de um site para explicar claramente a sua dinâmica de funcionamento.Além de centralizar informações básicas como o cardápio e a forma de contato em uma plataforma profissional que passe credibilidade e evite mal-entendidos sobre a proposta do espaço.

## Público-alvo
O público é formado por frequentadores assíduos de cafeterias, profissionais em home office e estudantes que buscam um lugar calmo, e pessoas que encontram na proximidade com animais uma forma de aliviar o estresse da rotina.

## Objetivo do site
O objetivo central do site é atrair o público em geral e fazê-los visitar o espaço físico, gerando interesse através da combinação entre um cardápio atraente e o diferencial da presença dos gatos. O site deve funcionar como o cartão de visitas digital que valida a qualidade da cafeteria e prepara o cliente para a experiência presencial.

## Processo de desenvolvimento
O desenvolvimento do projeto foi realizado em etapas, permitindo nós organizasse melhor as atividades e acompanhasse a evolução do site. Inicialmente foi realizado um levantamento das necessidades da cafeteria e definido o público-alvo, servindo como base para a estrutura do projeto.

Em seguida foi criada a estrutura em HTML, organizando as principais seções da página, como apresentação, cardápio e contato. Após essa etapa, foi desenvolvida a estilização utilizando CSS, buscando transmitir uma identidade visual aconchegante por meio de cores em tons de marrom, tipografia agradável e imagens de alta qualidade.

Posteriormente foram adicionados recursos de responsividade para garantir uma boa experiência em diferentes tamanhos de tela e implementada uma funcionalidade em JavaScript para tornar o cardápio mais interativo. Durante o desenvolvimento ocorreram diversas melhorias em relação à ideia inicial, principalmente na organização do conteúdo, na escolha das imagens, no layout dos cards do cardápio e na experiência do usuário durante a navegação.

## Principais decisões do projeto
Durante o desenvolvimento, algumas decisões precisaram ser revistas até chegarmos ao resultado final. Uma das principais foi a escolha de onde aplicar o JavaScript. Inicialmente pensamos em utilizá-lo em outras partes do site, mas percebemos que a melhor opção seria no cardápio, permitindo que o usuário exibisse ou ocultasse os ingredientes de cada produto. Essa escolha tornou a navegação mais organizada e interativa.

Outra decisão importante foi a identidade visual. No início, a ideia era utilizar uma paleta de cores mais clara, porém optamos por tons de marrom e bege por transmitirem aconchego e estarem mais associados ao universo das cafeterias. Também houve cuidado na escolha das imagens, priorizando fotos de cafés, bebidas, alimentos e gatos que representassem fielmente a proposta da Coffee Bernally e proporcionassem uma experiência visual mais atrativa ao visitante.

Outra decisão importante foi tornar a presença dos gatos o principal diferencial da cafeteria. Inicialmente, seria apenas uma cafeteria comum, mas percebemos que incluir os gatos tornaria o ambiente mais acolhedor e faria o estabelecimento se destacar dos demais. Essa escolha influenciou os textos, as imagens e toda a identidade do site.

## Funcionalidade em JavaScript
A funcionalidade implementada em JavaScript foi a exibição e ocultação dos ingredientes dos produtos do cardápio. Ela está presente na seção "Nosso Cardápio", onde cada card possui um botão "Quero esse!".

O funcionamento ocorre por meio da função "toggleInfo()", acionada pelo evento "onclick" do botão. Ao ser executada, a função utiliza a propriedade "nextElementSibling" e acessar o elemento "<p>" que contém os ingredientes do produto. Em seguida, verifica o valor da propriedade "style.display". Se o elemento estiver visível "(display: block)", a função altera seu estado para oculto "(display: none)" e redefine o texto do botão para "Quero esse!". Caso contrário, modifica o valor para "display: block", exibindo as informações, e atualiza o texto do botão para "Ocultar ingredientes".

Essa funcionalidade foi escolhida por melhorar a experiência do usuário, permitindo que informações adicionais sejam exibidas somente quando solicitadas. Assim, o cardápio permanece organizado, reduz a quantidade de informações visíveis simultaneamente e torna a navegação mais intuitiva e agradável.


## Uso de Bootstrap
No desenvolvimento do projeto foi utilizado o Bootstrap para a estilização dos botões. A classe de botão serviu como base para criar elementos responsivos e com boa usabilidade, enquanto o CSS personalizado foi utilizado para adaptar as cores, o formato arredondado e os efeitos visuais à identidade da cafeteria Coffee Bernally. A escolha do Bootstrap foi adequada porque agilizou o desenvolvimento, garantiu compatibilidade entre diferentes navegadores e facilitou a criação de uma interface moderna e intuitiva para o usuário.

## Testes realizados
Foram realizados diversos testes para verificar o funcionamento correto do site. A responsividade foi testada utilizando as ferramentas de desenvolvedor do navegador, testando diferentes resoluções de tela para garantir que os elementos permanecessem reponsivos e organizados em computadores, tablets e celulares.

Também foram verificados todos os links de navegação para confirmar que direcionavam corretamente para as respectivas seções da página. As imagens foram analisadas para garantir seu carregamento e qualidade visual em diferentes dispositivos.

A funcionalidade em JavaScript foi testada repetidamente para assegurar que os botões exibissem e ocultassem corretamente os ingredientes de cada produto, além de alterar o texto conforme o prato que o usuário selecionasse.

## Links
- Link do repositório:
- Link do site publicado:

## Contribuição dos integrantes
Descreva objetivamente o que cada integrante realizou no projeto.
