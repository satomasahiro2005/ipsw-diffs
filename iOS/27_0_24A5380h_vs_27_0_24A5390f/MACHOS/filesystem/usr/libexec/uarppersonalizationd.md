## uarppersonalizationd

> `/usr/libexec/uarppersonalizationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x49d0` | `0x4b4c` | **`+0x17c`** |
| `__DATA_CONST.__cfstring` | `0xf00` | `0xfa0` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0xa20` | `0xaa0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x903` | `0x939` | **`+0x36`** |
| `__TEXT.__cstring` | `0xd7e` | `0xdae` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x2e0` | `0x300` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x108` | `0x120` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x510` | `0x520` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1a8` | `0x1b8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1587.0.21.0.0
+1587.0.27.0.0

-  Functions: 123
-  Symbols:   117
-  CStrings:  343
+  Functions: 126
+  Symbols:   120
+  CStrings:  352
Symbols:
+ _OBJC_CLASS_$_NSCalendar
+ _OBJC_CLASS_$_NSDate
+ _OBJC_CLASS_$_NSMutableString
CStrings:
+ "%02ld-%02ld-%02ld"
+ "%04ld-%02ld-%02ld"
+ "-"
+ "PLST"
+ "PMAP"
+ "appendFormat:"
+ "component:fromDate:"
+ "currentCalendar"
+ "now"
```
