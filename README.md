# Pratique Escrita

Um projetinho simples para praticar e testar escrita diretamente no navegador usando `contenteditable`. Possui uma interface limpa com um “bloco de notas” centralizado para digitação, além de páginas de Sobre e Créditos.

## Funcionalidades
- Área de escrita com `contenteditable`, pronta para digitar
- Título centralizado e bloco com visual de "notepad"
- Altura fixa da área de escrita com rolagem vertical (não expande a página)
- Quebra de linha e palavras configuradas para boa leitura
- Páginas: Início, Sobre e Créditos

## Como usar
1. Baixe/clonar o repositório.
2. Abra o arquivo `index.html` no seu navegador (duplo clique é suficiente).
3. Comece a digitar no bloco central.

## Estrutura do projeto
- `index.html`: página principal com a área de escrita
- `sobre.html`: informações sobre o projeto
- `creditos.html`: créditos e link para o projeto original que inspirou
- `css/style.css`: estilos do site

## Personalização rápida
- Cores: ajustáveis em `:root` no `css/style.css`
- Tamanho da área de escrita: edite `.escreverTexto` (largura/altura)
- Sombra e borda do bloco: ajuste no seletor `#folha`

## Créditos
Projeto inspirado em: https://github.com/Scarcela13/Site-Escreve.com

## Licença
Este projeto é apenas para fins de estudo/demonstração.