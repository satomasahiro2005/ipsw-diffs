## BlissReader

> `/private/var/staged_system_apps/Books.app/Frameworks/BlissReader.framework/BlissReader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a4688` | `0x2a3b08` | **`-0xb80`** |
| `__TEXT.__objc_methname` | `0x8e069` | `0x8e160` | **`+0xf7`** |
| `__TEXT.__cstring` | `0x36a9e` | `0x36a33` | **`-0x6b`** |
| `__DATA.__objc_const` | `0x7cae0` | `0x7cb20` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x26b00` | `0x26ac0` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x60740` | `0x60780` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x4989c` | `0x498cc` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x1ed68` | `0x1ed88` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xdf10` | `0xdf18` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3e44` | `0x3e48` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x5b54` | `0x5b50` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-6629.0.0.0.0
+6636.0.0.0.0

-  Functions: 22728
+  Functions: 22731

-  CStrings:  32251
+  CStrings:  32254
CStrings:
+ "%lu column.count"
+ "%lu row.count"
+ "TB,N,V_isPresentationStyleTransitionInFlight"
+ "_isPresentationStyleTransitionInFlight"
+ "assetViewControllerLockContentLayoutAtSize:"
+ "assetViewControllerUnlockContentLayout"
+ "isPresentationStyleTransitionInFlight"
+ "setIsPresentationStyleTransitionInFlight:"
- "-[THBookViewController willRevealTOC]"
- "column.count.plural %@"
- "column.count.singular %@"
- "row.count.plural %@"
- "row.count.singular %@"
```
