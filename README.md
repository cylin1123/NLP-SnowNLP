## Python Version
* version 2.7.12
## Package
* SnowNLP
~~~~
pip install snownlp
~~~~
## SnowNLP
snownlp是一個中文的自然語言處理的Python套件，支援中文自然語言操作
* 中文分詞
*	詞性標注
*	情感分析
*	文本分類
*	轉換成拼音
*	繁體轉簡體
*	提取文本關鍵字
*	提取文本摘要
*	TF-IDF
*	Tokenization
*	文本相似

### SnowNLP 情感分析
情感分析結果是【0，1】區間上的一個值，越接近1，情感越積極，越接近0，情感越消極 => 可以理解為positive的概率
~~~~
s.sentiments
~~~~

### SnowNLP 繁體轉簡體
~~~~
s.han
~~~~

### SnowNLP 提取文章關鍵字
~~~~
s.keywords(N) # 提取N個關鍵字詞
~~~~

### SnowNLP 提取文章關鍵字
~~~~
s.summary(N) # 提取N個關鍵字詞組成摘要
~~~~

