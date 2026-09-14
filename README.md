# <Barber Dev>

**Assunto:** Site de uma Babearia
**Equipe:** Gabriel Kock · Ingrid Picorelle · Thome Carlos Pereira · Caio Henrrique Ferreira Jaqueira · Lucca Caixeta Lopes Silva
**Disciplina:** ARA0062 — Desenvolvimento Web em HTML5, CSS, JavaScript e PHP
**Centro Universitário Newton Paiva · 2026/2**

---

## Sobre o projeto

Um sistema web para uma barbearia, criado para que os clientes possam explorar os serviços oferecidos (como corte e barba),
 escolher seu profissional de preferência e agendar um horário de atendimento de forma autônoma.

O projeto contará com páginas de cadastro e de autenticação para dois tipos de usuários: clientes e administradores. A interface principal entregará um formulário de seleção de serviços integrado a um calendário interativo em JavaScript para a escolha de horários. Para a gestão da barbearia, haverá um painel administrativo processado em PHP. Todos os dados de usuários, serviços ofertados e horários agendados serão persistidos no banco de dados relacional.

---

## Identidade visual

*Estas são as decisões que o `frontend/css/estilo.css` aplica. Elas estão aqui
para quem lê o repositório entender **por que** o site tem essa cara — e para
a equipe não mudar de ideia a cada aula.*

### Paleta

| Papel | Cor | Por que esta |
|---|---|---|
| `--principal` | `#______` | <onde aparece, e o que ela comunica sobre o assunto> |
| `--sobre-principal` | `#______` | <o texto que fica em cima da principal> |
| `--apoio` | `#______` | <botões, destaques> |
| `--fundo` | `#______` | <o fundo da página> |
| `--superficie` | `#______` | <cartões e conteúdo> |
| `--texto` | `#______` | <a cor das letras> |

**Contraste conferido** em <https://webaim.org/resources/contrastchecker/>:

```
--texto sobre --superficie ......... __,_:1
--principal sobre --superficie ..... __,_:1
--sobre-principal sobre --principal  __,_:1
```

*Todos precisam ficar em 4,5:1 ou acima.*

### Tipografia

**Fonte:** <"Nome da fonte">, com plano B `<fonte de sistema>, sans-serif`
**Pesos:** 400 e <600 ou 700>
**Por que esta:** <uma frase ligando a fonte ao assunto>

**Escala:** `h1` 2.5rem · `h2` 1.75rem · `h3` 1.25rem · corpo 1rem

### Segundo tema

**Arquivo:** `frontend/css/tema-<nome>.css`
**O que é:** <em que situação este tema seria usado — modo escuro, uma data
comemorativa, uma campanha>

Para ligá-lo, tire o comentário da linha do `<link>` no `frontend/index.html`.
Ela vem **depois** do `estilo.css`.

---

## Como abrir

1. Abra **a pasta inteira** no VS Code (*Arquivo → Abrir Pasta*).
2. Abra `frontend/index.html` e clique em **Go Live** (extensão *Live Server*).

---

## Estrutura

```
.
├─ README.md                 esta folha de rosto
├─ frontend/                 tudo o que roda no navegador
│   ├─ index.html
│   ├─ css/
│   │   ├─ estilo.css        a folha do projeto
│   │   └─ tema-<nome>.css   o segundo tema: só variáveis
│   ├─ js/
│   │   └─ script.js         vazio até o ciclo 6
│   └─ img/
└─ backend/                  tudo o que roda no servidor
    ├─ config/
    │   └─ conexao.php       vazio até o ciclo 8
    └─ processa-contato.php
```

---

## Quem fez o quê

*Uma linha por integrante. É o mapa de quem procurar quando algo quebra — e
bate com o histórico de commits.*

| Integrante | Parte da folha de estilo |
|---|---|
| Gabriel Kock | |
| Thome Carlos| |
| Ingrid Picorelle| |
| <Nome 4> | |
| <Nome 5> | |
