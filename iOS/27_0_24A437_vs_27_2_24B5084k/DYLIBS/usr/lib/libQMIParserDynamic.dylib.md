## libQMIParserDynamic.dylib

> `/usr/lib/libQMIParserDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16dec` | `0x16fe8` | **`+0x1fc`** |
| `__TEXT.__gcc_except_tab` | `0x1990` | `0x19cc` | **`+0x3c`** |
| `__TEXT.__cstring` | `0x2485` | `0x24b0` | **`+0x2b`** |
| `__TEXT.__unwind_info` | `0x878` | `0x898` | **`+0x20`** |

### Other Changes

```diff

-1585.0.0.0.0
+1594.0.0.0.0

-  Functions: 449
-  Symbols:   761
-  CStrings:  390
+  Functions: 450
+  Symbols:   764
+  CStrings:  391
Symbols:
+ __ZN3qmi16createRawRequestEhNS_11buffer_viewEm
+ __ZNSt13runtime_errorC1EPKc
+ __ZNSt13runtime_errorD1Ev
+ __ZNSt3__110shared_ptrIN3qmi17SerializedMessageEED1B9noe220106Ev
- __ZNSt3__110shared_ptrIN3qmi17SerializedMessageEED2B9noe220106Ev
Functions:
~ __ZN3qmi18stripRequestHeaderEhRKNSt3__110shared_ptrIKNS_17SerializedMessageEEE : 44 -> 152
~ __ZN3qmi11fixupHeaderERKNSt3__110shared_ptrINS_17SerializedMessageEEEhh : 72 -> 84
+ __ZN3qmi16createRawRequestEhNS_11buffer_viewEm
CStrings:
+ "This API cannot be called for raw messages"
```
