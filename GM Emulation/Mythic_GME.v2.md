# Mythic Game Master Emulator

## Dice Rollers

| Check/Table               | Die Result                         |
| ------------------------- | ---------------------------------- |
| Fate Check (2d10+1d10)    | `dice: 2d10` + `dice: 1d10`        |
| Scene Setup (1d10)        | `dice: 1d10`                       |
| Standard Focus Table      | `dice: [[Mythic_GME#^EFStandard]]` |
| Action 1 (Verb)           | `dice: [[Mythic_GME#^MVerb]]`      |
| Action 2 (Subject)        | `dice: [[Mythic_GME#^MSubject]]`   |
| Description 1 (Adverb)    | `dice: [[Mythic_GME#^MAdverb]]`    |
| Description 2 (Adjective) | `dice: [[Mythic_GME#^MAdjective]]` |

**Event Focus Themes:**

| Focus Table     | Dice Result                         |
| --------------- | ----------------------------------- |
| Standard Focus  | `dice: [[Mythic_GME#^EFStandard]]`  |
| Horror Focus    | `dice: [[Mythic_GME#^EFHorror]]`    |
| Adventure Focus | `dice: [[Mythic_GME#^EFAdventure]]` |
| Epic Focus      | `dice: [[Mythic_GME#^EFEpic]]`      |
| Social Focus    | `dice: [[Mythic_GME#^EFSocial]]`    |
| Personal Focus  | `dice: [[Mythic_GME#^EFPersonal]]`  | 

___

# Mythic GME

### Scene Setup

* Roll __1d10__. If die face is under the Chaos Factor AND...
	* ODDS: Altered Scene
	* EVENS: Interrupt Scene

### Fate Check

* 2d10 Results (10- No / 11+ Yes) plus/minus modifiers
	* See charts below.
* When the Chaos Die is within/under the Chaos Factor AND Fate Dice are...
	* both ODD: Exceptional Yes/No
	* both EVEN: Random Event
	* both SAME: Exceptional result and Random Event

| Odds                        | Modifiers |
| --------------------------- | --------- |
| 50/50 Or Unsure             | *None*    |
| Likely / Unlikely           | *+2 / -2* |
| Very Likely / Very Unlikely | *+4 / -4* |
| Sure Thing / No Way         | *+6 / -6* |
| Has To Be / Impossible      | *+8 / -8* |

| Chaos Factor                | Modifiers |
| --------------------------- | --------- |
| *Cf 3:* |  -/+2 Toward Favorable |
| Cf 4-5:  | No modifier |
|*Cf 6:* | -/+2 Toward Unfavorable |

| Resisted Ranks                       | Modifiers                                                            |
| ------------------------------------ | -------------------------------------------------------------------- |
| Acting Rank<br>vs<br>Difficulty Rank | The Difference in Rank Shifts<br>(+ if AR is higher, - if AR is lower). | 

---

### Event Focus Tables

##### Standard Focus Table

| dice: 1d100 | Result                  |
| ----------- | ----------------------- |
| 1-7         | Remote event            |
| 8-28        | NPC action              |
| 29-35       | New NPC                 |
| 36-45       | Move toward a thread    |
| 46-52       | Move away from a thread |
| 53-55       | Close a thread          |
| 56-67       | PC negative             |
| 68-75       | PC positive             |
| 76-83       | Ambiguous event         |
| 84-92       | NPC negative            |
| 93-100      | NPC positive            |
^EFStandard


##### Horror Focus Table

| dice: 1d100 | Result                  |
| ----------- | ----------------------- |
| 1-10        | Horror - PC             |
| 11-23       | Horror - NPC            |
| 24-30       | Remote event            |
| 31-49       | NPC action              |
| 50-52       | New NPC                 |
| 53-55       | Move toward a thread    |
| 56-62       | Move away from a thread |
| 63-72       | PC negative             |
| 73-75       | PC positive             |
| 76-82       | Ambiguous event         |
| 83-97       | NPC negative            |
| 98-100      | NPC positive            |
^EFHorror

