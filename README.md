# Lutz / PerfectlyBasics — channel-corrected review draft

Merchant page: https://tobywinchester.github.io/pb-lutz-commerce/

## Important channel correction
The **70% iDEAL / 13% Amex / 17% debit split is RETAIL ONLY**. The previous revision applied this to online payments incorrectly; its figures are superseded.

Original merchant-supplied ONLINE mixes are restored:
- Lutz:49% iDEAL,21% Klarna,17% cards,7% PayPal,6% Bancontact.
- PerfectlyBasics:61% iDEAL,18% cards,16% Klarna,5% Bancontact.

## Retail processing
The model assumes eligible native Shopify Payments POS local iDEAL/Wero via QR. Shopify documents that local payments through Shopify Payments use online processing rates (card-not-present), not card-present rates. The quoted iDEAL fee is EUR0.29/payment on Advanced or EUR0.15/payment on Plus. No extra POS card percentage or EUR0.10 fixed card fee is applied to iDEAL.

Physical-card payments use their plan rates plus EUR0.10 per card payment: Advanced debit0.50%,credit1.90%,Amex2.90%; Plus debit0.35%,credit1.70%,Amex2.90%. Default retail mix:70%iDEAL,17%debit,0%credit,13%Amex. The supplied payment shares are also used to allocate sales value under an equal-method-AOV assumption. Historical all-retail AOV estimates counts unless a total retail payment count is entered.

POS iDEAL activation/eligibility and availability at migration/go-live MUST be confirmed. The illustration assumes availability over its modelled period; it is not a day-one promise or final binding quote. An external iDEAL provider requires its own fees.

Source: https://help.shopify.com/en/manual/sell-in-person/shopify-pos/payment-management/accepting-local-payments

## Scope and safeguards
Only Lutz Plus/PB Advanced and both Advanced+ShopifyPOS are compared; PB stays Advanced in both. Planning volumes remain Lutz onlineEUR2.4m/retailEUR4m and PB onlineEUR2.4m. EUR6,300 TOTAL first-year credit applies to Lutz Plus subscription fees across its first three monthly bills only; not processing, POS or PB fees, and not repeated in ongoing costs. Lifetime Rebuy/AfterSell checkout-feature access remains subject to scope/supplier/setup confirmation; indicative app value is not another fee deduction.

Quoted minimum/VPF terms are retained; processing-rate classification does not itself establish contracted platform-fee sales-channel classification. Final written rates/terms, captured-volume/VAT/refund basis, AOV and payment-share definitions govern. Hardware, implementation, ERP/apps/support, fee taxes and other stated extras are excluded. No conversion uplift or incumbent-saving guarantee is assumed.

Review labels, cost components, CSV/print and portable exports retain these caveats. Inputs stay in the browser. No email has been sent.
