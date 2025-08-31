# Calendário Anual (HTML/JS) - 2026

Projeto front-end que gera dinamicamente os 12 meses de 2026 em HTML, CSS e JavaScript. O calendário inclui feriados nacionais fixos e móveis (Carnaval, Sexta-Feira Santa, Corpus Christi) e exemplos de eventos/estudos personalizáveis.

## Destaques

- Semântica e acessibilidade: usa `role="grid"`, cabeçalhos e rótulos claros.
- Visual limpo e responsivo: layout em 3 colunas (1 em telas menores), tokens de cor em `:root`.
- Extensível: meses gerados por JavaScript; feriados e eventos configuráveis por objetos.

## Tecnologias

- HTML5 semântico
- CSS nativo (sem dependências)
- JavaScript (DOM API)

## Como executar

Abra `index.html` no navegador.

```bash
# Windows (PowerShell)
start index.html

# macOS
open index.html

# Linux (GNOME)
xdg-open index.html
```

## Estrutura

```
.
├─ index.html   # Calendário 2026 (estilos + JS embutidos)
└─ README.md    # Descrição e instruções
```

## Personalização rápida

- Eventos: edite o objeto `studyEvents` em `index.html` (chave no formato `AAAA-MM-DD`).
- Feriados fixos: edite o objeto `fixedHolidays` (`MM-DD`).
- Cores/Tema: ajuste os tokens no seletor `:root` (`--holiday`, `--event`, etc.).

## Licença

MIT
