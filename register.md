VERSION: 1.1
HASH: reg-1.1-a
REGISTER — Heather project
Numeric order, never renumbered, never skipped. Sort on the STATUS field.
STATUS INDEX
  DEFECT: F-09 F-10 F-19 F-20 F-25 F-26
  ADVISORY: F-21
 PROPOSAL: F-11 F-12
  CLOSED: F-01 F-02 F-03 F-04 F-05 F-06 F-14 F-18 F-22 F-23 F-24 F-27
  DEAD: F-07 F-08 F-13 F-15 F-16 F-17
Dead numbers keep their slot and are never reused.
RECONSTRUCTED entries may not be quoted verbatim until re-confirmed.

F-01 — DEFECT — CLOSED (content). previous.md empty; no outgoing version held.
F-02 — DEFECT — CLOSED (1.1 repair). current.md truncated at two thirds of Craft, §2–§5A absent.
F-03 — DEFECT — CLOSED (1.1 repair). Craft §11 tail truncated in the same write. Inferred from the 1.1 log.
F-04 — DEFECT — CLOSED (1.3 write). The token-driven in-chat write page never landed a write.
F-05 — DEFECT — CLOSED (1.3 write). Long code blocks truncate on copy.
F-06 — DEFECT — CLOSED (1.3 write). No verify step existed, so a write was assumed landed without a fetch.
F-07 — DEAD — REFERENCED-NOT-RECORDED.
F-08 — DEAD — REFERENCED-NOT-RECORDED.
F-09 — DEFECT — OPEN — RECONSTRUCTED — not verbatim. Intake chest line reads 34C and is obsolete against the set.
F-10 — DEFECT — OPEN — RECONSTRUCTED — not verbatim. Face block must be written from a rendered frame, not the photograph.
F-11 — PROPOSAL — OPEN — RECONSTRUCTED — not verbatim. Collapse the Craft/Process pair to a single file.
F-12 — PROPOSAL — OPEN — RECONSTRUCTED — not verbatim. previous.md is redundant against the version log.
F-13 — DEAD — REFERENCED-NOT-RECORDED.
F-14 — DEFECT — CLOSED (Wan confirmed). Engine lane unproven; closed at 15/18 with declared drift and mitigations, Seedance excluded at admission.
F-15 — DEAD — REFERENCED-NOT-RECORDED.
F-16 — DEAD — REFERENCED-NOT-RECORDED.
F-17 — DEAD — REFERENCED-NOT-RECORDED.
F-18 — DEFECT — CLOSED (1.4-b). §0A. File created as current.mf; documented URL 404s. A rename exists in the UI though not via API, so a wrong extension is correctable rather than permanent.
F-19 — DEFECT — OPEN. Part-joint blank lines lost; Part D header indented. Source fix: a transfer block never splits a part joint; the joint is carried whole inside one block, and every block boundary sits on a blank line. Cites F-25 and F-26.
F-20 — DEFECT — OPEN. Process §4 log indentation inconsistent between halves.
F-21 — ADVISORY — OPEN. Lines too long to read on a phone; held for the next edition.
F-22 — DEFECT — CLOSED (1.4-b). §0A. A raw fetch served a stale cached copy three times, once across a cache-buster, so a blank line that existed read as missing and was twice reported absent. The blob page confirmed it with line numbers. Rule: content checks on raw, structure checks on the blob page. The blob is a complete replacement for the structure check, not a workaround, and raw still serves content.
F-23 — DEFECT — CLOSED (1.4-b). 1B, A3. Cross-reference to §7.7, a section that never existed, cited from both 1B and A3. Number retired; the tone text sits verbatim at A3 and 1B points at it.
F-24 — DEFECT — CLOSED (1.4-b). 1B. 1B's reference count contradicted the five mandatory slots in 1A. Ruled per-shot and settled; 1A and the four-label rule unchanged.
F-25 — DEFECT — OPEN. 7.3/7.4 joint. The blank-line count at the joint does not survive the paste: lost in one instance, gained in another. One class, both directions. Cites F-19; the source fix is F-19's.
F-26 — DEFECT — OPEN. 7.3/7.4 joint. NOT an occurrence of the F-19 class — a different defect at the same seam: the separator line holds two spaces rather than being empty, and the file ends on two trailing spaces with no final newline. Cites F-19 and F-25 for location only.
F-27 — DEFECT — CLOSED (1.4-b). A3. A3 stated tone as an absolute only, which under-lights a reference, and omitted the relationship clause. Rewritten at 1.4-b.

COVERAGE. Six numbers are dead in production and four are reconstructions. Everything below F-09 is second-hand. The register was recoverable only because a production chat still held a session summary; it had no store file. F-09 to F-12 are re-confirmed or re-worded by the chief before any verbatim quote.
