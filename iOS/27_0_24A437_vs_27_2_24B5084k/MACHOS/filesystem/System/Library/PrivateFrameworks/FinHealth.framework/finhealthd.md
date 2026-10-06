## finhealthd

> `/System/Library/PrivateFrameworks/FinHealth.framework/finhealthd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xec68` | `0x10134` | **`+0x14cc`** |
| `__TEXT.__eh_frame` | `0xf90` | `0x11f0` | **`+0x260`** |
| `__TEXT.__oslogstring` | `0x648` | `0x7a8` | **`+0x160`** |
| `__TEXT.__unwind_info` | `0x580` | `0x5f0` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x780` | `0x7d0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x5b2` | `0x5f2` | **`+0x40`** |
| `__TEXT.__const` | `0x402` | `0x432` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0xe0` | `0x104` | **`+0x24`** |
| `__DATA.__objc_const` | `0x470` | `0x450` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0xae0` | `0xb00` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x260` | `0x280` | **`+0x20`** |
| `__TEXT.__cstring` | `0xc7` | `0xe3` | **`+0x1c`** |
| `__TEXT.__swift_as_ret` | `0x78` | `0x8c` | **`+0x14`** |
| `__DATA.__data` | `0x488` | `0x478` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x578` | `0x588` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x217` | `0x227` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x26c` | `0x27c` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x117` | `0x107` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xdc` | `0xd0` | **`-0xc`** |
| `__DATA.__objc_selrefs` | `0x178` | `0x180` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xc8` | `0xc0` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x1b4` | `0x1ac` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x6c` | `0x74` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1.9.1.30.0
+1.9.2.3.0

-  Functions: 464
+  Functions: 486

-  CStrings:  130
+  CStrings:  137
Symbols:
+ _objc_release_x27
+ _swift_retain_x28
- _$s13FinHealthCore0aB11FeatureFlagV0aB8FeaturesO21financekitIntegrationyA2EmFWC
- _swift_deletedAsyncMethodErrorTu
CStrings:
+ "Periodic full sync completed — no grouping-relevant changes"
+ "Periodic full sync completed — triggering grouping recompute"
+ "Periodic full sync failed: %@"
+ "Periodic full sync: BGSystemTask triggered"
+ "Periodic full sync: already ran this lifecycle, skipping"
+ "Periodic full sync: entityGroupWriter failed: %@"
+ "Periodic full sync: incomeInsightWriter failed: %@"
+ "hasRunOvernightSync"
+ "periodic-full-sync"
+ "updateTransactionsAsyncWithForceFullSync:batchSize:completionHandler:"
- "Bypass background group processing"
- "overnightSync"
- "processingRegistration"
```
