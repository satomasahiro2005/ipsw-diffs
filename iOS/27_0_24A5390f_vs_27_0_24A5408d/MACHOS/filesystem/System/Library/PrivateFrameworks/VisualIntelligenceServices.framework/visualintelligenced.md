## visualintelligenced

> `/System/Library/PrivateFrameworks/VisualIntelligenceServices.framework/visualintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35da4` | `0x362c4` | **`+0x520`** |
| `__DATA.__objc_const` | `0xda8` | `0x1098` | **`+0x2f0`** |
| `__TEXT.__oslogstring` | `0x149a` | `0x151a` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x2240` | `0x22a0` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x324` | `0x384` | **`+0x60`** |
| `__DATA.__data` | `0xf18` | `0xf70` | **`+0x58`** |
| `__TEXT.__objc_methtype` | `0x11f` | `0x15c` | **`+0x3d`** |
| `__TEXT.__auth_stubs` | `0x1dd0` | `0x1e00` | **`+0x30`** |
| `__TEXT.__cstring` | `0x959` | `0x987` | **`+0x2e`** |
| `__DATA_CONST.__const` | `0x1440` | `0x1468` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x865` | `0x889` | **`+0x24`** |
| `__TEXT.__unwind_info` | `0xb70` | `0xb90` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xef0` | `0xf08` | **`+0x18`** |
| `__TEXT.__const` | `0x1558` | `0x1568` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x6b0` | `0x6c0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x3f0` | `0x3f8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x6d0` | `0x6d8` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x1d0` | `0x1d8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-234.0.0.0.0
+246.0.0.0.0

-  Functions: 736
-  Symbols:   795
-  CStrings:  241
+  Functions: 742
+  Symbols:   800
+  CStrings:  244
Symbols:
+ _$s15Synchronization5_CellVMn
+ _$s22VisualIntelligenceCore24InferenceResourceManagerC22releaseWarmHoldForExityyFTj
+ _$s22VisualIntelligenceCore24InferenceResourceManagerC5clock11idleTimeout14evictionPolicy18warmStateDidChangeACyxGx_s8DurationVAA08EvictionK0OySbYbcSgtcfC
+ _$s22VisualIntelligenceCore24InferenceResourceManagerCAAs15ContinuousClockVRszrlE6sharedACyAEGvgZ
+ _$s22VisualIntelligenceCore24InferenceResourceManagerCyxGScAAAMc
+ _$sSp12deinitialize5countSvSi_tF
- _$s22VisualIntelligenceCore24InferenceResourceManagerC5clock11idleTimeout14evictionPolicyACyxGx_s8DurationVAA08EvictionK0OtcfC
CStrings:
+ "Acquired warm os_transaction (IRM resources warm)"
+ "Released warm os_transaction (IRM resources evicted)"
+ "com.apple.visualintelligenced.irm-warm"
```
