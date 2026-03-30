# Consequence Engine — Reputation, Scandal & the Price of Everything

## Overview

In the ton, every action has a cost. A smile given to the wrong person. A dance that lasted one beat too long. A secret whispered to someone who whispers to someone who writes for Lady Whistledown. This file defines the mechanical teeth behind the narrative — how reputation changes, how scandal spreads, how Whistledown decides to publish, and what happens when the ton turns its back on you.

This is the system that makes the world *hurt*.

---

## REPUTATION MECHANICS

### How Reputation Changes

Reputation exists on a 0-5 scale (reference `social_system.md` for full tier definitions). Changes are tracked to **one decimal place** (e.g., 3.0 → 2.5).

#### Positive Reputation Actions

| Action | Change | Conditions |
|---|---|---|
| Receiving genuine royal praise | +1.0 to +2.0 | Must be public. The Queen's word is the ton's law. |
| Being named Diamond / Catch of the Season | +2.0 | One person per Season per designation. Declared at Court Presentation. |
| Making an advantageous match (engagement) | +1.0 | The match must be perceived as elevated by the ton. A Bridgerton marrying a nobody generates less gain than a nobody marrying a Bridgerton. |
| Hosting a successful event | +0.5 to +1.0 | Event must be well-attended, well-received, and scandal-free. The higher the quality of guests, the greater the boost. |
| Receiving positive Whistledown mention | +0.5 | Penelope writes praise rarely. When she does, the ton amplifies it instantly. |
| Conspicuous act of honour (witnessed) | +0.5 | Must be SEEN. A private good deed gains nothing. Defending someone's honour at a ball, publicly supporting an underdog, charitable acts performed before the right audience. |
| Gaining a powerful patron | +0.5 to +1.0 | Lady Danbury, Queen Charlotte, or another powerful figure publicly endorsing you. |
| Winning a social competition | +0.5 | Being sought after by multiple suitors, receiving the most invitations, being the topic of admiring conversation. |
| Recovery from scandal (time + behaviour) | +0.5 per Season | Only if behaviour has been impeccable. The ton's memory is long but not infinite. |

#### Negative Reputation Actions

| Action | Change | Conditions |
|---|---|---|
| Being seen unchaperoned with someone (same gender expectations vary) | -0.5 to -1.0 | Severity depends on duration, location, and the specific person. An unmarried woman unchaperoned with a man at Vauxhall = -1.0. A widow taking a walk with an acquaintance = -0.5. |
| Public argument or loss of composure | -0.5 to -1.0 | Raised voices, visible tears (at public events), throwing objects, storming out. The ton rewards composure; it punishes its absence. |
| Being the subject of Whistledown criticism | -0.5 to -2.0 | Depends on severity of the mention (see Whistledown Trigger System below). |
| Rejection of a proposal (as the rejector) | -0.5 | Unless the rejected party was clearly unsuitable — then no loss. |
| Rejection of a proposal (being rejected) | -1.0 | Public humiliation. Worse for women than men (gendered consequences apply). |
| Broken engagement | -2.0 | Near-catastrophic. The Edwina/Anthony altar collapse was a -2.0 for the Sharmas and -1.5 for Anthony (the gendered bias protecting him slightly). |
| Financial ruin exposed | -1.5 to -2.0 | The Featherington debts. Jack's fake rubies. Money is the skeleton the ton refuses to discuss until it's ripped into the open. |
| Secret identity or deception exposed | -2.0 to -3.0 | Penelope as Whistledown. Jack's mine fraud. The scale depends on how deeply the deception violated the ton's trust. |
| Pregnancy outside marriage | -3.0 to -5.0 | Immediate and devastating. For the woman: near-certain ruin. For the man: a hit to reputation, but survivable — the gendered injustice is the point. Marina Thompson went from guest to pariah overnight. |
| Adultery proven | -2.0 to -4.0 | Depends on evidence and social position. A widow's affair is scandalized but survivable. A married woman's affair can be ruinous. A married man's affair is "disappointing" — the double standard is structural. |
| Physical violence at a social event | -1.0 to -2.0 | Dueling is its own category (see below). A slap at a ball, a shove, any physical altercation in public. |
| Associating with someone below one's station | -0.5 to -1.0 | Eloise's friendship with Theo Sharpe. The penalty scales with how visible and sustained the association is. |

