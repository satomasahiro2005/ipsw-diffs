## nearbyd

> `/usr/libexec/nearbyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55d244` | `0x55d8c0` | **`+0x67c`** |
| `__TEXT.__oslogstring` | `0x63ada` | `0x63c1a` | **`+0x140`** |
| `__TEXT.__gcc_except_tab` | `0x558ac` | `0x5595c` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x23aa5` | `0x23b25` | **`+0x80`** |
| `__DATA_CONST.__cfstring` | `0x177a0` | `0x17800` | **`+0x60`** |
| `__TEXT.__cstring` | `0x38e52` | `0x38eb2` | **`+0x60`** |
| `__DATA.__objc_const` | `0x1b900` | `0x1b940` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x17600` | `0x17640` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1d120` | `0x1d150` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xf8bc` | `0xf8e4` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x71c0` | `0x71d0` | **`+0x10`** |
| `__TEXT.__const` | `0x3faaa0` | `0x3faab0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x22dfd` | `0x22e0d` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x1a34` | `0x1a3c` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
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
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-575.0.5.0.0
+575.0.6.0.0

-  Functions: 23613
+  Functions: 23619

-  CStrings:  19977
+  CStrings:  19989
CStrings:
+ "#ses-loc,DL-TDoA background runtime budget (%.0fs) elapsed; force-closing session."
+ "#ses-loc,DL-TDoA background session NOT supported"
+ "#ses-loc,DL-TDoA session started while Not Foreground: %d; will be force-closed after %.0fs."
+ "#ses-loc,Skipping client update: no valid DL-TDoA anchors in range while app is backgrounded"
+ "DL-TDoA background session NOT supported"
+ "NIDLTDOABackgroundLaunchEnabled"
+ "_appLaunchedFromBackground"
+ "_checkIsInternalToolProxtool"
+ "_isClientBackgrounded"
+ "_sessionLaunchedFromBackground"
+ "isBackgroundSession"
+ "sessionInvalidateWithReason:isLaunchedFromBackground:"
+ "v24@0:8C16B20"
- "sessionInvalidateWithReason:"
```
