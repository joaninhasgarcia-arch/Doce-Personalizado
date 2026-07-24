# Doce Modelagem — Quiz de Vendas

Este pacote contém somente:

- `index.html` — página completa, com CSS e JavaScript incorporados.
- `README.md` — instruções rápidas.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie `index.html` e `README.md` para a raiz do repositório.
3. Abra **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/root`.
6. Salve e aguarde a publicação.

## Alterar o link de checkout

Abra o final do arquivo `index.html` e procure:

```js
checkoutUrl: "https://SEU-LINK-DE-CHECKOUT-AQUI.com"
```

Substitua pelo link real do checkout.

## Alterar preço, nome e textos

Pesquise no `index.html` pelos textos:

- `Doce Modelagem`
- `R$ 27,90`
- `Docinhos de leite em pó lucrativos`

Edite diretamente, sem precisar modificar a estrutura da página.

## Colocar as imagens da expert e dos produtos

O protótipo usa ilustrações feitas em CSS para manter tudo dentro do HTML.
Quando as imagens finais estiverem prontas, substitua os blocos abaixo por tags `<img>`:

- `.hero-art` — imagem principal da expert e dos doces.
- `.visual-card` — imagem de produção, ingredientes ou produtos.
- `.student-art` — resultados das alunas.

Exemplo:

```html
<img src="https://seu-site.com/imagem.jpg" alt="Docinhos personalizados">
```

Para continuar mantendo apenas um HTML, também é possível converter as imagens para Base64 e colocá-las diretamente no atributo `src`.

## Cronômetro

No bloco `CONFIG`, altere:

```js
countdownSeconds: 9 * 60 + 54
```

O valor representa minutos e segundos.

## Notificações de cadastro

Os nomes aparecem em:

```js
toastNames: ["Mariana", "Fernanda", "Juliana", "Roberta", "Ana"]
```

Use apenas nomes de clientes reais ou troque a mensagem por uma notificação genérica.

## Observação importante

Antes de publicar, revise promessas de renda, quantidade de vagas, depoimentos, preço e prazo da promoção. Mantenha somente informações verdadeiras e comprováveis.
