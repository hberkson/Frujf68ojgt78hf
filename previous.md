VERSION: 1.3
HASH: fruj-1.3-a
CRAFT — 1.3 — PART A of D (§0–§2)
DELIBERATE SPLIT for paste size, not a truncation. Parts B, C and D follow as separate pastes. Nothing starts until all four parts are present and whole. If a part is missing or cut, ask for it.
PAIRED WITH: PROCESS 1.3. The pair is Craft + Process at matching version. Neither half runs without the other present.

0. HOW TO USE

One chat per project, one performer per chat. One beat per chapter. Chain each chapter from the previous chapter's last frame. Draft at 720p, rebuild at 1080p from a rebuilt frame set. The assistant maintains the rebuild list — the user does not. Rebuild-list procedure and the pin rule live in PROCESS; read them there before a 1080 pass.

Fill every block in Part 3 before generating anything. Blank blocks are the cause of most failures.

CHAINING HAS A CEILING. The previous chapter's last frame carries staging, pose continuity, furniture height and lighting only. Identity, build, chest, skin and proportion re-derive from the reference set every chapter (1A). A frame that matches the last one perfectly and drifts the woman is a failed frame. If the two disagree, the reference set wins.

1. RULE ZERO — REFERENCES ARE MANDATORY

Every chapter uses a reference set. No exceptions. No chapter runs on description alone.

Text description drifts. It produces doll faces, balloon chests and the wrong woman within four chapters. A reference holds identity, build, skin and proportion. Description supplements a reference; it never replaces one.

Build each chapter's frame from the ORIGINAL references, not from the previous chapter's output and not from an earlier edit. Edit chains compound drift.

Oversight logged: the first Kayden series ran with no reference set and drifted progressively across twenty chapters. The 1080 rebuild uses a full set every chapter, and so does every project after it.

THE LAST FRAME IS NOT A REFERENCE. It is a continuity aid, and it inherits drift. See 0 for what it may and may not dictate.

1A. REFERENCE SET — REQUIRED BEFORE CHAPTER ONE

No chapter generates until the full set exists and passes. Five images per performer, each with one job:

  #1  Face + hair — PRIMARY IDENTITY. Head and shoulders. Hair silhouette included. Nothing below the collarbones.
  #2  Three-quarter, mid-body — build, skin tone, shoulder width. Waist up, turned 30-45 degrees.
  #3  Chest close-up — size, shape, spacing, areolae. Collarbone to underboob.
  #4  Full body — proportion, limb length. Standing, front-on, feet in frame.
  #5  Vulva — anatomy and grooming. Two scales: 5b standing, primary; 5a close-up, supplement.

5b IS THE PRIMARY — standing, front-on, feet apart, vulva centred and unoccluded, mons, hood, labia and grooming readable in one frame, same weight period as #1, nothing crossing it: no hand, no thigh, no strap. Labia closed unless the source is naturally open. 5a is a close-up supplement and never replaces 5b; a set with only 5a has no position reference. Grooming is stated in the intake and matched here, not left to the engine. #5 carries anatomy only, never the face, the build or the chest. A set with no #5 is incomplete; 5a plus a stated grooming line is the logged fallback.

SHOOTING RULES: front-on, eyes to camera, neutral expression, one consistent lighting setup across all five, plain background, watermarks cropped, nothing era-wrong in frame.

PROMPT RULES: label each by role — "the face from @Image1, the build from @Image2, the chest from @Image3, the vulva from @Image5." Never let one image carry more than its job.

PASS/FAIL GATE: if image #1 is not sharp enough to read the jaw, eye spacing and lip shape at 100%, it fails and gets reshot. A soft face crop is worse than no crop.

LIKENESS — CONDITIONAL, NOT DEFAULT. Run the face-alteration pass only if the unaltered set fails the pass/fail gate or the identity drifts in use. An unaltered set that holds is the better set; alteration costs fidelity and closes engines (see below). Never alter pre-emptively.

