# Facebook Lead Gen Playbook — Primerica Term Life (Atlanta)

**Operator:** 23M, Atlanta GA
**Goal:** Live campaign capturing inbound term life leads same-day
**Constraint:** Meta Special Ad Category (SAC) — Credit/Employment/Housing/Social Issues/Insurance

---

## CRITICAL PRE-FLIGHT (DO NOT SKIP)

Before any of the below goes live, two non-negotiables:

1. **Primerica Compliance / Field Marketing review.** Every ad creative, hook, script, lead-form question, landing copy, and disclosure must be submitted through your RVP / Primerica's marketing compliance portal and receive written approval. Running unapproved insurance ads — even "vanilla" ones — is a contract-terminating event. Build your campaign in Meta as DRAFT, then submit. **Same-day launch only works if compliance turnaround is same-day.**
2. **State licensing.** You must hold an active GA Life license (and any state you target) before a single dollar runs. Confirm appointment status with Primerica Life Insurance Company.

If either is unresolved, stop here and use today to clear them. Compliance > speed.

---

## PILLAR 1 — Campaign Setup for Speed

### Why Special Ad Category changes everything
When you flag the campaign as **Insurance** (which Meta will force you to do — the algorithm flags insurance keywords automatically), Meta strips:
- Age targeting (locked to 18–65+)
- Gender targeting (locked to All)
- ZIP-level targeting (minimum ~15 mile radius around a city/region)
- Most behavioral & detailed-interest targeting
- Lookalike Audiences (replaced historically by Special Ad Audiences, now also retired for SAC in most regions — assume unavailable)
- Many Custom Audience types stay usable (your CRM list, engagement audiences) but can't be used to seed lookalikes for SAC

That means **your copy and creative are your targeting**. Pillar 2 handles that.

### Exact build (Ads Manager)

**Objective:** Leads (engagement objective) → "Instant forms" as the conversion location.
- Do **NOT** pick "Calls" or "Website" today. Instant Forms keep friction near zero and you own the data instantly via Lead Center / CRM.

**Special Ad Category:** Toggle **ON** → select **Insurance**. Acknowledge the restriction.

**Campaign budget:** Use **Advantage Campaign Budget (CBO)** at **$50–$75/day** to start. CBO lets Meta redistribute spend to the winning ad without you babysitting.
- If you only have $20–$30 to test, set it ABO at the ad-set level instead so each creative gets a fair shot.

**Bid strategy:** Highest volume (default). Do **not** set a cost cap on day one — you have no data yet and a cap will starve delivery.

**Schedule:** Start ASAP, run 24/7 for the first 3 days. No dayparting until you have ≥30 leads to pattern.

### Ad set (one to start)

- **Location:** Atlanta + 25 mile radius. Add Marietta, Decatur, Stone Mountain, College Park, East Point as additional pins. Keep it metro-only — Primerica's Atlanta market has dense middle-income households.
- **Age:** 18–65+ (forced)
- **Gender:** All (forced)
- **Languages:** English. Add Spanish only if you're bilingual or have a bilingual partner to call leads.
- **Detailed targeting:** Leave **blank**. With SAC the available options are gutted, and "broad" actually performs better with strong copy filtering.
- **Placements:** **Advantage+ placements (automatic).** Do not hand-pick. Reels + Feed + Stories will share spend; let Meta optimize.
- **Optimization event:** Leads.

### Ads (load three at once — see Pillar 3)

All three creatives run inside the same ad set so Meta auctions them against each other. Kill the bottom performer after ~50 impressions per ad or 24 hours, whichever comes first.

### Pixel / CAPI

Even with Instant Forms, install the Meta Pixel + Conversions API on any landing destination you eventually use. For today, the form-fill event fires natively inside Meta — no pixel required to start.

### Tracking UTM

Tag each ad with `utm_source=fb&utm_medium=paidsocial&utm_campaign=atl_termlife_may&utm_content=hook1|hook2|hook3` so you can attribute downstream booked appointments.

### Honest timing note

Meta's review for Special Ad Category creatives is typically **<6 hours but occasionally up to 24**. Submit by **10:30 AM** to have a credible shot at 5 PM delivery. If you're seeing this past 11 AM, your true earliest delivery window is tomorrow — set expectations accordingly.

---

## PILLAR 2 — Copy-Based Filtering (Targeting via Words)

Because you can't target by age/income/parental status, your **first line of copy is the targeting**. Call out the avatar so non-prospects scroll past and prospects self-identify.

### The four Primerica Atlanta avatars to call out by name

1. **New / young parents** ("you just had a baby and the math hit you")
2. **New homeowners with a mortgage** ("the house is in your name — what happens to it if you're not here?")
3. **Middle-income dual-earner households $40k–$95k** ("if your paycheck disappeared tomorrow, would the bills still get paid?")
4. **People with credit card / student loan debt + dependents** ("debt doesn't die with you if it's co-signed")

