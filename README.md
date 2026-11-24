# Protótipo de Melhorias — No Fluxo UnB (Grupo Jean Sammet)

Protótipo interativo em **Antes vs. Depois** desenvolvido como entrega técnica complementar da disciplina **Qualidade de Software 1 (FCTE/UnB — 2026/2)**, preservando rigorosamente o design visual original (dark mode, paleta, cards e layout do Svelte Flow) do **No Fluxo UnB** e destacando as melhorias propostas em **Usabilidade** e **Adequação Funcional**.

## Pontos de Melhoria Demonstrados

1. **Explicação de Termos Críticos/Estratégicos (Usabilidade — M-01 / H2):** Tooltip acessível por teclado e ponteiro no card `CRÍTICAS` e nos badges `🔥 Crítica`.
2. **Feedback de Créditos Semestrais (Usabilidade — M-01 / H9):** Mensagem explícita quando o usuário informa valor fora da faixa `8–32` créditos (botão rápido *"Testar valor inválido (40 cr)"*).
3. **Reatividade do Onboarding (Adequação Funcional — COO):** Alternância de *Trabalho/Estágio (C3)* reduzindo a carga sugerida para `20 cr (300h)` e *Objetivo Velocidade (C4)* comprimindo o horizonte de 3 para 2 semestres.
4. **Completude de Obrigatórias (Adequação Funcional — CDO):** Inclusão da disciplina `FGA0206` (Informática e Sociedade) no plano e indicador `15 / 15 obrigatórias`.
5. **Consistência de Oferta e Calendário (Adequação Funcional — TVS):** Validação da oferta de `FGA0244` em semestre ímpar (`2027.1`) e selo de calendário UnB validado.

## Como executar localmente

Não requer instalação de dependências nem servidor: basta abrir o arquivo `index.html` diretamente no navegador (Chrome, Firefox ou Edge).

## Como publicar no GitHub Pages (em repositório separado)

1. Crie um novo repositório no GitHub (ex.: `prototipo-no-fluxo-melhorias`).
2. Copie os arquivos desta pasta (`index.html` e `README.md`) para o novo repositório e faça `git push`.
3. Em **Settings → Pages → Build and deployment**, selecione **Deploy from a branch** (`main`, pasta `/ (root)`) e salve.
4. Em cerca de 1 minuto o protótipo estará online em `https://<seu-usuario>.github.io/prototipo-no-fluxo-melhorias/`.

