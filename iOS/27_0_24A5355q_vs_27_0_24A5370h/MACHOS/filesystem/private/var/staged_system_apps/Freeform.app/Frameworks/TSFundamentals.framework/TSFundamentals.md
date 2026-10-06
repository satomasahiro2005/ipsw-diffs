## TSFundamentals

> `/private/var/staged_system_apps/Freeform.app/Frameworks/TSFundamentals.framework/TSFundamentals`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a08` | `0x4a44` | **`+0x3c`** |
| `__DATA.__bss` | `0xd8` | `0xe0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x280` | `0x278` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-646.0.0.202.4
+649.0.0.0.3

-  Symbols:   460
+  Symbols:   461
Symbols:
+ _nameDictionaryLock
Functions:
~ +[TSUAssertionHandler packedBacktraceStringWithReturnAddresses:] : 1540 -> 1528
~ -[TSUBacktrace backtraceString] : 168 -> 172
~ -[TSUBacktrace callerAtIndex:] : 148 -> 140
~ _TSULogGetNameDictionary -> _TSULogEnsureCreated : 68 -> 180
~ ___TSULogGetNameDictionary_block_invoke -> ___TSULogEnsureCreated_block_invoke : 72 -> 148
~ _TSULogEnsureCreated -> _TSULogGetName : 208 -> 124
~ ___TSULogEnsureCreated_block_invoke -> _TSULogGetNameDictionary : 76 -> 68
~ _TSULogGetName -> ___TSULogGetNameDictionary_block_invoke : 100 -> 72
~ sub_47e0 -> sub_4814 : 964 -> 972
```
