# This Section is about automatic spelling correction in Urdu . Studies have shown that the majority of
typing errors are caused by (let's assume the dictionary contains the word “پاکستان(“ :
1. Omitting one letter, e.g., the input word is “پاکتان“.
2. Adding an extra letter, e.g., the input word is “پاکستانف“.
3. Mistyping one letter, e.g., the input word is “پاکسطان“.
4. Transposing two adjacent letters, e.g., the input word is “پاسکتان“.
With the aid of a dictionary, word processing systems can often detect and automatically correct these kinds
of spelling errors.
The Problem:
You are to write a program that recognizes the four kinds of errors described above.
The Input:
The input should be the file wrong.txt which contains wrong words which you have to corrected.
The Output:
Print each input word to be spell checked. Then, if the word is in the dictionary, print CORRECT. If the
word is not in the dictionary, then find each word in the dictionary (in the order provided in the dictionary)
for which the given input word might be a misspelling, and print the appropriate message from the following
list:
ONE LETTER OMITTED FROM word
ONE LETTER ADDED TO word
ONE LETTER DIFFERENT FROM word TWO
LETTERS TRANSPOSED IN word
where word is a dictionary word. If the input word is not CORRECT and none of the above messages apply,
then print UNKNOWN.
Note that two or more of the above messages might be applicable to an input word, and that one message
might apply for more than one dictionary word. Note, however, that for a given input word and given
dictionary word, at most one of the above messages apply. For each input word, you are to process the
dictionary words in the order provided in the input and print all messages that are valid.
