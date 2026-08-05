# Doce Modelagem — Quiz com Mariana Alves (imagens nas respostas)

Este pacote contém somente dois arquivos:

- `index.html` — página completa com HTML, CSS, JavaScript e todas as imagens incorporadas em Base64.
- `README.md` — instruções de publicação e edição.

## Alterações desta versão

- Na etapa **“A receita é fácil para iniciantes?”**, a ilustração antiga foi substituída pela fotografia da Mariana Alves preparando os docinhos.
- Na etapa **“O custo é acessível para fazer?”**, a grade de ícones foi substituída pela fotografia dos ingredientes e corantes.
- As duas imagens foram incorporadas diretamente no `index.html`; não existe pasta `assets`.
- Foram preservados o alinhamento, o cronômetro, as perguntas, a prova social, a oferta e todo o funcionamento do quiz.
- O layout continua responsivo para celular e computador.

## Publicar no GitHub Pages

1. Abra o repositório da página.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Acesse **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch principal (`main`) e a pasta raiz (`/root`).
6. Salve e aguarde a atualização da publicação.

## Alterar o checkout

Abra o `index.html` e procure por:

```js
checkoutUrl: "https://SEU-LINK-DE-CHECKOUT-AQUI.com"
```

Substitua pelo endereço real do checkout.

## Editar a prova social

No final do `index.html`, procure por:

```js
toastNames: ["Jadiane", "Fernanda", "Juliana", "Roberta", "Ana", "Camila"]
```

Use apenas nomes e informações verdadeiras quando o aviso for apresentado como compra, cadastro ou resultado real.

## Antes de publicar

Revise preço, promessa de faturamento, bônus, garantia, vagas, notificações e link do checkout. Mantenha apenas informações verdadeiras e comprováveis.
