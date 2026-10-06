## libATCommandStudioDynamic.dylib

> `/usr/lib/libATCommandStudioDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x559f4` | `0x55e80` | **`+0x48c`** |
| `__TEXT.__gcc_except_tab` | `0x57f0` | `0x58bc` | **`+0xcc`** |
| `__TEXT.__oslogstring` | `0x257f` | `0x259d` | **`+0x1e`** |
| `__TEXT.__unwind_info` | `0x22f0` | `0x2308` | **`+0x18`** |
| `__TEXT.__cstring` | `0x203d` | `0x2032` | **`-0xb`** |

### Other Changes

```diff

-1585.0.0.0.0
+1594.0.0.0.0

-  Symbols:   2295
-  CStrings:  539
+  Symbols:   2296
+  CStrings:  540
Symbols:
+ __ZN3qmi16createRawRequestEhNS_11buffer_viewEm
Functions:
~ __ZN3qmi11ClientProxy5State15handleSend_syncERKN3xpc4dictERKNS2_6objectE : 704 -> 1216
~ __ZN3qmi6Client5State4sendERNS0_9SendProxyE : 1244 -> 1472
~ __ZNK13QMIServiceMsg9serializeEv : 376 -> 452
~ __ZN13QMIServiceMsg17createFromRawDataEPKhth : 8 -> 204
~ __ZN13QMIServiceMsg17createFromRawDataERKNSt3__16vectorIhNS0_9allocatorIhEEEEh : 8 -> 92
~ __ZNK13QMIServiceMsg9serializeEPvm : 284 -> 352
CStrings:
+ "[%s]: Sending RAW Request: %s"
```
