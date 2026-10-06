## AppleEthernetRL

> `/System/Library/Extensions/AppleEthernetRL.kext/AppleEthernetRL`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x2a8f` | `0x2ad5` | **`+0x46`** |
| `__TEXT_EXEC.__text` | `0x28170` | `0x2818c` | **`+0x1c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-171.0.0.0.0
+175.40.1.0.0

-  CStrings:  343
+  CStrings:  344
Symbols:
+ __ZZN15AppleEthernetRL4stopEP9IOServiceE20kalloc_type_view_292
- __ZZN15AppleEthernetRL4stopEP9IOServiceE20kalloc_type_view_283
CStrings:
+ "[0x%llx] rl::%s(%d): failed to allocate essential timer event source\n"
```
