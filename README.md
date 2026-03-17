# SIL Gourmet — organização do catálogo

Este projeto foi organizado para trabalhar com **duas categorias separadas**:

- **Tradicionais**
- **Especiais**

A regra é simples: **não misturar os dois blocos**.

## Estrutura correta

### 1) Tradicionais
Os sabores tradicionais ficam em um bloco próprio, com a lógica normal de preço e combos.

**Sabores tradicionais atuais:**
- Morango Clássico → `sabor-morango.jpg`
- Maracujá Tropical → `sabor-maracuja.jpg`
- Uva Intensa → `sabor-uva.jpg`
- Abacaxi Dourado → `sabor-abacaxi.jpg`
- Amora → `sabor-amora.jpg`
- Manga → `sabor-manga.jpg`

**Regras dos tradicionais:**
- ficam no bloco de sabores normais;
- usam a regra padrão de quantidade;
- usam a regra padrão de combos;
- entram no resumo como **tradicionais**.

## 2) Especiais
Os sabores especiais precisam ficar em **bloco separado**, sem misturar com os tradicionais.

**Modelo para cadastrar especiais:**
- Nome do sabor
- Descrição
- Imagem
- Preço próprio
- Quantidade própria

**Exemplo de organização:**
- Especial 1 → `especial-nome-do-sabor.jpg`
- Especial 2 → `especial-outro-sabor.jpg`
- Especial 3 → `especial-mais-um-sabor.jpg`

**Regras dos especiais:**
- aparecem em seção separada;
- possuem preço próprio;
- possuem quantidade separada;
- entram no resumo como **especiais**;
- não devem herdar automaticamente a regra dos tradicionais.

## Organização dos arquivos

Você pode manter assim:

- `pedido-sil-gourmet-com.html`
- `README.md`
- `sabor-morango.jpg`
- `sabor-maracuja.jpg`
- `sabor-uva.jpg`
- `sabor-abacaxi.jpg`
- `sabor-amora.jpg`
- `sabor-cupuacu.jpg`
- `sabor-kiwi-amarelo.jpg`
- `sabor-kiwi-verde.jpg`
- `sabor-manga.jpg`
- `sabor-pitaia.jpg`
- arquivos dos especiais

Se quiser deixar mais limpo, pode organizar em duas pastas:

- `img/tradicionais/`
- `img/especiais/`

## Regra obrigatória de organização

O catálogo deve sempre seguir esta ordem:

### BLOCO 1 — TRADICIONAIS
Lista de sabores normais do catálogo.

### BLOCO 2 — ESPECIAIS
Lista separada dos sabores especiais.

## Resumo do pedido

No fechamento do pedido, o sistema deve continuar mostrando separado:

- quantidade de **tradicionais**;
- valor de **tradicionais**;
- quantidade de **especiais**;
- valor de **especiais**.

## Observação importante

Se você editar só no navegador, a mudança pode ficar local.
Para valer para todo mundo, o certo é:

1. atualizar o arquivo publicado no site;
2. manter as imagens no caminho certo;
3. não misturar tradicionais com especiais.

## Resumo final

A estrutura correta da SIL Gourmet é esta:

- **Tradicionais separados**
- **Especiais separados**
- **Imagens puxadas do site**
- **Resumo separado por categoria**

