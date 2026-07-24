# Funil de Quiz — HTML único

Template responsivo em **HTML, CSS e JavaScript puro**, pronto para publicar no GitHub Pages, Vercel ou Netlify.

## Arquivos do ZIP

- `index.html`: contém toda a estrutura, o design, a lógica do quiz e as imagens demonstrativas incorporadas.
- `README.md`: instruções de personalização e publicação.

Não existe pasta `assets`. O CSS, o JavaScript e os SVGs demonstrativos já estão dentro do próprio `index.html`.

## Personalização rápida

Abra o `index.html` e procure por:

```js
const CONFIG = {
```

Edite esse objeto para adaptar o funil ao seu produto:

1. `brand`: nome do produto.
2. `checkoutUrl`: link real do checkout.
3. `pixelId`: ID do Pixel da Meta, quando necessário.
4. `intro`: título, texto, imagem e benefícios da abertura.
5. `questions`: perguntas e respostas do quiz.
6. `insight`: tela intermediária para quebrar uma objeção.
7. `result`: método, módulos, provas sociais e FAQ.
8. `offer`: preço, itens e textos da oferta.
9. `urgency.enabled`: mantenha `false` até existir uma condição real e verificável.

## Como substituir as imagens

As imagens provisórias estão incorporadas como `data:image/svg+xml;base64,...` dentro do `index.html`.

Para usar imagens próprias, você pode:

- substituir o valor de `image`, `mainImage` ou das imagens de depoimentos por uma URL pública; ou
- converter sua imagem para Base64 e colar como `data:image/webp;base64,...`.

Recomendações:

- capa/hero: 1080 × 1080 ou 1080 × 1350;
- especialista: 1080 × 1350;
- provas sociais: 1200 × 825;
- prefira WebP para carregamento mais rápido.

## Pixel da Meta

O template já está preparado para disparar, quando o Pixel estiver configurado:

- `PageView`;
- `Lead` ao concluir o quiz;
- `ViewContent` ao abrir o resultado;
- `InitiateCheckout` ao clicar no botão da oferta.

A compra deve ser enviada pela plataforma de checkout, preferencialmente por integração oficial ou API de conversões.

## Publicar no GitHub Pages

1. Crie um repositório novo.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Acesse **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/root`.
6. Salve e aguarde a publicação.

## Publicar na Vercel

1. Importe o repositório do GitHub.
2. Em **Framework Preset**, escolha **Other**.
3. Deixe **Build Command** vazio.
4. Deixe **Output Directory** vazio ou use `.`.
5. Clique em **Deploy**.

## Testes antes de anunciar

- confirme o link do checkout;
- teste todas as respostas e o botão Voltar;
- verifique o layout em celulares pequenos;
- confira os eventos no Meta Pixel Helper e no Gerenciador de Eventos;
- substitua todo conteúdo demonstrativo por conteúdo real.
