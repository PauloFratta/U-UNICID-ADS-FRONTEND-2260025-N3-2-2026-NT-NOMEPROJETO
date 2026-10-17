# EcoConecta — escopo e contexto do projeto

## Identificação

- **Projeto:** EcoConecta
- **Disciplina:** Desenvolvimento Front-end para Web — UNICID
- **Período:** 2026
- **Natureza:** projeto acadêmico; a organização, as pessoas, os contatos e os indicadores apresentados no site são fictícios.

## Visão geral

O EcoConecta é um site institucional que apresenta uma iniciativa fictícia de reciclagem inclusiva. A proposta é aproximar moradores, escolas, empresas e cooperativas de catadores para ampliar a destinação correta de materiais recicláveis e dar visibilidade ao trabalho de quem atua na coleta seletiva.

## Problema e justificativa

Materiais recicláveis podem acabar em aterros ou no descarte irregular, enquanto catadoras e catadores nem sempre têm reconhecimento, segurança e renda justa. O projeto usa informação e educação ambiental para mostrar como a participação da comunidade pode apoiar a coleta seletiva e a economia solidária.

## Público-alvo

- Moradores interessados em separar e encaminhar recicláveis.
- Catadoras, catadores e cooperativas de reciclagem.
- Escolas, educadores, empresas e organizações comunitárias.
- Pessoas com deficiência, consideradas desde o planejamento da navegação e do conteúdo.

## Objetivos

1. Explicar a causa, a missão e as formas de atuação do EcoConecta.
2. Orientar o público sobre coleta seletiva e participação comunitária.
3. Apresentar projetos e resultados fictícios de forma clara e identificada como acadêmica.
4. Oferecer informações de contato e um formulário acessível para aproximar interessados da iniciativa.

## Escopo funcional

A entrega acadêmica prevê dez páginas HTML interligadas:

| Página | Conteúdo esperado |
| --- | --- |
| `index.html` | Apresentação do tema, destaques e navegação principal. |
| `sobre.html` | História, missão, visão e valores da iniciativa. |
| `projetos.html` | Projetos de sustentabilidade e impacto social. |
| `impacto.html` | Indicadores, tabelas e resultados fictícios. |
| `acessibilidade.html` | Medidas de inclusão e orientações de acessibilidade. |
| `galeria.html` | Imagens com legendas e indicação de fontes. |
| `midia.html` | Conteúdo multimídia com vídeo, áudio e iframe. |
| `noticias.html` | Notícias, artigos ou conteúdo de blog fictícios. |
| `contato.html` | Dados fictícios da equipe e formulário com validação HTML5. |
| `orcamento_hospedagem.html` | Comparação de hospedagem e domínio, com justificativa. |

As páginas devem compartilhar navegação consistente e permitir que o visitante conheça a causa, consulte os conteúdos e encontre formas de participação. JavaScript é opcional para a entrega de interface; não se presume integração real com serviços, envio de formulário ou funcionamento de backend.

## Requisitos e critérios de qualidade

- **Semântica:** usar elementos HTML5 apropriados, hierarquia coerente de títulos e um `<h1>` por página.
- **Acessibilidade:** idioma `pt-BR`, textos alternativos descritivos, formulários com rótulos associados, navegação por teclado, foco visível, contraste adequado e ARIA quando necessário.
- **Responsividade:** apresentar e permitir a navegação em celular, tablet e desktop; adotar abordagem mobile-first.
- **Desempenho e manutenção:** preferir HTML e CSS claros, imagens otimizadas e componentes visuais consistentes.
- **SEO básico:** títulos, descrições e estrutura de cabeçalhos adequados em cada página.
- **Validação:** conferir o HTML no validador W3C e testar navegação e acessibilidade antes da entrega.
- **Conteúdo confiável:** identificar como fictícios os dados, contatos e resultados usados no projeto; não inserir dados pessoais reais.

## Stack e organização

O código existente usa HTML5 e CSS3 sem framework. As páginas ficam na raiz; `css/style.css` é a folha de estilos principal vinculada às páginas existentes. A pasta `img/` contém a ilustração usada na página inicial. A estrutura observada também inclui `images/` e `styles/globals.css`; antes de reutilizá-las, confirme se são pertinentes ao EcoConecta.

```text
/
├── .cursor/
│   └── rules/                 # Arquivos .mdc carregados pelo Cursor
├── css/
│   └── style.css
├── docs/
│   ├── readme.md              # Este contexto e escopo
│   └── rules/                 # Conteúdo documentado das regras
├── img/
├── index.html
├── sobre.html
└── impacto.html
```

## Estado atual e limites

No momento da documentação, estão presentes `index.html`, `sobre.html` e `impacto.html`. As outras sete páginas fazem parte do escopo previsto, mas ainda precisam ser desenvolvidas. Portanto, os links para elas não significam que seus conteúdos já existam.

Este repositório representa a interface acadêmica do projeto. Não estão confirmados ou incluídos no estado atual: backend, API, banco de dados, publicação, assistente de IA, processamento real de formulários ou dados reais de cooperativas. Qualquer ampliação desse escopo deve ser acordada pela equipe antes da implementação.

## Regras para desenvolvimento assistido por IA

As regras completas ficam em [`rules/`](rules/). Os arquivos correspondentes em `.cursor/rules/` fazem referência a elas para que o Cursor aplique as orientações automaticamente por escopo. Revise as alterações e os comandos sugeridos pela IA antes de aceitá-los; não publique segredos nem faça ações externas sem autorização da equipe.
