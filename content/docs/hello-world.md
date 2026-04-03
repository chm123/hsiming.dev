---
title: "Hello World"
weight: 1
# bookFlatSection: false
# bookToc: true
bookHidden: true
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
# bookHref: ''
# bookIcon: ''
---

這是我在 `hsiming.dev` 的第一篇測試文章！🎉

## 1. 測試程式碼區塊 (Code Block)

這是我平時用來測試 LLM 的 Python 腳本：

```python
import os

def call_local_model(prompt):
    print(f"Sending prompt to Ollama: {prompt}")
    # TODO: Implement connection
```

## 2. 測試 LaTeX 數學式
來寫一段機器學習常看到的損失函數（Loss Function）：

$$
J(\theta) = \frac{1}{2m} \sum_{i=1}^{m} (h_\theta(x^{(i)}) - y^{(i)})^2
$$

這是一段行內公式：模型預測值 $y = wx + b$ 會隨著權重更新而改變。