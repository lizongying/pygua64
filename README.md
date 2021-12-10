# 六十四卦

六十四卦代替base64

## example

```
from pygua64 import gua64
r = gua64.encode('hello，世界'.encode())
print(r.decode())

r = gua64.decode('䷯䷬䷿䷶䷸䷬䷀䷌䷌䷎䷼䷲䷰䷳䷸䷘䷔䷭䷒☯'.encode())
print(r.decode())
```