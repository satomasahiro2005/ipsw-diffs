## appleaccountd

> `/usr/libexec/appleaccountd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f7494` | `0x3f7d50` | **`+0x8bc`** |
| `__TEXT.__oslogstring` | `0x210ad` | `0x212ad` | **`+0x200`** |
| `__TEXT.__eh_frame` | `0x14824` | `0x14884` | **`+0x60`** |
| `__DATA.__data` | `0x14480` | `0x144a0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x8588` | `0x85a8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1580` | `0x1568` | **`-0x18`** |
| `__TEXT.__auth_stubs` | `0x3810` | `0x3800` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1c10` | `0x1c08` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x66a0` | `0x66a4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1069.125.4.0.0
+1069.125.7.0.0

-  Functions: 10281
-  Symbols:   1820
-  CStrings:  4205
+  Functions: 10282
+  Symbols:   1818
+  CStrings:  4213
Symbols:
+ _$s10Foundation4DateV2geoiySbAC_ACtFZ
+ _$s11Distributed0A23TargetInvocationDecoderP18decodeNextArgumentqd__yKlFTj
- _$s10Foundation4DateVSLAAMc
- _$s14XPCDistributed9XPCSystemC17InvocationDecoderV18decodeNextArgumentxyKSeRzSERzlF
- _$sSL2geoiySbx_xtFZTj
- _swift_conformsToProtocol2
CStrings:
+ "Avatar update handled by Contacts, using 1-hour expiration"
+ "Avatar update handled by background upload, using 3-day expiration"
+ "Cached identity from network fetch"
+ "Cancelling in-flight background refresh and upload for avatar update"
+ "Invalidating cached identity for account: %{private,mask.hash}s"
+ "Name-only update, preserving existing cache metadata"
+ "Network fetch failed, returning identity with name components only"
+ "Removed cached identity file"
```
