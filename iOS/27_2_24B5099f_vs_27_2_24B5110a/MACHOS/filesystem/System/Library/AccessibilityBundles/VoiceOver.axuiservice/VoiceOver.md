## VoiceOver

> `/System/Library/AccessibilityBundles/VoiceOver.axuiservice/VoiceOver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25c58` | `0x25f78` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0x2e7` | `0x35c` | **`+0x75`** |
| `__DATA.__data` | `0x16a8` | `0x16c8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4dc0` | `0x4de0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x9f8` | `0xa10` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x4c8` | `0x4d8` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x7140` | `0x7150` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1ac0` | `0x1ac8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2482.13.3.0.0
+2482.13.4.0.0

-  Functions: 844
+  Functions: 849

-  CStrings:  1534
+  CStrings:  1536
CStrings:
+ "Removing VoiceOver chrome for scene %{public}@ (displayID=%{public}@, cursor=%d captionPanel=%d rotor=%d curtain=%d)"
+ "_sceneIdentifier"
```