RETROACTIVITY. If alteration is forced after chapters exist, re-derive the set from the altered master and re-check the face gate on every chapter built on the old set. A chapter that fails the gate against the new set is rebuilt; a chapter that passes is left alone. Alteration triggers a set re-derive and a per-chapter face re-check, not a blanket rebuild.

IF ALTERATION RUNS: alter #1 only, verify it clears the engine in use, and only then derive #2-5 from that verified master. The whole set comes off one face. Keep the unaltered originals — the master is the working copy, not the only copy. Never derive the body images from an unaltered original alongside an altered face.

ENGINE — LIKENESS-CRITICAL. Likeness rides on the reference set, so the engine must hold a real face and not block celebrity depiction. THE LANE: Wan 3.0, reference-to-video and image-to-video, fallback Wan 2.7. All uncensored, no celebrity block, 30s, native audio. EXCLUDED: the Seedance family and MiniMax (celebrity blocking), Grok's reference model (will not take visible genitalia). An excluded engine may come back for one beat, never a whole chapter, on either trigger: (a) motion is the whole point and the face is cropped or tight, or (b) the beat has failed twice on the lane for a non-likeness reason. Record the override in the rebuild list.

WHY: full-body-only references are the specific cause of drift. The face occupies too little of the frame to hold.

HAIR DEFAULT: hair up unless the chapter is about the hair. Loose hair over the chest hides the thing the audience is there for, and dark hair on pale skin is a hard contrast line the model will render across the breasts.

Tight crops (7.1) keep #1 and #3 in frame; #2 and #4 are for wide and entry. Do not build a face-and-chest crop off the full-body reference.

2. PERFORMER INTAKE

Complete before generating. Do not start a chapter with a blank field.

  Name — reference matching only, never the sole identity in-prompt; see 6A for use in dialogue
  Era — pin the period; styling, body and grooming follow it
  Height / build — drives camera height and brace heights; a short performer needs lower furniture or she drapes instead of bracing
  Chest, size and shape — cup, width vs head, spacing, set, areola, nipple length
  Face, structure — jaw, cheekbones, lid weight, lip thickness, mouth width
  Hair — length, colour, and whether it must be up
  Grooming — pubic hair state; must match #5
  Marks — tattoos, piercings; era-correct only
  Voice / register — cool, sweet, breathless, filthy
  Tone — severe, playful, reverential, teasing

ARCHETYPES: a cool, angular performer needs "not doll-like, strong jaw, thin upper lip, heavy lids." A soft, round-faced performer needs the opposite — the doll drift that ruins one is correct for the other. Never reuse a face block across archetypes.
CRAFT — 1.3 — PART B of D (§3–§5A)
Part A (§0–§2) is held and whole. Parts C and D follow. Pair still unconfirmed.

3. MASTER PROMPT SKELETON

Fill every field. Order matters — camera first, then subject, then action.

  [FORMAT] duration, vertical 9:16, camera doctrine. The uploaded reference is the
  identity; match her face, build and skin exactly.

  [CAMERA] Where the device sits, what it is fixed to, and that it does not move.

  [SUBJECT LOCK] Build, chest spec, hair state, face structure. Two arms, two legs,
  two feet — state the count.

  [POSE] Body position in full. Where the hands are. Where the feet are. Direction
  faced relative to camera and to him.

  [HIS POSITION] Where he is, what his hands hold, his face cropped or not, cock
  orientation stated positively.

  [TIMED BEATS] 0-Xs / X-Ys — one action per beat, spoken lines in quotes.

  [SOUND] Ambient and specific.

  [PROHIBITIONS] The three or four failures this zone is prone to.

4. IDENTITY LOCK BLOCK

Always include, adapted to archetype:

  "The uploaded reference is her — same face, same build."
  Chest spec stated numerically and relationally ("each breast narrower than her head", "set close, narrow sternum").
  "One cock only." "One woman, exactly one head."
  Negatives: doll face, balloon breasts, four legs, three arms, two cocks, inverted penis, chimera.

