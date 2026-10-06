## CoreODI

> `/System/Library/PrivateFrameworks/CoreODI.framework/CoreODI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x1220` | `0x1240` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1c24` | `0x1c34` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x5b0` | `0x5b8` | **`+0x8`** |
| `__TEXT.__text` | `0x53a94` | `0x53a9c` | **`+0x8`** |

### Other Changes

```diff

-27.0.49.0.0
+27.0.52.0.0

-  Symbols:   1067
-  CStrings:  255
+  Symbols:   1068
+  CStrings:  256
Symbols:
+ _ODIServiceProviderIdIDVMigrate
Functions:
~ sub_25b147a8c -> sub_25c361a8c : 144 -> 36
~ sub_25b147b1c -> sub_25c361ab0 : 36 -> 20
~ sub_25b147b40 -> sub_25c361ac4 : 20 -> 36
~ sub_25b147b54 -> sub_25c361ae8 : 36 -> 28
~ sub_25b147b78 -> sub_25c361b04 : 20 -> 144
CStrings:
+ "com.apple.idv.migrate"
```
