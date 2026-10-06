## SpeakThis

> `/System/Library/AccessibilityBundles/SpeakThis.axuiservice/SpeakThis`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1aadc` | `0x1af4c` | **`+0x470`** |
| `__DATA.__objc_const` | `0x21d0` | `0x2260` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x1319` | `0x137c` | **`+0x63`** |
| `__DATA.__objc_data` | `0x420` | `0x470` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x9e0` | `0xa30` | **`+0x50`** |
| `__TEXT.__cstring` | `0x88d` | `0x8af` | **`+0x22`** |
| `__DATA_CONST.__cfstring` | `0x760` | `0x780` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xd10` | `0xd30` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4f20` | `0x4f40` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x2c3` | `0x2e1` | **`+0x1e`** |
| `__TEXT.__objc_methtype` | `0xc8a` | `0xca3` | **`+0x19`** |
| `__TEXT.__objc_methlist` | `0x1bcc` | `0x1be4` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x17d0` | `0x17e0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x698` | `0x6a8` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x5f65` | `0x5f75` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x48` | `0x50` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x68` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x710` | `0x718` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3237.1.0.0.0
+3240.3.0.0.0

-  Functions: 623
-  Symbols:   341
-  CStrings:  1314
+  Functions: 628
+  Symbols:   345
+  CStrings:  1320
Symbols:
+ _OBJC_CLASS_$_AXSpeakOverlayPassthroughView
+ _OBJC_METACLASS_$_AXSpeakOverlayPassthroughView
+ _dispatch_after
+ _dispatch_time
CStrings:
+ "@40@0:8{CGPoint=dd}16@32"
+ "AXSpeakOverlayPassthroughView"
+ "Frontmost app from focus was a placeholder (pid<=0); using kAXDefaultSpeakThisApplicationAttribute"
+ "com.apple.purplebuddy.budd.access"
+ "hitTest:withEvent:"
+ "name"
```