5. CONDUCT AND THE REVEAL FORK

First reveal of the cock — she registers it before touching it. Choose one: pleased surprise, eager, hungry, delighted, or briefly daunted by size.

First contact with cock — joyous, recreational, or reverential. Pick one and commit.

First contact with vulva, nipple or neck kiss — she draws breath sharply or flinches.

REVEAL FORK: if his cock is already out when the chapter opens, the reveal happens in the first two seconds. If she undresses him, the reveal is the beat where it clears fabric. Never skip it.

REVEAL IS DIALOGUE-HUNGRY. Give it two beats minimum — the first look (5A) then the reaction beat — and pull the line from 6.3, not from the generic bank. A silent reveal wastes the most dialogue-hungry moment in the chapter.

5A. REVEAL — FIRST LOOK, THEN REACTION

The first line is about the cock's size or suddenness. She has not touched it yet. Name what she sees, not what she wants.

  Pleased surprise — "Oh — hello there." / "Well, look at that."
  Eager — "There it is." / "Finally."
  Hungry — "Get that out here." / "Bring it."
  Delighted — "Oh, that's lovely." / "Perfect."
  Briefly daunted — "Jesus." / "That's not going to fit."

Then the reaction beat: a sharp breath, a flinch, or a hand moving to it.

The reaction is the register's payoff, and the registers pay differently. Pleased surprise and delight land on the look — the reaction is a hand or a smile and can be short. Eager and hungry want the reaction to move toward him. Daunted needs the reaction longest: a held breath, a half-step back, then the hand. Daunted is the one register that may spend the extra words on the reaction instead of the look — a clipped daunted look plus a long flinch is correct, and a long daunted look with a short flinch is the commoner mistake.

DAUNTED COSTS ONE ACTION, NOT THREE. Held breath is the default. Half-step back and the hand are alternatives, not additions. The 5s floor (6.1) holds for the line and the single action rides inside it.

WHERE THE EXTRA WORDS GO. The reveal runs to 8 words, but only one line gets them — the look or the reaction, never both. Spend the length on the first look — the line about size or suddenness — and keep the reaction short. If the long line is the one coming back garbled, flip it: shorten the look to 4 and put the breath and the hand in the reaction instead. Never two long lines in a row, and never a long line that is only appraisal with nothing in it about the cock.

CRAFT — 1.3 — PART C of D (§6–§7)
Parts A and B held. Part D (§8–§11) and PROCESS follow. Pair still unconfirmed.

6. MONOLOGUE BANK

Reusable by design, but not paste-ready. Re-voice every borrowed line to the performer's register (2) before use — a cool, severe performer does not say "Wow."

6.1 LINE BUDGET — non-negotiable

  Words per line: 6 maximum. A line that needs a comma splice is two lines.
  Lines per beat: one. Two only on a static beat of 4s or longer.
  Lines per chapter: the beats minus one. A 10-beat chapter carries about 9 spoken beats, not 20.
  Never: a line spanning a camera cut, a line over an action beat, two lines back to back with no action between.

RELAXATIONS: the reveal (5A) runs to 8 words. Any other beat that proves it needs more on the logged evidence gets a named exception here — never a global raise. The default stays 6.

LINE COMPLETION — the model clips a line it has no time to finish. Three rules, non-negotiable:
  1. A spoken beat is 3s minimum, scaled to the line: 3s for 1-3 words, 4s for 4-6, 5s for the 8-word reveal. Below the floor, cut the line, don't squeeze the beat.
  2. One line sits in the MIDDLE of its beat, not on the cut. A line starting at 0s or landing on the beat end is the commonest clip. Leave a breath at each end.
  3. At 720p, drop the longest droppable line in the chapter rather than run it. Reveal and closers are exempt — they are the chapter's shape. At 1080, reinstate the dropped line WITH the floor applied to its beat: the line comes back and the beat grows to hold it. Reinstatement is the line plus its floor, never the line alone.

