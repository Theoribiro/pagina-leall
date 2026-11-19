# 🪐 Landing Page — LEALL

Landing page desenvolvida como projeto de estudo de desenvolvimento web, inspirada na identidade visual e na trajetória do rapper brasileiro LEALL.

O site apresenta informações sobre o artista, links para suas plataformas, seus principais projetos musicais e uma seção dedicada ao álbum *Esculpido a Machado*.

> **Aviso:** projeto de caráter educacional e não oficial. Não possui vínculo com o artista LEALL.

---

## Funcionalidades

- **Header fixo** com navegação por âncoras e rolagem suave até cada seção:
  - **Home:** leva à seção "Mas afinal, quem é Leall?"
  - **Mídias:** leva aos cards de plataformas (TikTok, Instagram, YouTube, Spotify, X e Deezer)
  - **Álbuns:** leva à seção "Álbuns e Projetos"
- **Botão "Ouvir"** no header, que abre o perfil do artista no Spotify em nova aba
- Seção de apresentação do artista, com biografia, informações principais e discografia
- Cards de redes sociais e plataformas de música, com links externos
- Cards de álbuns e projetos, com capa, ano e descrição
- Seção dedicada ao álbum *Esculpido a Machado*
- Efeitos de hover em links, botões e cards
- Rodapé com aviso de projeto não oficial e crédito do desenvolvedor

## Responsividade

O layout se adapta a telas menores com `@media` queries (breakpoints em 950px, 768px e 600px):

- Header com itens que quebram linha em telas pequenas
- Conteúdo principal e imagens reorganizados em coluna
- Cards de álbuns e de redes sociais em coluna única
- Seção *Esculpido a Machado* com foto e texto empilhados

## Tecnologias

- HTML5
- CSS3 (Flexbox, Grid, `position: fixed`, `scroll-behavior`, media queries)

## Estrutura do projeto

```
/
├── index.html
├── style.css
├── imagens e capas (.jpg / .png)
└── README.md
```

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Theoribiro/NOME-DO-REPOSITORIO.git
   ```
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` no navegador (ou use a extensão Live Server do VS Code).

## O que pratiquei neste projeto

- Estruturação semântica de páginas (`header`, `nav`, `main`, `section`, `footer`)
- Navegação interna com âncoras (`href="#id"`) e rolagem suave
- Layouts com Flexbox e CSS Grid
- Responsividade com media queries
- Estilização de componentes (cards, botões, header fixo)
- Efeitos de interação com CSS
- Organização de um projeto para portfólio

## Desenvolvedor

**Theo Renan**
GitHub: [Theoribiro](https://github.com/Theoribiro)

Projeto desenvolvido para fins educacionais e de estudo.
