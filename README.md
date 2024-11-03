# <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Spider.png" alt="Spider" width="35" height="35" /> Spider-Man | Multiversos <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Animals/Spider%20Web.png" alt="Spider Web" width="35" height="35" />

Bem-vindo ao projeto **Spider-Man | Multiversos**! Este projeto é uma página interativa que explora os diferentes "multiversos" do Homem-Aranha, destacando as versões dos filmes interpretadas por Tobey Maguire, Andrew Garfield, e Tom Holland.

## 🌍 Visão Geral

O projeto visa proporcionar uma experiência visual e interativa sobre o universo do Homem-Aranha, permitindo ao usuário navegar por cards dos três atores que interpretaram o super-herói. A página possui um carrossel com animações e informações sobre cada versão do Homem-Aranha.

### 🚀 Funcionalidades
- **🕸️ Menu de Navegação**: Links para as diferentes versões do Homem-Aranha.
- **🎴 Carrossel de Cards**: Cards interativos de cada ator com animação ao passar o mouse.
- **🎮 Controle de Carrossel**: Botões para navegar pelos cards de forma mais intuitiva.

## 🏗️ Estrutura do Projeto

- **📝 HTML**: Responsável pela estrutura da página, com os cards dos três atores.
- **🎨 CSS** (`home-page-styles.css`): Estiliza o layout e os elementos da página, incluindo o carrossel e o menu de navegação.
- **⚙️ JavaScript** (`script.js`): Controla as animações dos cards e a lógica de interação do carrossel.

## 📜 JavaScript - Lógica de Interação

O arquivo `script.js` contém a lógica responsável por tornar a interação com os cards mais dinâmica e atraente. Abaixo estão algumas das principais funções implementadas:

- **`handleMouseEnter` e `handleMouseLeave`**: Essas funções adicionam e removem a classe `'s-card--hovered'` aos cards quando o mouse passa sobre eles, além de atualizar o `id` do corpo do documento para alterar o estilo conforme o card ativo.

- **`addEventListenersToCards`**: Adiciona os eventos de `mouseenter` e `mouseleave` a todos os cards presentes na página, permitindo que as animações de destaque sejam aplicadas quando o usuário interage com eles.

- **`selectCarouselItem`**: Responsável por controlar o carrossel ao clicar nos botões de navegação. Esta função altera a rotação dos cards no carrossel e destaca o botão de navegação ativo.

## 🎨 CSS - Animações e Estilos

O arquivo `home-page-styles.css` contém estilos que tornam a experiência visual mais envolvente. Abaixo estão algumas das principais animações e técnicas de estilização usadas:

- **✨ Animações de Hover**: Quando o usuário passa o mouse sobre um card (`.s-card--hovered`), a imagem de fundo do card desaparece gradualmente (`opacity: 0;`), e a imagem principal é ampliada (`transform: scale(1.4)`) com um efeito de sombra para dar destaque.

- **🌊 Transições Suaves**: O uso da propriedade `transition` em vários elementos permite uma mudança suave de estados, como opacidade, transformação (`transform`) e posicionamento. Isso melhora a experiência do usuário ao tornar as interações mais fluidas.

- **🔄 Rotação do Carrossel**: Os cards do carrossel são organizados em um espaço tridimensional usando `transform: rotateY(...) translateZ(...)`, criando um efeito visual de rotação para destacar o card selecionado.

- **🎨 Efeito de Filtro**: Cards que não estão em foco são estilizados com `filter: grayscale(100%)`, criando um contraste que ajuda a destacar o card ativo.

- **🖱️ Controle de Navegação**: Os botões de navegação do carrossel (`.s-controller__button`) têm efeitos de escala ao serem clicados ou ao passar o mouse sobre eles, proporcionando feedback visual ao usuário.

## 🤝 Contribuições

Contribuições são bem-vindas! Se você encontrar um bug, tiver uma sugestão de melhoria ou quiser adicionar uma nova funcionalidade, sinta-se à vontade para criar um issue ou pull request. Siga estas etapas:

1. Faça um fork do repositório.
2. Crie um novo branch com sua contribuição (`git checkout -b feature/minha-contribuicao`).
3. Faça commit das suas alterações (`git commit -am 'Adiciona minha contribuição'`).
4. Faça push para o branch (`git push origin feature/minha-contribuicao`).
5. Abra um Pull Request.

## ⚙ Suporte

Se você encontrar algum problema ou tiver dúvidas sobre o uso deste projeto, por favor, abra um issue para discussão.

Desenvolvido com <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Sparkling%20Heart.png" alt="Sparkling Heart" width="25" height="25" /> por Amadeo Bon para contribuir com a comunidade. Boa navegação!