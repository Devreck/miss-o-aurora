# 🚀 Missão: S.O.S. Aurora

![GitHub last commit](https://img.shields.io/github/last-commit/your‑user/miss-o-aurora?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/your‑user/miss-o-aurora?style=flat-square)
![License MIT](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)

> **Aventura interativa de Física em HTML + Tailwind + JavaScript**

![Preview Banner](assets/screenshot-banner.png)

A *Estação Espacial Aurora* está à beira do colapso! Assuma o papel de cadete de engenharia e resolva desafios de **Termologia, Ondulatória e Óptica** — inspirados no ENEM — para restaurar os sistemas vitais da nave.

---

## ✨ Demonstração

▶️ **Live Demo:** [https://your‑user.github.io/miss-o-aurora/](https://your‑user.github.io/miss-o-aurora/)

> Abra no desktop para a experiência completa; funciona também em mobile moderno (layout responsivo).

---

## 🗂️ Índice

1. [Recursos](#recursos)
2. [Capturas de Tela](#capturas-de-tela)
3. [Instalação](#instalação)
4. [Guia Rápido de Personalização](#guia-rápido-de-personalização)
5. [Estrutura de Pastas](#estrutura-de-pastas)
6. [Contribuindo](#contribuindo)
7. [Roadmap](#roadmap)
8. [Licença](#licença)

---

## Recursos

| Recurso                | Descrição                                                                                                                    |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Narrativa modular**  | Slides agrupados em capítulos com hubs de escolha livre.                                                                     |
| **E.N.E.M.**           | *Enciclopédia de Navegação e Engenharia da Missão*: abre um modal holográfico com questões tipo‑ENEM ligadas ao slide atual. |
| **Pontuação dinâmica** | Sistema de score e feedback instantâneo.                                                                                     |
| **MathJax 3**          | Renderização de fórmulas LaTeX pronta para uso.                                                                              |
| **Zero build**         | Apenas `index.html`, sem bundlers ou frameworks pesados.                                                                     |

---

## Capturas de Tela

| Início da Missão                          | Modal E.N.E.M.                            | Desafio de Conversão                          |
| ----------------------------------------- | ----------------------------------------- | --------------------------------------------- |
| ![slide‑1](assets/screenshot‑slide‑1.png) | ![enem‑modal](assets/screenshot‑enem.png) | ![calc‑challenge](assets/screenshot‑calc.png) |

---

## Instalação

```bash
# Clone o repositório
$ git clone https://github.com/your‑user/miss-o-aurora.git
$ cd miss-o-aurora

# Método rápido: abra o index.html
$ xdg‑open index.html  # ou explorer.exe index.html (Windows)

# Opcional: servidor local
$ python -m http.server 8000
# → http://localhost:8000
```

> **Pré‑requisitos:** Navegador com suporte a ES6 (Chrome ≥ 90, Firefox ≥ 88, Edge ≥ 90, Safari ≥ 14).

---

## Guia Rápido de Personalização

| Objetivo            | Onde modificar                                                          |
| ------------------- | ----------------------------------------------------------------------- |
| Conteúdo dos slides | Objeto `storyData` dentro de `index.html`.                              |
| Estilo global       | Bloco `<style>` ou classes Tailwind.                                    |
| Pontuação / lógica  | Funções JS: `checkAnswer`, `updateScore`.                               |
| Questões ENEM       | Campos `geminiCalcPrompt` e `geminiConceptPrompt`.                      |
| Novos capítulos     | Adicione IDs em `storyData` + atualize fluxos `startSlide`/`nextSlide`. |

---

## Estrutura de Pastas

```
📦 miss-o-aurora/
├── index.html            # Código fonte completo
├── assets/               # Imagens, ícones, capturas
├── LICENSE               # MIT
└── README.md             # Este documento
```

---

## Contribuindo

Pull requests são bem‑vindos! Para contribuições significativas:

1. Abra uma *issue* descrevendo a proposta.
2. Faça *fork* e crie uma *branch* com nome descritivo.
3. Documente suas mudanças no README se necessário.
4. Envie o *PR* com uma explicação sucinta.

### Convenção de Commits

* `feat:` novos recursos
* `fix:` correção de bugs
* `docs:` apenas documentação
* `chore:` tarefas internas

---

## Roadmap

* [ ] Persistir progresso no `localStorage`.
* [ ] Integrar API OpenAI / Gemini para gerar desafios on‑the‑fly.
* [ ] Tema escuro/claro com toggle.
* [ ] Exportar relatório de desempenho em CSV.
* [ ] Ranking online (Firebase/Supabase).

---

## Licença

Distribuído sob a licença **MIT** — consulte o arquivo [LICENSE](LICENSE) para detalhes.

---

<sub>Projeto educacional sem fins lucrativos. Ícones e imagens são apenas protótipos/demonstrações.</sub>
