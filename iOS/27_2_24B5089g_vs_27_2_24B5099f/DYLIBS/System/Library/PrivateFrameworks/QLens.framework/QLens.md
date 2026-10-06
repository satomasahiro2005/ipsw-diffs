## QLens

> `/System/Library/PrivateFrameworks/QLens.framework/QLens`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5283c` | `0x5cc38` | **`+0xa3fc`** |
| `__TEXT.__eh_frame` | `0x147c` | `0x175c` | **`+0x2e0`** |
| `__AUTH_CONST.__const` | `0xb808` | `0xbad0` | **`+0x2c8`** |
| `__DATA.__bss` | `0x6780` | `0x6980` | **`+0x200`** |
| `__TEXT.__const` | `0x41a0` | `0x42d0` | **`+0x130`** |
| `__TEXT.__swift5_fieldmd` | `0x18d4` | `0x199c` | **`+0xc8`** |
| `__TEXT.__swift5_reflstr` | `0xcbb` | `0xd7b` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x1220` | `0x12e0` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0xd32` | `0xdb0` | **`+0x7e`** |
| `__TEXT.__cstring` | `0x1809` | `0x1859` | **`+0x50`** |
| `__DATA.__data` | `0xd80` | `0xdc8` | **`+0x48`** |
| `__DATA.__common` | `0x858` | `0x890` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x113c` | `0x1174` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x8a8` | `0x8c8` | **`+0x20`** |
| `__AUTH.__data` | `0x15b0` | `0x15c0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x394` | `0x3a4` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1b0` | `0x1b8` | **`+0x8`** |

### Other Changes

```diff

-6.0.0.0.0
+6.1.1.0.0

-  Functions: 1605
-  Symbols:   614
-  CStrings:  183
+  Functions: 1653
+  Symbols:   627
+  CStrings:  184
Symbols:
+ ___swift_memcpy26_8
+ ___swift_memcpy296_8
+ ___swift_memcpy368_8
+ _associated conformance 5QLens9DateBoundOSHAASQ
+ _associated conformance 5QLens9NamedTimeV4KindOSHAASQ
+ _swift_release_x3
+ _symbolic SDySS_____G 5QLens9DateBoundO
+ _symbolic SS______t 5QLens9DateBoundO
+ _symbolic SiSg
+ _symbolic SiSg______Sgt 10Foundation8CalendarV9ComponentO
+ _symbolic _____ 5QLens9DateBoundO
+ _symbolic _____ 5QLens9NamedTimeV4KindO
+ _symbolic _____Sg 10Foundation8CalendarV9ComponentO
+ _symbolic _____Sg 5QLens9DateBoundO
+ _symbolic ______AAt 5QLens11ParseResultV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 5QLens9DateBoundO
+ _symbolic _____ySaySSGG s23_ContiguousArrayStorageC
- ___swift_memcpy25_8
- ___swift_memcpy281_8
- ___swift_memcpy360_8
- _objc_retain_x21
CStrings:
+ "An interval must bound at least one side (both were the open token \"..\")"
```
