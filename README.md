# Doce Modelagem — Quiz com Mariana Alves (abertura alinhada)

Este pacote contém somente dois arquivos:

- `index.html` — página completa com HTML, CSS, JavaScript e todas as imagens incorporadas em Base64.
- `README.md` — instruções de publicação e edição.

## Correções desta versão

- Removido o comentário escapado que aparecia como texto no topo da página.
- Abertura reorganizada para acompanhar o alinhamento, a hierarquia e os espaçamentos da página de referência.
- Título, parágrafos, destaques e margens foram recalibrados para celular e computador.
- Retirado o texto “com Mariana Alves” do cabeçalho inicial para manter a composição mais limpa; a especialista continua apresentada na seção seguinte.
- Removida a legenda sobreposta à imagem principal.
- Mantidas a imagem da Mariana Alves, a apresentação da especialista, a vitrine de doces, a prova social, o quiz, o cronômetro e a oferta.
- Todas as imagens continuam embutidas no próprio `index.html`; não existe pasta `assets`.

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
