# Doce Modelagem — Quiz atualizado

Esta versão parte da oferta final premium e inclui somente os ajustes solicitados nesta atualização.

## Arquivos

- `index.html` — página completa, com CSS, JavaScript e imagens incorporadas no próprio arquivo.
- `README.md` — instruções resumidas.

Não existe pasta `assets`. As imagens usadas nesta atualização estão em Base64 dentro do `index.html`.

## Alterações realizadas

- inserida a arte principal da oferta com Mariana Alves, aplicativo, garantia e docinhos;
- inserida a foto de Mariana Alves ao lado do carro na seção “Dos docinhos ao meu primeiro carro”;
- mantidos os demais espaços reservados para os três modelos de docinhos e para a imagem final da expert;
- as perguntas de escolha única agora avançam automaticamente cerca de 0,4 segundo após a opção ser selecionada;
- o botão **Continuar** foi mantido como alternativa de navegação e acessibilidade;
- o carrossel de depoimentos inicia a troca automática quando entra na área visível da tela e pausa quando sai dela;
- setas, pontos e gesto de deslizar do carrossel continuam funcionando.

## Configurar o checkout

No fim do `index.html`, procure por:

```javascript
checkoutUrl: "https://SEU-LINK-DE-CHECKOUT-AQUI.com"
```

Substitua pelo link real do checkout. Todos os botões de compra usam esse endereço.

## Publicação no GitHub Pages

1. Envie `index.html` e `README.md` para a raiz do repositório.
2. Abra **Settings → Pages**.
3. Escolha a branch principal e a pasta `/root`.
4. Salve e aguarde a publicação.
