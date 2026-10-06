## DaemonUtils

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/DaemonUtils.framework/DaemonUtils`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8aa8` | `0x89d4` | **`-0xd4`** |
| `__AUTH_CONST.__objc_intobj` | `0xd8` | `0xa8` | **`-0x30`** |
| `__TEXT.__oslogstring` | `0x997` | `0x96d` | **`-0x2a`** |
| `__DATA_CONST.__const` | `0x1c8` | `0x1a0` | **`-0x28`** |
| `__TEXT.__cstring` | `0x553` | `0x52d` | **`-0x26`** |
| `__AUTH_CONST.__const` | `0x1e0` | `0x1c0` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0x2b00` | `0x2b20` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x228` | `0x238` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xad8` | `0xae8` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0xc8` | `0xb8` | **`-0x10`** |
| `__TEXT.__const` | `0x170` | `0x160` | **`-0x10`** |
| `__TEXT.__objc_methlist` | `0x1230` | `0x1220` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2c0` | `0x2b8` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x160` | `0x164` | **`+0x4`** |

### Other Changes

```diff

-2319.0.33.0.1
+2319.0.46.0.0

-  Functions: 335
-  Symbols:   745
-  CStrings:  114
+  Functions: 331
+  Symbols:   743
+  CStrings:  109
Symbols:
+ -[LAAnalytics initWithEventName:reporter:]
+ GCC_except_table12
+ _LACDTOFeatureEnablementModeRawValueNotSet
+ _OBJC_CLASS_$_LACAnalyticsReporter
+ _OBJC_IVAR_$_LAAnalytics._reporter
- -[LAAnalytics logLevel]
- -[LAAnalyticsDTO logLevel]
- GCC_except_table13
- GCC_except_table18
- _AnalyticsSendEventLazy
- ___23-[LAAnalytics _collect]_block_invoke
- ___block_descriptor_40_e8_32s_e19_"NSDictionary"8?0ls32l8
CStrings:
- "%{public}s analytics event %{public}@: %@"
- "@\"NSDictionary\"8@?0"
- "C"
- "didn't send"
- "sent"
```
