# Doce Modelagem — Expert final e avisos rotativos

Esta versão mantém o quiz anterior e acrescenta os dois ajustes solicitados.

## Alterações realizadas

- A imagem enviada da Mariana Alves foi incorporada diretamente no final da oferta.
- Abaixo da imagem foi adicionada uma apresentação da expert, com texto organizado e botão de compra.
- O card da primeira etapa agora alterna automaticamente entre avisos da turma.
- A troca possui uma transição suave e ocorre a cada 6,5 segundos.
- Para não apresentar inscrições fictícias como fatos reais, os avisos padrão não usam nomes inventados.
- Caso existam inscrições reais e autorizadas, os textos podem ser alterados no array `registrationNotices`, dentro do bloco `CONFIG` no final do `index.html`.
- Todas as imagens continuam incorporadas no próprio `index.html`, sem pasta `assets`.

## Publicação no GitHub Pages

1. Extraia o ZIP.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Em **Settings > Pages**, selecione a branch principal e a pasta raiz.
4. Aguarde a publicação.

## Checkout

Substitua `https://SEU-LINK-DE-CHECKOUT-AQUI.com` pelo endereço real no bloco `CONFIG`, próximo ao final do `index.html`.
