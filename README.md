# Doce Modelagem — Quiz com oferta final premium

Esta versão mantém todas as etapas anteriores do quiz e altera **somente a última sessão de oferta**, seguindo a estrutura visual das referências enviadas.

## Arquivos

- `index.html` — página completa, com estilos e scripts no próprio arquivo.
- `README.md` — estas instruções.

Não existe pasta `assets` nesta versão.

## O que foi acrescentado na oferta final

- cronômetro e cartão de qualificação;
- lista completa do treinamento;
- apresentação dos quatro bônus;
- cartões de preço e botões de compra em três pontos;
- aviso de escassez e compra segura;
- história “Dos docinhos ao meu primeiro carro”;
- carrossel horizontal para três modelos;
- prova social da comunidade e avaliações;
- garantia de sete dias;
- estrutura totalmente adaptada para celular.

## Locais reservados para as próximas imagens

Os espaços estão identificados no HTML pelas propriedades `data-image-slot`:

1. `app-expert` — arte principal com Mariana Alves, aplicativo, garantia e docinhos;
2. `car-story` — foto da Mariana ao lado do carro;
3. `model-1` — primeiro modelo de docinho;
4. `model-2` — segundo modelo de docinho;
5. `model-3` — terceiro modelo de docinho;
6. `final-expert` — foto final da Mariana preparando os docinhos.

Por enquanto, esses pontos exibem cartões elegantes de marcação. Quando as imagens forem enviadas, eles podem ser substituídos por imagens em Base64 dentro do próprio `index.html`.

## Configurar o checkout

No final do `index.html`, procure por:

```javascript
checkoutUrl: "https://SEU-LINK-DE-CHECKOUT-AQUI.com"
```

Troque pelo endereço real do checkout. Todos os botões de compra usam esse mesmo link.

## Publicação no GitHub Pages

1. Crie ou abra o repositório.
2. Envie `index.html` e `README.md` para a raiz.
3. Abra **Settings → Pages**.
4. Escolha a branch principal e a pasta `/root`.
5. Salve e aguarde a publicação.
