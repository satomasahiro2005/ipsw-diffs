## Device Recovery Assistant

> `/Applications/Device Recovery Assistant.app/Device Recovery Assistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21314` | `0x216bc` | **`+0x3a8`** |
| `__DATA.__objc_const` | `0x6910` | `0x69e0` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x69a0` | `0x6a60` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x92ca` | `0x9362` | **`+0x98`** |
| `__TEXT.__objc_methlist` | `0x2f88` | `0x2fe8` | **`+0x60`** |
| `__DATA.__objc_data` | `0xbe0` | `0xc30` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x24d0` | `0x2500` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x790` | `0x7b0` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x6bf` | `0x6dc` | **`+0x1d`** |
| `__TEXT.__objc_methtype` | `0x2614` | `0x262e` | **`+0x1a`** |
| `__DATA_CONST.__got` | `0x4d8` | `0x4e0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x130` | `0x138` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x120` | `0x128` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x234` | `0x238` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-150.40.7.0.0
+150.40.9.0.0

-  Functions: 846
-  Symbols:   315
-  CStrings:  2502
+  Functions: 854
+  Symbols:   316
+  CStrings:  2512
Symbols:
+ _LAPasscodeServiceErrorDomain
CStrings:
+ "@\"UINavigationController\""
+ "DRPasscodeHostViewController"
+ "T@\"UINavigationController\",R,N"
+ "_innerNav"
+ "_passcodeErrorIsCancellation:"
+ "code"
+ "domain"
+ "eraseAndUpdateRestricted"
+ "innerNavigationController"
+ "topViewController"
```
