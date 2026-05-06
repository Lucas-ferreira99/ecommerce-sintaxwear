# Sintaxwear - Ecommerce de Tênis e Sneakers

## Descrição

A **Sintaxwear** é uma marca fictícia de tênis e sneakers que combina estilo urbano com tecnologia avançada. Este projeto é um site ecommerce estático desenvolvido para apresentar a coleção de calçados modernos e confortáveis para todas as ocasiões. O site permite aos usuários explorar categorias de produtos, visualizar o hero/banner principal e navegar por seções como Masculino, Feminino e Outlet.

O site é totalmente responsivo, adaptando-se a dispositivos móveis, tablets e desktops.

## Funcionalidades

- **Header Responsivo**: Navegação principal com menu mobile (hamburger) que desliza da direita em telas menores.
- **Seção Hero**: Banner principal com chamada para ação (botões "Ver modelos" e "Comprar").
- **Categorias de Produtos**: Cards interativos para categorias como Casual, Moderno e Esporte, com overlays e links.
- **Footer**: Informações de contato, redes sociais e links úteis (não implementado no HTML atual, mas estruturado no CSS).
- **Ícones SVG**: Uso de ícones vetoriais para logo, menu, usuário, ajuda, carrinho e redes sociais.
- **Imagens de Produtos**: Galeria de imagens JPG para diferentes estilos de tênis.

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica do site.
- **CSS3**: Estilização responsiva com variáveis CSS, flexbox e media queries.
- **SVG**: Ícones vetoriais para melhor escalabilidade.

## Estrutura de Arquivos

```
ecommerce-sintaxwear/
├── index.html                 # Arquivo principal do site
├── README.md                  # Este arquivo
├── CSS/
│   └── components/
│       ├── reset.css          # Reset de estilos padrão
│       ├── variables.css      # Variáveis CSS (cores, fontes, etc.)
│       ├── base.css           # Estilos base (body, etc.)
│       ├── header.css         # Estilos do cabeçalho e navegação
│       ├── hero.css           # Estilos da seção hero/banner
│       ├── product-category.css # Estilos das categorias de produtos
│       ├── product-grid.css   # Estilos da grade de produtos
│       └── footer.css         # Estilos do rodapé
├── icons/
│   ├── logo.svg               # Logo da marca
│   ├── hamburguer.svg         # Ícone do menu mobile
│   ├── user.svg               # Ícone de usuário
│   ├── help.svg               # Ícone de ajuda
│   ├── bag.svg                # Ícone do carrinho
│   ├── facebook.svg           # Ícone do Facebook
│   ├── instagram.svg          # Ícone do Instagram
│   ├── tiktok.svg             # Ícone do TikTok
│   └── whatsapp.svg           # Ícone do WhatsApp
└── images/
    ├── casual.jpg             # Imagem para categoria Casual
    ├── casual-grig.jpg        # Imagem de grade para Casual
    ├── moderno.jpg            # Imagem para categoria Moderno
    ├── esportivo.jpg          # Imagem para categoria Esporte
    ├── feminino-grid.jpg      # Imagem de grade para Feminino
    ├── futurista.jpg          # Imagem para categoria Futurista
    ├── futurista-grid.jpg     # Imagem de grade para Futurista
    ├── hero.css.jpg           # Imagem do hero (nota: extensão .css.jpg pode ser erro)
    ├── menu-grid.jpg          # Imagem de grade para menu
    ├── roxo-grid.jpg          # Imagem de grade roxa
    └── ztênis preto azul-gridl.jpg # Imagem de tênis preto e azul
```

## Instalação e Configuração

Este é um site estático, então não requer instalação de dependências ou servidor backend.

1. **Clone ou baixe o repositório**:
   ```
   git clone https://github.com/seu-usuario/ecommerce-sintaxwear.git
   ```

2. **Abra o arquivo `index.html`** em qualquer navegador web moderno (Chrome, Firefox, Edge, etc.).

Não há necessidade de servidor local; o site funciona diretamente no navegador.

## Uso

- **Navegação**: Use o menu no header para acessar seções como Masculino, Feminino e Outlet.
- **Menu Mobile**: Em dispositivos móveis, clique no ícone de hamburger para abrir o menu deslizante.
- **Explorar Categorias**: Clique nos cards de categoria para visualizar produtos.
- **Links Sociais**: No footer (quando implementado), acesse redes sociais via ícones.

## Desenvolvimento

Para editar o site:

- Modifique os arquivos HTML em `index.html`.
- Ajuste estilos em `CSS/components/`.
- Adicione novas imagens em `images/` e ícones em `icons/`.

Certifique-se de testar a responsividade em diferentes tamanhos de tela.

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Fork o repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto é licenciado sob a [MIT License](https://opensource.org/licenses/MIT). Sinta-se à vontade para usar e modificar conforme necessário.

## Contato

Para dúvidas ou sugestões, entre em contato via [email] ou redes sociais.

---

Desenvolvido com ❤️ para a Sintaxwear.