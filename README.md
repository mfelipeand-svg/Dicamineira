# Catálogo Digital — Dica Mineira & BigChef

Catálogo digital responsivo em HTML, CSS e JavaScript puro, sem frameworks e sem etapa de build.

## Estrutura

```text
.
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── foto-cesta-pao-de-queijo.jpg
    ├── logo-bigchef.png
    ├── logo-dica-mineira-catalogo.png
    ├── logo-dica-mineira.png
    ├── produto-bigchef-atum.jpg
    ├── produto-bigchef-peru.jpg
    ├── produto-dm-carne-seca-alt.jpg
    ├── produto-dm-carne-seca.jpg
    └── produto-dm-provolone.jpg
```

## Como visualizar localmente

1. Baixe ou clone este repositório.
2. Mantenha a pasta `assets` ao lado do `index.html`.
3. Abra `index.html` no navegador.

Também é possível usar a extensão **Live Server** do VS Code para visualizar durante a edição.

## Publicar com GitHub Pages

1. No GitHub, abra **Settings → Pages**.
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha a branch `main` e a pasta `/ (root)`.
4. Salve. O GitHub Pages publicará o `index.html` na URL informada na própria página de configurações.

Não há dependências para instalar nem comando de build.

## Observações

- As imagens do catálogo são carregadas localmente a partir de `assets/`.
- As fontes Playfair Display e DM Sans são carregadas do Google Fonts; se a conexão externa não estiver disponível, o navegador usará as fontes alternativas definidas no CSS.
- Os botões de contato usam o WhatsApp informado no projeto.
- A versão `dica_mineira_catalogo_arquivo_unico.html` foi mantida fora deste pacote de publicação porque duplica as imagens em Base64. O arquivo principal de publicação é `index.html`.
