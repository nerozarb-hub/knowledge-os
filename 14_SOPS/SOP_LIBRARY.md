---
title: "SOP Library"
domain: "14_SOPS"
source_notebooks: 28
source_count: 2213
document_type: "retrieval-library"
agent_use: true
confidence: "medium"
freshness_sensitive: true
last_extracted: "2026-08-30"
status: "retrieval"
tags: [notebooklm, sops, source-grounded]
---

> **Authority boundary:** This library is supporting research. It does not override current canonical SOPs, client truth, or Hamza-only authority. Verify platform tactics and company claims before execution.

# NEROZARB OPERATIONS COGNITIVE OPERATING SYSTEM: THE COMPREHENSIVE SOP LIBRARY (2026.Q3)

---

## 1. STRATEGIC PURPOSE & COMPLIANCE BLUEPRINT

This SOP library serves as the unified, high-density, and legally/operationally grounded manual for all human partners and AI agent nodes running within the **NEROZARB System** [MC-1.1, MM-1.1]. Every procedure herein is designed to eliminate speculative operations, "AI sheen," and "agency distrust" [MC-1.1, MC-2.3]. 

All executing entities (whether human specialists or computational AI agents) must adhere strictly to these steps [MC-1.2]. Factual claims and procedures are pulled directly from our grounded Master Operating Systems and knowledge synthesis [MC-1.2]. No external training data may be used to fill operational gaps [MC-1.2].

---

## 2. THE SEVEN IMMUTABLE OPERATIONAL AXIOMS

*   **Axiom 1: Social Media is NOT Social; It is Media [MC-3, MM-2.1].** Platforms are matchmaking engines pairing highly specific topics with highly specific viewer interests [MC-3]. Follower moats are dead [MC-3]. You win by optimizing for the platform's matchmaking algorithm, not by chasing vanity likes [MC-3].
*   **Axiom 2: You Are NOT the Niche [MC-3, MM-2.1].** Documenting daily life is a relic of the low-supply era [MC-3]. Viewers consume content solely for self-interest (entertainment or tactical usefulness) [MC-3]. Fragmenting topics confuses the algorithm and throttles distribution [MC-3].
*   **Axiom 3: Restraint is Authority [MC-3, MM-2.1].** High-status brands command attention through negative space and aggressive minimalist control [MC-3]. Clutter is a signal of desperation; negative space is a signal of luxury [MC-3]. Every element on a canvas that does not explicitly serve the strategic message dilutes authority [MC-3].
*   **Axiom 4: Visuals are the Cake; Words are the Icing [MC-3, MM-2.1].** The human eye processes motion, color, and brightness in 200 milliseconds (bottoms-up processing) [MC-3], long before the brain comprehends text or spoken audio [MC-3]. Visuals dictate the "click/stop"; words dictate the "stay" [MC-3].
*   **Axiom 5: Dopamine is a Chemical of Prediction, NOT Reward [MC-3, MM-2.1].** To make content addictive, you must keep the brain off-balance [MC-3]. Dopamine is released when a viewer is actively anticipating what will happen next, trying to resolve a curiosity loop [MC-3]. You must open a new loop *before* closing the existing one [MC-3].
*   **Axiom 6: Trust is a Mathematical Product of Content Minutes [MC-3, MM-2.1].** Trust is built by compounding minutes of attention [MC-3]. You must use short-form to drive mass exposure ("world exposure") and long-form/email/community to drive deep immersion ("world immersion") [MC-3].
*   **Axiom 7: Pain Prioritizing Trumps Opportunity Promising [MC-3, MM-2.1].** The human amygdala is biologically wired to prioritize threats over opportunities (loss aversion) [MC-3]. A viewer is twice as motivated to avoid losing $10,000 than making an extra $10,000 [MC-3]. Content that agitates a specific "Bleeding Neck" pain point will always out-convert content promising a vague positive benefit [MC-3].

---

## 3. DOMAIN 1: RESEARCH DOMAIN

### 3.1 SOP R1: The Deep Empathy Research Protocol
*   **Purpose:** To systematically extract raw, un-sanitized customer language, visceral vocabularies, competitor objections, and deep psychological purchase drivers, bypassing clean corporate marketing summaries [MC-5, MM-5.1, PA-SOP1, CP-SOP1].
*   **Trigger:** Launching a new client acquisition campaign, onboarding a new SKU, or initiating a quarterly content cycle [MM-5.1].
*   **Inputs:** Complete raw customer reviews CSV from storefront backends (Shopify, Yotpo, Okendo, Amazon), competitor product URLs, and negative review logs [MM-5.1, PA-SOP1].
*   **Prerequisites:** Dedicated LLM instance (Claude Sonnet preferred) configured, list of top 3 competitor domains compiled [MM-5.1, PA-SOP1].
*   **Procedure:**
    1.  **Download Reviews CSV:** Export the complete CSV of all customer reviews from the client storefront backend [MM-5.1, PA-SOP1].
    2.  **Initialize Claude Project:** Open a dedicated project space in Claude. Upload the reviews CSV along with negative review logs and competitor product URLs [MM-5.1, PA-SOP1].
    3.  **Run Golden Nugget Mining:** Execute the "Reviews to Golden Nugget" Mining Prompt (see SOP PR1) to isolate hyper-specific frustrations, competitor objections, and raw customer vocabulary [MM-5.1, PA-SOP1].
    4.  **Perform Reddit Social Listening:** Search niche-relevant subreddits (e.g., r/skincareaddicts, r/parenting, r/SaaS) for the extracted frustrations. Note the exact conversational vocabulary and visceral phrases used by real humans (e.g., fake tan "biscuit smell") [MM-5.1, PA-SOP1].
    5.  **Compile Brand Brain:** Save raw verbatim quotes, competitor objections, and the extracted emotional language to `/workspace/scratch/` as the **Brand Brain** [MM-5.1, PA-SOP1].
*   **Decision Points:**
    *   **IF** high price is identified as the primary customer objection [MM-6.2, PA-Decision2, CP-Rule1]:
        *   **THEN** lead with the price objection directly in the content hook [MM-6.2].
        *   **AND** deploy the "We are not cheap and we don't want to be" high-status script format [MM-6.2, CP-Rule1].
    *   **IF** the product market sophistication is at Stage 3 or 4 [MM-4.6, CP-Rule2]:
        *   **THEN** suppress raw benefit claims [CP-Rule2].
        *   **AND** reframe copy entirely around your Unique Mechanism [CP-Rule2].
*   **Output:** Standardized, evidence-backed "Brand Brain" markdown document (.md) linked to the active CRM account record [MM-5.1, OUT-11.1].
*   **DoD:** A markdown file containing at least 15 verified, raw customer quotes, a categorized list of 5 primary objections, and 10 specific pain-point keywords [MM-5.1].
*   **QA:** No corporate marketing jargon (e.g., "next-level", "transformative", "synergy") allowed [CP-SOP3]. All emotional keywords must be verified from actual user text, not inferred by AI [MM-5.1].
*   **Metrics:** Time to complete research (target < 120 minutes), unique objections extracted ($\ge 10$).
*   **Recovery:** If the client's storefront has < 50 reviews, scrape Amazon or Trustpilot reviews for the top 3 direct competitors using Apify and merge into the raw CSV dataset [PA-SOP1].
*   **Agent Role:** Customer Intelligence Agent (CIA).
*   **Sources:** [MC-5.1, MM-5.1, PA-SOP1, CP-SOP1, CP-SOP2].

### 3.2 SOP R2: Outlier Mining & Idea Development
*   **Purpose:** To systematically extract data-validated video topics, concepts, and hooks from competitor channels, eliminating creative guessing and ensuring high probability of distribution [MC-4, MM-5.8, CO-SOP1, CP-SOP2, PE-SOP5.1].
*   **Trigger:** Monthly content batching planning phase or immediate creative testing campaign setup [MM-5.8, CO-SOP1].
*   **Inputs:** Competitor list, target audience demographic, Sandcastles.ai account credentials [CO-SOP1, MM-5.8].
*   **Prerequisites:** Access to Sandcastles.ai and Claude 3.7 Projects [CO-SOP1, MM-5.8].
*   **Procedure:**
    1.  **Configure Scraper Watchlist:** Log into Sandcastles.ai. Build a highly curated watchlist of 20 to 30 competitor channels or adjacent niche leaders targeting your exact Ideal Viewer Avatar (IVA) [MM-5.8, CO-SOP1].
    2.  **Apply Filters:** Set filter criteria: Post Date = "Last 90 Days," Sponsor Posts = "Excluded" (set minimum engagement rate to 2% to filter out paid/boosted posts) [MM-5.8, CO-SOP1].
    3.  **Isolate Outliers:** Sort descending by **Outlier Score**. Identify any video that has achieved a **5x or better** performance compared to that channel's baseline average view count [MM-5.8, CO-SOP1].
    4.  **Export CSV:** Export the top 100 outlier results to a .csv file [MM-5.8, CO-SOP1].
    5.  **Execute Claude Ingestion:** Upload the .csv file to Claude. Execute the *Ingestion Prompt* (see SOP PR1) to bucket topics, isolate hooks, and generate 10 fresh, contrarian content ideas [MM-5.8, CO-SOP1].
    6.  **Write Reframed Concepts:** For selected ideas, hold 10 of the "11 Lego Bricks" constant to the outlier, and write your proprietary system reframe into the "Substance" block [MM-5.8, CO-SOP1].
*   **Decision Points:**
    *   **IF** a competitor video has an Outlier Score < 5.0 but shows high retention in comments:
        *   **THEN** isolate only the written text hook and test in Trial Reels [MM-4].
    *   **IF** the Outlier Score is $\ge 10.0$ and views exceed creator followings [PE-SOP5.1]:
        *   **THEN** clone the visual hook, set design, and pacing 1:1, modifying only the proprietary mechanism [PE-SOP5.1].
*   **Output:** CSV export sheet of top outliers and a Claude-compiled "10-Idea Campaign Strategy" document saved in `/workspace/scratch/` [MM-5.8, CO-SOP1].
*   **DoD:** Ideation list of 10 fully scoped concepts, each mapping: the source outlier URL, the 5x Outlier Score, the visual hook setup, and the NEROZARB system reframe [MM-5.8, CO-SOP1].
*   **QA:** No idea is approved unless its underlying source outlier achieved a minimum of a **5x view count multiplier** compared to the channel baseline [MM-5.8, CO-SOP1].
*   **Metrics:** Sandcastles outlier verification rate (100%), Outlier view threshold ($\ge 5x$).
*   **Recovery:** If the niche has zero competitor outliers in the last 90 days, expand search to adjacent niches with identical psychographic traits (e.g., shifting from skincare to premium oral hygiene) [MM-5.8, CO-SOP1].
*   **Agent Role:** Creative Research Node / Ideation Agent.
*   **Sources:** [MC-5.1, MM-5.8, CO-SOP1, CP-SOP2, PE-SOP5.1].

### 3.3 SOP R3: The NERO Programmatic Sifting Pipeline
*   **Purpose:** To automatically extract and qualify premium local and Gulf business leads, bypassing manual spreadsheet assembly and qualifying leads on active marketing activity [AOS-5.1].
*   **Trigger:** Automated cron trigger at 12:00 AM daily, or GTM pipeline capacity drop below 50 active prospects [AOS-5.1].
*   **Inputs:** Apify Maps Extractor API key, geographic boundaries, pre-approved niche lists [AOS-5.1].
*   **Prerequisites:** Apify account connected, Make.com webhook configured, and Notion CRM War Room live [AOS-5.1].
*   **Procedure:**
    1.  **Scrape Google Maps:** Deploy Apify's Google Maps Extractor or Manus AI to scrape business profiles in high-status, affluent areas [AOS-5.1].
        *   *Pakistan Local:* Lahore DHA Phases 1–6, Gulberg II & III, Model Town, Lahore Cantt, MM Alam Road; Islamabad Sector F and E [AOS-5.1].
        *   *Gulf/MENA:* Affluent sectors of Doha, Kuwait City, Riyadh (strictly excluding Dubai/UAE) [AOS-5.1].
    2.  **Filter by Niche:** Restrict extraction to high-ticket B2C verticals: Aesthetic Clinics, Dermatologists, Fine Dining, Interior Designers, Premium Salons, Boutique Fashion, and Real Estate [AOS-5.1].
    3.  **Verify Active Marketing Budget:** Deploy social scrapers to verify target businesses have active Instagram or Facebook links with posts published in the last 30 days [AOS-5.1].
    4.  **Filter by Authority:** Extract follower metrics. If the Instagram profile has under 2,000 followers or shows obvious bot-buying behavior (high follower-to-engagement asymmetry), flag as Archived-Disqualified [AOS-5.1].
    5.  **Filter by Revenue (Pakistan Only):** Exclude accounts generating under 1,000,000 PKR in monthly revenue to prevent auditing broke clients [AOS-5.1].
    6.  **Inject to CRM:** Route the qualified payload through a Make.com webhook to inject lead profiles directly into the visual Notion CRM War Room [AOS-5.1].
*   **Decision Points:**
    *   **IF** contact email is missing from Google Maps/socials:
        *   **THEN** run Hunter.io or Apollo.io API enrichment step to extract Founder/CMO address [OUT-11.1].
    *   **IF** follower count is > 100,000:
        *   **THEN** flag as "Enterprise Stealth Opportunity" and route to high-status CEO direct outreach pipeline [AOS-5.1, OUT-11.1].
*   **Output:** Live, structured prospect record populated in the Notion CRM War Room with active pixel data and follower count [AOS-5.1].
*   **DoD:** Leads injected into CRM with complete phone, name, verified website, Instagram URL, active post check (Y/N), and geographic location [AOS-5.1].
*   **QA:** No leads from Dubai/UAE allowed under the strict Gulf exclusion policy [MC-1.1, AOS-5.1]. Active post date must be within 30 days.
*   **Metrics:** Daily scraped leads ($\ge 500$), target qualification rate ($\ge 12\%$) [AOS-5.1].
*   **Recovery:** If Google Maps API fails, switch to manual Yelp and Instagram location tag scraping using alternate proxy-backed ScrapingBee accounts [AOS-5.1].
*   **Agent Role:** GTM Systems Lead / Data Scraping Agent.
*   **Sources:** [MC-1.1, AOS-5.1].

---

## 4. DOMAIN 2: MARKETING DOMAIN

