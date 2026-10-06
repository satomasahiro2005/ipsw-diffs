## ClarityUIPhoneFaceTimeSettings

> `/System/Library/PreferenceBundles/ClarityUIPhoneFaceTimeSettings.bundle/ClarityUIPhoneFaceTimeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ed4` | `0x300c` | **`+0x138`** |
| `__TEXT.__objc_methname` | `0x13ad` | `0x1422` | **`+0x75`** |
| `__TEXT.__objc_stubs` | `0xee0` | `0xf40` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x270` | `0x2c0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0x140` | `0x170` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xb0` | `0xd8` | **`+0x28`** |
| `__TEXT.__gcc_except_tab` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x108` | `0x128` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x598` | `0x5b0` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x128` | `0x130` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x59c` | `0x5a4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-1851.0.0.0.0
+1854.0.0.0.0

-  Functions: 86
-  Symbols:   341
-  CStrings:  296
+  Functions: 88
+  Symbols:   354
+  CStrings:  299
Symbols:
+ -[CLPHController _didUpdateOutgoingCommunicationLimit]
+ GCC_except_table23
+ __Unwind_Resume
+ ___29-[CLPHController viewDidLoad]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
+ ___objc_personality_v0
+ _objc_copyWeak
+ _objc_destroyWeak
+ _objc_initWeak
+ _objc_loadWeakRetained
+ _objc_msgSend$_didUpdateOutgoingCommunicationLimit
+ _objc_msgSend$registerUpdateBlock:forRetrieveSelector:withListener:
+ _objc_msgSend$reloadSpecifier:animated:
Functions:
~ -[CLPHController viewDidLoad] : 184 -> 376
+ ___29-[CLPHController viewDidLoad]_block_invoke
+ -[CLPHController _didUpdateOutgoingCommunicationLimit]
~ -[AXCLFCommunicationLimitController tableView:didSelectRowAtIndexPath:] : 476 -> 468
~ -[AXCLFCommunicationLimitController _updateForOutgoingCommunicationLimit] : 292 -> 352
CStrings:
+ "_didUpdateOutgoingCommunicationLimit"
+ "registerUpdateBlock:forRetrieveSelector:withListener:"
+ "reloadSpecifier:animated:"
```
