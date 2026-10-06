## nfcd

> `/usr/libexec/nfcd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e71b0` | `0x1e854c` | **`+0x139c`** |
| `__TEXT.__cstring` | `0x22880` | `0x22a48` | **`+0x1c8`** |
| `__TEXT.__oslogstring` | `0x205b3` | `0x20776` | **`+0x1c3`** |
| `__TEXT.__objc_methname` | `0x158cd` | `0x15a48` | **`+0x17b`** |
| `__TEXT.__objc_stubs` | `0xdf40` | `0xe060` | **`+0x120`** |
| `__DATA_CONST.__cfstring` | `0x11320` | `0x113a0` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x4b78` | `0x4bc8` | **`+0x50`** |
| `__DATA_CONST.__objc_arrayobj` | `0x318` | `0x360` | **`+0x48`** |
| `__TEXT.__objc_methlist` | `0x9d9c` | `0x9de4` | **`+0x48`** |
| `__DATA_CONST.__objc_intobj` | `0x7bf0` | `0x7c20` | **`+0x30`** |
| `__DATA.__objc_const` | `0x14ea8` | `0x14ec8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1860` | `0x1880` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `0x1e58` | `0x1e70` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xce0` | `0xcf0` | **`+0x10`** |
| `__TEXT.__const` | `0x144c` | `0x145c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2c48` | `0x2c58` | **`+0x10`** |
| `__DATA.__data` | `0x2b34` | `0x2b3c` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa00` | `0xa08` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1134` | `0x1138` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-370.40.2.0.0
+370.42.1.0.0

-  Functions: 4274
-  Symbols:   671
-  CStrings:  11389
+  Functions: 4281
+  Symbols:   673
+  CStrings:  11419
Symbols:
+ _NFDriverSetReaderModeDynamicBBA
+ _NFPlatformHasAlternateRFSettingsForPACE
CStrings:
+ "%{public}s:%i Applying specialized PACE reader RF tuning"
+ "%{public}s:%i Default forcePaceRFSettings override"
+ "%{public}s:%i Failed to disable dynamic BBA: %{public}@"
+ "%{public}s:%i Failed to re-enable dynamic BBA: %{public}@"
+ "%{public}s:%i Mobile Asset specialized PACE global override"
+ "%{public}s:%i Overriding known bad wireless ECP frame to terminal type other"
+ "%{public}s:%i PACE config enabled"
+ "%{public}s:%i Reverting specialized PACE reader RF tuning"
+ "+[NFATLMobileSettings paceStaticRFAlwaysOn]"
+ "+[NFATLMobileSettings paceStaticRFBundleIds]"
+ "-[NFFieldNotificationECP1_0 initWithDictionary:]"
+ "-[_NFReaderSession _isSpecializedPACEReadingCoreNfcConfig:]"
+ "-[_NFReaderSession _isSpecializedPACEReadingInternalConfig:]"
+ "-[_NFReaderSession prepareForSpecializedPACEReading]"
+ "-[_NFReaderSession revertSpecializedPACEReading]"
+ "NFCD built from (B&I) Stockholm_Base-370.42.1"
+ "PACE_STATIC_RF_ALWAYS_ON"
+ "PACE_STATIC_RF_BUNDLE_IDS"
+ "_didApplySpecializedPACEReading"
+ "_isSpecializedPACEReadingCoreNfcConfig:"
+ "_isSpecializedPACEReadingInternalConfig:"
+ "forcePaceRFSettings"
+ "fr.gouv.france-identite"
+ "pace"
+ "paceStaticRFAlwaysOn"
+ "paceStaticRFBundleIds"
+ "prepareForSpecializedPACEReading"
+ "rangeOfString:options:"
+ "revertSpecializedPACEReading"
+ "setReaderModeDynamicBBA:staticBBA:"
+ "startISO18013WithConnectionHandoverConfiguration:type:credentialType:deviceCAParameters:delegate:"
- "NFCD built from (B&I) Stockholm_Base-370.40.2"
```
