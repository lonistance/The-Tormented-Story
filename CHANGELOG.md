# Changelog

**#29 (2026-08-18) — New `STORY_BIBLE.md`: AI writing bible v1.0 (style rules + repo canon)**
- **Content**: created `STORY_BIBLE.md` — the user-provided "The Tormented AI writing rules (v1.0)" consolidated into a standing constraint file, augmented with this repo's established canon; all future chapters must be written against it —
  - 0. Usage: every chapter prompt organized as 【PROJECT】【CANON】【STYLE BIBLE】【CHARACTER BIBLE】【PREVIOUS CHAPTER】【CURRENT CHAPTER PURPOSE】【CURRENT CHAPTER OUTLINE】【FORBIDDEN】【OUTPUT】; 【OUTPUT】 is prose only.
  - 1. Highest priority: not "hero becomes legend" but "an ordinary man misreads strength/love/responsibility — legend — laying the legend down"; Kael is first a person; "the reader always knows a little more than Kael".
  - 2–3. World & volume structure: gods beyond good/evil (War God's verdict, Neow's three hidden truths), Emberstone tribe, mixed-blood taboo, seven-volume timeline and file conventions.
  - 4. Character bible: Kael ("I must prove I deserve to stay" + misreading chain + unreliable childhood memory), Adrian (imperfect mentor, acts not speaks, true-name rule), Erian ("Long-Legged Doctor" persona, reversal-seed payoff chain), Serin/Gar, Mira (the hand-made necklace), Eilin (counterpoint to Kael, seeking her father, duel core), the War God, Neow.
  - 5. Narration & style: limited third person, future voice at most once per chapter, emotion through action, restraint (wife's death only via objects/survivors/rumors/environment/reaction), age-appropriate dialogue, legend principle, combat/growth/happiness/tragedy/foreshadow/prophecy rules.
  - 6. Key beats: both challenges to the god, ordinary-life period, the leaving-home paradox, vol3 Erian redesign.
  - 7–11. Forbidden list, the 12 pre-chapter questions, six post-chapter checks, never "improve" the characters for the author, final philosophy ("he finally no longer needs to be anything").
- **Docs**: new `STORY_BIBLE.md`.
- **Verification**: UTF-8 no BOM.

**#30 (2026-08-18) — Volume 2《持剑的孩子》polish: drop the "master" address, cut interpretive narration**
- **Content**: per the author's full-volume review of Volume 2 (core flaw = over-explanation: four voices — author, narrator, future Kael, Adrian — explaining the same thing; restraint 6.5/10, narration discipline 6.5/10), polished `第二卷 持剑的孩子.md` (all 15 chapters) —
  - Address system reset: **99 occurrences of "师父" deleted volume-wide**, replaced with — bare "你" in dialogue, no title ("教我剑术吧。" "你从前……信过剑吗？"); daily "骑士"; the intimate word only in the heart ("爹" almost spoken by the spring, swallowed); narration uses "骑士/那个人". Chapter 3's "uttering 师父" scene rewritten as a word stuck in the throat (the absence of a name for him mirrors his own namelessness), tying into the "爹" seed (谁家孩子跟爹长得像了); the key line becomes "你从不夸我。所以我还不够好。" (same person as ch12's "你从来没夸过我"); in ch12 Kael tells the soldier "我跟着一个赶路的练剑" (echoing the name 赶路的). Ch14's true-name reveal ("艾德里安·瓦尔") untouched; the farewell's only vocative is now "……骑士？".
  - Interpretive narration cut ~30–40%: removed the two lines the author named ("这句话，一半是说他的，另一半，是说骑士自己的。" "能说得出'认为自己只能成为怪物'是什么滋味的人……"), the three-strike structural spoiler of "认为自己只能成为怪物的人", ch4's "师父在等一个问题" exposition, ch5's duplicated "同一堂课" statement and the "我希望你不会像我一样" future-echo, ch8's "逃到神的高度上去" spoiler, ch9's "等你不想学的时候" echo, ch4's "从一道伤口里挤出去" advance notice, ch3's "自己也走在没有尽头的路上" exposition; trimmed ch1's triple "放走敌人" clauses, ch4's "拿/收" expansion, ch5's duplicated "many-years-later in the yard" passage (the chapter's tight version kept), ch7's "赢了所有的仗" spoiler (only "这条路他将来也会走一遍" kept), etc.
  - Kept true fate-echoes: ch2's "我见过很多比印记更可怕的东西" later spoken to another person; ch6's generational nightmare replication; ch8's "对不起"; ch9's "你已经赢了"→"你的剑很锋利——但它让我安心"; ch10's "你已经足够好了" to his child; ch12's daughter "想离开，先打败我"; ch14's "我不会失败／我不是这个意思" understood decades later.
  - Synced `小说大纲.md` (10 师父-related entries: the address beat, key lines, true-name rule wording).
- **Next**: retry pushing `2667fc6` (STORY_BIBLE commit, push previously failed).
- **Verification**: UTF-8 no BOM; grep "师父" zero hits in prose (only CHANGELOG history and STORY_BIBLE's forbidden-item list remain).

---

**#28 (2026-08-18) — Volume 1《血痕之子》polish: let the twelve-year-old be just a child**
- **Content**: revised `第一卷 血痕之子.md` per the reader's full review of the volume (structure and themes untouched; editorial subtraction/addition only) —
  - **Prophecy made ambiguous (ch1)**: removed the explicit reveal that the prophecy said "随他而来" not "因他而来"; instead the crowd asks what it means and Toron answers nothing; that night he recites the line to himself and finds "he cannot read it correctly either" — the reader knows there is ambiguity but not the answer; Toron is not a simple villain but a priest unsure of himself (the seed of fear turning the prophecy into a self-fulfilling one).
  - **The wolf night gains expectation (ch4)**: after the wolves flee, Kael's heart is warm — he has the words "没事了，狼走了" ready — and turns to find the children standing a few paces away, unmoving; no one thanks him, no one calls his name; "那声'没事了'卡在他的喉咙里". His first heroic act directly meets "no one loves him for it".
  - **Kael's own choices (four new beats; innocent motives, self-harmful acts)**: ch3 — to prove he is not sick, he secretly pours his medicine into the grass by the wall (that patch of grass dies); at the chasing game "the poured medicine comes back to collect" and, asked if he hurts, "he does not dare mention the medicine poured into the grass". Ch5 — he goes into the mountains alone to hunt a boar and nearly has his flank ripped open (Gar's only reply while dressing the wound: "下回，叫我"); he deliberately picks the tallest section of fence to train balance; he publicly challenges the strongest hunter, is floored bare-handed, gets up and says "再来", trains in the snow until moonrise, concluding "还是不够" rather than "我不该来".
  - **Moments of warmth added**: ch3 — Mairy at the window ("那你快点好"); ch5 — Gar takes him into the mountains once, teaching tracks — "山不说话，但它会回答" ("the only mountain road his father ever walked with him").
  - **"Years later" limited to at most one per chapter**: ch2's long passage shortened; ch3's "buried into wilds, battlefields, piles of corpses" list removed (keeps "忘了"); ch7's closing list of "他不知道" trimmed from six items to three — dropping "become the strongest on the continent" and "he will return/ruins" (ruins already in ch6, kept there). The volume now keeps only: ch1's rain-night dream, ch4's "红印之子", ch6's ruins-and-necklace, ch7's three closing beats.
  - **Other**: ch7's farewell upgraded to the core-line variation ("等我足够强大，强到你们再也无法假装看不见我的时候"); ch4 adds "从那一夜起，那片印记不再只是生下来就带着的东西了" (seed of the third layer of "blood-marks"); ch6 adds "他始终不知道那句预言的原话……他要洗清的，是一件他连内容都不知道的罪" (the child-understandable version, not the truth).
  - Untouched: Gar's "argued once, just once", Serin's "活着，然后回家", the talisman and "你值得被爱", leaving home voluntarily (ch7) — all kept.
- **Docs**: `第一卷 血痕之子.md` only.
- **Next**: Volume 3《战争之子》Chapter 1《踏入战场》.
- **Verification**: UTF-8 no BOM.

---

