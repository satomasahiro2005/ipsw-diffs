## EmergencyAlerts

> `/System/Library/PrivateFrameworks/EmergencyAlerts.framework/EmergencyAlerts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3820` | `0x3de8` | **`+0x5c8`** |
| `__AUTH_CONST.__cfstring` | `0x780` | `0x880` | **`+0x100`** |
| `__TEXT.__cstring` | `0x40e` | `0x494` | **`+0x86`** |
| `__TEXT.__oslogstring` | `0x824` | `0x894` | **`+0x70`** |
| `__DATA_CONST.__objc_selrefs` | `0x3e8` | `0x430` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x230` | `0x268` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x148` | `0x170` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x110` | `0x120` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x178` | `0x184` | **`+0xc`** |

### Other Changes

```diff

-263.0.0.0.0
+266.0.0.0.0

-  Functions: 70
-  Symbols:   210
-  CStrings:  114
+  Functions: 72
+  Symbols:   222
+  CStrings:  125
Symbols:
+ -[EAEmergencyAlertCenter registerInternalCategoriesIfNeeded]
+ _EACategoryIdentifierGeoAlertInternal
+ _EACategoryIdentifierGeoAlertWatchInternal
+ _OBJC_CLASS_$_NSMutableSet
+ _OBJC_CLASS_$_UNNotificationAction
+ _OBJC_CLASS_$_UNNotificationActionIcon
+ _OBJC_CLASS_$_UNNotificationCategory
+ ___60-[EAEmergencyAlertCenter registerInternalCategoriesIfNeeded]_block_invoke
+ ___NSArray0__struct
+ ___block_descriptor_56_e8_32s40s48s_e15_v16?0"NSSet"8ls32l8s40l8s48l8
+ _objc_retain_x26
+ _os_variant_has_internal_content
CStrings:
+ "Additional Details supported by carrier bundle: %{BOOL}d"
+ "MAPS_ACTION_TITLE"
+ "Registered internal notification categories with icons"
+ "TAP_TO_RADAR_ACTION_TITLE"
+ "geo-alert-internal"
+ "geo-alert-watch-internal"
+ "ladybug"
+ "map"
+ "maps"
+ "tap-to-radar"
+ "v16@?0@\"NSSet\"8"
```