### Filter-style primary text formulas (drop directly into the ad)

**Formula A — Calling out the role:**
> Atlanta parents — if your kids depend on your paycheck, this 60 seconds is for you.
> Most families I sit with have never been shown what term life actually costs. Spoiler: for most healthy 25–45 year olds it's less than what you spend on streaming.
> I'm a licensed life agent here in Atlanta. Tap below, answer 4 quick questions, and I'll text you a free, no-pressure quote today.

**Formula B — Life-stage trigger:**
> Just bought a house in metro Atlanta? Read this before your next mortgage payment.
> If something happened to you, the bank doesn't care that your family is grieving — the payment is still due on the 1st.
> A simple term life policy can cover the mortgage so your family keeps the home. Tap below for a free quote — takes 30 seconds.

**Formula C — Income replacement:**
> Question for working parents in Atlanta: if your paycheck stopped Friday, how long before your family felt it?
> For most households it's 30 days or less. Term life replaces that paycheck for your family if the worst happens. I'll show you what coverage costs in your situation — no cost, no obligation.

**Compliance language to keep in:** "term life insurance," "subject to underwriting," "rates vary by age, health, and coverage amount."
**Compliance language to KEEP OUT:** "guaranteed approval," "free money," "investment returns," "build wealth," "everyone qualifies," "lock in rates forever," "tax-free retirement" — all of these will get the ad rejected by Meta and/or flagged by Primerica.

---

## PILLAR 3 — Three Video Ads (Hooks, Visuals, Scripts)

### Universal direction for the on-camera you (23M, Atlanta)

**Wardrobe:**
- Solid navy or charcoal quarter-zip OR a clean white/light-blue button-down with sleeves rolled once. **No suit jacket** — at 23 a full suit reads "salesman." No logos, no Primerica-branded apparel on camera (compliance — branded apparel triggers logo-use review).
- Minimal jewelry. Watch is fine. Clean fade, trimmed beard if you have one.

**Setting (pick one, keep it consistent across all 3 spots so the algorithm reads it as one creator):**
- **Option 1 (preferred):** A clean home office — bookshelf or plant in soft focus behind you, warm lamp light off-camera, daylight from the side. Reads "competent advisor working from home" not "kid in a dorm."
- **Option 2:** Walking-and-talking shot in a recognizably Atlanta-ish residential neighborhood (sidewalk, trees) — feels native to Reels.

**Camera:** Phone, vertical 9:16, eye level (NOT below — below makes you look younger). Lock exposure on your face.

**Body language to bridge the age gap:**
- Slow your speech ~15% from your natural pace. Young people read fast = nervous = unqualified.
- Eye contact straight into the lens, not at yourself in the screen.
- Hands visible, gesture on emphasis but stay in frame.
- One natural smile in the first 3 seconds, then settle into earnest. You're the friend who happens to do this for a living, not a hype-man.

**Captions:** Burn in captions (CapCut auto-caption is fine). 80% of FB video plays muted.

**Length:** 30–45 seconds. Anything past 45s loses Reels distribution.

**Compliance overlay (must appear in every video, on-screen text last 2–3 seconds):**
> "Licensed in [GA]. Term life insurance offered through Primerica Life Insurance Company. Rates and approval subject to underwriting."
> *(Submit for Primerica compliance review — exact wording is dictated by your RVP/the Home Office. Do NOT freelance the disclosure.)*

---

### Ad 1 — "The Paycheck Question" (Income Replacement Angle)

**Hook (0–3s, on-camera, direct to lens):**
> "If your paycheck stopped this Friday, how long before your family felt it?"

**Beat 2 (3–10s):**
*B-roll cut: shot of an envelope of bills on a kitchen table, or just stay on you.*
> "For most families I work with here in Atlanta, the answer is less than a month. Rent, daycare, groceries — none of that pauses."

**Beat 3 (10–25s):**
*Back on you, leaning slightly forward.*
> "Term life insurance is built for exactly that. It replaces your income for your family if something happens to you. For a healthy 25- to 45-year-old, it usually costs less than a tank of gas a month — but the actual rate depends on your age, your health, and how much coverage makes sense."

**Beat 4 — CTA (25–35s):**
> "If you've never had someone walk you through what your number should be, tap the button below. Four quick questions, I'll text you a free quote today, and if it doesn't make sense for your family — no pressure, that's a totally fine answer."

**On-screen text:** "Free term life quote — Atlanta families" + compliance disclosure card at the end.

---

### Ad 2 — "The Mortgage Doesn't Care" (Debt / Homeowner Angle)

**Hook (0–3s, walking shot OR seated lean-in):**
> "If you just bought a house in Atlanta, this 30 seconds might save your family the house."

