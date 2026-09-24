# FITtty

Landing page de página única para um app de fitness. É só a página de divulgação: o app não
existe, e os prints em `images/` são telas do produto imaginado.

## Como rodar

Abra o `index.html` no navegador. Sem build. A única dependência externa é a fonte Inter, que
vem do Google Fonts.

## Decisões

As cores, o espaçamento e a largura máxima saem de variáveis no `:root` do `style.css`, então
trocar a paleta é mexer em um bloco só. O layout é pensado primeiro para o celular, com um
breakpoint único em 800px para a versão larga.

A página respeita as preferências do sistema: tem versão escura em `prefers-color-scheme` e
desliga as animações de entrada em `prefers-reduced-motion`.

## O que não tem

Não tem app para baixar, então os botões "Baixar o app" apontam para a própria seção
`#download`. O rodapé também não tem links.
