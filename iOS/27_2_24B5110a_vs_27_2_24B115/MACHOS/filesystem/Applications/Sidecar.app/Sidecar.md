## Sidecar

> `/Applications/Sidecar.app/Sidecar`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c3d0` | `0x1d3fc` | **`+0x102c`** |
| `__TEXT.__cstring` | `0x4bc` | `0x57c` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0xacf` | `0xb7f` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x213f` | `0x21cd` | **`+0x8e`** |
| `__TEXT.__unwind_info` | `0x5b8` | `0x5f8` | **`+0x40`** |
| `__DATA.__objc_const` | `0xea0` | `0xed0` | **`+0x30`** |
| `__DATA.__objc_data` | `0xbb8` | `0xbe8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xac4` | `0xaf4` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x7a0` | `0x7c8` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x184` | `0x1a4` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xac0` | `0xae0` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x289` | `0x2a9` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x728` | `0x740` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2d0` | `0x2dc` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-  Functions: 806
+  Functions: 824

-  CStrings:  512
+  CStrings:  524
CStrings:
+ "Gesture assertion already exists for current scene: %{public}s"
+ "Gesture assertion taken for current scene: %{public}s"
+ "No currentWindowScene, ignoring: %{public}s"
+ "acquireAssertionForScene(_:)"
+ "areiPadSystemGesturesDisabled"
+ "disableiPadSystemGestures()"
+ "enableiPadSystemGestures()"
+ "sbui_acquireSystemGestureDisableAssertion"
+ "sidecarServiceDisableSystemGestures"
+ "sidecarServiceDisableSystemGestures()"
+ "sidecarServiceEnableSystemGestures"
+ "sidecarServiceEnableSystemGestures()"
```