**#27 (2026-08-18) — Kael's child is now a daughter: the shelved gender-swap assets become a second playable character**
- **Content**: Kael's child changed from a son (艾登) to a daughter (艾琳【拟定】, Eilin); all occurrences updated repo-wide —
  - `小说大纲.md`: vol5 "孩子出生（艾登【拟定】，儿子）" → "（艾琳【拟定】，女儿）"; vol6 chapter titles "父子最后一次对话"→"父女最后一次对话", "父子决斗"→"父女决斗"; two foreshadow-table mentions "第六卷父子决斗"→"第六卷父女决斗"; character-table row 艾登（Aiden）【拟定】/儿子 → 艾琳（Eilin）【拟定】/女儿.
  - `第二卷 持剑的孩子.md`: ch12 close "当凯尔的儿子站在他面前"→"当凯尔的女儿站在他面前"; ch10 close "他把木剑扔在地上"→"她把木剑扔在地上"; ch13 close "拦住他走同一条路"→"拦住她走同一条路". All key lines remain unchanged as they are gender-neutral ("想离开，先打败我。" "你的剑很锋利——但它让我安心。" "我已经不是孩子了。").
  - Bilingual changelog history entries corrected in kind (#18/#21 etc.).
  - Erian's "grandson" thread untouched (vol4 ch6/ch7 and vol5 ch2 belong to Erian's descendants, unrelated to Kael's child).
- **Reason** (also recorded in README): while making the MOD, the author had jokingly produced a small set of gender-swapped ("性转版") assets for the character — shelved. Once the novel was decided upon, publishing that version himself would damage the character's literary/artistic image, so the shelved assets are given to Kael's daughter instead: she will exist as a (very likely unreleased) second playable character whose motive for entering the Spire is simple — to find her father. She will not receive full character development like The Tormented (and the author needs a rest).
- **Docs**: `README.md` gains a note section (备注：主角的孩子与性转废案资源); outline and Volume 2 text synced.
- **Next**: Volume 3 Chapter 1《踏入战场》.
- **Verification**: UTF-8 no BOM.

---

**#26 (2026-08-18) — Outline strengthening: the War God's grievance made explicit**
- **Content**: `小说大纲.md` — the War God's profile (worldview section) now carries the core beat explicitly: He does not hate victors — He hates those who win without understanding what victory means. When Kael cuts off His arm, His anger was never about losing, but that the man had won and still did not know what victory means. (This formalizes the beat already in vol4 ch11 "神明的愤怒" — "不是因失败愤怒，而是因为他没有理解" — into the god's standing profile, tying the vol3 ch13 memory of Erian to the vol4 ch10-11 arm scene.) Note: the Erian Sol redesign itself (ordinary survivor, deserter, saving enemies, the reversal-seed and its payoffs) had already been applied to the outline in `6cc572d` (CHANGELOG #25) — verified intact in vol3 header/ch5/ch7/ch8/ch11/ch12/ch13/ch15, vol4 ch6/ch7, vol5 ch2, character table, and god profile.
- **Docs**: none beyond outline.
- **Next**: Volume 3 Chapter 1《踏入战场》.
- **Verification**: UTF-8 no BOM.

---

**#25 (2026-08-18) — Outline revision: Erian Sol redesigned from idealist to ordinary survivor**
- **Content**: reworked `小说大纲.md` — Erian Sol is no longer an idealistic veteran who "believed war could change the world"; he is an ordinary man forced into war: home burned by the war, joined the army to fill his belly ("我参军，是因为军队管饭"), a war victim who witnessed mass death and war's dehumanization, the only un-brainwashed person Kael knows. He has an ordinary man's full set of flaws — fear of death, a history of desertion — yet never departs from humanity: he saves the wounded regardless of side ("敌人"), refuses mass killing. He is the antithesis of battlefield-god Kael: "an ordinary man surviving desperate odds". Chapters touched: vol3 ch5 (saving habit, not heroism; "救人不分敌我的习惯——第八章他挡在降兵面前的原因"), ch7 (past is an accountant's ledger, not an idealist's confession; "我杀死的每一个敌人，都留下一个新的敌人" as counted observation — he counted them), ch8 (his courage = blocking with shaking hands; a deserter knows where his line is), ch11 (leaves not out of weariness but "打不动了。我想回去种地"), ch12 (challenge: not "someone must stand up" but "我救的人，在那边" — the one time he forgets to run; "我怕。可我怕了，也得站在这儿"), ch13 (god stops not for character but because in ten thousand years He has never seen anyone so weak stand in His way; "我记住你了。" — the reversal-seed pays off: the God of War remembers not the strongest who fights without knowing why, but the weakest who dared defy Him), ch15 (god's gaze passes over Kael to another memory; "又一个寻求荣耀的人" while His memory holds one who never sought glory — half-payoff), vol4 ch6 (descendants: ordinary farm, "爷爷不是英雄……就是那一次，他说他忘了跑"), vol4 ch7 (god's memory: "我记住过一个凡人。不是你。" — full payoff), vol5 ch2 (grandson: "他说，那一天，他忘了跑。" — "我这辈子，就勇敢过一次。一次，够了。"), character table (now 老兵（逃兵）, role = the opposite of the battlefield god), and the War God's profile (remembers not strength but those who dare stand in His way — in ten thousand years, one).
- **Docs**: no text files changed.
- **Next**: Volume 3 Chapter 1《踏入战场》.
- **Verification**: UTF-8 no BOM.

---

**#24 (2026-08-18) — Volume 2 Chapter 15《雾中独白》（volume-final monologue）drafted — VOLUME 2 COMPLETE (15/15)**
- **Content**: appended to `第二卷 持剑的孩子.md` — the only chapter in the volume told as third-person-limited stream of consciousness (camera outside, thought inside): the knight alone in the mist at the crossroads where Kael vanished, an old man poor with words, thinking in fragments that self-correct. He remembers the first meeting (ch.1's evening, the waystation, five desperate men around the boy whose eyes had caught fire — a fire he recognizes, having housed one himself), and his first lesson was already about release: "握紧，但别攥死。" — he taught the gripping half for a winter; the other three words he only said, never taught. He asks whether he should never have taught him the sword, and snuffs the thought: the sword was not the cause, only the easier road — the fire was burning before him. His true failure is not technique (Kael's sword already surpasses him) but the "why": he taught every way to hold the sword and none to lay it down — laying it down is harder than picking it up, and "why" cannot pass from an old man's mouth; it must grow from a man's own blood. He waited six years for it to grow. Some sentences he practiced: "你已经足够好了" — mastered the night before the boy left, spoken to the dark; now, un-practiced, he says it whole into the mist, where no one hears — perhaps it was always meant for the fog. Then the word that makes his hand tighten on the rein: not a student, not a soldier, not a thing to be trained — my child. He has lost the most precious before; the taste of it: waking the next morning to a cold fire (left blank, unnamed). He fears losing again; he considers chaining the boy down and snuffs that too — that is not protection, that is caging a bird. Nothing he did was wrong, and yet right choices can still end in tragedy — the last thing he ever learned. He knows only one art: pulling people from fire; he pulled himself. What he never learned is standing aside while someone he would give everything for walks toward it, un-walkable — some farewells are not release but the admission that he cannot walk to the boy's end. Yet he will wait. "如果有一天，你累了，回来。" — he finally understands the sentence he spoke that morning: not a plea, a home. He turns back; the mill door was never barred; he picks up the hazel stick (its two notches), stands it by his bed; he kneels and rebuilds the fire; sitting on the threshold as the fog opens toward a southward dawn, the old horse blowing at the hay, he opens his mouth — a name turns on his tongue like a coin kept too long — and he swallows it back. The fire burns. The door stands open. He chooses to believe the child will return.
- **Docs**: `README.md` — Volume 2 marked complete (15/15). Volume header chapter list updated.
- **Next**: Volume 3《战争之子》Chapter 1《踏入战场》.
- **Verification**: UTF-8 no BOM.

---

**#23 (2026-08-17) — Volume 2 Chapter 14《分别》drafted, then rewritten per direction — VOLUME 2 COMPLETE (14/14)**
- **Content**: appended to `第二卷 持剑的孩子.md`, ending the volume — the climax of the volume, rewritten per direction: Kael is **eighteen** (six winters at the mill; "今天，他十八岁。"); the knight **spurs the old horse hard** to catch him before it is too late, dismounts, straightens his clothes — a formal occasion; and he opens with Kael's **full name** — "凯尔·阿伦。" — the first time in six years, because today is a formal farewell. The sword, plain and uninscribed, cloth-wrapped hilt tied by the rider's own hands: the giving itself is the recognition and the expectation — "六年。你把我教的东西，都学会了。" — and what he cannot say is passed through the object: go, do what you believe in — but do not become me. "我会让它成为传奇。" — the knight says nothing (he has seen that fire; he once had it, and it burned him to ash). The **name as the last lesson**: "艾德里安·瓦尔。" — neither confirming nor denying the bard's tale, he uses his own failure as the final curriculum: "那个人以为，一把剑可以结束战争。""他错了吗？""他输了。输得很彻底。他把能输的都输光了——仗、名字，还有他自己。""剑不是用来证明自己的。我用它证明过——证明到最后，连名字都证明丢了。你记住了。" — "你替我记住。" The embrace, the three sentences that miss: "如果有一天，你累了，回来。" / "我不会失败。" / "我不是这个意思。" — Kael does not understand, turns, walks the wide road, does not look back; the knight watches, the horse snorting into his palm, the cloak lifted by the wind. No tears. The close is deliberately flat: "那一年，凯尔·阿伦十八岁……他腰间那把剑，和他颈上那块护符，是同一种东西。那两句话——'我不会失败'，和'我不是这个意思'——他数十年后才听懂。听懂的时候，已经晚了。" All narration kept calm and restrained, the subject being heavy. (Pays off: ch6 "名字落在路上了", ch7's tale, ch10's swallowed sentence, ch13's "明天清晨，南边的大路上"; plants: the plain sword = vol 5's firewood and vol 6's village guard.)
- **Docs**: `README.md` — Volume 2 marked complete (14/14).
- **Next**: Volume 3《战争之子》Chapter 1《踏入战场》.
- **Verification**: UTF-8 no BOM.

---

