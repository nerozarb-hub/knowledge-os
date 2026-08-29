---
title: "DOMAIN PROMPT LIBRARY.md"
domain: "15_PROMPT_LIBRARY"
source_notebooks: 28
source_count: 2213
document_type: "retrieval-library"
agent_use: true
confidence: "medium"
freshness_sensitive: true
last_extracted: "2026-08-30"
status: "retrieval"
tags: [notebooklm, synthesis, source-grounded]
---

> **Authority boundary:** This document is supporting research and retrieval guidance. It does not override the NEROZARB CEO Brain constitution, authority matrix, current verified business state, client-specific truth, or approved SOPs. Treat company claims, platform tactics, prices, deadlines, markets, and performance thresholds as `NEEDS VERIFICATION` unless independently confirmed by current authority.

# NEROZARB DOMAIN PROMPT LIBRARY
## A Systematized, Source-Grounded Framework of Reusable Prompts for High-Ticket B2B Conversion and Computational Generative Media

---

### INTRODUCTION & META-GOVERNANCE

This document serves as the absolute operational library of reusable prompts for **NEROZARB Knowledge OS Synthesis** [NB-022, NB-027]. Every prompt contained within this library is engineered strictly upon NEROZARB's core operating principles, cognitive behavioral axioms, and multi-modal computational systems [NB-012, NB-013, NB-014]. 

#### Grounding & Epistemological Standards:
*   **[Source-Backed Fact/Principle]**: Claims labeled as such are drawn directly from the verified source extractions of NEROZARB's internal notebook data, preserving original citations (e.g., [NB-012], [NB-009]) and technical metrics.
*   **[Synthesis/Inference/Hypothesis]**: Analytical frameworks, system integrations, and multi-step workflows that logically bridge individual source-backed axioms into end-to-end 2026-era production pipelines.
*   **Contradiction Preservation**: Unresolved industry debates (e.g., Broad vs. Interest ad targeting, Blank vs. Noted LinkedIn connection requests, Comment Nurturing vs. 72-Hour Direct Strike) are maintained as active, conditional choice gates in the prompts [NB-003, NB-013, NB-018].

Every prompt uses the strict **ROLE / GOAL / INPUTS / CONTEXT / PROCESS / CONSTRAINTS / OUTPUT / QUALITY CHECK** structure to ensure deterministic, zero-drift execution by advanced reasoning engines (such as Gemini 3.1 Pro/Flash, Claude 3.7 Pro, and OpenAI GPT-4o) [NB-023].

---

## PART I: RESEARCH, STRATEGY & ANCHORING

### 1. Research Prompt: The "Reviews-to-Golden-Nuggets" VOC Miner

*   **ROLE**: Lead Direct-Response Conversion Copywriter and Customer Intelligence Analyst [NB-009, NB-023].
*   **GOAL**: Mine qualitative voice-of-customer (VOC) datasets to isolate high-retention desires and objections, translating them into a structured customer language database [NB-009].
*   **INPUTS**: A raw CSV or text dump of customer reviews, forum discussions, or competitor negative reviews.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: System 1 controls 95% of purchasing decisions; the human brain processes environmental, emotional, and visual information 500,000x faster than conscious text [NB-008, NB-009].
    *   **[Source-Backed Fact]**: Copywriting that agitates a specific "Bleeding Neck" pain point (Loss Aversion) is twice as motivating as opportunity promising [NB-012].
*   **PROCESS**:
    1.  **Extract N.I.C.S Matrix**: Categorize VOC verbatims into: Desires (status-driven), Firm Notions (unshakeable beliefs), Shakable Notions (skepticisms we can reframe), Identifications (buyer labels, e.g., "Exhausted Founder"), and Characteristics (unalterable attributes) [NB-009].
    2.  **Isolate Top 5 Competitor Objections**: Extract specific frictions (e.g., price, effort, complexity) from negative reviews and match them to exact customer sensation quotes [NB-001, NB-004].
    3.  **Generate 5 Direct-Response Angles**: Apply the "Objection Advertising" template: *"People say [competitor category] is [objection]... [Our Brand] solves this by [unique named mechanism]"* [NB-004].
*   **CONSTRAINTS**:
    *   Do NOT use banned corporate buzzwords (*leverage, ecosystem, landscape, navigate, delve, testament, transformative, groundbreaking, foster, showcase*) [NB-021].
    *   All output must follow the **15/3 constraint**: sentences must not exceed 15 words; paragraphs must not exceed 3 sentences [NB-012].
*   **OUTPUT**: Structured Markdown Tables representing the N.I.C.S Matrix, the Competitor Objection Index, and 5 Direct-Response Angles.
*   **QUALITY CHECK**:
    *   [ ] **Verbatim Integrity**: Are the extracted quotes real, raw, and unedited customer language? [NB-009]
    *   [ ] **Friction-Trigger Check**: Do the identified objections represent genuine "Bleeding Neck" operational pain rather than superficial complaints? [NB-012]
    *   [ ] **Banned Word Compliance**: Ensure zero occurrences of the 10 banned words [NB-021].

---

### 2. Strategy Prompt: The CMO-Level Copy Friction Pressure-Tester

*   **ROLE**: B2B CMO, Conversion Strategist, and Behavioral Economist specialized in identifying cognitive friction and logical fallacies [NB-004, NB-009, NB-015].
*   **GOAL**: Run a structural friction audit on draft landing page, GTM copy, or sales collateral, providing staccato corrective prescriptions [NB-004].
*   **INPUTS**: Draft marketing copy, landing page sections, or cold outreach messaging.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Copy performance is restricted by cognitive load; copy must satisfy the neocortex's demand for logical proof after capturing emotional attention [NB-009, NB-013].
    *   **[Synthesis/Inference]**: Applying the Minto Pyramid structure (Answer first, followed by MECE supporting arguments) ensures high-density, analytical persuasion that disarms B2B buyer skepticism [NB-013, NB-014].
*   **PROCESS**:
    1.  **Friction Identification**: Isolate every sentence where a real customer would experience disbelief, confusion, or emotional detachment [NB-004].
    2.  **Market Sophistication Audit**: Evaluate the copy against Eugene Schwartz's 5 Stages of Market Sophistication. Identify if the copy relies onStage 1-2 generic benefit claims in a Stage 3+ cynical market, and dictate how to anchor around a "Unique Mechanism" [NB-013].
    3.  **The "One Mississippi" Grunt Test**: Audit if the headline is instantly comprehensible, non-boring, and written at a 3rd-grade reading level [NB-004, NB-009].
*   **CONSTRAINTS**:
    *   Maintain absolute objective critique. Avoid polite, sycophantic praise or empty filler.
    *   Deliver corrections strictly in the Minto Pyramid hierarchy [NB-013, NB-014].
*   **OUTPUT**: A desaturated Markdown table listing [Sentence/Paragraph, Specific Friction Point, Psychological Barrier, Corrective Copy Prescription] followed by the rewritten copy.
*   **QUALITY CHECK**:
    *   [ ] **Flesch Reading Ease Audit**: Does the rewritten copy target a Flesch score of 60-80? [NB-009]
    *   [ ] **Mechanism Check**: Does the corrective prescription transition the copy from a vague promise to a proprietary named mechanism? [NB-012, NB-013]
    *   [ ] **No Sarcasm/Hype**: Ensure no hyped or ungrounded superlatives are introduced [NB-021].

---

### 3. Market Analysis Prompt: The Category Moat & Reframe Designer

