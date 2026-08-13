---
name: ziwei-doushu
description: "Zi Wei Dou Shu chart reading. Keywords: 紫微斗数, Zi Wei Dou Shu, chart, stars, Four Transformations, patterns."
version: 1.0.0
author: 玄微子 (Xuanweizi)
license: CC0
platforms: [windows, linux, macos]
metadata:
  hermes:
    tags: [Zi Wei Dou Shu, Chinese Astrology, Chen Tuan, Divination, Star Chart]
    related_skills: [hermes-agent]
---

# Zi Wei Dou Shu — The Divination Canon of Master Xuanwei (English Edition)

This skill is grounded in the full OCR text of the 143-page scanned edition of *Zi Wei Dou Shu Quan Shu* (Complete Book of Zi Wei Dou Shu) attributed to Chen Tuan (希夷先生), preserved in `references/ziwei_quanshu_ocr.txt` (with page markers). Whenever reading a Zi Wei Dou Shu chart, consult this canon first, then render the judgment.

> **OCR corrections**: the scanned classical text has occasional misrecognized characters. Common ones: 「牛」may be 「生」or 「午」, 「古」=「吉」, 「坦」=「垣」or 「地」, 「已」=「巳」, 「车」=「午」, 「门」=「巨门」, 「内」=「丙」, 「炎」=「癸」, 「戌成」mixed. Reconstruct by sense; never read the surface glyphs literally.

## Canon Structure (chapters → pages, for reference lookup)

**Volume I: Essays & Formulas (pp. 2–24)**
- Taiwei Fu 2 | Xingxing Fu 3 | Xingyuan Lun 4 | Doushu Zhunsheng 4 | Doushu Fawei Lun 5 | Chongbu Doushu Gulü 5 | Zengbu Taiwei Fu 6
- Questions & Answers on the Stars 7–17 (the nature of the 14 major stars and auxiliary stars)
- Doushu Suisui Fu 17 | Women's Suisui Fu 19
- Ten Grades of Wealth/Nobility/Poverty 21 | Star Merits by Palace 21 | Broken Patterns 22 | Wealth/Nobility by Merit 22 | Poverty by Loss 22
- Wealth Patterns 23 | Nobility Patterns 23 | Poverty Patterns 24 | Miscellaneous Patterns 24

**Volume II: Star Placement (pp. 25–66)**
- Placement of Life & Body palaces 25 | Twelve palaces 25 | Five-element bureau 25 | Na-yin songs 25 | North-South Dipper stars 25
- Wenchang/Wenqu 25 | Zuofu/Youbi 26 | Tiankui/Tianyue 26 | Tianma 26 | Lucun 26 | Qingyang/Tuoluo 26 | Huoxing/Lingxing 26 | Four Transformations 26 | Tiankong/Dijie 27 | Tianshang/Tianshi 27 | Taisui 27 | Tianxing/Tianyao 27 | Santai/Bazuo 27
- Tianku/Tianxu 28 | Longchi/Fengge 28 | Hongluan/Tianxi 28 | Sangmen/Baihu/Diaoke/Guanfu 28 | Doujun 29 | Feitian Sansha 29 | Jielu Kongwang 29 | Xunzhong Kongwang 29 | Great Limit 29 | Small Limit 29 | Tong Limit 30 | Mingzhu/Shenzhu 30 | Jin Suo Tie She Guan 30 | Zhu Luo San Xian 30 | Palace Strength 30 | Star Resting Places 30
- Generation & Control of Stars 31 | North/South Dipper classification 31
- Twelve palaces: good/bad omens (pp. 33–65, mid Volume II)

**Volume III: Star Discourse (pp. 67–83)**
- Tan Xing Yao Lun 67 (master method) | Patterns 67 | Grade levels 68 | Male/female differences 68 | Children's charts 68
- Birth-hour verification 69 | Life-palace hour omens 69 | Precise hour matters 69 | Children harming parents 69 | Late wealth 69
- Ten-year limits 70 | Two limits & Taisui 70 | North-South Dipper limits 70 | Annual Taisui stars 70 | Yin-de longevity 70
- Yang-tuo overlaps 71 | Qisha recurrence 71 | Limit palace taboos 71 | Limit palace songs 71 | Taisui small-limit temples 71
- Stars in combination, wealth/nobility/lifespan by merit 75–83

**Volume IV: Star-in-Palace Detailed Readings (pp. 84–140)** + **Sample Chart Critiques (pp. 141–143)**

## Master Method of Chart Reading (from Tan Xing Yao Lun, p. 67)

Read in order, never invert:

1. **Read the Life Palace**: auspiciousness, temple/exalted states, transforming auspicious/jealous, generation & control. If the Life Palace has no major star, check whether Wealth & Career palaces offer auspicious support — such charts may attain wealth and rank, but often born as secondary/side-branch children.
2. **Read the Body Palace / Body Master**: auspiciousness and generation & control (the Body palace sets the foundation).
3. **Read Migration, Wealth, Career**: the punishments, clashes, breaks in the three directions (Dou Shu weights triads and four corners).
4. **Read the Virtue (Fude) Palace**: power/wealth/emptiness/temples — it faces Wealth and decides character and late-life fortune.
5. The six palaces of Body-Life, Migration, Wealth, Career, Virtue are called the "Eight Seats": all auspicious and transformed auspicious = wealth, rank, long life; all fallen and clustered with jealous stars = lonely, widowed, short-lived.
6. Then read Parents, Spouse, Children: if all hold emptiness/killing/jealous stars, the chart is monk/nun-like, or else lonely and poor.

**Grade hierarchy (On Star Grades, p. 68)**: star & count both high = supreme nobility; star high count mid = Three Dukes; star high count low = Six Ministers; star mid count high = Provincial Judge; star mid count mid = District Magistrate; star mid count low = unofficial career path; star low count high = wealth rivaling Tao Zhu with flourishing descendants; star low count mid = no lack of food and clothing; star low count low = poverty and early death.