### 4.1 SOP M1: Dual-Instagram Profile Optimization
*   **Purpose:** To turn cold profile visitors into high-intent buyers in under 5 seconds by separating active outreach from brand authority [AOS-5.2, PE-SOP5.4].
*   **Trigger:** Launching organic social outreach or initiating cold outreach via direct message [AOS-5.2].
*   **Inputs:** High-contrast personal creator headshot, professional Void Black (#0A0A0A) background designs, bio copywriting briefs [AOS-5.2].
*   **Prerequisites:** Two active Instagram handles registered: Account 1 (@nerozarb) and Account 2 (Personal/expert handle, e.g., @hamzabuilds) [AOS-5.2, PE-SOP5.4].
*   **Procedure:**
    1.  **Configure Account 1 (@nerozarb) — The Brand Hub:**
        *   Design visual grid with Onyx Black backgrounds, Olive Green radial glow systems, and left-aligned Montserrat Black headlines [AOS-5.2, PE-SOP5.4].
        *   Pin exactly 3 reels: Pin 1 = Founder Story Reel; Pin 2 = 60-Day Sprint Walkthrough; Pin 3 = Best performing Educational Reel [AOS-5.2].
        *   Build exactly 5 Highlights with Void Black covers and Olive Green icons: (1) START HERE, (2) PROOF (case studies), (3) SERVICES, (4) TIPS (15s value clips), (5) FAQ (pricing and result times) [AOS-5.2].
    2.  **Configure Account 2 (@hamzabuilds) — The Active Stealth Arm:**
        *   Upload a casual, high-contrast, high-status human profile picture on a dark background [AOS-5.2].
        *   Ensure zero mention of "NEROZARB," "agency," "CEO," or olive green design assets [AOS-5.2].
        *   Bio must focus purely on raw growth observations and systems thinking [AOS-5.2].
        *   Pin exactly 3 reels: Pin 1 = My Story (casual, no pitch); Pin 2 = Mission Statement; Pin 3 = Best Value Reel [AOS-5.2].
        *   Build exactly 3 Highlights with solid dark covers: (1) ABOUT ME (15s selfie video), (2) INSIGHTS (raw teardowns), (3) RESULTS (unbranded proof) [AOS-5.2].
    3.  **Run Mobile 5-Second Test:** Open both profiles on mobile. Verify a visitor can answer: *Who is this? What do they do? Why should I care? What should I do next?* in 5 seconds [AOS-5.2, MM-5.6].
*   **Decision Points:**
    *   **IF** the visitor profile fails the 5-Second Test (ambiguity in offer):
        *   **THEN** rewrite bio using the Proof-First framing formula: `[Lived Proof / Metric] / [Promise] / [Unique Mechanism]` [MM-5.6].
    *   **IF** Account 2 experiences a drop in reply rates below 10%:
        *   **THEN** audit profile for hidden agency pitches or promotional words and delete immediately [AOS-5.2].
*   **Output:** Fully optimized, synchronized dual-profile ecosystem live on Instagram [AOS-5.2].
*   **DoD:** Account 1 has exactly 5 highlights; Account 2 has exactly 3 highlights. Zero crossover of brand assets on Account 2 [AOS-5.2].
*   **QA:** No links or tags to Account 1 should exist on Account 2's main bio. Bio must pass the 5-Second Test on mobile [AOS-5.2, MM-5.6].
*   **Metrics:** Profile visitor-to-follower rate ($\ge 15\%$), outreach reply rate on Account 2 ($\ge 25\%$) [AOS-5.2, MM-5.6].
*   **Recovery:** If Instagram flags the personal account for link sharing, pause outbound links, shift to native comment keyword triggers ("DM word 'SCALE'"), and route traffic through DMs [AOS-5.2].
*   **Agent Role:** Social Media Manager Node / Brand Custodian.
*   **Sources:** [AOS-5.2, PE-SOP5.4, MM-5.6].

### 4.2 SOP M2: High-Ticket Instagram DM Funnel Setup & Qualification
*   **Purpose:** To bypass traditional high-friction landing pages and automate qualification/capture of organic social traffic natively in Instagram DMs [MC-5.9, MM-5.5, MC-SOP5].
*   **Trigger:** A social visitor comments a trigger keyword (e.g., "ENGINE", "SCALE") on a reel or sends a direct message [MM-5.5].
*   **Inputs:** Verified Meta Graph API connection, ManyChat account access, structured qualification script templates [MM-5.5].
*   **Prerequisites:** ManyChat officially integrated and authorized. Unofficial scraper/automation bots strictly banned to protect account security [MM-5.5].
*   **Procedure:**
    1.  **Deploy Trigger Monitoring:** Configure ManyChat to monitor all reels, posts, and story replies for specific high-value keywords [MM-5.5].
    2.  **Execute Instant Auto-DM:** Set automation to dispatch a personalized direct message within 180 seconds of keyword detection [MM-5.5].
    3.  **Execute Qualitative Qualification Flow:** Set up automated chat sequences to parse customer details without friction [MM-5.5]:
        *   *Step 1 (Context Capture):* Ask 1 open-ended question about their current situation (e.g., "What's your current biggest bottleneck scaling your salon?") [MM-5.5].
        *   *Step 2 (The Hook):* Provide an immediate "Zero-Click" micro-asset directly in chat (e.g., a simple diagnostic breakdown table or high-value infographic) to prove peer authority [MM-5.5].
        *   *Step 3 (Critical Event / Action Pressure):* Identify their primary deadline or trigger (e.g., "Do you need this growth system implemented before Q4?") [MM-5.5].
    4.  **Execute Human Handoff:** Once a critical event/positive intent is verified, trigger a notification to the sales account executive [MM-5.5].
    5.  **WhatsApp Handoff:** Transfer the qualified prospect to a WhatsApp-based voice memo funnel [MM-5.5, AOS-5.1].
*   **Decision Points:**
    *   **IF** prospect does not reply to the open-ended question within 24 hours:
        *   **THEN** dispatch a automated, low-pressure follow-up offering a 1-page free resource [MM-5.5].
    *   **IF** the prospect is disqualified (e.g., Pakistan Local under 1M PKR revenue):
        *   **THEN** trigger the "Self-Study" path, sending them to a free YouTube resource and exit the queue [AOS-5.1].
*   **Output:** Qualified lead details and conversion signals synced natively to HubSpot CRM [MM-5.5].
*   **DoD:** Lead record updated with Situation, Pain, Trigger Event, and WhatsApp number. Notification sent to human rep [MM-5.5].
*   **QA:** ManyChat workflow must utilize official API [MM-5.5]. Message copy must contain zero broken links or spelling errors.
*   **Metrics:** Comment-to-DM conversion rate ($\ge 85\%$), DM-to-Qualified Lead conversion rate ($\ge 18\%$) [MM-5.5].
*   **Recovery:** If ManyChat API disconnects, immediately halt comment-trigger content, switch to "Link in Bio" redirection, and manually qualify incoming direct messages [MM-5.5].
*   **Agent Role:** Automation Engineer / Inbound Sales Rep.
*   **Sources:** [MC-5.9, MM-5.5, MC-SOP5].

### 4.3 SOP M3: Infinite-Loop Reel Production
*   **Purpose:** To produce highly addictive, short-form vertical video assets that loop seamlessly, maximizing platform retention metrics and organic shares [MM-5.12].
*   **Trigger:** Monthly batching pipeline release, or high-potential outlier hook isolated in Sandcastles [MM-5.12, CO-SOP1].
*   **Inputs:** Approved talking-head script, minimalist studio setup, camera/mic equipment [MM-5.12].
*   **Prerequisites:** High-contrast studio backdrop, direct-response script utilizing the 15/3 constraint [MM-5.12, CO-SOP2].
*   **Procedure:**
    1.  **Write Grammatical Continuity:** Draft the final script sentence to merge seamlessly back into the opening hook, hiding the transition [MM-5.12].
        *   *Opening Hook:* "...why your organic reach is completely dead." [MM-5.12].
        *   *Closing Script:* "If you are still posting without keyword-rich alt text, that is exactly..." [MM-5.12].
    2.  **Shoot for Bottom-Up Attention:** Start recording mid-action (e.g., pouring water, sketching, speaking mid-phrase) to immediately disrupt scroll autopilot [MM-5.12]. Avoid greetings, intros, or hand-waves [MC-3, MM-5.12, CO-SOP2].
    3.  **Pace and Cut Aggressively:** Cut out all pauses, breaths, and micro-sighs [MM-5.12]. Every 1.5 to 3 seconds, force a visual pattern break: crop-zoom shift, new camera angle, or high-contrast B-roll overlay [MM-5.12].
    4.  **Format Burned-In Captions:** Burn highly stylized, Montserrat Bold ALL CAPS captions word-by-word at the exact center of the screen [MM-5.12]. Avoid placing text in the bottom 30% "UI Dead Zone" [MM-5.12].
    5.  **Export Settings:** Export the video at exactly 1080x1920 pixels, 60fps, h.264 compression, with zero watermarks [MM-5.12].
*   **Decision Points:**
    *   **IF** the natural script structure cannot loop grammatically:
        *   **THEN** film a visual loop (e.g., starting and ending the clip with the exact same hand motion and frame placement) [MM-5.12, CP-SOP4].
    *   **IF** the video hold rate drops below target thresholds at the 3s mark:
        *   **THEN** pause the reel and replace the first 3 seconds with a visual-jolt pattern break (e.g., dropping a product onto a hard surface) [MM-5.12, PA-SOP7].
*   **Output:** Raw, loop-verified MP4 asset ready for publication [MM-5.12].
*   **DoD:** Video plays seamlessly on repeat without a visible seam in audio or video. Montserrat captions verified safe from UI overlay elements [MM-5.12].
*   **QA:** Zero corporate transition slides allowed. Audio must have zero popping or low-frequency hums [MM-5.12].
*   **Metrics:** 3-Second Hook Rate ($\ge 35\%$), Average watch time ($\ge 100\%$) [MM-5.12].
*   **Recovery:** If the loop has a noticeable jump in audio, apply a 0.1-second crossfade on the audio track in the editing software to smooth the transition [MM-5.12].
*   **Agent Role:** Video Editor / Production Node.
*   **Sources:** [MM-5.12, CO-SOP2].

### 4.4 SOP M4: Mixed-Format Carousel Generation
*   **Purpose:** To generate high-end, brand-consistent carousel posts combining aesthetic static slides with silent video loops to dominate platform feed algorithms [MM-5.11].
*   **Trigger:** Identifying a highly discussed customer objection or complex system blueprint in the CRM [MM-5.11].
*   **Inputs:** Objection logs, system blueprints, Figma/Canva design templates [MM-5.11].
*   **Prerequisites:** Void Black (#0A0A0A) background color set, Montserrat Black and Space Mono fonts installed [MC-4, MM-5.11].
*   **Procedure:**
    1.  **Extract Pain Point:** Locate a highly validated customer frustration or bottleneck in the Brand Brain or CRM [MM-5.11].
    2.  **Map Narrative Structure (The 10-Slide Deck):**
        *   *Slide 1 (The Scroll-Stopper):* Write a bold headline (< 10 words). Leave > 50% negative space. Include a "Swipe →" visual cue [MM-5.11].
        *   *Slide 2 (The Frame Shift):* Show a "Before vs. After" comparison matrix to validate Slide 1 [MM-5.11].
        *   *Slides 3–5 (The System):* Explain the *why* using "Information Asymmetry" [MM-5.11]. Embed technical schematics or process flow charts [MM-5.11].
        *   *Slides 6–8 (The Playbook):* Step-by-step actionable resolution [MM-5.11].
        *   *Slide 9 (The Case Study Proof):* Show a high-contrast CleanShot X screen-capture of client results or slack messages [MC-5.3, MM-5.11].
        *   *Slide 10 (Single-Gate CTA):* Point directly to a single, high-contrast WhatsApp link [MC-5.4, MM-5.11].
    3.  **Embed Silent Video Loops:** On Slide 1 and Slide 5, insert a subtle, high-end 3-second animated video loop (e.g., shifting light reflections on glass) rather than a static image to capture bottom-up visual attention [MM-5.11].
    4.  **Perform Design Audit:** Ensure a maximum of 3 visual elements are present on any slide to prevent cognitive load [MC-4, MM-5.11].
*   **Decision Points:**
    *   **IF** text content on a slide exceeds 30 words:
        *   **THEN** strip 50% of copy and replace with a simplified graphic symbol [MM-5.11].
    *   **IF** carousel swiping speed drops at Slide 3:
        *   **THEN** place a contrarian "Header Interruption" on Slide 3 to break reading autopilot [MC-5.4].
*   **Output:** 10-Slide mixed-format high-resolution carousel asset package [MM-5.11].
*   **DoD:** Complete slide set exported, containing Onyx Black backgrounds, Montserrat headlines, and exactly 1 call to action on the final slide [MC-5.4, MM-5.11].
*   **QA:** No drop shadows or text glows. Text must align strictly to the left edge of the slides [MC-5.4, MM-5.11].
*   **Metrics:** Swipe-through completion rate ($\ge 65\%$), CTA clicks ($\ge 2.5\%$) [MM-5.11].
*   **Recovery:** If platform compression degrades slide text clarity, re-export slides at 2000x2000 pixels in PNG-24 format to force high-fidelity rendering [MM-5.11].
*   **Agent Role:** Graphic Designer Node / Brand Stylist.
*   **Sources:** [MC-4, MC-5.4, MM-5.11].

---

## 5. DOMAIN 3: PAID ADS DOMAIN

### 5.1 SOP PA1: The "AndroMeta One" Pure Consolidation Setup
*   **Purpose:** To maximize account data liquidity, eliminate campaign fragmentation, bypass audience overlap penalties, and allow Meta's machine learning model to auto-distribute budget across the full funnel efficiently [MM-4, PA-SOP2, AC-SOP6].
*   **Trigger:** Launching a brand's scaling phase, or replacing a fragmented ad account setup [AC-SOP6, PA-SOP2].
*   **Inputs:** Clean Meta Ads Manager account, catalog feeds, approved conceptually diverse ad creatives (8 to 20 units) [AC-SOP6, PA-SOP2].
*   **Prerequisites:** Server-side Conversions API verified, website domains authenticated, legal identity verified [MM-5.10, PA-SOP4].
*   **Procedure:**
    1.  **Initialize Campaign:** Navigate to Meta Ads Manager, click **Create Campaign**, and select the **Sales** or **Leads** objective based on target business KPIs [AC-SOP6, PA-SOP2].
    2.  **Toggle CBO:** Toggle on **Advantage Campaign Budget (CBO)** at the campaign level [AC-SOP6, PA-SOP2]. Absolutely prohibit the use of ad set budgets (ABO) in scaling campaigns [AC-SOP6, PA-SOP2].
    3.  **Configure Broad Targeting:** Under the ad set level, set targeting to **completely broad** [AC-SOP6, PA-SOP2]:
        *   Choose country, age (18–65+), and gender [AC-SOP6, PA-SOP2].
        *   Exclusions: Set zero detailed interests, behaviors, or lookalike restrictions [AC-SOP6, PA-SOP2].
        *   Do NOT exclude past buyers unless deploying a short-term introductory offer [AC-SOP6, PA-SOP2].
    4.  **Set Placements:** Set to **Advantage+ Placements (Automatic)** [AC-SOP6, PA-SOP2].
    5.  **Deploy Creatives:** At the ad level, upload **8 to 20 conceptually diverse creative units** [AC-SOP6, PA-SOP2]. Combine vertical (9:16) video loops, square (1:1) statics, and multi-format carousels [AC-SOP6, PA-SOP2].
*   **Decision Points:**
    *   **IF** campaign performance falls below target MER:
        *   **THEN** do not change targeting parameters [AC-SOP6]. Introduce 3 new, highly diverse creatives to target new audience pockets [MM-5.3].
    *   **IF** the product catalog has > 50 SKUs:
        *   **THEN** bypass single product UGC [MM-6.1, PA-Decision1]. Deploy an Advantage+ Catalog sales ad with styled Marpipe templates [MM-6.1, PA-Decision1].
*   **Output:** Live, consolidated Advantage+ Scaling campaign operating with complete data liquidity [AC-SOP6, PA-SOP2].
*   **DoD:** Active campaign in Ads Manager with CBO enabled, broad targeting settings, automatic placements, and a minimum of 8 conceptually distinct ad creatives [AC-SOP6, PA-SOP2].
*   **QA:** No interest keywords, LAL audiences, or custom audience exclusions are present in the active scaling ad set [AC-SOP6, PA-SOP2].
*   **Metrics:** Campaign ROAS, Blended MER, Event Match Quality ($\ge 6.0$) [PA-SOP4, PA-Formulas].
*   **Recovery:** If the learning phase gets stuck, increase the daily budget by 10% to push more conversion signals through the system or double-check server-side signal integrations [MM-5.3, MM-5.10].
*   **Agent Role:** Media Buyer Agent / Algorithmic Systems Engineer.
*   **Sources:** [AC-SOP6, PA-SOP2, MM-5.3, MM-6.1, PA-Decision1].

### 5.2 SOP PA2: The 3-Stage Signal Isolation Funnel (Testing to Scale)
*   **Purpose:** To systematically test and isolate champion ad creatives in a controlled environment without disrupting scaling campaigns or resetting learning phases [MM-5.4, AC-SOP7, PA-SOP3].
*   **Trigger:** Creative assets generated from production are ready for validation [AC-SOP7, PA-SOP3].
*   **Inputs:** Fresh ad creative mockups, budget allocation matrices, target CPA metrics [AC-SOP7, PA-SOP3].
*   **Prerequisites:** Sandbox testing campaign created separate from the main scaling campaign [AC-SOP7, PA-SOP3].
*   **Procedure:**
    1.  **Stage 1: ABO Testing Campaign:**
        *   Create campaign named `[TEST] ABO_Creative_Testing_Q3_2026` utilizing **Ad Set Budget Optimization (ABO)** [AC-SOP7, PA-SOP3].
        *   Create exactly 1 Ad Set for each new conceptual angle (e.g., `[Concept_Meme_Comparison]`). Allocate a testing budget equal to exactly $1.5 \times$ target CPA per ad set [AC-SOP7, PA-SOP3].
        *   Inside each ad set, deploy a single dynamic ad utilizing the **3:2:2 Dynamic Creative Protocol** [AC-SOP7, PA-SOP3] (3 creatives, 2 headlines, 2 descriptions).
    2.  **Stage 2: Challenger Campaign:**
        *   Create campaign named `[CHALLENGER] Advantage_Sales_Champion_Ad_Sets` [AC-SOP7, PA-SOP3].
        *   Isolate the top **5 to 10 champion variations** that proved highly efficient in Stage 1 but failed to capture substantial budget [AC-SOP7, PA-SOP3]. Let them compete with dedicated challenger budgets [AC-SOP7, PA-SOP3].
    3.  **Stage 3: Graduate to Core Evergreen:**
        *   Graduate undisputed winners from Stage 2 into the consolidated **Core Evergreen Campaign** [AC-SOP7, PA-SOP3].
        *   Never scale a winning ad unchanged. Scale the underlying concept by horizontal expansion (e.g., turning a winning static headline into a video hook) [AC-SOP7, PA-SOP3].
*   **Decision Points:**
    *   **IF** a creative spends 2x AOV and fails to achieve break-even CPA [MM-5.4]:
        *   **THEN** deactivate the ad set [MM-5.4].
    *   **IF** a creative exceeds target ROAS in Stage 2 [CP-Rule4]:
        *   **THEN** duplicate the exact post-ID directly into the scaling campaign to preserve social proof [CP-Rule4].
*   **Output:** Verified champion creative assets graduated to the core scaling campaign [AC-SOP7, PA-SOP3].
*   **DoD:** Testing ad sets launched, data collected up to 2x AOV, and winning post-IDs successfully transferred to core scaling campaigns [MM-5.4, AC-SOP7].
*   **QA:** Dynamic ad set contains exactly the 3:2:2 configuration [AC-SOP7, PA-SOP3]. Test ad sets must run until they hit the 2x AOV spend threshold before any optimization decision is made [MM-5.4].
*   **Metrics:** Cost Per Click (CPC), Hook Rate ($\ge 25\%$), Hold Rate ($\ge 15\%$), ROAS [PA-Formulas].
*   **Recovery:** If a test ad set fails to spend, check for high audience overlap with existing campaigns and temporarily lower bid/budget caps [AC-SOP7].
*   **Agent Role:** Media Buyer Node / Performance Analyst.
*   **Sources:** [AC-SOP7, PA-SOP3, MM-5.4, CP-Rule4].

### 5.3 SOP PA3: Server-Side Signal Engineering (Pixel-to-CAPI Redundancy)
*   **Purpose:** To maximize Event Match Quality (EMQ), solve cookie-deprecation and ATT tracking limitations, and increase conversion attribution accuracy by implementing server-side Pixel redundancy [MM-5.10, PA-SOP4].
*   **Trigger:** Launching a web storefront or observing an Event Match Quality drop below 6.0 in Events Manager [PA-SOP4].
*   **Inputs:** Meta Pixel ID, Access Token, server-side integration access (Shopify, Custom Node backend, Popsixle, or wetracked.io) [PA-SOP4].
*   **Prerequisites:** Administrative access to Meta Business Manager and dns registrar [MM-5.10, PA-SOP4].
*   **Procedure:**
    1.  **Configure API Connection:** Connect your storefront/CRM directly to Meta's servers using native server-side integrations (e.g., Conversions API) [PA-SOP4].
    2.  **Deploy Deduplication Parameters:** Ensure browser Pixel and server CAPI fire identical event names (`Purchase`, `Lead`, `AddToCart`) [PA-SOP4]. Configure tracking scripts to generate a completely unique, matching `event_id` string for both client-side and server-side payloads of the same event [PA-SOP4].
    3.  **Enrich Customer Match Parameters:** Securely hash (SHA-256) and pass all available first-party data in the server payload (Email, Phone, First Name, Last Name, IP Address, User Agent, Click ID `fbc`, Browser ID `fbp`) [PA-SOP4].
    4.  **Audit Event Quality:** Open Meta Events Manager, locate the active dataset, and verify deduplication rates are at 100% and Event Match Quality scores are high [PA-SOP4].
*   **Decision Points:**
    *   **IF** Event Match Quality scores are < 6.0:
        *   **THEN** review payload and force additional matching parameters (like ZIP code or state) into the server-side JSON schema [PA-SOP4].
    *   **IF** deduplication warnings appear in Events Manager:
        *   **THEN** audit and ensure the `event_id` string generated on the client browser matches the server payload character-for-character [PA-SOP4].
*   **Output:** High-fidelity, adblock-proof conversion signals streaming directly to Meta servers [PA-SOP4].
*   **DoD:** Server-side CAPI events verified in Events Manager with 100% deduplication and an Event Match Quality score of $\ge 7.0$ for primary conversion events [PA-SOP4].
*   **QA:** No unhashed first-party parameters are sent in raw text. Server payloads must execute in < 200ms of transaction completion.
*   **Metrics:** Event Match Quality (EMQ) Score, Deduplication Rate (100%), CAPI Attribution Lift.
*   **Recovery:** If CAPI signals drop, verify webhook server logs for HTTP 400 errors or expired Meta Access Tokens, and regenerate tokens immediately [PA-SOP4].
*   **Agent Role:** GTM Systems Engineer / Tracking Specialist.
*   **Sources:** [PA-SOP4, MM-5.10].

### 5.4 SOP PA4: Click-to-WhatsApp (CTWA) Conversational Funnels
*   **Purpose:** To drive cold social media traffic directly into conversational lead-qualification funnels on WhatsApp, bypassing high-friction landing pages and optimizing conversion rates [MM-5.5, PA-SOP5].
*   **Trigger:** Initiating client acquisition in a region where mobile web page conversion rates are low, or executing campaigns in highly conversational territories [PA-SOP5].
*   **Inputs:** Linked WhatsApp Business API, Meta Business Manager access, qualified chatbot/CRM system (GoKwik, ActiveCampaign, YCloud) [PA-SOP5].
*   **Prerequisites:** Official WhatsApp Business API number verified and connected in Business Manager [PA-SOP5].
*   **Procedure:**
    1.  **Configure Campaign:** Open Ads Manager, select the **Leads** or **Engagement** objective [PA-SOP5].
    2.  **Set Up Ad Set:** Select **Messaging Apps** as conversion location. Uncheck Messenger and Instagram, leaving only **WhatsApp** checked [PA-SOP5]. Set targeting broad [PA-SOP5].
    3.  **Design Ad Level Copy:** Craft a mobile-optimized creative (9:16 vertical video loop). Apply the Ad Copy Formula: *Hook (Local Pain Point) + Benefit + WhatsApp CTA* [PA-SOP5].
        *   *Example:* "Looking for affordable EV chargers in Lahore? Get a free consultation instantly on WhatsApp. Tap below to chat now!" [PA-SOP5].
    4.  **Configure Template Payload:** Build a Pre-filled message template [PA-SOP5]. Set default text to: *"Hi, I'm interested in your EV charging options. Please share pricing and details."* [PA-SOP5].
    5.  **Configure Chatbot Automation:** Connect the WhatsApp API to a conversational CRM. Set automated chatbot to trigger instantly when the pre-filled message is received [PA-SOP5]:
        *   *Step 1:* "Hi 👋 Thanks for reaching out. What is your preferred budget range?" [PA-SOP5].
        *   *Step 2:* Collect name, city, and timeline, then route to CRM [PA-SOP5].
*   **Decision Points:**
    *   **IF** WhatsApp conversation-start cost exceeds ₹120 (or equivalent regional threshold):
        *   **THEN** replace video creative with a static localized price-comparison chart [PA-SOP5, PA-Benchmarks].
    *   **IF** contact fails to answer Bot Step 1 within 10 minutes:
        *   **THEN** trigger a friendly 1-step automated follow-up ping [PA-SOP5].
*   **Output:** Live conversational ad campaign routing prospects directly into automated qualified chat queues [PA-SOP5].
*   **DoD:** Active campaign in Ads Manager with WhatsApp selected, pre-filled message configured, and test chatbot flows fully verified on a mobile device [PA-SOP5].
*   **QA:** Chatbot flow must contain zero dead ends. Verify webhook routes CRM data without delay [PA-SOP5].
*   **Metrics:** Cost Per Conversation (CPC: ₹20–₹120), WhatsApp Open Rate ($\ge 90\%$) [PA-Benchmarks].
*   **Recovery:** If the chatbot fails to trigger, check Meta Webhook developer logs for validation errors or API payload mismatches and re-save ManyChat/YCloud routing keys [PA-SOP5].
*   **Agent Role:** Conversational Funnel Architect / Automations Specialist.
*   **Sources:** [PA-SOP5, MM-5.5, PA-Benchmarks].

### 5.5 SOP PA5: Web2App Subscription Funnel Architecture (Bypassing App Stores)
*   **Purpose:** To monetize mobile applications by routing users through an optimized mobile web quiz subscription funnel, bypassing 15–30% app store fees and enhancing attribution signals [PA-SOP6].
*   **Trigger:** Launching a mobile application campaign targeting scaling revenue without app store dependency [PA-SOP6].
*   **Inputs:** Mobile-optimized quiz platform access (FunnelFox, Typeform), payment gateway with card-retry/dunning capabilities [PA-SOP6].
*   **Prerequisites:** Server-side purchase tracking set up on checkout domain [PA-SOP6].
*   **Procedure:**
    1.  **Configure Onboarding Quiz:** Build a responsive onboarding quiz consisting of 20 to 40 steps that educate and prequalify the user [PA-SOP6].
    2.  **Implement Direct Checkout:** At the end of the quiz, display a personalized result screen paired with a direct card-payment subscription checkout [PA-SOP6].
    3.  **Integrate Payment Redundancy:** Deploy localized payment methods and advanced card-retry logic to handle up to 50% failed payment rates [PA-Benchmarks, PA-SOP6].
    4.  **Execute App Direct-Ramp:** Post-payment, display a high-contrast landing page with a single button: *"Download App & Access Your Plan"* containing a deep-linked token to auto-log them in [PA-SOP6].
*   **Decision Points:**
    *   **IF** quiz drop-off exceeds 50% at a specific question:
        *   **THEN** remove or simplify that step into a binary selection [PA-SOP6].
    *   **IF** card payment failure exceeds 50%:
        *   **THEN** implement instant alternative payment methods (APMs like dLocal, UPI, or regional wallets) [PA-Benchmarks].
*   **Output:** A high-converting web quiz landing page connected directly to a subscription checkout, bypassing app store control [PA-SOP6].
*   **DoD:** Integration verified: quiz completion leads to checkout, payment success redirects to a functional app-download deep-link [PA-SOP6].
*   **QA:** Test all checkout flows using active credit cards. Ensure no user is billed without legal compliance terms displayed [PA-SOP6].
*   **Metrics:** Quiz completion rate ($\ge 45\%$), Payment success rate, Trial-to-paid conversion rate.
*   **Recovery:** If web-to-app deep-linking fails, automatically email the user their custom secure login token within 60 seconds [PA-SOP6].
*   **Agent Role:** Growth Architect / Checkout Engineer.
*   **Sources:** [PA-SOP6, PA-Benchmarks].

### 5.6 SOP PA6: Daily Media Buyer Audit (The 4:00 AM Routine)
*   **Purpose:** To establish a disciplined, daily telemetry feedback loop to scale profitable campaigns and ruthlessly prune losing ad creatives based on real business revenue [MM-5.3].
*   **Trigger:** Daily recurrence at 4:00 AM local time [MM-5.3].
*   **Inputs:** Blended attribution dashboard access (Triple Whale, Triple L), Meta Ads Manager access [MM-5.3].
*   **Prerequisites:** High-fidelity conversion tracking active, historical break-even MER targets calculated [MM-5.3].
*   **Procedure:**
    1.  **Check Blended Metrics First:** Log into your multi-touch attribution dashboard to check true blended ad spend, net revenue, and Marketing Efficiency Ratio (MER) [MM-5.3]. **Do not rely on native Meta Ads Manager tracking, which underreports browser purchases post-iOS14** [MM-5.3].
    2.  **Optimize Campaign-Level Bidding:** If blended MER is highly profitable and outperforming break-even targets, increase the consolidated Advantage+ daily budget by **10% to 30%** [MM-5.3]. Never scale faster than 30% daily to avoid resetting the learning phase [MM-5.3].
    3.  **Apply Davies Columns View:** Open Meta Ads Manager. Activate the customized "Davies Columns" layout preset [MM-5.3].
    4.  **Perform Ad-Level Performance Triage:** Isolate creatives that have spent at least two times the product's Average Order Value (2x AOV) [MM-5.3]. If an asset is underperforming break-even targets, toggle it OFF [MM-5.3].
    5.  **Inject Creative Refresh:** Introduce **1 to 3 new creative assets** into the consolidated scaling campaign to prevent creative fatigue [MM-5.3].
    6.  **Construct Future testing pipeline:** Spend 30 minutes in competitive ad libraries (Trend Rocket, Facebook Ad Library) analyzing top-performing hooks [MM-5.3].
*   **Decision Points:**
    *   **IF** blended MER falls below break-even target:
        *   **THEN** pause underperforming ad creatives and reduce campaign daily budget by 15% [MM-5.3].
    *   **IF** an ad has spent > 2x AOV but has zero conversions:
        *   **THEN** turn it off immediately [MM-5.4].
*   **Output:** Scaled budgets, pruned underperforming creatives, and active testing pipeline queue updated in the team dashboard [MM-5.3].
*   **DoD:** Budget adjustments and creative changes executed in Meta Ads Manager. Telemetry logged into the daily reporting sheet.
*   **QA:** No budget adjustments exceed 30% in a single day to protect learning state stability [MM-5.3].
*   **Metrics:** Blended MER, Ad Spend, CPA, CPA Change %, Target Scaling Velocity.
*   **Recovery:** If a major campaign-level pause was executed in error, do not toggle the ad set back on. Duplicate the ad set to launch a clean learning phase [MM-5.3].
*   **Agent Role:** Senior Media Buyer Node.
*   **Sources:** [MM-5.3, MM-5.4].

### 5.7 SOP PA7: Technical Meta Account Security & Verification
*   **Purpose:** To build highly verified, bulletproof Meta advertising infrastructure, preventing automated account suspensions and protecting active digital assets [MM-5.10].
*   **Trigger:** Launching a brand's media presence or setting up a fresh Meta Business Manager account [MM-5.10].
*   **Inputs:** Business legal registration, admin personal Facebook accounts, domain access [MM-5.10].
*   **Prerequisites:** Legal business documentation matching physical addresses [MM-5.10].
*   **Procedure:**
    1.  **Verify Account Age:** Ensure the personal Facebook profile managing the Business Manager is at least 6 months old and has active, human history [MM-5.10].
    2.  **Match Legal Identity:** Input the Business Manager's legal name, address, and contact details to match corporate registration documents exactly [MM-5.10].
    3.  **Enforce Two-Factor Authentication:** Activate mandatory 2FA for all administrators and employees added to the Business Manager [MM-5.10].
    4.  **Configure Backup Administrator:** Add a trusted, secondary personal Facebook profile as an alternate administrator to prevent lockouts if the primary admin is flagged [MM-5.10].
    5.  **Warm the Facebook Page:** Publish 5 to 10 organic posts, update high-resolution imagery, and build basic page activity before launching paid ads [MM-5.10].
    6.  **Verify Website Domain:** Navigate to Brand Safety > Domains, add the storefront URL, copy the meta-tag, and paste it into the HTML `<head>` section of the shop template [MM-5.10].
    7.  **Integrate Server-Side API:** Connect the Pixel via server-side integrations to track customer events cleanly [MM-5.10].
*   **Decision Points:**
    *   **IF** Meta requests ID verification:
        *   **THEN** upload a high-resolution, uncropped photo of the passport/driver's license matching the personal profile name exactly [MM-5.10].
    *   **IF** a domain verification meta-tag is rejected:
        *   **THEN** switch to DNS TXT record verification, pasting the verification string into the domain's DNS zone file [MM-5.10].
*   **Output:** Fully verified, highly secure Meta Business Manager infrastructure active [MM-5.10].
*   **DoD:** Domain verified, Business Manager status showing "Verified," backup admins configured, and CAPI signals active [MM-5.10].
*   **QA:** No names or addresses in Meta settings are abbreviated or mismatched with legal documents [MM-5.10].
*   **Metrics:** Verification Rate (100%), Account Health Score, Setup Time.
*   **Recovery:** If an ad account is restricted, do not submit repeated appeals. Submit a single appeal attaching legal business registration and matching physical IDs [MM-5.10].
*   **Agent Role:** Infrastructure Engineer / GTM Lead.
*   **Sources:** [MM-5.10].

---

## 6. DOMAIN 4: CONTENT DOMAIN

### 6.1 SOP C1: Scriptwriting & Script Assembly (The 15/3 Constraint)
*   **Purpose:** To write highly hypnotic, clinical short-form scripts optimized for maximum comprehension, visual-auditory pacing, and retention, strictly adhering to physical reading limits [MC-5, MC-SOP2, PE-SOP5.2, CO-SOP2].
*   **Trigger:** Content planning phase or rapid-test ad concept execution [MC-SOP2, PE-SOP5.2].
*   **Inputs:** Validated outliers, Brand Brain document, target audience pain points [MC-SOP2, PE-SOP5.2].
*   **Prerequisites:** Target unique mechanism selected, banned vocabulary list open [AOS-5.3, MC-SOP2].
*   **Procedure:**
    1.  **Draft Spoken Hook (0:00 - 0:05):** Open immediately with a **Negative Frame** (Loss Aversion) targeting their "Bleeding Neck" pain [MC-SOP2, PE-SOP5.2]. Absolutely prohibit hand waves, name greetings, or introductory preambles [MC-1.1, MC-SOP2].
        *   *Example:* "Stop running ads to an ugly website. It is destroying your profit margins." [MC-SOP2].
    2.  **Agitate and Scapegoat (0:05 - 0:15):** Lower reader defensiveness (cortisol) and shift blame from the user to a systemic villain using "The Scapegoat Protocol" [MC-SOP2, PE-SOP5.2].
        *   *Example:* "It is not your fault your conversion is low. Traditional agencies built something pretty. They did not build a revenue machine." [MC-SOP2].
    3.  **Execute the Rehook (0:15 - 0:20):** Use a sharp contrast transition ("But," "Therefore") to reopen a new curiosity loop [MC-SOP2, PE-SOP5.2].
        *   *Example:* "But here is the crazy part. You do not need a redesign." [MC-SOP2].
    4.  **Introduce the Mechanism (0:20 - 0:40):** Introduce NEROZARB's proprietary named mechanism (Term Branding) as the only logical solution path [MC-SOP2, PE-SOP5.2].
        *   *Example:* "We install The Neural Moat. It locks out your competitors instantly." [MC-SOP2].
    5.  **Frictionless Outro & CTA (0:40 - 0:45):** Deliver a frictionless, non-hypnosis-breaking CTA pointing exclusively to a single WhatsApp or ManyChat direct-message link [MC-SOP2, PE-SOP5.2].
        *   *Example:* "Message us on WhatsApp. We will install it in 4 days." [MC-SOP2].
    6.  **Pre-flight Constraints Audit:** Execute the strict 15/3 writing constraints:
        *   Sentence word-count check: No sentence may exceed **15 words** [AOS-5.3, MC-SOP2, PE-SOP5.2]. Split longer sentences into two lines.
        *   Paragraph sentence check: No paragraph may exceed **3 sentences** [AOS-5.3, MC-SOP2, PE-SOP5.2].
*   **Decision Points:**
    *   **IF** any sentence exceeds 15 words:
        *   **THEN** force a split or remove unnecessary filler descriptors [AOS-5.3, MC-SOP2].
    *   **IF** a banned word is found (e.g., *delve, landscape, passionate, comprehensive, next-level, synergy, leverage, transformative*):
        *   **THEN** delete the word and rephrase with active, plain-language verbs [AOS-5.3, MC-SOP2].
*   **Output:** Complete, highly hypnotic direct-response short-form script ready for filming or actor briefing [MC-SOP2, PE-SOP5.2].
*   **DoD:** A scripted draft meeting all 15/3 constraint metrics, verified free of banned terms, and utilizing the 5-step Q.S.T.A. storytelling structure [AOS-5.3, MC-SOP2].
*   **QA:** No sentence exceeds 15 words. All transitions utilize "therefore" or "but" rather than "and then" to ensure logical cause-and-effect progression [MC-4, AOS-5.3].
*   **Metrics:** Average sentence length ($\le 12$ words), banned words (0), paragraph line-breaks (double space between all blocks) [AOS-5.3, MC-SOP2].
*   **Recovery:** If script reading feels choppy, verify F-Shaped anchor points (ensuring critical high-impact words are positioned in the first 2-3 words of every line) to guide visual scanning [AOS-5.3].
*   **Agent Role:** Lead Content Specialist / Scriptwriting Agent.
*   **Sources:** [MC-5.1, MC-SOP2, PE-SOP5.2, AOS-5.3, MC-4].

### 6.2 SOP C2: Script Structure Extraction & Templatization
*   **Purpose:** To extract the underlying structural formula of any viral competitor outlier and save it as a repeatable, clean variables-based template in the Script Bank [CO-SOP3].
*   **Trigger:** Isolate a 5x competitor outlier video featuring a clear educational flow in Sandcastles [CO-SOP3].
*   **Inputs:** Outlier video URL, transcript extraction tool access (e.g., gettranscribe.ai) [CO-SOP3].
*   **Prerequisites:** Claude 3.7 or ChatGPT access configured with the Structural Extraction Prompt [CO-SOP3].
*   **Procedure:**
    1.  **Extract Video Transcript:** Input the target outlier URL into a high-fidelity transcript extractor to pull raw, un-edited spoken text [CO-SOP3].
    2.  **Submit Transcript to LLM:** Paste the raw transcript into your LLM workspace with the Structural Extraction Prompt (see SOP PR2) [CO-SOP3].
    3.  **Generate Variables:** Instruct the model to replace specific niche details with blank variables (`[PROB]`, `[SCAPEGOAT]`, `[MECH]`, `[PROOF]`, `[CTA]`) [CO-SOP3].
    4.  **Isolate Visual/Spoken Triggers:** Map out the exact timing of the pattern breaks, visual B-rolls, and camera pans aligned to the spoken lines [CO-SOP3].
    5.  **Save to Script Bank:** Append the newly generated modular template to your team's centralized Script Bank sheet [CO-SOP3].
*   **Decision Points:**
    *   **IF** transcript contains unstructured, rambling speech:
        *   **THEN** run an initial cleanup pass instructing the LLM to preserve the raw conversational flow while stripping verbal ticks [CO-SOP3].
    *   **IF** the outlier structure is too complex for standard 5-step mapping:
        *   **THEN** fragment the video into 15-second sub-loops and template each sub-loop separately [CO-SOP3, MC-4].
*   **Output:** Repeatable, variables-based copywriting template logged in the team Script Bank [CO-SOP3].
*   **DoD:** Template formatted with clean markdown variables, timing markers, and visual cues, ready for execution on different products [CO-SOP3].
*   **QA:** Ensure zero residual brand or niche terms from the original video remain in the final template [CO-SOP3].
*   **Metrics:** Templates generated per outlier (1), formatting compliance (100%).
*   **Recovery:** If the extracted transcript lacks readability, manually dictate the video line-by-line while watching at 0.5x speed to capture exact phrasing [CO-SOP3].
*   **Agent Role:** Script Engineer / Systems Copywriter.
*   **Sources:** [CO-SOP3, MC-4].

### 6.3 SOP C3: The 60-Minute Monthly Content Batching Engine
*   **Purpose:** To plan, structure, and script a complete month of validated content (12–16 high-potential posts) in under 60 minutes, bypassing operational analysis paralysis [CO-SOP4].
*   **Trigger:** Monthly recurrence on the 25th of each month [CO-SOP4].
*   **Inputs:** Centralized Outlier sheets, Script Bank, ManyChat dashboard access [CO-SOP4].
*   **Prerequisites:** High-priority niche-validated keywords selected [CO-SOP4].
*   **Procedure:**
    1.  **Minutes 00–15: Research & Hook Stacking:**
        *   Open Sandcastles outlier sheets. Select 12 high-potential topics matching your 40/40/20 filter [CO-SOP4].
        *   Build a three-layer **Hook Stack** (Verbal hook, Written screen text, and Visual start frame) for each post by combining proven high-engagement hooks [CO-SOP4, CP-Anatomy1].
    2.  **Minutes 15–40: Scripting & Structuring Value:**
        *   Apply the pre-built Script Bank templates to your selected topics [CO-SOP4].
        *   Inject client case study results, raw data, or clinical facts to form the high-value substance of the video [CO-SOP4].
    3.  **Minutes 40–50: CTAs & ManyChat Setup:**
        *   Assign a specific Call-to-Action to each post based on its funnel tier (TOFU = Follow, MOFU = DM keyword for freebie, BOFU = DM keyword for audit) [CO-SOP4].
        *   Build trigger words inside ManyChat and test WhatsApp redirects [CO-SOP4].
    4.  **Minutes 50–60: Formatting & Editor Notes:**
        *   Select the visual format for each post (Talking Back & Forth, Clone, Whiteboard, or Cinematic B-Roll) [CO-SOP4].
        *   Add color-coded visual shot direction and SFX instructions for the video editor [CO-SOP4, CO-SOP5].
*   **Decision Points:**
    *   **IF** a selected topic fails to align with the 40/40/20 filter:
        *   **THEN** reject the topic and replace it with a proven outlier concept from the Script Bank [CO-SOP4].
    *   **IF** the scripting phase exceeds 25 minutes:
        *   **THEN** use pre-verified Claude prompt structures to write drafts under direct human supervision [CO-SOP1].
*   **Output:** Unified batch document containing 12–16 fully formatted scripts and automated DM triggers [CO-SOP4].
*   **DoD:** 12–16 scripts formatted using the three-bullet visual hierarchy, complete with ManyChat keywords and CTA definitions [CO-SOP4, CO-SOP5].
*   **QA:** Confirm every script in the batch has undergone the pre-flight 15/3 constraint audit [CO-SOP2, AOS-5.3].
*   **Metrics:** Time to complete (60 minutes), completed script count ($\ge 12$).
*   **Recovery:** If ManyChat automation fails, manually assign a VA to dispatch direct copy-pasted audit links to commenters within 10 minutes of post [MM-5.5].
*   **Agent Role:** Creative Director Node / Content Batcher.
*   **Sources:** [CO-SOP4, CO-SOP5, CO-SOP1, MM-5.5].

### 6.4 SOP C4: Visual Script Organization & Shooting Protocol
*   **Purpose:** To format scripts into a standardized, color-coded visual-bullet hierarchy to streamline filming and eliminate confusion during post-production handoff [CO-SOP5].
*   **Trigger:** Final script batch approved and ready for production filming [CO-SOP5].
*   **Inputs:** Raw batch scripts, video editor template access, target file directory links [CO-SOP5].
*   **Prerequisites:** High-quality smartphone or camera setup, professional lapel/shotgun mic calibrated [CO-SOP5].
*   **Procedure:**
    1.  **Format Script into Three-Bullet Hierarchy:** Restructure every sentence block into three distinct color-coded bullets [CO-SOP5]:
        *   **Black Bullet (●):** Spoken verbal script line [CO-SOP5].
        *   **Red Bullet (●):** Specific physical action to perform, camera angle, or location change [CO-SOP5].
        *   **Green Bullet (●):** Specific instructions for the editor (e.g., overlay screenshots, add PNG diagrams, sound effect cues) [CO-SOP5].
    2.  **Calibrate Equipment:** Set up tripod, check direct audio levels, and ensure lighting casts zero harsh shadows on the speaker's face [CO-SOP5, MM-5.12].
    3.  **Filming Execution:** Read and record **one bullet block at a time** [CO-SOP5]. Pause, look down at the script, reset your facial posture, look back at the camera, and speak the next spoken line [CO-SOP5].
    4.  **Run Camera Continuously:** Keep the camera rolling throughout the session [CO-SOP5]. Your editor will cut out all pauses, resets, and physical resets [CO-SOP5, MM-5.12].
    5.  **Organize Output Files:** Create structured folders immediately: `Batch_Name -> Video_ID_Topic -> Raw Clips + Script PDF` [CO-SOP5].
*   **Decision Points:**
    *   **IF** audio recording exhibits background noise (AC humming, wind):
        *   **THEN** stop recording and activate noise isolation or relocate to a carpeted, insulated room [CO-SOP5, VI-SOP8].
    *   **IF** visual lighting changes drastically mid-session:
        *   **THEN** lock the camera ISO and white balance settings to manual before resuming [VI-SOP8].
*   **Output:** Organized directory containing raw high-fidelity MP4 footage and formatted script files ready for the editor [CO-SOP5].
*   **DoD:** Every video folder populated with raw footage, complete three-bullet formatted scripts, and visual overlay PNG assets [CO-SOP5].
*   **QA:** Spoken verbal lines must match the script text exactly. Audio levels must peak between -6dB and -12dB [CO-SOP5, VI-SOP8].
*   **Metrics:** Filming efficiency (target < 5 mins per video), editing handoff success (100%).
*   **Recovery:** If a clip is missing editor overlay instructions, halt the editor's progress and update the green bullets in the master script file before resuming [CO-SOP5].
*   **Agent Role:** Actor/Creator Node & Production Engineer.
*   **Sources:** [CO-SOP5, MM-5.12, VI-SOP8].

---

## 7. DOMAIN 5: COPYWRITING DOMAIN

### 7.1 SOP CP1: In-Vivo Review Mining & Client Language Extraction
*   **Purpose:** To extract the un-edited voice of the customer (IVOC) to build a robust, pain-point-driven vocabulary list that connects directly to the buyer's amygdala [MC-5, CP-SOP1, PS-SOP3].
*   **Trigger:** Onboarding a new brand or entering a fresh copywriting cycle [CP-SOP1].
*   **Inputs:** Complete raw reviews dataset, competitor brand profiles, Claude Sonnet access [CP-SOP1, PS-SOP3].
*   **Prerequisites:** Brand target audience demographics identified [CP-SOP1].
*   **Procedure:**
    1.  **Extract Storefront Reviews:** Export all customer reviews from Shopify, Okendo, or Yotpo storefronts [CP-SOP1].
    2.  **Initialize Review Analysis Project:** Import the CSV reviews dataset into a clean Claude Project [CP-SOP1].
    3.  **Run In-Vivo Mining:** Execute the *Reviews to Golden Nugget* prompt (see SOP PR1) [CP-SOP1]. Instruct the model to extract verbatim customer expressions of pain, failed competitor attempts, and raw, emotionally charged phrases [CP-SOP1].
    4.  **Perform Reddit Listening Check:** Verify extracted vocabularies on Reddit. Note conversational idioms used in active discussions [CP-SOP1].
    5.  **Assemble the Objection Matrix:** Structure complaints into a 3-column objection matrix: `[Raw Frustration] -> [Failed Solution] -> [Verbatim Vocabulary]` [CP-SOP1].
    6.  **Create the Brand Brain Document:** Save the objection matrix and extracted verbatim customer language as a markdown file in `/workspace/scratch/` to serve as the copywriting foundation [CP-SOP1].
*   **Decision Points:**
    *   **IF** raw customer language contains highly specific physical complaints (e.g., "makes my eyes water"):
        *   **THEN** lead with that specific somatic reaction in your next hook [CP-SOP1, MM-6.2].
    *   **IF** competitor reviews focus on customer service failures:
        *   **THEN** build a "Service Integrity" script block contrasting your operations with the industry [CP-SOP1].
*   **Output:** Complete "Brand Brain" file housing un-edited customer vocabulary and objection matrices [CP-SOP1].
*   **DoD:** Structured objection matrix completed and verified. A list of 15 visceral, non-marketing vocabularies saved to the project [CP-SOP1].
*   **QA:** No corporate marketing buzzwords (such as "innovative", "comprehensive") are allowed in the Brand Brain document [CP-SOP3]. All phrases must be direct, raw customer verbatims [CP-SOP1].
*   **Metrics:** Total review volume analyzed ($\ge 100$), extracted visceral phrases count ($\ge 15$).
*   **Recovery:** If reviews contain insufficient qualitative text, run a YouTube video review transcript scrape for the top 3 competitor products to gather raw spoken customer comments [CP-SOP1].
*   **Agent Role:** Copywriter Node / Customer Psychology Expert.
*   **Sources:** [CP-SOP1, PS-SOP3, MM-6.2, CP-SOP3].

### 7.2 SOP CP2: Direct-Response Scriptwriting & Modular Briefing
*   **Purpose:** To write modular direct-response ad scripts and structured briefing packages for creators, allowing for post-production hook swapping and ad-slice optimizations [MM-5.2].
*   **Trigger:** Paid ad campaign ideation cycle or new creative concept launch [MM-5.2].
*   **Inputs:** Brand Brain document, validated outliers, creator roster profiles [MM-5.2].
*   **Prerequisites:** High-status copywriting tone guidelines open [AOS-5.3].
*   **Procedure:**
    1.  **Draft Modular Hooks (Module A):** Write exactly 5 distinct spoken hook variations (< 15 words each) focusing on loss aversion or pattern interruption [MM-5.2].
    2.  **Draft Modular Body (Module B):** Write a single core video body explaining the unique mechanism (Term Branding) and displaying proof [MM-5.2].
    3.  **Draft Modular Outro (Module C):** Write 2 distinct Call-to-Action variations pointing to a single conversion action [MM-5.2].
    4.  **Format the Creator Brief:** Assemble a vertical safe-zone template outlining exact visual action directions alongside the spoken script [MM-5.2, VI-SOP3].
    5.  **Insert Visual Examples:** Include visual reference links or B-roll ideas to guide the creator's pacing and lighting [MM-5.2].
*   **Decision Points:**
    *   **IF** a creator's reading style sounds overly promotional or rehearsed:
        *   **THEN** reject the assets and send back with instructions to read as a FaceTime call to a friend [VI-SOP3].
    *   **IF** the hook rate drops below target:
        *   **THEN** deploy a visual-shock pattern break in the first 1.5 seconds [MM-5.12].
*   **Output:** Standardized, modular direct-response creator brief package saved to the drive [MM-5.2].
*   **DoD:** Standard briefing document completed with 5 hooks, 1 body, 2 CTAs, safe-zone definitions, and visual asset references [MM-5.2, VI-SOP3].
*   **QA:** Verify that every sentence in the brief meets the strict 15-word maximum limit [AOS-5.3].
*   **Metrics:** Completed briefs (1 per campaign angle), hook variations written ($\ge 5$).
*   **Recovery:** If the creator struggle to film vertical safe-zone compliant footage, supply them with a transparent PNG overlay to place over their smartphone screen while recording [VI-SOP3].
*   **Agent Role:** Performance Copywriter Node.
*   **Sources:** [MM-5.2, AOS-5.3, MM-5.12, VI-SOP3].

### 7.3 SOP CP3: Hook Refurbishing (Creative Lifecycle Extension)
*   **Purpose:** To revitalize high-performing scaling ad creatives experiencing performance drops (creative fatigue) by replacing only the hook, saving extensive production budgets [MM-5.9, AC-SOP5, CP-SOP4, PA-SOP7].
*   **Trigger:** Ad creative frequency rises above 2.0 within 30 days, or ROAS falls below break-even targets [MM-6.3, PA-Decision3].
*   **Inputs:** Winning video ad post-ID, 3–5 fresh hook ideas, CapCut/Premiere access [AC-SOP5].
*   **Prerequisites:** Original raw footage of the winning ad body and outro isolated [AC-SOP5].
*   **Procedure:**
    1.  **Identify Fatigue:** Check Ads Manager telemetry to isolate scaling ad units with falling click-through rates and high frequency metrics [AC-SOP5].
    2.  **Isolate Body & Outro:** Keep the original video body (Module B) and CTA (Module C) completely untouched [AC-SOP5].
    3.  **Script 3–5 New Hooks:** Write 3 to 5 new hooks based on current high-potential formats (e.g., green screen reaction, TikTok comment bubble response, Snapchat filter hook) [AC-SOP5].
    4.  **Film and Edit Swaps:** Record the new hook lines and stitch them onto the front of the original video body using editing software [AC-SOP5].
    5.  **Sandbox Test:** Deploy the new refurbished ad variations into the Stage 1 ABO testing sandbox to reset Meta's similarity score and capture fresh distribution [AC-SOP5, AC-SOP7].
*   **Decision Points:**
    *   **IF** a refurbished variation outperforms the original baseline ROAS in testing:
        *   **THEN** graduate the new variation directly into the consolidated scaling campaign [AC-SOP5, AC-SOP7].
    *   **IF** all 5 refurbished variations fail to convert:
        *   **THEN** pause the concept and initiate a deep research cycle to uncover a fresh positioning angle [AC-SOP7, MM-5.1].
*   **Output:** Refurbished ad variations ready for deployment, resetting creative similarity profiles [AC-SOP5].
*   **DoD:** 3–5 new hook-stitched ad creatives launched in the ABO testing campaign [AC-SOP5, AC-SOP7].
*   **QA:** Ensure visual transitions between the new hooks and the old video body are seamless with matching color grading and audio loudness levels [AC-SOP5].
*   **Metrics:** Cost Per Purchase, CTR Lift ($\ge 20\%$), Hook Rate Lift ($\ge 25\%$) [PA-Formulas].
*   **Recovery:** If the audio transitions sound disjointed, apply a 2-frame constant power crossfade and normalize the entire video's audio track to -14 LUFS [VI-SOP8].
*   **Agent Role:** Video Editor / Media Buyer Node.
*   **Sources:** [AC-SOP5, AC-SOP7, MM-5.9, MM-6.3, PA-Decision3, VI-SOP8].

### 7.4 SOP CP4: Generative Engine Optimization (GEO) Content Structuring
*   **Purpose:** To format, structure, and optimize all digital assets and web copy to ensure AI Answer Engines (Perplexity, SearchGPT, Gemini, Google AI Overviews) extract and cite your brand as the primary authority [AOS-5.4, CP-SOP5, CO-SOP6].
*   **Trigger:** Creating new informational blog posts, landing pages, or product pages [CP-SOP5, CO-SOP6].
*   **Inputs:** Web content draft, JSON-LD Schema templates, llms.txt template [CP-SOP5, CO-SOP6].
*   **Prerequisites:** Root domain administrative access configured [AOS-5.4, CP-SOP5].
*   **Procedure:**
    1.  **Front-Load the Answer Block:** Ensure the first 50–70 words of any informational page contain a direct answer block satisfying the target query [AOS-5.4, CP-SOP5].
    2.  **Apply Definition Syntax:** Format definitions using the exact structure: **[Entity] is a [Category] that [Function]** [AOS-5.4, CP-SOP5].
    3.  **Serialize Data in HTML Tables:** Convert all comparative arguments, pricing matrices, and feature lists into clean, server-side rendered HTML tables [AOS-5.4, CP-SOP5].
    4.  **Inject Schema 2.0:** Implement rich JSON-LD Schema (including Speakable, FactCheck, and Dataset markup) on your root domain [AOS-5.4, CP-SOP5].
    5.  **Deploy llms.txt File:** Serve a clean, markdown-based directory file at `yourdomain.com/llms.txt` for bot navigation [AOS-5.4, CP-SOP5].
*   **Decision Points:**
    *   **IF** page content is highly complex or narrative-driven:
        *   **THEN** append a 3-bullet "Executive Summary" table at the top of the page [CP-SOP5].
    *   **IF** a page contains comparative products:
        *   **THEN** build a comprehensive feature-comparison table with your brand highlighted in the first column [CP-SOP5].
*   **Output:** GEO-structured webpage containing schema markup and LLM-readable text files live on domain [AOS-5.4, CP-SOP5].
*   **DoD:** Page contains an inverted-pyramid answer block in the first 70 words, data serialized in HTML tables, JSON-LD schema injected, and root /llms.txt file active [AOS-5.4, CP-SOP5].
*   **QA:** Test the URL using the Rich Results Test tool to confirm Schema validity. Verify `llms.txt` renders as raw text [CP-SOP5].
*   **Metrics:** AI Search Engine Citation Share %, Organic Search Clicks, Brand Awareness Lift [MM-4].
*   **Recovery:** If Google Search Console flags invalid schema, audit the JSON-LD formatting for trailing comma errors or unclosed brackets and patch immediately [AOS-5.4].
*   **Agent Role:** Technical SEO Specialist / Copywriter Agent.
*   **Sources:** [AOS-5.4, CP-SOP5, CO-SOP6, MM-4].

---

## 8. DOMAIN 6: SALES DOMAIN

### 8.1 SOP S1: Discovery Call Frame & Flow
*   **Purpose:** To systematically qualify prospective B2B clients, establish professional boundaries and peer authority, map organizational triggers, and secure a fit/no-fit decision without traditional sales pitching [OUT-11.3, SA-4].
*   **Trigger:** A qualified prospect schedules a calendar slot from outreach or inbound ManyChat funnels [OUT-11.3].
*   **Inputs:** Lead Research Brief, active client acquisition data, target company website [OUT-11.3].
*   **Prerequisites:** Prospect's CRM record populated and reviewed [OUT-11.3, OUT-11.5].
*   **Procedure:**
    1.  **Pre-Call Preparation:** Read the linked Lead Research Brief in the CRM [OUT-11.3]. Note their visible acquisition channels and active pixels [OUT-11.1].
    2.  **Up-Front Contract (Sandler UFC):** Establish equal-peer authority in the first 3 minutes of the call [OUT-11.3]. Secure a mutual contract that a firm "yes" or "no" decision will be made at the end of the call [OUT-11.3].
        *   *Phases:* Context -> Time -> Agenda -> Prospect's Goal -> Your Goal -> fit/no-fit decision moment [OUT-11.3].
    3.  **Current State Audit:** Map current customer acquisition channels, conversion rates, and exact organizational ownership [OUT-11.3].
    4.  **Problem Implication (Cost of Inaction - COI):** Guide the prospect using targeted questions to calculate the exact financial cost of their current bottlenecks [OUT-11.3].
    5.  **Need-Payoff State:** Guide the prospect to articulate the financial and operational impact of solving their core bottleneck [OUT-11.3].
    6.  **Decision Engineering:** Map active decision-makers, stakeholders, procurement cycles, budgets, and timeline criteria [OUT-11.3].
    7.  **Resolution Contract:** Conclude the call with a firm decision to proceed to proposal or disqualify the lead [OUT-11.3].
*   **Decision Points:**
    *   **IF** the prospect resists the Sandler UFC (unwillingness to commit to a decision moment):
        *   **THEN** pause and explain that we cap our client intake to maintain high quality, and we only partner with active decision-makers [MC-2.3, OUT-11.3].
    *   **IF** the prospect is a fit and is ready to proceed:
        *   **THEN** book the "Systems Demonstration" session within 48 hours [OUT-11.3].
*   **Output:** Completed discovery call diagnostic record synced to the CRM [OUT-11.3, OUT-11.5].
*   **DoD:** Discovery call completed with UFC established, COI quantified in cash terms, decision engineering mapped, and follow-up proposal date booked [OUT-11.3].
*   **QA:** No agency pitches or slide presentations allowed during the discovery call. The conversation must remain strictly diagnostic [MC-2.3, OUT-11.3].
*   **Metrics:** UFC Agreement Rate (100%), Qualified Handoff Rate ($\ge 35\%$).
*   **Recovery:** If the prospect fails to show up for the call, send a brief email within 10 minutes: *"We missed you on our call. Since we keep our onboarding slots highly capped, please reply to let us know if we should release your slot to the next company."* [MC-2.3, OUT-11.3].
*   **Agent Role:** Senior Sales Executive / Account Executive.
*   **Sources:** [MC-2.3, OUT-11.3, OUT-11.5, SA-4].

### 8.2 SOP S2: Post-Close Client Reinforcement (First 48 Hours)
*   **Purpose:** To proactively neutralize buyer's remorse, prevent credit card chargebacks or invoice cancellations, and establish long-term client retention during the critical post-purchase window [OUT-11.4].
*   **Trigger:** Client signs contract and submits initial setup payment [OUT-11.4].
*   **Inputs:** Signed contract details, paid invoice records, client onboarding documents [OUT-11.4].
*   **Prerequisites:** Project management space configured [OUT-11.4].
*   **Procedure:**
    1.  **Validate the Decision:** Immediately post-payment, send a personalized congratulatory message validating their leadership in making a systems-level change [OUT-11.4].
    2.  **Deliver Onboarding Roadmap:** Within **24 hours**, email the client a clear, structured roadmap for their first 30 days, demonstrating near-zero client effort and detailing what assets your team is deploying [OUT-11.4].
    3.  **Establish Slack Hub:** Launch a designated Slack channel between the agency team and client stakeholders [OUT-11.4].
    4.  **Inject Value Feed:** Connect automated sales notifications or target industry trend scraping feeds to this channel to demonstrate immediate daily value-add within the first week [OUT-11.4].
*   **Decision Points:**
    *   **IF** client onboarding documents are delayed beyond 24 hours:
        *   **THEN** send a friendly Slack ping offering a 10-minute Loom walk-through to complete the setup [OUT-11.4].
    *   **IF** the client expresses confusion about responsibilities:
        *   **THEN** immediately schedule a 15-minute alignment call to reinforce the zero-effort onboarding commitment [OUT-11.4].
*   **Output:** Active Slack onboarding space, clear 30-day roadmap delivered, and onboarding metrics logged in the CRM [OUT-11.4].
*   **DoD:** Welcome email sent, Slack workspace established, and first onboarding milestone marked as complete within 48 hours [OUT-11.4].
*   **QA:** The roadmap document must contain zero speculative dates. All milestones must map to pre-approved resources.
*   **Metrics:** Onboarding completion time (target < 48 hours), Client Satisfaction score.
*   **Recovery:** If a client initiates a refund dispute, halt active production immediately and schedule a direct partner-led escalation call to resolve misalignment [OUT-11.4].
*   **Agent Role:** Customer Success Lead / Account Manager.
*   **Sources:** [OUT-11.4].

### 8.3 SOP S3: CRM Data Entry & Source Provenance Logging
*   **Purpose:** To ensure rigorous, standardized tracking of all outbound and inbound leads, logging precise source provenance, trigger events, and diagnostic pain mapping to optimize sales pipelines [OUT-11.5].
*   **Trigger:** Any outreach reply, email interaction, or discovery call concludes [OUT-11.5].
*   **Inputs:** Call transcripts, email replies, researcher briefs, active CRM portals [OUT-11.5].
*   **Prerequisites:** Account executive access authorized in HubSpot/Notion CRM [OUT-11.5].
*   **Procedure:**
    1.  **Log Source Provenance:** Record the original acquisition channel, targeting campaign ID, and scraper trigger cohort [OUT-11.5].
    2.  **Update Opportunity Status:** Transition the prospect's pipeline stage based on the latest interaction (e.g., Lead -> Contacted -> Qualified -> Proposal) [OUT-11.5].
    3.  **Log Verifiable Evidence:** Input specific corporate trigger events and verifiable public facts (such as hiring patterns or ad pixels detected) [OUT-11.5].
    4.  **Map Operational Pain:** Record the diagnosed bottleneck, cash-quantified cost of inaction, and desired client outcome [OUT-11.5].
    5.  **Log Objections & Constraints:** Note all raised objections, financial parameters, and procurement constraints [OUT-11.5].
    6.  **Schedule Next Action:** Input the next step, assign an owner, and select a hard due date in the CRM [OUT-11.5].
    7.  **Input Confidence Score:** Record data entry date and assign a subjective confidence score to the lead [OUT-11.5].
*   **Decision Points:**
    *   **IF** a lead exhibits high-priority triggers (e.g., hiring a CMO):
        *   **THEN** tag the lead record as "Vanguard Opportunity" to escalate follow-up velocity [OUT-11.5, OUT-11.1].
    *   **IF** critical pain data is missing from the record:
        *   **THEN** set the task "Pain Discovery Follow-up" and do not graduate the lead to the proposal stage [OUT-11.5].
*   **Output:** standardized, fully populated lead record active in CRM [OUT-11.5].
*   **DoD:** CRM record updated with provenance, pain mapping, trigger events, next scheduled step, and owner within 2 hours of interaction [OUT-11.5].
*   **QA:** No free-text fields should be left ambiguous. Ensure every objection is categorized using dropdown matrices.
*   **Metrics:** CRM compliance rate (100%), Time to log after call (target < 120 minutes) [OUT-11.5].
*   **Recovery:** If data entry is missed, run a weekly audit script to flag un-updated lead records and assign them back to the respective owner [OUT-11.5].
*   **Agent Role:** Sales Operations Lead / Account Executive.
*   **Sources:** [OUT-11.5, OUT-11.1, OUT-11.3].

---

## 9. DOMAIN 7: OUTREACH / OUTBOUND DOMAIN

### 9.1 SOP O1: Lead Research & Prospecting
*   **Purpose:** To systematically verify prospects, identify active corporate triggers, map visible digital bottlenecks, and write hyper-personalized outreach copy without generic flattery [OUT-11.1, SA-4.2].
*   **Trigger:** A high-status target account enters the prospecting queue [OUT-11.1].
*   **Inputs:** Prospect account name, LinkedIn URL, corporate website, ICP criteria [OUT-11.1].
*   **Prerequisites:** Clean database of corporate targets from the sifting pipeline [AOS-5.1, OUT-11.1].
*   **Procedure:**
    1.  **Verify Decision-Maker Role:** Ensure the target contact is an active decision-maker (Founder, CMO, Head of Growth) with verified spending authority [OUT-11.1].
    2.  **Audit Corporate Trigger Events:** Parse company socials, job boards, and PR wires to locate a recent public trigger (e.g., hiring shifts, channel saturation, product launches, or funding rounds) [OUT-11.1].
    3.  **Map Acquisition Channels:** Audit visible channels (e.g., active Facebook/TikTok ad pixels, SEO rank, or content style) [OUT-11.1].
    4.  **Formulate Bottleneck Hypotheses:** Map out exactly where they are leaving money on the table (e.g., ad pixel firing but weak checkout dunning logic) and formulate one objective alternative hypothesis to maintain diagnostic integrity [OUT-11.1].
    5.  **Draft Contextual Personalization:** Write a personalized outreach brief utilizing Level 3–5 personalization, avoiding superficial flattery [OUT-11.1]. Focus on active triggers rather than personal hobbies [OUT-11.1].
    6.  **Log Evidence:** Record all evidence, confidence scores, and privacy boundaries into the CRM before dispatching outbound messages [OUT-11.1].
*   **Decision Points:**
    *   **IF** the prospect's company shows zero active ad pixels or digital presence:
        *   **THEN** tag as "Low-Sophistication / Cold" and route to the educational content funnel [OUT-11.1].
    *   **IF** contact email is unverified:
        *   **THEN** use Zerobounce to verify and execute a manual LinkedIn search to locate secondary contacts [OUT-11.2].
*   **Output:** evidence-backed Research Brief linked to the CRM account record [OUT-11.1].
*   **DoD:** Prospect verified, trigger event identified, bottleneck hypothesis mapped, and personalized brief logged in CRM [OUT-11.1].
*   **QA:** No generic flattery (e.g., "Loved your recent post!"). All personalizations must reference concrete business data or triggers [OUT-11.1].
*   **Metrics:** Lead qualification rate ($\ge 85\%$), personalization depth level (target $\ge 3$).
*   **Recovery:** If the primary decision-maker is unresponsive on LinkedIn, shift the outreach vector to a corporate email address using a highly specific subject line targeting their trigger event [OUT-11.2].
*   **Agent Role:** Lead Researcher Agent.
*   **Sources:** [OUT-11.1, OUT-11.2, AOS-5.1].

### 9.2 SOP O2: Cold Email Infrastructure Deployment & Volume Ramp
*   **Purpose:** To deploy, warm, and maintain a highly secure B2B cold email outreach infrastructure, configuring domain authenticity and inbox volume caps to protect deliverability and avoid spam folders [OUT-11.2, OUT-6].
*   **Trigger:** Launching a fresh outbound campaign, or when existing domain deliverability drops below 95% [OUT-11.2].
*   **Inputs:** Domain registrar access, GSuite/Office365 credentials, MX Toolbox access [OUT-11.2].
*   **Prerequisites:** Primary domain identified and secured from cold sending [OUT-11.2].
*   **Procedure:**
    1.  **Procure Secondary Domains:** Purchase secondary domains via a reputable registrar (e.g., if primary is `nerozarb.com`, purchase `getnerozarb.com`, `meetnerozarb.com`, `heynerozarb.com`) [OUT-11.2].
    2.  **Authenticate DNS Records:**
        *   Configure MX records pointing to Google Workspace or Office365 [OUT-11.2].
        *   Configure SPF TXT record: `v=spf1 include:_spf.google.com ~all` [OUT-11.2].
        *   Generate a 2048-bit key in email admin and publish as a DKIM TXT record [OUT-11.2].
        *   Configure DMARC TXT record: `v=DMARC1; p=quarantine; pct=100; rua=mailto:dmarc-reports@yourdomain.com` [OUT-11.2].
        *   Verify record status using MX Toolbox [OUT-11.2].
    3.  **Provision Inbox Settings:** Provision exactly **2 to 3 mailboxes per domain** [OUT-11.2]. Upload a high-contrast personal photo and set up a clean, link-free text signature [OUT-11.2].
    4.  **Configure Custom Tracking Domain:** Add CNAME record `inst` pointing to your email sequencer tracking host [OUT-11.2].
    5.  **Initialize Domain Warming:** Connect inboxes to an automated warming tool (e.g., instantly.ai) for exactly **14 to 21 days** to build domain sender reputation [OUT-11.2].
    6.  **Volume Ramp Protocol:** Post-warming, initiate cold sends at **5 emails/day/mailbox**, ramping up by 5 emails/day weekly until capping at a strict maximum of **30 emails/day/mailbox** [OUT-11.2].
*   **Decision Points:**
    *   **IF** open rates fall below 40% on an active outbound domain:
        *   **THEN** pause sending on that domain immediately, reconnect to warming tools for 14 days, and review copy for spam trigger words [OUT-11.2].
    *   **IF** bounce rate rises above 3%:
        *   **THEN** pause sending and run the email list through NeverBounce to purge inactive addresses [OUT-11.2].
*   **Output:** Highly optimized cold sending infrastructure live and delivering [OUT-11.2].
*   **DoD:** Secondary domains purchased, SPF/DKIM/DMARC active, mailboxes warmed for 14 days, and daily sending caps locked at 30 messages/inbox [OUT-11.2].
*   **QA:** No links or attachments allowed in cold emails. Signature must be strictly plain text.
*   **Metrics:** Open Rate ($\ge 55\%$), Reply Rate ($\ge 10\%$), Bounce Rate ($< 2.5\%$), Deliverability Rate ($\ge 98\%$) [OUT-11.2].
*   **Recovery:** If an outbound domain is permanently blacklisted, purchase a replacement domain immediately and initiate the 14-day warming protocol [OUT-11.2].
*   **Agent Role:** GTM Infrastructure Engineer.
*   **Sources:** [OUT-11.2].

### 9.3 SOP O3: Outbound Trojan Horse Outreach SOP
*   **Purpose:** To build partnerships and book high-ticket clients with an unselfish, high-reciprocity pipeline by sending personalized, high-value visual audits and pre-written copy assets [MM-5.7].
*   **Trigger:** Sales pipeline capacity falls below target goals, or target account enters the high-priority queue [MM-5.7].
*   **Inputs:** Ideal prospect target list, screen-recording tools, Loom, Google Sheets access [MM-5.7].
*   **Prerequisites:** Brand target objectives mapped and reviewed [MM-5.7].
*   **Procedure:**
    1.  **Dream 100 Curation:** Build a curated spreadsheet containing **100 ideal founders, CEOs, or target companies** you want to partner with [MM-5.7].
    2.  **Record Personalized Loom Audit:** Record a highly-personalized 10-minute video outlining exactly where they are leaving money on the table (the "gap" or "leaks" in their acquisition funnel) [MM-5.7, OUT-11.1]. Do not offer fluff or superficial flattery; deliver a clinical diagnosis [MM-5.7].
    3.  **Draft Bespoke Writing Assets:** Write **5 free high-converting social media posts** in their unique tone based on their podcast, blog, or website copy [MM-5.7].
    4.  **Execute Outbound Delivery:** Send the pre-written posts and Loom link with zero friction, zero sales pitches, and zero financial asks [MM-5.7].
    5.  **Reciprocity Follow-Up:** If they do not reply within 24 hours, send a low-friction follow-up: *"I have the content ready to send, just need your permission."* [MM-5.7].
*   **Decision Points:**
    *   **IF** prospect replies with positive feedback but asks about costs:
        *   **THEN** direct them to schedule a Systems Demonstration, keeping your high-status posture intact [OUT-11.3].
    *   **IF** the prospect remains unresponsive after 2 follow-ups:
        *   **THEN** archive the account and replace it in your Dream 100 list with a fresh prospect [MM-5.7].
*   **Output:** personalized outreach assets dispatched, initiating high-reciprocity dialogues [MM-5.7].
*   **DoD:** Custom Loom recorded, 5 custom copy posts drafted, and initial outreach message sent to target decision-maker [MM-5.7].
*   **QA:** No sales pitches or pricing mentioned in the initial Loom video or message copy. Loom must be under 10 minutes [MM-5.7].
*   **Metrics:** Loom View Rate ($\ge 65\%$), Outbound response rate ($\ge 25\%$), Booking conversion rate.
*   **Recovery:** If the Loom video goes un-watched for 48 hours, upload a GIF preview of the audit directly in their DM to entice visual curiosity and trigger the view [MM-5.7].
*   **Agent Role:** Outreach Specialist / Copywriter Agent.
*   **Sources:** [MM-5.7, OUT-11.1, OUT-11.3].

---

## 10. DOMAIN 8: IMAGE, VIDEO & VISUAL PRODUCTION DOMAIN

### 10.1 SOP VP1: Character & Product Asset Locking (Flow AI / Whisk)
*   **Purpose:** To achieve complete cross-shot consistency, lock product geometries, and prevent facial/skin or packaging drift across generated visual assets [VI-SOP1, AC-SOP1, AI-SOP1].
*   **Trigger:** Launching a video/image asset creation sprint requiring consistent characters or a specific physical product (SKU) [VI-SOP1].
*   **Inputs:** High-quality master images of the character or unbranded product, vector logos [VI-SOP1].
*   **Prerequisites:** High-contrast, neutral-colored background on base assets [VI-SOP1].
*   **Procedure:**
    1.  **Initialize Base Image on solid gray background:** Avoid white seamless backdrops [VI-SOP1, IM-SOP1]. High-exposure white seamless backdrops blow out jaw and skin edges, cause light-bleed, and yield a flat, plasticky, "pasted-on" look [VI-SOP1, IM-SOP1]. Always generate base references on a neutral, solid gray backdrop to keep lighting values clean and prevent edge shine [VI-SOP1, IM-SOP1].
    2.  **Compile Multi-Angle Reference Sheet:** In the Characters tab, utilize the multi-angle template to generate front (0°), three-quarter (45°), side profile (90°), and rear (180°) views of the subject [VI-SOP1, IM-SOP1]. (Flow permits a maximum of exactly two reference images per character: the main reference and the multi-angle sheet) [VI-SOP1, IM-SOP1].
    3.  **Lock Voice/Audio Profile:** Choose from Flow's voice library or record a custom visual/audio avatar via the mobile app [VI-SOP1]. Save the asset package under a unique name (e.g., `@OrlandoHugh` or `@SoapBaseBar`) [VI-SOP1, IM-SOP1].
    4.  **Execute Product Silhouette & Logo Locking:**
        *   Generate the unbranded, naked product silhouette using the *Product-as-Sculpture* strategy [VI-SOP1]. Save as `@SoapBaseBar` [VI-SOP1].
        *   Open Flow's edit interface and upload your master vector logo [VI-SOP1].
        *   Use the **Box Selection Tool** or **Lasso Tool** to draw directly over the exact target center face of the product [VI-SOP1].
        *   Apply the operational command: *"Follow edit instructions on annotations: Emboss the uploaded vector graphic directly into the center surface of @SoapBaseBar with a 2.5mm downward depth deformation, preserving all surrounding wet-satin matte textures. Lock this complete composite asset as @ProductVariantBase."* [VI-SOP1, IM-SOP1].
*   **Decision Points:**
    *   **IF** the logo emboss exhibits bleeding edges:
        *   **THEN** increase the vector graphic's stroke weight and re-upload [VI-SOP1].
    *   **IF** the character's skin texture appears overly smooth (AI look):
        *   **THEN** force micro-pore details in the prompt (see SOP VP3) [IM-SOP3].
*   **Output:** Locked character/product asset files saved and tagged in Flow AI [VI-SOP1, IM-SOP1].
*   **DoD:** Complete asset package saved under a unique `@Name` tag containing multi-angle sheets and verified physical textures [VI-SOP1, IM-SOP1].
*   **QA:** No white backdrops utilized in the base asset. Logo depth deformation must not exceed 3mm [VI-SOP1].
*   **Metrics:** Asset consistency across 5 shots ($\ge 95\%$), setup time (< 20 mins).
*   **Recovery:** If the asset drifts, re-anchor by selecting the highest-quality generated frame as your new primary seed and deleting the drifting reference [IM-SOP5].
*   **Agent Role:** Lead AI Art Director / Visual Asset Engineer.
*   **Sources:** [VI-SOP1, IM-SOP1, IM-SOP3, IM-SOP5, AC-SOP1].

### 10.2 SOP VP2: Location Locking & Scene Plate Curation
*   **Purpose:** To maintain background architectural and spatial continuity across scenes, preventing background morphing during multi-shot sequences [VI-SOP2, IM-SOP2].
*   **Trigger:** Designing a multi-shot video storyboard or photo sequence in a shared location [VI-SOP2].
*   **Inputs:** Scene Explorer access, target location descriptions, camera angle tags [VI-SOP2].
*   **Prerequisites:** Brand mood board and spatial guidelines approved [VI-SOP2].
*   **Procedure:**
    1.  **Generate Standalone Environment Plates:** Render clean architectural location plates (e.g., `@IvoryGallery` or `@NeroMarquinaBathroom`) with zero characters, products, or moving objects present [VI-SOP2, IM-SOP2].
    2.  **Execute Angle Selection via Scene Explorer:** Open the custom Scene Explorer tool [VI-SOP2]. Input your location description, select your target camera angle tags (Wide, Low Angle, High Angle), and generate [VI-SOP2]. Select the optimal plates [VI-SOP2].
    3.  **Lock Location Seeds:** Save the selected plates to your scene library, assigning unique names [VI-SOP2]. Utilize these identical plates as background anchors in all downstream product and character integrations [VI-SOP2].
*   **Decision Points:**
    *   **IF** background details morph between shots:
        *   **THEN** lower the background weight slider or use the "Lock Background" prompt modifier [IM-SOP2].
    *   **IF** the lighting on the product does not match the location plate:
        *   **THEN** manually describe the plate's lighting source (e.g., "illuminated by a low-angle sunset from the left") in the product generation prompt [IM-SOP2, VI-SOP2].
*   **Output:** Standardized, locked background plates saved in the Scene Explorer library [VI-SOP2].
*   **DoD:** Background plates verified clean, containing zero moving visual distortions, and logged as `@PlateName` [VI-SOP2].
*   **QA:** No characters or moving objects may exist on the master background plate [VI-SOP2].
*   **Metrics:** Background spatial similarity index ($\ge 90\%$).
*   **Recovery:** If the background continues to drift, isolate the background plate in Photoshop, manually paint out the morphing elements, and re-upload as a rigid image reference [IM-SOP2].
*   **Agent Role:** Virtual Location Scout / Plate Curator.
*   **Sources:** [VI-SOP2, IM-SOP2].

### 10.3 SOP VP3: Material Physics & Shading Shaders
*   **Purpose:** To eliminate flat, plasticky AI renders and force realistic, physical light-surface interactions by explicitly describing material micro-geometry in prompt structures [IM-SOP3].
*   **Trigger:** Generating highly realistic product close-ups or extreme macros [IM-SOP3].
*   **Inputs:** Material specs, raw surface geometry data, rendering prompts [IM-SOP3].
*   **Prerequisites:** High-fidelity prompt engine access [IM-SOP3].
*   **Procedure:**
    1.  **Inject Subsurface Scattering (SSS):** For translucent materials (skin, soap, wax, liquids, flower petals), light must penetrate the outer boundary, scatter multiple times inside, and exit with wavelength-dependent absorption [IM-SOP3].
        *   *Prompt Syntax:* "Apply screen-space Burley Subsurface Scattering with a 1.2cm scatter radius, showing a natural reddish tissue undertone." [IM-SOP3] or "Random Walk SSS model with red wavelength-deep internal scattering." [IM-SOP3].
    2.  **Inject Vellus Hair & Asperity Scattering:** Human skin must feature short, thin, translucent vellus hairs ("peach fuzz") [IM-SOP3]. In backlit scenarios, light striking these micro-fibers undergoes asperity scattering, illuminating the silhouette and creating a soft halo glow [IM-SOP3].
        *   *Prompt Syntax:* "Micro-pore skin texture with realistic 1.5mm vellus hair (peach fuzz) along the facial silhouette, illuminated by backlight to create asperity scattering, preventing a flat render look." [IM-SOP3].
    3.  **Inject Anisotropic Highlights:** For directional micro-structures (brushed metals, hair, woven fabrics), light reflections must stretch perpendicularly to the micro-grooves rather than forming uniform circular spots [IM-SOP3].
        *   *Prompt Syntax:* "Anisotropic reflections stretching perpendicularly across the brushed steel surface." [IM-SOP3] or "Marschner hair model showing distinct primary and secondary anisotropic highlights." [IM-SOP3].
    4.  **Describe Worsted Wool Weave DNA:** For premium clothing, describe fiber diameter and weave pattern [IM-SOP3].
        *   *Prompt Syntax:* "Super 120s worsted wool (17.75-micron fibers) woven in a dense twill weave with parallel diagonal ribs, showing natural drape and a subtle, soft luster under diffused lighting." [IM-SOP3].
*   **Decision Points:**
    *   **IF** material surface looks flat under lighting:
        *   **THEN** inject a low-angle raking key light from a 3 o'clock position to cast micro-shadows [IM-SOP4].
    *   **IF** skin appears oily or sweaty:
        *   **THEN** adjust the "Specular Roughness" or describe skin as "matte-satin skin texture with dry pores" [IM-SOP3].
*   **Output:** Highly realistic, physically grounded visual asset [IM-SOP3].
*   **DoD:** Render contains accurate subsurface scattering, micro-pore skin detail, and non-circular anisotropic reflections verified via visual inspection [IM-SOP3].
*   **QA:** No flat digital gradients or plastic-sheen surfaces allowed in the final image.
*   **Metrics:** Pixel realism score, specular highlight accuracy.
*   **Recovery:** If the model ignores micro-details, increase prompt weight modifiers on physics-based descriptions using parentheses (e.g., `(realistic 1.5mm vellus hair:1.3)`) [IM-SOP3].
*   **Agent Role:** Technical Shader Engineer / Prompt Developer.
*   **Sources:** [IM-SOP3].

### 10.4 SOP VP4: Start & End Frame Video Motion Locking & Temporal Continuity
*   **Purpose:** To generate smooth, high-fidelity video transitions with zero perspective drift or warping, especially when animating translucent, glass, or liquid materials [VI-SOP5, IM-SOP5].
*   **Trigger:** Launching a video generation sprint based on static image frames [VI-SOP5].
*   **Inputs:** High-quality Start Frame (Frame A), High-quality End Frame (Frame B) [VI-SOP5].
*   **Prerequisites:** High-fidelity static images generated and verified [VI-SOP5, IM-SOP5].
*   **Procedure:**
    1.  **Verify Frame Quality:** Ensure both Frame A and Frame B feature identical environments, subjects, and stable, non-flickering lighting [VI-SOP5]. Poorly aligned references will yield glitchy transitions [VI-SOP5].
    2.  **Apply the "Anti-Melt" Frame-Anchor Cheat Code:** When animating highly translucent, glass, or liquid objects, light refractions confuse the model, causing geometry to warp [IM-SOP5].
        *   Upload the **exact same reference image as both the Start Frame and the End Frame** [IM-SOP5].
        *   By capping both poles of the 5-to-8-second timeline with identical pixel coordinate sets, the model's physics engine is mathematically forced to return to the starting geometry, anchoring the object's solid state [IM-SOP5].
        *   Reduce the platform's motion slider to **10% - 20%** to force the AI to only animate lighting or environmental particles (like steam) while the product block remains completely frozen [IM-SOP5].
    3.  **Prompt the Interpolation Motion:** For static subjects with moving cameras, use the following syntax: *"[Subject] remains completely still, holding majestic posture. The camera performs a slow dolly push-in, ending on a tight close-up. The background remains consistent throughout."* [VI-SOP5, IM-SOP5].
*   **Decision Points:**
    *   **IF** the video exhibits severe warping (melt) on camera movement:
        *   **THEN** toggle on the Frame-Anchor Cheat Code and reduce the motion slider [IM-SOP5].
    *   **IF** the subject's face morphs across the timeline:
        *   **THEN** increase the "Character Weight" slider to maximum and shorten the generation duration to 3 seconds [VI-SOP5].
*   **Output:** Seamless, jitter-free video sequence [VI-SOP5, IM-SOP5].
*   **DoD:** Generated video maintains structural geometry and stable lighting across the entire timeline with zero visual warping or melting [VI-SOP5, IM-SOP5].
*   **QA:** Zero "hallucinated frames" or sudden visual glitches. Product boundaries must remain rigid [IM-SOP5].
*   **Metrics:** Frame rate compliance (60fps), Jitter score, Geometry drift rate (0%).
*   **Recovery:** If the interpolation glitches, generate the video in shorter 2-second segments, using the final frame of the previous segment as the starting frame for the next [VI-SOP5].
*   **Agent Role:** Cinematography Node / Video Animator.
*   **Sources:** [VI-SOP5, IM-SOP5].

### 10.5 SOP VP5: Surgical JSON Image Editing & Multi-Object Spatial Annotation
*   **Purpose:** To execute precise, localized edits on single image elements or multi-object coordinates without modifying the surrounding background or composition [VI-SOP3, VI-SOP4].
*   **Trigger:** Feedback received on a generated image requiring localized adjustments (e.g., removing a cup, shifting eyes) [VI-SOP3, VI-SOP4].
*   **Inputs:** Original image asset, editing prompt guidelines [VI-SOP3, VI-SOP4].
*   **Prerequisites:** High-fidelity image model interface open with JSON/annotation support [VI-SOP3, VI-SOP4].
*   **Procedure:**
    1.  **Extract Image Metadata:** Ask the reasoning model (Gemini or ChatGPT) to: *"Extract the metadata of the image, including style, composition, dominant colors, and objects, and convert it to JSON format."* [VI-SOP3].
    2.  **Execute Granular Value Modifications:** Locate the specific key-value pair in the JSON output you want to edit. Modify the target value (e.g., change `"plant_type": "monstera"` to `"plant_type": "dried eucalyptus"`) [VI-SOP3].
    3.  **Submit JSON for Surgical Execution:** Paste the modified JSON back with the command: *"Modify the image following the instructions of this JSON."* [VI-SOP3].
    4.  **Execute Multi-Object Spatial Annotations:**
        *   Open the visual edit panel. Use the **Box Selection Tool** or **Lasso Tool** to highlight the target region (e.g., a coffee cup) [VI-SOP4].
        *   Draw arrows and write exact text instructions directly over the selection (e.g., write "remove cup" or "change her eyes to look at the camera") [VI-SOP4].
        *   Submit the generation. **You must explicitly include this exact phrase in the prompt box: "Follow edit instructions on annotations."** [VI-SOP4]. (Without this string, the model will ignore your annotations and default to standard prompts) [VI-SOP4].
*   **Decision Points:**
    *   **IF** the model edits the background during a JSON update:
        *   **THEN** add a root key `"locked_composition": true` to the JSON schema [VI-SOP3].
    *   **IF** visual annotations are ignored by the editor:
        *   **THEN** verify the exact phrase "Follow edit instructions on annotations" is written in the main prompt input box [VI-SOP4].
*   **Output:** Surgically updated image asset with zero background alteration [VI-SOP3, VI-SOP4].
*   **DoD:** Localized edit completed, background and all non-targeted objects remain pixel-identical to the original asset [VI-SOP3, VI-SOP4].
*   **QA:** Run a visual toggle check (before vs after) to confirm zero pixel change outside the annotated box.
*   **Metrics:** Pixel preservation rate outside edit zone (100%), surgical accuracy.
*   **Recovery:** If the surgical edit fails repeatedly, isolate the element in Photoshop, apply the edit manually, and use the updated image as an image-to-image reference at 0.1 strength [IM-SOP2].
*   **Agent Role:** Digital Compositor / Image Editor Node.
*   **Sources:** [VI-SOP3, VI-SOP4, IM-SOP2].

### 10.6 SOP VP6: Stateful Conversational Editing Loop (Gemini Omni Flash)
*   **Purpose:** To maintain scene continuity and execute rapid, iterative conversational edits on generated assets by capturing session state [VI-SOP7].
*   **Trigger:** Client feedback or design revisions requested on a generated sequence [VI-SOP7].
*   **Inputs:** Active session ID, client revision notes, API payload keys [VI-SOP7].
*   **Prerequisites:** Meta/Google developer console access, API connection active [VI-SOP7].
*   **Procedure:**
    1.  **Capture Session State:** Retrieve the `previous_interaction_id` from the REST API payload to preserve scene continuity across conversational turns [VI-SOP7].
    2.  **Enforce One-Change Protocol:** Request only **one major change per conversational turn** [VI-SOP7]. (Forcing multiple adjustments simultaneously, such as "Change background, change shirt color, make him run" degrades compositional coherence) [VI-SOP7].
    3.  **Append Preservation Suffix:** End every edit prompt with the literal string: *"Keep everything else identical."* or *"Keep everything else the same."* to instruct the model's preservation attention maps [VI-SOP7].
    4.  **Manage Edit Parameters [BUG WARNING]:** During an edit task, **never pass aspect_ratio or duration parameters** in the API payload [VI-SOP7]. Passing these parameters triggers a generic HTTP 400 error or causes the request to fail with a backend timeout after 45 seconds [VI-SOP7].
*   **Decision Points:**
    *   **IF** the edit request requires multiple changes (e.g., color and position):
        *   **THEN** split the instructions into consecutive conversational turns, executing one change at a time [VI-SOP7].
    *   **IF** the API returns an HTTP 400 error during an edit call:
        *   **THEN** immediately check and remove any aspect ratio or duration parameters from the payload [VI-SOP7].
*   **Output:** Iterated visual asset maintaining perfect continuity [VI-SOP7].
*   **DoD:** Edit completed successfully, session history preserved, and API calls executed without timeout errors [VI-SOP7].
*   **QA:** No background warping or loss of character identity across the editing chain.
*   **Metrics:** API Success Rate (100%), editing speed, revision cycles.
*   **Recovery:** If the API times out after 45 seconds, clear the active session cache and initiate a fresh call using the previous frame ID as a direct image-to-image starting reference [VI-SOP7].
*   **Agent Role:** Visual Systems Integrator / API Specialist.
*   **Sources:** [VI-SOP7].

### 10.7 SOP VP7: 5-Shot eCommerce Catalog Automation Pipeline
*   **Purpose:** To systematically transform raw product data and silhouettes into a complete, standardized, publication-ready e-commerce catalog package without physical photoshoots [VI-SOP6, IM-SOP4, AC-SOP4, PE-SOP5.3].
*   **Trigger:** Onboarding a new physical product SKU under the NEROZARB luxury portfolio [VI-SOP6, IM-SOP4].
*   **Inputs:** Product silhouette reference `@ProductVariantBase`, design guidelines, color and material specifications [VI-SOP6, IM-SOP4].
*   **Prerequisites:** High-fidelity product geometry locked [VI-SOP1, VI-SOP6].
*   **Procedure:** Generate the following five standardized listing assets in exact sequence to build a cohesive, high-converting catalog package [VI-SOP6, IM-SOP4, AC-SOP4]:
    1.  **Shot 1: The Hero Packshot (Pure Listing Asset):**
        *   *Objective:* Focuses entirely on product purity and geometrical authority to build immediate consumer trust [VI-SOP6, IM-SOP4].
        *   *Prompt Pattern:* *"Studio packshot of [Product, e.g., @ProductVariantBase], centered in the frame, angled at a 3/4 perspective. Resting on a clean white Carrera marble slab. Background is a seamless, desaturated warm alabaster (#EFECE1) wall. Shot on Hasselblad X2D 100C with an 85mm prime lens at f/8.0 for corner-to-corner sharpness. Lighting: Daylight-balanced high-key clamshell configuration. Large overhead softbox at 5500K angled down at 45 degrees, paired with a white reflector card below to eliminate harsh shadows under the product. Material: Satin-matte finish with 1.2cm subsurface scattering. No water droplets, no decorative props. Clean, isolated, pure."* [VI-SOP6, IM-SOP4].
    2.  **Shot 2: The Detailed Macro (Surgical Topography Setup):**
        *   *Objective:* Highlights artisan craftsmanship, raw ingredients, and undeniable material truth [VI-SOP6, IM-SOP4].
        *   *Prompt Pattern:* *"Extreme macro photography of the surface of [Product], focusing on the [Micro-details: e.g., debossed calligraphy logo and embedded organic coffee fibers]. The frame is filled with the rugged, microscopic topography of the surface, showing natural irregularities. Shot on Phase One IQ4 with a 100mm macro lens at f/11 for deep, razor-sharp focus across the plane. Lighting: Single low-angle raking key light from a 3 o'clock position (right side), casting micro-shadows in the texture's relief to emphasize tactile grit and exfoliation. Tiny glistening beads of moisture sit on the surface like jewels. Tonal palette of espresso, bronze, and cream. No digital smoothing; raw, organic, tactile."* [VI-SOP6, IM-SOP4].
    3.  **Shot 3: The Sensorial Lifestyle (Human Ritual Scene):**
        *   *Objective:* Evokes tactile luxury and sensory desire through human interaction and wet-use physics [VI-SOP6, IM-SOP4].
        *   *Prompt Pattern:* *"Lifestyle ritual scene showing a close-up of [Subject, e.g., a person's wet hands lathering a bar of Soap]. The hands are covered in a dense, heavy, luxurious velvet lather foam with microscopic bubbles of varying sizes. Water droplets and rich, thick suds drip elegantly from the wrists. Shot on Arri Alexa 35 with a 50mm Master Macro lens at f/2.8, capturing extreme shallow depth of field. Background is a soft, completely out-of-focus dark slate bathroom wall with warm candle glow. Lighting: Cinematic side-lit soft panel at 3200K, casting rich golden highlights across the wet suds and skin. High-speed shutter setting to capture individual flying suds and water splashes in razor-sharp stasis. Raw, emotional, sensorial."* [VI-SOP6, IM-SOP4].
    4.  **Shot 4: The Copy-Safe Canvas (Marketing Infographic Asset):**
        *   *Objective:* Combines premium B-roll with aggressive minimalist negative space to allow for typography overlays [VI-SOP6, IM-SOP4].
        *   *Prompt Pattern:* *"High-end editorial composition featuring [Product] positioned in the lower-right third of the frame. The entire left and upper-left two-thirds of the canvas consists of a completely empty, smooth, desaturated dark charcoal concrete wall with soft, subtle light fall-off. Shot on Hasselblad H6D-100c with a 50mm lens at f/5.6. Lighting: Single soft overhead light source casting a long, elegant shadow from the product extending toward the bottom right. The texture of the concrete is visible but highly subtle, providing a premium, copy-safe negative space canvas for overlay text. Avant-garde, quiet luxury, brutalist."* [VI-SOP6, IM-SOP4].
    5.  **Shot 5: The Viral Spectacle (High-Speed Fluid Dynamics):**
        *   *Objective:* Captures high-speed physical physics to disrupt social scroll autopilot [VI-SOP6, IM-SOP4].
        *   *Prompt Pattern:* *"High-speed macro action shot of [Product] falling into a deep, dark pool of liquid espresso. The exact moment of impact is captured in razor-sharp stasis, showing a majestic crown splash with individual, glistening coffee droplets suspended in mid-air. Intricate fluid dynamics with ripples and microscopic air bubbles spreading across the surface. Shot on Phantom Flex 4K at 2000fps with a 90mm macro lens at f/8.0. Lighting: High-intensity strobes from both left and right sides to perfectly freeze the motion with zero motion blur. Backlit by a soft amber panel to illuminate the liquid's transparency. Raw, hyper-kinetic, spellbinding."* [VI-SOP6, IM-SOP4].
*   **Decision Points:**
    *   **IF** Shot 3 exhibits flat, soapy lather (fake looking):
        *   **THEN** force microscopic bubbles of varying sizes and wet-use physics in the prompt [VI-SOP6].
    *   **IF** Shot 4 lacks sufficient negative space for copy:
        *   **THEN** increase the canvas width or crop the product to the far edge using spatial coordinates [IM-SOP4].
*   **Output:** Five cohesive, publication-quality product listing and advertising assets [VI-SOP6, IM-SOP4].
*   **DoD:** All five shots generated in sequence, matching product geometry, color-graded to a unified brand palette, and verified as high-resolution assets [VI-SOP6, IM-SOP4].
*   **QA:** No digital overlays, watermarks, or text in the raw generated frames. All shots must maintain geometric product authority [VI-SOP1, VI-SOP6].
*   **Metrics:** Production time ($\le 45$ mins), Asset resolution ($\ge 4K$).
*   **Recovery:** If the product geometry drifts in Shot 5 due to complex fluid physics, overlay the original locked packshot silhouette on top using Photoshop masks and merge [IM-SOP5].
*   **Agent Role:** Lead Product Designer / CGI Automation Node.
*   **Sources:** [VI-SOP6, IM-SOP4, AC-SOP4, PE-SOP5.3, VI-SOP1].

### 10.8 SOP VP8: AI-Assisted Static Ad Production (Canva Magic Layers Workflow)
*   **Purpose:** To construct professional-grade, editable image and static ads in minutes utilizing AI design models combined with canvas layers, bypassing expensive graphic design cycles [AC-SOP2, PA-SOP8].
*   **Trigger:** Launching a static ad variation batch in the testing sandbox campaign [AC-SOP2, PA-SOP8].
*   **Inputs:** High-res product images, Canva/Figma workspace access, Nano Banana Pro 2 prompt templates [AC-SOP2, PA-SOP8].
*   **Prerequisites:** High-fidelity cutout of the product with transparent background available [AC-SOP2, PA-SOP8].
*   **Procedure:**
    1.  **Generate Base Background Scene:** Generate a high-resolution scroll-stopping background scene in **Nano Banana Pro 2** [AC-SOP2, PA-SOP8].
        *   *Prompt Reference Technique:* Upload a flat-lay cutout of your product. Prompt: *"Make this woman sat in her bedroom at a vanity table holding the product in image 1, shot on an iPhone 17 Pro."* [AC-SOP2].
    2.  **Upload to Canva:** Download the high-res generated asset and upload it to Canva [AC-SOP2, PA-SOP8].
    3.  **Activate Magic Layers:** Open Canva's **Magic Layers** tool to automatically scan and separate the background, product, and human hand elements into editable, independent layers [AC-SOP2, PA-SOP8].
    4.  **Format Typography Overlay:** Layer in bold Montserrat Black ALL CAPS headline copy directly onto the background layer, placing it *behind* the foreground product layer to create professional, three-dimensional depth [AC-SOP2, PA-SOP8].
    5.  **Audit and Export:** Run the Squint Test (see Section 11) to verify visual hierarchy, then export at 2000x2000 PNG format [PA-SOP8].
*   **Decision Points:**
    *   **IF** the Magic Layers tool misaligns the foreground boundaries:
        *   **THEN** manually touch up the boundaries using the background remover brush [AC-SOP2].
    *   **IF** the overlay typography is difficult to read:
        *   **THEN** add a subtle, dark gradient mask (#0A0A0A at 15% opacity) directly behind the text [AC-SOP2].
*   **Output:** Professional, high-contrast, layered static ad ready for media buying [AC-SOP2, PA-SOP8].
*   **DoD:** Completed static ad exported, containing a 3D layered structure, high-contrast Montserrat typography, and passing the Squint Test [AC-SOP2, PA-SOP8].
*   **QA:** No cheap AI drop shadows, text glows, or outlines allowed on the typography layers [MC-5.4, AC-SOP2].
*   **Metrics:** Design production speed (< 15 mins), click-through rate performance.
*   **Recovery:** If the background remover ruins the product silhouette, import the assets to Photoshop and manually mask the layer boundaries using the pen tool before uploading back [AC-SOP2].
*   **Agent Role:** Graphic Designer Node.
*   **Sources:** [AC-SOP2, PA-SOP8, MC-5.4].

### 10.9 SOP VP9: UGC Casting, Vetting, and Vibe Management
*   **Purpose:** To source authentic, highly native, and high-status creators on digital channels while maintaining strict brand alignment and direct-response performance [AC-SOP3].
*   **Trigger:** Designing a creator-led UGC campaign or sourcing new video actors [AC-SOP3].
*   **Inputs:** Casting channel access (Backstage, StarNow), buyer persona demographics, vetting checklists [AC-SOP3].
*   **Prerequisites:** Modular UGC briefing package completed [MM-5.2, AC-SOP3].
*   **Procedure:**
    1.  **Post Casting Call:** Post casting briefs on platforms specifying vertical filming (9:16) with all action kept within the safe zones [AC-SOP3].
    2.  **Align Personas:** Match the candidate's age, gender, accent, look, and skin tone to the exact buyer persona identified during review mining [AC-SOP3].
    3.  **Vett Reading Style:** Force candidates to submit a 15-second raw talking video. Reject candidates who sound like they are reading off teleprompters with flat, inflected, or "salesy" tones [AC-SOP3]. Seek raw, natural "FaceTime" style delivery [AC-SOP3].
    4.  **Deploy Production Instructions:** Instruct selected creators to film raw (no background music, no filter, no burned-in text), using clean natural lighting, direct mic audio (no AC hums), and to deliver both the rough edited cut and all raw MP4 assets [AC-SOP3].
*   **Decision Points:**
    *   **IF** creator submissions exhibit poor lighting or audio hum:
        *   **THEN** reject the draft and require a re-shoot with specific window-light alignment directions [AC-SOP3].
    *   **IF** a creator is highly authentic but struggles with pacing:
        *   **THEN** have your internal video editor assemble the raw clips using tight jump cuts to force rapid momentum [MM-5.12, AC-SOP3].
*   **Output:** Vetted creator roster and raw UGC assets saved to the campaign directory [AC-SOP3].
*   **DoD:** Raw footage and edited cuts delivered by creator, safe-zone checked, and backed up in raw format for modular hook refurbishing [AC-SOP5, AC-SOP3].
*   **QA:** Ensure no music is baked into raw files. Creator's eyes must look directly at the smartphone lens, not slightly above or below.
*   **Metrics:** Creator onboarding speed, vetting pass rate, raw asset count per creator ($\ge 5$ clips).
*   **Recovery:** If a creator fails to deliver within agreed timelines, automatically trigger a reminder warning, and if unresolved in 24 hours, terminate the contract and transition the brief to your backup creator [AC-SOP3].
*   **Agent Role:** UGC Casting Director / Vibe Manager.
*   **Sources:** [AC-SOP3, MM-5.2, AC-SOP5].

---

## 11. DOMAIN 9: PROMPTING DOMAIN

### 11.1 SOP PR1: Ingestion and Outlier Prompt Execution Structures
*   **Purpose:** To programmatically execute data-validated ingestion and classification tasks on competitor CSV files within Claude Projects, isolating 5x outliers and organizing high-converting hooks [MM-5.8, CO-SOP1].
*   **Trigger:** Exporting raw outlier datasets from Sandcastles.ai or customer reviews CSVs from Shopify storefronts [MM-5.8, CO-SOP1, PA-SOP1].
*   **Inputs:** Raw .csv file exports, Claude 3.7 Projects access [CO-SOP1].
*   **Prerequisites:** Target brand parameters and positioning goals verified [MM-5.8].
*   **Procedure:**
    1.  **Initialize Project Interface:** Open Claude 3.7. Create a clean project space and upload your raw `.csv` dataset (e.g., `Sandcastles_Outliers_Export.csv` or `Shopify_Reviews.csv`) [CO-SOP1, PA-SOP1].
    2.  **Execute Ingestion Prompt:** Paste and run the following exact system prompt string into the console [CO-SOP1]:
        ```text
        [SYSTEM: INGESTION & COHORT ANALYSIS]
        You are NERO, the Chief Systems Analyst at NEROZARB. Analyze this uploaded .csv dataset containing [Sandcastles competitor video metrics / Shopify customer reviews].
        Execute the following sequence with mathematical precision:
        1. Parse the rows and calculate the baseline average metric for each channel or product grouping.
        2. Isolate and output a clean Markdown table containing only the rows where the "Outlier Score" or engagement metric is >= 5x the calculated baseline average.
        3. Extract the exact written hook text and categorise them into one of the 4 creative levers: Persona, Messaging, Hook, or Format.
        4. Output a list of the top 10 contrarian topics based on these outliers, keeping the visual structure constant while reframing the substance to target our proprietary growth mechanisms.
        Do not output preambles, summaries, or conversational filler. Output raw structured data only.
        ```
    3.  **Execute Golden Nugget Mining Prompt:** If analyzing customer reviews, paste and run the following exact prompt string [PA-SOP1, CP-SOP1]:
        ```text
        [SYSTEM: IN-VIVO REVIEWS MINING]
        You are NEROZARB's Lead Copywriter. Analyze the uploaded Shopify reviews CSV and execute the Golden Nugget Mining sequence:
        1. Extract the top 15 verbatim customer quotes expressing extreme emotional frustration, pain, or failed competitor attempts. Preserve raw, un-edited customer idioms and visceral terms.
        2. Compile a 3-column Objections Matrix:
           Col 1: Verbatim Frustration (e.g., "biscuit smell")
           Col 2: Failed Competitor Attempt (e.g., "other brand left streaks")
           Col 3: Amygdala Anchor (e.g., fear of smelling weird in public)
        3. Identify any "grainy textures," "bad smells," or "broken customer support" mentioned in rival brands.
        Do not add corporate or marketing jargon. Do not summarize quotes. Output the raw Markdown matrix.
        ```
*   **Decision Points:**
    *   **IF** the model outputs conversational filler or starts sentences with "Certainly, here is...":
        *   **THEN** stop generation, clear cache, and add the negative system tag `[CONSTRAINT: NO CHATTY TEXT]` at the top of your prompt [CO-SOP2].
    *   **IF** the CSV upload fails due to size limits:
        *   **THEN** run a local python script to split the CSV into 500-row chunks and run sequential chunk-ingestion [PA-SOP1].
*   **Output:** Live, structured competitor data tables and objection matrices saved in Claude Projects [CO-SOP1, CP-SOP1].
*   **DoD:** Raw CSV uploaded, exact prompt executed, and structured Markdown output tables generated and verified [CO-SOP1].
*   **QA:** No conversational preambles present in the generated output. Ensure the verbatim quotes match original CSV strings exactly.
*   **Metrics:** Prompt execution accuracy (100%), processing time (< 30 seconds).
*   **Recovery:** If Claude generates truncated tables, input the command: *"Continue outputting exactly where you left off, preserving table headers."* [CO-SOP1].
*   **Agent Role:** Prompts Architect Agent.
*   **Sources:** [MM-5.8, CO-SOP1, PA-SOP1, CP-SOP1, CO-SOP2].

### 11.2 SOP PR2: Structure Extraction Prompt Formats
*   **Purpose:** To extract the abstract, structural formula of viral video transcripts and save them as variables-based templates, bypassing original niche context [CO-SOP3].
*   **Trigger:** Raw transcripts successfully pulled from transcription software are ready for templatization [CO-SOP3].
*   **Inputs:** Raw video spoken transcript text, Claude/ChatGPT workspace access [CO-SOP3].
*   **Prerequisites:** High-performance transcription verified [CO-SOP3].
*   **Procedure:**
    1.  **Initialize LLM Session:** Open a clean conversation thread in your LLM workspace [CO-SOP3].
    2.  **Execute Structural Extraction Prompt:** Paste and run the following exact prompt string into the input field [CO-SOP3]:
        ```text
        [SYSTEM: STRUCTURAL TEMPLATE EXTRACTION]
        You are a NEROZARB Systems Copywriter. Analyze the following raw video transcript and extract its underlying direct-response formula:
        1. Replace all specific product, brand, or niche elements with generic variables: [PROB] for problem, [SCAPEGOAT] for systemic villain, [MECH] for unique mechanism, [PROOF] for case study, and [CTA] for call to action.
        2. Isolate and map the pacing structure, timing blocks (0:00 - 0:05, 0:05 - 0:15, etc.), and visual-auditory pattern breaks.
        3. Output the final result as a clean, repeatable copywriting script template. Preserve all structural transitions like "But here is the crazy part" or "Therefore."
        Transcript text to analyze:
        ---
        [INSERT RAW TRANSCRIPT TEXT HERE]
        ---
        ```
    3.  **Validate Variables Output:** Confirm that all specific product/niche words have been successfully replaced by brackets [CO-SOP3].
*   **Decision Points:**
    *   **IF** the generated template still contains specific references (e.g., "soap", "skincare"):
        *   **THEN** run a refinement prompt: *"Ruthlessly replace any remaining niche-specific words with generic bracketed variables."* [CO-SOP3].
    *   **IF** the transcript pacing is too slow:
        *   **THEN** instruct the model to compress the transcript into a tight 15/3 constraint format [AOS-5.3, CO-SOP2].
*   **Output:** Variables-based direct-response template ready to be deployed on client products [CO-SOP3].
*   **DoD:** Complete template generated with timing brackets, visual action markers, and clean bracketed variables [CO-SOP3].
*   **QA:** No lingering competitor brand names or niche definitions allowed. All transitions must be strictly logical [CO-SOP3].
*   **Metrics:** Templatization speed, variables compliance (100%).
*   **Recovery:** If the LLM output is too generic, re-run by providing a pre-built example of a high-converting NEROZARB Q.S.T.A. template as a few-shot guide [CO-SOP3].
*   **Agent Role:** Prompt Engineer / Variable Architect.
*   **Sources:** [CO-SOP3, AOS-5.3, CO-SOP2].

---

## 12. DOMAIN 10: QA DOMAIN

### 12.1 SOP QA1: Pre-Publish Quality Gate Audit
*   **Purpose:** To enforce a rigorous, mandatory design and copywriting audit on every social media asset and video clip prior to publication, ensuring absolute compliance with NEROZARB's premium aesthetic and technical standards [MC-1.2, MC-SOP4, VI-SOP8].
*   **Trigger:** Design or video editing node submits an asset as "complete" and requests publication [MC-SOP4, VI-SOP8].
*   **Inputs:** Completed image or video asset file, active Quality Gate checklist [MC-SOP4].
*   **Prerequisites:** Original project files open for immediate adjustments [MC-SOP4, VI-SOP8].
*   **Procedure:**
    1.  **Execute Checklist Verification:** Perform a manual, item-by-item verification of the following strict parameters:
        *   [ ] **Void Base:** Background is 100% Onyx Black (#0A0A0A) occupying 60–70% of the canvas [MC-SOP4].
        *   [ ] **Strict 3-Color Cap:** Post utilizes a maximum of exactly 3 colors (Void Black #0A0A0A, Pure White #FFFFFF, and Olive Leaf Green #3F6A24) [MC-SOP3, MC-SOP4].
        *   [ ] **Negative Space Check:** Minimum 40% of the canvas is empty, clean, negative space [MC-SOP3, MC-SOP4].
        *   [ ] **No Effects on Typography:** Zero drop shadows, zero text glows, zero outlines. Text must sit raw on the black void [MC-SOP4].
        *   [ ] **Montserrat Dominance:** Hero headline is Montserrat Black, ALL CAPS, 70–85pt, left-aligned, with letter tracking set to -3px [MC-SOP3, MC-SOP4].
        *   [ ] **Mono System Tags:** Space Mono is used exclusively for functional, small system tags (e.g., `[ SYSTEM: DIAGNOSTIC ]`) [MC-SOP4].
        *   [ ] **Zero Jargon:** Copywriting has run through the Jargon Translation Table. No forbidden words are present [MC-SOP4].
        *   [ ] **The 15/3 Constraint:** No sentence exceeds 15 words. No paragraph exceeds 3 sentences [MC-SOP4, AOS-5.3].
        *   [ ] **The Scapegoat Present:** Cortisol has been lowered by shifting blame from the user to traditional agencies or broken industry systems [MC-SOP2, MC-SOP4].
        *   [ ] **One Gate CTA:** Call to action points exclusively to a single WhatsApp or ManyChat link. No secondary links or multiple choice options allowed [MC-SOP4, MM-5.11].
    2.  **Calculate Quality Gate Score:** Sum the positive checkmarks. Every asset must achieve a minimum score of **9/10** to pass [MC-SOP4].
*   **Decision Points:**
    *   **IF** the asset scores below 9/10:
        *   **THEN** immediately reject, delete from the publishing queue, and send back to the design room with specific checklist failure logs [MC-SOP4].
    *   **IF** typography exhibits drop shadows or outlines:
        *   **THEN** remove the effects immediately; text must rest raw on the void background [MC-SOP4].
*   **Output:** Approved, compliant visual/copy asset signed off for publication [MC-SOP4].
*   **DoD:** Quality Gate checklist fully checked, score $\ge 9/10$ achieved, and approval signature logged in the publishing channel [MC-SOP4].
*   **QA:** No exceptions to the 3-color cap or the Onyx Black background are permitted for organic brand channels [MC-SOP3, MC-SOP4].
*   **Metrics:** Quality Gate Pass Rate, Revise Cycles, Publishing compliance (100%).
*   **Recovery:** If a non-compliant asset is accidentally published, delete the post from the live grid within 60 seconds and initiate the QA1 audit before re-uploading [MC-SOP4].
*   **Agent Role:** Quality Assurance Lead / Brand Guardian.
*   **Sources:** [MC-1.2, MC-SOP4, MC-SOP3, MC-SOP2, AOS-5.3, MM-5.11, VI-SOP8].

### 12.2 SOP QA2: VFX & Plate NLE Finishing (MANDATORY AGENCY GATE)
*   **Purpose:** To perform high-end post-production cleanup, branding overlays, and professional audio mastering on all generated video assets, neutralizing compression artifacts and ensuring professional broadcast specs [VI-SOP8].
*   **Trigger:** A video generation task successfully compiles un-edited raw clips [VI-SOP8].
*   **Inputs:** Raw MP4/MOV footage, vector logo assets, DAW/NLE software access (DaVinci Resolve, After Effects, Premiere, ProTools) [VI-SOP8].
*   **Prerequisites:** High-fidelity source video files downloaded and organized [VI-SOP8, CO-SOP5].
*   **Procedure:**
    1.  **Execute Visual Cleanup:** Import the generated MP4 clips into DaVinci Resolve or After Effects [VI-SOP8]. Apply a professional spatial/temporal de-noise pass to clear up 720p/1080p generative model compression artifacts [VI-SOP8].
    2.  **Apply Branding Overlays:** Utilize 3D camera tracking or rotoscoping to track moving product surfaces [VI-SOP8]. Composite vector logos, wordmarks, regulatory tags, and legal text blocks natively onto the moving product layers [VI-SOP8, VI-SOP1].
    3.  **Master Audio Track:** Normalize spoken audio loudness levels [VI-SOP8]. (Native generative models can yield highly erratic, peaking audio outputs) [VI-SOP8]. Separate the audio track, apply clean Foley sound effects (water splashes, lather suds, paper crinkles), and master final levels to standard broadcast specs (e.g., **-14 LUFS** with a maximum peak at -1dBTP) [VI-SOP8].
    4.  **Sync and Export:** Export the final master clip at exactly 1080x1920 pixels, 60fps, h.264, matching direct safe zones [MM-5.12, VI-SOP8].
*   **Decision Points:**
    *   **IF** video compression artifacts remain visible after standard de-noise:
        *   **THEN** apply a subtle, premium film grain overlay (3% opacity) to hide pixel blockiness [VI-SOP8].
    *   **IF** audio peaks exceed -1dBTP:
        *   **THEN** apply a hard limiter at -1.5dB on the master output bus [VI-SOP8].
*   **Output:** Mastered, professional broadcast-ready MP4 video file [VI-SOP8].
*   **DoD:** Visual de-noise applied, 3D tracking logo composited, Foley audio mixed, and track mastered to -14 LUFS [VI-SOP8].
*   **QA:** No watermarks from generative AI software may remain in the final export. Spoken dialogue must be 100% audible with zero distortion [VI-SOP8].
*   **Metrics:** Audio loudness level (-14 LUFS), Frame rate stability (60fps), Video artifacts score.
*   **Recovery:** If the 3D tracker drifts off the product face, manually keyframe the logo's position and scale frame-by-frame to ensure rigid lock [VI-SOP1, VI-SOP8].
*   **Agent Role:** Senior Post-Production Lead / VFX Editor.
*   **Sources:** [VI-SOP8, VI-SOP1, CO-SOP5, MM-5.12].

### 12.3 SOP QA3: Pre-flight Constraints Audit
*   **Purpose:** To perform a clinical, word-by-word and layout-by-layout constraint audit on written copy and static designs before handing them off to the production teams, ensuring absolute cognitive readability and zero brand dilution [AOS-5.3].
*   **Trigger:** Copywriter or Designer Node submits a copy draft or static asset for initial staging [AOS-5.3].
*   **Inputs:** Copy draft text, static asset layout file [AOS-5.3].
*   **Prerequisites:** Banned vocabulary list open, F-Shaped reading pattern guide verified [AOS-5.3].
*   **Procedure:**
    1.  **Check Sentence Word Counts:** Count every word in every individual sentence [AOS-5.3, MC-SOP2]. If any sentence exceeds a strict maximum of **15 words** (or **10 words** for LinkedIn ghostwriting), flag it, and rewrite by splitting it into two distinct lines [AOS-5.3, MC-SOP2].
    2.  **Verify Paragraph Depth:** Count sentences per paragraph block [AOS-5.3, MC-SOP2]. If any paragraph contains more than **3 sentences**, break it [AOS-5.3, MC-SOP2]. Ensure there is a double space between every line block to prevent mobile cognitive strain [AOS-5.3].
    3.  **Execute Banned Word Search:** Run a find command across the copy for the following banned terms: *leverage, ecosystem, navigate, landscape, delve, testament, pivotal, transformative, groundbreaking, vibrant, foster, showcase, passionate, next-level, synergy, comprehensive* [AOS-5.3, MC-SOP2]. Ruthlessly delete any hits and replace them with active, plain-language verbs [AOS-5.3].
    4.  **Audit Visual Layout Pacing:** Open static designs and verify F-Shaped anchor points [AOS-5.3]. Ensure the most critical, high-impact words are positioned within the first 2–3 words of every line to guide the reader's vertical scan [AOS-5.3].
    5.  **Verify Kerning & Font Size:** Ensure Montserrat headlines have a letter tracking locked to exactly **-3px to -4px** [AOS-5.3, MC-SOP3].
*   **Decision Points:**
    *   **IF** a banned word is essential to a specific industry certification (e.g., "comprehensive audit"):
        *   **THEN** replace with "full audit" or "diagnostics" to retain peer authority and avoid marketing speak [AOS-5.3, OUT-11.3].
    *   **IF** the layout has F-Shaped issues:
        *   **THEN** shift line-break locations manually to force high-value nouns/verbs to the start of each line [AOS-5.3].
*   **Output:** Verified, constraint-compliant copy and design drafts cleared for staging [AOS-5.3].
*   **DoD:** Written copy meeting the 15/3 constraint, free of banned words, and visual layouts conforming to F-shaped tracking and letter tracking parameters [AOS-5.3, MC-SOP2].
*   **QA:** No sentences over 15 words allowed under any circumstances. No paragraph blocks exceeding 3 sentences [AOS-5.3].
*   **Metrics:** Sentence length check (100% compliance), Banned word occurrences (0) [AOS-5.3].
*   **Recovery:** If non-compliant copy is sent to a creator, immediately recall the brief, apply the 15/3 constraints in scratch, and resend the updated brief within 15 minutes [MC-SOP2, AOS-5.3].
*   **Agent Role:** Copy Editor / Quality Controller Node.
*   **Sources:** [AOS-5.3, MC-SOP2, MC-SOP3, OUT-11.3].


