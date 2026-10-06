## libmdns.dylib

> `/usr/lib/libmdns.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x310b4` | `0x31164` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x21ce` | `0x21c9` | **`-0x5`** |

### Other Changes

```diff

-3089.0.0.0.1
+3109.0.0.0.0
Functions:
~ _DNSMessageToString : 4844 -> 5012
~ __DNSRecordDataToStringEx2 : 5136 -> 5144
CStrings:
+ " ["
+ " key%u"
- " %s%s"
- " key%u=\""
```