**Male vs. Female charts (p. 68)**: Male — first Body-Life, then Wealth/Career/Migration (must be exalted), third Virtue, then Fields/Servants/Health, then Parents/Spouse/Children. Female — first Body-Life (Greedy Wolf, Seven Kills, Qingyang inauspicious), second Virtue (Seven Kills alone in Virtue = prostitute/servant girl), third Spouse, fourth Children/Wealth/Fields; peach-blossom killing stars must fall in defeated/empty places to be ominous.

## Iron Rules of Judgment (from Doushu Zhunsheng & Chongbu Doushu Gulü, pp. 4–5)

- All stars auspicious: even meeting misfortune is auspicious. All stars inauspicious: meeting misfortune is inauspicious.
- Life dwelling in growth-prosperity fixes wealth and rank; Body sitting in emptiness decides glory or decline.
- Life meeting Zi Wei is not only long-lived but honored; Body meeting killing stars is not only poor but base.
- Qingyang-Tuoluo and Seven Kills in limit years: do not meet them — meeting brings punishment and injury; Tianku and Sangmen in annual years: do not encounter them — encountering brings ruin.
- Official star dwelling in fortune land: proximity to nobility, wealth and glory; Fortune star dwelling in career palace becomes useless.
- Appearance meeting misfortune: certain facial flaw; Health meeting jealous star: certain chronic illness.
- Fortune and misfortune travel together; judgment must weigh host/guest strength, temple/fall, merit — never one-size-fits-all.

## The Fourteen Major Stars (from Questions & Answers on the Stars, pp. 7–17)

**Zi Wei 紫微** (Earth; Supreme Emperor of the Central Heaven): governs the pivot of creation and rank. Bestows fortune in all palaces, dissolves a hundred evils, tames Fire-Bell into goodness, converts Seven Kills into authority. Without Zuofu-Youbi companions it is a Solitary Emperor — fine jade with a flaw; with killing stars it is "gentlemen in the wild, petty men in office," making the person cunning and falsely virtuous. In Health/Siblings/Servants/Appearance (four fallen palaces) it brings toil. A woman with it is judged a noble lady.

**Tianji 天机** (Wood; South Dipper star of benefit): transforms into goodness; resourceful, perceptive, methodical. A woman meeting it is blessed. With Tianliang, Zuofu-Youbi, Wenchang-Wenqu: literary men are clean and prominent, military men loyal and good; fallen and broken by four killings: a low grade — monk/nun-like leisure. With Tianliang in the same palace, destined as Taoist or monk; a woman clever but inevitably licentious and running away.

**Taiyang 太阳** (Fire; essence of the Sun; pivot of the Career palace): transforms into nobility and wealth; most suitable in the Career palace. For a man the father star; for a woman the husband star. Rising in Mao-Yin (dawn), enthroned in Chen-Si, "sun beautiful at noon" in Wu = great wealth and rank, Wei-Shen partial walls = diligence then laziness, You = setting, noble but hidden, Xu-Hai-Zi = dim, a lifetime of toil and poverty; eye injuries. With Taiyin shining together: wealth and rank complete; fallen with killings: harms wife and father.

**Wuqu 武曲** (Metal; North Dipper master of the Wealth palace): governs lifespan and wealth; firm and decisive; can bless or harm. With Tianfu in the same palace: long life. With Lu-Ma crossing: wealth from distant places; with Pojun in the wealth palace: wealth gained then void; with Qisha and Huoxing: robbed because of money; with Qingyang-Tuoluo: solitary and harsh; with Pojun: hard to attain rank. Wuqu in idle palaces: much craftsmanship.

**Tianlong 天同** (Water; South Dipper lord of Fortune, transforms into blessing): humble, gentle, skilled in letters; not afraid of Seven Kills; blessed in all twelve palaces. With Zuofu-Youbi and Changliang: noble and prominent; six-Geng-born people in You land: never keep a household; with four killings in Si-Hai: fallen, disabled, solitary.

**Lianzhen 廉贞** (Fire; North Dipper master of rank and orders; transforms imprisonment into killing; secondary peach blossom): cruel-hearted and wild; with the Emperor: wields authority; with Lucun: wealth and rank; in Career: authority. In a prosperous palace: gambling, infatuation, lawsuits. Lianzhen-Qisha in the same place: corpse buried by the road (wandering and drifting); Lianzhen-Greedy Wolf in Si-Hai meeting auspiciousness: abundant fortune, but after thirty, guard against a bad end.

**Tianfu 天府** (Earth; South Dipper first commander; master of the wealth treasury): tames Qingyang-Tuoluo into servants, converts Fire-Bell into blessing. With Lucun and Wuqu: vast wealth. Meeting it, one ends rich; auspicious in all palaces; only emptiness makes it isolated. Fields & Wealth are its temple; Servants & Appearance its fallen weakness.

**Taiyin 太阴** (Water; master of Fields; transforms into wealth): waxing moon is key, waning moon loses power. Mao-Chen-Si-Wu-Wei are fallen; You-Xu-Hai-Zi-Chou are meritorious. For a man the wife star, also the mother star. With Wenqu in Body-Life: a nine-stream artisan; in Body: stepmother-raised or leaving the ancestral home. "Moon bright at Heaven's Gate" (Hai) and "Moon born in the sea" (Zi) are noble patterns.

**Tanlang 贪狼** (Water-Wood; North Dipper liberator; transforms into peach blossom; governs fortune and misfortune): delights in profligate pursuits. With Pojun: lost in wine and women, even death; with Wuqu: flattering and greedy; with Lianzhen in a court: certain punishment; with Fire-Bell: wealth and rank (Fire-Greedy, Bell-Greedy patterns); pleased to see emptiness — turns upright instead. In temple with Fire and Wuqu: authority and rank. Men and women alike, a star not of the blessed land; best unseen.

