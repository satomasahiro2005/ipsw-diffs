## fpassetmanagerd

> `/usr/libexec/fpassetmanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e0ac` | `0x249c8` | **`+0x691c`** |
| `__DATA.__bss` | `0x480` | `0x780` | **`+0x300`** |
| `__TEXT.__cstring` | `0x98f` | `0xc4f` | **`+0x2c0`** |
| `__TEXT.__const` | `0x608` | `0x778` | **`+0x170`** |
| `__DATA_CONST.__const` | `0x918` | `0xa70` | **`+0x158`** |
| `__TEXT.__swift5_reflstr` | `0x174` | `0x2b4` | **`+0x140`** |
| `__TEXT.__oslogstring` | `0x1978` | `0x1a78` | **`+0x100`** |
| `__DATA.__data` | `0x530` | `0x620` | **`+0xf0`** |
| `__TEXT.__swift5_fieldmd` | `0x224` | `0x304` | **`+0xe0`** |
| `__TEXT.__swift5_typeref` | `0x2d4` | `0x36e` | **`+0x9a`** |
| `__TEXT.__objc_methtype` | `0x1e4` | `0x274` | **`+0x90`** |
| `__TEXT.__swift5_capture` | `0x204` | `0x288` | **`+0x84`** |
| `__TEXT.__constg_swiftt` | `0x220` | `0x298` | **`+0x78`** |
| `__TEXT.__auth_stubs` | `0xe90` | `0xf00` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x5e8` | `0x648` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x460` | `0x4c0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1b4` | `0x1f8` | **`+0x44`** |
| `__DATA_CONST.__auth_got` | `0x750` | `0x788` | **`+0x38`** |
| `__DATA_CONST.__auth_ptr` | `0x180` | `0x1b0` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `—` | `0x30` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1f8` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0xa04` | `0xa24` | **`+0x20`** |
| `__DATA.__common` | `0x70` | `0x58` | **`-0x18`** |
| `__DATA.__objc_const` | `0x3b0` | `0x3c8` | **`+0x18`** |
| `__DATA.__objc_data` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1e0` | `0x1f8` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x24` | `0x3c` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `—` | `0x14` | **`+0x14`** |
| `__TEXT.__swift5_types` | `0x24` | `0x30` | **`+0xc`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1.5.0.0.0
+2.0.0.0.0

