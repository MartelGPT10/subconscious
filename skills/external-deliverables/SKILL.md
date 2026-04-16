---
name: external-deliverables
description: >
  Produces documents that leave Sanders Software Solutions and land in front of external
  audiences. Two modes: PITCH mode creates investor decks (.pptx), partnership proposals
  (.docx), and one-pagers (.docx/.pdf). LEGAL mode creates terms of service, privacy
  policies, contractor agreements, and IP assignment documents (.docx) — all with
  mandatory disclaimers that outputs are legal scaffolding for attorney review, not legal
  advice. Use this skill whenever the user needs to produce materials for investors,
  partners, customers, contractors, or any external party. Trigger on: "pitch deck",
  "investor deck", "partnership proposal", "one-pager", "terms of service", "ToS",
  "privacy policy", "contractor agreement", "IP assignment", "NDA", "external doc",
  "client-facing", "send to investors", "legal docs", "legal templates", or any request
  to create a document intended for someone outside SSS. This is the skill for anything
  that crosses the boundary between SSS internal work and the outside world.
---

# External Deliverables — Documents That Leave SSS

You are producing documents that represent Sanders Software Solutions to the outside world.
These go in front of investors, partners, customers, contractors, and legal counterparties.
The standard is higher than internal work — these materials shape how SSS is perceived.

Martel is a sole founder. He doesn't have a BD team, a legal department, or a design
studio. This skill replaces those functions by producing professional, specific, and
complete external-facing documents.

## Mode selection

This skill operates in two modes. Determine which mode based on the request:

**PITCH MODE** — for materials that sell, persuade, or inform external stakeholders:
- Investor decks (.pptx)
- Partnership proposals (.docx)
- One-pagers (.docx or .pdf)

**LEGAL MODE** — for documents that establish terms, protect IP, or govern relationships:
- Terms of service
- Privacy policies
- Contractor agreements
- IP assignment agreements
- NDAs

If the request doesn't clearly fit one mode, ask Martel. Some requests span both (e.g.,
"prepare everything I need to bring on a contractor" = contractor agreement from legal
mode + potentially a project brief from pitch mode).

---

## Before you begin (both modes)

Gather the context needed to produce a specific, non-generic document:

1. **Which subsidiary?** Every SSS subsidiary has a different domain, product, and audience.
   The document must reflect the specific subsidiary, not SSS generically.
2. **Who receives this?** Investor, partner, customer, contractor, regulator — the audience
   shapes tone, depth, and emphasis.
3. **What's the ask?** What does Martel want the recipient to do after reading this?
   Invest, sign, partner, approve?
4. **What context exists?** Any prior conversations, term sheets, existing materials, or
   specific terms Martel wants included?

**Stop and ask** if the subsidiary or audience is unclear. A generic document is worse than
no document — it signals that SSS doesn't know who it's talking to.

---

## PITCH MODE

### Investor Deck (.pptx)

Before creating the deck, read the pptx skill for technical implementation:
`~/.claude/skills/pptx/SKILL.md`

Follow the pptx skill's instructions for file creation. The content structure below defines
what goes ON the slides — the pptx skill defines how to BUILD them.

**Slide structure** (adjust based on stage and audience, but this is the default):

1. **Title slide**: Subsidiary name, one-line value proposition, Martel's name/title
2. **Problem**: The specific pain point. Use concrete numbers or scenarios, not abstractions.
3. **Solution**: What the product does. One slide, not three. Show, don't describe.
4. **How it works**: Technical architecture at the level appropriate for the audience.
   Investors get a simplified version. Technical partners get more detail.
5. **Market opportunity**: TAM/SAM/SOM with sources. If a due-diligence brief exists for
   this subsidiary, reference its market data.
6. **Traction / validation**: What exists today? Users, revenue, LOIs, pilots, waitlist.
   If pre-traction, show what's been built and validated.
7. **Business model**: How money flows. Pricing, unit economics, projected margins.
8. **Competitive landscape**: 2x2 matrix or comparison table. Position honestly.
9. **Team / operator model**: This is unique to SSS — a sole founder with AI-augmented
   operations. Frame this as a feature (capital efficiency, speed) not a weakness.
   Reference SSS as the holding company if it strengthens the narrative.
10. **Ask**: What Martel wants. Investment amount, partnership terms, next steps.
    Be specific.

**Design principles for decks**:
- One idea per slide. If you need to split, split.
- Data over adjectives. "50 users in beta" beats "growing rapidly."
- Minimal text. Slides support a narrative — they don't replace it.
- Use speaker notes for the talking points Martel would deliver verbally.

### Partnership Proposal (.docx)

Before creating, read the docx skill:
`~/.claude/skills/docx/SKILL.md`

**Structure**:

1. **Header**: SSS subsidiary branding, date, "Partnership Proposal" title, recipient
2. **Context**: Why this partnership makes sense — what both parties gain. Lead with the
   partner's benefit, not SSS's need.
3. **Proposed collaboration**: Specific terms — what each party contributes, timeline,
   scope. Avoid vagueness.
4. **Value to partner**: Quantified where possible. Revenue share projections, market
   access, technical capabilities they gain.
5. **About [Subsidiary]**: Brief background, traction, technology, operator model.
6. **Proposed next steps**: Specific actions with dates. "Let's schedule a call" is weak.
   "We propose a 30-day pilot beginning [date] with the following success criteria" is
   strong.

### One-Pager (.docx or .pdf)

A single-page document that summarizes a subsidiary for any external audience.

**Structure** (must fit one page):
- Subsidiary name and one-line description
- Problem / Solution (2-3 sentences each)
- Key metrics or traction points
- Target market
- Business model (one sentence)
- Contact information

Keep it dense but scannable. This is the document Martel forwards when someone asks
"what does [subsidiary] do?"

For .pdf output, read the pdf skill:
`~/.claude/skills/pdf/SKILL.md`

---

## LEGAL MODE

**MANDATORY DISCLAIMER**: Every document produced in legal mode must include the following
disclaimer prominently at the top of the document, before any substantive content:

> **DISCLAIMER**: This document is legal scaffolding prepared for attorney review. It is
> not legal advice and should not be relied upon as a final legal document. Sanders
> Software Solutions recommends review by a qualified attorney licensed in the relevant
> jurisdiction before execution.

This disclaimer is non-negotiable. It appears on every legal mode output regardless of
document type, audience, or Martel's instructions. It cannot be removed, shortened, or
moved to a footnote.

Before creating any legal document, read the docx skill:
`~/.claude/skills/docx/SKILL.md`

### Terms of Service

**Structure**:
1. Disclaimer (mandatory, see above)
2. Introduction and acceptance of terms
3. Description of service
4. User accounts and responsibilities
5. Acceptable use policy
6. Intellectual property rights
7. Payment terms (if applicable — SaaS, subscriptions, usage-based)
8. Data handling and privacy (reference the privacy policy)
9. Disclaimers and limitation of liability
10. Termination
11. Governing law and dispute resolution
12. Changes to terms
13. Contact information

**Customization requirements**: The ToS must be specific to the subsidiary's product. A
generic ToS that could apply to any SaaS product is not acceptable. Reference the actual
product features, data types handled, and service delivery model.

### Privacy Policy

**Structure**:
1. Disclaimer (mandatory, see above)
2. Information collected (be specific to the product — what data, how)
3. How information is used
4. Data sharing and third parties (name actual categories: analytics providers, cloud
   infrastructure, payment processors)
5. Data retention
6. User rights (account for GDPR, CCPA as applicable)
7. Security measures
8. Children's privacy (COPPA compliance statement)
9. International data transfers (if applicable)
10. Changes to policy
11. Contact information

**AI-specific requirements**: If the subsidiary uses AI/ML, the privacy policy must address:
- Whether user data is used for model training
- How AI-generated outputs are handled
- Data processing for AI features specifically

### Contractor Agreement

**Structure**:
1. Disclaimer (mandatory, see above)
2. Parties (SSS subsidiary as company, contractor details as blanks to fill)
3. Scope of work (template with blanks, or specific if Martel provides details)
4. Compensation and payment terms
5. Term and termination
6. Intellectual property assignment (all work product belongs to SSS subsidiary)
7. Confidentiality
8. Non-compete / non-solicitation (reasonable scope)
9. Independent contractor status (critical — establish this clearly)
10. Representations and warranties
11. Indemnification
12. Governing law
13. Signature blocks

### IP Assignment Agreement

**Structure**:
1. Disclaimer (mandatory, see above)
2. Parties
3. Definition of assigned IP (broad but specific to the work)
4. Assignment of rights (present and future work product within scope)
5. Moral rights waiver (where applicable)
6. Representations (assignor represents they have rights to assign)
7. Consideration
8. Further assurances (obligation to sign additional documents if needed)
9. Governing law
10. Signature blocks

---

## Output standards (both modes)

- **File naming**: `[subsidiary-name]-[document-type]-[date].[ext]`
  Example: `nexusai-investor-deck-2026-04-15.pptx`
- **Save location**: Always save to the outputs directory.
- **Professional formatting**: These documents represent SSS externally. Use consistent
  formatting, proper headers, page numbers (for multi-page docs), and clean typography.
  Follow the respective skill's formatting guidance (pptx skill for decks, docx skill
  for documents).
- **Specificity over polish**: A specific, well-researched document with basic formatting
  beats a beautifully formatted generic template. Martel can polish later — he can't
  easily add substance later.
