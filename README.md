Hangul-Syllabus-for-Python
==========================
http://en.wikipedia.org/wiki/Hangul_Syllables

```
>>> import hangul
>>> hangul.row
[u'AC0', u'AC1', u'AC2', u'AC3', ...]

>>> hangul.column
[u'0', u'1', u'2', u'3', u'4', u'5', u'6', u'7', u'8', u'9', u'A', u'B', u'C', u'D', u'E', u'F']

>>> hangul.total
[u'\uac00', u'\uac01', u'\uac02', u'\uac03', u'\uac04', u'\uac05', u'\uac06', u'\uac07', u'\uac08', u'\uac09', ...]

>>> for key in hangul.total:
...     print key
...
가
각
갂
갃
..
```

```
>>> len(hangul.total)
11172
```
