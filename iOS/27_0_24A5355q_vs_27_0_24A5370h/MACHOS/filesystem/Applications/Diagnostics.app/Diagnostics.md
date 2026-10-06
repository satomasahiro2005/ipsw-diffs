## Diagnostics

> `/Applications/Diagnostics.app/Diagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c108c` | `0x1c1874` | **`+0x7e8`** |
| `__DATA.__objc_const` | `0x27128` | `0x272a8` | **`+0x180`** |
| `__DATA_CONST.__const` | `0x12179` | `0x12251` | **`+0xd8`** |
| `__TEXT.__objc_stubs` | `0xb080` | `0xb120` | **`+0xa0`** |
| `__TEXT.__const` | `0xeaf4` | `0xeb54` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x69a8` | `0x6a08` | **`+0x60`** |
| `__DATA.__objc_data` | `0xc1a8` | `0xc1f8` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x13165` | `0x131b5` | **`+0x50`** |
| `__DATA.__data` | `0xb230` | `0xb1f0` | **`-0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x5458` | `0x5494` | **`+0x3c`** |
| `__TEXT.__constg_swiftt` | `0x95dc` | `0x9614` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x738c` | `0x73c4` | **`+0x38`** |
| `__TEXT.__cstring` | `0xaf88` | `0xaf58` | **`-0x30`** |
| `__DATA_CONST.__cfstring` | `0x1e40` | `0x1e20` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x425c` | `0x427c` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0xa68` | `0xa50` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x6318` | `0x6300` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0x4f00` | `0x4ef0` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x3d50` | `0x3d58` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x2790` | `0x2788` | **`-0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x2c0` | `0x2b8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 9537
-  Symbols:   2320
-  CStrings:  5195
+  Functions: 9543
+  Symbols:   2319
+  CStrings:  5198
Symbols:
- _objc_retain_x12
CStrings:
+ "@?24@0:8@?16"
+ "completionReenablingButtonEvents:"
+ "onViewDidAppear"
+ "pendingPresentCompletion"
+ "setDiagnosticsAnimationState:"
- "com.apple.Diagnostics.DKViewControllerPresented"
- "testViewPresented:"
```