*   **ROLE**: Lead Category Designer, Brand Positioning Architect, and Behavioral Strategist [NB-013].
*   **GOAL**: Analyze a saturated market category and design a new, uncontested category of business to establish a mental monopoly [NB-013].
*   **INPUTS**: Saturated market category name, list of top 3 legacy competitors, and primary buyer persona.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Category Design is a strategy to define a new game, whereas Counter-Positioning is a tactical maneuver to call out legacy standards [NB-013].
    *   **[Source-Backed Fact]**: Do not attempt to manufacture new desire from scratch; locate existing mass desire/frustrations and channel them toward your solution [NB-013].
*   **PROCESS**:
    1.  **Analyze Satiation**: Map out the core "Opportunity Promises" made by legacy competitors. Show how these promises have created buyer cynicism.
    2.  **Construct the Scapegoat**: Identify the systemic "Villain" (e.g., traditional agencies, outdated billing, cosmetic focus) and shift the blame of the buyer's past failures from them to this system [NB-012].
    3.  **Aesthetic Reframe / Category Rebrand**: Design a contrarian positioning concept (e.g., "The Beauty Trap", "Aesthetic Brutalism") that establishes a high-status mental barrier [NB-008, NB-013].
    4.  **Term Branding Registry**: Invent 3 proprietary, trademarked names for the core operational mechanisms of the new category [NB-012].
*   **CONSTRAINTS**:
    *   Do not suggest incremental improvements (e.g., "we are 20% faster"). The reframe must represent a total structural shift [NB-013].
    *   Enforce a desaturated, high-status, minimalist tone.
*   **OUTPUT**: Category Design Manifesto, The System Scapegoat Script, and the Term Branding Registry.
*   **QUALITY CHECK**:
    *   [ ] **"Nobody Else Can Say It" Test**: Does the designed category rely on proprietary mechanisms that competitors cannot claim without citing you? [NB-009, NB-012]
    *   [ ] **Bleeding Neck Match**: Does the designed category address a high-priority "One Standard Deviation Away" pain point? [NB-012]

---

### 4. Offers Prompt: The B2B Productized Sprint & Grand Slam Offer Engineer

*   **ROLE**: Elite B2B Offer Architect, Value Equation Engineer, and Growth Consultant [NB-013, NB-015, NB-016].
*   **GOAL**: Deconstruct an open-ended, customized service or hourly-billing model and engineer it into an irresistible, fixed-scope B2B "Productized Sprint" [NB-013, NB-015].
*   **INPUTS**: Current service description, average delivery duration, pricing, and list of required client inputs.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Scale is achieved only by transforming open-ended services into productized sprints priced by client outcome, not input hours [NB-013].
    *   **[Source-Backed Fact]**: Alex Hormozi's Value Equation defines Value as: *(Dream Outcome * Likelihood) / (Time Delay * Effort & Sacrifice)* [NB-013, NB-015].
*   **PROCESS**:
    1.  **Deconstruct Current Value-to-Friction Ratio**: Map where the current offer forces excessive labor, long wait periods, or client decision-fatigue [NB-015, NB-018].
    2.  **Productize the Mechanism**: Package the delivery into a staccato "NERO Sprint" (e.g., 4-day installation) with a fixed scope and high-speed execution [NB-012, NB-013].
    3.  **Design the M-A-G-I-C Offer Name**: Wrap the offer name using the formula: *M (Magnetize), A (Agree on outcomes), G (Guarantee), I (Incentivize), C (Clear scarcity)* [Sales OS].
    4.  **Inject "God-Mode" Risk Reversal**: Craft a performance-linked or action-based refund guarantee to eliminate buyer hesitation [NB-013, NB-015].
*   **CONSTRAINTS**:
    *   Strictly ban any reference to "hourly rates," "custom retainers," or billable hours.
    *   All execution steps must prioritize shifting cognitive and physical labor off the client.
*   **OUTPUT**: Productized Sprint Specification Sheet, Hormone-Equation Breakdown, M-A-G-I-C Offer Package, and Risk-Reversal Wording.
*   **QUALITY CHECK**:
    *   [ ] **Denominator Leak Check**: Have we successfully reduced the client's effort, sacrifice, and time delay to near zero? [NB-015, NB-018]
    *   [ ] **Productization Audit**: Is the sprint fully standard, structured, and repeatable without custom scope-creep? [NB-013]

---

## PART II: COPYWRITING & HIGH-RETENTION CONTENT

### 5. Copy Prompt: The 5-Step PARIS Conversational Copy Engine

*   **ROLE**: Elite B2C Conversion Copywriter trained in dual-process behavioral conversion [NB-009, NB-012].
*   **GOAL**: Write persuasive, highly structured long-form landing page or ad body copy that appeals to subconscious emotion and validates with logic [NB-009].
*   **INPUTS**: Target Avatar, Brand/Product, Core Pain Point, Unique Mechanism.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: System 1 controls 95% of buying behavior. Use emotional "vibe coding" for System 1; use specifications solely to allow System 2 to logically defend the purchase [NB-008, NB-009, NB-013].
    *   **[Source-Backed Fact]**: The PARIS Framework represents the optimal structure for guiding analytical, skeptical, or high-ticket buyers [NB-009].
*   **PROCESS**:
    1.  **Problem (P)**: State the target customer's painful reality. Drill down to the raw emotional core of their daily struggle [NB-009].
    2.  **Agitate (A)**: Twist the knife. Explore the direct psychological, financial, and operational consequences if the problem remains unsolved [NB-009].
    3.  **Remind (R)**: Future-pace the uncompromised dream and their desired future self [NB-009].
    4.  **Interest (I)**: Satisfy the neocortex (System 2) by injecting a shocking, falsifiable statistic, clinical trial metric, or scientific fact [NB-009].
    5.  **Solution (S)**: Present the productized solution with transparent pricing, absolute risk-reversal, and a direct CTA [NB-009].
*   **CONSTRAINTS**:
    *   Apply the strict **15/3 constraint**: sentences < 15 words, paragraphs < 3 sentences [NB-012].
    *   Banish all fake, ungrounded authoritative jargon or fluffy promotional preambles [NB-021].
*   **OUTPUT**: Full direct-response copy block styled in clean Markdown with clear headings for each PARIS letter.
*   **QUALITY CHECK**:
    *   [ ] **Subconscious-to-Conscious Pivot**: Does the copy transition clearly from System 1 emotional resonance (P, A) to System 2 empirical data validation (I)? [NB-009, NB-013]
    *   [ ] **Flesch score check**: Ensure simple, clear, conversational reading complexity [NB-009].

---

### 6. Hooks Prompt: The 6-Word Dopamine-Triggered Hook Generator

*   **ROLE**: Performance Creative Director and Dopamine Engineer [NB-012].
*   **GOAL**: Construct 10 high-retention spoken video hooks that capture connected attention and act as a precise viewer filter [NB-001, NB-012].
*   **INPUTS**: Target Buyer Persona, Dream Outcome, Constraint-Free Timeline, Named Mechanism.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: The hook is a filter designed to capture the attention of a highly specific target demographic and weed out unqualified scrollers; clickbait hooks ruin CPA [NB-001, NB-005, NB-007, NB-012].
    *   **[Source-Backed Fact]**: The 6-Word Desire Hook System: `[Condition-Free Dream Outcome]` + `[Constraint-Free Timeline]` + `[The System / Vehicle]` [NB-012].
*   **PROCESS**:
    1.  **Draft Formula Hooks**: Generate 5 hooks using the exact 6-Word Desire Hook formula, ensuring the Dream Outcome is condition-free (e.g., *"scale without hiring SDRs"*) [NB-012].
    2.  **Draft Loss-Aversion Hooks**: Generate 5 hooks using a Negative Frame targeting their exact "Bleeding Neck" pain [NB-012].
    3.  **Develop Red & Green Bullets**: For each hook, write a staccato script visual layer (Red Bullet: physical camera action/angle, Green Bullet: editing overlay/sound effects) [NB-007, NB-012].
