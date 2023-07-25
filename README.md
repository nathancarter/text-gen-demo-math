
# "Text" Generation with Math Hallucinations

This repository contains a [Streamlit](http://www.streamlit.io) app that can be used
to demonstrate some concepts of generative language models.  It doesn't really
generate text, because all of its training data is simple statements of arithmetic,
such as `10 - 4 = 6` and `9 + 5 = 14`, so all it knows is arithmetic (no words).
But you can customize the sophistication of the (very very simple) model so that
various types of errors (including what LLMs call "hallucinations") are exhibited
or are not exhibited.  It is useful as a demo of some concepts in text generation.

[You can view the app running online here.](https://math-hallucinations.streamlit.app/)

