# Burger In The Box

Site estático adaptado do modelo Dom Menu, preservando a estrutura de navegação, vitrine, apresentação e pedido. Basta servir `index.html`; não há instalação nem etapa de build.

- Pedidos: https://burgerinthebox.mandarpedido.com/mobile/home
- WhatsApp: +55 47 98867-4198
- Instagram: https://www.instagram.com/burgerinthebox/
- Endereço: Rua Selso Duarte Moreira, 933, Cordeiros, Itajaí – SC.

Os horários devem ser consultados no sistema de pedidos. Os materiais fornecidos apresentavam horários divergentes. Preços ficam no cardápio externo para evitar duplicação desatualizada.

## Imagens

Todos os arquivos usados ficam em `img/`, com fotografias WebP comprimidas incorporadas em contêineres SVG autossuficientes. As fotos principais dos burgers, o logo e a fachada vieram dos materiais fornecidos para a Burger In The Box. Xis e fritas são imagens de apoio mantidas do modelo, conforme autorizado; a imagem do xis representa a categoria, sem identificação como foto de um produto específico.

As fotos promocionais e as cinco fotos adicionais de burgers e combos foram tratadas com a ferramenta integrada imagegen. Os arquivos receberam conversão e compressão WebP. A fachada usa a foto original com enquadramento no CSS para ocultar o ícone de vídeo do print.

Prompts de edição usados:

1. `img/double-smash-bacon.svg`: Remove only the promotional lettering above the burger and the small floating yellow logo below. Reconstruct the background seamlessly. Preserve the exact burger, number and placement of patties, bacon, cheddar, pickles, bun, hands in black gloves, camera angle and dark warm lighting. Modest photographic clarity improvement, natural food texture. No added ingredients, no new text.
2. `img/smash-burger.svg`: Remove only overlaid promotional text HOJE VOCÊ MERECE and the small floating yellow logo at top. Reconstruct the yellow dark blurred background seamlessly. Preserve exact burger, beef patty, cheddar, pickles, red onion, bun and black gloved hand unchanged. Improve clarity and exposure subtly without inventing ingredients or altering food. No added text.

## Verificação

Conferido em navegador Chromium em 1440, 390 e 320 pixels: imagens carregadas, ausência de erros JavaScript, links resolvidos, ausência de overflow horizontal e SVG do WhatsApp renderizado. O site encaminha ao sistema de pedidos; não recebe pedidos nem processa pagamentos.

As fotografias permanecem rasterizadas em WebP; o contêiner SVG permite transporte como texto pela conexão do GitHub sem dependências externas.

## Atualização da galeria

O cardápio enviado pelo usuário confirma xis (carne, bacon, frango, filé, calabresa e coração), batata frita palito de 150 g e 250 g e batata frita com cheddar e bacon. Por isso as fotos de apoio de xis e fritas foram mantidas somente nas categorias. A foto das fritas representa a opção palito simples, sem cheddar. A confirmação se refere aos itens do cardápio, não à autoria dessas duas imagens de apoio.

A vitrine passa a mostrar uma foto real do Fried Chicken no lugar da imagem genérica de xis. As cinco fotos novas foram distribuídas entre categorias, reconhecimento e passos do pedido, reduzindo cada imagem a no máximo duas aparições. Os nomes e ingredientes vêm do cardápio enviado; os valores e disponibilidade ficam no sistema de pedidos.

Fotos adicionais: `combo-bacon.svg`, `bacon-nas-maos.svg`, `combo-da-casa.svg`, `burger-cervejinha.svg` e `fried-chicken.svg`. Edições realizadas pela ferramenta imagegen integrada, preservando os produtos e a composição original, seguidas de compressão WebP.

Os prompts completos das cinco novas edições estão em `IMAGE_EDITS.md`.