##### Adventure Focus Table

| dice: 1d100 | Result                  |
| ----------- | ----------------------- |
| 1-16        | Action!                 |
| 17-24       | Remote event            |
| 25-44       | NPC action              |
| 45-52       | New NPC                 |
| 53-56       | Move toward a thread    |
| 57-64       | Move away from a thread |
| 65-76       | PC negative             |
| 77-80       | PC positive             |
| 81-84       | Ambiguous event         |
| 85-96       | NPC negative            |
| 97-100      | NPC positive            |
^EFAdventure

##### Epic Focus Table

| dice: 1d100 | Result                  |
| ----------- | ----------------------- |
| 1-12        | Thread escalates        |
| 13-16       | Remote event            |
| 17-30       | NPC action              |
| 31-42       | New NPC                 |
| 43-46       | Move toward a thread    |
| 47-58       | Move away from a thread |
| 59-72       | PC negative             |
| 73-80       | PC positive             |
| 81-84       | Ambiguous event         |
| 85-92       | NPC negative            |
| 93-100      | NPC positive            |
^EFEpic

##### Social Focus Table

| dice: 1d100 | Result                  |
| ----------- | ----------------------- |
| 1-12        | Drop a bomb!            |
| 13-24       | Remote event            |
| 25-36       | NPC action              |
| 37-44       | New NPC                 |
| 45-56       | Move toward a thread    |
| 57-60       | Move away from a thread |
| 61-64       | Close a thread          |
| 65-72       | PC negative             |
| 73-80       | PC positive             |
| 81-92       | Ambiguous event         |
| 93-96       | NPC negative            |
| 97-100      | NPC positive            |
^EFSocial

##### Personal Focus Table

| dice: 1d100 | Result                     |
| ----------- | -------------------------- |
| 1-7         | Remote event               |
| 8-24        | NPC action                 |
| 25-28       | PC NPC action              |
| 29-35       | New NPC                    |
| 36-42       | Move toward a thread       |
| 43-45       | Move toward a PC thread    |
| 46-50       | Move away from a thread    |
| 51-52       | Move away from a PC thread |
| 53-54       | Close thread               |
| 55          | Close PC thread            |
| 56-67       | PC negative                |
| 68-75       | PC positive                |
| 76-83       | Ambiguous event            |
| 84-90       | NPC negative               |
| 91-92       | PC NPC negative            |
| 93-99       | NPC positive               |
| 100         | PC NPC positive            |
^EFPersonal

### Meaning Tables

##### Meaning Description 1 - Adverb

