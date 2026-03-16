# Pedido SIL Gourmet

Sistema de pedidos da **SIL Gourmet** com catálogo visual, imagens carregadas direto do repositório e organização separada entre **potinhos tradicionais** e **potinhos especiais**.

## Organização do catálogo

O projeto foi estruturado com **duas categorias separadas**:

### 1. Potinhos tradicionais
São os sabores normais do catálogo principal.

Exemplos de arquivos de imagem:
- `sabor-abacaxi.jpg`
- `sabor-amora.jpg`
- `sabor-cupuacu.jpg`
- `sabor-kiwi-amarelo.jpg`
- `sabor-kiwi-verde.jpg`
- `sabor-manga.jpg`
- `sabor-maracujá.jpg`
- `sabor-morango.jpg`
- `sabor-pitaia.jpg`
- `sabor-uva.jpg`

Esses itens seguem a regra normal de preço e combos.

### 2. Potinhos especiais
Os **potinhos especiais não ficam misturados com os tradicionais**.

Regras da estrutura:
- aparecem em **bloco separado**;
- possuem **quantidade separada**;
- possuem **valor separado**;
- no resumo final e no texto de pedido eles devem continuar separados dos tradicionais.

## Arquivos principais

- `pedido-sil-gourmet-com.html` → página principal do sistema de pedidos
- arquivos `.jpg` dos sabores → imagens usadas no catálogo
- `README.md` → explicação básica do projeto

## Como funciona

O HTML foi preparado para puxar as imagens direto dos arquivos enviados para o repositório/site, sem deixar as imagens embutidas no código.

Isso facilita:
- trocar fotos sem refazer a página inteira;
- manter o projeto mais limpo;
- publicar pelo GitHub Pages com mais organização.

## Como publicar no GitHub Pages

1. Envie o arquivo HTML e todas as imagens para o mesmo repositório.
2. Mantenha tudo na **mesma pasta**.
3. Vá em **Settings > Pages** no GitHub.
4. Ative o GitHub Pages para a branch principal.
5. Publique usando o arquivo HTML do projeto.

## Cuidados importantes

- Os nomes das imagens devem permanecer exatamente iguais.
- Se mudar o nome de algum arquivo, o HTML precisa ser atualizado também.
- Os **tradicionais** e os **especiais** devem continuar em blocos separados dentro da lógica do sistema.
- Não misture preços dos especiais com os preços dos tradicionais.

## Atualizações futuras

Você pode alterar depois:
- nomes dos sabores;
- imagens;
- preços;
- combos;
- potinhos especiais;
- layout visual.

## Resumo da lógica correta

A estrutura certa do sistema é esta:
- **Tradicionais separados**
- **Especiais separados**
- **Fotos puxadas direto do site/repositório**
- **Resumo do pedido com valores separados por categoria**

---

Projeto usado para o catálogo e sistema de pedidos online da **SIL Gourmet**.
