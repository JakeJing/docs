

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Basque)

This relation is universal.

66 nodes (0%) are attached to their parents as `discourse`.

41 instances of `discourse` (62%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.66666666666667.

The following 12 pairs of parts of speech are connected with `discourse`: [eu-pos/VERB]()-[eu-pos/PART]() (20; 30% instances), [eu-pos/VERB]()-[eu-pos/INTJ]() (19; 29% instances), [eu-pos/VERB]()-[eu-pos/CONJ]() (6; 9% instances), [eu-pos/VERB]()-[eu-pos/X]() (6; 9% instances), [eu-pos/VERB]()-[eu-pos/ADJ]() (5; 8% instances), [eu-pos/VERB]()-[eu-pos/ADV]() (4; 6% instances), [eu-pos/CONJ]()-[eu-pos/ADV]() (1; 2% instances), [eu-pos/CONJ]()-[eu-pos/INTJ]() (1; 2% instances), [eu-pos/CONJ]()-[eu-pos/PART]() (1; 2% instances), [eu-pos/NOUN]()-[eu-pos/INTJ]() (1; 2% instances), [eu-pos/VERB]()-[eu-pos/DET]() (1; 2% instances), [eu-pos/VERB]()-[eu-pos/PRON]() (1; 2% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 1 discourse	color:blue
1	Ez	ez	PART	_	Negative=Neg	6	discourse	_	_
2	,	,	PUNCT	_	_	6	punct	_	_
3	ez	ez	PART	_	Negative=Neg	6	neg	_	_
4	naiz	izan	AUX	_	Mood=Ind|Number[abs]=Sing|Person[abs]=1	6	aux	_	_
5	bakarrik	bakarrik	ADV	_	_	6	advmod	_	_
6	egoiten	egon	VERB	_	Aspect=Imp|VerbForm=Inf	0	root	_	_
7	e	e	NOUN	_	Animacy=Inan|Case=Abs|Definite=Def|Number=Sing	6	vocative	_	_
8	!	!	PUNCT	_	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 2 discourse	color:blue
1	-	-	PUNCT	_	_	8	punct	_	_
2	Eskerrak	eskerrak	INTJ	_	_	8	discourse	_	_
3	ez	ez	PART	_	Negative=Neg	8	neg	_	_
4	nintzen	izan	AUX	_	Aspect=Prog|Mood=Ind|Number[abs]=Sing|Person[abs]=1	8	aux	_	_
5	garai	garai	NOUN	_	_	8	nmod	_	_
6	hartan	hura	DET	_	Case=Ine|Definite=Def|Number=Sing	5	det	_	_
7	bizi	bizi	NOUN	_	Case=Abs|Definite=Ind	8	compound	_	_
8	izan	izan	VERB	_	Aspect=Perf|VerbForm=Part	0	root	_	_
9	!	!	PUNCT	_	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 11 discourse	color:blue
1	Baina	baina	CONJ	_	_	4	cc	_	_
2	interes	interes	NOUN	_	_	4	nsubj	_	_
3	handiak	handi	ADJ	_	Case=Abs|Definite=Def|Number=Plur	2	amod	_	_
4	daude	egon	VERB	_	Aspect=Prog|Mood=Ind|Number[abs]=Plur|Person[abs]=3	0	root	_	_
5	hori	hori	DET	_	Case=Abs|Definite=Def|Number=Sing	6	nsubj	_	_
6	hala	hala	ADV	_	_	4	advcl	_	_
7	izan	izan	VERB	_	VerbForm=Inf	6	cop	_	_
8	ez	ez	PART	_	Negative=Neg	7	neg	_	_
9	dadin	*edin	AUX	_	Mood=Sub|Number[abs]=Sing|Person[abs]=3	7	aux	_	_
10	,	,	PUNCT	_	_	7	punct	_	_
11	ezta	ezta	X	_	_	4	discourse	_	_
12	?	?	PUNCT	_	_	4	punct	_	_

~~~


