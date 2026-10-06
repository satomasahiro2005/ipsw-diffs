## EmergencyAlerts

> `/System/Library/PrivateFrameworks/EmergencyAlerts.framework/EmergencyAlerts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3de8` | `0x3f34` | **`+0x14c`** |
| `__TEXT.__oslogstring` | `0x894` | `0x966` | **`+0xd2`** |
| `__AUTH_CONST.__cfstring` | `0x880` | `0x8a0` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x1d0` | `0x1f0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x184` | `0x1a0` | **`+0x1c`** |
| `__TEXT.__cstring` | `0x494` | `0x47a` | **`-0x1a`** |
| `__DATA_CONST.__const` | `0x268` | `0x250` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x120` | `0x138` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x170` | `0x178` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xc` | `0x10` | **`+0x4`** |

### Other Changes

```diff

-268.0.0.0.0
+272.1.0.0.0

-  Functions: 72
-  Symbols:   222
-  CStrings:  125
+  Functions: 75
+  Symbols:   224
+  CStrings:  130
Symbols:
+ -[EACellBroadcastMessageListener preferredLanguageChanged:]
+ -[EAEmergencyAlertCenter preferredLanguageChanged:]
+ -[EAEmergencyAlertCenter registerNotificationCategories]
+ _CFBundleCopyLocalizedStringForLocalization
+ _CFBundleCreate
+ _OBJC_CLASS_$_NSSet
+ _OBJC_IVAR_$_EAEmergencyAlertCenter._preferredLanguage
+ ___59-[EACellBroadcastMessageListener preferredLanguageChanged:]_block_invoke
+ ___block_descriptor_48_e8_32s40s_e5_v8?0ls32l8s40l8
+ _kCFAllocatorDefault
- -[EAEmergencyAlertCenter registerInternalCategoriesIfNeeded]
- _EACategoryIdentifierGeoAlertWatch
- _EACategoryIdentifierGeoAlertWatchInternal
- _EACategoryIdentifierIgneous
- _OBJC_CLASS_$_NSMutableSet
- ___60-[EAEmergencyAlertCenter registerInternalCategoriesIfNeeded]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e15_v16?0"NSSet"8ls32l8s40l8s48l8
- _objc_retain_x26
CStrings:
+ "Failed to create CFBundleRef from CMAS bundle URL"
+ "Language changing from %{public}@ to %{public}@"
+ "Localizable"
+ "Maps action title: %{public}@"
+ "No change in preferred language from %{public}@"
+ "Open in Maps"
+ "Registered emergency alert notification categories"
+ "Tap-to-Radar"
+ "Tap-to-Radar action title: %{public}@"
+ "en"
- "Registered internal notification categories with icons"
- "geo-alert-watch"
- "geo-alert-watch-internal"
- "igneous"
- "v16@?0@\"NSSet\"8"
```