**Beat 2 (3–12s):**
> "Here's what a lot of new homeowners don't realize: if something happens to you, the mortgage company doesn't pause the payment. Your family is grieving and the bank is still expecting the 1st."

**Beat 3 (12–25s):**
> "A term life policy sized to your mortgage means your family can stay in the home — no scramble, no forced sale. I'm a licensed life agent right here in metro Atlanta, and this is the conversation I have most often."

**Beat 4 — CTA (25–35s):**
> "Tap below, tell me your mortgage balance and a couple basics, and I'll send you a free quote today. No phone tag — I'll text first."

---

### Ad 3 — "The Conversation Nobody Has" (Empathy / Young Parent Angle)

**Hook (0–3s, soft tone, slight smile then serious):**
> "I'm 23. I'm not a parent yet. But I sit with parents every week who tell me the same thing —"

**Beat 2 (3–12s):**
> "— 'I knew I needed to figure this out, I just kept putting it off.' And then life happens and they're glad they didn't wait."

**Beat 3 (12–25s):**
> "Term life isn't complicated and it isn't expensive for most healthy families. It's a small monthly amount that means your kids' world doesn't fall apart financially if you're not there. That's the whole product."

**Beat 4 — CTA (25–35s):**
> "If you're a parent in Atlanta and you've been putting this off, let me make it easy. Tap the button, four quick questions, free quote back to you today. No pressure, ever."

> *Why this works for a 23-year-old:* you name the age gap before the viewer does. Disarms the "what does this kid know" objection in 3 seconds.

---

### Compliance language NOT to use in any of the three

