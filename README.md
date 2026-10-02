#  Exercício Fashion

Página web estática de uma marca de moda fictícia (**Fast Fashion**), criada como exercício prático de **HTML5 e CSS3**. O objetivo é reproduzir fielmente o layout de referência (`layout_final.jpg`) usando apenas HTML e CSS, sem frameworks ou JavaScript.

## 📸 Layout de referência

O design a ser reproduzido está em [`layout_final.jpg`](layout_final.jpg).

## 🧱 Estrutura da página

A página é composta por:

| Seção | Descrição |
|-------|-----------|
| **Header / Menu** | Barra escura com logotipo e navegação (*portfolio*, *about us*, *contact*), seguida de uma imagem de topo (banner). |
| **Portfolio** | Título "New Fashion Everything Never Enough" com texto de apresentação centralizado. |
| **Galeria** | Três modelos lado a lado (Vest Romasa, Jacket Fima, Jacket Black Kira), cada um com foto, título e slogan. |
| **About** | Bloco com imagem de fundo decorativa e texto sobreposto ("Everything Never Enough / Just Fashion"). |
| **Contato** | Chamada "Call me now for design" com telefone. |
| **Mapa** | Google Maps incorporado via `<iframe>`. |
| **Rodapé** | Copyright © fastfashion.com. |

## 📁 Estrutura de arquivos

```
Exercicio-Fashion-main/
├── .vscode/
│   └── settings.json      # Configuração do Live Server (porta 5501)
├── imagens/
│   ├── bg_detalhe.png     # Fundo da seção About
│   ├── logo.png           # Logotipo
│   ├── modelo1.jpg        # Foto da galeria
│   ├── modelo2.jpg        # Foto da galeria
│   ├── modelo3.jpg        # Foto da galeria
│   └── topo.jpg           # Banner do topo
├── conteudo.txt           # Textos fornecidos para o exercício
├── index.html             # Estrutura da página
├── syle.css               # Estilos da página
└── layout_final.jpg       # Layout de referência
```

## 🛠️ Tecnologias

- **HTML5**: estrutura semântica (`header`, `nav`, `main`, `article`, `section`, `footer`)
- **CSS3**: Flexbox, posicionamento (`relative` / `absolute`), seletores de classe e id
- **Google Maps Embed**: mapa incorporado por `<iframe>`

## ▶️ Como executar

Não há dependências nem etapa de build.

**Opção 1: direto no navegador**

1. Baixe ou clone o repositório.
2. Abra o arquivo `index.html` no navegador.

**Opção 2: com Live Server (VS Code)**

1. Abra a pasta do projeto no VS Code.
2. Instale a extensão **Live Server**.
3. Clique em **Go Live**. O projeto já está configurado para rodar na porta `5501`.

## 🎨 Detalhes de estilo

- Fonte: `Tahoma, Arial, sans-serif`
- Largura do conteúdo principal: `1025px`, centralizado
- Cores principais:
  - Header: `#162028`
  - Rodapé: fundo `#001018` e texto `#053449`
  - Chamada de contato: `#053449`
- Galeria montada com `display: flex`
- Seção *About* com texto posicionado sobre a imagem usando `position: relative`



