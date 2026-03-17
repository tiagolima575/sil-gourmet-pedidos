# SIL Gourmet — catálogo separado do jeito certo

Agora o catálogo foi organizado em **dois blocos fixos**, para não misturar na hora de editar:

## BLOCO 1 — TRADICIONAIS
Esses entram na regra normal do catálogo e nos combos padrões.

**Sabores tradicionais fixos:**
- Morango Clássico → `sabor-morango.jpg`
- Maracujá Tropical → `sabor-maracuja.jpg`
- Uva Intensa → `sabor-uva.jpg`
- Abacaxi Dourado → `sabor-abacaxi.jpg`
- Amora → `sabor-amora.jpg`
- Manga → `sabor-manga.jpg`

**Regra dos tradicionais:**
- ficam no bloco normal;
- usam a lógica padrão de quantidade;
- usam a lógica padrão de combos;
- entram no resumo como **tradicionais**.

## BLOCO 2 — ESPECIAIS
Esses ficam separados para não bagunçar o catálogo.

**Sabores especiais fixos:**
- Cupuaçu → `sabor-cupuacu.jpg`
- Kiwi Amarelo → `sabor-kiwi-amarelo.jpg`
- Kiwi Verde → `sabor-kiwi-verde.jpg`
- Pitaia → `sabor-pitaia.jpg`

**Regra dos especiais:**
- aparecem em bloco separado;
- têm quantidade separada;
- têm preço próprio editável;
- entram no resumo como **especiais**;
- não se misturam com os tradicionais.

## Como adicionar novos depois

### Se for TRADICIONAL
Adicionar no bloco de tradicionais.
Exemplo:
- Nome
- Descrição
- Imagem do site

### Se for ESPECIAL
Adicionar no bloco de especiais.
Exemplo:
- Nome
- Descrição
- Imagem do site
- Preço próprio

## Organização dos arquivos

Você pode manter tudo na mesma pasta:
- `pedido-sil-gourmet-com-separado-definitivo.html`
- `README-separado-definitivo.md`
- `sabor-morango.jpg`
- `sabor-maracuja.jpg`
- `sabor-uva.jpg`
- `sabor-abacaxi.jpg`
- `sabor-amora.jpg`
- `sabor-manga.jpg`
- `sabor-cupuacu.jpg`
- `sabor-kiwi-amarelo.jpg`
- `sabor-kiwi-verde.jpg`
- `sabor-pitaia.jpg`

Se quiser deixar mais limpo, também pode organizar assim:
- `img/tradicionais/`
- `img/especiais/`

Nesse caso, ajuste o caminho base das imagens no HTML.

## Resumo final do pedido
No fechamento, o sistema deve mostrar separado:
- quantidade de **tradicionais**;
- valor de **tradicionais**;
- quantidade de **especiais**;
- valor de **especiais**.

## Observação importante
Essa versão usa uma separação nova de armazenamento no navegador para evitar puxar a mistura da versão antiga.
Ou seja: abriu a nova versão, ela já começa organizada do jeito certo.
