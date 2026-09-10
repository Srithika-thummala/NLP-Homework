Srithika Thummala - 700778790

1. Mini-BPE Learner

This code implements a simple Byte Pair Encoding (BPE) algorithm from scratch.
It starts by representing words as individual characters with an end-of-word marker _.
The code counts adjacent token pairs and repeatedly merges the most frequent pair.
Each merge creates a new subword token and increases the vocabulary size.
The process is repeated for 8 merge steps and the results are printed.

2. BPE on English Language

This code applies BPE tokenization to an English-language text corpus.
It first extracts words using a regular expression and converts them to lowercase.
Each word is split into characters, followed by an end-of-word marker.
The most frequent adjacent token pairs are identified and merged for 30 iterations.
The code displays each merge, its frequency, and the resulting vocabulary size.

3. Naive Tokenization

This code demonstrates simple space-based tokenization using Python's split() function.
A Hindi/Hinglish paragraph is stored as a string and divided wherever spaces occur.
Each resulting item is treated as a separate token and printed individually.
This approach is straightforward but does not intelligently handle punctuation or word parts.
It provides a basic comparison to more advanced subword tokenization methods such as BPE.