*   **CONSTRAINTS**:
    *   Spoken hook text must be under 15 words and completed in under 3 seconds [NB-012].
    *   Strictly ban generic greetings (e.g., *"What is up"*, *"Are you struggling with..."*).
*   **OUTPUT**: 10 Hook Scripts, each structured as: Spoken Hook, Red Bullet (Visual Setup), Green Bullet (Editor Blueprint).
*   **QUALITY CHECK**:
    *   [ ] **Visual-Audio Sandwich Check**: Does the visual action (Red Bullet) communicate the exact same concept as the spoken line in the first 3 seconds? [NB-012]
    *   [ ] **Condition-Free Compliance**: Does the dream outcome omit restrictive prerequisites to minimize initial friction? [NB-012]

---

### 7. Content Prompt: The "Systems-Over-Posts" Barbell Strategy Planner

*   **ROLE**: NEROZARB Content Systems Engineer and Behavioral Design Architect [NB-008, NB-013].
*   **GOAL**: Build a comprehensive 30-day "Systems-Over-Posts" Content Blueprint to drive mass exposure while cementing off-algorithm trust [NB-008, NB-013].
*   **INPUTS**: Core niche topic, primary customer avatar, target backend product.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Trust is a mathematical product of content minutes. Short-form reel metrics alone cannot convert cold prospects into high-ticket buyers [NB-012].
    *   **[Source-Backed Fact]**: The Barbell Content Strategy divides output between short-form mass reach ("world exposure") and long-form, newsletters, or private communities ("world immersion") [NB-012, NB-013].
*   **PROCESS**:
    1.  **Define Core Scapegoat**: Isolate the systemic failure or industry villain the buyer is running from [NB-012].
    2.  **Construct the 40/40/20 Idea Matrix**: Filter all content ideas into: Core (40% hyper-specific workflow pain), Inner (40% adjacent topics), and Outer (20% controlled chaos/manifestos) [NB-012].
    3.  **Map out the TOFU-MOFU-BOFU Distribution**:
        *   **TOFU (60% of Volume)**: Highly visual, pattern-interrupt short-form reels to capture reach.
        *   **MOFU (20% of Volume)**: Long-form, founder-led storytelling, newsletters, or case studies to build deep trust [NB-006, NB-008].
        *   **BOFU (20% of Volume)**: High-competence technical breakdowns linked to low-friction CTAs (e.g., *"DM the word 'SPRINT'"*) [NB-006, NB-008, NB-013].
*   **CONSTRAINTS**:
    *   Ban generic, trends-focused "infotainment" or dance reels. All short-form must focus on extreme, tactical usefulness [NB-012].
    *   Enforce a desaturated, high-status, minimalist aesthetic.
*   **OUTPUT**: A 30-Day Content Distribution Grid outlining [Day, Funnel Stage, Content Type, 40/40/20 Ring, Concept, Spoken Hook, CTA/ManyChat Trigger].
*   **QUALITY CHECK**:
    *   [ ] **Variety Show Avoidance**: Are all 30 days strictly locked onto a single, cohesive customer avatar and topic rather than fragmented niches? [NB-012]
    *   [ ] **Barbell Balance**: Is there a clear, programmatic bridge directing TOFU viral traffic to MOFU/BOFU world-immersion channels off-algorithm? [NB-012, NB-013]

---

## PART III: PAID MEDIA & CREATIVE STRATEGY

### 8. Paid Ads Prompt: The 3:2:2 Dynamic Creative Copy Constructor

*   **ROLE**: Performance Growth Architect and Direct-Response Copywriter specialized in Advantage+ Shopping Campaign optimization [NB-003, NB-004].
*   **GOAL**: Write the complete copywriting assets for a Charley Tichenor 3:2:2 Dynamic Creative Protocol test [NB-003].
*   **INPUTS**: Product name, primary customer pain points, unique named mechanism.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Post-iOS14, platform delivery algorithms act as the targeting engine; Rosetta subsystems scan on-screen text, audio, and captions to route the ad [NB-001, NB-003, NB-004, NB-005].
    *   **[Source-Backed Fact]**: Charley Tichenor's 3:2:2 Dynamic Creative Protocol utilizes: 3 visual assets, 2 primary texts, and 2 headlines inside a single ad unit [NB-003].
*   **PROCESS**:
    1.  **Primary Text A (The Mobile Skimmer)**: Craft a short, benefit-focused copy block strictly under 125 characters, optimized to avoid the "See More" truncation [NB-003].
    2.  **Primary Text B (The Storyteller)**: Craft a medium-length storytelling narrative that agitates a pain point and establishes your proprietary "Unique Mechanism" [NB-003, NB-013].
    3.  **Headline A (The Dream Outcome)**: Write a bold, high-contrast, benefit-driven headline [NB-003].
    4.  **Headline B (The Objection Crusher)**: Write an objection-crushing, question-based headline [NB-003, NB-004].
*   **CONSTRAINTS**:
    *   Strictly write copy at a 3rd-grade reading level to maximize processing fluency [NB-004, NB-009].
    *   No empty marketing puffery or buzzwords (*groundbreaking, leading, state-of-the-art*).
*   **OUTPUT**: The finalized 3:2:2 copy block (Primary Texts A & B, Headlines A & B) and recomended visual cues for the 3 ad concepts.
*   **QUALITY CHECK**:
    *   [ ] **Character Constraint Audit**: Is Primary Text A strictly under 125 characters with spacing? [NB-003]
    *   [ ] **Mechanism Specificity**: Does Primary Text B name a trademarked mechanism rather than a generic service description? [NB-012, NB-013]

---

### 9. Creative Strategy Prompt: The Visual Diversity & Format-Wrapper Architect

*   **ROLE**: Elite DTC Creative Strategist and Visual Performance Architect [NB-001, NB-007, NB-012].
*   **GOAL**: Map out a conceptual creative diversity testing matrix, unbundling a single winning message into 4 distinct visual wrappers [NB-004, NB-007].
*   **INPUTS**: Winning copywriting hook, core value proposition, product physical description.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Platform algorithms experience creative fatigue when minor variants are tested (lazy volume); scale requires testing completely diverse visual formats [NB-003, NB-004, NB-007].
    *   **[Source-Backed Fact]**: Creative diversity compliance is achieved by wrapping the same psychological trigger in divergent visual structures [NB-007].
*   **PROCESS**:
    1.  **Deconstruct the Message**: Isolate the core psychological trigger and target "Bleeding Neck" pain point [NB-012].
    2.  **Wrapper 1 (UGC Founder Story)**: Design a raw, low-production personal monologue outline focusing on the "Aha" moment.
    3.  **Wrapper 2 (Direct-Response VSSL)**: Map out a staccato, slide-based text video structure following the NERO Q.S.T.A structure [NB-012].
    4.  **Wrapper 3 (The Static Problem Grid)**: Design a high-contrast, desaturated "Us vs. Them" grid comparing your mechanism against legacy systems [NB-012, NB-013].
    5.  **Wrapper 4 (The Mixed-Format Carousel)**: Structure a multi-slide PDF/swipe post merging educational value with a before-after-bridge arc [NB-012, NB-013].
*   **CONSTRAINTS**:
    *   Ensure each wrapper has a distinct "Squint Test" signature (completely different color weights and focal points) [NB-001, NB-012].
    *   Every wrapper must feature at least one "Displacement" visual concept to halt the scroll [NB-013].
