## Projeto 14 - Card de Funcionários Interativo

### 🚀 Sobre o Projeto 

Este projeto consiste em uma página de apresentação de funcionários. Cada foto é um pequeno card que, ao receber o cursor do mouse, se transforma de forma animada, revelando uma imagem maior, o nome e o cargo do profissional.

### 🛠️ Tecnologias e Conceitos Abordados

#### HTML5

Neste projeto, utilizei a tag alt de forma detalhada e descritiva em cada imagem. Isso é crucial para a acessibilidade do site, permitindo que leitores de tela descrevam o conteúdo das imagens para usuários com deficiência visual. A hierarquia de divs foi bem planejada para comportar os diferentes estados do card (o ícone pequeno e a imagem em destaque).

#### CSS3

Eu me aprofundei em várias técnicas CSS, com destaque para a animação baseada no :hover. A propriedade transition foi usada de forma precisa para animar múltiplas propriedades (transform, left, z-index, opacity) com diferentes atrasos (transition-delay), criando um efeito complexo e fluido. O uso de transform: translateX() foi essencial para posicionar os cards em destaque, enquanto a pseudoclasse :hover controlou o gatilho para a animação. Além disso, a propriedade z-index foi fundamental para garantir que o card em destaque aparecesse na frente dos outros elementos, e a propriedade pointer-events: none foi usada para controlar como o mouse interage com o card, impedindo cliques indesejados e melhorando a experiência do usuário.

### 💻 Como Executar:

Instale o arquivo no seu computador, e abra no seu navegador de preferencia.
