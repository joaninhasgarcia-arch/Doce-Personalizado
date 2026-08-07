# Bolos Gelados Gourmet — página de vendas em formato de quiz

Página completa de vendas em formato de quiz para o treinamento **Bolos Gelados Gourmet**, preparada para publicação no GitHub Pages.

## Atualização desta versão

- Abertura revisada para reduzir repetições e deixar a promessa mais direta.
- Lista inicial atualizada com 8 sabores gourmet:
  - Ninho com Nutella
  - Chocolate Trufado
  - Morango com Ninho
  - Bombom de Morango
  - Mousse de Chocolate Branco
  - Prestígio Cremoso
  - Coco com Abacaxi
  - Oreo Cremoso
- Carrossel da etapa final substituído pelas 8 imagens novas correspondentes.
- Imagens ajustadas ao formato vertical **4:5**, com enquadramento central e legenda visível de cada sabor.
- Pontos de navegação e textos alternativos do carrossel atualizados.
- Capa, vitrine inicial, especialista, ingredientes, depoimentos, trabalhos das alunas e arte da oferta final mantidos com as imagens atualizadas da versão anterior.
- Estrutura do quiz, cronômetros, botões e demais seções preservados.

## Imagens

Todas as imagens estão incorporadas em Base64 dentro do próprio `index.html`. Não é necessário enviar uma pasta separada de imagens para o GitHub.

## Arquivos

- `index.html` — página completa e responsiva.
- `README.md` — informações e instruções desta versão.

## Publicação no GitHub Pages

1. Extraia o arquivo ZIP.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. No GitHub, abra **Settings > Pages**.
4. Selecione a branch principal e a pasta raiz.
5. Salve e aguarde a publicação.


## Meta Pixel

Esta versão já inclui o **Meta Pixel ID `1067939512402354`** no `index.html`, com o evento padrão **PageView** disparado no carregamento da página.

O **token de acesso da API de Conversões não foi colocado no HTML**, porque tokens de acesso são credenciais privadas e ficariam expostos publicamente no navegador/GitHub. Caso a API de Conversões (CAPI) seja configurada depois, o token deve ficar somente em um ambiente seguro no servidor/backend.

## Checkout

Checkout configurado na **Cakto**:

Todos os botões de compra da oferta estão configurados para abrir:

```text
https://pay.cakto.com.br/3ft7qvb_1026273
```

O endereço fica centralizado em `CONFIG.checkoutUrl`, próximo ao final do `index.html`, facilitando futuras alterações.

## Observação comercial

As possibilidades de renda apresentadas são objetivos de venda, não garantia de faturamento. Os resultados dependem da execução, divulgação, preço, demanda local e constância.
