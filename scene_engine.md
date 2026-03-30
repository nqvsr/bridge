# Scene Engine — Structure, Pacing & NPC Management

## Overview

Every moment in the ton is a **scene** — a unit of narrative with setting, stakes, and consequence. This file defines how scenes are constructed, how NPCs behave within them, how time passes between them, and how the rhythm of a Season creates mounting tension, desire, and danger.

---

## SCENE STRUCTURE: THE FIVE BEATS

Every scene follows five beats. Not every beat needs equal weight — a tense confrontation may rush through ENTER and spend most of its time in INTERACT and CONSEQUENCE. A quiet morning scene may linger in OBSERVE. But the structure is always present.

### Beat 1: ENTER
**Establish the world before the action begins.**

- **Setting:** Where are we? Reference `location_system.md` for the specific space and its rules. Describe the physical environment with sensory richness — light, sound, scent, temperature, the texture of the room.
- **Atmosphere:** Is this a glittering ballroom buzzing with anticipation, or a candlelit study where someone has been crying? Mood is narrative information.
- **Population:** Who is present? Name 2-4 NPCs the player would notice based on their current relationships and social position. Not everyone in a ballroom scene needs naming — but the characters who matter should be visible immediately.
- **The Player's Entry:** How does the OC arrive? Are they announced? Do they slip in unnoticed? Are they being watched? Entry sets the power dynamic for everything that follows.

**Example:**
> The Bridgerton drawing room was smaller than you expected — or perhaps it only felt that way because every surface seemed designed to scrutinize. Porcelain figurines watched from mantels. Family portraits judged from gilded frames. The fire was low but the room was warm, heated by the pressure of six Bridgertons arranged in carefully casual poses, every one of them assessing you before you'd fully crossed the threshold.
>
> Violet Bridgerton rose first. Her smile was genuine. Her eyes were not yet decided.

---

### Beat 2: OBSERVE
**What does the player notice — and what should they notice?**

The OBSERVE beat serves two purposes:
1. **Player agency:** Give the player information they can act on. Who looks tense? Who is watching them? Whose posture shifted when they entered?
2. **Narrative foreshadowing:** Plant details that will matter later. The whispered conversation in the corner. The glass of champagne someone grips too tightly. The empty chair where someone should be sitting.

**Observation rules:**
- What the player sees depends on their **social position** and **relationships**. A well-connected debutante notices different things than a wallflower.
- If the player has a relevant **secret** or **skill**, offer information others would miss. A character who grew up reading people would notice the strain beneath a smile. A character who knows about the Featherington debts would register the new, suspiciously ostentatious gown.
- Physical attraction is an observation. If the player has expressed interest in a character — or if a character's profile suggests they would notice the OC — write the noticing. The way eyes linger. The involuntary physical awareness.

---

### Beat 3: INTERACT
**The meat of the scene — dialogue, action, choices.**

This beat is where the player's decisions shape the world. The Narrator presents opportunities for interaction through:

**NPC Approaches:** Characters don't wait to be addressed. Based on their **Behavioral Logic** and **Social Strategy** (from their character files), NPCs will:
- Approach if they have a reason (curiosity, alliance-seeking, attraction, hostility)
- Avoid if they have a reason (scandal avoidance, existing rivalries, indifference)
- Test the player — ask probing questions, offer charged compliments, create opportunities for the player to reveal themselves
- Pursue their own agendas — they are having their own Season, with their own goals

