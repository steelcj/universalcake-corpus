# Québec Public Spend on Microsoft & Amazon by Ministry (Draft, 2018–2025)

> **Scope:** First-pass coverage for **Santé (MSSS)**, **Revenu Québec (ARQ)**, and **Transports et mobilité durable (MTMD/CTQ)** with verifiable line items from official *Listes des engagements financiers* and SEAO-derived annexes. Totals are **partial** and conservative. We also compare against NGO/media tallies to identify gaps that further collection should close.

---

## Method in brief
We extracted ministerial monthly PDFs and captured rows that explicitly name **Microsoft** (incl. Microsoft Azure / Microsoft 365 / Office 365 / Microsoft Unified Support) or **Amazon Web Services (AWS)**. Where a ministry’s ledger is sparse, we include cross-ministerial ledgers that record charges made **on behalf of** (or to) another public body (e.g., Revenu Québec) and items in sector commissions (e.g., **CTQ** under MTMD).

---

## Per-ministry findings (documented rows)

### 1) Ministère de la Santé et des Services sociaux (MSSS)
- <a name="msss-azure-june2023-citation"></a>**Direct Microsoft Azure engagements (June 2023)**:  
  The MSSS FRISSSS ledger lists *“Contrat GG 396403428 … Solutions infonuagiques Azure”* with **“134 526,00 $ MICROSOFT CANADA”**, and a second line with **“127 660,91 $ MICROSOFT CANADA”** for the same ITQ framework. :contentReference[oaicite:0]{index=0}

**MSSS (partial) annualized (CAD)**
- **2023:** Microsoft (Azure) **≈ 262 186.91** (sum of the two lines above).  
  *Note:* Additional large 2023 FRISSSS network items are charged via MCN and other suppliers; those are **not** Microsoft/Amazon and are excluded.

---

### 2) Revenu Québec (ARQ)
- <a name="arq-azure-2024-2025-citation"></a>**Microsoft Azure services (FY 2024–2025)**:  
  *“Frais de service – solutions infonuagiques – Microsoft Azure”* with **“135 000 $ Revenu Québec”** is recorded in a government ledger (published in another ministry’s monthly report). :contentReference[oaicite:1]{index=1}

**Revenu Québec (partial) annualized (CAD)**
- **2024–2025:** Microsoft (Azure) **135 000**.

---

### 3) Transports et de la Mobilité durable (MTMD) / Commission des transports du Québec (CTQ)
- <a name="mtmd-ctq-microsoft-2024-2025-citation"></a>**CTQ professional services including “produits Microsoft, suite Office et Fortinet”** reported as a *“contrat de service professionnel en infonuagique, réseautique, produits Microsoft, suite Office et Fortinet”* for **120 000 $** (engagement transmitted May 2024, carried in **March 2025** ledger). :contentReference[oaicite:2]{index=2}
- MTMD monthly ledgers also mention **Microsoft/Azure** in their descriptive headers/notes for IT operations (DGRITN), though individual rows with vendor+amount are sparse; see 2024–2025 ledgers for context. :contentReference[oaicite:3]{index=3}

**MTMD/CTQ (partial) annualized (CAD)**
- **2024–2025:** Microsoft-related services (CTQ) **120 000**.

---

## Cross-checks (contextual, not directly annualized here)
- **Hydro-Québec** (state corporation): media reports cloud hosting with **Microsoft, Google, Amazon “quelque 40 M$ cette année”**; this signals scale but sits **outside ministries** and requires separate reconciliation to official ledgers. :contentReference[oaicite:4]{index=4}
- **Amazon in Québec (2018–)**: journalism tallies **~100 M$** in public-sector contracts (mostly cloud). We have not yet distributed these by ministry/year. :contentReference[oaicite:5]{index=5}
- **Civil society view**: Advocacy sources estimate **> 2 G$** in Québec public-cloud contracts since 2011 (across multiple vendors, incl. Microsoft & Amazon). Treat as an **upper-bound context** until reconciled. :contentReference[oaicite:6]{index=6}