| dice: d100 | Adverb           |
| ---------- | ---------------- |
| 1          | Abnormally       |
| 2          | Adventurously    |
| 3          | Aggressively     |
| 4          | Angrily          |
| 5          | Anxiously        |
| 6          | Awkwardly        |
| 7          | Beautifully      |
| 8          | Bleakly          |
| 9          | Boldly           |
| 10         | Bravely          |
| 11         | Busily           |
| 12         | Calmly           |
| 13         | Carefully        |
| 14         | Carelessly       |
| 15         | Cautiously       |
| 16         | Ceaselessly      |
| 17         | Cheerfully       |
| 18         | Coolly           |
| 19         | Crazily          |
| 20         | Curiously        |
| 21         | Daintily         |
| 22         | Dangerously      |
| 23         | Defiantly        |
| 24         | Deliberately     |
| 25         | Delightfully     |
| 26         | Dimly            |
| 27         | Efficiently      |
| 28         | Energetically    |
| 29         | Enormously       |
| 30         | Enthusiastically |
| 31         | Excitedly        |
| 32         | Fearfully        |
| 33         | Ferociously      |
| 34         | Fiercely         |
| 35         | Foolishly        |
| 36         | Fortunately      |
| 37         | Frantically      |
| 38         | Freely           |
| 39         | Frighteningly    |
| 40         | Fully            |
| 41         | Generously       |
| 42         | Gently           |
| 43         | Gladly           |
| 44         | Gracefully       |
| 45         | Gratefully       |
| 46         | Happily          |
| 47         | Hastily          |
| 48         | Healthily        |
| 49         | Helpfully        |
| 50         | Helplessly       |
| 51         | Hopelessly       |
| 52         | Innocently       |
| 53         | Intensely        |
| 54         | Interestingly    |
| 55         | Irritatingly     |
| 56         | Jovially         |
| 57         | Joyfully         |
| 58         | Judgementally    |
| 59         | Kindly           |
| 60         | Kookily          |
| 61         | Lazily           |
| 62         | Lightly          |
| 63         | Loosely          |
| 64         | Loudly           |
| 65         | Lovingly         |
| 66         | Loyally          |
| 67         | Majestically     |
| 68         | Meaningfully     |
| 69         | Mechanically     |
| 70         | Miserably        |
| 71         | Mockingly        |
| 72         | Mysteriously     |
| 73         | Naturally        |
| 74         | Neatly           |
| 75         | Nicely           |
| 76         | Oddly            |
| 77         | Offensively      |
| 78         | Officially       |
| 79         | Partially        |
| 80         | Peacefully       |
| 81         | Perfectly        |
| 82         | Playfully        |
| 83         | Politely         |
| 84         | Positively       |
| 85         | Powerfully       |
| 86         | Quaintly         |
| 87         | Quarrelsomely    |
| 89         | Quietly          |
| 90         | Roughly          |
| 91         | Rudely           |
| 92         | Ruthlessly       |
| 93         | Slowly           |
| 94         | Softly           |
| 95         | Swiftly          |
| 96         | Threateningly    |
| 97         | Very             |
| 98         | Violently        |
| 99         | Wildly           |
| 100        | Yieldingly       |

^MAdverb

##### Meaning Description 2 - Adjective

| dice: d100 | Adjective    |
| ---------- | ------------ |
| 1          | Abandoned    |
| 2          | Abnormal     |
| 3          | Amusing      |
| 4          | Ancient      |
| 5          | Aromatic     |
| 6          | Average      |
| 7          | Beautiful    |
| 8          | Bizarre      |
| 9          | Classy       |
| 10         | Clean        |
| 11         | Cold         |
| 12         | Colorful     |
| 13         | Creepy       |
| 14         | Cute         |
| 15         | Damaged      |
| 16         | Dark         |
| 17         | Defeated     |
| 18         | Delicate     |
| 19         | Delightful   |
| 20         | Dirty        |
| 21         | Disagreeable |
| 22         | Disgusting   |
| 23         | Drab         |
| 24         | Dry          |
| 25         | Dull         |
| 26         | Empty        |
| 27         | Enormous     |
| 28         | Exotic       |
| 29         | Faded        |
| 30         | Familiar     |
| 31         | Fancy        |
| 32         | Fat          |
| 33         | Feeble       |
| 34         | Feminine     |
| 35         | Festive      |
| 36         | Flawless     |
| 37         | Fresh        |
| 38         | Full         |
| 39         | Glorious     |
| 40         | Good         |
| 41         | Graceful     |
| 42         | Hard         |
| 43         | Harsh        |
| 44         | Healthy      |
| 45         | Heavy        |
| 46         | Historical   |
| 47         | Horrible     |
| 48         | Important    |
| 49         | Interesting  |
| 50         | Juvenile     |
| 51         | Lacking      |
| 52         | Lame         |
| 53         | Large        |
| 54         | Lavish       |
| 55         | Lean         |
| 56         | Less         |
| 57         | Lethal       |
| 58         | Lonely       |
| 59         | Lovely       |
| 60         | Macabre      |
| 61         | Magnificent  |
| 62         | Masculine    |
| 63         | Mature       |
| 64         | Messy        |
| 65         | Mighty       |
| 66         | Military     |
| 67         | Modern       |
| 68         | Extravagant  |
| 69         | Mundane      |
| 70         | Mysterious   |
| 71         | Natural      |
| 72         | Nondescript  |
| 73         | Odd          |
| 74         | Pale         |
| 75         | Petite       |
| 76         | Poor         |
| 77         | Powerful     |
| 78         | Quaint       |
| 79         | Rare         |
| 80         | Reassuring   |
| 81         | Remarkable   |
| 82         | Rotten       |
| 83         | Rough        |
| 84         | Ruined       |
| 85         | Rustic       |
| 86         | Scary        |
| 87         | Simple       |
| 88         | Small        |
| 89         | Smelly       |
| 90         | Smooth       |
| 91         | Soft         |
| 92         | Strong       |
| 93         | Tranquil     |
| 94         | Ugly         |
| 95         | Valuable     |
| 96         | Warlike      |
| 97         | Warm         |
| 98         | Watery       |
| 99         | Weak         |
| 100        | Young        |
^MAdjective

