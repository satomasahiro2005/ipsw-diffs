## GAXClient

> `/System/Library/AccessibilityBundles/GAXClient.bundle/GAXClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa1ec` | `0xa284` | **`+0x98`** |
| `__DATA_CONST.__cfstring` | `0x2980` | `0x2a00` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2a28` | `0x2aa6` | **`+0x7e`** |
| `__DATA_CONST.__const` | `0xcc0` | `0xcd0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   466
-  CStrings:  757
+  Symbols:   468
+  CStrings:  761
Symbols:
+ _GAXProfileAllowsDisplayChanges
+ _GAXProfileAllowsLayoutTransitions
Functions:
~ sub_9518 : 2852 -> 2948
~ _gaxDebugDescriptionForGAXBackboardState : 764 -> 820
CStrings:
+ "  allowsDisplayChanges: %ld\n"
+ "  allowsLayoutTransitions: %ld\n"
+ "GAXProfileAllowsDisplayChanges"
+ "GAXProfileAllowsLayoutTransitions"
```
