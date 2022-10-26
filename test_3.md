# NLP 自然語言處理
## 中研院ckiptagger
$a^2+b^2 = c^2$
$$a_x+b_x = c_x$$

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

## Jieba 簡體中文