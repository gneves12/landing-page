# landing-page
Oi, gente!
Meu nome é Gabriel, sou acadêmico de Sistemas de Informação e essa página é um projeto prático simples de um site. Fiquem à vontade para aperfeiçoar se quiserem!
Aqui, vou explicar o que foi feito no meu trabalho de Desenv. Web:
	Inicialmente, coloquei o clássico cabeçalho que deve ter em absolutamente TODO projeto que envolver HTML:
	Defini o estilo de caracteres (UTF-8). Logo após, defini, ainda no meta, um comando com o objetivo de tornar o projeto do site responsivo de acordo com cada tela em que for exibido.
	Coloquei o título do projeto, que é "landing page" e, logo após, chamei o CSS para o código.
	Já no body, iniciei criando a primeira div e também um nav com o objetivo de trabalhar com o menu já no início da página.
	Meu projeto foi feito de forma sucinta, de forma a não necessitar que outras páginas fossem criadas a cada tópico. 
	Após a criação da primeira div, inseri um link com a primeira imagem que foi a logo da empresa fictícia, a "Moon". O link é para fazer com que a página se desloque de uma div para outra para dar menos trabalho para o leitor/cliente.
	Criei uma ul (unordered list) para deixá-la como o menu do projeto, deixando, como itens de tal lista, todos os tópicos que, ao apertar, teriam o efeito de sombreamento graças ao padding ajustado no CSS. Além disso, todos os itens do menu direcionam às suas respectivas div's após serem referenciadas no campo dos links em cada item. Para que seja feito esse direcionamento, basta colocar, no lugar do link de cada item, a id criada correspondente à div. Finalizei a primeira div e iniciei a próxima.
	Na segunda div, já adicionei a imagem que seria a responsável por representar o primeiro tópico, uma espécie de "banner" de informações que foi identificada com o id "about-us-banner". Fechei a segunda div e criei as outras duas com o mesmo comando, seguindo o propósito mencionado a cima.

CSS:
	Na parte do CSS, iniciei customizando o "html" em si, ou seja, o projeto inteiro, com o comando "scroll-behavior: smooth", que tem o objetivo de direcionar o usuário de forma suave (smooth) ao banner respectivo ao item do menu clicado.
	Logo após, customizei o "body" para que tenha o estilo de fonte do texto em arial, helvetica e sans-serif, bem como o tamanho da fonte (20 pixels).
	No "#header", id referenciando-se à primeira div criada no CSS, ajustei, respectivamente:
- A posição da div (fixed = fixa);
- A margem (0 pixels);
- A largura da div (em 100%, para que preencha a tela de seja qual for o aparelho);
- A cor do fundo (white).
	No id "#menu1" ajustei somente a margem à direita para 50 pixels, para que o menu fosse colocado mais à esquerda, próximo à logo.
	No id "#logo" ajustei também somente a margem, dessa vez à esquerda para 90 pixels.
	Na classe ".menu" foram ajustados, respectivamente:
- O estilo de lista (none = nenhum);
- A margem na direção de cima para 25 pixels, para não ficar muito colada na borda do site;
- A margem no topo, determinada em 0%;
- A margem à esquerda, determinada em 22%, para não sobrepor a logo;
- A sua posição (fixa);
- A largura em 100%, para que seja responsivo, conforme foi citado acima;
- A cor do fundo, em branco.
	Na classe ".menu li", foram determinados os seguintes ajustes:
- A posição, determinada como relativa;
- O float, na esquerda, para que o menu não seja exibido de forma vertical e sim horizontal;
- O estilo da fonte.
	Na classe ".menu", referindo-se à "li" (list item) e ao "a" (link), temos os seguintes ajustes:
- Cor em laranja;
- Decoração do texto, ajustada em none (nenhuma), para que o sublinhado do link desapareça;
- O padding (preenchimento ao redor do texto), ajustado para preencher 10 pixels à direita e 10 pixels no topo;
- O display (forma de exibição do item), em block (bloco).
	Na classe ".menu", referindo-se à "li", ao "a" e com o inicial ajuste "hover" (comando que permite alterar a cor do link ao passar o mouse), temos:
- A cor de fundo a ser exibida (laranja);
- Cor da fonte ao ter o mouse em cima (branco);
- A sombra do texto, efeito determinado na cor branca e com a sombra em 0 pixels à direita, 0 pixels à esquerda e 5 pixels no topo.
	Na classe ".menu", "li" e direcionada também à "ul" (unordered list), defini os ajustes:
- Posição, em absolute (absoluto);
- A margem no topo, em 45 pixels;
-  A margem à esquerda, em 0 pixels;
- A cor de fundo em branco.
	Na classe ".menu", "li, "ul' e "li", temos:
- O formato de exibição em block (bloco);
- A largura, em 150px;
- A cor de fundo, para branco fumaça;
- O tamanho da fonte, em 17 pixels.
	Deixei também todas as imagens utilizadas no projeto organizadas em uma pasta específica, de forma a organizar o trabalho.
