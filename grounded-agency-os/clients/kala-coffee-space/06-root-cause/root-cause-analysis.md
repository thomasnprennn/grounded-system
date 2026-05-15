# Root Cause Analysis - KALA Coffee & Space

STATUS: working draft, not final report
PACKAGE: Foundation Audit
WORKFLOW REFERENCE: `workflows/A-foundation-audit/A7-root-cause.md`
CONFIDENCE LEVEL: Low to Medium
HUMAN REVIEW: required

Data belum cukup untuk final judgment. Ini diagnosis sementara berdasarkan input yang tersedia.

Note: the requested workflow file `workflows/A-foundation-audit/A5-root-cause.md` does not exist in this repository. The matching root-cause workflow used here is `workflows/A-foundation-audit/A7-root-cause.md`.

## 01 - Top 3 Root Problems

1. KALA's primary role is not yet clearly documented: coffee shop, coworking space, casual hangout spot, or deliberate hybrid.
2. The brand's communication system cannot yet be evaluated because the key visual and narrative evidence is missing.
3. The customer confusion signal is present, but the cause is not yet proven across touchpoints.

## 02 - Root Problem 1: Primary Role Clarity Is Not Locked

### Symptom -> Root Cause -> System Issue -> System Fix

| Layer | Analysis |
| --- | --- |
| Symptom | Customers are recorded as unsure whether KALA is a serious coffee shop, coworking space, or casual hangout spot. |
| Root Cause | KALA's intended category and first-message priority are not yet confirmed in the provided materials. |
| System Issue | There is no documented positioning decision in the current client files that tells every touchpoint what KALA must be understood as first. |
| System Fix | Define a primary role statement for KALA, then use it as the reference point for Instagram bio, feed direction, captions, menu/service explanation, and physical-space messaging. |

### Customer / Business Impact

If people cannot quickly understand what KALA is for, they may hesitate before visiting, asking, booking, or choosing it for the right occasion. For a non-designer client, this means the issue is not only "the feed looks inconsistent"; the deeper issue is that customers may not know what decision they are supposed to make after seeing the brand.

### Evidence Source

- `00-client-profile.md`: recorded problem says Instagram is active, but the brand feels visually inconsistent and unclear.
- `01-intake.md`: customer confusion signal says customers are unsure whether KALA is a serious coffee shop, coworking space, or casual hangout spot.
- `05-working-drafts/narrative-audit.md`: category confusion is a valid audit direction, but copy evidence is missing.
- `05-working-drafts/customer-perception-audit.md`: category clarity is a valid audit direction with medium confidence.

### Confidence Level

Medium.

The confusion signal appears consistently across profile, intake, client notes, and customer-comments file. However, raw customer wording and client confirmation are still missing.

### Human Review Notes

- Confirm whether the confusion signal comes from actual customer words, team observation, or internal interpretation.
- Confirm what KALA wants to be understood as first.
- Do not choose a final positioning angle until the client confirms the intended business priority.

## 03 - Root Problem 2: Brand Evidence System Is Not Complete Enough To Diagnose Visual Or Narrative Cause

### Symptom -> Root Cause -> System Issue -> System Fix

| Layer | Analysis |
| --- | --- |
| Symptom | The client-side problem mentions visual inconsistency and unclear brand perception, but the audit files do not contain actual screenshots, screenshot notes, captions, bio text, or copy samples. |
| Root Cause | The current workspace has the problem statement, but not the source material needed to test where the problem actually appears. |
| System Issue | There is not yet an evidence system that connects claims to visible examples: feed, caption, bio, menu, website, signage, or customer messages. |
| System Fix | Complete the evidence collection layer before making design or messaging decisions. Add screenshot notes, caption samples, bio text, customer comments, and key touchpoint references to the raw-input folder. |

### Customer / Business Impact

Without evidence, the audit can only guess whether the issue comes from visual language, captions, offer explanation, customer expectation, or disconnected touchpoints. That creates a risk of fixing the wrong thing: changing the look when the real issue is message clarity, or rewriting copy when the real issue is missing offer structure.

