## DataAccessExpress

> `/System/Library/PrivateFrameworks/DataAccessExpress.framework/DataAccessExpress`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2869c` | `0x28764` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x3642` | `0x3667` | **`+0x25`** |
| `__AUTH_CONST.__cfstring` | `0x3f40` | `0x3f60` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2094` | `0x20a4` | **`+0x10`** |
| `__DATA.__bss` | `0x254` | `0x25c` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1560` | `0x1568` | **`+0x8`** |

### Other Changes

```diff

-2708.0.0.0.0
+2708.1.5.0.0

-  Functions: 946
-  Symbols:   2149
-  CStrings:  805
+  Functions: 947
+  Symbols:   2153
+  CStrings:  806
Symbols:
+ +[DABehaviorOptions suppressSyncTokenChangeNotifications]
+ _suppressSyncTokenChangeNotifications.__haveCheckedSuppressSyncTokenChangeNotifications
+ _suppressSyncTokenChangeNotifications.__lastToken
+ _suppressSyncTokenChangeNotifications.__suppressSyncTokenChangeNotifications
Functions:
+ +[DABehaviorOptions customAutoDV2UserAgentEnabled]
CStrings:
+ "SuppressSyncTokenChangeNotifications"
```
