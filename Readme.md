# markdownExtension_PreCodeCustom
[GitHub - Python-Markdown/markdown: A Python implementation of John Gruber’s Markdown with Extension support.](https://github.com/Python-Markdown/markdown)
python markdown/fenced_codeとattr_listを使用した際に、下記のようになる。
```
{.lang key=value}
-> <pre><code Key=Value>
```
下記のように変更したPython拡張。
```
{.lang key=value}
-> <pre Key=Value><code>
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