**#22 (2026-08-17) — Volume 2 Chapter 13《凯尔离开骑士》drafted**
- **Content**: appended to `第二卷 持剑的孩子.md` — the countdown of last days (per direction, chapter 12 was the decision, chapter 13 is the parting, all restraint, no tears). The reverse-hand lesson finishes on the tenth morning ("成了。" — and the sentence he waited for leaves him hollow: 成了。然后呢？); the master's last lessons are about living, not winning — the hanging knot, the North Star, folding clothes so the pack stays dry ("打仗，也是活。"). Kael's hesitation, visible: he sits staring south toward the mother and child's road, the inner voice asking 你真的要去吗; his self-justification is honest and wrong — he has been homeless, he knows the taste of a lost home, he will end the war so no one else flees ("他要去的那场战争，正是让那个孩子发烧的那场战争" — the reader's foreshadow, mirrored in Volume 6 where he will stop his own child from the same road). The knight does not hold him back — three motives layered: he sees his own idealistic sixteen-year-old self; some answers can only be found alone; and the compensation — he has poured everything he knows into this boy, and wonders if the boy can find the answer he never found (剑之外，还有什么，能拦住那些兵). The confrontation lands per outline: "你教我握剑，现在为什么阻止我使用它？""因为剑不是你证明自己的方式。""那是什么？""保护。" — Kael hears "你还不够强"; "我要证明给你看。" — and the most honest sentence of the knight's life is thrown away: "遇到打不过的，就跑。跑不丢人。" — misheard as doubt: "我不会输！" The night beat: Kael wakes smiling from a dream of saving the child, and hears through the mill wall someone practicing a sentence he never learned to say, over and over, each repetition smoother, finally too soft to hear: "你已经足够好了。" — Kael almost rises to answer, and decides he will come back and hear it face to face (he never will). Dawn: he leaves the hazel stick — the first stick, with the reverse-hand notches — standing at the door like a person, and walks; the mill is silent, no one comes out; the window holds a figure who watches until the mist eats the road. Narrator's close: the last look at the mill, one more meeting on the south road tomorrow — the last in their lives; "证明给你看" will take years and be forgotten by the time it is proven; and one day he will block his own child with all his strength, exactly as the man at the window tried and failed.
- **Docs**: `README.md` — Volume 2 marked chapters 1-13 complete.
- **Next**: Volume 2 Chapter 14《分别》— the true parting: the plain sword, the hug, "如果有一天你累了，回来", "我不是这个意思", and the name (Adrian Vale) entering the text at last.
- **Verification**: UTF-8 no BOM.

---

**#21 (2026-08-17) — Volume 2 Chapter 12《战争的诱惑》drafted**
- **Content**: appended to `第二卷 持剑的孩子.md` — the war arrives along the road: refugees first (Kael knows the look now), then hooves. A cavalry squad camps by the mill — Kael's first real soldiers, and the ironic counterpoint the reader sees and he doesn't: the snake-like scar he envies, the child's shoe hanging on the biggest horse's saddle (he does not ask why), the wounded soldier's half-truths — "打赢了。乡里人没了。" — "别练到像我们一样，就晚了。" — words Kael takes for jokes. In the morning the old soldier watches his footwork: "这样的孩子，应该去战场！" — his blood catches fire; the knight's refusal lands as dismissal: "那里不是孩子该去的地方。""我已经不是孩子了！""正因为你还年轻。" — Kael speaks the chapter-10 line aloud at last: "你从来没夸过我。你从来不说我行。现在有人说我行，你又不让去。" — and the knight cannot explain why (the fire he knows from his own youth; no one stopped him either, and no one told him what lay ahead). The third day: Kael, packed, at the door; the knight carves two notches on the stick (the reverse-hand mark) and does not stop him: "要去，就去吧。""拦不住。""把反手练完，再上路。" — an anticlimax that empties the boy's gathered strength. That night the glory dream turns cold: the crowd, the horse, and then the little shoe swinging from the saddle — he wakes in a cold sweat, not knowing what he fears. Closing foreshadow per outline: years later, when his own daughter says "我已经不是孩子了", Kael hears himself give the old answer in a new form — "想离开，先打败我。" — and finally understands both why the man blocked him and why he finally did not.
- **Docs**: `README.md` — Volume 2 marked chapters 1-12 complete.
- **Next**: Volume 2 Chapter 13《凯尔离开骑士》.
- **Verification**: UTF-8 no BOM.

---

**#20 (2026-08-17) — Volume 2 Chapter 11《孩子的问题》drafted**
- **Content**: appended to `第二卷 持剑的孩子.md` — the occasion that prompts the question: a mother and fevered infant fleeing the border fighting pass the mill; Kael can't touch a burning child, his wooden sword cures no fever, the family must walk on ("后面的兵，追得紧" — the war, ch12's hinge, enters the frame as rumor); he gives the biscuit the master saved for him (the love of ch10 flows onward, unnamed). That night by the fire the boy's double dilemma: "是不是因为我还不够强？还是我练的方法错了？" — the knight, without confidence: "有些事，剑管用。有些事，剑管不了。管不了的那些……活到这把年纪，我也还是不知道该怎么办。" Then the interrogation and the answer: "你从前……信过剑吗？""信过。""信了很久。""那后来呢？" — he walks to the door, his shadow long as another man's; and the key line, spoken thin and unsteady: "……真正重要的，是你接受自己。" — then, dropping all pretense of authority: "这句话，是别人说给我听的。我自己，也没学会。" (The correct answer, given for the first time, for both of them — the answer he never lived.) Kael hears it as "don't care what others think," turns it into one more unmastered lesson, while his hunger for a nod and a bright look stays unhealed; the knight asks himself whether the sentence was meant for the boy or himself and does not follow the thought ("他没有想下去"). Ends with a fever-dream of chasing the family with a sword where his hands should be, and the volume-7 echo: Kael finally says the sentence to his own child and understands at last that it was never for him — it was the master speaking to himself; by the day he understands, the mill and the man are far away.
- **Docs**: `README.md` — Volume 2 marked chapters 1-11 complete.
- **Next**: Volume 2 Chapter 12《战争的诱惑》.
- **Verification**: UTF-8 no BOM.

---

**#19 (2026-08-17) — Volume 2 Chapter 10《骑士最大的错误》drafted, then rewritten per direction**
- **Content**: appended to `第二卷 持剑的孩子.md`. First draft narrated the knight's unspoken love one-sidedly; **rewritten** on direction to make the misunderstanding two-way, stop the narrator from naming the knight's true intent, and expose his past instead: (1) his loving acts without a word — wrapping the split hand (he presses his thumb on an old wrist scar, so it won't "speak"), the whole biscuit against his crumbs (his own six words: 这孩子，吃得下), the mended sleeve (the knight alone judges his own work: 一个逃兵的手，还能指望补出什么好的来) — each read by Kael as fuel for the sword, duty, "you still have a road to travel"; (2) the knight misreads the boy in turn: dawn collapse read as grit (the word 好兵 slips in his mind and is crushed), "我想要别人看见我" read as youthful fire ("有这口气，是好事"), even his asking read as a swordsmanship question; (3) why he cannot explain — not willful riddling: 他不敢回头看一眼自己的过去; the text explains to himself only as much as he lets himself; (4) the two wakes in the dark — the nightmare, the hand on the sword withdrawn, each decision made in the black: he resolves to place the boy somewhere and walk on alone ("这孩子跟着我，是跟错了人"), the boy resolves to become strong enough that the master will tell him his dreams; (5) the key line lands verbatim: "师父从不夸我。所以我还不够好。" — the knight answering real technique critique because he heard a question about the sword; (6) the greatest error shown by behavior alone: the boy has quietly been refilling his nights (the cold-sweat nights have stopped), and he misreads his own healing as tiredness — and would flee if he knew ("他不敢欠人。他这一辈子，欠得最多的，就是他自己。"); closing frame kept: the two fish waiting on either side of the fire, and the book's crucial emotional loop — "你已经足够好了" finally spoken through Kael's own mouth, years later, for his own child.
- **Docs**: `README.md` — Volume 2 marked chapters 1-10 complete.
- **Next**: Volume 2 Chapter 11《孩子的问题》.
- **Verification**: UTF-8 no BOM.

---

**#18 (2026-08-17) — Volume 2 Chapter 9《骑士教导凯尔》drafted**
- **Content**: appended to `第二卷 持剑的孩子.md` — the winter of training in the abandoned mill (frozen water wheel, cracked millstone): a full season of sword lessons written as parallel life lessons — the hazel branch before any sword ("等你握着棍子和握着剑一样稳，再摸剑"), standing in the snow ("冷是一面镜子——你急，镜子就晃"), the circle of footwork ("杀招从来不是往前的那一剑——是往回的那半步"), guarding ("守不住的人，攻出去也是送死"), the closing ("放出去收不回的剑，是一根扔出去的棍子"), all learned perfectly and not understood at all — water poured on stone. Kael's unnatural speed makes the knight quiet. The spring duel: Kael beats the guard — "你已经赢了。" — "可是我还可以更强。" The knight hears his young self in those exact words (no identity revealed); "你练的不是剑。""那我练的是什么？""你练的是怕。" The night interior: "我该教他什么，才能让他不变成我？" — the wall behind which the twelve-year-old holds the stone "你们什么时候，才会认可我"。Kael's own darkness: he fears not losing but being "enough" — once he is enough, no one will need to watch his sword, and he will be the unseen child again; "我什么时候，才算学成了？" — "等你不想学的时候。" Narrator foreword to the key lesson: "你已经赢了" will take a lifetime — he will finally say it, in another form, to his own child's trembling sword: "你的剑很锋利——但它让我安心。" (Volume 6's duel) And the closing irony: these winter days — fire, someone calling his name, a sword to train — are the days he will spend the rest of his life searching for, while he thinks only that they are not enough.
- **Docs**: `README.md` — Volume 2 marked chapters 1-9 complete.
- **Next**: Volume 2 Chapter 10《骑士最大的错误》.
- **Verification**: UTF-8 no BOM.

---

**#17 (2026-08-17) — Volume 2 Chapter 8《骑士的觉悟》drafted (reflection shown without traces, no reveal)**
- **Content**: appended to `第二卷 持剑的孩子.md` — the awakening rendered through behavior and third-person commentary, never through confession: the mayor's invitation to stay (the "留下来" motif echoed from the 柴房 offer) refused — Kael cannot understand; the war-worn veteran's probing answered with non-answers ("记不清了" — evasion shown as behavior); Kael's question about Adrian's later fate draws the master's deepest self-reflection disguised as commentary on the legend: "一开始是赎罪。赎不动，就变成了逃。" — "逃的人，是不给自己设终点的。他不敢停。停下来了，旧账就会追上来。" — "放下剑容易——可放下剑之前，你得先放下那个拿剑的自己。" — not one "我" in the chapter. Kael misreads everything again: he vows to settle all accounts cleanly, once and for all (the Adrian road he will actually walk); the creed lines land: "有时候，一把剑不如一根绳子。" and, at the wagon fire, "教你剑，是让你有一天不需要剑。" The unfinished awakening: at midnight the master polishes his sword like an apology and breathes one word — "对不起。" — the sword he cannot put down because he has not forgiven himself. Foreshadow: "逃" is the defect Kael will inherit (Volume 6); the reserved key line "我离开不是因为想走，是因为不敢停" stays banked until the parting chapter.
- **Docs**: `README.md` — Volume 2 marked chapters 1-8 complete; `小说大纲.md` — Chapter 8 outline refined with the no-reveal presentation method.
- **Next**: Volume 2 Chapter 9《骑士教导凯尔》.
- **Verification**: UTF-8 no BOM.