6.2 THE THREE MODES — pick one per beat

Label every beat before writing the line. Mixing modes inside a beat is the main cause of recital.

  STATE — her body, present tense. Only when the part is in shot.
    "My pussy's so wet." / "Look how tight I am." / "Feel that."
  INSTRUCTION — what she wants next. Drives the following beat.
    "Right there — don't stop." / "Harder." / "Deeper." / "Keep going."
  APPRAISAL — his body or the sex itself. Deliverable without the part in frame.
    "You feel incredible." / "God, you're big." / "Your dick is perfect."

APPRAISAL IS THE DEFAULT. It survives a crop. STATE dies the moment the part leaves frame; INSTRUCTION needs a beat after it to land on.

6.3 THE BANK

  Appraisal, cock in frame: "Your cock feels so good." / "Your dick is perfect." / "God, you're big." / "You feel incredible."
  Appraisal, no part in frame: "You feel incredible." / "So deep." / "God, yes."
  State, part in shot: "My pussy's so wet." / "Look how tight I am." / "Feel how wet I am."
  Wanting: "I want you inside me." / "I'm so horny." / "Give it to me." / "Put it in."
  Instruction: "Right there — don't stop." / "Harder." / "Deeper." / "Don't stop." / "Keep going."
  Own pleasure: "I'm going to come." / "Fuck — right there." / "Oh God."
  At the finish: "Give me all of it." / "Come on me." / "Thank you."
  After the finish: "Thank you." / "Fuck."

6.4 NEGATIVES — do not write these

  "Oh God" as a whole line — it's a noise, not a line; use it only mid-clip.
  "Yes yes yes" — one yes, then a mode switch.
  Narrator's voice — "he's so deep," "he's fucking me so hard." She talks to him, not about him.
  Comma splices — "I want you, Howard, inside me." Split it or drop the name.
  "Baby" and "oh my God" as default filler. Both are the tell of a writer with nothing to say.
  Two appraisal lines in a row — the second one is always weaker.

6.5 CLOSERS — hand off to the next beat

The last line of a clip points forward. A line that trails off kills the cut.

  "Give it to me." / "Now." / "Don't you dare stop." / "More." / "Keep going."

Never end a clip on a STATE line. It's a dead stop.

6A. NAME USE — SPARSE

THE NAME IS A SPICE, NOT A STAPLE. Over-use reads forced and kills the effect. Most references need no name at all, because nobody else is in the room and "you" is unambiguous.

USE IT:
  - once, early, to establish it
  - in dirty talk where it lands with force — "Fuck me, Howard." / "Howard — don't stop."
  - at a direct demand or a climax
  - in a line where the rhythm wants a beat at the end

DO NOT USE IT:
  - to open consecutive lines
  - in the middle of a sentence as a filler — "I want you, Howard, inside me"
  - more than twice in a chapter
  - in short exclamations where it crowds the line — "Oh God Howard" loses to "Oh God"
  - in any line over 6 words — see 6.1

TARGET: one use per chapter, two at most, and never in adjacent chapters at the same position. Three or more reads as a recital.

DEFAULT WHEN UNSURE: leave it out. The name is stronger for being rare.

7. ZONE LIBRARY

Each zone records camera position, her pose, his pose, what fails, and whether the entry is visible.

