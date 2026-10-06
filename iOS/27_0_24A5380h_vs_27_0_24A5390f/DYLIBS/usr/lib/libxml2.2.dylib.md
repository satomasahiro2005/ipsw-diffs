## libxml2.2.dylib

> `/usr/lib/libxml2.2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc6758` | `0xc6844` | **`+0xec`** |
| `__TEXT.__cstring` | `0x19aee` | `0x19bae` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x1b98` | `0x1ba0` | **`+0x8`** |

### Other Changes

```diff

-39.10.2.0.0
+39.10.3.0.0

-  Functions: 2628
-  Symbols:   3098
-  CStrings:  3983
+  Functions: 2629
+  Symbols:   3099
+  CStrings:  3986
Symbols:
+ _xmlSchemaIDCRegisterMatchers
Functions:
~ _xmlAddChild : 504 -> 540
~ _xmlC14NProcessNodeList : 3856 -> 3868
~ _xmlSchemaValidateElem : 3544 -> 3188
+ _xmlSchemaIDCRegisterMatchers
~ _xmlSchemaVAttributesSimple : 120 -> 152
~ _xmlSchemaXPathProcessHistory : 2768 -> 2820
CStrings:
+ "calling xmlSchemaIDCRegisterMatchers()"
+ "negative `pos` at selector (`depth >= matcher->depth` invariant violated)"
+ "negative `pos` in field handler (`depth >= matcher->depth` invariant violated)"
```
