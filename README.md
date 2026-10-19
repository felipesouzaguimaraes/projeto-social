# 📱 Projeto Redes Sociais — Curso em Vídeo (Desafio 11)

<p align="center">
  <span>🔶 <b>HTML5</b></span> &nbsp;&nbsp;•&nbsp;&nbsp;
  <span>🔷 <b>CSS3</b></span> &nbsp;&nbsp;•&nbsp;&nbsp;
  <span>🖼️ <b>iFrames Dinâmicos</b></span>
</p>

Este é o **Projeto Redes Sociais**, desenvolvido como o **Desafio 11 (Módulo 4)** do curso de HTML5 e CSS3 do **Curso em Vídeo**, ministrado pelo professor **Gustavo Guanabara**.

O grande objetivo deste desafio foi criar uma interface interativa que simula a tela de um smartphone. Ao clicar nos ícones das redes sociais posicionados na lateral ou abaixo do aparelho, o conteúdo correspondente (YouTube, GitHub, Instagram, LinkedIn ou Facebook) é carregado dinamicamente dentro da tela do dispositivo falso.

---

## 🔗 Demonstração ao Vivo

O projeto está publicado e pode ser testado e navegado diretamente pelo seu navegador:

📌 **[Clique aqui para acessar o Projeto Redes Sociais](https://felipesouzaguimaraes.github.io/projeto-social/)**

---

## 🎨 Conceitos Visuais e Funcionalidades

O projeto exige um controle preciso de posicionamento CSS para alcançar o efeito visual desejado:

| Aspecto Técnico | Implementação Aplicada |
| :--- | :--- |
| **Simulação de Hardware** | Uso de uma imagem de smartphone vazada no centro, servindo de moldura para o conteúdo digital. |
| **Uso Otimizado de `<iframe>`** | Incorporação da tag `<iframe>` configurada com tamanhos exatos e barras de rolagem internas para exibir as páginas web reais dentro do telefone simulado. |
| **Alvos de Links (`target`)** | Associação do atributo `target` nos links dos botões para que apontem diretamente para o `name` do iframe, permitindo trocar de página sem atualizar o site principal. |
| **Efeitos de Transição** | Criação de botões flutuantes arredondados para as redes sociais, utilizando pseudo-classes do CSS para criar efeitos visuais ao passar o mouse (*hover*). |

### 📸 Prévia do Layout (Desktop)
<p align="center">
  <img width="1901" height="911" alt="print-layout" src="https://github.com/user-attachments/assets/e31f0a1b-722a-4a3e-bd80-1acf92fe07ee" />
</p>

---

## 📂 Estrutura de Arquivos do Repositório

O projeto possui uma estrutura focada na organização de mídias e sobreposição de camadas:

* `index.html` — Estrutura principal do site, contendo a declaração do iframe central e os botões das redes.
* `estilos/` (ou pasta correspondente)
  * `style.css` — Controle de posicionamento absoluto, centralização do smartphone e estilização dos botões flutuantes.
* `imagens/` — Contém a imagem da moldura do celular, os fundos de tela de cada rede social e os logotipos utilizados.

---

## 🚀 Como Executar o Projeto Localmente

Por ser um projeto puramente Front-End estático, você pode rodá-lo instantaneamente:

1. Baixe os arquivos ou clone este repositório.
2. Abra a pasta principal do projeto.
3. Dê um duplo clique no arquivo `index.html` para executá-lo.
4. Clique nos botões laterais para ver as diferentes páginas carregando dentro do smartphone simulado!
