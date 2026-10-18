# Brasil Open Personalizados

Site de apresentação e vendas da **Brasil Open Personalizados**: presentes personalizados com arte autoral (canecas, azulejos, ecobags e garrafas). Santa Cruz do Sul, RS.

- Instagram: [@brasil_open](https://www.instagram.com/brasil_open)

## Estrutura

```
index.html      página do site (HTML, CSS e JS em um único arquivo)
logo.png        logo da marca
catalogo.pdf    catálogo de produtos
fotos/          fotos dos produtos
.nojekyll       evita processamento do Jekyll no GitHub Pages
```

## Como editar

Abra o `index.html` e procure o bloco **EDITE AQUI** no começo do script:

- `CONFIG`: links do WhatsApp, Instagram e catálogo.
- `PRODUTOS`: nome, descrição, detalhe, preço e foto de cada produto.
- `FOTOS`: fotos da galeria "Nossos trabalhos". Para adicionar uma, coloque a imagem na pasta `fotos/` e copie uma linha da lista.

## Publicar no GitHub Pages

1. Envie todos os arquivos para a raiz de um repositório.
2. Vá em **Settings → Pages**.
3. Em **Branch**, escolha `main` e a pasta `/ (root)`, e salve.
4. O site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.
