# markdownExtension_PreCodeCustom
python公式markdown/fenced_codeはattr_listを使用した際に、下記のようになる。
```
<pre><code Key=Value>
```
下記のように変更したPython拡張。
```
<pre Key=Value><code>
```


## Requirements
```
import markdown
```

## Installation
```
git clone 
pip install -e .
```
or
```
pip install git+...
```

## Author
ambergon
