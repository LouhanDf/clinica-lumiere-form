# 🌿 Clínica Lumière — Formulário de Agendamento

> Projeto acadêmico desenvolvido para a disciplina **Padrões Web para No-Code e Low-Code**  
> Curso: Graduação Tecnológica em IA e Automação Digital — UniFECAF / Rocketseat 2025  
> Aluno: Louhan D'Franco

---

## 📋 Sobre o Projeto

A **Clínica Lumière** é uma solução web desenvolvida para um pequeno negócio local de estética que deseja ter presença online sem contratar programadores. O projeto é composto por duas partes integradas:

| Componente | Ferramenta | Link |
|---|---|---|
| Site institucional | Webflow (AI Builder) | [clinica-lumiere-57b479.webflow.io](https://clinica-lumiere-57b479.webflow.io/) |
| Formulário de agendamento | HTML/CSS/JS + GitHub Pages | [louhandf.github.io/clinica-lumiere-form](https://louhandf.github.io/clinica-lumiere-form/) |

---

## 🎯 Problema Resolvido

Pequenos negócios locais — como clínicas de estética — frequentemente perdem clientes por não terem presença digital. Contratar um desenvolvedor é caro e inviável para quem está começando.

Esta solução oferece:
- Página institucional profissional com informações da clínica
- Formulário de agendamento online funcional
- Visual sofisticado e responsivo para mobile e desktop
- Custo zero de desenvolvimento

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

### No-Code
- **Webflow** — construção do site institucional com AI Builder
- Geração automática de HTML semântico, CSS responsivo e meta tags de SEO

### Código Manual (este repositório)
- **HTML5 semântico** — estrutura acessível com elementos nativos (`form`, `label`, `input`, `select`, `textarea`)
- **CSS3 customizado** — variáveis CSS, Flexbox, Grid, Media Queries, transições
- **JavaScript puro** — validação de formulário sem dependências externas

---

## 📁 Estrutura do Repositório

```
clinica-lumiere-form/
│
└── index.html        # Formulário completo (HTML + CSS + JS em arquivo único)
```

---

## ✨ Funcionalidades

- ✅ Formulário de agendamento com 7 campos
- ✅ Validação em tempo real com JavaScript puro
- ✅ Feedback visual de erro (borda vermelha) e sucesso (borda verde)
- ✅ Validação de e-mail com expressão regular (regex)
- ✅ Mensagem de confirmação após envio válido
- ✅ Layout responsivo (mobile, tablet, desktop)
- ✅ Acessibilidade: `aria-label`, `aria-required`, `role="alert"`, foco por teclado
- ✅ Tipografia premium com Google Fonts (Playfair Display + Lato)
- ✅ Paleta de cores customizada via variáveis CSS
- ✅ Link de retorno ao site principal no Webflow

---

## 🎨 Identidade Visual

| Elemento | Valor |
|---|---|
| Cor principal | `#C9A96E` (dourado suave) |
| Cor de fundo | `#FAF7F4` (off-white) |
| Cor de texto | `#3D2B1F` (marrom escuro) |
| Fonte títulos | Playfair Display (serifa) |
| Fonte corpo | Lato (sans-serif) |

---

## ♿ Acessibilidade Aplicada

- Hierarquia semântica de títulos (H1 → H2)
- Atributo `aria-label` em links e botões
- Atributo `aria-required` em campos obrigatórios
- `role="alert"` nas mensagens de erro (leitores de tela anunciam automaticamente)
- `role="status"` na mensagem de sucesso
- Foco visível com anel dourado em todos os elementos interativos
- Foco redirecionado ao primeiro campo com erro após tentativa de envio inválida

---

## 📱 Responsividade

- Meta tag `viewport` configurada
- Layout em grid com `grid-template-columns` adaptável
- Media query para mobile (`max-width: 600px`):
  - Campos duplos se tornam coluna única
  - Padding reduzido para melhor aproveitamento de tela
  - Tipografia escalável com `clamp()`

---

## 💻 Como Visualizar Localmente

1. Baixe o arquivo `index.html`
2. Abra diretamente no navegador (duplo clique)
3. Não requer servidor ou dependências

---

## 🔗 Links do Projeto

- 🌐 **Site institucional:** https://clinica-lumiere-57b479.webflow.io/
- 📋 **Formulário:** https://louhandf.github.io/clinica-lumiere-form/
- 💻 **Repositório:** https://github.com/LouhanDf/clinica-lumiere-form

---

## 📚 Padrões Web Aplicados

| Padrão | Aplicação |
|---|---|
| HTML semântico | `form`, `label`, `input`, `select`, `textarea`, `header`, `main`, `footer`, `section` |
| CSS Variables | `--cor-principal`, `--cor-fundo`, `--cor-texto` — paleta centralizada |
| CSS Flexbox | Header, hero, layout de campos duplos |
| CSS Grid | Campos lado a lado com `grid-template-columns` |
| Media Queries | Breakpoint em 600px para mobile |
| JavaScript DOM | `querySelector`, `addEventListener`, `classList` |
| Regex (JS) | Validação de formato de e-mail |
| ARIA | Acessibilidade para leitores de tela |
| Google Fonts API | Tipografia externa carregada via `<link>` |

---

*Projeto desenvolvido para fins acadêmicos — UniFECAF / Rocketseat 2025*