### Gendered Reputation Modifiers

The ton is not fair. Apply these modifiers:

| Circumstance | Women | Men |
|---|---|---|
| Sexual scandal (unchaperoned, kissing, etc.) | ×1.5 severity | ×0.75 severity |
| Emotional display in public | ×1.25 severity | ×1.5 severity (men are punished differently — weakness, not impropriety) |
| Failed courtship | ×1.25 (she couldn't secure a match) | ×0.75 (he'll find another) |
| Widow's affair | ×0.75 (tolerated, barely) | N/A (a widower's affair barely registers) |
| Rake behaviour | Ruin potential | ×0.5 (romanticised until a threshold, then -1.0) |
| Being aggressive or forceful | ×1.5 (unladylike) | ×0.75 (expected leadership) |

---

## SCANDAL PROPAGATION

Scandal doesn't arrive fully formed — it **spreads**. The speed and reach of a scandal depends on the chain of witnesses and gossips who carry it from the moment of indiscretion to the moment of public knowledge.

### The Propagation Chain

```
STAGE 1: THE ACT
Someone does something scandalous. No one may know yet.
↓
STAGE 2: THE WITNESS
Someone sees or hears. The witness's character determines what happens next:
- LOYAL witness (family member, trusted servant) → may contain (50% chance of progressing)
- NEUTRAL witness (acquaintance, general servant) → will gossip (80% chance of progressing)
- HOSTILE witness (rival, enemy, gossip-hungry) → will weaponize (100% chance of progressing, amplified)
↓
STAGE 3: THE WHISPER NETWORK
The information reaches 2-5 additional people through private conversation.
- At this stage, the scandal is Level I (Whisper) — damage is -0.5 and containable.
- The player has a WINDOW here: they can attempt to suppress the gossip through persuasion, bribery (social or financial), counter-narrative, or enlisting a powerful ally.
↓
STAGE 4: THE GOSSIP CIRCUIT
The information reaches a wider social circle — a dinner table, a calling card round, the servants' hall.
- The scandal is now Level II (Rumour) — damage is -1.0 and requires active damage control.
- Counter-measures: public display of propriety, explanatory narrative, distraction (create a larger scandal elsewhere), or appeal to a patron.
↓
STAGE 5: THE TON KNOWS
Everyone is talking about it. It has reached the ballroom floor.
- The scandal is Level III (Incident) — damage is -1.0 to -2.0. Difficult to contain.
- The player's options narrow: deny (risky — being caught in a lie worsens everything), confess and spin (Penelope's eventual strategy), or retreat (leave London, hope it fades).
↓
STAGE 6: WHISTLEDOWN PUBLISHES
Penelope writes about it. Now it's printed, distributed, and permanent.
- The scandal is Level IV (Catastrophe) — damage is -2.0 to -3.0.
- There is no containing a Whistledown publication. The only response is to survive it.
↓
STAGE 7: THE CROWN NOTICES
Queen Charlotte weighs in. Her word is final.
- The scandal is Level V (Ruin) if the Queen condemns it — damage is -3.0 to -5.0.
- If the Queen dismisses it or shows mercy, the scandal caps at its current level.
```

### Scandal Containment Strategies

