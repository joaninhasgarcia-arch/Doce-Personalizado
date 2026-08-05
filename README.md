# Doce Modelagem — Quiz com prova social em carrossel

Este pacote contém somente dois arquivos:

- `index.html` — página completa, com HTML, CSS, JavaScript e todas as imagens incorporadas em Base64.
- `README.md` — instruções de publicação e edição.

## Alterações desta versão

- A seção **“Veja alguns depoimentos das minhas alunas”** agora possui um carrossel com os depoimentos de **Juliana** e **Camila**.
- O carrossel dos depoimentos avança automaticamente enquanto a visitante permanece nessa etapa.
- Também é possível trocar o depoimento pelas setas, pelos indicadores ou deslizando o dedo no celular.
- A seção **“Alguns docinhos feitos por alunas da turma”** foi incorporada logo abaixo dos depoimentos, sem criar uma etapa separada.
- Foram inseridos os trabalhos das alunas **Juliana**, **Irene** e **Luara**.
- O carrossel dos trabalhos permite rolagem lateral e deixa uma parte do próximo cartão visível para indicar que há mais imagens.
- As etapas seguintes foram renumeradas e o funcionamento do carregamento, da oferta, do cronômetro e dos botões foi preservado.
- Todas as cinco imagens novas estão embutidas diretamente no `index.html`; não existe pasta `assets`.

## Publicar no GitHub Pages

1. Abra o repositório usado para publicar a página.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Substitua os arquivos antigos quando o GitHub solicitar confirmação.
4. Acesse **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Escolha a branch principal (`main`) e a pasta raiz (`/root`).
7. Salve e aguarde alguns minutos pela atualização.

## Alterar o checkout

Abra o `index.html` e procure por:

```js
checkoutUrl: "https://SEU-LINK-DE-CHECKOUT-AQUI.com"
```

Substitua pelo endereço real do checkout.

## Tempo de troca dos depoimentos

No JavaScript, procure por:

```js
4800
```

Esse valor representa 4,8 segundos. Aumente ou diminua para ajustar a velocidade do carrossel automático.

## Antes de publicar

Revise preço, promessa de faturamento, bônus, garantia, vagas, notificações, depoimentos e link do checkout. Mantenha apenas informações verdadeiras e comprováveis.