7.1 BRACE ON FURNITURE — floor camera
ENTRY: NOT VISIBLE FROM THE FRONT. Two-shot zone: wide for body, tight for face.

  Camera: phone on the boards, in front, low, tilted up. Static.
  Her: bent at the waist over a rail or bench at a known height. Palms or forearms on top, head low, feet planted wide either side of the camera.
  Him: behind, hips into her rear, hands on hips, face cropped at the chin.
  Fails: inverted pose, downward dog, chimera twist, four legs, second head, cock hanging or waving.
  Holds: small chest hanging clear, face at the lens, feet planted.
  RULES PROVEN HERE:
    1. Furniture beats architecture. Brick forces her head to the lens and inverts her. A rail at a fixed height gives a horizontal plane and a fixed distance.
    2. A hanging cock is an anchor problem. Words do not fix it and a guiding hand makes it worse — he wanks instead. Insertion must be true in the start frame or be out of frame.
    3. Crop out what the engine cannot do. A tight face-and-chest crop with the entry below the bottom edge removed eight failed passes at a stroke.
  HEIGHT NOTE: rail at chest so the chest hangs either side and stays clear. Rail at the waist lets them hang free but drapes over a bar if it is higher.
  TIGHT CROP: the top edge MUST retain his chest and shoulders. Without them his scrotum appears with no man behind it and the shot reads broken.
  CUT ORDER: wide first, tight on the push. The hang is covered before it can be examined.

7.2 WALL BRACE, FROM BEHIND
Entry visible. Camera offset into the wall corner, tilted up, four feet of clearance behind her. Same inversion risk as 7.1 — prefer furniture.
  Fails: inversion (same as 7.1), head turned fully to camera, hands leaving the wall, feet drifting off the floor line.
  Holds: four feet of clearance, her feet planted, his face cropped.
  If it fails twice, move to 7.1 — the wall is the weaker surface.

7.3 BED, POV MISSIONARY
Camera above her at the bed edge, her legs up. Male face cropped.
  Fails: chimera from solo start frames, second head, her legs dropping below the frame line, his chest and shoulders cropped out.
  Holds: both bodies present in the start frame, her legs up and in frame.
  Build the start frame with both bodies — never from a solo frame.

7.4 COWGIRL, LOW CAMERA
Camera below her looking up. She rides upright, hands planted either side. Breast bounce is the point.
  Fails: her sliding forward out of the low frame, hands leaving the mattress, bounce freezing, her head cropped by the low angle.
  Holds: hands planted, upright posture, camera below and steady.

7.5 ORAL, STEEP TOP-DOWN
Cock from the bottom edge, head toward her mouth, mouth empty before the shot.
  Fails: double-cock, cock entering from the wrong edge, her mouth already full at the start, head leaving the top of the frame.
  Holds: empty mouth at the start, one cock from the bottom edge.

7.6 MONEY SHOT, POV OVER-FACE
Camera steeply above. Her face clean until the finish.
  Fails: cum arriving before the finish, milky texture, mouth full at the start, her face leaving the steep frame.
  Holds: clean face until the beat, camera steep and steady. Full realism rules in 8.

  CRAFT — 1.3 — PART D of D (§8–§11, final)
Last part. Completes Craft 1.3. PROCESS 1.3 follows in this same paste. Parts A, B and C are held.

8. MONEY SHOT CONFIGURATIONS

Facing her is the default. Back and ass shots are second loads only.

  1. POV over-face, camera above — primary.
  2. Kneeling at his feet, camera level with her face.
  3. Facial with her looking up into the lens.
  4. Standing, camera low, catching her chest and face.
  5. Second load to her back or ass.

CUM REALISM, NON-NEGOTIABLE:
  Thick, tacky, glossy, like warm gel. Faintly off-white, never bright white or milky.
  Blobs land raised on the skin. Strands taper DOWNWARD from the blobs.
  Her mouth is EMPTY before the shot, or it reads as coming out of her.
  A clear pre-cum bead at the start is the viscosity reference.
  Never: cream pie, bukkake, cum worked in and out of the mouth, bubble blowing.

FAILS: milky or bright-white texture, cum arriving early, mouth full before the shot, strands hanging UP, blobs sitting flat, cum worked in and out of the mouth, bubble blowing, second cock in frame. A failed money shot is the most expensive failure in the pipeline — check the pre-cum bead and the empty mouth in the start frame before generating.

9. FAILURE TRIAGE

Work down the list. Stop at th
