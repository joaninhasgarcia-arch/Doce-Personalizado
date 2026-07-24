# Doce Modelagem — Funil Quiz

Este pacote contém somente dois arquivos:

- `index.html` — página completa, com HTML, CSS e JavaScript incorporados.
- `README.md` — instruções rápidas.

## Ajustes desta versão

- Textos da abertura, apresentação, perguntas, objeções, custos e oferta aproximados da copy da página de referência enviada.
- Notificação de cadastro integrada ao final da primeira etapa, sem cobrir o conteúdo.
- Fontes, tamanhos, espaçamentos, paleta rosa-clara e estrutura mobile preservados.
- Avisos discretos sobre variação de resultados adicionados junto às menções de faturamento.

## Alterar o checkout

Abra o `index.html` e procure por:

```js
checkoutUrl: "https://SEU-LINK-DE-CHECKOUT-AQUI.com"
```

Substitua pelo link real do checkout.

## Alterar nomes da notificação

No bloco `CONFIG`, edite:

```js
toastNames: ["Mariana", "Fernanda", "Juliana", "Roberta", "Ana"]
```

Use apenas nomes autorizados.

## Publicar no GitHub Pages

1. Envie `index.html` e `README.md` para a raiz do repositório.
2. Abra **Settings → Pages**.
3. Selecione a branch principal e a pasta raiz.
4. Salve e aguarde a publicação.
