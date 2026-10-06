## appstored

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Support/appstored`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56ad24` | `0x56b4e4` | **`+0x7c0`** |
| `__TEXT.__oslogstring` | `0x3d5fc` | `0x3d79e` | **`+0x1a2`** |
| `__DATA_CONST.__const` | `0x29720` | `0x297f0` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x21372` | `0x213e9` | **`+0x77`** |
| `__DATA.__objc_const` | `0x33ce0` | `0x33ca0` | **`-0x40`** |
| `__TEXT.__eh_frame` | `0xeab8` | `0xea78` | **`-0x40`** |
| `__TEXT.__gcc_except_tab` | `0x8c28` | `0x8c5c` | **`+0x34`** |
| `__DATA_CONST.__cfstring` | `0x1ad20` | `0x1ad40` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xbce8` | `0xbd08` | **`+0x20`** |
| `__DATA.__bss` | `0x8e50` | `0x8e60` | **`+0x10`** |
| `__DATA.__data` | `0x8628` | `0x8638` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xd6dc` | `0xd6ec` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x22cc` | `0x22c4` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x1e88` | `0x1e80` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
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
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-13.1.12.0.0
+13.1.16.0.0

-  Functions: 13796
+  Functions: 13809

-  CStrings:  15098
+  CStrings:  15108
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
- _$sSL2geoiySbx_xtFZTj
CStrings:
+ "01:15:46"
+ "Coordinator %{public}@ for %{public}@ was created by client %lu, not App Store"
+ "Failed to enumerate coordinators while resolving %lu identifier(s): %{public}@"
+ "ManagedAppDistribution.InstallSheet.AppStore.Body.NoLink.V2"
+ "Notified that coordinator %{public}@ - %{public}@ completed successfully, but we don't have an active installation for it."
+ "Scheduling without coordinator states: %{public}@"
+ "Sep 28 2026"
+ "Unable to load the bag"
+ "[%@] No bag available: %{public}@"
+ "[%@] Timed out waiting to resolve subscribed account"
+ "com.apple.Preview"
+ "com.apple.SiriApp"
+ "com.apple.TVRemoteApp"
- "23:08:22"
- "ManagedAppDistribution.InstallSheet.AppStore.Body.NoLink"
- "Sep 13 2026"
```