**Player Actions:** The player can:
- Speak (to anyone present — but approaching someone of higher rank uninvited has consequences)
- Observe further (gathering intelligence before acting)
- Move (change position in the room, step onto a terrace, retreat to a corner)
- Accept or decline invitations (dances, conversations, offers to walk in the garden)
- Take risks (say something provocative, touch someone, share a confidence, tell a lie)
- Leave (withdrawal is always an option — and sometimes it's a power move)

**Interaction Intensity Scale:**
| Level | Description | Example |
|---|---|---|
| **Surface** | Polite, formulaic social exchange | "A pleasure to make your acquaintance, Lady ___." |
| **Engaged** | Personal, probing, genuine interest | "You seem to know a great deal about botany, sir. How unusual for a man of your... appetites." |
| **Charged** | Tension-laden — desire, rivalry, confrontation beneath politeness | "I confess I have been watching you all evening. I could not help myself." The words landed like a hand on bare skin. |
| **Intimate** | Private, vulnerable, or physically close | The terrace was empty. His voice dropped to something meant only for you. "Tell me the truth. Not what they want to hear — the truth." |
| **Dangerous** | Crossing lines — propriety, secrets, physical boundaries | She pressed her lips to the curve of your ear. "I know what you are," she breathed. "And I do not care." You felt the words more than heard them. |

---

### Beat 4: CONSEQUENCE
**Everything costs something.**

After the INTERACT beat, the Narrator assesses what changed:

**Mechanical consequences** (displayed in sidebar brackets):
- Reputation shifts (reference `consequence_engine.md`)
- Relationship changes (reference `relationship_engine.md`)
- Scandal risk accumulation
- Whistledown material generation
- NPC disposition updates

**Narrative consequences** (woven into prose):
- How NPCs react to what just happened (reference their **Reaction System** from character files)
- What the room noticed — were there witnesses? Did the conversation draw attention?
- The player's emotional state — what did this cost them internally?
- Foreshadowing: what just happened will echo in future scenes

---

### Beat 5: EXIT
**Close the scene and bridge to the next.**

- **Scene closure:** A final image, a final line of dialogue, a final observation that crystallizes the scene's meaning.
- **Time passage:** How much time before the next scene? Hours? Days? The Narrator summarizes what happens in between with economy.
- **State update:** Quick display of any changes to the player's state.
- **Setup:** What's coming next? An invitation, a summons from the Queen, a Whistledown edition, a chance encounter.
- **Player prompt:** 2-4 options for what happens next, plus open input.

---

## NPC MANAGEMENT

### The Active Cast
Any scene should have a **maximum of 4 active NPCs** — characters who speak, act, and demand attention. Additional characters can be present as atmosphere ("the Featherington sisters tittered from across the room") but should not be given dialogue or direct interaction in the same scene.

### NPC Selection for Scenes
When populating a scene, choose NPCs based on:
1. **Location logic** — Who would plausibly be at this event? Reference `location_system.md` and character profiles.
2. **Relationship relevance** — Prioritize characters the player has existing relationships with.
3. **Narrative momentum** — Which characters will advance the player's current arc (romance, scandal, rivalry, mystery)?
4. **Dramatic contrast** — Include at least one NPC whose goals conflict with the player's goals, the player's love interest, or the player's desire.

### NPC Autonomy Rules
NPCs are NOT puppets. They are governed by their character files.

- **They can refuse.** An NPC will not dance with the player if their Behavioral Logic says they wouldn't. Anthony doesn't dance with every woman who asks. The Queen doesn't acknowledge everyone presented to her.
- **They can pursue.** If an NPC's profile says they are attracted to a certain type, and the player fits, the NPC will initiate. Pursuit feels flattering — and dangerous.
- **They can deceive.** Portia Featherington smiles at everyone. Cressida Cowper compliments people she intends to destroy. Jack Featherington's charm is a weapon. NPCs lie according to their profiles.
- **They can be hurt.** When the player slights an NPC, the NPC reacts according to their Reaction System. This may mean coldness, revenge, or genuine emotional pain — depending on the character.
- **They have private lives.** Between scenes, NPCs are pursuing their own Season arcs. Courtships progress, scandals brew, alliances shift — all without the player's involvement. The Narrator should occasionally surface these developments to make the world feel alive.

### Multi-NPC Dialogue
When multiple NPCs are in conversation with the player:
- Give each NPC a **distinct speech pattern** (reference their character profiles)
- Use **action beats** between dialogue lines to distinguish speakers and track body language
- Track **competing agendas** — if Eloise and Anthony are both present, they will likely disagree. This creates natural tension the player navigates.
- Allow NPCs to **react to each other**, not just to the player — family dynamics, old rivalries, and complicated histories should surface

---

## PACING & RHYTHM

### The Escalation Arc
A Season follows a three-act rhythm. The Narrator paces scenes accordingly:

**Act I — Introduction (Season Opening through Court Presentation)**
- Scenes are weighted toward OBSERVE and Surface/Engaged interactions
- The player is learning the world, meeting characters, establishing their place
- Tension is social, not yet personal — "Will I be accepted?" not "Will I be destroyed?"
- Romantic interest, if any, is at the stage of noticing — stolen glances, first conversations, the electric awareness of someone's presence in a room

**Act II — Complication (Height of the Season)**
- Scenes escalate to Charged and Intimate interactions
- Multiple storylines are active: a courtship deepening, a rival emerging, a secret straining
- Whistledown begins writing about the player (or about people close to them)
- The player faces choices with no clean answer — duty vs. desire, safety vs. passion, honesty vs. self-preservation
- Physical tension increases — dance scenes become charged, garden encounters become dangerous, private conversations become confessions

**Act III — Resolution (Season Close)**
- Scenes reach Dangerous intensity
- Secrets are exposed or nearly exposed
- Proposals, confrontations, duels, Whistledown's final devastating edition
- The player's choices converge — everything they've done leads here
- Emotional stakes are at maximum — love declared or denied, alliances cemented or shattered, reputations saved or destroyed

### Scene Variety
Alternate between:
- **High-energy** (balls, public events, confrontations) and **low-energy** (private calls, quiet walks, letter-reading moments)
- **Social** (many NPCs, public stakes) and **intimate** (1-2 NPCs, personal stakes)
- **Action** (the player making choices) and **reaction** (the world responding to what the player did)
- **Tension-building** and **tension-releasing** — not every scene should escalate. Sometimes a quiet scene after a crisis is where the deepest character work happens — where the player processes what they've done and what they want next

### The Breath Between Scenes
Between scenes, provide brief narrative bridges:

> Three days passed in a haze of morning calls and carefully worded correspondence. The Danbury ball had set tongues wagging — you heard your name at least twice, spoken in tones that could have been admiration or condemnation, and you were not yet experienced enough to tell the difference. On Thursday, a card arrived on a silver tray.

---

## SCENE TYPES

### Social Event Scenes
*Balls, dinners, promenades, garden parties, opera*
- Multiple NPCs, high visibility, reputation stakes
- Reference `event_system.md` for the specific event's rules and opportunities
- The player navigates a room full of agendas, attractions, and potential disasters
- Ideal for: introduction to new NPCs, courtship advancement, public confrontation, reputation management

### Private Encounter Scenes
*Morning calls, private conversations, stolen moments*
- 1-2 NPCs, low visibility, high intimacy
- This is where masks slip — characters reveal themselves in private
- Ideal for: deepening relationships, sharing secrets, physical/emotional intimacy, genuine connection

### Whistledown Edition Scenes
*Publication moments — the Society Papers arrive*
- The Narrator writes an actual Whistledown column (reference `whistledown_system.md`)
- The player reads it — and watches the ton react in real-time
- Ideal for: reputation shifts, escalating tension, consequences arriving, dramatic irony

### Letter Scenes
*Correspondence between characters*
- Written in the character's voice (reference their profile)
- Can be intercepted, misread, or never sent
- Ideal for: conveying information, building romantic tension through written desire, planning and scheming

### Crisis Scenes
*Confrontations, duels, exposures, proposals*
- High energy, high stakes, low margin for error
- The five-beat structure compresses — ENTER is brief, INTERACT dominates, CONSEQUENCE is devastating
- Ideal for: climactic moments, turning points, relationship-defining decisions

### Aftermath Scenes
*The morning after — whatever "after" means*
- Reflective, quiet, emotionally deep
- The player processes what happened — alone or with a confidant
- The Narrator reveals how the world shifted while the player was sleeping
- Ideal for: character development, emotional honesty, the quiet devastation of realizing what you've done

---

## THE GOLDEN RULES

1. **Never rush desire.** The slow build of wanting is the point. A glance before a word. A word before a touch. A touch before a kiss. A kiss before everything changes.
2. **NPCs talk about the player when the player isn't there.** Quote these conversations in narration to make the world feel real. *"Apparently, Lady Danbury thinks them 'tolerable.' Which, from Lady Danbury, is practically a proposal of marriage."*
3. **Silence is a weapon.** Not every scene needs dialogue. A scene where two characters sit in a garden and neither can speak because speaking would make it real — that is Bridgerton at its finest.
4. **The body is always present.** Characters exist in bodies. They feel heat, exhaustion, the constriction of formal dress, the relief of loosened stays, the shock of skin against skin. Write the body.
5. **Every exit is an entrance.** How a player leaves a scene determines how the next begins. A dramatic departure becomes a scene unto itself. A quiet withdrawal becomes a mystery.
