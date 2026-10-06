## Passbook

> `/private/var/staged_system_apps/Passbook.app/Passbook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x938` | `0x910` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0x2f80` | `0x2f60` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x4828` | `0x4844` | **`+0x1c`** |
| `__TEXT.__text` | `0xffa0` | `0xffb8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xff0` | `0xfe8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x930` | `0x938` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1695.1.4.0.0
+1696.2.5.0.0

-  Functions: 198
-  Symbols:   404
-  CStrings:  790
+  Functions: 197
+  Symbols:   405
+  CStrings:  789
Symbols:
+ _PKAnalyticsSubjectContactless
CStrings:
+ "presentInitialStateAnimated:withPassWithUniqueID:context:preventTableFallback:completionHandler:"
- "presentInitialState:"
- "presentOffscreenAnimated:withCompletionHandler:"
```
