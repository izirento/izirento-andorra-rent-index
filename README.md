# Andorra: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Andorra: deposits, rent increases, termination notice, lease terms and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-05
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Scope and limits

Residential leases of a habitual and permanent home under Law 15/2022 (consolidated text). Rent update rules, temporary emergency housing measures, tourist rentals and penalties are not covered.

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main law | Law 15/2022 of 23 May, consolidated text of the Urban Property Lease Law (BOPA núm. 72, 15 June 2022), as amended. | [Consell General d'Andorra / BOPA (Butlletí Oficial del Principat d'Andorra), BOPA núm. 72 of 15 June 2022](https://www.consellgeneral.ad/fitxers/documents/lleis-2022/llei-15-2022-del-23-de-maig-de-text-consolidat-d2019arrendaments-de-finques-urbanes) |
| deposit | Maximum deposit | For a habitual and permanent home the deposit may not exceed two months' rent; a bank guarantee or other agreed guarantee may replace it (Art. 14.1). | [Consell General d'Andorra / BOPA (Butlletí Oficial del Principat d'Andorra), BOPA núm. 72 of 15 June 2022](https://www.consellgeneral.ad/fitxers/documents/lleis-2022/llei-15-2022-del-23-de-maig-de-text-consolidat-d2019arrendaments-de-finques-urbanes) |
| deposit | Deposit return | The landlord must return the deposit at the end of the lease on receiving the keys, unless it is applied, with supporting documents, to unpaid obligations or damage; the claim to recover it lapses three years after the lease ends (Art. 14.3-14.4). | [Consell General d'Andorra / BOPA (Butlletí Oficial del Principat d'Andorra), BOPA núm. 72 of 15 June 2022](https://www.consellgeneral.ad/fitxers/documents/lleis-2022/llei-15-2022-del-23-de-maig-de-text-consolidat-d2019arrendaments-de-finques-urbanes) |
| rent | Payment and advance rent | Unless agreed otherwise, rent is paid monthly within the first five days of each month; the landlord may not demand more than one month's rent in advance and must always give a receipt (Art. 20). | [Consell General d'Andorra / BOPA (Butlletí Oficial del Principat d'Andorra), BOPA núm. 72 of 15 June 2022](https://www.consellgeneral.ad/fitxers/documents/lleis-2022/llei-15-2022-del-23-de-maig-de-text-consolidat-d2019arrendaments-de-finques-urbanes) |
| lease_term | Minimum duration | A lease of a habitual and permanent home may not be shorter than five years; a shorter or open-ended lease is treated as five years if the tenant so wishes (Art. 42.1-42.2). | [Consell General d'Andorra / BOPA (Butlletí Oficial del Principat d'Andorra), BOPA núm. 72 of 15 June 2022](https://www.consellgeneral.ad/fitxers/documents/lleis-2022/llei-15-2022-del-23-de-maig-de-text-consolidat-d2019arrendaments-de-finques-urbanes) |
| lease_term | Tacit renewal | After the minimum term the lease is tacitly renewed for one-year periods unless either party gives at least three months' notice before the end of the term or a renewal (Art. 42.3). | [Consell General d'Andorra / BOPA (Butlletí Oficial del Principat d'Andorra), BOPA núm. 72 of 15 June 2022](https://www.consellgeneral.ad/fitxers/documents/lleis-2022/llei-15-2022-del-23-de-maig-de-text-consolidat-d2019arrendaments-de-finques-urbanes) |
| termination | Early exit by tenant | The tenant may end the lease before the agreed term with one month's notice; without that notice the tenant owes one month's rent for each year left to run (Art. 18). | [Consell General d'Andorra / BOPA (Butlletí Oficial del Principat d'Andorra), BOPA núm. 72 of 15 June 2022](https://www.consellgeneral.ad/fitxers/documents/lleis-2022/llei-15-2022-del-23-de-maig-de-text-consolidat-d2019arrendaments-de-finques-urbanes) |

## Català

**Andorra.** Dades obertes sobre l'arrendament d'habitatge segons la Llei 15/2022 de text consolidat d'arrendaments de finques urbanes: fiança, pagament de la renda, durada mínima, pròrroga i desistiment, amb l'enllaç a la font oficial per a cada valor.

*Les dades es proporcionen tal qual, sense cap responsabilitat. Només organitzem el que publiquen les fonts oficials. Comproveu cada valor amb la font primària.*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `andorra_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Andorra: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-andorra-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
