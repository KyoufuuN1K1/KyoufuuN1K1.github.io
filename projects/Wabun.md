---
layout: project
type: project
title: Wabun
date: 2018-06-25
labels:
  - Java
summary: I developed a Java file that converts romaji into Wabun Code.
---

For the purposes of writing a story online, I elected to use Wabun code for section breaks. Wabun code is the Japanese version of Morse code, so the file will take input, then translate it into a series of dots and dashes corresponding to the code.  However, because Java (or the editor I was using) doesn't support Hiragana text strings, I set it up to take romaji (Japanese with romanized text) instead. There are still problems with the ん and small つ in the program, which needs some workarounds to get correct input. There are also issues where the characters would get mixed up, so I believe a complete overhaul is in order.
