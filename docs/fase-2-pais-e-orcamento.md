# FASE 2 — Escolha do país e plano de orçamento

> Setembro/2026 · câmbio de referência: **€1 = R$5,90**
> ⚖️ = precisa ser confirmado com profissional especializado.

## 2.1 Seu perfil (restrições reais)

| Item | Resposta | Impacto |
|---|---|---|
| Capital | R$10.000 ≈ **€1.695** | Dá para ~2 testes sérios de produto. Zero margem para desperdício. |
| CNPJ | Não tem, pode abrir | Abrir **em paralelo** às fases 3–4 (leva semanas). ⚖️ |
| Idiomas | Inglês e espanhol | Primeiro mercado em inglês ou espanhol. |
| Tempo | "Poucas horas" | **Maior risco do projeto.** Mínimo viável: ~8 h/semana, mais 20–30 min por dia durante os testes. |
| Vídeo | Não quer aparecer | Viável, mas o criativo vira o gargalo. O produto precisa se vender pela demonstração. |

## 2.2 Decisão: **Irlanda como mercado de validação**

Motivos:
1. **Inglês nativo.** O copy e o atendimento gerados com IA ficam naturais, sem revisão de nativo.
2. **O cartão é o pagamento padrão.** Isso contorna o maior bloqueio de quem opera com empresa brasileira: não precisamos de iDEAL, Bancontact nem Bizum no primeiro teste.
3. 95% dos usuários de internet compram online, a maior taxa da UE.
4. Com €300–400 por teste, o tamanho pequeno do país **não limita nada**.
5. O mesmo inglês serve depois para Holanda e países nórdicos (DK/SE/FI), que falam inglês muito bem. Isso fica como expansão, não como teste.

Contras aceitos: CPM mais caro (~US$11,7) e mercado pequeno para escalar.

Mercados de segunda onda, decididos pelos dados do produto:
- **Holanda:** rica, mas exige iDEAL/Wero.
- **Espanha:** você domina o idioma, mas o poder de compra é menor. Só com produto de margem alta.
- **Alemanha + Áustria:** só com operação madura.

Descartado agora: **Reino Unido**. Está fora da UE, exige registro de VAT próprio desde a primeira venda e acrescentaria complexidade.

## 2.3 Logística: China direto × armazém na UE

| | China → Irlanda | Armazém CJ na UE → Irlanda |
|---|---|---|
| Preço do produto | base | ~+20% (CJ embute o IVA pago na importação) |
| Taxa aduaneira €3 (+~€2) por pedido | **sim** | **não** (já importado a granel) |
| Prazo | 7–15 dias | 2–6 dias |
| Risco de chargeback/reclamação | maior | menor |
| Catálogo | enorme | limitado |
| IVA do lado do lojista | IOSS + intermediário | provavelmente OSS, regras diferentes ⚖️ |

**Preferência: armazém na UE sempre que o produto existir lá.** Em ticket de €50–70, os €5 fixos e o prazo pesam mais que os 20% no custo. Isso precisa ser recalculado por produto.

## 2.4 Alocação do capital (€1.695)

| Item | € estimado | Classificação | Quando |
|---|---|---|---|
| Contador: abertura de CNPJ + consulta fiscal (BR + IVA UE) | 200–250 | ESSENCIAL | Semanas 2–4 |
| Shopify (planos mensais, nunca anual) | ~80 por 3 meses | ESSENCIAL | Só na Fase 8 |
| Domínio | ~12 | IMPORTANTE | Fase 8 |
| Intermediário IOSS (se China direto) | 20–110/mês | ESSENCIAL se aplicável | Antes da 1ª venda |
| Responsible Person GPSR | a orçar | ESSENCIAL | Antes da 1ª venda ⚖️ |
| Amostras de produto | ~60 | IMPORTANTE | Fase 6 |
| Reserva para reembolsos/chargebacks | ~150 | ESSENCIAL | Na conta, sem gastar |
| **Anúncios** | **~800–1.000** | ESSENCIAL | Fase 11 |
| Apps, ferramentas de spy, logo, curso | 0 | DESNECESSÁRIO | — |

**Implicação:** cabem **2, no máximo 3 testes de produto**. O lucro das primeiras vendas é que financia a continuação.
As fases 3 a 5 (nicho, pesquisa e validação no papel) custam **€0**. Só pagamos algo recorrente com o produto escolhido.

## 2.5 Gateway de pagamento (a confirmar)

- Shopify Payments: **indisponível** para o Brasil.
- Stripe Brasil: aceita cobrança em EUR, mas cobra ~3,99% + R$0,39 **+1% de conversão**. Na conta usar **~5% + €0,10**.
- A confirmar no cadastro: se o Stripe BR libera Apple Pay/Google Pay para clientes da UE, e as condições do PayPal Business BR.
- A taxa extra da Shopify por gateway de terceiros também entra na conta.

## 2.6 Perguntas para o contador ⚖️
1. Tipo de empresa: ME no Simples Nacional × MEI. O MEI provavelmente não serve (limite de faturamento e atividades).
2. Tributação de venda a consumidor estrangeiro de mercadoria que **nunca passa pelo Brasil**.
3. Recebimento em EUR via Stripe/PayPal: câmbio, contrato e declaração.
4. IVA na UE: IOSS (China direto) × OSS/registro (estoque na UE). Qual se aplica a cada modelo de fornecedor?
5. Obrigações de GPSR: quem pode ser o Responsible Person e quanto custa.

## Fontes
- Câmbio: https://br.investing.com/currencies/eur-brl
- Custos de intermediário IOSS: https://avask.com/blog/ioss-registration-cost/ · https://www.crossborderit.com/ioss · https://goodvat.com/guides/selling-to-eu/ioss-intermediary-comparison/
- Stripe (taxas BR / métodos locais): https://checkoutpage.com/blog/stripe-international-fees · https://stripe.com/en-br/pricing/local-payment-methods
- CJ e a taxa de €3 / armazém UE: https://cjdropshipping.com/blogs/cj-news/EU-Customs-Duty-Update-for-July-2026 · https://cjdropship.com/new-tax-policy-is-charging-vat-with-dropshipping-parcels-to-the-eu-what-can-dropshippers-do/
