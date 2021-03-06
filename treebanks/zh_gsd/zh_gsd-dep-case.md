---
layout: base
title:  'Statistics of case in UD_Chinese-GSD'
udver: '2'
---

## Treebank Statistics: UD_Chinese-GSD: Relations: `case`

This relation is universal.
There are 3 language-specific subtypes of `case`: <tt><a href="zh_gsd-dep-case-dec.html">case:dec</a></tt>, <tt><a href="zh_gsd-dep-case-pref.html">case:pref</a></tt>, <tt><a href="zh_gsd-dep-case-suff.html">case:suff</a></tt>.

3747 nodes (3%) are attached to their parents as `case`.

3730 instances of `case` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.16226314384841.

The following 12 pairs of parts of speech are connected with `case`: <tt><a href="zh_gsd-pos-NOUN.html">NOUN</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (2230; 60% instances), <tt><a href="zh_gsd-pos-VERB.html">VERB</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (655; 17% instances), <tt><a href="zh_gsd-pos-PART.html">PART</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (294; 8% instances), <tt><a href="zh_gsd-pos-PROPN.html">PROPN</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (240; 6% instances), <tt><a href="zh_gsd-pos-PRON.html">PRON</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (199; 5% instances), <tt><a href="zh_gsd-pos-ADJ.html">ADJ</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (68; 2% instances), <tt><a href="zh_gsd-pos-X.html">X</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (29; 1% instances), <tt><a href="zh_gsd-pos-ADV.html">ADV</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (13; 0% instances), <tt><a href="zh_gsd-pos-NUM.html">NUM</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (11; 0% instances), <tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (6; 0% instances), <tt><a href="zh_gsd-pos-AUX.html">AUX</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (1; 0% instances), <tt><a href="zh_gsd-pos-DET.html">DET</a></tt>-<tt><a href="zh_gsd-pos-ADP.html">ADP</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 18	bgColor:blue
# visual-style 18	fgColor:white
# visual-style 22	bgColor:blue
# visual-style 22	fgColor:white
# visual-style 22 18 case	color:blue
1	在	在	VERB	VV	_	12	advcl	_	SpaceAfter=No
2	平原	平原	NOUN	NN	_	1	obj	_	SpaceAfter=No
3	、	、	PUNCT	EC	_	4	punct	_	SpaceAfter=No
4	塔	塔	NOUN	NN	_	2	conj	_	SpaceAfter=No
5	、	、	PUNCT	EC	_	6	punct	_	SpaceAfter=No
6	洞窟	洞窟	NOUN	NN	_	2	conj	_	SpaceAfter=No
7	、	、	PUNCT	EC	_	8	punct	_	SpaceAfter=No
8	海	海	NOUN	NN	_	2	conj	_	SpaceAfter=No
9	或	或	CCONJ	CC	_	10	cc	_	SpaceAfter=No
10	迷宮	迷宮	NOUN	NN	_	2	conj	_	SpaceAfter=No
11	中	中	NOUN	NN	_	2	acl	_	SpaceAfter=No
12	移動	移動	VERB	VV	_	23	advcl	_	SpaceAfter=No
13	時	時	ADP	IN	_	12	mark	_	SpaceAfter=No
14	，	，	PUNCT	,	_	23	punct	_	SpaceAfter=No
15	玩家	玩家	NOUN	NN	_	23	nsubj	_	SpaceAfter=No
16	將	將	ADV	RB	_	23	advmod	_	SpaceAfter=No
17	會	會	AUX	MD	_	23	aux	_	SpaceAfter=No
18	和	和	ADP	IN	_	22	case	_	SpaceAfter=No
19	隨機	隨機	ADV	RB	_	20	advmod	_	SpaceAfter=No
20	遇到	遇到	VERB	VV	_	22	acl:relcl	_	SpaceAfter=No
21	的	的	PART	DEC	_	20	mark:relcl	_	SpaceAfter=No
22	敵人	敵人	NOUN	NN	_	23	obl	_	SpaceAfter=No
23	作戰	作戰	VERB	VV	_	0	root	_	SpaceAfter=No
24	。	。	PUNCT	.	_	23	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 case	color:blue
1	這種	這種	DET	DT	_	2	det	_	SpaceAfter=No
2	車輛	車輛	NOUN	NN	_	10	nsubj	_	SpaceAfter=No
3	如果	如果	ADP	IN	_	4	case	_	SpaceAfter=No
4	歸	歸	VERB	VV	_	10	xcomp	_	SpaceAfter=No
5	私人	私人	NOUN	NN	_	6	nsubj	_	SpaceAfter=No
6	擁有	擁有	VERB	VV	_	4	ccomp	_	SpaceAfter=No
7	，	，	PUNCT	,	_	10	punct	_	SpaceAfter=No
8	多半	多半	ADV	RB	_	10	advmod	_	SpaceAfter=No
9	會	會	AUX	MD	_	10	aux	_	SpaceAfter=No
10	設置	設置	VERB	VV	_	0	root	_	SpaceAfter=No
11	昂貴	昂貴	ADJ	JJ	_	14	amod	_	SpaceAfter=No
12	的	的	PART	DEC	_	11	mark:relcl	_	SpaceAfter=No
13	音頻	音頻	NOUN	NN	_	14	nmod	_	SpaceAfter=No
14	設備	設備	NOUN	NN	_	10	obj	_	SpaceAfter=No
15	、	、	PUNCT	EC	_	17	punct	_	SpaceAfter=No
16	電視	電視	NOUN	NN	_	17	compound	_	SpaceAfter=No
17	機	機	PART	SFN	_	14	conj	_	SpaceAfter=No
18	、	、	PUNCT	EC	_	20	punct	_	SpaceAfter=No
19	影碟	影碟	NOUN	NN	_	20	compound	_	SpaceAfter=No
20	機	機	PART	SFN	_	14	conj	_	SpaceAfter=No
21	，	，	PUNCT	,	_	23	punct	_	SpaceAfter=No
22	以及	以及	CCONJ	CC	_	23	cc	_	SpaceAfter=No
23	吧台	吧台	NOUN	NN	_	14	conj	_	SpaceAfter=No
24	和	和	CCONJ	CC	_	25	cc	_	SpaceAfter=No
25	冰箱	冰箱	NOUN	NN	_	23	conj	_	SpaceAfter=No
26	。	。	PUNCT	.	_	10	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 case	color:blue
1	支線	支線	NOUN	NN	_	19	nsubj	_	SpaceAfter=No
2	從	從	ADP	IN	_	4	case	_	SpaceAfter=No
3	朝陽	朝陽	PROPN	NNP	_	4	compound	_	SpaceAfter=No
4	門	門	PART	SFN	_	5	obl	_	SpaceAfter=No
5	到	到	VERB	VV	_	9	advcl	_	SpaceAfter=No
6	楊閘	楊閘	PROPN	NNP	_	7	nmod	_	SpaceAfter=No
7	環島	環島	NOUN	NN	_	5	obj	_	SpaceAfter=No
8	後	後	ADP	IN	_	5	mark	_	SpaceAfter=No
9	繼續	繼續	VERB	VV	_	19	advcl	_	SpaceAfter=No
10	向	向	ADP	IN	_	11	case	_	SpaceAfter=No
11	東	東	NOUN	NN	_	12	obl	_	SpaceAfter=No
12	行駛	行駛	VERB	VV	_	9	xcomp	_	SpaceAfter=No
13	，	，	PUNCT	,	_	19	punct	_	SpaceAfter=No
14	上	上	VERB	VV	_	19	advcl	_	SpaceAfter=No
15	京	京	PROPN	NNP	_	17	nmod	_	SpaceAfter=No
16	哈	哈	PROPN	NNP	_	17	nmod	_	SpaceAfter=No
17	高速	高速	NOUN	NN	_	14	obj	_	SpaceAfter=No
18	後	後	ADP	IN	_	14	mark	_	SpaceAfter=No
19	到達	到達	VERB	VV	_	0	root	_	SpaceAfter=No
20	通州	通州	PROPN	NNP	_	23	nmod	_	SpaceAfter=No
21	武夷	武夷	PROPN	NNP	_	23	nmod	_	SpaceAfter=No
22	花園	花園	NOUN	NN	_	23	nmod	_	SpaceAfter=No
23	小區	小區	NOUN	NN	_	19	obj	_	SpaceAfter=No
24	。	。	PUNCT	.	_	19	punct	_	SpaceAfter=No

~~~


