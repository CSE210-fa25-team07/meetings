# Features
Translated emoji limited to `iOS default emoji`.
## Single Word Text Input
Single word text input -> All Emoji Has the Matching
e.g. multi-output
Inpput = sport
Ouput = 🏀 ⚽ 🏉
e.g. single-output
Input = Basketball
Ouput = 🏀
## Emoji Input
Each emoji input mapped to one and only one word.
e.g. single-input
Input = 🏀
Output = Basketball
e.g. multi-input
Input = 🏀 ⚽ 🏉
Ouput = basketball, soccer, football [spearator for `frontend` team to decide]
## Multi-word (paragraph) Input
Each word mapped to one emoji at most.
Not mapped word will remain text in output
e.g. I like basketball
I like 🏀
(if we make like mapped to ❤️: I ❤️ 🏀)
## A Reverse Button
change mode from “english -> emoji” to “emoji -> english”, vice versa

# Interface Design
Layout looks like google translator
