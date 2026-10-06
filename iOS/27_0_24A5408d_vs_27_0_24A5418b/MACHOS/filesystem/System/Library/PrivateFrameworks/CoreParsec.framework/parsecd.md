## parsecd

> `/System/Library/PrivateFrameworks/CoreParsec.framework/parsecd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1768f4` | `0x175520` | **`-0x13d4`** |
| `__DATA.__objc_const` | `0x7738` | `0x7498` | **`-0x2a0`** |
| `__DATA.__data` | `0x9ce0` | `0x9b40` | **`-0x1a0`** |
| `__TEXT.__oslogstring` | `0x6286` | `0x6156` | **`-0x130`** |
| `__TEXT.__objc_classname` | `0x14b7` | `0x13d7` | **`-0xe0`** |
| `__DATA.__objc_data` | `0x1680` | `0x15b8` | **`-0xc8`** |
| `__TEXT.__constg_swiftt` | `0x5aec` | `0x5a28` | **`-0xc4`** |
| `__TEXT.__objc_methname` | `0x6665` | `0x65d5` | **`-0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x5254` | `0x51c4` | **`-0x90`** |
| `__TEXT.__swift5_typeref` | `0x500a` | `0x4f98` | **`-0x72`** |
| `__TEXT.__swift5_reflstr` | `0x5603` | `0x5593` | **`-0x70`** |
| `__TEXT.__const` | `0xf0e0` | `0xf080` | **`-0x60`** |
| `__TEXT.__objc_stubs` | `0x4200` | `0x41a0` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x54f8` | `0x5498` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x10ec` | `0x10a4` | **`-0x48`** |
| `__TEXT.__eh_frame` | `0x75e0` | `0x75a0` | **`-0x40`** |
| `__TEXT.__cstring` | `0x6944` | `0x6924` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x1598` | `0x1580` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x2f8` | `0x2e0` | **`-0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1f08` | `0x1ef8` | **`-0x10`** |
| `__TEXT.__swift5_types` | `0x4a0` | `0x494` | **`-0xc`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.56.26.0.0
+3600.56.26.11.2

-  Functions: 9057
+  Functions: 9025

-  CStrings:  2552
+  CStrings:  2536
CStrings:
- "Caller location authorization changed: %{bool,public}d (status: %{public}d, accuracy: %{public}ld)"
- "Caller location authorized: %{bool,public}d for %{public}s"
- "Caller location request failed: %@"
- "Caller location updated: (%{public}f, %{public}f) accuracy: %{public}fm"
- "_TtC7parsecd21CallerLocationMonitor"
- "_TtCC7parsecd21CallerLocationMonitorP33_623A24F31DADE66D4B56BCDC3BA1128F5State"
- "_TtCC7parsecd21CallerLocationMonitorP33_623A24F31DADE66D4B56BCDC3BA1128F8Delegate"
- "accuracyAuthorization"
- "authHandler"
- "authorizationStatus"
- "authorized"
- "initWithEffectiveBundleIdentifier:delegate:onQueue:"
- "locationHandler"
- "manager"
- "parsecd.Delegate"
- "safariCallerLocationMonitor"
```
