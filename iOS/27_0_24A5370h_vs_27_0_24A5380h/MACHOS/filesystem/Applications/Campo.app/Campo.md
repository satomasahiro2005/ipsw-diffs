## Campo

> `/Applications/Campo.app/Campo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd900` | `0xdddc` | **`+0x4dc`** |
| `__DATA.__common` | `—` | `0x228` | **`+0x228`** |
| `__DATA.__data` | `0xab8` | `0x8b8` | **`-0x200`** |
| `__DATA_CONST.__const` | `0x8a0` | `0x848` | **`-0x58`** |
| `__TEXT.__objc_stubs` | `0x6e0` | `0x720` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xe20` | `0xe40` | **`+0x20`** |
| `__TEXT.__cstring` | `0x39d` | `0x3bd` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x510` | `0x520` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x718` | `0x728` | **`+0x10`** |
| `__TEXT.__const` | `0x634` | `0x644` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x17cc` | `0x17dc` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x5d0` | `0x5d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-67.4.100.0.0
+73.0.5.102.0

-  Functions: 453
-  Symbols:   395
-  CStrings:  313
+  Functions: 498
+  Symbols:   397
+  CStrings:  316
Symbols:
+ _$sSS15CampoUIInternalE0A0V38noConversationSelectedPlaceholderTitleSSvgZ
+ _objc_release_x26
+ _objc_retain_x26
- _$s15CampoUIInternal23CarPlayConversationItemV7summarySSvg
CStrings:
+ "com.apple.AgentCanvasKit"
+ "setEmptyViewTitleVariants:"
+ "title"
```