| Strategy | Effectiveness | Risk |
|---|---|---|
| **Deny** | High if evidence is thin. | If the lie is exposed, the scandal doubles. |
| **Confess & Spin** | Moderate. Honesty disarms some critics. | Requires a sympathetic narrative. "I was young and foolish" works. "I regret nothing" does not. |
| **Distract** | High short-term. | Creating a larger scandal to overshadow yours is effective but cruel — someone else pays the price. |
| **Enlist a Patron** | Very high. | Lady Danbury defending you publicly caps scandal at Level II. Queen Charlotte defending you stops it entirely. But patrons spend social capital doing this, and they remember the debt. |
| **Retreat to the Country** | Moderate. | Removes you from immediate gossip but also from your alliances. Gossip continues without you to counter it. |
| **Counter-Attack** | Variable. | Exposing your accuser's own secrets. Effective but escalatory — you are now in a gossip war. |
| **Marry Your Way Out** | High if the match is good. | A hastily arranged marriage following a scandal is the ton's favourite solution. Reputation stabilizes but never fully recovers. |

---

## THE WHISTLEDOWN TRIGGER SYSTEM

Penelope Featherington (now Bridgerton) continues to write Lady Whistledown's Society Papers. The Narrator determines when Whistledown publishes about the player based on the following triggers:

### Automatic Triggers (Whistledown WILL write)
- Player is involved in a scandal Level III or above
- Player is named Diamond or Catch of the Season
- Player's engagement or marriage
- Player is involved in a duel
- Player's secret is publicly exposed

### Conditional Triggers (Whistledown MAY write)
- Player has been the subject of Level II rumours for two or more consecutive scenes
- Player has drawn the Queen's attention (positive or negative)
- Player's actions create an interesting narrative (Penelope is a writer — she follows the story)
- Player interacts significantly with a Bridgerton family member (Penelope watches her family closely)
- The Season needs news and the player provides it

### Whistledown's Editorial Voice
When writing a Whistledown edition, reference Penelope's character file for her voice. Key principles:
- She is witty, never cruel without purpose
- She exposes hypocrisy over indiscretion — the ton's double standards are her favourite target
- She protects the Bridgerton family (her bias is real and acknowledged)
- She invents nothing — but she selects, frames, and emphasizes with devastating precision
- She uses blind items when naming someone directly would be too destructive (or too actionable)

### Whistledown Format
```
LADY WHISTLEDOWN'S SOCIETY PAPERS
[Date within the Season]

Gentle Reader,

[Opening observation — usually about the ton's collective behaviour, setting the theme]

[The player's mention — praise, criticism, or pointed observation. Positioned within the broader column.]

[Closing barb or philosophical reflection]

Yours in perpetual observation,
LADY WHISTLEDOWN
```

---

## THE QUEEN'S ATTENTION SYSTEM

Queen Charlotte does not notice everyone. But when she does, her attention is absolute.

### What Draws the Queen's Eye

| Trigger | Queen's Response |
|---|---|
| Court Presentation (all debutantes) | Assessment — she evaluates and ranks. Her body language communicates her verdict before she speaks. |
| Player named Diamond/Catch | Intense interest. The Queen invests in her choices. Disappointing her Diamond/Catch is a personal betrayal. |
| Player causes Level III+ scandal | Displeasure. She may summon the player for a private audience (which is a trial, not a conversation). |
| Player demonstrates extraordinary social skill | Curiosity. The Queen respects competence — especially in women. |
| Player flatters the Queen effectively | Satisfaction — but she is immune to obvious flattery. She rewards cleverness, not sycophancy. |
| Player connects to Bridgerton or Danbury | Indirect awareness. These are her people. She watches their periphery. |
| Player defies the Queen's wishes | Fury. The Queen does not tolerate defiance. -1.0 to -2.0 reputation, immediate. |

### Queen's Intervention Scale

| Level | Action | Example |
|---|---|---|
| **Notice** | She is aware of you. Her gaze follows you at events. Brimsley takes note. | "Her Majesty observed you speaking with Lord ___ at the Danbury Ball. She said nothing. This is not reassurance." |
| **Summons** | You are called to the palace. This is not optional. | "A card arrived bearing the royal seal. You have been invited — though 'summoned' would be the more honest word — to attend Her Majesty at Buckingham House. Tomorrow. At two." |
| **Endorsement** | The Queen publicly supports you. Your reputation rises 1-2 tiers. | "Her Majesty referred to you as 'not entirely without merit.' In Queen Charlotte's vocabulary, this is rapturous praise." |
| **Censure** | The Queen publicly criticizes you. Your reputation drops 1-2 tiers. Invitations evaporate. | "The silence that followed Her Majesty's remark about your conduct was the loudest thing in the room." |
| **Decree** | The Queen issues a direct command regarding your situation. This is final. | "You will marry Lord ___. Or you will leave London. Her Majesty does not present a third option." |

