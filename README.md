# Codigos-css

1. O Modelo de Caixa (Box Model)
No CSS, tudo é uma caixa. Essas propriedades definem o tamanho, o espaço e as bordas de cada uma.

box-sizing: border-box;

O que faz: Impede que o elemento cresça além da largura definida quando você adiciona padding ou border. (Coloque isso no topo de todo projeto).

width / height

O que faz: Define a largura e a altura do elemento (ex: 200px, 100%).

max-width / min-width

O que faz: Define um limite máximo ou mínimo para a largura. Muito útil para fazer sites adaptáveis a telas de celular.

padding

O que faz: Espaço interno (afasta o conteúdo de dentro para longe da borda).

margin

O que faz: Espaço externo (empurra a caixa para longe das outras caixas vizinhas).

border

O que faz: Cria a borda da caixa. Define espessura, estilo e cor de uma vez (ex: 2px solid #000).

border-radius

O que faz: Arredonda as pontas dos cantos (ex: 8px para cantos suaves, 50% para virar um círculo).

2. Textos e Fontes (Tipografia)
Para formatar e estilizar a leitura.

color

O que faz: Muda a cor do texto (aceita nomes como red, códigos como #333 ou rgb()).

font-family

O que faz: Escolhe a fonte (ex: Arial, sans-serif).

font-size

O que faz: Define o tamanho da letra (ex: 16px, 1.2rem).

font-weight

O que faz: Define a espessura da letra (normal, bold, ou números como 400 e 700).

text-align

O que faz: Alinha o texto dentro da caixa (left, center, right, justify).

line-height

O que faz: Define o espaçamento entre as linhas do texto, melhorando a leitura.

text-decoration

O que faz: Coloca ou tira efeitos no texto. O uso principal é text-decoration: none; para tirar a linha azul feia de baixo dos links (<a>).

3. Cores e Fundos
Para dar vida visual aos elementos.

background-color

O que faz: Define a cor do fundo do elemento.

background-image

O que faz: Coloca uma imagem no fundo (ex: url('imagem.jpg')).

background-size: cover;

O que faz: Faz a imagem de fundo esticar/encolher para cobrir todo o espaço sem distorcer.

4. Layout com Flexbox
A ferramenta moderna mais fácil para alinhar coisas na página.

⚠️ Todas essas propriedades (exceto o gap) devem ser aplicadas na caixa pai que segura os elementos.

display: flex;

O que faz: Liga o modo Flexbox. Por padrão, coloca os itens filhos um ao lado do outro na mesma linha.

flex-direction

O que faz: Escolhe a direção dos itens: row (lado a lado, padrão) ou column (um embaixo do outro).

justify-content

O que faz: Alinha os itens na horizontal (se estiver em row).

Valores principais: center (centro), space-between (separa nas pontas), flex-start (início).

align-items

O que faz: Alinha os itens na vertical (se estiver em row).

Valor principal: center (centraliza verticalmente).

gap

O que faz: Define uma distância fixa e uniforme entre os itens sem precisar mexer com margens.

5. Posição e Exibição na Tela
Para controlar onde e como as coisas aparecem.

display (block, inline, none)

O que faz: block faz o elemento ocupar a linha inteira; inline faz ocupar só o espaço do próprio texto; none esconde o elemento completamente.

position (static, relative, absolute, fixed)

O que faz:

relative: Permite mover o elemento a partir da sua posição original.

absolute: Posiciona o elemento exatamente onde você mandar em relação ao container pai.

fixed: Deixa o elemento "congelado" na tela mesmo rolando a página (ótimo para menus fixos).

top / bottom / left / right

O que faz: Define a distância em pixels quando você usa position.

opacity

O que faz: Controla a transparência do elemento (de 0 para invisível a 1 para total visibilidade).

cursor: pointer;

O que faz: Faz o ponteiro do mouse virar a "mãozinha de clique" ao passar por cima (essencial para botões).

6. Bônus: A "Mágica" do :hover
elemento:hover

O que faz: Não é uma propriedade isolada, mas um pseudoclasse. Aplica estilos apenas quando o usuário passa o mouse por cima do elemento.

Exemplo: button:hover { background-color: blue; }
