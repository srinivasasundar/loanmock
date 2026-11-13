# Auto Loan Calculator – mock

A one-page demo of an auto loan calculator. Everything is in `index.html`; there is no build step and no server code.

**Demo only.** "MockBank", the brands, vehicles, rates and fees are illustrative. They are not a real bank's offer.

## Versions

Use the **V1 / V2** switch in the page header, or open the page with `?v=1` or `?v=2`.

- **V1** – the original calculator. It has brand, model and variant pickers, a vehicle price and a loan term, with results side by side for 20% and 30% downpayment and promo fee waivers.
- **V2** – the enhanced calculator built from business request BRQ-RT-7643827 (ALC-01 to ALC-05). It adds:
  - a vehicle category and an electric/hybrid rate question;
  - a downpayment slider;
  - a Desired Monthly Payment mode;
  - chattel mortgage and motor insurance add-ons;
  - a results table by loan term with messages that follow the fee scenarios;
  - a dealer quote comparison;
  - an accordion stepper and comma formatting.

The full change list is under **Release notes** in the page header.

## Pre-filling V2

`index.html?category=new&ehv=yes&price=1500000` fills in the form and computes the results straight away.

## FAQ

**Where do the rates come from?**
V1 uses promo rates that match the reference calculator. V2 uses Annex 1 of the business request.

**Are the insurance and chattel mortgage figures real?**
No. They are placeholders until the business supplies Annex 4 and the fee schedule. The release notes list every assumption.