**Jumen 巨门** (Water-Metal; North Dipper dark essence; transforms into obscurity; governs disputes): a lifetime of slander in Body-Life; in the Spouse palace: cornered separation, living death. With Taiyang: fortune and misfortune mixed; with Seven Kills: killing and injury; with the Emperor: its strength is restrained; with Lucun: its calamity is dissolved. "Jade hidden in stone" (Jumen at Zi-Wu) is a noble pattern. A star of solitude and harshness; only as monk, nun, or nine-stream person is it spared from toil.

**Tianxiang 天相** (Water; South Dipper lord of rank; transforms into the Seal; literary star of the Career palace): honest speech, compassionate heart; assists the Emperor; also dissolves Lianzhen's evil. In Body-Life: glory; auspicious fortune in all twelve palaces. Fallen with Greedy-Lianzhen-Wuqu-Pojun-Qingyang-Tuoluo: artisan skills as refuge; broken by Fire-Bell: disability; a woman: clever, dignified, ambition exceeding men.

**Tianliang 天梁** (Earth; South Dipper lord of lifespan; transforms into protection and longevity; the Parents star): open and magnanimous, warm and humble; versed in strategy; protects the body and blesses descendants. With Changqu-Zuofu-Youbi: reaches high office. Struck by Taisui: still blessed; facing Baihu: unharmed. With Greedy-Jumen: corrupting of morals; with Tianji: monk-nun leisure. An extremely auspicious star, governing longevity.

**Qisha 七杀** (Fire-Metal; South Dipper general; star of success-and-ruin): a star of authority, not truly auspicious. With Zi Wei: converts to authority and blessing; with Fire-Bell: its killing power grows. In Body-Life: a life of hardship; with Changqu in key places: stubborn and wild. "Seven Kills facing the Dipper" (Yin-Shen-Zi-Wu): rank and glory; fallen with killings: evil death in youth. A woman in a prosperous place: wealth and authority that commands the masses, ambition exceeding men.

**Pojun 破军** (Water; North Dipper seventh star; transforms into expenditure; governs spouse, children, servants): violent, fierce, cunning; harms others at the slightest provocation. With Zi Wei: loses authority; with Tianfu: fraud and treachery; with Zi-Greedy: petty theft. With Lianzhen and Fire-Bell: certain lawsuits; with Wuqu in the wealth position: collapse east and west. Only Tianliang restrains its evil; heavenly lu dissolves its madness. In temple at Zi-Wu, with Greedy Wolf and Seven Kills flanking: might that shakes the realm.

## The Six Auspicious Auxiliary Stars (pp. 12–14)

