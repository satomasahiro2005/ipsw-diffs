## tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bbb4` | `0x8bcf8` | **`+0x144`** |
| `__TEXT.__oslogstring` | `0x10851` | `0x108a8` | **`+0x57`** |
| `__TEXT.__cstring` | `0x12a07` | `0x12a48` | **`+0x41`** |
| `__TEXT.__objc_methname` | `0x13084` | `0x130ae` | **`+0x2a`** |
| `__TEXT.__objc_stubs` | `0xb680` | `0xb6a0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x3700` | `0x3708` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5504` | `0x550c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a58` | `0x1a60` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-913.0.0.0.0
+913.0.1.0.0

-  Functions: 3014
+  Functions: 3016

-  CStrings:  5901
+  CStrings:  5904
Functions:
~ sub_10003cdb0 : 1476 -> 332
+ sub_10003cefc
+ sub_100086d30
CStrings:
+ "%s: service %{public}@ has no usageDescriptionKeyName; cannot resolve reminder purpose"
+ "-[TCCDReminderMonitor reminderPurposeForService:client:context:]"
+ "reminderPurposeForService:client:context:"
```
