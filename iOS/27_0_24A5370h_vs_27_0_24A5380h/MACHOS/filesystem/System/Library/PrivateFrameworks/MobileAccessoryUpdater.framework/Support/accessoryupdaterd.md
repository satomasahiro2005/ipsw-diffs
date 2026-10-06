## accessoryupdaterd

> `/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/Support/accessoryupdaterd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f564` | `0x4f6d4` | **`+0x170`** |
| `__TEXT.__cstring` | `0x86fc` | `0x86b9` | **`-0x43`** |
| `__DATA_CONST.__got` | `0x3f8` | `0x430` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x12e8` | `0x12f8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1587.0.3.0.3
+1587.0.21.0.0

-  Functions: 2194
+  Functions: 2198

-  CStrings:  3636
+  CStrings:  3635
CStrings:
+ "%s: ESPRESSO: Message <type=0x%04x, id=0x%04x> Length too big ! expected <%u>, got <%u>"
- "%s: ESPRESSO:Bonus Message <type=0x%04x, length=x0x%04x, id=0x%04x>"
- "%s: ESPRESSO:Message <type=0x%04x, id=0x%04x> Length too big ! expected <%u>, got <%u>"
```
