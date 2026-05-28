# Cepton Position Paper — Operating Kit

Repo: deck template (`Ipsen.pptx`) + financials template (`PandL.xlsx`).
Use: 1h timed case study → 3 slides on a pharma company → 5-10 min oral presentation (English) + 10-15 min Q&A.

---

## PROMPT TO PASTE INTO A NEW CLAUDE CONVERSATION

> You are my research and structuring accelerator for a timed strategy-consulting case (Cepton, healthcare-focused boutique). I have 1 hour to build a 3-slide Position Paper on a pharma company, present it in English (5-10 min), then defend it in Q&A (10-15 min). I do the analysis and judgment; you accelerate the factual retrieval and formatting. Be extremely direct, reason from first principles, contradict me when I'm wrong, no filler.
>
> **The 3 slides:**
> 1. **Company Overview** — identity (HQ, founded, controlling shareholder, CEO, FTE), financials 3Y (revenue + segment split, gross margin, R&D%, operating income, net income, net debt/EBITDA or net cash, FCF), TA mix %, geographic mix %, top 5-7 products (Product | TA | MoA | Indication | Revenue | Type | LOE).
> 2. **Key Markets & Competitive Landscape** — top banner = focus rationale (which 2-3 markets and why). For each market: size ($), incidence/prevalence, CAGR, company position (leader/challenger/niche) + market share, top 3 named competitors with their key assets.
> 3. **Strategic Outlook & Key Questions** — bold 1-sentence thesis on top ("[Company] is shifting from X to Y, anchored by Z, facing [risk]"), then 3 columns: Patent Cliff (asset | LOE | revenue at risk | total = X% of revenue) / Pipeline (asset | phase | TA, risk-adjusted) / M&A-BD (deals 24mo + amounts + same-TA?). Bottom = 3 questions to the prospect, each forcing a non-public answer.
>
> **How you help me, fast:** when I give you a company name, give me (a) the financial snapshot in slide-1 table format, (b) candidate markets for slide 2 with order-of-magnitude sizing, (c) the cliff/pipeline/M&A raw material for slide 3. I write the thesis and questions myself; challenge mine.
>
> Today's company is: **[NAME]**. Start with slide 1 financials.

---

## METHOD — 5 PASSES (60 min)

| Pass | Time | Output |
|---|---|---|
| 1. Financial identity | 5 min | Revenue, margins, R&D%, net debt/EBITDA, market cap |
| 2. Portfolio mapping | 10 min | Top products, TA mix %, geo mix, molecule type mix |
| 3. Cliff & replacement | 15 min | Per asset: LOE / type / MoA / next-gen pipeline / M&A relay |
| 4. Strategic moves | 10 min | 3-5 M&A 24mo, BD/licensing, spin-offs, mgmt changes |
| 5. Thesis + questions | 15 min | 1-sentence thesis + 3 prospect questions |
| Buffer | 5 min | Formatting + oral rehearsal |

---

## SOURCES BY SLIDE (fast, no paid reports)

**Slide 1:** Investor Relations / annual report (primary) · stockanalysis.com (3-5Y financials, listed) · macrotrends.net (10Y trends) · Wikipedia (identity, M&A history) · earnings Q4 deck (product sales).

**Slide 2:** SEER (US cancer incidence) · Orphanet (rare disease prevalence) · Wikipedia "[disease] epidemiology" · Google "[indication] market size billion 2024" → take the number from the snippet, don't open/pay · Wikipedia of the drug class → competitors.

**Slide 3:** corporate Pipeline page · "[product] patent expiration" / DrugPatentWatch · Wikipedia "[Company]" Acquisitions section · FiercePharma / Endpoints for deal rationale.

**Fast start on an unknown listed company:** stockanalysis.com (financials) → pipeline page (slide 3) → Wikipedia acquisitions (M&A) → Google market size (slide 2). Four tabs = 80% of content. Never open a full analyst PDF when timed.

---

## RECURRING MISTAKES TO AVOID

- Slide 3 missing the **1-sentence thesis on top** (forgotten twice in practice).
- Slide 3 missing the **3 prospect questions** at the bottom — this is the MAIN deliverable per brief ("ask intelligent questions").
- Slide 2 with no market figures — always give order of magnitude even if estimated.
- Confusing **LOE (date)** with **erosion (speed)**.
- Applying small-molecule erosion (-80% in 24mo) to a biologic, or vice versa. Lantus = insulin = biologic.
- Confusing **YoY value growth** ("+11% gross margin") with **margin-point change** ("+2pt of margin"). These are different. Don't write "11pt GM increase".
- Net debt/EBITDA negative = net cash position. Express as "+€XM net cash", not a negative multiple.
- Listing M&A without qualifying: cliff-relay vs diversification bet.
- Using historical Humira erosion model for post-2028 biologic cliffs (Asia capacity + streamlined FDA pathway + manufacturing modularity accelerate erosion).
- Naming a pipeline asset wrong (e.g. check exact INN/code before fixing) — weak point in Q&A.

---

## KEY NUMBERS TO ANCHOR (reference)

**Phase → approval (all-indications avg):** Ph1 ~8% / Ph2 ~15% / Ph3 ~55%. Onco solid much lower (5/8/35), heme much higher (23/28/74).

**Cost per phase:** Ph1 25-50M$ · Ph2 60-150M$ · Ph3 250-600M$ (cardio outcomes trials 500-800M$, rare 80-200M$). Full NME all-in: 1.5-2.5B$.

**Erosion at LOE:** small molecule -80 to -98% in 24mo · biologic -50 to -70% in 3-5y (faster post-2028) · vaccine/complex -20 to -40%.

**Regulatory exclusivity:** small molecule 5y FDA / 10y EU · biologic 12y FDA / ~11y EU · orphan 7y FDA / 10y EU.

**Market sizes (rough):** Onco ~250B$ · immuno-inflammation ~150B$ · cardio-metabolic ~120B$ · CNS ~95B$ · rare disease ~200B$. Global Rx ~1,600B$.

**Pricing per patient/year (peak):** precision onco 100-200k$ · rare disease 200-500k$ · immuno biologic 30-80k$ · CNS/MS 30-60k$ · cardio-metabolic chronic 1-5k$ · HIV 25-40k$ · vaccine 100-300$/dose.

---

## DAY-OF ACCESS

- Get files: github.com → this repo → **Code → Download ZIP** (zero dependency, no login). Or `git clone https://github.com/Benoitntfr/Ipsen_Template.git` if git available.
- Claude: only if explicitly authorized by Cepton. If unconfirmed, assume NOT allowed and perform solo.
- Excel embedding does not travel via git — embed in the .pptx beforehand if needed.