---

**#16 (2026-08-17) — Volume 2 Chapter 7《骑士的悲剧》drafted (true name in play, never pointed at)**
- **Content**: appended to `第二卷 持剑的孩子.md` — the tragedy told as a bard's tale at the Broken Barrel in Oakton: the young "胜利者"艾德里安·瓦尔, his three vows, "邪恶必须被消灭", the river-bank victory, the general slain, peace for one winter, then the revenge-chain, the nameless burning city, the dead one he had sworn to protect — "他赢了战争，却输掉了自己的名字"; the name buried by himself. Kael listens, stores "艾德里安·瓦尔" as a stranger's name, a cautionary tale ("别走那条路" — which he will walk anyway; narrator primes his Volumes 3-4 fate only). The master's self-judgment, verbatim per plan: "艾德里安·瓦尔是个傻瓜——至少曾经是。" — "他相信，杀了恶人，恶就没有了。" Kael's answer — kill them all and hold the peace — draws the quietest of replies: "他当年，也是这么想的。" Per the true-name rule: nothing in the text ever connects the knight to the name — no physical match, no narrator confirmation (the reveal awaits Chapter 13《分别》); the only cracks for the rereader are the fool line, the still soup, and the extra coin in the bard's hat.
- **Docs**: `README.md` — Volume 2 marked chapters 1-7 complete; `小说大纲.md` — Chapter 7 outline refined with the true-name rule.
- **Next**: Volume 2 Chapter 8《骑士的觉悟》.
- **Verification**: UTF-8 no BOM.

---

**#15 (2026-08-17) — Volume 2 Chapter 6《骑士过去的秘密》drafted**
- **Content**: appended to `第二卷 持剑的孩子.md` — a man who never speaks of his past, spoken of everywhere: three rumors in three towns (the tavern veteran's lone knight facing an army — "后来他就不是他了"; the roadside elder's king-slayer — "他赢了好大的事，输了好大的命"; the ferryman's man who lost everything), each trailing a half-finished sentence, and all agreeing he once had a name no one dares say anymore. Kael's questions deflected with the callback line ("镇子上的人还说，天上下雨，是因为有人哭得太多了。"), the dead end "你看我像杀过国王的人吗？" — "像。" — and the name question answered "想不起来了。走了太远的路。名字落在路上了。" The nightmare night: the knight asleep with the sword half-drawn, cold sweat, two syllables — like a name, like an apology; the first time Kael sees that the fearless man fears. The outline's key line: "师父，你也有害怕的事？" — "怕。" (pause) "所以我把剑握得更稳。" Kael mishears: fear means become stronger until nothing can frighten you; the knight meant: fear, and still walk forward — the second, deeper rift. Closing narrator: years later, on a distant battlefield, Kael wakes from his own nightmare with his hand on the half-drawn sword, cold sweat, white knuckles — the generational replication of the nightmare (Volume 5), the last lesson learned when the teacher is no longer there; the teacher never found the day to say "人这一辈子，总有一两样东西，是你练到最强也赢不了的。"
- **Docs**: `README.md` — Volume 2 marked chapters 1-6 complete.
- **Next**: Volume 2 Chapter 7《骑士的悲剧》.
- **Verification**: UTF-8 no BOM.

---

**#14 (2026-08-17) — Volume 2 Chapter 5《没有剑的一天》rewritten (Western-fantasy setting; the unspoken tragedy of the other path)**
- **Content**: `第二卷 持剑的孩子.md` — full rewrite per user direction. Setting westernized: the village becomes 柳溪村 (mill, barn, threshing yard); the villagers become 加雷思 (roof, wood shingles), the miller 霍布斯 (water), and the widow 玛莎 (beans, the winter invitation and hot soup); the taunt now uses the nameless knight ("跟着个连名字都没有的老头——你该不会也没名字吧？" — the name motif). New frame: the knight is deliberately tempering the boy's mind through ordinary labor — "水桶晃，是你脚跟没站稳。脚跟稳了，剑根就稳了。""豆子要一颗一颗捡……想快，先学会慢。" — one lesson, two hearings: the master teaches 过日子, the boy learns 练功夫; the boy counts the days to the road, ignores the widow's invitation to stay the winter (the unregistered fork). The unspoken tragedy stays explicit but quiet: "我希望你不会像我一样。" — he thought he could lay that swordless road under the boy's feet. Calm, ordinary, everyday — the closer to an ordinary life, the more it hurts in retrospect: the closing narrator now reaches forward to his later ordinary life (a courtyard, a wife hanging clothes, a child chasing chickens) — 那样的日子，他早就被邀请过。他那时候，没有听见。 (direct echo of Volume 5's return to ordinary life).
- **Docs**: `小说大纲.md` — Chapter 5 outline entry rewritten to match.
- **Next**: Volume 2 Chapter 6《骑士过去的秘密》.
- **Verification**: UTF-8 no BOM.

---

**#13 (2026-08-17) — Volume 2 Chapter 5《没有剑的一天》inserted (no combat; the first divergence), subsequent chapters renumbered**
- **Content**: new chapter inserted before the former Chapter 5, per user direction — a chapter with no combat at all, contrasting the previous chapter's displayed power: the knight earns respect without any skill or sword — mending Old Chen's roof, carrying water, picking beans for Widow Li, soothing a crying child; dogs wag tails, children follow him, eyes stay warm ("亮") all day with the sword never leaving its sheath. Kael tries to copy the deeds but with the wrong motive — his eyes search for an audience while the water is on his shoulder; he wants "厉害", gets "真勤快"; taunted by village boys as an 外乡仔, his hand shakes with anger and the master's "手，又抖了" returns for the second time (now anger, not sword drill — he still cannot learn stillness). The outline's key line: 凯尔："我练了这么久，为什么大家夸的是你？" 骑士："你先把今天挑的水挑稳，再问这个。" — and the late-night praise "你今天做得很好" / "该看见的，都看见了。", which Kael cannot hear as praise because he wants the position in everyone's eyes, not one man's voice. The first divergence is planted: Kael concludes the difference is skill (strength will earn respect); the master's scales never carried other people's mouths; the boy's scales carry a stone written "你们什么时候，才会认可我". The master sees the shape of the thought "我要变强，强到他们尊敬我" and waits to teach him that respect does not come that way — he waits a lifetime (echo of Chapter 10, the master's greatest mistake). Volume 2 renumbered: former chapters 5-13 are now 6-14 (outline and volume header synced).
- **Docs**: `README.md` — Volume 2 marked chapters 1-5 complete; `小说大纲.md` — new Chapter 5 outline entry added, chapters 6-14 renumbered.
- **Next**: Volume 2 Chapter 6《骑士过去的秘密》.
- **Verification**: UTF-8 no BOM.

