# AMR_CHINESE_CHALLENGE_SET

Description: 120 sentences in four templates.

The amr annotation of the same dataset as the UD one (https://github.com/rabbit0v0/UD_CHINESE_CHALLENGE_SET), which is collected and extended from commonMT contextless dataset (https://github.com/tjunlp-lab/CommonMT).
The sentenses are morphological similar but different semantically, they have ambiguities resolved by selectional preferences and commonsense reasoning.

The templates include:
- [VERB][NOUN1][ATV][NOUN2]
- [NUM][CLF][NOUN1]([ADP])[ATV][NOUN2]
- [VERB][PFV][NUM][CLF][NOUN]
- [NOUN1][CCONJ][NOUN2][ATV][NOUN3] or [NOUN1][ATV][NOUN2][CCONJ][NOUN3]

In our templates, ATV is 的(de), CLF is the classifier in the quantifier phrases like 个(ge), PFV is 了(le). Reference: https://link.springer.com/article/10.1007/s10579-021-09564-2

The source of the semantics: http://verbs.colorado.edu/chinese/cpb/html_frames/index.html

The AMR criterion: CAMR guidelines v1.2 (https://www.cs.brandeis.edu/~clp/camr/res/CAMR_GL_v1.2.pdf)

