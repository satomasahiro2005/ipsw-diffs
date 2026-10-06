## com.apple.DocumentManagerCore.Rename

> `/System/Library/PrivateFrameworks/DocumentManagerCore.framework/XPCServices/com.apple.DocumentManagerCore.Rename.xpc/com.apple.DocumentManagerCore.Rename`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb00` | `0xc68` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x1bc` | `0x250` | **`+0x94`** |
| `__TEXT.__objc_stubs` | `0x280` | `0x2a0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x3c7` | `0x3df` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x160` | `0x168` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-401.1.5.0.0
+403.1.8.0.0

-  Functions: 15
+  Functions: 17

-  CStrings:  84
+  CStrings:  87
Symbols:
+ _objc_retain_x22
- _objc_retain_x2
CStrings:
+ "[Rename] Import API failed, could not build a nofollow wrapper. Error: %@"
+ "[Rename] Rename API failed, could not build a nofollow wrapper. Error: %@"
+ "doc_noFollowSafeWrapper"
```
