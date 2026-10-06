## libATCommandStudioDynamic.dylib

> `/usr/lib/libATCommandStudioDynamic.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55b7c` | `0x556f0` | **`-0x48c`** |
| `__TEXT.__gcc_except_tab` | `0x58bc` | `0x57f0` | **`-0xcc`** |
| `__TEXT.__oslogstring` | `0x259d` | `0x257f` | **`-0x1e`** |
| `__TEXT.__unwind_info` | `0x2308` | `0x22f0` | **`-0x18`** |
| `__TEXT.__cstring` | `0x2032` | `0x203d` | **`+0xb`** |

### Other Changes

```diff

-  Symbols:   2296
-  CStrings:  540
+  Symbols:   2295
+  CStrings:  539
Symbols:
- __ZN3qmi16createRawRequestEhNS_11buffer_viewEm
Functions:
~ __ZN3qmi11ClientProxy5State15handleSend_syncERKN3xpc4dictERKNS2_6objectE : 1216 -> 704
~ __ZN3qmi6Client5State4sendERNS0_9SendProxyE : 1472 -> 1244
~ __ZNK13QMIServiceMsg9serializeEv : 452 -> 376
~ __ZN13QMIServiceMsg17createFromRawDataEPKhth : 204 -> 8
~ __ZN13QMIServiceMsg17createFromRawDataERKNSt3__16vectorIhNS0_9allocatorIhEEEEh : 92 -> 8
~ __ZNK13QMIServiceMsg9serializeEPvm : 352 -> 284
CStrings:
- "[%s]: Sending RAW Request: %s"
```