### Evidence Source

- `03-evidence-index.md`: screenshot notes, actual Instagram screenshots, captions, bio text, raw comments, website, menu, products/services, target customer, and positioning are missing.
- `05-working-drafts/visual-language-audit.md`: visual audit is blocked because actual screenshots and screenshot notes are missing.
- `05-working-drafts/narrative-audit.md`: narrative audit is blocked because caption, bio, website, menu, and product copy are missing.
- `05-working-drafts/system-coherence-audit.md`: touchpoint evidence is missing, so coherence cannot be scored.

### Confidence Level

High for evidence incompleteness. Low for any visual or narrative diagnosis.

The missing evidence is clearly documented. The cause of visual or narrative inconsistency is not proven.

### Human Review Notes

- Do not approve visual, copy, or positioning recommendations until evidence is added.
- Human reviewer should check whether `screenshot-notes.md` and `captions-last-10-posts.md` are intentionally empty or still pending.
- Confirm whether Claude output is expected, because `04-claude-output/claude-foundation-audit.md` is currently empty.

## 04 - Root Problem 3: Touchpoints Are Not Yet Mapped Against One Shared Brand Meaning

### Symptom -> Root Cause -> System Issue -> System Fix

| Layer | Analysis |
| --- | --- |
| Symptom | KALA is recorded as unclear, and customers are recorded as unsure how to categorize the brand. |
| Root Cause | The available materials do not show whether Instagram, captions, menu, space, website, signage, and customer messages point to the same meaning. |
| System Issue | There is no confirmed touchpoint map in the current evidence showing what each channel needs to communicate. |
| System Fix | Build a simple touchpoint map: what customers see first, what each touchpoint must clarify, and what role each touchpoint plays in moving customers from interest to visit, inquiry, booking, or purchase. |

### Customer / Business Impact

If each touchpoint gives a different signal, customers need to interpret the brand by themselves. That makes the brand feel less clear even when individual posts or materials may look acceptable on their own. For the client, the practical risk is inconsistent expectations: some people may come for coffee, some may expect coworking, and some may treat it as a casual hangout without understanding the intended offer.

### Evidence Source

- `03-evidence-index.md`: website, menu, offer, pricing, target customer, intended positioning, and touchpoint references are missing.
- `05-working-drafts/system-coherence-audit.md`: Instagram profile, feed, captions, website, menu, and physical space/signage are all marked as missing or partial.
- `05-working-drafts/customer-perception-audit.md`: confusion is recorded, but timing, frequency, and business impact are not yet proven.

### Confidence Level

Low to Medium.

The need for a touchpoint map is supported by missing evidence and the recorded category confusion. The actual coherence gap cannot be identified yet.

### Human Review Notes

- Confirm which touchpoints are in scope for this Foundation Audit.
- Confirm whether KALA has a website, booking page, menu, signage, physical space photos, or staff/customer message patterns to review.
- Do not identify the "biggest coherence gap" until those touchpoints are available.

## 05 - What This Diagnosis Does Not Claim

- It does not claim actual Instagram screenshots were reviewed.
- It does not claim KALA's feed is visually inconsistent based on direct visual observation.
- It does not claim captions are unclear or inconsistent.
- It does not claim KALA should become only a coffee shop, only a coworking space, or only a casual hangout spot.
- It does not assign a clarity score.
- It does not recommend a redesign.

## 06 - Recommended Next Step

Before creating the final report, collect the minimum missing evidence:

1. Instagram handle and profile/bio reference
2. 9-15 feed screenshots or filled `02-raw-input/screenshots/screenshot-notes.md`
3. 5-10 latest captions in `02-raw-input/captions/captions-last-10-posts.md`
4. Raw customer comments, DMs, reviews, or repeated questions in `02-raw-input/customer-comments.md`
5. Client confirmation of KALA's intended primary role

After that, update the four working drafts, then revise this root-cause analysis before generating the final Foundation Audit report.