- **Wenchang 文昌** (Metal): governs examination success; refined and scholarly, widely read, instant fame. Chen-Si are prosperous lands; Mao-You it dislikes; unfavorable for Fire-element people.
- **Wenqu 文曲** (Water): governs examination and essays; a scholar of the ranks. With Taiyin in Body: a nine-stream artisan; fears Pojun — disaster near water; dislikes meeting Greedy Wolf — governance inverted. Unsuitable for women: fickle as water and flowers.
- **Zuofu 左辅** (Earth): assists Zi Wei; delights in flanking Sun and Moon. In the Spouse position: a second marriage; with Lianzhen: base and evil, suffering clamps.
- **Youbi 右弼** (Water): star of imperial command; with Zi-Fu auspicious stars in the same palace: wealth and rank in both offices. Broken by Qingyang-Tuoluo-Fire-jealousy: a low grade.
- **Tiankui & Tianyue 天魁天钺**: stars of examination merit in the Dipper; seated with nobility facing nobility; in trouble, noble assistance is certain. When limits pass them: women rejoice in pregnancy, sons born handsome.
- **Lucun 禄存** (Earth; North Dipper true man's star): governs noble rank and lifespan. Body-Life, Fields, Wealth are key — it governs wealth. Alone in the Life palace without auspicious transformations: a miser. Most dislikes falling in empty places; with Fire-Bell and emptiness: artisan skills as refuge.
- **Tianma 天马**: in Body-Life it is called the post horse. With Lucun: Lu-Ma galloping (whip-broken horse); with Zi-Fu: supporting horse; with punishments: corpse-carrying horse; with Huoxing: war horse; with Sun-Moon: yin-yang horse; meeting emptiness: dead horse; with Tuoluo: broken-leg horse — all bring illness and calamity.

## Malefic Stars (pp. 14–16)

- **Qingyang 擎羊** (Fire-Metal; transforms into punishment): North Dipper helper; rough and violent in nature; turns gratitude into resentment. In temple: firm and decisive, governing authority; in Mao-You: calamity and extreme punishment; for six-Jia and six-Geng born: certain misfortune. Blade in temple (Chen-Xu-Chou-Wei) meeting auspiciousness: a noble pattern.
- **Tuoluo 陀罗** (Fire-Metal; transforms into jealousy): crooked in heart and deed; gains and losses by violence, drifting and unsettled. With Greedy Wolf: consumption through wine and lust; in Health: lingering hidden illness. Chen-Xu-Chou-Wei born: blessed.
- **Huoxing 火星** (South Dipper killing god): vicious temperament, outstanding toughness. With Greedy Wolf in a prosperous land: extreme nobility (Fire-Greedy pattern); a woman in a prosperous land: chaste; fallen: licentious.
- **Lingxing 铃星** (South Dipper attendant): brooding temperament, authority and fame. With Greedy Wolf: immediate frontier fame (Bell-Greedy pattern); temple: wealth and rank in office; fallen: solitary poverty.
- **Tiankong & Dijie 天空地劫**: guarding Body-Life, auspicious with auspiciousness, inauspicious with inauspiciousness; certain loss of wealth; in the two limits, certain misfortune. Emptiness and robbery harm most; only monkhood and scholarship escape; mountains of gold and jade still end poor. Emptiness in the chart: drifting or illness.
- **Tianshang & Tianshi 天伤天使**: six positions before the Life palace is Tianshang (Servants); six after is Tianshi (Health). Body and year-limit sandwiched between them is called "sandwich land"; with evil stars, much misfortune. In Taisui or two limits without auspiciousness: official calamity, death, ruin.
- **Tianxing 天刑** (from You, first month, clockwise): with Greedy Wolf: romantic and beating; punishment-and-imprisonment clamping the Seal: a martial, brave person.
- **Tianyao 天姚** (from Chou, first month, clockwise): hidden peach blossom; licentious and runaway nature; with killings: lewd and drunken.

## The Four Transformations (pp. 14–15; formulas in Volume II, p. 26)

- **Hua Lu 化禄 (Wealth transformation)**: the god of fortune. Guarding Body-Life or Career: meeting Quan-Ke, certain high office; a decade of celebration in the Great Limit.
- **Hua Quan 化权 (Power transformation)**: the Small Limit meeting it is never inauspicious; the Great Limit decade surely fulfills ambition; with Qingyang-Tuoluo-waste-jealousy-emptiness: official calamity and demotion.
- **Hua Ke 化科 (Examination transformation)**: star of the celestial examinations, governing letters; with Quan-Lu: minister-level nobility; even broken by four killings, still wealth and rank.
- **Hua Ji 化忌 (Jealousy transformation)**: the star of much interference. Guarding Body-Life: a lifetime of adversity; Small Limit meeting it: a year of deficiency; Great Limit: a decade of regret. With Zi-Fu-Changqu-Zuofu-Youbi-Quan-Ke-Lu in the same palace: still not good; alone with the four killings and waste: drifting with illness.

## Selected Patterns (pp. 23–24)

**Wealth patterns**: Wealth-shade clamping Seal (Wuqu-Tianliang clamping Life) | Sun-Moon clamping Wealth (Wuqu guarding Life, Sun-Moon flanking) | Wealth-Lu clamping Horse | Shade-Seal arching Body | Sun-Moon shining on walls (Sun-Moon in Fields) | Golden radiance (Sun alone at noon, Wu).

**Nobility patterns**: Sun-Moon clamping Life | Sun rising from Fusang (Sun at Mao) | Moon falling in Hai (moon bright at Heaven's Gate) | Moon born in the sea (Moon at Zi in Fields) | Fu-Bi arching the Master | Ruler-Minister celebration (Zi Wei with Zuofu-Youbi at Life) | Wealth-Seal clamping Lu | Lu-Ma with Seal | Seated nobility facing nobility (Kui-Yue flanking) | Horse-head blade (horse with blade) | Seven Kills facing the Dipper | Sun-Moon both bright | Bright pearl emerging from the sea | Sun-Moon together | Punishment-Imprisonment clamping Seal (Tianxing-Lianzhen clamping Body-Life, martial bravery) | Ke-Quan-Lu arching | Greedy-Fire meeting | Wuqu guarding the wall (Wuqu at Mao) | Fu-Xiang facing the court | Zi-Fu facing the court | Literary stars arching Life | Quan-Lu meeting | Blade entering temple (Chen-Xu-Chou-Wei) | Ju-Ji at Mao | Bright Lu hidden Lu | Ke bright hidden Lu | Golden carriage (Zi Wei with Sun-Moon flanking front and back).

**Poverty patterns**: born at the wrong time (Life in emptiness with Lianzhen) | Lu meeting two killings | Horse fallen in emptiness | Sun-Moon hiding radiance (Sun-Moon reversed meeting darkness) | Wealth at enmity with prisoner (Wu-Zhen both in Body-Life) | a lifetime of solitary poverty (Pojun at Life in fallen land) | gentlemen in the wild (four killings in Body-Life in fallen land) | double canopy (Lucun with Hua Lu at Life meeting emptiness).

**Miscellaneous patterns**: wind and cloud meeting | embroidery on brocade | Lu failing, Horse trapped | returning home in brocade (no success in youth, tomb-luck after forty) | steps without support | stars riding water (one good year, one bad) | fortune and misfortune together | dead wood meeting spring (weak chart, good limit).

**Additional judgments from the Bone Marrow Fu (pp. 17–19, much tested)**: Lianzhen-Qisha reversed — a man of accumulated wealth; Tianliang-Taiyin — a drifting guest; first poor then rich: Wuqu-Greedy Wolf in Body-Life; glory from birth: Quan-Lu guarding Wealth-Career; Zi Wei at Wu without killings: rank of Three Dukes; Tianfu at Xu with support: gold belt and purple robes; Sun-Moon together: rank of marquis; Tianji-Tianliang-Qingyang meeting: early punishment, late solitude; Greedy-Wuqu-Lianzhen meeting: poor in youth, blessed later; Bell-Chang-Luo-Wu at the limit: thrown into the river; Horse-head arrow: early death or punishment; Greedy Wolf in Life: certain prostitution; Seven Kills in Body: certain early death.

## Star Placement (Volume II pp. 25–30, the foundation of charting)

- **Life & Body palaces**: from Yin count months clockwise from the first month to the birth month; from that month's branch count backward from Zi hour to the birth hour for the Life palace, forward for the Body palace. Leap month counts as the second month.
- **Twelve-palace order** (both sexes, counterclockwise from Life): Life, Siblings, Spouse, Children, Wealth, Health, Migration, Servants, Career, Fields, Virtue, Parents.
- **Sixty Jiazi Na-yin**: Jiazi-Yichou metal in the sea, Bingyin-Dingmao furnace fire, Wuchen-Jisi great forest wood, Gengwu-Xinwei roadside earth, Renshen-Guiyou sword-edge metal… (full text in reference p. 25).
- **Zi Wei star system** (counterclockwise): Zi Wei, Tianji; skip one — Taiyang, Wuqu, Tiantong; skip two — Lianzhen; skip three — Zi Wei returns (i.e., five positions from Zi Wei to Greedy Wolf, where Tianfu begins).
- **Tianfu star system** (clockwise): Tianfu, Taiyin, Tanlang, Jumen, Tianxiang, Tianliang, Qisha; skip three — Pojun.
- **Wenchang**: from Xu count hours backward to birth hour; **Wenqu**: from Chen count hours forward to birth hour.
- **Zuofu**: from Chen count months forward; **Youbi**: from Xu count months backward.
- **Tiankui & Tianyue** (year stem): Jia-Wu-Geng: ox and goat; Yi-Ji: rat and monkey; Xin: tiger and horse; Ren-Gui: rabbit and snake; Bing-Ding: pig and dog.
- **Tianma** (year branch): Yin-Wu-Xu horse dwells in Shen; Shen-Zi-Chen dwells in Yin; Si-You-Chou dwells in Hai; Hai-Mao-Wei dwells in Si.
- **Lucun** (year stem): Jia Lu at Yin, Yi at Mao, Bing-Wu at Si, Ding-Ji at Wu, Geng at Shen, Xin at You, Ren at Hai, Gui at Zi. **Qingyang** is one position before Lu; **Tuoluo** one after.
- **Fire-Bell** (year branch): Yin-Wu-Xu people at Chou-Mao; Shen-Zi-Chen at Yin-Xu; Si-You-Chou at Mao-Xu; Hai-Mao-Wei at You-Xu.
- **Four Transformations** (year stem): Jia: Lianzhen Lu, Pojun Quan, Wuqu Ke, Taiyang Ji; Yi: Tianji, Tianliang, Ziwei, Taiyin; Bing: Tiantong, Tianji, Wenchang, Lianzhen; Ding: Taiyin, Tiantong, Tianji, Jumen; Wu: Tanlang, Taiyin, Youbi, Tianji; Ji: Wuqu, Tanlang, Tianliang, Wenqu; Geng: Taiyang, Wuqu, Taiyin, Tiantong; Xin: Jumen, Taiyang, Wenqu, Wenchang; Ren: Tianliang, Ziwei, Tianfu, Wuqu; Gui: Pojun, Jumen, Taiyin, Tanlang. See reference p. 26.
- **Great Limit**: Yang-male and Yin-female go forward; Yin-male and Yang-female go backward, starting from the Life palace; the Five-Element Bureau sets the starting age (see reference p. 29).
- **Life Master** (year branch): Zi belongs to Greedy Wolf; Chou-Hai to Jumen; Yin-Xu to Lucun; Mao-You to Wenqu; Chen-Shen to Lianzhen; Si-Wei to Wuqu; Wu to Pojun. **Body Master** (year branch): Zi-Wu Huoxing; Chou-Wei Tianxiang; Yin-Shen Tianliang; Mao-You Tiantong; Chen-Xu Wenchang; Si-Hai Tianji.

## Twelve-Palace Good & Bad Omens (Volume II pp. 33–65, essentials)

- Life: see Master Method. Life seated with evil killings in fallen land before the two limits run: many childhood calamities.
- Siblings: Jumen — estranged siblings; Qingyang-Tuoluo-jealousy in Siblings/Fields/Parents: estrangement (Qingyang-Tuoluo general, p. 15).
- Spouse: Taiyin meeting Wenqu in the Spouse palace: plucking the cassia in the moon palace; Lianzhen-Pojun guarding Spouse: many storms; Tianxiang-Zuofu in Spouse: certain second marriage (Zuofu song); Qisha in Spouse: half-cold bed.
- Children: Pojun — first loss then success; Tianliang shields children; Qingyang-waste-killings in Children: harm to offspring.
- Wealth: Wuqu governs the treasury, most fears emptiness; Taiyin in temple: radiant, heaps of gold and jade; Greedy Wolf in a prosperous palace: a lifetime of petty theft; Pojun in Wealth: wealth melting like snow; Lucun guarding Fields-Wealth: heaps of gold and jade.
- Health: Health meeting jealousy: certain chronic illness; Qingyang-Tuoluo in Health: dim eyes; Taiyin with Tuoluo: eye disease; with Fire-Bell: calamity; with Greedy-killings: eye damage; Pojun in Health: wasting illness.
- Migration: Sha-Po-Lang suited to going abroad (Qisha-Pojun should travel); Lu in Servants: even with office, always running; Tianliang-Tianma fallen: drifting without doubt; Wuqu with Lu-Ma galloping: wealth from distant places.
- Career: Zi-Fu in Career: rich and noble; punishment-killings with Lianzhen in Career: shackles unavoidable; official-fu with punishment-killings in Migration: exiled from home; Taiyang meeting Wenchang in Career: court attendance, wealth and rank complete.
- Fields: Tianfu is the temple of Fields; Pojun in Fields: first break then success, fallen: ancestral property destroyed; Sun-Moon shining on walls delights in tomb-store.
- Virtue: Zi Wei in a man is fallen, in a woman temple-blessed; Qisha alone in Virtue: a woman certain prostitute or servant; Virtue meeting emptiness: running without strength.
- Parents: Tuoluo-waste guarding Parents: certain breaking of ancestry and punishment; evil stars in Parents-Migration: punishment and broken ancestry; Taiyang fallen, radiance lost: harms father; Taiyin fallen, radiance lost: mother has calamity.

## How to Consult the Reference Texts

0. **The library**: `references/ziwei_quanshu_ocr.txt` (Chen Tuan's Complete Book, pp. 1–143) | `references/lijuming_shang.txt` (Li Juming on windfall & speculative wealth, Vol. 1: chart patterns) | `references/lijuming_xia.txt` (Vol. 2: wealth journeys by chart) | `references/xie_tianquan.txt` (Xie Tianquan on strong women & courtesan charts).
1. For a specific question (a star in a palace, whether a pattern forms, a year's fortune), first read this SKILL's digest; if insufficient, consult the reference originals.
2. Full texts are paginated by `===== PAGE N =====`; use the page map above to locate: "Questions & Answers" pp. 7–17; "Star Placement" pp. 25–30; "Palace Merits" pp. 21–22.
3. Search by keyword (e.g., 「问天府所主」「化忌」「批命」「紫微破軍」「女强人」「桃花」); after a hit, read the page context.
4. The texts are OCR output; whenever encountering 「牛/古/坦/已/车/门/内」etc., reconstruct by sense (see OCR corrections above). Li Juming and Xie Tianquan are traditional-script vertical typeset with more errors (「儒」=「偏」、「椽」=「禄」、「剧」=「则」); read with extra care.

## The Heart-Method of Judgment

- First chart the wheel (Bazi → Life & Body palaces → twelve palaces → stars → Four Transformations → Great & Small Limits), then judge patterns, then stars, then limits. Every step must cite the canon; never fabricate.
- Stars have temple and fall; people have generation and control: entering the temple is wondrous, losing degree is empty; strong host, weak guest — safe; weak host, strong guest — danger appears at once.
- Good chart, good body, good limits: glory to old age; weak chart, weak body, weak limits: a lifelong beggar. First read Virtue, then Migration; weigh the opposite palace as body and function, set the triad's source and flow.
- Reading a woman's chart: first Virtue and Spouse; a man's: first Wealth-Career and Migration; peach-blossom and punishment killings govern licentiousness; Ke-Quan-Lu arching governs prominence.
- Whenever disaster is found, one must offer the method of resolution and avoidance (timing, direction, cultivation, accumulated virtue) — this is the proper duty of a cultivator.

## Windfall & Speculative Wealth (Li Juming, two volumes: lijuming_shang.txt & lijuming_xia.txt)

### General Principles

- **Windfall wealth (偏财)**: money outside proper profession — gambling, speculation, lottery, gray-area trades, side income. **Sudden wealth (横财)**: money from nothing, explosive gain — lottery jackpots, casino windfalls, accidental finds.
- Windfall charts are rooted in **seeing Lu**: Hua Lu or Lucun (double Lu best) entering Life, Wealth, or Career triads — only then does windfall have substance; **without Lu, explosive gains end in explosive losses — wealth on paper**.
- **Wuqu Hua Ji and Lianzhen Hua Ji** carry the heaviest windfall nature; with malefics (Fire-Bell-Qingyang-Tuoluo-Emptiness) there is a "walking on a razor's edge" risk — windfall wealth possible, but enemies, lawsuits, and punishment are attracted; hard to keep as blessing.
- **Taiyang Hua Ji** seeking windfall: easy disputes and lawsuits. **Jumen Hua Ji**: lawsuits or hidden damage; with Fire-Bell-Qingyang-Tuoluo-Emptiness-Tianxing: official calamity.
- Wuqu-Tanlang in Wealth: Wuqu the wealth star, Greedy Wolf the desire star — urgent desire for money, must amass great wealth to feel satisfied.
- Huoxing or Lingxing in Life, Wealth, or Career: explosive-wealth nature — "sudden wealth in hand; may play the lottery or gamble for huge profit" — but after rising, must hold fullness and preserve safety, else burst.
- **Fire-Greedy and Bell-Greedy patterns** (Greedy Wolf meeting Fire/Bell in temple): great windfall luck; but Greedy Wolf Hua Lu seeking wealth is toilsome, and fortune is explosive-burst, never lasting.
- Zi Wei resists malefics strongly; Tianji resists very weakly; Tianji meeting malefics with Hua Ji: a crooked mind, windfall trades riddled with deception.

### Windfall Reading by Life Star (Li Juming Vol. 1, by Life-palace combination)

- **Zi Wei-Pojun (Chou-Wei)**: fierce nature; with Fire-Bell: violent temper, thunderous methods. Zi Wei Hua Quan: strong desire for power, methods harsher; Pojun Hua Quan seeking windfall: a toiling fate (hands-on effort); Zi Wei Hua Ke: more brains. This pattern often meets Lianzhen/Greedy Wolf/Wuqu Hua Ji, all strengthening the windfall nature. If Wealth palace must have Wuqu Hua Ke and Career must have Lianzhen Hua Lu: abundant wealth sources. Without auspicious stars, windfall means diversified gray trades — gambling houses, usury, sex industry; with peach-blossom miscellany (Hongluan, Tianxi, Xianchi, Dahao, Tianyao, Muyu): suited to the romantic/sex trade.
- **Zi Wei-Tianfu (Yin-Shen)**: conservative nature; seek sudden wealth preferably with Hua Lu or Lucun. Tianfu without Lu, further seeing Dijie-Tiankong-Xunkong-Jiekong: an "**empty treasury**" — low pattern, wealth hidden from view; exposed treasury means everyone sees one's money and safety is lost, personality petty; Zi-Wei-Tianfu exposed treasury with Tianfu Hua Ke: a hypocrite, using deception and gray methods to earn. If Wealth palace has Wuqu alone without Lu, or Wuqu Hua Ji: strong windfall nature. If Career has Lianzhen-Tianxiang forming the Punishment-Jealousy clamping Seal pattern: proper work hampered, windfall is a stormy sea; if forming Wealth-Shade clamping Seal: an open and upright career, not a windfall chart.
- **Zi Wei-Tanlang (Mao-You)**: "peach blossom violating the master" pattern, deep sensual temperament. Zi Wei Hua Ke or meeting Wenchang-Wenqu: elegant but windfall favorable; life may be emptier. Zi Wei-Tanlang in Life: prone to heart disease, blood-vessel ailments, or mental illness (character-induced). With malefics forming patterns: thrives among the dregs of society, truly capable of leadership — Zuofu-Wenchang flanking, Youbi-Wenqu flanking: both wisdom and boldness, can win fame and wealth in windfall trades. Tanlang Hua Quan too aggressive, worse with Fire-Bell (Wealth palace must have Wuqu Hua Lu, benefiting wealth, but many auspicious stars do not mean gray trades).
- **Zi Wei-Tianxiang (Chen-Xu)**: opposite palace has Pojun arching (a general outside, the king's command unheeded); Wealth has Wuqu-Tianfu (Wuqu acts to earn, Tianfu guards and manages). Wealth-Shade clamping Seal, or Wealth's Wuqu-Tianfu getting Lu (Wuqu Hua Lu / Lianzhen Hua Lu / Lucun): good — suited to proper wealth; methods fierce, personal ties thin, cold, but fewer storms. Punishment-Jealousy clamping Seal: strong windfall tendency, stormy proper career; Zi Wei-Tianxiang Hua Quan with Wuqu Hua Ji in the triad: strong desire for power, windfall may enrich but ties thinner and methods fiercer. Wuqu Hua Ji must be in Zi with Qingyang (Chen palace especially): seeking wealth on a razor's edge, easy lawsuits.
- **Zi Wei-Qisha (Si-Hai)**: converting killing into authority; fierce nature, grand personal ambition, wants to be the boss; aggressive in both proper and windfall wealth. In proper work, avoid Zi Wei Hua Quan (Wealth must have Wuqu Hua Ji): any ordinary industry brings storms; **with Wuqu Hua Ji, proper wealth suits only industry, while windfall matches the nature**; Tanlang Hua Ji with Pojun Hua Quan also favors windfall. Wuqu Hua Lu and Tanlang Hua Quan: strongest wealth aura, both proper and windfall great; especially Hai palace (Career has Lianzhen-Pojun with Lucun; Qisha also delights in Lu). If Life, Wealth, or Career has Huoxing or Lingxing: sudden wealth in hand (lottery, casino), must hold fullness and preserve safety. Lianzhen-Pojun with Lianzhen Hua Ji: work carries danger and high risk; windfall sources broad and diversified; Lian-Po in You is luckier than Mao (Mao's Lianzhen Hua Ji without Lu; You can meet Si's Lucun). Lianzhen Hua Ji governs blood and injury; seeking windfall, beware karmic retribution.
- **Tianji (Zi-Wu / Chou-Wei etc.)**: Zi-Wu in temple; creative, many fancies; with auspicious transformations and then malefics with Hua Ji, windfall becomes favorable instead. Tianji Hua Lu triad must have Tianliang Hua Quan and Taiyin Hua Lu — the Four Transformations gathered, the Three Wonders pattern; with Huoxing-Lingxing-Emptiness: the basic windfall structure. Tianji Hua Ji in Life: hardest to express its goodness; with Qingyang-Tuoluo-Emptiness-Fire-Bell: a crooked mind, windfall trades riddled with deception. Lucun must be at Wu (Zi-Wu Tianji): same palace or arching with Tianji — wealth aura, windfall can fire, proper wealth also fine. Tianji as salaried worker or deputy is safer; same for proper and windfall.

### Windfall Journey by Limit (Li Juming Vol. 2: by Life star's likes/dislikes, judge by the limit's star)

**Method**: the original Wealth-palace star fixes the chart's wealth nature; when a Great Limit enters a star's journey, judge windfall by that star's affinity with the Life star. Core secret — "in a star's journey, that star's Hua Lu is best," "Hua Ji reverses it," "meeting malefics with jealousy: explosive gain, explosive loss."

- **Tianji in Life**: delights in Zi Wei-Tianfu journeys (Lu best), Tiantong-Tianliang (Tiantong Hua Lu: wealth trickles like a long stream), Tianxiang (Wealth-Shade clamping Seal: stable earning; Punishment-Jealousy clamping Seal: higher hopes, greater disappointment), Taiyin (You better than Mao; Taiyin Hua Lu best). Avoids: Wuqu-Qisha (windfall and proper both rough; Wuqu Hua Lu eases wealth; Wuqu Hua Ji: both empty), Lianzhen-Tanlang (stormy; Lianzhen or Tanlang Hua Ji: thin wealth), Jumen (Jumen Hua Lu breaks through; Hua Ji harms windfall; with malefics, lawsuits), Taiyang (Hua Ji causes trouble), Tanlang (only Fire-Greedy/Bell-Greedy favor windfall).
- **Wuqu-Pojun in Life (Si-Hai)**: delights in Qisha journeys (Wuqu's liking, favors windfall; Qisha with Lu best; without Lu and with Fire-Bell-Emptiness-Qingyang-Tuoluo: guard against explosive gain/loss), Lianzhen-Tianxiang (Lianzhen Hua Lu best; Wealth-Shade clamping Seal also good), Taiyin (Taiyin Hua Lu, Tianji Hua Ke: wealth). Avoids: Taiyang (not liked by Wuqu-Pojun; Taiyang Hua Lu eases income), Tiantong (nature mismatched). Wuqu Hua Ji or Tanlang Hua Ji: explosive gain, explosive loss; gain first, loss later — be conservative and quiet, seek windfall by stillness, guard against lawsuits and punishment. Pojun Hua Lu: many dangers in wealth sources but still profit; Taiyang Hua Ji seeking windfall: lawsuits and litigation.
- **Tiantong-Taiyin in Life (Zi-Wu)**: delights in Taiyang-Jumen (sun-moon complement — Taiyang chart likes Taiyin limits, Taiyin chart likes Taiyang limits; Yin's Taiyang-Jumen most favored, Taiyang Hua Lu better; Zi can meet Lucun forming double Lu facing; Wu's Tiantong Hua Lu with Qingyang forms strong stimulation, favoring all three wealths), Tiantong-Taiyin (Tong Hua Lu or Taiyin Hua Lu best), Zi Wei-Tanlang (Lu and auspicious stars open the fortune; Tanlang Hua Lu favors both). Avoids: Jumen (Jumen Hua Ji seeking windfall: lawsuits or hidden damage), Wuqu-Tanlang (many shocks; Wuqu or Tanlang Hua Ji: explosive gain, explosive loss, first gain then loss), Tiantong (windfall weak; Tiantong Hua Lu stabilizes).

## Women's Charts (Xie Tianquan, references/xie_tianquan.txt)

### Strong-Woman Patterns

- Strong-woman chart = Life star in temple/exalted merit + **no broken pattern**. With a broken pattern she is no longer a strong woman — sometimes a shrew: unreasonable, unlearned.
- Those entering strong-woman patterns often have Hua Lu, Hua Quan, Hua Ke, Zuofu, Youbi, Wenchang, Wenqu — Chang-Qu add learning and fame, Fu-Bi raise managerial ability; Hua Lu, Lucun, Tianma add wealth; Tiankui-Tianyue bring noble patronage. The more auspicious stars and transformations, the higher the pattern (upper grade).
- **Zi Wei in Life is the easiest strong-woman pattern.** Zi Wei without auspicious stars but with peach blossom and Hua Ji: falls to the wind-and-dust path; Zi Wei in a low pattern with Fire-Bell-Qingyang-Tuoluo: a tyrant-style strong woman — selfish, cold, inhuman, dictatorial.
- Zi Wei combinations: Zi Wei-Tianfu unfavorable for business; with auspicious stars can be a strong woman in public office (politics, headmistress, institutional officer); Zi Wei-Tanlang suits entertainment/consumer-industry strong women; Zi Wei-Tianxiang is the managerial strong woman, but cold in method; Zi Wei-Pojun rich in pioneering; with Fu-Bi-Kui-Yue-Chang-Qu: a business strong woman; Zi Wei-Qisha (killing into authority) has decent managerial ability even without auspicious stars; Zi Wei Hua Quan especially suits managing rough grassroots men — meet hardness with hardness.
- Citing the Complete Book: a woman with Zi Wei is judged a noble lady; with killing and breaks, an ordinary person, never base.

### Women's Star-by-Star Reading (Xie Tianquan)

- **Lianzhen** (secondary peach blossom): not all Lianzhen-Life women are peach blossom, but Lianzhen beauty draws men near. Lianzhen most delights in Chang-Qu — "Lianzhen with Chang-Qu: peach blossom becomes refined, also learning" — the basic condition of the Lianzhen strong woman. Lianzhen Hua Lu adds talent and wealth; with Chang-Qu suited to management and art. Lianzhen Hua Lu or Hua Ji with malefics and emptiness, plus Hongluan-Tianxi-Xianchi-Tianyao: easily tempted, weak will. Lianzhen-Qisha: the woman least ruled by emotion, steel-strong. Lianzhen-Pojun: turbulent life; with malefics and peach blossom, possible fall to the wind-and-dust — but there she can be a brilliant hostess, a red figure of the pleasure quarters. Lianzhen-Tanlang: double peach blossom; heavy sensual nature; with Chang-Qu-Hongluan-Tianxi-Xianchi-Dahao-Tianyao-Muyu plus Qingyang-Tuoluo-Emptiness-Hua Ji: courtesan traits — not merely for money, but satisfying personal lust; but Lianzhen-Tanlang meeting Huoxing with auspicious transformations, plus Fu-Bi-Kui-Yue-Chang-Qu: peach blossom turned into art — a strong woman of film, entertainment, or fashion design. Lianzhen-Tianfu: meeting Lucun or Hua Lu is the basic requirement of a stable pattern; without Lu and seeing Dijie-Tiankong-Xunkong-Jiekong: "empty treasury," low pattern, selfish and petty; with malefics and Hua Ji: "exposed treasury," crooked and treacherous; with peach blossom miscellany: easy fall to the dust. Lianzhen-Tianxiang: public-relations skill; with Chang-Qu-Hua Lu-Lucun: a managerial strong woman; Lianzhen Hua Ji forming the Qingyang-Tuoluo clamping jealousy pattern, plus malefics and peach blossom: low pattern.
- **Tiantong**: Tiantong-Taiyin with Taiyin in temple: higher pattern, good at study and work, less likely to fall to the dust; Tiantong-Jumen is a star system that hides emotion within (unless Bright Pearl Emerging from the Sea): brooding, inner pain unspeakable, yet a sensual temperament that attracts men; with peach blossom miscellany: dust-tendency. Tiantong-Tianliang with Hua Ke-Hua Quan and Fu-Bi-Kui-Yue-Chang-Qu: higher pattern; with malefics-Hua Ji or Tianliang/Tiantong Hua Lu (plus malefics-emptiness): exaggeration and self-indulgence, willing to fall into the dust. Tiantong's auspicious transformations are not auspicious either — able to enjoy blessing, not strength.
- **Wuqu (Hero star)**: Wuqu alone in Spouse at Chen-Xu: the widow star; unfavorable for marriage; at minimum, discord and easy separation; Tanlang alone in Career at Chen-Xu: slick handling, good management, favorable for business; Tanlang Hua Quan favors public office and disciplined forces.

### Courtesan Patterns (peach-blossom miscellany)

- **The six peach-blossom miscellaneous stars**: Hongluan, Tianxi, Xianchi, Tianyao, Dahao, Muyu. They relate deeply to charts that fall to the wind-and-dust; not every courtesan chart has them, but a Life palace with peach blossom makes this judgment especially apt.
- **Hongluan**: in Life, beautiful and passionate, lively, easy to approach; Hongluan and Tianxi always sit opposite each other (Hongluan at Zi, Tianxi at Wu).
- **Tianxi**: in Life with Hongluan arching: cold-beauty, iceberg-goddess temperament; both love grooming and dressing up.
- **Xianchi**: also governs lewdness; in Life it does not mean beauty, but carries loss of virtue and scandal; a woman with it in Life certainly loves dressing and is striking — but with a tainted, seductive aura.
- **Tianyao**: the licentious star; a single one already relates to lewdness.
- **Dahao**: peach blossom with waste nature; in Life, troubled by lust and emotion, prone to problems with men, or ruining life through lust.
- **Muyu**: unstable peach blossom; meeting Xianchi-Tianyao greatly strengthens the peach-blossom nature.
- Seeing peach-blossom miscellany + malefics with Hua Ji (especially Pojun with Fire-Bell-Qingyang-Tuoluo-Emptiness-Hua Ji): a very low pattern; women easily fall to the dust or similar behavior. Without peach-blossom miscellany but with lighter malefics and some peach blossom: fall through hardship or overreaching ambition.
- Courtesans are not necessarily in sex venues — earning through sex-related activity (mistresses, errand girls, paid by beauty, casual relations) all count; modern courtesans may have decent income or status, but emotion, marriage, children, and ethics are riddled with problems; self-respect wears away in a life without dignity.
- Reading a woman's peach blossom: do not moralize — the chart says what it says, speak plainly, but point out "where this road ends" and the way out.














