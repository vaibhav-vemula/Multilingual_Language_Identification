# Multilingual Language Identification

### Dataset - 
Dataset used -  https://drive.google.com/file/d/1-2lhUZy9x1WW3WHhTP2DrFl_t9vbPr58/view?usp=sharing

Languages in the dataset -
1. English
2. French
3. Spanish
4. Hindi
5. Portugeese
6. Italian
7. Russian
8. Sweedish
9. Malayalam
10. Dutch
11. Arabic
12. Turkish
13. German
14. Tamil
15. Danish
16. Kannada

## Examples - 

### 1.

```py
sentence = 'भाषा भाषा ПРОВЕРКА ലാംഗ്വേജ് ലാംഗ്വേജ് ലാംഗ്വേജ് ലാംഗ്വേജ് ലാംഗ്വേജ് ലാംഗ്വേജ് ലാംഗ്വേജ് VÉRIFICATION'
pred(sentence)
```
### Output - 
Languages Detected in the Sentence - 

1. Hindi
2. Russian
3. Malayalam
4. French


### 2.

```py
sentence = 'ಕನ್ನಡ ലാംഗ്വേജ് को काला कहा जाता है മലയാളം மொழி' 
pred(sentence)
```
### Output - 
Languages Detected in the Sentence - 

1. Kannada
2. Malayalam
3. Hindi
4. Malayalam
5. Tamil
