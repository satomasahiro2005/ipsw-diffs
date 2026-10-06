## TrustedPeersHelper

> `/System/Library/Frameworks/Security.framework/XPCServices/TrustedPeersHelper.xpc/TrustedPeersHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a3ccc` | `0x2a43a4` | **`+0x6d8`** |
| `__DATA_CONST.__const` | `0x14d88` | `0x14e78` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x516c` | `0x51f4` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x4f78` | `0x4f90` | **`+0x18`** |
| `__DATA_CONST.__got` | `0xa40` | `0xa30` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-62460.0.38.0.1
+62460.0.55.0.1

-  Functions: 8898
-  Symbols:   578
+  Functions: 8907
+  Symbols:   576
Symbols:
+ _kSecurityRTCEventNameRKSponsorsWithFlagSet
+ _kSecurityRTCEventNameRecoverRKTLKSharesFetchSharesForRecovery
+ _kSecurityRTCFieldNumberOfTLKsFetched
- _kSecurityRTCEventNameRecoverRKTLKShares
- _kSecurityRTCFieldAuthenticatedRKSponsorSelected
- _kSecurityRTCFieldNumRKTLKShares
- _kSecurityRTCFieldNumRKTLKSharesRecovered
- _kSecurityRTCFieldPotentialRKSponsorsWithStableInfoFlagSet
```
