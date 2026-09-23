# Barber Dev

---
## Assunto

Barbearia tradicional com agendamento online de serviços de corte, barba e catálogo de produtos de cuidados masculinos.

---

**Equipe:**
Gabriel Kock · Ingrid Picorelle · Thome Carlos Pereira · Caio Henrrique Ferreira Jaqueira · Lucca Caixeta Lopes Silva

**Disciplina:** 
ARA0062 — Desenvolvimento Web em HTML5, CSS, JavaScript e PHP

**Centro Universitário Newton Paiva · 2026/2**

---

## Sobre o projeto

Um sistema web para uma barbearia, criado para que os clientes possam explorar os serviços oferecidos (como corte e barba),
 escolher seu profissional de preferência e agendar um horário de atendimento de forma autônoma.

O projeto contará com páginas de cadastro e de autenticação para dois tipos de usuários: clientes e administradores. A interface principal entregará um formulário de seleção de serviços integrado a um calendário interativo em JavaScript para a escolha de horários. Para a gestão da barbearia, haverá um painel administrativo processado em PHP. Todos os dados de usuários, serviços ofertados e horários agendados serão persistidos no banco de dados relacional.

---

## Identidade visual

### Paleta

| Papel | Cor | Por que esta |
|---|---|---|
| `--principal` | `#2b1e1a` | Marrom couro escuro rementendo as barberias tradicionais |
| `--sobre-principal` | `#ffffff` | Texto branco com alto contraste sobre o marrom principal |
| `--apoio` | `#8c2d19` | Vermelho terracota para botões secundários/detalhes |
| `--fundo` | `#f4efe6` | Fundo creme rementendo as barbearias tradicionais |
| `--superficie` | `#ffffff` | Fundo branco para cartões, tabelas e formulários |
| `--texto` | `#1c1917` | Grafite bem escuro para o corpo do texto |

**Contraste conferido** em <https://webaim.org/resources/contrastchecker/>:

```
--texto sobre --superficie ......... 17,48:1
--principal sobre --superficie ..... 16,11:1
--sobre-principal sobre --principal  16,11:1
```

### Tipografia

**Fonte:** <"Nome da fonte">, com plano B `<fonte de sistema>, sans-serif`
**Pesos:** 400 e <600 ou 700>
**Por que esta:** <uma frase ligando a fonte ao assunto>

**Escala:** `h1` 2.5rem · `h2` 1.75rem · `h3` 1.25rem · corpo 1rem

### Segundo tema

**Arquivo:** 
`frontend/css/tema-escuro.css`
**O que é:** 
O tema escuro foi criado para ofercer uma experiencia de navegação noturna mais confortável para os clientes.

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
│   │   └─ tema-escuro.css   o segundo tema: só variáveis
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

| Integrante | Parte da folha de estilo |
|---|---|
| Gabriel Kock |:root e tema e o tema-escuro |
| Thome Carlos| |
| Ingrid Picorelle| |
| Caio Henrique | |
| <Nome 5> | |
