# Doce Modelagem — Quiz com Mariana Alves (abertura estendida)

Este pacote contém somente dois arquivos:

- `index.html` — página completa com HTML, CSS, JavaScript e todas as imagens incorporadas em Base64.
- `README.md` — instruções de publicação e edição.

## Alterações desta versão

- Mantida a imagem principal da especialista **Mariana Alves**.
- Acrescentada uma apresentação mais completa da especialista logo após a imagem principal.
- Incluída uma lista visual dos tipos de doces ensinados.
- Acrescentada a nova imagem com docinhos de animais, flores e tema fundo do mar.
- Criado um texto de orientação seguido pelo botão **Continuar**.
- A prova social agora aparece dentro do fluxo da página, abaixo do botão, sem cobrir o conteúdo.
- O bloco informa uma inscrição recente e a quantidade de vagas disponíveis.
- A antiga etapa introdutória repetida foi removida, deixando o quiz mais direto.
- Todas as imagens estão embutidas dentro do `index.html`; não existe pasta `assets`.
- O quiz, as perguntas, a barra de progresso, o carregamento, a oferta e a responsividade foram preservados.

## Publicar no GitHub Pages

1. Crie ou abra o repositório do quiz.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Acesse **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch principal (`main`) e a pasta raiz (`/root`).
6. Salve e aguarde a publicação.

## Alterar o checkout

Abra o `index.html` e procure por:

```js
checkoutUrl: "https://SEU-LINK-DE-CHECKOUT-AQUI.com"
```

Substitua pelo link real do checkout.

## Editar nomes da prova social

No final do `index.html`, procure por:

```js
toastNames: ["Jadiane", "Fernanda", "Juliana", "Roberta", "Ana", "Camila"]
```

Você pode trocar os nomes. Use apenas informações verdadeiras quando a mensagem for apresentada como uma compra ou inscrição real.

## Antes de publicar

Revise preço, bônus, garantia, promessas de resultado, disponibilidade de vagas, notificações e link do checkout. Mantenha somente informações verdadeiras e comprováveis.
