# ViaLeve — v0.11.5 (itens 1–7 aplicados)

Inclui:
1) Validação forte de e-mail e nome.
2) Altura aceita vírgula (ex.: 1,70).
3) Telefone + opt-in WhatsApp na etapa 0.
4) Preços a partir de `pricing.json` (fallback interno).
5) Baixar resumo em **Markdown** (etapas 6 e 9).
6) Botões “Editar” que voltam à etapa e rolam para o topo.
7) Bloqueios extras: peso/altura/idade.

## Deploy
1. Suba os arquivos no GitHub.
2. No Streamlit Cloud, aponte para `app.py`.
3. Variáveis opcionais:
   - `VIALEVE_CHECKOUT_URL` — URL do gateway de pagamento.
   - `VIALEVE_SCHED_URL` — URL de agendamento (se desejar).
4. Para alterar preços, edite `pricing.json` (ou remova para usar o fallback).