---**#12 (2026-08-17) — Volume 2 Chapter 4《凯尔眼中的骑士》rewritten (combat beats, wrong conclusion, restraint foreshadowing)**
- **Content**: `第二卷 持剑的孩子.md` — full rewrite per user direction. Kept the non-combat beats: the river village letter (a dead son's half-written home letter; grief done as firewood, water, a straightened door), the two eggs ("她给得起的，我才收"), the robbed traveler sharing rations, "赶路的" as the name that lets strangers be at ease. Added the knight's strength and mystery: protecting an attacked merchant — three bandits downed bare-handed, no sword drawn, no reward taken ("我赶路的。路过，顺手。"), the merchant's bafflement ("凭你这身手……何苦当个赶路的") answered by one mystery line — "当过。不想当了。"; driving off a wolf pack — he walks empty-handed toward the pack and the wolves retreat of their own accord; Kael, who has killed wolves, cannot understand what made them afraid; the question goes unanswered. Kael reasons it out alone: not kindness (his father Gar was kind and could not make wolves retreat), but strength — "尊敬和害怕，原来是同一件事的两面" — his wrong conclusion, refined from Volume 1's "只要我够强，他们就会知道我不是灾厄" into "只要我够强——人们就会尊敬我，而不是躲开我。" He asks the master directly and gets no explanation ("你自己想" — the master waits for a question Kael will never ask). Kael asks to learn swordsmanship "想帮上忙" — and the first lesson is standing still: "手稳，心才稳。" The untaught sentence becomes the chapter's key foreshadowing: "力量如果没有克制，反而会毁了最珍贵的东西。" — the master waits for a "再大一点" that never comes, and Kael will learn it only after destroying what he treasured most. Ending keeps the outline's key line: "总有一天，我会像你一样强。" / unspoken "我希望你不会像我一样强。"; the two kinds of strength divided by the thin line called 克制 (Volume 4's wound).
- **Docs**: `README.md` — Volume 2 marked chapters 1-4 complete.
- **Next**: Volume 2 Chapter 5《骑士过去的秘密》.
- **Verification**: UTF-8 no BOM.

---

**#11 (2026-08-17) — Volume 2 Chapter 3《是路人也是同伴》revised (renamed from《骑士收养他》; outline key line anchored)**
- **Content**: `第二卷 持剑的孩子.md` — renamed to signal the mutual nature of the bond: a stranger and a companion belong together; both are people who have not found their own road. Kept from the draft: 23 days of traveling, the villagers' "我家的" moment, the snake lesson, Kael giving his name ("凯尔·阿伦——不会迷路的人"), the short knife with the bark inscription, walking on the knight's left. Added per outline: "你为什么帮我？" / "因为你需要帮助。" — the key line 凯尔："所有人帮我，都是因为我可能有用。" 骑士："那你现在没有用，我为什么还在这里？" (Kael cannot answer with "usefulness"); the 师父 beat — he says it by the spring, the knight neither corrects nor accepts, only the one glance that is the answer; narrator hints the mutual redemption: the man who said "你走到哪儿，我就在哪儿" was himself walking a road without end, unable to stop, and Kael's adoption of the knight was simultaneous with the knight's adoption of him — 两个没找到自己路的人互相捡起了对方 (seed of Volume 5's reasonless togetherness).
- **Verification**: UTF-8 no BOM.

---

**#10 (2026-08-17) — Volume 2 Chapter 2《骑士没有看到怪物》drafted (revised to anchor the outline's key line)**
- **Content**: appended to `第二卷 持剑的孩子.md` — a chapter of almost pure psychology: dawn at the ruined way station, the shoulder wound needs re-dressing, the collar slips, the birthmark meets the firelight; Kael braces for twelve years' worth of practiced fear — and the knight lights the lantern and says "天黑了，看不清路"; Kael forces the confrontation — he opens the collar wide himself and asks "你不怕我？" — and the knight's answer is the outline's key line, spoken at the fire, not at him: "我见过很多比印记更可怕的东西。" (pause) "比如一个认为自己只能成为怪物的人。" It speaks of Kael AND of the knight's own past — "能说得出'认为自己只能成为怪物'是什么滋味的人，多半自己也咽过一样长的黑夜" — left silent, per the outline's rule of restraint; then "你希望我问？" / "不希望。" / "那就不问。"; the folk wisdom taken apart ("天就是想下雨"); "我只是看见一个孩子。" — his first time being seen as a person; "我杀过的人，够我记一辈子"; Kael decides "那我不信它。我走我的路"; narrator foreshadow: the sentence will strike three times in his life — remembered, forgotten, understood at the cliff's edge (echoing the outline's Volume 6/7 closure); two shadows becoming one on the road.
- **Next**: Volume 2 Chapter 3《骑士收养他》.
- **Verification**: UTF-8 no BOM.

---

**#9 (2026-08-17) — Volume 2 opened: Chapter 1《来自远方的陌生人》drafted**
- **Content**: new file `第二卷 持剑的孩子.md` — Kael's half-year wandering (herbs, stars, beast-hunting, learning to keep the mark covered, the "赶路的" answer he will use for years), then his first human enemies: five starving robbers at a ruined way station; his hand trembling for the first time — hesitation's price is a wounded shoulder; the tired knight who arrives without ceremony, shows him how to grip ("孩子，剑不是这样握的"), disarms all five without drawing his own sword; the exchange "他们是敌人！" / "他们是走投无路的人。"; night by the fire, the wound dressed, "我跟你走" — "我没有别的地方可去"; first lesson seeded: letting enemies go is harder than killing them (echo of Volume 5).
- **Docs**: `README.md` — Volume 2 status row added.
- **Next**: Volume 2 Chapter 2《骑士没有看到怪物》.
- **Verification**: UTF-8 no BOM.

---

**#8 (2026-08-17) — Volume 1 complete: Chapter 7《离别故乡》(final chapter) drafted**
- **Content**: appended to `第一卷 血痕之子.md` — the dawn departure: telling his parents the night before, mother's mended clothes and the still-warm dry food silently added to the bundle, the re-tied charm knot, passing the millstone/sun-field/the tree at the edge, the words spoken to the mist at the village gate ("等我回来。当我足够强大时，你们会知道我不是灾厄。"), mother Serin leaning on the doorframe without waving, father's absence, walking south alone — and the cruelty after he is gone: the village relaxing, no one mentioning his name, the stone moved away; priest Toren watching the southern road. Volume-ending narrator lines close the arc (fear not weakness rejects him; the "等我回来" that will one day be too late).
- **Docs**: `README.md` — Volume 1 marked complete (7/7 chapters).
- **Next**: Volume 2《持剑的孩子》— first chapter《来自远方的陌生人》.
- **Verification**: UTF-8 no BOM.

---

**#7 (2026-08-17) — Volume 1 Chapter 6《预言的误解》drafted**
- **Content**: appended to `第一卷 血痕之子.md` — spring of Kael's 12th year: he overhears the elders' meeting behind the granary ("不能让他留下" / "谁去说？" — no one will take responsibility; priest Toren's "'不说'，也是一种话"); the deepening silent ostracism (no one calls his name, the unnamed dry-food-and-shoes parcel sized for his father's feet left at the door, Melly pulled back behind the curtain); his questions to the tribe that go unanswered; father Gar's one and only facing of the truth ("你什么都没做错"); Serin's "我们可以走" refused by Kael ("我又没做错"); and the night he makes his first big choice: "如果你们害怕现在的我，那我就成为你们无法忽视的人。" Source settings preserved.
- **Docs**: `README.md` — Volume 1 status updated to Chapters 1–6.
- **Next**: Chapter 7《离别故乡》(final chapter of Volume 1).
- **Verification**: UTF-8 no BOM.

---

**#6 (2026-08-17) — Volume 1 Chapter 5《渴望认可》drafted**
- **Content**: appended to `第一卷 血痕之子.md` — from age 8 to ~12: secret dawn training with branches by the forest fence, night balance drills, learning tracking by tailing the hunters; the tribe distancing further with every leap in skill (the silent-ostracism loop: 孤独→训练→强大→更孤独); Serin's "你为什么非要证明？"; the scrap iron from Mey's smith father ("别让她哭") ground over one autumn into the first crude sword; Gar's twelve days of archery ("箭离弦之前，手要稳"); the night whisper "只要我够强，他们就会知道我不是灾厄"; and the wind carrying away the words "……不能让他留下". Source settings preserved.
- **Docs**: `README.md` — Volume 1 status updated to Chapters 1–5.
- **Next**: Chapter 6《预言的误解》.
- **Verification**: UTF-8 no BOM.

---

**#5 (2026-08-17) — Volume 1 Chapter 4《第一次展现天赋》drafted**
- **Content**: appended to `第一卷 血痕之子.md` — the hungry-wolf night raid on Emberstone (Kael, age 8, at the neglected edge of the village, grabs the door bar and shields four cornered children — Luen who had mocked him included; his dark-elf instinct and night sight explode, the pack retreats, he collapses; waking to silence, no cheers, priest Toren's "果然。灾厄拥有力量", his unheard "我……保护了他们", mother Serin crying from fear not joy; the wolf blood seeping into the mark; only Melly still waves at him). Source settings preserved.
- **Docs**: `README.md` — Volume 1 status updated to Chapters 1–4.
- **Next**: Chapter 5《渴望认可》.
- **Verification**: UTF-8 no BOM.

---

**#4 (2026-08-17) — Volume 1 Chapter 3《虚弱的孩子》drafted**
- **Content**: appended to `第一卷 血痕之子.md` — Kael's sickly childhood (the heavy fever with the mark deepening, father Gar's fall while herb-gathering, watching other children from the window, mother Serin teaching herbs and stars, the one attempt to join the game "追风" that ends with a scraped knee and no one looking back, learning to swallow pain, and her words "活着，然后回家"). Source settings preserved.
- **Docs**: `README.md` — Volume 1 status updated to Chapters 1–3.
- **Next**: Chapter 4《第一次展现天赋》.
- **Verification**: UTF-8 no BOM.

---

**#3 (2026-08-17) — Volume 1 Chapter 2《被恐惧的孩子》drafted**
- **Content**: appended to `第一卷 血痕之子.md` — Kael's infancy and early childhood in Emberstone (tribe's silent ostracism "被让开的位置", father Gar's one argument with the elders, priest Toren's monthly watch, dark-elf lullaby, learning to walk alone, first "灾厄之子" taunt, Mey's question "你为什么和我们不一样" with Kael's "我……不知道", and mother Serin sewing the talisman that carries her unsaid words "你值得被爱"). Source settings preserved.
- **Docs**: `README.md` — Volume 1 status updated to Chapters 1–2.
- **Next**: Chapter 3《虚弱的孩子》.
- **Verification**: UTF-8 no BOM.

---

**#2 (2026-08-17) — Volume 1 Chapter 1 draft; per-volume document structure established**
- **New**: `第一卷 血痕之子.md` — Volume 1 document (one file per volume from now on), opening with volume metadata + chapter list, containing the full draft of Chapter 1《不祥的诞生》(the rain-night birth of Kael Aren in Emberstone tribe: the burning-brand birthmark, the misinterpreted prophecy, mother Serin's naming, father Gar's helplessness; source settings preserved) — details drafted per the outline; new names marked 【拟定】 in the outline, used directly in prose.
- **Docs**: `README.md` — added per-volume document status table.
- **Next**: Chapter 2《被恐惧的孩子》to be appended to the same file.
- **Verification**: UTF-8 no BOM.

---

**#1 (2026-08-17) — Initial commit: detailed novel outline (7 volumes, 101 chapters)**
- **Content**: `小说大纲.md` — a chapter-by-chapter detailed outline expanded from 《故事设定.docx》:
  - Volume overview + per-chapter breakdown for all 7 volumes / 101 chapters, each with: one-line summary, scene breakdown, key dialogue, chapter turn, foreshadowing/callback, writing tips.
  - New appendices: character table, key objects, timeline, volume theme-sentences, connection points to the Slay the Spire game.
  - Original settings preserved; newly invented details marked 【拟定】.
- **Docs**: `README.md` — repository overview and volume list.
- **Verification**: UTF-8 no BOM.

**#31 (2026-08-19) — Volume 3 Chapter 1《踏入战场》draft deleted; history scrubbed**
- **Content**: per the author's instruction ("delete Volume 3 Chapter 1, undo its GitHub push"), the trial draft of the volume's opening chapter was **removed entirely** — history rewritten and force-pushed: the rebuilt #30 commit no longer contains `第三卷 战争之子.md`, and the old #31/#32 commits (both drafts) were dropped; earlier changelog mentions of the draft were removed in kind. No prose for the chapter remains in the repository.
- **Docs**: `第三卷 战争之子.md` restored to the volume header + chapter structure only (ch1 未开始); `README.md` Volume 3 row back to 未开始; `STORY_BIBLE.md` §3 status row back to 未开始, §6's vol3-ch1 established-settings line removed.
- **Verification**: UTF-8 no BOM; `git log` for `第三卷 战争之子.md` shows only this commit.

**#32 (2026-08-19) — Volume 3 outline revised: Chapter 1 expanded to a "three days / three chapters" block (author-approved plan)**
- **Content**: per the author's plan (dual-layer narration: Kael's "the battlefield only tests strength" fantasy vs. the reader's glimpse of tags / grain / class / death), the outline's Volume-3 chapters 1–3 were rewritten into an 入营三日 (three days in camp) block —
  - Ch1《踏入战场》Day 1: opening with the footlocker; registration ("猎户" by the half-eared veteran); quartermaster 哈维's ledger; first dinner (the "那个凯尔？……听说你会使剑？" beat); Erian's entrance grabbing the last bowl of soup, the nickname "长腿的医生" first heard this chapter; wooden-sword win over 巴恩; "因为他是骑士，你不是"; the key line spoken to the tent roof.
  - Ch2《现实中的战争》Day 2: dawn formation; patrol → village raid; first real blade; first kill — the young enemy's "母……亲……"; saving a child ("我能保护别人"); "狼崽子" = dread, not praise; Erian sharing water and binding an enemy's wound; the night's first self-deception ("我不是怪物。我只是……赢了。").
  - Ch3《天赋带来的荣耀》Day 3: aftermath — the extra salt meat, the toast, "红印的小子"; awe ≠ acceptance; Erian's cold water ("等你多活几年就知道了"…"没什么意思。"); the veterans' night talk ("昨天那几个村民呢？""没救回来。"); Kael's refusal ("如果我们足够强，就能救下来。") and Erian's "也许吧。""早点睡。"; ending on "我终于找到了属于自己的地方" + the theme sentence (the chapter's single allowed future voice).
  - Ch4 absorbs the old ch3 glory arc (夜袭/破阵/斩将、"红印之子" etc.); Ch5 retitled《你想死吗？》— the pursuit rescue is now the bond-forming night, not the first meeting (Erian's entry moved to ch1's dinner as approved).
  - One-time characters with plain names (used only in this block): quartermaster 哈维, testing veteran 巴恩, young noble knight 奥兰. Future voice counts 0/0/1; 烟火气 fully behavioral; "红印之子" seed (callback to Volume 1 ch4).
- **Docs**: `小说大纲.md` (ch1–5 entries rewritten), `第三卷 战争之子.md` (volume header: ch5 title), `STORY_BIBLE.md` (§3 status row, new §6 入营三日 entry), `README.md` (Volume 3 row).
- **Next**: draft Chapter 1 prose (author gates the prose).
- **Verification**: UTF-8 no BOM.

**#33 (2026-08-19) — Volume 3 Chapter 1《踏入战场》drafted (Day 1 of the 入营三日 block)**
- **Content**: Chapter 1 prose drafted per the approved outline (author gates the prose). Day 1 — arrival and the night before:
  - Opening on the footlocker ("新来的？"); registration by the half-eared veteran (the collar opened — first time un-covered since age 12; "猎户"; the sword noted); quartermaster 哈维 counting grain one kernel at a time — the reader's first glimpse that grain, not swords, keeps an army alive.
  - Camp walk-in-one-glance: 烟火气 fully behavioral (mending soles / swiping thread, dice and bad language, the cook chasing a meat-thief, grooming a horse).
  - First dinner (chapter core): "那个凯尔？" → "听说你会使剑？""会。""那就好。"; Erian grabs the last bowl of soup ("你再不快点，它就是我的了。"), the nickname "长腿的医生" first heard this chapter.
  - Wooden-sword win over 巴恩 grounded in observation (his left foot bears no weight — the half-beat lag); "谁教你的？""一个骑士。"; "这小子有点东西。"
  - 奥兰 ("不过是乡下人的把戏。"), the officer stops it — "因为他是骑士，你不是。"; Kael's self-persuasion (没关系。等上了战场就不一样了。).
  - Night: the talisman, the hilt knot, the stick-first/sword-after line, the key line spoken to the tent roof — "只要我赢，所有人都会接受我。" Closing on hope; zero future voice (this block's single one is reserved for ch3).
  - Dual-layer narration carried by scene choice only, no narrator explanations.
- **Docs**: `第三卷 战争之子.md` (chapter appended); `README.md` + `STORY_BIBLE.md` §3 status rows updated.
- **Verification**: UTF-8 no BOM; grep "师父" zero hits in the chapter.

**#34 (2026-08-19) — Volume 3 Chapter 2《现实中的战争》drafted (Day 2 of the 入营三日 block); outline += Orlan's death**
- **Content**: per the author's direction (Orlan dies with a knight's code, covering his comrades — reported after the return by a companion; never a web-novel "picked a fight with the protagonist" beat), Chapter 2 prose drafted —
  - Dawn formation; the patrol led by the young armored knight Orlan (Kael recognizes him from last night's "不过是乡下人的把戏"); the arm's-length march; the village raid; first real blade (weight, blood, bone, sound — nothing like the wooden sword); first kill — the young enemy's "母……亲……"; the rescue ("我能保护别人。"). "狼崽子" = dread, not praise.
  - The retreat: a flash of bright armor at the crossroads — his only image of Orlan ("别停！…走！" — someone drags him on). After the return, 巴恩 reports flatly: 昨天校场那个……死了。他让我们先走。他说他是骑士，骑士没有跑在别人后头的道理。"他这人，嘴不饶人。" — a justified death by knight's code, not a villain's comeuppance.
  - Night, double self-deception: the trembling hand pressed down — "我不是怪物。我只是……赢了。"; then Orlan — he tries to recall his face, cannot (only the bright armor and that one sentence remain) — "强大的人，才能活下来。他活下来了。所以他够强。" Second repetition, the hand stops trembling. Reader-side revelation carried by scene choice alone, no narrator explanation: yesterday's comrade is today's corpse; war's "fairness" lies not in "不问出身" but in everyone having exactly one life.
  - Erian sharing water / dressing an enemy's wound; Kael sees and doesn't ask. Ending echoes ch1's dawn line.
  - Zero future voice; the recalled maxim verbatim from Volume 2's farewell ("剑不是用来证明自己的。")
- **Docs**: `小说大纲.md` (Ch2 entry: Orlan death beats, key lines, writing notes), `第三卷 战争之子.md` (chapter appended), `README.md` + `STORY_BIBLE.md` §3 status rows, `STORY_BIBLE.md` §6 入营三日 entry.
- **Next**: draft Chapter 3《天赋带来的荣耀》(Day 3, per approved outline; note ch3 carries 3-5 extras and the volume's single allowed future voice).
- **Verification**: UTF-8 no BOM; grep "师父" zero; no future-voice markers except "干了以后发涩" (physical causality).
- **Revision**: Chapter 2 expanded per author feedback (the draft was too short, the pace too fast) — every beat thickened: waking + roll-call ("没有人看他"), Orlan asking "人齐了没有？", the march (letter-writing, bragging, the off-key song; 巴恩 on the frontier — the burnt fields, the fire-scarred boundary stone), the village's false calm (the dog, the laundry, "这村子，看着还行。") before the fire, the first-blade beat (the missed first strike, the sting of a real edge), the alley duel (the enemy's face — mud and fear), the rescue (the broken axle, the burning beam, the child finally crying), the retreat (Kael half-turning back — 他能打; the armor's shine dulled by dried mud), the return (stretchers, counting heads, the fireside silence), Erian's night beat, and the night mirror — the enemy's face remembered clearly, Orlan's unrecallable. All author red lines untouched: Orlan's death stays a knight's-code cover, no "picked a fight" beat, no narrator explanations, future voice 0.
- **Revision 2**: per the author's second review ("still too short, pace too fast; expand longer, write to the world-building"), another layer of dark-fantasy texture and breathing room was added — dawn muster (the ration soup line, the grain wagon leaving with the column — 哈维 counting the last sack the way he counted rye yesterday; the grain theme untold); the march (water pools in the ruts, Kael's shoulder aching, the mill-raised eye reading the fallow field, seven burnt house frames he counts, the noon halt and 巴恩's "年轻。那下回，你背着我的水囊走。"); the approach (the heat, the smell that has no name); the melee (a recruit's shoulder cut and the veteran's flat-of-blade shove — "蹲下！别挡道！", a veteran swearing and binding his own arm, Kael learning the veterans' economy while staying half a beat ahead); the enemy's farm-tool blade and patched collar; the rescue (the old soldier's shaking hands holding the child like something found again); the retreat ("别停！" now 巴恩's); the camp return (the dinner that tastes of nothing, the "狼崽子" murmur); the night (men setting their swords within reach, the guard's footfalls outside; the changed guard-step echo of ch1's night). All key lines verbatim; canon quotes only; zero future voice; no new named characters; 埃里安's wound-dressing beat untouched.
- **Revision 3**: per the author's review ("适当精简，保留真实感" — trim, keep the realism), the decorative flourishes were cut while the grounded details stayed — removed the house-frame count ("数了数，七根"), the nameless smell at the village approach, "他越打越快，越打越稳", the "like something found again" simile, and "和今天早些时候见过的那些人一样"; everything else from Revision 2 stands.

**#35 (2026-08-19) — Volume 3 Chapter 3《天赋带来的荣耀》drafted (Day 3 of the 入营三日 block; aftermath & campfire)**
- **Content**: Day 3 prose drafted per the approved outline — the day of aftermath and awe —
  - Dawn: yesterday's deed has spread through camp; the ration-line talk ("就是他？…昨天巷口那个。"), the morning sword practice before the meal.
  - 哈维 counts out the salt meat and adds a third piece without saying why ("多出来的，是你的。你昨天出了趟营。"); a bystander's "怎么他四块？" — reader-side: the useful man is kept. The grain wagon from the village, Kael hefting sacks, the mill smell of six years; 哈维: "够吃到下个月。"
  - Camp day: the red horse, the dice (不赌好。赌钱的人，手会抖。), 巴恩's noon invitation — Kael lets him win two passes.
  - The name: "红印的小子" first spoken across the parade ground — Kael answers. (部落里人们叫他灾厄；在这里，人们叫他红印的小子。) The wine (he drinks too fast, chokes, laughs loudest), the axe mid-swing as he passes.
  - Awe ≠ acceptance, all behavioral: the riverbank washer gives up his spot and moves away; the fire-side seat shifts; the raised hand that falls on a knee; the talk that drops to whispers as he passes and revives behind him. Kael's old wrong equation re-applied: 他们怕我，也敬我。怕和敬，原来是一回事。
  - Afternoon with Erian: "这地方比我想象得好。" "哪一点？" "至少这里的人只看实力。" "你真这么觉得？" "难道不是？" … "等你多活几年就知道了。" "什么意思？" "没什么意思。" — then he is sent to carry medicine to the wounded tent; the enemy prisoner still squatting in the corner; the wounded man who nods to him; Erian washing his hands a long time at dusk.
  - The night fire: Kael wiping his sword (blade, then the six-year-old knot, darkened by blood); the veterans' talk — "明天谁去前哨？""我。"…"昨天那几个村民呢？" silence. "没救回来。" — Kael's first realization: not everyone can be saved. His refusal: "如果我们足够强，就能救下来。" Erian: "也许吧。""早点睡。"
  - The close: the talisman, the mark under his collar (day one he opened the collar himself; today they call him 红印的小子 and he answers), the sword bright by the fire, "我终于找到了属于自己的地方。" — then the block's single allowed future voice, the volume theme sentence landing for the first time: 他还不知道，这句话，他会在未来无数次听见——剑不能带来和平。而每一次，他听见的，都是另一句话：你的剑，还不够强。
  - Day-3 only; future voice exactly once (the 0/0/1 quota closes); "师父" zero; no new named characters; Erian never preaches.
- **Docs**: `第三卷 战争之子.md` (chapter appended); `README.md` + `STORY_BIBLE.md` §3 status rows.
- **Next**: Chapter 4《他误解了认可》(absorption of the glory arc; per outline).
- **Verification**: UTF-8 no BOM; grep "师父" zero; no future-time words; one future voice.
- **Revision**: per the author's direction, a midday patrol highlight was inserted into Day 3 — Kael volunteers for a sortie to the forward outpost where 7-8 defeated soldiers (溃兵) are looting the grain store; he drives them off single-handedly (straight-line economy, each strike at a vital gap). In the split second the last man is at sword-point, the enemy's shadow overlaps with the lead wolf from his childhood (the one he drove off with a stick) — the illusion nearly triggers a killing blow, but the blade stops a hair's breadth away. The rescued comrade presses his fist to his chest in silent gratitude; Kael feels an absurd bloom of "hero's glory" (the sword's purpose deviates for the first time), and is frightened by the feeling. No internal monologue tags ("he thought/felt") — the psychology is carried by action beats: the axe mid-swing pausing as he passes, the white-knuckled grip on the hilt, the breath held over the blade later at the fire. All other Day 3 beats intact (哈维 extra meat, 红印的小子, Erian's cold water, veterans' talk, theme-sentence future voice).
- **Docs**: `第三卷 战争之子.md` (chapter rewritten).

**#36 (2026-08-20) — English story bible & outline added; chapter count corrected to 102; Chapter 4《他误解了认可》initial draft withdrawn (rewrite pending)**
- **Chapter 4 withdrawn**: the initial draft of Chapter 4 was removed from the repo; its push to GitHub cancelled via history rewrite + force-push — `第三卷 战争之子.md` restored to the Chapter-3 state. Rewrite per the outline is pending.
- **English materials** (per the author's request to translate the story bible and outline into English):
  - New `STORY_BIBLE_EN.md`: complete English translation of `STORY_BIBLE.md` (duplicate §6 bullet removed; the Day-3 noon patrol highlight synced into the §6 入营三日 entry, matching the Chinese bible).
  - New `novel_outline.md`: complete English translation of `小说大纲.md` (7 volumes, 102 chapters — same structure: one-line synopsis, scene expansion, key lines, chapter twist, foreshadow/callback, writing notes; plus the appendix: character list, key objects, timeline, volume theme sentences, game connection points).
- **Chapter count correction**: the outlines' header and its mentions claimed "101 chapters", but the actual heading count is **102** — corrected in `小说大纲.md`, `novel_outline.md`, `STORY_BIBLE.md`, `STORY_BIBLE_EN.md`, `README.md` (historical CHANGELOG #1 wording left as recorded).
- **Docs**: `README.md` + both bibles §3 status rows now 第一～三章成稿 (Ch4 rewrite pending).
- **Verification**: UTF-8 no BOM on all files; `novel_outline.md`/`STORY_BIBLE_EN.md` contain no Chinese characters; markers clean; "师父" zero in prose.

**#37 (2026-08-21) — Volume 3 Ch1-3 revised (less tell, more show); Volume 2 Ch5 dialogue added; Outline Vol5 Ch14 name echo added**
- **Vol 3 Ch1-3 revision** (per author's full review: "psychological arc too explicit"): cut ~10-15% interpretive narration ("he realized/he thought/this meant") across three chapters; let actions carry meaning; broke the repetitive night-reflection template (amulet/sword/monologue); preserved the 5 core scenes ("那就好", quartermaster counting grain, "母…亲…", dead knight's forgotten face, "红印的小子"); Erian gains micro fear-behaviors (fills water skin first, counts men by fire); Harvey strengthened as recurring functional background; sword-knot as Adrian's ghost threaded through.
- **Vol 2 Ch5 "没有剑的一天"**: added dialogue — Kael notices knight's empty sheath, asks "你的剑呢？" → "收起来了" → "为什么？" → "因为我现在用不到它。比起剑，我现在更需要一把斧子。" — foreshadows Vol 5's sword/firewood irony.
- **Outline Vol 5 Ch14 "剑与柴"**: after the "Enemies don't run. Firewood does" joke, Kael murmurs "艾德里安·瓦尔"; daughter asks "他是谁？"; Kael dazedly answers "一位教我如何使用剑的骑士" — echoes Vol 2 Ch14 true-name reveal and Vol 2 Ch5 axe line across decades.
- **EN outline synced** to match.
- **Docs**: `第三卷 战争之子.md` (Ch1-3 revised), `第二卷 持剑的孩子.md` (Ch5 dialogue), `小说大纲.md` + `novel_outline.md` (Vol 5 Ch14 updated).
- **Verification**: UTF-8 no BOM; "师父" zero; no future-time words; future voice quota respected (Vol 3 Ch3 had the sole 0/0/1).

**#38 (2026-08-21) — Volume 3 Chapter 4《他误解了认可》rewritten per blueprint**
- **Core**: first active wrong choice — Kael believes his power judgment > others' caution; small-scale mission (search/capture deserters in village with civilians); succeeds beautifully (14 captured, 3 killed, 0 civilian casualties); rewarded with official sword ("你现在值得一把好剑").
- **Erian conflict established**: "等白天" / "那就让他们跑" / "少死几个人，也可以接受任务失败" — value divergence seeded, no preaching.
- **Micro cost**: one soldier grazed by arrow; Erian treats silently, "你赢了" / "嗯" — divergence shown, not argued.
- **New sword moment**: military-issue sword given as recognition; Kael tests it, then re-ties knot on old sword (Adrian's ghost) — sword = recognition proof.
- **Prisoner mirror**: deserter's fear mirrors childhood clan fear; Kael recognizes ("怕他本人的怕") then self-deceives ("怕我，就是承认我。承认我，我就赢了。").
- **Ending**: dual swords on knees → old sword back on pillow, new sword hung; night footsteps; internal equation reinforced.
- **Style**: zero future voice (Vol 3 quota closed at Ch3); "师父" zero; no new named characters; Erian never preaches; psychology via action beats only.
- **Docs**: `第三卷 战争之子.md` (Ch4 appended); `README.md` + both bibles §3 status rows now 第一～四章成稿.
- **Verification**: UTF-8 no BOM; "师父" zero; no future-time words.

**#40 (2026-08-21) — Added `EDITOR_PROTOCOL.md` (Author Opinion Review Protocol / editor-role document)**

- **Content**: committed verbatim per the author — dual identity (author/reader), no mechanical flattery, the 8-step analysis flow for new ideas (intent → character consistency → character arc → theme → dramatic value → freshness → alternatives → execution), explicit-confirmation rule for Canon changes, fact-fix vs creative-suggestion distinction, guardrails against author-power-fantasies / tragedy escalation / "cooling up" Kael, AI may oppose the author while final authority stays with the author, opinion levels LEVEL 0–5 (higher level = analyze first, execute later).
- **Workflow**: from this entry on, every session must first read: all volume manuscripts, `小说大纲.md`, `STORY_BIBLE.md` and `EDITOR_PROTOCOL.md` (the standing order is also written into the workspace AGENTS.md so it survives across sessions).
- **Docs**: new `EDITOR_PROTOCOL.md`; `README.md` content list now includes it.
- **Note**: the Volume 3 Chapter 2 split structure is author-approved; titles and the fragmentary-retelling design await confirmation before prose rewriting (related uncommitted changes remain in the working tree).

**#41 (2026-08-21) — Volume 3 Chapter 2 literary split complete: new *I Can Protect People* + new *The Face He Couldn't Recall*; whole book 102→103 chapters**

- **Background**: the author rejected the earlier "table-of-contents-level cut" (*真剑* / *数人头* — titles swapped, prose untouched) and demanded a true narrative reconstruction — each chapter must have its own core theme / dramatic goal / conflict source / emotional climax / closing hook; titles must not be ambiguous or one-sided; Orlan's death becomes a fragmentary retelling with no witnesses. After analysis and author confirmation, final titles: Ch2 *I Can Protect People*, Ch3 *The Face He Couldn't Recall*.
- **Prose** (`第三卷 战争之子.md`):
  - Ch2 *I Can Protect People* (Day 2 first half, compact rhythm): short verb-first sentences, zero reflection; dawn roll call "no one looked at him here"; Orlan's only line "All present?"; march glimpse (burnt fields, fire-scarred boundary stone); false calm before the village (the yellow dog lies back down, "This village looks all right." — smoke rises mid-sentence); first real blade (heavy/cold/numbing, first strike misses the vitals); killing the peer "Mother…" gets a three-breath quota, then he wipes the blade and keeps pressing; rescue (broken shaft, burning ridge-beam, the child cries only once handed over, "I can protect people." said on the run); chapter break at the rescue peak + cross-chapter hook "Only the right hand hanging at his side kept shaking." Battlefield memory asides and the Harvey grain-wagon passage deleted (detail budget).
  - Ch3 *The Face He Couldn't Recall* (Day 2 second half, slow rhythm): rear-guard thud + new silence beat ("the sound still clung to their necks"); head-count at the gate, "wolf cub", tasteless supper; the fireside **fragmentary contradictory retelling** replaces Bane's single-source account — one: "He blocked the crossroads. I saw it" / another: "Smoke that thick — couldn't tell a man at three paces" / "think I heard him shout something" / "heard nothing"; every version agrees on one thing: he stayed behind so the others could go. Bane demoted to secondhand: "He never had a kind mouth." "He must have said that line. You all know which one." → "He said he was a knight, and a knight had no business running behind the others." — the words survivors needed him to have said (knight's code stays positive; no face-slap beat); Kael tries to piece it together (when? which crossroads? how many held off?) — no one can answer; reader-rule inversion: not even the reader knows the truth; Erian's water-sharing and bandaging left untouched as silence; night self-deception chain unchanged ("I'm not a monster. I just… won." → the face he can't recall → "Strong men survive. I survived, so I'm strong enough."); closing line answers Ch2's hook: "The second time, his hand didn't shake."
  - Old Chapters 3–17 renumbered 4–18 (end-of-file marker updated to "Chapter 5 *He Misunderstood Acceptance* pending rewrite"); future voice quota now Chs 1–3 zero each, Ch 4 once (0/0/0/1).
- **Outline** (`小说大纲.md`): disclaimer line added to the general rules ("章节划分仅供参考，可以随时调整（但需要用户同意）。"); 102→103 chapters; both entries rewritten under the new titles (new pacing bullets, the fragmentary-retelling design table, reader-rule inversion note, cross-chapter hook callback); contrast foreshadow updated to "Chs 13-14 hooked"; remaining Vol III headings renumbered in descending order; internal refs synced ("Red-Mark Child" seed → Ch4, wolf-cub expansion → Ch5, surrender-soldier massacre → Ch9).
- **English mirror** (`novel_outline.md`): all corresponding changes landed — 103 chapters + disclaimer line; Chapter 2 *I Can Protect People* / Chapter 3 *The Face He Couldn't Recall* entries rewritten; Ch5–Ch18 renumbered; cross-refs synced (Chapter 5 expansion, Chapter 4 seed, Vol III Ch 9 massacre, Vol III Chs 13-14 hook).
- **Bibles** (`STORY_BIBLE.md` / `STORY_BIBLE_EN.md`): §3 status rows note the Day-2 split plus the same disclaimer, chapter count 103; payoff chain "Ch 13 hook" → Ch 14; thread table updated to Chs 6,8,9,12,13,14,16; §6 induction entry fully rewritten as "three days / four chapters" (pacing settings for both chapters, full fragmentary-retelling design, Orlan never named in prose, 0/0/0/1 quota, cross-chapter hooks).
- **README.md**: 103 chapters; Vol III status parenthetical updated.
- **Protocol** (`EDITOR_PROTOCOL.md`): appended Section 12 "Three-Identity Creation Process (agent-executable edition)" — novelist / literary editor / Kael character editor as mutual adversaries, nine-stage flow (draft → cooling → structure pass → sentence pass → revision → character audit → memorability check → 30% deletion challenge → protocol compliance), detail-priority principles, deletion criteria (agent-executable restructuring of the author-provided methodology).
- **Verification**: UTF-8 no BOM; "师父" zero; zero future-time words in Chs 1–3; key lines verbatim; English mirror free of Chinese residue.

**#42 (2026-08-21) — Story Bible upgraded to v2.0 (author-provided skeleton + repo Canon additions merged); four rulings landed**

- **Content**: after the author re-pasted the full v2.0 text, graded per EDITOR_PROTOCOL and executed following four author rulings, `STORY_BIBLE.md` was rewritten wholesale as the merged v2.0 —
  - **New (brought by v2)**: Misunderstanding Mechanics table (truncation / substitution / delay) + execution rule; Unreliable-Memory technical execution table (Memory-Deviation Register → new Appendix B placeholder); Adrian limited-POV naming-rules table; Erian writing red-lines table; Neow three-layer writing-boundary table (behavior / interpretation / narrative); wife's-death "gray zone" (body reaction, not cognition); web-novel tone five-type detection table; god-challenge tables; three anti-optimization technical strategies; Appendix A failure modes & repair templates A–G; 【CANON】 copy-verbatim rule (no "see Section X" substitutes).
  - **Four rulings**: ① Neow's three truths enumeration kept from v1 (① Blight connected to Neow ② Neow envies the Creator ③ Neow uses Spire-climbers to solve her own problems); ② the "Three-Day Induction" section overwritten with the #41-approved version (v2 held a pre-split stale snapshot: four chapters, new titles, fragmentary contradictory retelling, Orlan unnamed in prose, future voice 0/0/0/1); ③ future-voice quota column: Vols I–II marked TBD (no counts written), Vol III 0/0/0/1, Vols IV–VII TBD, unallocated volumes default to 0; ④ Adrian naming tightened per v2 — Kael does not use "Father/Dad" as spoken address (the unspoken "Dad" at the Volume II spring stays as an existing beat), no new spoken address going forward.
  - **Repo additions preserved**: Kael Misunderstanding Chain instances merged into §1; Torlen "can't read it" note kept; §12 Detail Selection & Deletion Principles and §13 30% Deletion Challenge kept verbatim (introduced in 9aae6a2); Vol III Erian-reset thread line kept; 103 chapters + "chapter division for reference only" disclaimer kept.
  - **Stale refs updated to post-#41 state**: foreshadow chain "Ch 13 hook" → Ch 14; relationship-stages table "Ch 3 first contact (soup-grabbing)" → Ch 1 dinner, "Ch 5 Do You Want to Die?" → Ch 6.
- **English mirror**: `STORY_BIBLE_EN.md` rewritten wholesale as v2.0 (all new tables translated; established renderings retained: Celine/Gar/Mira/Eilin/Herrag/Torlen).
- **Docs**: `STORY_BIBLE.md` (v2.0 rewrite), `STORY_BIBLE_EN.md` (mirror rewrite).

**#43 (2026-08-22) — Volume 3 Chapters 5–7 final prose outline backfill and chapter renumbering (whole book 103→104 chapters)**

- **Outline** (`小说大纲.md`): total book chapters 103→104; Volume 3 total chapters 18→19; newly added Chapter 6 *Entrust Your Lives to Me* (orders & hunter positioning, squad ambush, wounded comrade rescue, comrades' trust & hand-on-hilt hook); adjusted Chapter 7 *Do You Want to Die?* (insubordinate pursuit over the ridge, falling into trap & underwater concealment, Erian's bluff rescue, life-and-death interrogation & return punishment); original Chapters 7–18 shifted to Chapters 8–19; internal cross-references synced (War God foreshadow hook → Chs 14-15, slaughtering surrendering soldiers → Ch 10, god challenge setup → Ch 17).
- **English mirror** (`novel_outline.md`): all corresponding changes synced (104 chapters; Chapter 6 *Entrust Your Lives to Me* added; Chapter 7 *Do You Want to Die?* adjusted; Chapters 8–19 shifted with cross-refs synced).
- **Manuscript & Bibles**: `第三卷 战争之子.md` volume structure header updated to 19 chapters and typo on line 456 fixed; `STORY_BIBLE.md` / `STORY_BIBLE_EN.md` synced to 104 chapters, Vol III Chs 1–7 drafted status row, War God memory chain, and thread table; `README.md` updated to 104 chapters.
- **Verification**: UTF-8 no BOM; whole book 104 chapters; Volume 3 19-chapter outline strictly aligned with manuscript.

---