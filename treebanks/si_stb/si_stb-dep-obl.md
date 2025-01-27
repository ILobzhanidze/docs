---
layout: base
title:  'Statistics of obl in UD_Sinhala-STB'
udver: '2'
---

## Treebank Statistics: UD_Sinhala-STB: Relations: `obl`

This relation is universal.
There are 2 language-specific subtypes of `obl`: <tt><a href="si_stb-dep-obl-lmod.html">obl:lmod</a></tt>, <tt><a href="si_stb-dep-obl-tmod.html">obl:tmod</a></tt>.

24 nodes (3%) are attached to their parents as `obl`.

23 instances of `obl` (96%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.375.

The following 8 pairs of parts of speech are connected with `obl`: <tt><a href="si_stb-pos-VERB.html">VERB</a></tt>-<tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt> (10; 42% instances), <tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt> (6; 25% instances), <tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="si_stb-pos-ADV.html">ADV</a></tt> (2; 8% instances), <tt><a href="si_stb-pos-VERB.html">VERB</a></tt>-<tt><a href="si_stb-pos-PROPN.html">PROPN</a></tt> (2; 8% instances), <tt><a href="si_stb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="si_stb-pos-ADJ.html">ADJ</a></tt> (1; 4% instances), <tt><a href="si_stb-pos-AUX.html">AUX</a></tt>-<tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt> (1; 4% instances), <tt><a href="si_stb-pos-VERB.html">VERB</a></tt>-<tt><a href="si_stb-pos-NUM.html">NUM</a></tt> (1; 4% instances), <tt><a href="si_stb-pos-VERB.html">VERB</a></tt>-<tt><a href="si_stb-pos-PRON.html">PRON</a></tt> (1; 4% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 obl	color:blue
1	එබඳු	එබඳු	ADJ	_	_	2	nmod	_	_
2	තත්ත්වයක්	තත්ත්ව	NOUN	_	Case=Acc|Definite=Ind|Gender=Neut|Number=Sing	6	nsubj	_	_
3	1990	1990	NUM	_	NumType=Card	6	obl	_	_
4	දී	දී	PART	_	AdpType=Post	3	dep	_	_
5	ජපානයේ	ජපාන	NOUN	_	Case=Ine|Definite=Def|Gender=Neut|Number=Sing	6	obl	_	_
6	ඇති	ඇත	VERB	_	_	0	root	_	_
7	විය	වෙ	AUX	_	Mood=Ind|Tense=Past|VerbForm=Fin	6	compound:lvc	_	_
8	.	.	PUNCT	_	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 4 obl	color:blue
1	සාකච්ඡාවල	සාකච්ඡා	NOUN	_	Case=Gen|Gender=Neut|Number=Plur	2	nmod	_	_
2	අරමුණ	අරමුණ	NOUN	_	Case=Nom|Definite=Def|Gender=Neut|Number=Sing	6	nsubj	_	_
3	අයවැය	අයවැය	NOUN	_	Case=Nom|Gender=Neut|Number=Plur	4	nmod	_	_
4	ඡන්දයෙන්	ඡන්ද	NOUN	_	Case=Abl|Definite=Def|Gender=Neut|Number=Sing	6	obl	_	_
5	ආණ්ඩුව	ආණ්ඩු	NOUN	_	Case=Nom|Definite=Def|Gender=Neut|Number=Plur	6	obj	_	_
6	පැරදවීම	පරදි	NOUN	_	Case=Acc|Definite=Def|Number=Sing|VerbForm=Ger	0	root	_	_
7	ය	ය	PART	_	AdpType=Post	6	dep	_	_
8	.	.	PUNCT	_	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 2 obl	color:blue
1	අද	අද	ADV	_	AdvType=Tim	5	obl:tmod	_	_
2	නිදහසේ	නිදහස්	ADV	_	AdvType=Man	5	obl	_	_
3	හුස්ම	හුස්ම	NOUN	_	Case=Acc|Gender=Neut|Number=Plur	4	nmod	_	_
4	පොදක්	පොද	NOUN	_	Case=Acc|Definite=Ind|Gender=Neut|Number=Sing	5	obj	_	_
5	ගැනීමේ	ගන්	NOUN	_	Number=Sing|VerbForm=Ger	6	acl	_	_
6	අවස්ථාව	අවස්ථා	NOUN	_	Case=Nom|Definite=Def|Gender=Neut|Number=Sing	8	obj	_	_
7	ජනතාවට	ජනතා	NOUN	_	Animacy=Anim|Case=Dat|Number=Sing	8	nsubj	_	_
8	තිබේ	තිබෙ	VERB	_	Mood=Ind|Tense=Pres|VerbForm=Fin	0	root	_	_
9	.	.	PUNCT	_	_	8	punct	_	_

~~~


