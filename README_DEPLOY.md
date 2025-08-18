# ViaLeve — Pré-elegibilidade + Fase 2 (v0.11)

Inclui:
- Tela de **Planos** (Receita, Entrega, Acompanhamento, Premium) com recomendação automática.
- Etapa de **preferência de medicação** (Semaglutida/Tirzepatida) quando aplicável.
- **Resumo + consentimentos + preço** + botão de checkout (linkado por env `VIALEVE_CHECKOUT_URL`).
- Fallback de **tabela de preços** local (editável no `app.py`).

Deploy: suba estes arquivos no GitHub e aponte o Streamlit Cloud para `app.py`.