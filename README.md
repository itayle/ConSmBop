# ConSmBop - Context-Dependent Bottom-up Semantic Parsing
Code for my [ConSmBop project](ConSmBop.pdf) will be available soon.

* [About](#About)
    * [Acknowledgements](#Acknowledgements)


# About
[SmBoP](https://arxiv.org/abs/2010.12412) is
a semi-autoregressive bottom-up semantic parser,
which takes an utterance and a DB schema as input, and constructs at decoding step $t$ the top-$K$
program sub-trees of height $≤ t$.


In this work I studied several methods to enhance SmBoP’s contextual modeling to improve performance when mapping a sequence of context-dependent user utterances to structured programs. I altered the
encoder to address previous utterances, and enriched
the decoder at each decoding step by reusing subtrees of the same height predicted in previous turns
within the same interaction.

## Acknowledgements
I thank Prof. Jonathan Berant and Ohad Rubin for
their valuable guidance and feedback.


