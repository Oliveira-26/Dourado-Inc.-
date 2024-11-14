# Landing Page Customizada - Dourado Inc.

Este repositório contém o código-fonte de uma landing page customizada para a Dourado Inc., uma empresa fictícia de tecnologia. Esta página é responsiva, utiliza HTML, CSS e JavaScript para oferecer uma experiência de usuário interativa, com funcionalidades como carrossel de imagens, modais informativos de produtos, e um formulário de contato.


## Visão Geral
A landing page foi projetada com uma estética moderna, usando uma paleta de cores sóbria, tipografia clara, e elementos interativos para engajar os visitantes. A página promove os produtos e serviços da Dourado Inc., destacando os valores da empresa e facilitando o contato dos usuários.

## Estrutura do Projeto
A estrutura da página é organizada em várias seções:

1. **Cabeçalho**: Inclui o logotipo e uma barra de navegação.
2. **Carrossel de Imagens**: Exibe uma galeria de imagens com transição suave.
3. **Seção "Sobre"**: Apresenta a missão e os valores da Dourado Inc.
4. **Seção de Produtos**: Lista os principais serviços oferecidos, cada um com uma janela modal de detalhes.
5. **Depoimentos**: Mostra comentários de clientes em um layout de cartões.
6. **Formulário de Contato**: Permite que visitantes enviem uma mensagem para a empresa.
7. **Rodapé**: Inclui links para navegação interna e direitos autorais.

## Funcionalidades

### Carrossel de Imagens
O carrossel permite que o usuário navegue entre diferentes imagens usando botões de próxima e anterior. As imagens deslizam horizontalmente com uma transição suave.

### Modais de Produtos
Cada produto na seção de "Produtos" abre uma modal ao ser clicado, onde são exibidos o título e a descrição do serviço. As funções JavaScript `openModal()` e `closeModal()` controlam a exibição da modal.

### Formulário de Contato
O formulário inclui campos para nome, email e mensagem. Todos os campos são obrigatórios (`required`), garantindo que os visitantes preencham as informações necessárias antes de enviar.

## Como Usar

1. Clone este repositório ou baixe o arquivo HTML.
2. Abra o arquivo `index.html` em seu navegador para visualizar a página.

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

3. Para editar o conteúdo ou estilização, abra o arquivo HTML em seu editor de código preferido.

## Personalização

### Alterando Imagens
Para substituir as imagens do carrossel ou dos produtos:
- Substitua o URL da imagem em cada tag `<img>` pela URL de sua imagem ou pelo caminho de um arquivo local.

### Mudando o Texto
- Edite o conteúdo diretamente nas tags HTML correspondentes, como `<h2>`, `<p>`, ou `<span>`.

### Ajustando Estilos
- Altere as propriedades de estilo no bloco `<style>` para personalizar as cores, fontes e layout da página.

### Modificando o JavaScript
Para personalizar as funcionalidades interativas:
- Altere o JavaScript localizado no final do arquivo `index.html`.

