# Doce Modelagem — Quiz com Mariana Alves

Este pacote contém somente dois arquivos:

- `index.html` — página completa, com HTML, CSS, JavaScript e a imagem principal incorporada em Base64.
- `README.md` — instruções de publicação e edição.

## Ajustes desta versão

- A imagem principal do quiz foi substituída pela arte oficial com **Mariana Alves**.
- O nome **Mariana Alves** foi acrescentado na abertura e na identificação da especialista.
- A imagem está embutida diretamente no `index.html`; não existe pasta `assets` e não é necessário enviar arquivos de imagem separados.
- O layout anterior do quiz, as perguntas, o cronômetro, a oferta e a responsividade foram preservados.
- O nome “Mariana” foi retirado da lista de notificações simuladas para não confundir a especialista com uma visitante.

## Publicar no GitHub Pages

1. Crie ou abra o repositório do quiz.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Selecione a branch principal (`main`) e a pasta raiz (`/root`).
6. Salve e aguarde a publicação.

## Alterar o checkout

Abra o `index.html` e procure por:

```js
checkoutUrl: "https://SEU-LINK-DE-CHECKOUT-AQUI.com"
```

Substitua pelo link real do checkout.

## Observação sobre a imagem

A imagem da especialista está convertida para Base64 dentro do HTML. Isso deixa o arquivo maior, porém facilita a publicação: basta subir somente o `index.html` e o `README.md`.

## Antes de publicar

Revise preço, bônus, garantia, promessas de resultado, disponibilidade de vagas e notificações. Mantenha apenas informações reais e comprováveis.