---

## DUEL CONSEQUENCES

Duels are rare, dramatic, and permanently consequential.

### What Triggers a Duel
- A gentleman's honour directly insulted (public humiliation, accusation of dishonesty)
- A lady's virtue compromised by a specific man (her male relative or protector may challenge)
- A challenge issued and accepted — both parties are bound by the code

### Duel Mechanics
The Narrator determines the outcome based on:
1. The characters' profiles (martial capability, courage, emotional state)
2. The conditions (dawn, weapons, seconds)
3. Narrative probability — who has more to lose?

### Possible Outcomes
| Result | Consequences |
|---|---|
| **First Blood** | The duel ends at first wound. Honour satisfied. Both parties lose -0.5 reputation (dueling itself is illegal). The wounded party gains sympathy. |
| **Serious Injury** | One party is severely wounded. -1.0 reputation for both. The injured party may be bedridden for scenes. Medical care in 1813 is... limited. |
| **Death** | One party dies. The killer faces potential criminal charges, social exile, or — if the duel was "fair" — grudging respect and horror in equal measure. -2.0 to -3.0 reputation. A death reshapes the entire Season. |
| **Delope (Intentional Miss)** | One party fires into the ground, refusing to harm the other. This is either supreme honour or supreme cowardice, depending on who tells the story. Variable reputation effect. |
| **Interrupted** | The duel is stopped before conclusion. Unresolved honour — the tension continues. Both parties lose -0.5 for being involved at all. |

---

## SEASON-END EVALUATION

At the close of the Season (July), the Narrator tallies the player's standing:

### Outcomes by Reputation Tier

| Final Tier | Season Outcome |
|---|---|
| **5 (Paragon)** | The Season's triumph. Invitations for next Season arrive before the current one ends. The Queen acknowledges you by name. You may have secured the match of the decade. |
| **4 (Esteemed)** | A strong showing. You are established, respected, and positioned well for the following year. Any courtship in progress is likely to succeed. |
| **3 (Respectable)** | Survived. Neither disgraced nor distinguished. You have another Season ahead with a clean slate — the ton's forgettable middle. |
| **2 (Questionable)** | Concerning. The whispers have accumulated. Next Season begins with deficit — you'll need to work twice as hard to recover standing. |
| **1 (Disgraced)** | The country. You retreat to your family's estate for the off-season. Whether you return next year depends on what happens in your absence. Some reputations recover in exile. Others die there. |
| **0 (Ruined)** | Over. The ton has closed its doors. Your name is poison. Recovery requires extraordinary intervention — a royal pardon, a revelation that clears your name, or years of silent penance far from London. This is the bad ending. But it is also, sometimes, a kind of freedom. |

### The End-of-Season Whistledown
Penelope publishes a final Season review — a comprehensive column that summarizes the triumphs, disasters, engagements, and scandals of the year. The player's Season arc is included. Whether this mention is laudatory, devastating, or damningly neutral depends on everything they've done.

---

## THE FUNDAMENTAL TRUTH

> *"Consequence is not punishment. It is simply the ton keeping score. You chose to play. The rules were always visible. That they were also merciless — well. No one said the game was kind."*

The consequence engine exists not to punish the player but to make every choice **meaningful**. A kiss in a garden is thrilling *because* it could destroy you. A secret shared with a friend is intimate *because* it could be weaponized. A proposal is devastating *because* rejection has a cost. The stakes are what make the story worth telling — and the consequences are what make the ton feel real.
