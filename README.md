# Why `len('😶‍🌫️') == 4` and other weird things you should know about strings in Python

[**Slides**](PyConUS-2025-slides.pdf)

Strings in Python behave in all sorts of unexpected ways: `len('😶‍🌫️') == 4`, `'ñ' != 'ñ'`, `'‪‮dlrow olleh‬"‬.split()[1] == 'olleh‬‬'`! How is this possible? And importantly, why should you care?

In this presentation, we’ll give a brief introduction to text encoding, the different Unicode standards and how Python encodes strings before we dive deep into Unicode oddities. We’ll cover how one code point can represent multiple characters, why converting between upper-case and lower-case characters should be locale-dependent and how emoji’s work. Finally, we will discuss some best practices for handling unicode input in Python.

After this talk, you'll have a better understanding of strings in Python, the Unicode character encoding and you’ll be aware of some common pitfalls and how to avoid them.
