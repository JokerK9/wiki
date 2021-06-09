This package allows users to extract keys

```

from wiki import ExtractKeysFromWiki


kws = ExtractKeysFromWiki("Coronavirus")
for kw in kws:
    print(kw[0])
    
```