-  Functions: 322
-  Symbols:   350
-  CStrings:  285
+  Functions: 365
+  Symbols:   368
+  CStrings:  304
Symbols:
+ _$s8RawValueSYTl
+ _$sBi64_WV
+ _$sSY8rawValue03RawB0QzvgTq
+ _$sSY8rawValuexSg03RawB0Qz_tcfCTq
+ _$sSYMp
+ _$sSdN
+ _$sShMa
+ _$ss10_HashTableV12previousHole6beforeAB6BucketVAF_tF
+ _$ss11_SetStorageC8allocate8capacityAByxGSi_tFZ
+ _$ss11_SetStorageCMn
+ _$ss15_print_unlockedyyx_q_zts16TextOutputStreamR_r0_lF
+ _$ss26DefaultStringInterpolationVN
+ _$ss26DefaultStringInterpolationVs16TextOutputStreamsWP
+ _$ss32_diagnoseUnexpectedEnumCaseValue4type03rawE0s5NeverOxm_q_tr0_lF
+ _$ss5NeverOMn
+ _$ss6HasherV5_hash4seed5bytes5countS2i_s6UInt64VSitFZ
+ _$ss6HasherV8_combineyys6UInt32VF
+ _$ss6UInt32VSHsWP
+ _objc_retain_x26
+ _objc_retain_x8
+ _swift_release_x27
+ _swift_retain_x27
- _objc_retain_x24
- _swift_release_x26
- _swift_retain_x22
- _swift_retain_x26
CStrings:
+ " not supported in this bundle"
+ "/private/var/db/fpsd/dvp/fpassetmanager/fps/cert_info/"
+ "/private/var/db/fpsd/dvp/fpassetmanager/fps/cert_info/bundle_metadata.plist"
+ "/private/var/db/fpsd/dvp/fpassetmanager/fps/cert_info/current_bundle.dat"
+ "/private/var/db/fpsd/dvp/fpassetmanager/fps/cert_info/staging_bundle.dat"
+ "/private/var/db/fpsd/dvp/fpassetmanager/fps/cert_info/staging_metadata.plist"
+ "Asset %s in index but type mismatch or read failed"
+ "Asset %s... type mismatch: requested 0x%s, found 0x%s"
+ "Asset request: bundle=%ld, type=0x%s, id=%s..."
+ "Asset type 0x%s not supported in bundle %ld"
+ "Background tasks registered for %ld bundles"
+ "Boot refresh cancelled due to expiration for %s"
+ "Boot refresh failed for %s: %s"
+ "Built index for %s: %ld assets"
+ "Checking remote ETag at %s"
+ "Daemon initialized with %ld bundle indexes (%ld total assets, ~%ld bytes)"
+ "Failed to build index for %s: %s"
+ "Force refresh requested for bundle %ld"
+ "Indexed %s - ID: %s..., Offset: %ld, Size: %ld bytes"
+ "Loaded bundle: %ld bytes from %s"
+ "Metadata inconsistency detected for bundle %s"
+ "No bundle available yet for %s"
+ "No bundle file exists at %s - nothing to validate"
+ "No bundle installed for %s, attempting initial download"
+ "On-boot check triggered for %s"
+ "Periodic refresh cancelled due to expiration for %s"
+ "Periodic refresh failed for %s: %s"
+ "Periodic refresh triggered for %s"
+ "Periodic task expired by system for %s, cancelling async work"
+ "Rebuilt index for %s: %ld assets"
+ "Signature verification failed before asset read - possible tampering!"
+ "Signature verification failed for on-disk bundle!"
+ "Starting asset bundle refresh for %s (trigger: %s)"
+ "Using internal asset URLs"
+ "Using production asset URLs"
+ "Using production asset URLs (non-internal OS)"
+ "Version request for bundle %ld"
+ "bundleIndexes"
+ "com.apple.fpassetmanagerd.retrievecertinfoonboot"
+ "com.apple.fpassetmanagerd.retrievecertinfoperiodic"
+ "fetchAssetFromBundle:assetType:assetID:reply:"
+ "forceRefreshForBundle:reply:"
+ "getCurrentBundleVersionForBundle:reply:"
+ "https://silverbullet-external.itunes.apple.com/content/fp-assets/fps/cert_info"
+ "https://silverbullet-itms7.itunes.apple.com/content/fp-assets/fps/cert_info"
+ "v32@0:8q16@?24"
+ "v32@0:8q16@?<v@?@\"NSError\">24"
+ "v32@0:8q16@?<v@?I>24"
+ "v44@0:8q16I24@\"NSData\"28@?<v@?@\"NSData\"@\"NSError\">36"
+ "v44@0:8q16I24@28@?36"
- "Asset %s in index but failed to read"
- "Asset request: %s..."
- "Background tasks registered"
- "Boot refresh cancelled due to expiration"
- "Boot refresh failed: %s"
- "Built index for %ld assets"
- "Daemon initialized with asset index (%ld assets, ~%ld bytes)"
- "Daemon started with no asset bundle available"
- "Failed to build index: %s"
- "Force refresh requested"
- "Indexed CA blob - ID: %s..., Offset: %ld, Size: %ld bytes"
- "Loaded bundle: %ld bytes"
- "Metadata inconsistency detected"
- "No bundle available yet"
- "No bundle file exists - nothing to validate"
- "No bundle installed, attempting initial download for asset request"
- "On-boot asset check triggered"
- "Periodic asset refresh triggered"
- "Periodic refresh cancelled due to expiration"
- "Periodic refresh failed: %s"
- "Periodic task expired by system, cancelling async work"
- "Rebuilt index for %ld assets"
- "Starting asset bundle refresh (trigger: %s)"
- "Storage directory does not exist: %s"
- "Using internal asset URL: %s"
- "Using production asset URL (non-internal OS)"
- "Using production asset URL: %s"
- "Version request"
- "assetIndex"
- "❌ Signature verification failed before asset read - possible tampering!"
- "❌ Signature verification failed for on-disk bundle!"
```
