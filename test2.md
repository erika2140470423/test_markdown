# NLP 自然語言處理 ver2

## 中研院 ckiptagger

$a^2+b^2 = 1$
$$a^2 + b^2 = {c_g}^2$$

```<javascript>
from ckiptagger import data_utils, construct_dictionary, WS, POS, NER

def print_word_pos_sentence(word_sentence, pos_sentence):
	assert len(word_sentence) == len(pos_sentence)
	for word, pos in zip(word_sentence, pos_sentence):
		#print(f"{word}({pos})", end="\u3000")
		print(f"{word}", end="\u3000")
	print()
	return

```

## Jieba