*   **OUTPUT**: A 4-Quadrant Creative Strategy Matrix detailing: Wrapper Type, Visual Aesthetic/Assets, Optical Lens/Camera Specs, and Script/Copy Outline.
*   **QUALITY CHECK**:
    *   [ ] **Squint Test Verification**: If you squint your eyes, do these 4 concepts look entirely different from each other in composition and color distribution? [NB-001, NB-012]
    *   [ ] **Friction Balance**: Does the proposed matrix unbundle "empty reach" from high-intent conversion hooks? [NB-001, NB-008]

---

## PART IV: SALES, DISCOVERY & HIGH-TICKET CLOSING

### 10. Sales Prompt: The High-Ticket Contract ACV-Routing Playbook Constructor

*   **ROLE**: High-Ticket Sales Architect, Closed Circuit Selling (CCS) Coach, and Deal Engineer [NB-014].
*   **GOAL**: Build a comprehensive sales playbook that programmatically routes sales methodology based on estimated Annual Contract Value (ACV) segments [NB-014].
*   **INPUTS**: High-ticket B2B service descriptions, target buyer committee details, average sales cycle timeline.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: High-ticket deals require distinct logical frameworks depending on commercial complexity and procurement friction [NB-014].
    *   **[Source-Backed Fact]**: Deal Value & Complexity Mapping defines the following conditional decision gates [NB-014]:
        *   *ACV < $20K*: BANT for rapid filtering + Sandler upfront contracts [NB-014].
        *   *ACV $20K - $100K*: SPIN Selling for implication-focused discovery [NB-014].
        *   *ACV $100K - $250K*: SPICED to align the customer bowtie (SDR -> AE -> CS) [NB-014].
        *   *ACV > $250K+*: MEDDPICC with rigorous stakeholder matrices [NB-014].
*   **PROCESS**:
    1.  **Build the ACV Decision Matrix**: Detail the operational steps, key metrics, and disqualification thresholds for each of the four segments [NB-014].
    2.  **Formulate Segment Playbooks**: Draft specific playbooks for each segment, outlining the exact qualification/discovery process to run.
    3.  **Define Stakeholder Alignment SOPs**: Map out how to coordinate and align the sales reps, account executives, and client success managers under Closed Circuit Selling [NB-014].
*   **CONSTRAINTS**:
    *   Avoid any "one-size-fits-all" sales advice. Strictly enforce the conditional ACV gates [NB-014].
    *   Write scripts in a direct, authoritative, consultative tone.
*   **OUTPUT**: High-Ticket Sales Playbook featuring the ACV Routing Decision Matrix, Segmented Qualification Scripts, and Stakeholder Mapping Sheets.
*   **QUALITY CHECK**:
    *   [ ] **Disqualification Check**: Do the playbooks feature explicit conditional gates to disqualify low-urgency or non-fit prospects? [NB-014]
    *   [ ] **Sandler Alignment**: Ensure every contract value playbook opens with a firm Up-Front Contract [NB-014].

---

### 11. Lead Research Prompt: The Signal-Based B2B Prospect Mining SOP Generator

*   **ROLE**: Lead Generation Systems Architect and Programmatic B2B Researcher [NB-018].
*   **GOAL**: Build a rigorous lead research standard operating procedure (SOP) that extracts high-intent trigger signals and maps them to operational gaps [NB-018].
*   **INPUTS**: Target industry, lists of target executive job titles, and common high-signal platform data sources.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Outbound scale requires transforming generic, low-conversion prospecting into precise, signal-based account mining to protect domain reputation [NB-018].
    *   **[Source-Backed Fact]**: High-signal B2B prospecting relies on locating real-time trigger events (e.g., specific job hires, new software adoption, capital funding) [NB-018].
*   **PROCESS**:
    1.  **Define Trigger Signals**: Identify the top 5 high-intent trigger events for B2B accounts.
    2.  **Map Trigger to Bottleneck**: For each trigger, outline the exact Level 3-4 operational bottleneck it implies [NB-018].
    3.  **Formulate Ingestion SOP**: Write the step-by-step procedure for utilizing tools (such as Clay, Apollo) to programmatically sift and verify these signals [NB-018, SOP 11.1].
    4.  **Draft Sifting Disqualification Gates**: Establish the exact conditional criteria to disqualify leads (e.g., revenue < threshold, missing tracking pixels) [NB-014].
*   **CONSTRAINTS**:
    *   Strictly ban the compilation of unsegmented, raw list-scraping without trigger-event criteria.
    *   All instructions must be written as clear, numbered SOP steps.
*   **OUTPUT**: Inbound/Outbound Lead Research SOP, Trigger-to-Bottleneck Mapping Table, and the Disqualification Gates.
*   **QUALITY CHECK**:
    *   [ ] **Verifiability Rules**: Does the SOP require verification steps to ensure triggers are recent (<30 days)? [NB-018]
    *   [ ] **Relevance Alignment**: Does every identified trigger link logically to the specific business problem the agency solves? [NB-018, NB-019]

---

### 12. Personalization Prompt: The Level 4/5 "Leaky Bucket" Hypothesis Architect

*   **ROLE**: High-Ticket Personalization Strategist and B2B Conversion Architect [NB-018].
*   **GOAL**: Write a Level 4 (Economic Insight) or Level 5 (Validated Hypothesis) personalization snippet that maps an account trigger to a business bottleneck [NB-018].
*   **INPUTS**: Target Company Name, Website Tech Stack, Public Job Openings, Target executive title.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Outreach copywriting is graded strictly based on verified context; Level 1-2 generic company observations (e.g., *"saw you are based in Lahore"*) are flagged as spam by ESPs [NB-018].
    *   **[Source-Backed Fact]**: Level 4/5 personalization links a real-time trigger to the systemic opportunity cost or hidden failure modes of that bottleneck (the "Leaky Bucket" model) [NB-018].
*   **PROCESS**:
    1.  **Analyze Lead Signal**: Review the provided company data and isolate the highest-intent trigger.
    2.  **Formulate the Economic Leak Hypothesis**: Deduce what operational bottleneck occurs from this trigger (e.g., *"Hiring 3 Account Executives usually leads to manual prospecting, burning domain reputation and risking a 15-20% drop in deliverability..."*) [NB-018].
    3.  **Draft a Socratic Hook**: Construct a staccato, conversational opening line strictly under 30 words in a low-pressure, lowercase voice [NB-012, NB-018].
*   **CONSTRAINTS**:
    *   The personalization snippet must be written strictly in lowercase, warm, and highly casual phrasing [NB-012, NB-018].
    *   Do NOT include sycophantic compliments or fake flattery (*"Congrats on the amazing growth!"*).
*   **OUTPUT**: A desaturated Markdown table listing: Company, Trigger, Bottleneck, Level 4/5 Snippet, and matching Socratic Question.
*   **QUALITY CHECK**:
    *   [ ] **Invasiveness Check**: Is the observation business-relevant, or does it cross into creepy, non-professional details? [NB-018]
    *   [ ] **Word Count Audit**: Is the final personalization snippet under 35 words? [NB-018]

---

### 13. Cold Email Prompt: The 100-Word Plain-Text Socratic Email Constructor

*   **ROLE**: Direct-Response Outreach Copywriter and Deliverability Engineer [NB-018].
*   **GOAL**: Write a highly-converting, 3-step cold email sequence restricted strictly under 100 words per email, using the D.I.C. framework [NB-009, NB-018].
*   **INPUTS**: Target Avatar, Unique Named Mechanism, Target Offer, Level 4/5 Personalization Snippet.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Email ESPs screen for corporate pitch-deck language. Outreach emails must be formatted as raw, plain-text human copy restricted under 100 words to maximize deliverability [NB-018].
    *   **[Source-Backed Fact]**: The D.I.C. Framework (Disrupt, Intrigue, Click) is designed solely to sell the "click" or active reply, never the final offer [NB-009].