##### Meaning Action 1 - Verb

| dice: d100 | Action        |
| ---------- | ------------- |
| 1          | Attainment    |
| 2          | Starting      |
| 3          | Neglect       |
| 4          | Fight         |
| 5          | Recruit       |
| 6          | Triumph       |
| 7          | Violate       |
| 8          | Oppose        |
| 9          | Malice        |
| 10         | Communicate   |
| 11         | Persecute     |
| 12         | Increase      |
| 13         | Decrease      |
| 14         | Abandon       |
| 15         | Gratify       |
| 16         | Inquire       |
| 17         | Antagonize    |
| 18         | Move          |
| 19         | Waste         |
| 20         | Truce         |
| 21         | Release       |
| 22         | Befriend      |
| 23         | Judge         |
| 24         | Desert        |
| 25         | Dominate      |
| 26         | Procrastinate |
| 27         | Praise        |
| 28         | Separate      |
| 29         | Take          |
| 30         | Break         |
| 31         | Heal          |
| 32         | Delay         |
| 33         | Stop          |
| 34         | Lie           |
| 35         | Return        |
| 36         | Imitate       |
| 37         | Struggle      |
| 38         | Inform        |
| 39         | Bestow        |
| 40         | Postpone      |
| 41         | Expose        |
| 42         | Haggle        |
| 43         | Imprison      |
| 44         | Release       |
| 45         | Celebrate     |
| 46         | Develop       |
| 47         | Travel        |
| 48         | Block         |
| 49         | Harm          |
| 50         | Debase        |
| 51         | Overindulge   |
| 52         | Adjourn       |
| 53         | Adversity     |
| 54         | Kill          |
| 55         | Disrupt       |
| 56         | Usurp         |
| 57         | Create        |
| 58         | Betray        |
| 59         | Agree         |
| 60         | Abuse         |
| 61         | Oppress       |
| 62         | Inspect       |
| 63         | Ambush        |
| 64         | Spy           |
| 65         | Attach        |
| 66         | Carry         |
| 67         | Open          |
| 68         | Carelessness  |
| 69         | Ruin          |
| 70         | Extravagance  |
| 71         | Trick         |
| 72         | Arrive        |
| 73         | Propose       |
| 74         | Divide        |
| 75         | Refuse        |
| 76         | Mistrust      |
| 77         | Deceive       |
| 78         | Cruelty       |
| 79         | Intolerance   |
| 80         | Trust         |
| 81         | Excitement    |
| 82         | Activity      |
| 83         | Assist        |
| 84         | Care          |
| 85         | Negligence    |
| 86         | Passion       |
| 87         | Work          |
| 88         | Control       |
| 89         | Attract       |
| 90         | Failure       |
| 91         | Pursue        |
| 92         | Vengeance     |
| 93         | Proceedings   |
| 94         | Dispute       |
| 95         | Punish        |
| 96         | Guide         |
| 97         | Transform     |
| 98         | Overthrow     |
| 99         | Oppress       |
| 100        | Change        |
^MVerb

