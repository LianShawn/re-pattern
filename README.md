# re-pattern
#两个字符中的内容
```
#example:九江中星是一家医药研发制造商。公司主要从事医药中间体、化学试剂产品的研制与生产。
pattern = r'一家(.*?)。'
re.find_all(pattern,example)
```