*   **PROCESS**:
    1.  **Step 1 (The Socratic Opener)**: Disrupt autopilot thinking with a pattern-interrupt subject line. Open directly with the Level 4/5 personalization hook, followed by a Socratic, open-ended question [NB-009, NB-018].
    2.  **Step 2 (The Value Drop)**: Send a follow-up sharing a highly specific, ungated case study or asset proving NEROZARB's named mechanism [NB-018].
    3.  **Step 3 (The Low-Friction Close)**: Construct a frictionless CTA that invites open dialogue over forcing a scheduled meeting calendar link [NB-018].
*   **CONSTRAINTS**:
    *   Every email must remain strictly under 100 words [NB-018].
    *   Write copy strictly in lowercase, unformatted, plain-text voiceover styling [NB-012, NB-018].
    *   No attachments, no marketing links, and zero corporate buzzwords.
*   **OUTPUT**: 3-Step Cold Email Sequence featuring Subject Lines, Word Counts, and Body Copy.
*   **QUALITY CHECK**:
    *   [ ] **Word Count Audit**: Is each email body strictly under 100 words? [NB-018]
    *   [ ] **Spam Trigger Check**: Ensure zero occurrences of sales-pitch triggers (*"buy now," "free call," "guarantee"*).
    *   [ ] **D.I.C. Check**: Does the email solely focus on selling the reply rather than pitching the entire backend? [NB-009]

---

### 14. LinkedIn Prompt: The 6-Step Multi-Channel Wrapping Sequence Architect

*   **ROLE**: B2B LinkedIn Social Selling Director and Account-Based Marketing (ABM) Expert [NB-018].
*   **GOAL**: Draft connection requests and Socratic follow-up messages for a highly coordinated 6-step Social Selling Sequence [NB-018].
*   **INPUTS**: Target Executive Bio, Company Domain, Operational Pain Points, Socratic Opener.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: LinkedIn connection acceptance: Blank requests achieve slightly higher acceptance rates (27.6%) than noted requests (25.3%), but noted requests achieve higher reply rates (8.2%) than blank ones (5.3%) [NB-018].
    *   **[Source-Backed Fact]**: To protect account standing, LinkedIn outbound must operate strictly under heyReach cloud orchestration with pacing limited under 100 invitations per week [NB-018].
*   **PROCESS**:
    1.  **Day -1 (Pre-Engagement)**: Draft a high-value, specific comment to leave on the prospect's recent LinkedIn post 1 day prior to connection [NB-018].
    2.  **Day 1 (Connection request)**: Construct a personalized connection request note strictly under 200 characters, referencing a specific trigger (no sales pitches) [NB-018].
    3.  **Day 2 (Socratic Opener)**: Draft a short 2-4 line follow-up message containing an open-ended question about their GTM model [NB-018].
    4.  **Day 5 (Value Drop)**: Share a helpful, ungated resource proving competence [NB-018].
*   **CONSTRAINTS**:
    *   Connection requests must strictly be under 200 characters to prevent mobile truncation.
    *   No sales pitches or calendar booking links allowed in the sequence.
*   **OUTPUT**: 6-Step LinkedIn Sequence touchpoints (Comment, Connection Request, Opener, Value Drop, Follow-up scripts).
*   **QUALITY CHECK**:
    *   [ ] **Pacing Compliance**: Does the SOP enforce the <100 weekly invite ceiling to protect account safety? [NB-018]
    *   [ ] **Socratic Quality**: Does the opener ask an intellectually engaging question rather than a disguised sales pitch? [NB-018]

---

### 15. Discovery Prompt: The 5-Phase Diagnostic Discovery Script Architect

*   **ROLE**: Clinical B2B Discovery Specialist and Sandler Up-Front Contract Engineer [NB-014].
*   **GOAL**: Build a highly structured, 5-phase diagnostic discovery call script that uncovers financial and operational pain while establishing absolute equal status [NB-014].
*   **INPUTS**: High-Ticket B2B Offer, Target Buyer Persona, Typical baseline metrics.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: The high-ticket discovery call is the structural heart of sales, designed to qualify or disqualify the deal by mapping the commercial gap [NB-014].
    *   **[Source-Backed Fact]**: The 5-Phase Discovery Call Structure consists of: Up-Front Contract (Phase 1), Current State Mapping (Phase 2), SPIN Diagnostic (Phase 3), Need-Payoff State (Phase 4), Decision Engineering (Phase 5) [NB-014].
*   **PROCESS**:
    1.  **Phase 1 (The Sandler UFC Script)**: Draft the exact verbal script for the Sandler Upfront Contract, establishing mutual agreement to say "No" and disqualify early [NB-014].
    2.  **Phase 2 (Current State Map)**: Formulate 3 diagnostic inquiries mapping acquisition metrics and operational ownership [NB-014].
    3.  **Phase 3 (SPIN Implication Diagnostic)**: Construct SPIN-aligned problem and implication inquiries to amplify the financial cost of inaction [NB-014].
    4.  **Phase 4 (Need-Payoff)**: Draft inquiries prompting the buyer to vocalize the bottom-line revenue impact of resolving the bottleneck [NB-014].
    5.  **Phase 5 (Decision Engineering)**: Construct stakeholder and procurement alignment inquiries [NB-014].
*   **CONSTRAINTS**:
    *   Strictly ban submissive or pleasing sales language. Reps must maintain a high-status "consultative physician" posture.
*   **OUTPUT**: Full 5-Phase Discovery Playbook featuring verbatim verbal scripts and transition markers.
*   **QUALITY CHECK**:
    *   [ ] **Sandler Agreement Check**: Does the UFC script explicitly invite the prospect to say "No" if there is no clear alignment? [NB-014]
    *   [ ] **SPIN Progression**: Do the Phase 3 questions explicitly force the prospect to calculate the financial cost of leaving the problem unsolved? [NB-014]

---

### 16. Objections Prompt: The Non-Combative Objection-Handling Accusation Audit Matrix

*   **ROLE**: High-Ticket Objections Diagnostician and Tactical Empathy Specialist [NB-014].
*   **GOAL**: Construct a highly responsive, non-combative objection-handling script matrix utilizing Accusation Audits, Labels, Mirrors, and the JOLT method [NB-014].
*   **INPUTS**: High-ticket B2B service, primary buyer objections (e.g., *"We manage in-house,"* *"Too expensive,"* *"Tried this before"*).
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: High-ticket sales are lost to indecision (40-60%) caused by buyer fear of failure; the JOLT method overcomes this by judging indecision and taking risk off [NB-014].
    *   **[Source-Backed Fact]**: Chris Voss's Tactical Empathy uses Labels and Accusation Audits to proactively neutralize emotional barriers before they arise [NB-014].
*   **PROCESS**:
    1.  **Draft the Accusation Audit**: Construct a pre-emptive script statement neutralizing buyer skepticism before presenting.
    2.  **Develop Voss-Style Labels**: Formulate 3 distinct labels (e.g., *"It seems like you've had prior agency trauma..."*) for the core objections [NB-014].
    3.  **Formulate Mirror Questions**: Create staccato mirrors repeating the prospect's critical words to invite deeper elaboration [NB-014].
    4.  **Inject JOLT Resolution**: Apply J (Judge Indecision), O (Offer Recommendation), L (Limit Options), and T (Take Risk Off) to neutralize risk-aversion [NB-014].
*   **CONSTRAINTS**:
    *   **Zero Discounting Rule**: Do not offer prices cuts; if price objections arise, execute the Sandler/Belfort Step-Down Card Matrix [Sales OS].
