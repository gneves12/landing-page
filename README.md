# landing-page
Oi, gente!
Essa página é um projeto prático simples de um site. Fiquem à vontade para aperfeiçoar se quiserem!
Aqui, vou explicar o que foi feito no meu trabalho de Desenv. Web:
	Inicialmente, coloquei o cl�ssico cabe�alho que deve ter em absolutamente TODO projeto que envolver HTML:
	Defini o estilo de caracteres (UTF-8). Logo ap�s, defini, ainda no meta, um comando com o objetivo de tornar o projeto do site responsivo de acordo com cada tela em que for exibido.
	Coloquei o t�tulo do projeto, que � "Trabalho Avaliativo - 2� Av." e, logo ap�s, chamei o CSS para o c�digo.
	J� no body, iniciei criando a primeira div e tamb�m um nav com o objetivo de trabalhar com o menu j� no in�cio da p�gina.
	Meu projeto foi feito de forma sucinta, de forma a n�o necessitar que outras p�ginas fossem criadas a cada t�pico. 
	Ap�s a cria��o da primeira div, inseri um link com a primeira imagem que foi a logo da empresa fict�cia, a "Moon". O link � para fazer com que a p�gina se desloque de uma div para outra para dar menos trabalho para o leitor/cliente.
	Criei uma ul (unordered list) para deix�-la como o menu do projeto, deixando, como itens de tal lista, todos os t�picos que, ao apertar, teriam o efeito de sombreamento gra�as ao padding ajustado no CSS. Al�m disso, todos os itens do menu direcionam �s suas respectivas div's ap�s serem referenciadas no campo dos links em cada item. Para que seja feito esse direcionamento, basta colocar, no lugar do link de cada item, a id criada correspondente � div. Finalizei a primeira div e iniciei a pr�xima.
	Na segunda div, j� adicionei a imagem que seria a respons�vel por representar o primeiro t�pico, uma esp�cie de "banner" de informa��es que foi identificada com o id "about-us-banner". Fechei a segunda div e criei as outras duas com o mesmo comando, seguindo o prop�sito mencionado a cima.

CSS:
	Na parte do CSS, iniciei customizando o "html" em si, ou seja, o projeto inteiro, com o comando "scroll-behavior: smooth", que tem o objetivo de direcionar o usu�rio de forma suave (smooth) ao banner respectivo ao item do menu clicado.
	Logo ap�s, customizei o "body" para que tenha o estilo de fonte do texto em arial, helvetica e sans-serif, bem como o tamanho da fonte (20 pixels).
	No "#header", id referenciando-se � primeira div criada no CSS, ajustei, respectivamente:
- A posi��o da div (fixed = fixa);
- A margem (0 pixels);
- A largura da div (em 100%, para que preencha a tela de seja qual for o aparelho);
- A cor do fundo (white).
	No id "#menu1" ajustei somente a margem � direita para 50 pixels, para que o menu fosse colocado mais � esquerda, pr�ximo � logo.
	No id "#logo" ajustei tamb�m somente a margem, dessa vez � esquerda para 90 pixels.
	Na classe ".menu" foram ajustados, respectivamente:
- O estilo de lista (none = nenhum);
- A margem na dire��o de cima para 25 pixels, para n�o ficar muito colada na borda do site;
- A margem no topo, determinada em 0%;
- A margem � esquerda, determinada em 22%, para n�o sobrepor a logo;
- A sua posi��o (fixa);
- A largura em 100%, para que seja responsivo, conforme foi citado acima;
- A cor do fundo, em branco.
	Na classe ".menu li", foram determinados os seguintes ajustes:
- A posi��o, determinada como relativa;
- O float, na esquerda, para que o menu n�o seja exibido de forma vertical e sim horizontal;
- O estilo da fonte.
	Na classe ".menu", referindo-se � "li" (list item) e ao "a" (link), temos os seguintes ajustes:
- Cor em laranja;
- Decora��o do texto, ajustada em none (nenhuma), para que o sublinhado do link desapare�a;
- O padding (preenchimento ao redor do texto), ajustado para preencher 10 pixels � direita e 10 pixels no topo;
- O display (forma de exibi��o do item), em block (bloco).
	Na classe ".menu", referindo-se � "li", ao "a" e com o inicial ajuste "hover" (comando que permite alterar a cor do link ao passar o mouse), temos:
- A cor de fundo a ser exibida (laranja);
- Cor da fonte ao ter o mouse em cima (branco);
- A sombra do texto, efeito determinado na cor branca e com a sombra em 0 pixels � direita, 0 pixels � esquerda e 5 pixels no topo.
	Na classe ".menu", "li" e direcionada tamb�m � "ul" (unordered list), defini os ajustes:
- Posi��o, em absolute (absoluto);
- A margem no topo, em 45 pixels;
-  A margem � esquerda, em 0 pixels;
- A cor de fundo em branco.
	Na classe ".menu", "li, "ul' e "li", temos:
- O formato de exibi��o em block (bloco);
- A largura, em 150px;
- A cor de fundo, para branco fuma�a;
- O tamanho da fonte, em 17 pixels.
	Deixei tamb�m todas as imagens utilizadas no projeto organizadas em uma pasta espec�fica, de forma a organizar o trabalho.
