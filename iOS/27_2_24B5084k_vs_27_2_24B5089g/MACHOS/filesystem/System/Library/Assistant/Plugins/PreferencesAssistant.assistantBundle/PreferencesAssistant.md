## PreferencesAssistant

> `/System/Library/Assistant/Plugins/PreferencesAssistant.assistantBundle/PreferencesAssistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x84fc` | `0x8694` | **`+0x198`** |
| `__TEXT.__cstring` | `0x606` | `0x68e` | **`+0x88`** |
| `__TEXT.__objc_methname` | `0x916` | `0x976` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xb20` | `0xb80` | **`+0x60`** |
| `__DATA_CONST.__cfstring` | `0x640` | `0x680` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x3c0` | `0x400` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x8fc` | `0x924` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0xce7` | `0xd0b` | **`+0x24`** |
| `__DATA_CONST.__auth_got` | `0x1f0` | `0x210` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x3b0` | `0x3c8` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x221` | `0x22f` | **`+0xe`** |
| `__DATA_CONST.__got` | `0x330` | `0x338` | **`+0x8`** |
| `__TEXT.__const` | `0x98` | `0xa0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a8` | `0x1b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-2027.1.4.0.0
+2027.1.6.0.0

-  Functions: 112
-  Symbols:   312
-  CStrings:  368
+  Functions: 115
+  Symbols:   317
+  CStrings:  377
Symbols:
+ _TCCAccessResetForBundleIdWithOptions
+ ___NSDictionary0__struct
+ __os_feature_enabled_impl
+ _notify_post
+ _objc_retain_x28
CStrings:
+ "########## PASetSiriAuthorizationForApp: %@ (%@ / prev: %@ / value: %@ / excluded: %@ / resetExclusion: %@ / %@)"
+ "AppExclusions"
+ "B32@0:8@16@24"
+ "IntelligenceFlow"
+ "TCC App Access exclusion reset failed"
+ "_clearSiriExclusionForAppID:"
+ "_isAppAccessFeatureEnabled"
+ "_isExcludedFromSiri:"
+ "_siriAccessForBundle:tccAccessInfo:"
+ "com.apple.assistant.siri_settings_did_change"
+ "kTCCServiceSiriAccess"
- "########## PASetSiriAuthorizationForApp: %@ (%@ / prev: %@ / value: %@ / %@)"
- "_accessForAppID:"
```
