

# Landing Page AGROVANT — Drone Agrícola

Projeto prático da unidade curricular de **Linguagem de Marcação**, do curso Técnico em
Desenvolvimento de Sistemas — SESI/SENAI Itapeva.

## Identificação

| | |
|---|---|
| **Aluno** | [Igor Escudeiro Gouveia] |
| **Turma** | [2° ano B E.M.] |
| **Professor** | Rafael Ribas |
| **Entrega** | [24/08/2026] |

## Sobre o projeto

Landing page de apresentação do **AGROVANT**, um drone agrícola fictício voltado à
pulverização e ao monitoramento de lavouras. O objetivo da página é convencer o
agricultor a agendar uma demonstração do produto.

O layout foi construído a partir de um protótipo no Figma, com HTML semântico e CSS,
sem frameworks.

A principal dificuldade que eu encontrei no projeto foi ajustar as imagem no site e utilizar a teg Z-index, além disso tive dificuladades para ajustar a responsividade, apartir de medias flexiveis e da lógica utilizada no final, do site. 

## Página publicada

**[cole aqui o link da sua página no ar]**

<!-- https://projetodrone-seven.vercel.app/ -->

## Estrutura de pastas

```
landing-page-drone/
├── index.html      página principal
├── README.md 
├── style.css       este arquivo
├── assets/
│   └──img/         estilos do projeto
                    imagens e vídeos
```

## Seções da página

- [X] Menu (cabeçalho)
- [X] Hero section
- [X] Especificações
- [X] Vídeo do produto
- [X] Cards de benefícios
- [X] Depoimentos
- [X] Formulário de contato


## Tecnologias e conceitos aplicados

- **HTML5 semântico** — `header`, `main`, `section`, `footer`
- **CSS3** com variáveis em `:root`
- **Flexbox** para os layouts
- **Design responsivo** com abordagem *mobile first* e media queries
- **Unidades relativas** (`rem`, `%`) no lugar de medidas fixas

## Responsividade

A página foi construída começando pelo celular. O CSS base atende telas pequenas e as
media queries acrescentam o comportamento das telas maiores, a partir de **768px**.

| Tela | Comportamento |
|---|---|
| Celular | [descreva: O menu mantém apenas a opção Agende, os cards de especificações ficam empilhados e as seções passam a ocupar uma única coluna. O formulário e o conteúdo da seção de agendamento também ficam um abaixo do outro.] |

| Desktop | [descreva: O menu completo aparece, os cards de especificações ficam organizados em três cards por linha, e as seções utilizam layouts horizontais, como o conteúdo de depoimentos e o formulário de agendamento.] |

## Como rodar localmente

```bash
git clone [https://github.com/igor-escudeiro/projetodrone.git]
cd [projetodrone]
```

Depois é só abrir o `index.html` no navegador.

## Créditos

- Protótipo do layout: material da disciplina
- Imagens e vídeos: material fornecido pelo professor
- Fontes: [Roboto](https://fonts.google.com/specimen/Roboto) e
  [Inter](https://fonts.google.com/specimen/Inter), via Google Fonts

---

<!-- Antes de entregar, passe a sua página pela ferramenta de autoavaliação
     indicada pelo professor. Ela mostra, critério por critério, o que ainda
     falta ajustar. -->

Projeto acadêmico, sem fins comerciais. O drone AGROVANT é fictício.