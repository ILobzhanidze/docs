---
layout: relation
title:  'obl:prep'
shortdef : 'prepositional pronouns'
udver: '2'
---

`obl:prep`, used for prepositional pronouns, is a UD Irish subtype of the [obl]() relation: 

(previously nmod:prep)

16 of the most common Irish simple prepositions can be inflected to mark pronominal objects. These are referred to as pronominal prepositions or prepositional pronouns. We regard these as playing nominal modifier roles instead of prepositional modifier roles.

### Examples
_agam_ "at me"; _leis_ "with him", _uainn_ "from us"
 
_D'inis mé <b>di</b>_ `I told her'
 
~~~ sdparse
D' inis mé di \n  [] told I to_her
obl:prep(inis, di)
~~~

_Is dóigh <b>leis</b> go bhfuil páirtíocht <b>acu</b> lena chéile_ `He believes that they have a partnership together'

~~~ sdparse
Is dóigh leis go bhfuil páirtíocht acu lena chéile \n Is belief with_him that is partnership at_them with each_other
obl:prep(dóigh, leis)
obl:prep(bhfuil, acu)
~~~

_Níl fhios <b>agam</b>_ `I don't know'

~~~ sdparse
Níl fhios agam \n Is_not knowledge at_me
obl:prep(Níl,agam)
~~~ 

Note, the label is used for adpositional prepositions also. See below. 

_Níl fhios <b>agam</b>_ `I don't know'

~~~ sdparse
Tháinig an féar glas ann. \n Came the grass green in_it. 
obl:prep(Tháinig,ann)
~~~ 