---

## Interim yearly estimate (sum of verified rows above)

|     Year (FY) |                                         MSSS (Microsoft/AWS) |                                Revenu Québec (Microsoft/AWS) |                                     MTMD/CTQ (Microsoft/AWS) | **Subtotal (CAD)** |
| ------------: | -----------------------------------------------------------: | -----------------------------------------------------------: | -----------------------------------------------------------: | -----------------: |
|      **2023** | **262,186.91** (Microsoft Azure) :contentReference[oaicite:7]{index=7} |                                                            — |                                                            — |     **262,186.91** |
| **2024–2025** |                                                            — | **135,000** (Microsoft Azure) :contentReference[oaicite:8]{index=8} | **120,000** (Microsoft/Office) :contentReference[oaicite:9]{index=9} |        **255,000** |

> **Note:** These are **floor** values. We expect totals to grow as we add additional months/years, other line items (e.g., Microsoft 365 licensing via resellers, Azure consumption, AWS purchases), and reconcile SEAO notices with the monthly PDFs.

---

## Gaps vs. NGO/media estimates

- <a name="gap-aws-100m-citation"></a>**AWS ~100 M$ since 2018 (media)** vs. our current ministry-level ledger capture: **we have not yet attributed the bulk of AWS spend to specific ministries/years**. The press tally implies several **tens of millions** remain to be located across MCN-led frameworks and consuming ministries. :contentReference[oaicite:10]{index=10}  
- <a name="gap-2b-citation"></a>**“> 2 G$ cloud since 2011” (advocacy)** vs. verified rows: our dataset is tiny by comparison; closing this gap requires systematic harvesting of **all ministries’** PDFs (2018→present) + **SEAO** export and deduplication. :contentReference[oaicite:11]{index=11}

---

## Next data-collection passes (action plan)

1. **MSSS expansion (2018→present):** scrape all FRISSSS monthly PDFs; capture rows where the *Contractant* is **Microsoft**, **Amazon**, or a reseller associated to **Azure/M365/AWS**, plus any *ITQ/entente-cadre* references pointing to those vendors. Start with 2022–2024 PDFs similar to June 2023. :contentReference[oaicite:12]{index=12}  
2. **Revenu Québec direct ledgers:** ARQ’s own PDFs are sparse online; use **cross-ministerial ledgers** (Finances, Immigration, MCN) that post ARQ-tagged items (e.g., *“Frais de service – Microsoft Azure – Revenu Québec 135 000 $”*) and follow the **SEAO item IDs** to retrieve contract cards. :contentReference[oaicite:13]{index=13}  
3. **Transports/CTQ:** continue through **2024–2025** MTMD ledgers to enumerate all “Microsoft/Azure” and “AWS” occurrences with explicit amounts (the CTQ 120 000 $ line provides a clear pattern to follow). :contentReference[oaicite:14]{index=14}  
4. **AWS attribution:** pivot from media tallies to **MCN’s monthly lists** (Fonds de la cybersécurité et du numérique) and target rows naming **Amazon Web Services** or **AWS**; back-allocate to consuming ministries when the object text indicates ministry or program. :contentReference[oaicite:15]{index=15}  
5. **Reconciliation rules:** store both **“Montant du contrat”** and **“Montant total payé”** by fiscal year; flag items channeled through integrators (e.g., Alithya for M365) as **Microsoft-related** with an attribute `via_reseller=true` and keep the original supplier in a separate column.

---

## Direct quotes (CAP) used in this draft