*   **OUTPUT**: High-Ticket Objection Handling Playbook structured as a Markdown Matrix of: [Objection, Root Cause, Accusation Audit, Voss Label, Mirror, JOLT Action].
*   **QUALITY CHECK**:
    *   [ ] **Defensiveness Check**: Ensure none of the responses argue with or validate the objection combatively.
    *   [ ] **JOLT Alignment**: Does the "T (Take Risk Off)" column introduce robust, performance-linked risk-reversals? [NB-014]

---

### 17. Closing Prompt: The Three Tens Zoom Close Screen-Share Script Constructor

*   **ROLE**: Straight Line Closer, Deal Engineer, and Sales Coach [NB-014].
*   **GOAL**: Construct a transition-to-close Zoom screen-share script designed to audit and lock Jordan Belfort's Three Tens [NB-014].
*   **INPUTS**: Stacked Grand Slam Offer, pricing plans, client core pain points mapped during discovery.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: High-ticket closing requires the prospect to simultaneously reach a 10/10 certainty score on: (1) The Product/Mechanism, (2) The Seller/Expert, and (3) The Company [NB-014].
    *   **[Source-Backed Fact]**: The "Down-Payment Close" secures financial commitment and immediate skin in the game while protecting rep time [NB-014].
*   **PROCESS**:
    1.  **Transition to Screen Share**: Draft the staccato verbal transition prompting the prospect to view the proposal deck.
    2.  **Audit the Three Tens**: Formulate calibrated questions (Voss-aligned) to assess their certainty score on the mechanism and company [NB-014].
    3.  **The "Down-Payment Close" Script**: Draft the exact closing script to secure immediate, non-refundable down-payments [NB-014].
    4.  **The First 48-Hour Reinforcement SOP**: Write the staccato instructions to eliminate buyer's remorse immediately post-close [NB-014].
*   **CONSTRAINTS**:
    *   Avoid the "milestone payment trap" — enforce standard upfront deposits or phased structured billing.
*   **OUTPUT**: Zoom Proposal Transition Script, Three Tens Audit Inquiries, Down-Payment Close Script, and Post-Close Client Reinforcement SOP.
*   **QUALITY CHECK**:
    *   [ ] **Remorse Elimination Check**: Does the post-close SOP trigger a high-value onboarding touchpoint in under 2 hours? [NB-014]
    *   [ ] **Zero Discounting compliance**: Ensure pricing transitions rely strictly on the Step-Down Card Matrix rather than direct discounting.

---

## PART V: COMPUTER CINEMATOGRAPHY & MEDIA GENERATION

### 18. Image Prompt: The Layered Physics-Grounded Photographic Asset Constructor

*   **ROLE**: Computational Cinematographer, Physics-Grounded Material Shader, and Expert Studio Lighting Designer [NB-027].
*   **GOAL**: Compile a highly detailed, machine-native text prompt for static image models (Flux Pro / Flux 1.1) to eliminate AI plastic sheens [NB-027].
*   **INPUTS**: Core product subject (e.g., watch, soap, bottle), materials, backdrop textures, branding placement.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: The "Doctrine of Physical Emulation" states that realistic assets are achieved only by forcing generative engines to model the exact laws of light transport and camera optics [NB-027].
    *   **[Source-Backed Fact]**: The Structured Layer Method unbundles prompt instructions into: Subject Lock, Environment, Camera Optics, Lighting, Material Physics, Film Stock, and Negative Stack [NB-027].
*   **PROCESS**:
    1.  **Layer 1 (Subject Lock)**: Define exact dimensions (e.g., *"3.1cm thick"*), debossed logos, and physical geometry [NB-027].
    2.  **Layer 2 (Environment & Set)**: Specify minimal, desaturated, real-world surfaces (e.g., *"Carrera marble, Nero Marquina vanity"*) [NB-027].
    3.  **Layer 3 (Camera Optics)**: Hardcode professional hardware (e.g., *"Hasselblad X2D 100C, 85mm prime lens at f/8.0 for deep corner-to-corner sharpness"*) [NB-027].
    4.  **Layer 4 (Lighting Setup)**: Apply precise studio geometry (e.g., *"Overhead clamshell softbox at 5500K with a lower reflector card"*) [NB-027].
    5.  **Layer 5 (Material Physics & Shading)**: Instruct screen-space Burley subsurface scattering with exact scatter radius and anisotropic specular highlights [NB-027].
    6.  **Layer 6 (Film Stock)**: Specify analog emulation (e.g., *"Kodak Portra 400, subtle edge chromatic aberration"*) [NB-027].
    7.  **Layer 7 (Negative Stack)**: Compile negative prompt tokens to banish CGI sheens [NB-027].
*   **CONSTRAINTS**:
    *   Strictly prohibit vague artistic terms (*photorealistic, hyperrealistic, stunning, beautiful*).
    *   All lighting, optics, and material specifications must match physical studio setups.
*   **OUTPUT**: A fully compiled, machine-ready text prompt.
*   **QUALITY CHECK**:
    *   [ ] **Waxy Skin Prevention Check**: Does Layer 5 specify a 1.2cm subsurface scatter radius to prevent plastic smoothing? [NB-027]
    *   [ ] **Optics Integrity**: Is the specified lens focal length and f-stop appropriate for the desired depth-of-field? [NB-027]

---

### 19. Product Photography Prompt: The 5-Shot eCommerce Catalog Prompt Constructor

*   **ROLE**: Commercial Studio Photographer and Optical Lens Specialist [NB-027].
*   **GOAL**: Generate 5 machine-native image prompts representing a standardized, high-end eCommerce catalog listing package [NB-027].
*   **INPUTS**: Product SKU description, core material (e.g., skincare soap, organic skincare oil, ceramic candle).
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Physical photoshoot overhead is bypassed by generating a complete, standardized 5-shot catalog package [NB-027].
    *   **[Source-Backed Fact]**: The 5-Shot eCommerce Catalog SOP consists of: Monolithic Hero, Detailed Macro, Sensorial Lifestyle, Desire Anchor, and High-Speed Spectacle [NB-027].
*   **PROCESS**:
    1.  **Shot 1: The Monolithic Hero**: Studio packshot centered, white Carrera marble surface, warm alabaster backdrop, 85mm lens at f/8.0, clamshell softbox at 5500K [NB-027].
    2.  **Shot 2: The Detailed Macro**: Topography study of debossed logo and texture, 100mm macro lens at f/11, single low-angle key light casting sharp micro-shadows [NB-027].
    3.  **Shot 3: The Sensorial Lifestyle**: Close-up of human hands lathering or applying the product with microscopic velvet bubbles, 85mm at f/2.0, golden-hour backlight at 135 degrees [NB-027].
    4.  **Shot 4: The Desire Anchor**: Product placed on asymmetrical black obsidian inside a luxury vanity, soft-focus background, golden-hour window light, 50mm anamorphic lens [NB-027].
    5.  **Shot 5: The High-Speed Spectacle**: High-speed splash frozen in time, dropping into water, crown-shaped splash, 100mm macro at f/2.8, 1/8000s shutter speed, rim lighting refraction [NB-027].
*   **CONSTRAINTS**:
    *   Do not allow any waxy AI smoothing or plastic sheens.
    *   Every shot description must hardcode the exact optical lens, f-stop, lighting color temperature, and surface textures of the SOP.
*   **OUTPUT**: 5 Machine-Native Photographic Prompts (Shot 1 to Shot 5).
*   **QUALITY CHECK**:
    *   [ ] **Lens/Aperture Check**: Does Shot 2 macro specify f/11 for deep focus, and Shot 3 specify f/2.0 for shallow, creamy separation? [NB-027]
    *   [ ] **Refraction & Liquid Dynamics**: Does Shot 5 specify 1/8000s shutter and 180-degree rim lighting refraction? [NB-027]

---

