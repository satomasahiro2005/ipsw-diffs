## HangHUD

> `/System/Library/CoreServices/HangHUD.app/HangHUD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x1ab0` | `0x1ad0` | **`+0x20`** |
| `__TEXT.__text` | `0x2f624` | `0x2f638` | **`+0x14`** |
| `__TEXT.__objc_methname` | `0xa78d` | `0xa797` | **`+0xa`** |
| `__TEXT.__objc_methtype` | `0x19f9` | `0x19f1` | **`-0x8`** |
| `__TEXT.__cstring` | `0x3891` | `0x3895` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-421.0.0.0.0
+424.0.0.0.0

-  CStrings:  3098
+  CStrings:  3097
Functions:
~ sub_100004130 : 496 -> 548
~ sub_100004320 -> sub_100004354 : 300 -> 308
~ sub_1000044cc -> sub_100004508 : 776 -> 736
CStrings:
+ "@56@0:8@16Q24Q32Q40Q48"
+ "end_matu"
+ "intervalsByClippingIntervals:toHangStart:hangEnd:sampleStart:sampleEnd:"
+ "jsonStringForIntervals:"
+ "start_matu"
- "@32@0:8@16Q24"
- "@40@0:8@16Q24Q32"
- "end_ms"
- "intervalsByClippingIntervals:toWindowStart:end:"
- "jsonStringForIntervals:hangStartMATU:"
- "start_ms"
```
