# Bolos Gelados Gourmet — página de vendas em formato de quiz

Página completa de vendas em formato de quiz para o treinamento **Bolos Gelados Gourmet**, pronta para publicação no GitHub Pages.

## Atualização desta versão

Foram alteradas **somente** as partes solicitadas da página:

- seção final de **bônus** redesenhada para ficar no estilo visual da página de referência;
- bônus apresentados em cards organizados, com imagem quadrada **1:1** e texto ao lado;
- inclusão das imagens dos bônus **diretamente dentro do `index.html`** (sem pasta `assets`);
- inclusão de um novo card para o bônus **Acesso Vitalício ao Treinamento**;
- criação de **duas ofertas lado a lado** na seção final:
  - **Plano Essencial — R$ 10,00**
  - **Plano Completo — R$ 20,90** (com destaque de **Mais vendido**)
- botão da oferta de **R$ 10,00** apontando para o checkout antigo;
- botão da oferta de **R$ 20,90** apontando para o novo checkout informado;
- ajuste do comportamento dos botões para aceitar checkout individual por oferta.

## Bônus exibidos na página

1. **Guia de Conservação e Durabilidade**
2. **Acesso Vitalício ao Treinamento**
3. **Embalagem e Apresentação**
4. **Precificação Inteligente**
5. **Como Vender Sem Aparecer**

## Imagens

Todas as imagens dos bônus estão incorporadas em Base64 dentro do próprio `index.html`.

Não é necessário enviar nenhuma pasta extra de imagens para o GitHub.

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

Esta versão mantém o **Meta Pixel ID `1067939512402354`** no `index.html`, com o evento padrão **PageView** disparado no carregamento da página.

## Checkouts

### Oferta de R$ 10,00
```text
https://pay.cakto.com.br/3ft7qvb_1026273
```

### Oferta de R$ 20,90
```text
https://pay.cakto.com.br/c2gc4iw
```

O `CONFIG.checkoutUrl` padrão foi atualizado para a oferta de **R$ 20,90**, e a oferta de **R$ 10,00** usa um link próprio no botão correspondente.

## Observação comercial

As possibilidades de renda apresentadas são objetivos de venda, não garantia de faturamento. Os resultados dependem da execução, divulgação, preço, demanda local e constância.

## Atualização — destaque da oferta completa e rolagem para escolha

- O botão **“quero garantir minha vaga”** logo abaixo do carrossel de sabores agora faz uma **rolagem suave** até a área de escolha entre as ofertas de R$ 10,00 e R$ 20,90, em vez de abrir diretamente o checkout.
- A oferta **Plano Completo — R$ 20,90** recebeu mais destaque visual, mantendo a identidade da página: selo **⭐ MAIS VENDIDO ⭐**, indicação de **melhor custo-benefício**, detalhes em verde, estrelas e maior destaque para preço e botão.
- O texto **“⚠️ Corra! Faltam apenas 8 vagas disponíveis nesta oferta.”** foi mantido sem alteração.
- Os checkouts e os demais conteúdos da página foram preservados.

## Ajuste de navegação — versão v4

- Os dois botões adicionais **“quero garantir minha vaga”** da parte final da página não abrem mais o checkout diretamente.
- Agora, assim como o botão abaixo do carrossel de sabores, eles fazem **rolagem suave automática** até a seção com as duas opções de oferta (**R$ 10,00** e **R$ 20,90**).
- Somente os botões dentro dos próprios cards das duas ofertas seguem para seus respectivos checkouts.