### 20. Storyboard Prompt: The Bottom-Up Cinematic Storyboard Sequence Director

*   **ROLE**: Cinematic AI Director and Visual Semiotics Specialist [NB-022, NB-027].
*   **GOAL**: Deconstruct a vertical short-form script into a 4-beat visual storyboard sequence optimized for bottoms-up visual processing [NB-012, NB-022, NB-027].
*   **INPUTS**: Completed 30-second vertical script, target emotional trajectory, and product details.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Visual bottom-up processing (motion, contrast, lighting) occurs in under 200ms, long before the conscious neocortex comprehends text or audio [NB-012, NB-013].
    *   **[Source-Backed Fact]**: Camera Angle Power Dynamics: Low Angle = Dominant/Aspirational subject; High Angle = Vulnerable/Observed subject; Eye Level = Equality/Honesty [NB-022, NB-027].
*   **PROCESS**:
    1.  **Define Visual Starting Frame (Beat 1)**: Design a high-contrast visual pattern interrupt that halts the zombie-scroll in under 2.5 seconds [NB-012, NB-013].
    2.  **Apply Angle Selection gates**: Select the optical camera angles (Low, High, Eye-Level) based on the psychological power dynamics of each script beat [NB-022, NB-027].
    3.  **Apply Cinematic Motion gates**: Map movement trajectories (Dolly Push-In = Intimacy/Focus; Dolly Pull-Out = Isolation/Reveal; Orbit = Separation) [NB-022, NB-027].
    4.  **Inject Environmental Kinetics**: Add ongoing kinetics (steam, water droplets, dust) to satisfy the physics engine [NB-025].
*   **CONSTRAINTS**:
    *   Maintain strict single-axis camera movements (no complex, unnatural multi-axis fly-throughs) [NB-025].
    *   Adhere to the **30-Degree Rule** to prevent glitchy cuts between consecutive scenes [NB-022, NB-027].