- <a name="msss-azure-june2023-citation"></a>**MSSS, June 2023:** *“Contrat GG 396403428 – Offres infonuagiques de solutions IAAS, PAAS et SAAS reliées – ITQ pour le MSSS – **Solutions infonuagiques Azure**.”* Amounts listed with **“MICROSOFT CANADA”** for **134 526,00 $** and **127 660,91 $**. [Return to citation](#msss-azure-june2023-citation). :contentReference[oaicite:16]{index=16}  
- <a name="arq-azure-2024-2025-citation"></a>**Revenu Québec, FY 2024–2025 (recorded in another ministry’s ledger):** *“Frais de service – **solutions infonuagiques – Microsoft Azure** … 135 000 $ Revenu Québec.”* [Return to citation](#arq-azure-2024-2025-citation). :contentReference[oaicite:17]{index=17}  
- <a name="mtmd-ctq-microsoft-2024-2025-citation"></a>**MTMD/CTQ, March 2025:** *“CTQ 24-25 **contrat de service professionnel en infonuagique, réseautique, produits Microsoft, suite Office et Fortinet** … 120 000,00 $.”* [Return to citation](#mtmd-ctq-microsoft-2024-2025-citation). :contentReference[oaicite:18]{index=18}  
- <a name="gap-aws-100m-citation"></a>**Media context:** *“Les ministères et organismes publics du Québec ont conclu près d’une centaine de contrats avec Amazon totalisant **plus de 100 M$** depuis 2018.”* [Return to citation](#gap-aws-100m-citation). :contentReference[oaicite:19]{index=19}  
- <a name="gap-2b-citation"></a>**NGO context:** claim of **“plus de 2 G$”** in public-cloud contracts since 2011 in Québec, including Microsoft/Amazon. [Return to citation](#gap-2b-citation). :contentReference[oaicite:20]{index=20}

---

## Reference section (APA-7)

<a name="msss-june2023-reference"></a>Ministère de la Santé et des Services sociaux (MSSS). (2023, June). *Liste mensuelle des engagements financiers – FRISSSS (Juin 2023)*. Gouvernement du Québec. :contentReference[oaicite:21]{index=21} [Return to citation](#msss-azure-june2023-citation)

<a name="arq-azure-2024-2025-reference"></a>Ministère de l’Immigration, de la Francisation et de l’Intégration (MIFI). (2024/2025). *Liste des engagements financiers* (entries incl. “Frais de service – solutions infonuagiques – Microsoft Azure – Revenu Québec, 135 000 $”). Gouvernement du Québec. :contentReference[oaicite:22]{index=22} [Return to citation](#arq-azure-2024-2025-citation)

<a name="mtmd-march2025-reference"></a>Ministère des Transports et de la Mobilité durable (MTMD). (2025, March). *Liste des engagements financiers de 25 000 $ et plus* (CTQ 24-25 contrat … Microsoft / Office / Fortinet – 120 000 $). Gouvernement du Québec. :contentReference[oaicite:23]{index=23} [Return to citation](#mtmd-ctq-microsoft-2024-2025-citation)

<a name="media-hq-2025-reference"></a>Descôteaux, D. (2025, January 10). *Les GAFAM veillent sur vos données d’Hydro-Québec* (Hydro-Québec cloud bills “quelque 40 M$”). *Journal de Montréal*. :contentReference[oaicite:24]{index=24}

<a name="media-aws-100m-reference"></a>*Amazon, qui quitte le Québec, a reçu des centaines de millions $ de fonds publics* (news aggregation quoting JdM: “plus de 100 M$” since 2018). (2025). Reddit summary linking to original report. :contentReference[oaicite:25]{index=25} [Return to citation](#gap-aws-100m-citation)

<a name="ngo-2b-reference"></a>FACiL. (n.d.). *Souveraineté numérique au Québec – Communiqué de campagne* (claiming “> 2 G$” cloud contracts since 2011). :contentReference[oaicite:26]{index=26} [Return to citation](#gap-2b-citation)

---

## What this draft enables next
- We can now **scale this into a per-ministry, per-year dataset** (CSV/JSON) and keep a **running subtotal vs. media/NGO claims**.  
- If you want, I’ll extend to **MSSS 2018→present**, **ARQ 2018→present**, **MTMD 2018→present**, and add **AWS rows** (starting with MCN-led ITQ/AWS lines and ministry consumers).