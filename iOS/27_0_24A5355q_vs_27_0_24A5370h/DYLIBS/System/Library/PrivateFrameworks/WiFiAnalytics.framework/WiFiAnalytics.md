## WiFiAnalytics

> `/System/Library/PrivateFrameworks/WiFiAnalytics.framework/WiFiAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x11c1b` | `0x11cf5` | **`+0xda`** |
| `__TEXT.__text` | `0x154ea4` | `0x154f00` | **`+0x5c`** |
| `__TEXT.__cstring` | `0x148b0` | `0x148ee` | **`+0x3e`** |
| `__AUTH_CONST.__objc_const` | `0x16bf0` | `0x16c20` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2a40` | `0x2a10` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x105b8` | `0x105e0` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x8a0` | `0x8b8` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x8c68` | `0x8c80` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0xa30` | `0xa40` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xfd8` | `0xfdc` | **`+0x4`** |

### Other Changes

```diff

-825.52.0.0.0
+825.53.0.0.0

-  Functions: 6035
-  Symbols:   8778
-  CStrings:  4067
+  Functions: 6038
+  Symbols:   8780
+  CStrings:  4071
Symbols:
+ -[AnalyticsProcessor _attributedBSSForCachedFaultsWithError:]
+ -[WAEvent bssidAttributionAttempted]
+ -[WAEvent setBssidAttributionAttempted:]
+ _OBJC_IVAR_$_WAEvent._bssidAttributionAttempted
+ ___block_descriptor_66_e8_32s40s48r56r_e5_v8?0ls32l8s40l8r48l8r56l8
- GCC_except_table71
- GCC_except_table73
- ___block_descriptor_66_e8_32s40s48r56r_e5_v8?0ls32l8r48l8s40l8r56l8
CStrings:
+ "%{public}s::%d:Batch fault attribution: bss=%@ until=%@ (faults=%lu)"
+ "%{public}s::%d:Batch fault attribution: eventSequencesFor: failed: %@"
+ "%{public}s::%d:Batch fault attribution: failed to build events-of-interest: %@"
+ "-[AnalyticsProcessor _attributedBSSForCachedFaultsWithError:]"
+ "WiFiAnalytics-825.53 Jun 16 2026 21:43:37"
- "WiFiAnalytics-825.52 May 29 2026 20:06:48"
```