*   **OUTPUT**: A 4-Beat Storyboard Table detailing: [Beat #, Time Window, Visual Action & Subject, Optical Angle & Movement, Specular Lighting, Audio/SFX Track].
*   **QUALITY CHECK**:
    *   [ ] **Scroll-Stop Validation**: Does Beat 1 (0:00 - 0:02) feature a clear visual pattern interrupt to arrest bottoms-up visual processing? [NB-012, NB-013]
    *   [ ] **Motion Physics**: Ensure all camera motion remains restricted along a single geometric axis [NB-025].

---

### 21. Video Prompt: The Single-Axis Physical Motion Frame Locking Prompt

*   **ROLE**: Master AI Cinematographer and Physical Motion Director [NB-025, NB-026].
*   **GOAL**: Construct high-fidelity video generation prompts for image-to-video generators (Kling, Luma, Runway Gen-3) with strict temporal and physical motion stability [NB-025].
*   **INPUTS**: High-quality static starting image, target motion description, required camera speed.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: The defining dichotomy of AI video is "Beautiful Frame" vs. "Usable Sequence" [NB-025].
    *   **[Source-Backed Fact]**: Temporal continuity is achieved by suppressing fast multi-axis motions and prioritizing continuous environmental kinetics (smoke, dust, liquid sliding) [NB-025].
*   **PROCESS**:
    1.  **Optical Conservation**: Restrict camera movement to a single-axis linear dolly or slow pan [NB-025].
    2.  **Environmental Dominance**: Enforce a rigid, stationary subject while injecting fluid kinetics to prevent morphing or melting [NB-025].
    3.  **Film Stock Calibration**: Emulate professional cinema parameters (e.g., *"35mm anamorphic, 180-degree physical shutter speed to ensure natural motion blur"*) [NB-025].
    4.  **Bake the Negative Stack**: Formulate precise negative keywords to prevent typical video defects (gummy-bear melts, geometry morphing, text splatter) [NB-025].
*   **CONSTRAINTS**:
    *   **Decoupled Typography**: Never instruct the rendering of text, spelling, or logo frames; generate clean visual plates only [NB-025].
    *   Strictly ban rapid transitions, camera rotations, or multi-axis movements in the prompt.
*   **OUTPUT**: Staccato Video Prompts for Kling/Runway Gen-3 and accompanying generation parameters.
*   **QUALITY CHECK**:
    *   [ ] **Single-Axis Audit**: Is the camera motion locked entirely to a single geometric plane (e.g., linear horizontal dolly slider)? [NB-025]
    *   [ ] **Fluid Kinetic Check**: Does the prompt describe natural liquid behavior conforming to gravity and surface tension? [NB-025, NB-026]

---

### 22. Veo Prompt: The Machine-Native JSON Video Physics Director

*   **ROLE**: Google Veo 3.1 Cinematic Director and JSON Physics Architect [NB-025, NB-027].
*   **GOAL**: Construct a highly-engineered, machine-native JSON-formatted video generation prompt for Google Veo 3.1 to eliminate geometric warping [NB-025].
*   **INPUTS**: Subject setup, backdrop environment, camera optics, lighting configuration, material shading specs.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Google Veo 3.1 responds with extreme deterministic accuracy when prompted using structured, machine-native JSON-first syntax [NB-025].
    *   **[Source-Backed Fact]**: Physics-based motion stability requires decoupling subject physics from camera motion to prevent "geometric melting" [NB-025].
*   **PROCESS**:
    1.  **Scene & Subject Setup**: Define the rigid subject with millimeter-scale geometry [NB-025, NB-027].
    2.  **Camera & Optics**: Hardcode physical lens parameters (e.g., *"35mm premium anamorphic lens"*) and single-axis Dolly Pan tracking [NB-025].
    3.  **Lighting & Specular Shading**: Define volumetric studio key light positions and real-time moving specular highlights on material edges [NB-025, NB-027].
    4.  **Fluid Physics Logic**: Script realistic, gravity-conforming liquid actions (e.g., *"coffee-tinted droplet lather slowly sliding down"* with *no motion blur* on drops) [NB-025, NB-026, NB-027].
    5.  **Environmental Kinetics & SFX**: Inject volumetric steam rising and deep sub-bass sound design parameters [NB-025].
*   **CONSTRAINTS**:
    *   Output must be structured as a strictly valid, parseable JSON block.
    *   No on-screen spelling, text rendering, or morphing.
*   **OUTPUT**: Fully structured Google Veo 3.1 JSON Prompt Block.
*   **QUALITY CHECK**:
    *   [ ] **JSON Validation**: Ensure the prompt parses cleanly as JSON.
    *   [ ] **Decoupled Typography Check**: Does the JSON contain explicit parameters to banish spelling or text rendering in the video? [NB-025]

---

## PART VI: PROMPT ENGINEERING & QUALITY ASSURANCE

### 23. Gemini Prompt: The Anti-Context-Drift Recursive Gem Configurator

*   **ROLE**: Lead AI Systems Engineer, Gemini Prompt Architect, and GEO Specialist [NB-009, NB-023].
*   **GOAL**: Set up a robust, custom Gemini Gem or Opal System Prompt with recursive context gates to prevent context drift and hallucination [NB-023].
*   **INPUTS**: Agent Role, Core Domain, Target SOPs to execute, Operational Constraints.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: Custom Gems and LLM agents experience context drift, "Empty Brain" errors, and "Kitchen Sink" overstuffing when not strictly constrained [NB-023].
    *   **[Synthesis/Inference]**: Hardcoding a programmatic verification queue and strict behavioral guardrails directly into the agent's system prompt reduces required human revision loops by an average of 40% [NB-009, NB-023].
*   **PROCESS**:
    1.  **Define Core Identity**: Establish a highly specialized, physics-grounded or behavioral-design persona [NB-008, NB-027].
    2.  **Hardcode the SOP Pipeline**: Program a linear, step-by-step task execution protocol, forcing the agent to complete each step before proceeding [NB-012, NB-023].
    3.  **Inject the Verification Queue**: Build a mandatory pre-publishing checkpoint requiring the model to run its own quality rubrics [NB-023].
*   **CONSTRAINTS**:
    *   Strictly ban the generation of conversational filler (*"Sure, I can help with that!"*, *"Based on my sources..."*).
    *   Banish the 10 forbidden buzzwords [NB-021].
*   **OUTPUT**: The finalized System Prompt designed for Gemini Gems / Opal custom workflows.
*   **QUALITY CHECK**:
    *   [ ] **No Filler Check**: Does the prompt include strict negative constraints to prevent introductory conversational fluff? [NB-021, NB-023]
    *   [ ] **SOP Linearity**: Are the execution steps linear, sequential, and gated? [NB-023]

---

### 24. Critique and QA Prompt: The 30-Point Art-Direction & Copy QA Auditor

*   **ROLE**: Senior Art Director and Creative Director specialized in Luxury Visual Semiotics [NB-009, NB-012, NB-022, NB-027].
*   **GOAL**: Run a comprehensive Art Direction and Copywriting QA Audit on generated visual assets and written collateral [NB-009, NB-022].
*   **INPUTS**: Draft ad copy, script, static image prompt, or video link.
*   **CONTEXT**:
    *   **[Source-Backed Fact]**: High-end brand status is protected only by enforcing rigorous visual desaturation, aggressive minimalism, and precise optical physics [NB-012, NB-022, NB-027].
    *   **[Source-Backed Fact]**: Visual and copy critique is processed under strict, score-based gateways: below 20 = REJECT; 20-25 = REVISE; 25+ = PUBLISH [NB-022].
*   **PROCESS**:
    1.  **Composition Audit (1-10 pts)**: Grade lighting stability, grid alignment, Rule of Thirds, and tactile material specificity. Identify flat washes or impossible optics [NB-022, NB-027].
    2.  **Effectivity Audit (1-10 pts)**: Audit if the asset has a single focal point (covering 45-65% of the frame) and halts zombie-scroll behavior in under 2.5 seconds [NB-012, NB-022, NB-027].
    3.  **Vibes Audit (1-10 pts)**: Grade visual desaturation, luxury desaturation, and "aura" [NB-012, NB-022].
    4.  **Run 3-Question Copy Discipline**: Test copy against: (A) Can the reader actively visualize it? (B) Is it verifiably falsifiable? (C) Does it rely on our proprietary named mechanism? [NB-009, NB-012]
*   **CONSTRAINTS**:
    *   Deliver audit scores strictly in a desaturated, high-status Markdown table [NB-021, NB-022].
    *   Do NOT allow any "close-enough" approvals; any score under 25 must trigger staccato corrective copy/prompt prescriptions.
*   **OUTPUT**: High-Density Audit Table, Scoring Breakdown, and Rewrite Prescriptions.
*   **QUALITY CHECK**:
    *   [ ] **Scoring Gateways Compliance**: Does the prompt enforce the mandatory reject/revise thresholds? [NB-022]
    *   [ ] **Falsifiability Check**: Are the corrective copy prescriptions verifiably falsifiable and written under the 15/3 constraint? [NB-009, NB-012]

---

## PART VII: TECHNICAL BENCHMARKS, CONSTRAINTS & FAILURE MODES

To ensure maximum alignment and performance, the following technical indexes must be hardcoded into the execution logic of all prompts in this library:

### 1. Hard Copywriting Metrics & Constraints:
*   **95%**: Subconscious mind purchasing decision threshold [NB-008, NB-009].
*   **500,000x**: Subconscious visual processing speed multiplier versus neocortex text comprehension [NB-009].
*   **2.5 Seconds**: Scroll-stop engagement window [NB-009, NB-012].
*   **10 Words**: Maximum allowed sentence length for high-status social copywriting [NB-011].
*   **15/3 Constraint**: Sentences must be under 15 words; paragraphs must not exceed 3 sentences [NB-012].
*   **Flesch score (60-80)**: Mandatory readability range [NB-009].

### 2. Digital Distribution & Paid Media Benchmarks:
*   **29% CPA reduction**: Advantage+ Shopping Campaigns with 20+ creatives [NB-001].
*   **3x LinkedIn Engagement**: Document carousel posts (12.3% average engagement vs. 3.1% text-only) [NB-013].
*   **30%-50% Reach Penalty**: Triggered by external outbound links on platforms [NB-013].
*   **34.5% CTR Drop**: Organic blue links when Google AI Overview is present [NB-013].
*   **7-11-4 Rule**: 7 hours of content, across 11 touchpoints, in 4 formats prior to high-ticket conversion [NB-011, NB-012].
*   **70%-90% VVSA Rate**: Viewed-vs-Swiped-Away rate for short-form recommendation feed seeding [NB-002].

### 3. outbound & LinkedIn Pacing Limits:
*   **100 invites/week**: Maximum connection invitations limit for HeyReach static IP accounts [NB-018].
*   **10.3% reply rate**: Average LinkedIn ABM outreach reply rate [NB-018].
*   **3.43% reply rate**: Average Cold Email outreach reply rate [NB-018].

### 4. Banned Corporate Jargon List:
`leverage`, `ecosystem`, `landscape`, `navigate`, `delve`, `testament`, `pivotal`, `transformative`, `groundbreaking`, `vibrant`, `foster`, `showcase` [NB-021].

---

## SYSTEM INDEX & EVIDENCE REGISTRY

This section serves as the trace map of grounding sources for every prompt architecture engineered in this library:

*   **Research & Strategy (Prompts 1, 2, 3)**: Grounded in VOC mining SOPs [NB-001, NB-009], cognitive load theories [NB-008, NB-009], Schwartz's market sophistication [NB-013], and category design principles [NB-013].
*   **Offers & Copywriting (Prompts 4, 5, 6, 7)**: Grounded in Alex Hormozi's Value Equation [NB-013, NB-015], the 6-Level Dopamine Ladder [NB-012], the 4-Step Neuro-Storytelling Addiction Loop [NB-012], the 6-Word Desire Hook System [NB-012], and the PARIS Framework [NB-009].
*   **Paid Media & Creative (Prompts 8, 9)**: Grounded in Charley Tichenor's 3:2:2 Dynamic Creative Protocol [NB-003], Advantage+ performance benchmarks [NB-001], and Fraser Cottrell's Fraggle performance wrappers [NB-007].
*   **Sales & Outbound (Prompts 10, 11, 12, 13, 14)**: Grounded in Deal Value & Complexity Mapping [NB-014], the 6-Level Personalization Engine [NB-018], domain isolation SOPs [NB-018], and LinkedIn ABM sequence metrics [NB-018].
*   **Discovery, Objections & Closing (Prompts 15, 16, 17)**: Grounded in the 5-Phase Discovery Call System [NB-014], Chris Voss's Tactical Empathy [NB-014], Jordan Belfort's Three Tens [NB-014], and the JOLT Method [NB-014].
*   **AI Media Generation (Prompts 18, 19, 20, 21, 22)**: Grounded in the "Doctrine of Physical Emulation" [NB-027], the Structured Layer Method [NB-027], the 5-Shot eCommerce Catalog SOP [NB-027], camera angle power dynamics [NB-022, NB-027], single-axis camera constraints [NB-025], and Google Veo JSON schema structures [NB-025].
*   **QA & Prompt Configuration (Prompts 23, 24)**: Grounded in custom Gem context drift failure modes [NB-023], the 30-point Art-Direction Critique Matrix [NB-022], and the 3-question copy sentence discipline [NB-009].

---

