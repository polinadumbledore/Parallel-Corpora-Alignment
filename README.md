# Parallel Corpora Alignment
This is the repository for a project «Частотный словарь параллельного корпуса». In this repository, we store the code and files that are required to transorm a corpora of xml files into one single txt file and then align the text. 
## Contents
1. 'xmltotxt.ipynb' — This code is used to transform the folder with xml files into a single txt file. If the line in english/russian doesn't have a counterpart in other language, it is paired with a «None» line. Before the start of every new text, its name and authour is marked like this: ### author - textname.xml ###
2. 'output-eng-rus.txt' — This is the txt file that is made with xmltotxt.ipynb. This part is english-to-russian parallel corpora. Its structure looks like this:
```
"I'll run back.» ||| - Пойду погляжу.
"Do."she answered. ||| - Ступайте, -- сказала она.
```
3. 'output-rus-eng.txt' — This is the txt file that is made with xmltotxt.ipynb. This part is russian-to-englisg parallel corpora. Its structure is similar to 'output-eng-rus.txt' but with russian text on the left and english text on the right.
