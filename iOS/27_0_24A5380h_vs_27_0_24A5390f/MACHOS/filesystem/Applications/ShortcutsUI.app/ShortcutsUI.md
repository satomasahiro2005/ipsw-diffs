## ShortcutsUI

> `/Applications/ShortcutsUI.app/ShortcutsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f464` | `0x1f954` | **`+0x4f0`** |
| `__TEXT.__objc_stubs` | `0x5860` | `0x5960` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x84d4` | `0x85cd` | **`+0xf9`** |
| `__DATA_CONST.__cfstring` | `0xd40` | `0xe20` | **`+0xe0`** |
| `__TEXT.__cstring` | `0x2483` | `0x24dc` | **`+0x59`** |
| `__DATA.__objc_selrefs` | `0x1cf0` | `0x1d30` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1ea8` | `0x1edd` | **`+0x35`** |
| `__TEXT.__auth_stubs` | `0x6b0` | `0x6e0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0xab0` | `0xad0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x368` | `0x380` | **`+0x18`** |
| `__DATA.__bss` | `0x40` | `0x50` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x7c8` | `0x7d8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x700` | `0x70c` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-5032.5.0.0.0
+5034.0.12.100.0

-  Functions: 777
-  Symbols:   254
-  CStrings:  1858
+  Functions: 781
+  Symbols:   257
+  CStrings:  1875
Symbols:
+ __CFBundleCopyBundleURLForExecutableURL
+ _dladdr
+ _getWFGeneralLogObject
CStrings:
+ "\n"
+ " "
+ "%@ (Pluralization)"
+ "%ld hours"
+ "%ld minutes"
+ "%ld seconds"
+ "%s WFLocalizedString failed to locate current bundle"
+ ", "
+ "WFCurrentBundle_block_invoke"
+ "bundleWithURL:"
+ "componentsJoinedByString:"
+ "initFileURLWithFileSystemRepresentation:isDirectory:relativeToURL:"
+ "length"
+ "localizedStringForKey:value:table:"
+ "localizedStringWithFormat:"
+ "setAccessibilityLabel:"
+ "stringByReplacingOccurrencesOfString:withString:"
```
