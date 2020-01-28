---
title: Lexical Grammar
weight: 1
---

# Lexical Grammar

```
IDENTIFIER -> ALPHA (ALPHA | DIGIT)*
ALPHA -> a-z | A-Z | _
DIGIT -> 0-9
STRING -> " any char except " "
NUMBER -> DIGIT+ [.DIGIT+]
LINE_COMMENT -> "//" any character
BLOCK_COMMENT ->. "/*"any character "*/"
```


