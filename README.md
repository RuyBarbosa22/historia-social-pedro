# A Rotina do Pedro

História social interativa para o Pedro, desenvolvida para comunicar de forma visual, simples e previsível uma mudança na rotina escolar.

## Sobre

O Pedro tem 6 anos e gosta da escola Tutto Amore. Este site conta, em 8 slides interativos, como vai funcionar a nova rotina que começa no dia **05/05/2026**:

- De manhã, Pedro fica em casa com a mamãe
- Depois do almoço, Pedro vai para a escola
- À tarde, Pedro fica na escola com a professora Jaqueline e a Louise

## Como usar

Abra o arquivo `index.html` direto no navegador — não precisa de servidor ou instalação.

```
historia-social-pedro/
├── index.html                  # Arquivo principal (tudo inline)
└── assets/
    └── characters/
        ├── pedro.jpg
        ├── mamae-jacqueline.jpg
        ├── professora-jaqueline.jpg
        └── at-louise.jpg
```

## Slides

| # | Tema | Interação |
|---|------|-----------|
| 1 | Pedro gosta da escola | Clique nos personagens → balões de fala |
| 2 | Rotina da escola | Timeline com ícones clicáveis |
| 3 | Pedro fica cansado | Clique no Pedro → "Descansar ajuda." |
| 4 | Calendário 05/05 | Marque os dias até a rotina nova |
| 5 | De manhã com a mamãe | Botões: Descansar / Brincar / Almoçar |
| 6 | Vai para a escola | Seta animada — Pedro caminha até a escola |
| 7 | Na escola à tarde | Clique nos personagens → cumprimentos |
| 8 | A nova rotina | Resumo visual + "Eu consegui! ⭐" com confetes |

## Funcionalidades

- Navegação por botões grandes (Anterior / Próximo / Recomeçar)
- Indicador de progresso (Slide X de 8)
- Calendário interativo com checkboxes — estado salvo automaticamente
- Progresso salvo no navegador (continua do ponto que parou)
- Responsivo: funciona em celular, tablet e desktop
- Sem dependências externas — arquivo único HTML + CSS + JS
- Sem sons automáticos
- Animações suaves e não agressivas

## Personagens

| Personagem | Arquivo |
|---|---|
| Pedro | `assets/characters/pedro.jpg` |
| Mamãe Jacqueline | `assets/characters/mamae-jacqueline.jpg` |
| Professora Jaqueline | `assets/characters/professora-jaqueline.jpg` |
| AT Louise | `assets/characters/at-louise.jpg` |