❌ "Guaranteed approval" / "everyone qualifies"
❌ "Lock in your rate forever" (term policies have a level period, then expire/convert — say it accurately)
❌ "Tax-free retirement income" (that's a different product line and triggers securities review)
❌ "Investment" / "returns" / "build wealth" — term life is not an investment
❌ Specific monthly dollar amounts ("$9.99/month!") unless you have a Primerica-approved illustration with all assumptions shown
❌ The Primerica logo on screen unless you have logo-use approval

---

## PILLAR 4 — Low-Friction Lead Form (Instant Form)

Goal: enough info to quote and prioritize, few enough fields to submit on a phone in <45 seconds.

### Form type
**Use "More volume" form type**, not "Higher intent."
- "Higher intent" adds a review screen that cuts conversion ~20–30%. You need volume today; you can re-qualify on the call.

### Intro screen
- **Headline:** "Get your free term life quote — Atlanta"
- **Image:** Same first frame as the video (continuity = higher conversion)
- **Description (3 short bullets):**
  > • Licensed life agent in Atlanta
  > • Free quote, no obligation, no phone spam
  > • You'll hear from me by text within minutes

### Questions (in this exact order)

1. **Full name** (autofill — pre-filled from FB profile, near zero friction)
2. **Email** (autofill)
3. **Phone number** (autofill — critical for the speed-to-lead protocol)
4. **ZIP code** (autofill if available, otherwise short-answer — needed for state-licensing routing)
5. **Custom multiple choice — Date of birth range:**
   - Under 25 / 25–34 / 35–44 / 45–54 / 55–64 / 65+
   *(Range, not exact DOB — lower friction, still gives you a quoting bracket. Ask exact DOB on the phone.)*
6. **Custom multiple choice — "Do you currently use any tobacco or nicotine products (including vapes)?"**
   - No / Quit 12+ months ago / Yes
   *(Single biggest rate driver — you need it before you quote.)*
7. **Custom multiple choice — "What's the main reason you're looking?"**
   - Protect my family's income
   - Cover my mortgage / debt
   - Replace or upgrade existing coverage
   - Just exploring / not sure yet
   *(Doubles as intent qualifier and gives you the opening line of the call.)*
8. **Custom multiple choice — "Best time to reach you today?"**
   - Right now
   - Within the next hour
   - Later today / evening
   - Tomorrow

**Stop at 8.** Do not ask income, beneficiaries, health conditions, or coverage amount on the form — every one of those tanks submission rate and you can ask on the phone.

### Privacy policy
You **must** link to a privacy policy URL (Meta requires it). If you don't have one, generate a basic one tonight; for today, link to Primerica's public privacy policy page if your RVP says that's acceptable (verify first — do not assume).

### Thank-you screen
- **Headline:** "Got it — I'll text you in the next few minutes."
- **Button 1:** "Text me now" → `sms:+1XXXXXXXXXX?body=Hi%2C%20I%20just%20submitted%20the%20form` (deeplinks to their messaging app with a pre-filled text to you — turns inbound leads into outbound texts from THEM)
- **Button 2:** "Book a 15-min call" → your Calendly / SavvyCal link (15-min slots, today + tomorrow only visible)

The text-me-now button is the single highest-leverage thing on this whole page. It collapses speed-to-lead from minutes to seconds.

---

## PILLAR 5 — Speed-to-Lead Protocol (the moment a lead drops)

Industry data is brutal: contact in **<5 minutes** is ~9× more likely to convert than 30+ minutes. For SAC insurance leads on FB, the half-life is even shorter because users are mid-scroll. Treat every lead as a fire drill.

### Setup (do this BEFORE the campaign goes live)

- [ ] **Meta Lead Center notifications ON** in the Meta Business Suite app on your phone — push + sound.
- [ ] **Lead webhook → CRM/Zapier/Make** so leads also hit your phone via SMS within 30 seconds. Free path: Zapier "FB Lead Ads → SMS by Twilio (or your own number via Google Voice)."
- [ ] **Calendar:** open 15-min slots from now until 8 PM, every 30 min. Hold them.
- [ ] **Two text templates and one voicemail script saved in your phone** (below).
- [ ] **Quoting tool open** in a tab (Primerica's TermNow / agent portal) with your profile loaded.

### The 5-minute drill (run for every lead)

**T+0 to T+2 minutes — Text first, not call.**
Cold calls from unknown numbers get ignored by anyone under 40. Text from your real cell:

> Hey [First name], it's [Your name] — the licensed life agent from the Facebook ad you just filled out. Thanks for reaching out. You picked "[their reason from Q7]" as the reason — totally common one. I can pull a quick quote for you right now if you've got 10 minutes, or grab a slot here: [Calendly link]. Either works.

**T+2 to T+5 minutes — Call.**
If no text reply in 2 min, call from the same number you texted from. Two rings minimum, leave voicemail:

> "Hey [First name], this is [Your name] — I'm the agent from the ad you filled out a couple minutes ago, calling like I said I would. I just texted you too. When you've got a minute today, shoot me a text back or give me a ring — happy to walk you through your quote. Talk soon."

**T+5 to T+30 minutes — Second touch.**
If still no answer, one more text:

> No worries if now's not a good time — want me to just text you the quote when I have it? Reply YES and I'll get it to you by tonight.

This converts the silent leads. ~25–35% of "no-answer" leads will reply YES and re-enter the funnel.

### The live conversation (when they pick up — 7-minute frame)

1. **Confirm + thank (15 sec):** "Hey, thanks for filling that out — gonna make this quick and useful for you."
2. **Mirror their reason (30 sec):** "You said you're looking at this to [protect your family's income / cover the mortgage / etc.] — tell me a little more about what's going on at home."
3. **Three discovery Qs (90 sec):**
   - "Anyone else dependent on your income — spouse, kids?"
   - "What's your household roughly bringing in a year — ballpark is fine?"
   - "Any coverage in place right now, even through work?"
4. **Quote with the range (90 sec):** Give a coverage range (e.g., "based on what you told me, most families like yours land in $250k–$500k of term"), and a monthly cost RANGE — never a single dollar figure until underwritten. "Subject to underwriting" out loud, every time.
5. **Close to the appointment, not the sale:** "I want to do this right and pull a real apples-to-apples quote with the exact numbers — that's a 20-minute Zoom. I have today at [X] or tomorrow at [Y]. Which works?"

**Do NOT try to bind a policy on this first call.** Same-day appointment booked = win. The actual app + underwriting happens in the scheduled session.

### Compliance guardrails on every call

- State your name, that you're a licensed life agent, the state you're licensed in, and that you represent Primerica Life Insurance Company.
- Don't quote dollars without saying "subject to underwriting."
- Don't promise approval. Don't promise rates.
- Don't pitch any non-insurance product (securities, debt consolidation, business opportunity) on this first call — those are separate compliance regimes and several require different licenses.
- Log the call in your CRM / Primerica system per home-office requirements.

### End-of-day scoreboard (for tonight)

Before you log off, count:
- Leads received
- Texted in <5 min (target: 100%)
- Connected by phone (target: 35–50% of leads on day 1)
- Appointments booked today/tomorrow (target: 25–40% of connected)
- Cost per lead (CPL) — kill the bottom creative if its CPL is >2× the best one

---

## TL;DR — what you do in the next 60 minutes

1. Confirm GA license + Primerica compliance can review TODAY. If not, stop.
2. Submit all 3 video scripts + ad copy + lead form to Primerica compliance now.
3. While that's in review: shoot the 3 videos (same outfit, same setting, ~30s each, vertical, captions).
4. Build the campaign in Meta Ads Manager as a draft (Pillar 1 settings, SAC = Insurance).
5. Wire up the lead webhook → your phone (Zapier or Lead Center push notifications).
6. The second compliance approves: publish. Submit to Meta review. Watch Lead Center.
7. Run the speed-to-lead protocol on every lead the moment it lands.
