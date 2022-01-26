# 木こり

- 薪便利スクリプト集


## ランダムソート
発表順番を決めるときとか

```python
import numpy as np
name = ["ゾロアット", "ドムットリア", "アビゴル", "ザンネック", "ガルグイユ"]
rng = np.random.default_rng(seed=123)
rng.shuffle(name)
print(name)
```

実行例
```console
$ python sort_name.py 
['ガルグイユ', 'ゾロアット', 'アビゴル', 'ザンネック', 'ドムットリア']
```