##### Meaning Action 2 - Subject

| dice: d100 | Subject        |
| ---------- | -------------- |
| 1          | Goals          |
| 2          | Dreams         |
| 3          | Environment    |
| 4          | Outside        |
| 5          | Inside         |
| 6          | Reality        |
| 7          | Allies         |
| 8          | Enemies        |
| 9          | Evil           |
| 10         | Good           |
| 11         | Emotions       |
| 12         | Opposition     |
| 13         | War            |
| 14         | Peace          |
| 15         | Innocent       |
| 16         | Love           |
| 17         | Spirit         |
| 18         | Intellect      |
| 19         | Ideas          |
| 20         | Joy            |
| 21         | Messages       |
| 22         | Energy         |
| 23         | Balance        |
| 24         | Tension        |
| 25         | Friendship     |
| 26         | Physical       |
| 27         | Project        |
| 28         | Pleasures      |
| 29         | Pain           |
| 30         | Possessions    |
| 31         | Benefits       |
| 32         | Plans          |
| 33         | Lies           |
| 34         | Expectations   |
| 35         | Legal          |
| 36         | Bureaucracy    |
| 37         | Business       |
| 38         | Path           |
| 39         | News           |
| 40         | Exterior       |
| 41         | Advice         |
| 42         | Plot           |
| 43         | Competition    |
| 44         | Prison         |
| 45         | Illness        |
| 46         | Food           |
| 47         | Attention      |
| 48         | Success        |
| 49         | Failure        |
| 50         | Travel         |
| 51         | Jealousy       |
| 52         | Dispute        |
| 53         | Home           |
| 54         | Investment     |
| 55         | Suffering      |
| 56         | Wishes         |
| 57         | Tactics        |
| 58         | Stalemate      |
| 59         | Randomness     |
| 60         | Misfortune     |
| 61         | Death          |
| 62         | Disruption     |
| 63         | Power          |
| 64         | Burden         |
| 65         | Intrigues      |
| 66         | Fears          |
| 67         | Ambush         |
| 68         | Rumor          |
| 69         | Wounds         |
| 70         | Extravagance   |
| 71         | Representative |
| 72         | Adversities    |
| 73         | Opulence       |
| 74         | Liberty        |
| 75         | Military       |
| 76         | Mundane        |
| 77         | Trials         |
| 78         | Masses         |
| 79         | Vehicle        |
| 80         | Art            |
| 81         | Victory        |
| 82         | Dispute        |
| 83         | Riches         |
| 84         | Normal         |
| 85         | Technology     |
| 86         | Hope           |
| 87         | Magic          |
| 88         | Illusions      |
| 89         | Portals        |
| 90         | Danger         |
| 91         | Weapons        |
| 92         | Animals        |
| 93         | Weather        |
| 94         | Elements       |
| 95         | Nature         |
| 96         | Masses         |
| 97         | Leadership     |
| 98         | Fame           |
| 99         | Anger          |
| 100        | Information    |
^MSubject

## References

* [Mythic Game Master Emulator](https://www.drivethrurpg.com/product/20798/Mythic-Game-Master-Emulator)
* [Mythic Magazine](https://www.drivethrurpg.com/browse/pub/480/Word-Mill/subcategory/1393_37897/Mythic-Magazine)

## Attributions

> [!Important]
> The Location Crafter, Mythic RPG, Mythic Game Master Emulator, Mythic Variations 1 & 2 and Mythic Magazine are properties of Word Mill Games and Tana Pigeon. Visit https://wordmillgames.com for more information.
