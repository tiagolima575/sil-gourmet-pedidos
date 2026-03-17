# Pedido SIL Gourmet — versão corrigida

## O que estava causando o problema

O catálogo anterior deixava parte das alterações salvas no **navegador** (`localStorage` / `indexedDB`).

Na prática:
- no seu aparelho parecia certo;
- para outras pessoas, não;
- porque elas não tinham os mesmos dados salvos localmente.

## O que foi corrigido

Esta versão nova já deixa no próprio HTML a base pública do catálogo:

### Tradicionais públicos já incluídos no arquivo
- Morango Clássico → `sabor-morango.jpg`
- Maracujá Tropical → `sabor-maracuja.jpg`
- Uva Intensa → `sabor-uva.jpg`
- Abacaxi Dourado → `sabor-abacaxi.jpg`
- Amora → `sabor-amora.jpg`
- Cupuaçu → `sabor-cupuacu.jpg`
- Kiwi Amarelo → `sabor-kiwi-amarelo.jpg`
- Kiwi Verde → `sabor-kiwi-verde.jpg`
- Manga → `sabor-manga.jpg`
- Pitaia → `sabor-pitaia.jpg`

## Regra importante

Para funcionar para todo mundo no site:
- o HTML precisa ser o arquivo novo corrigido;
- as imagens precisam estar publicadas no mesmo lugar do HTML ou no caminho certo;
- os nomes dos arquivos devem bater exatamente.

## Estrutura esperada

Se tudo estiver na mesma pasta do site/repositório:
- `pedido-sil-gourmet-com-fixado.html`
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

## Observação direta

Se você editar sabores/fotos só pelo botão secreto dentro da página, isso continua sendo alteração local do navegador até você substituir o HTML publicado.

Ou seja: o arquivo certo para subir no site é o **HTML corrigido**, não só a versão que abriu no seu celular.
