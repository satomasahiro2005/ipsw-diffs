## EmergencyAlertsUIExtension

> `/System/Library/PrivateFrameworks/EmergencyAlerts.framework/PlugIns/EmergencyAlertsUIExtension.appex/EmergencyAlertsUIExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5618` | `0x5c5c` | **`+0x644`** |
| `__DATA_CONST.__cfstring` | `0x680` | `0x8c0` | **`+0x240`** |
| `__TEXT.__objc_stubs` | `0x1b20` | `0x1c80` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x6c0` | `0x808` | **`+0x148`** |
| `__TEXT.__objc_methname` | `0x168e` | `0x17b9` | **`+0x12b`** |
| `__TEXT.__cstring` | `0x403` | `0x52a` | **`+0x127`** |
| `__DATA.__objc_selrefs` | `0x840` | `0x898` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x1e0` | `0x218` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x1b8` | `0x1e0` | **`+0x28`** |
| `__DATA.__objc_const` | `0x650` | `0x670` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x3c0` | `0x3d0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__TEXT.__const` | `0x10c` | `0x114` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x3c` | `0x40` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-263.0.0.0.0
+266.0.0.0.0

-  Functions: 98
-  Symbols:   165
-  CStrings:  449
+  Functions: 101
+  Symbols:   173
+  CStrings:  486
Symbols:
+ _CFAbsoluteTimeGetCurrent
+ _EACategoryIdentifierGeoAlertInternal
+ _EACategoryIdentifierGeoAlertWatchInternal
+ _OBJC_CLASS_$_NSURLComponents
+ _OBJC_CLASS_$_NSURLQueryItem
+ _OBJC_CLASS_$_UIFontMetrics
+ _UIFontDescriptorSystemDesignDefault
+ _UIFontTextStyleBody
+ _UIFontTextStyleFootnote
+ _UIFontTextStyleHeadline
+ _objc_retain_x28
- _UIFontWeightBold
- _UIFontWeightRegular
- _objc_retain_x23
CStrings:
+ "2280104"
+ "993331"
+ "Alert supports Additional Details: %{BOOL}d"
+ "All"
+ "ComponentID"
+ "ComponentName"
+ "ComponentVersion"
+ "Description"
+ "Emergency Alerts"
+ "Failed to construct Tap To Radar URL"
+ "Failed to open Tap To Radar"
+ "Keywords"
+ "Please attach screenshots and provide a brief description of the issue faced."
+ "Skipping showing Safety Alerts View: Additional Details supported for this message ID"
+ "Successfully opened Tap To Radar"
+ "Tap ignored: Additional Details not supported for this message ID"
+ "TimeOfIssue"
+ "Title"
+ "User tapped 'Tap To Radar' action"
+ "User tapped alert, showing Additional Details"
+ "[EmergencyAlerts]"
+ "alertSupportsAdditionalDetails"
+ "boolValue"
+ "dateWithTimeIntervalSinceReferenceDate:"
+ "fontDescriptor"
+ "fontDescriptorWithDesign:"
+ "fontWithDescriptor:size:"
+ "geo-alert-internal"
+ "geo-alert-watch-internal"
+ "metricsForTextStyle:"
+ "new"
+ "preferredFontForTextStyle:"
+ "queryItemWithName:value:"
+ "scaledValueForValue:"
+ "setAdjustsFontForContentSizeCategory:"
+ "setHost:"
+ "setQueryItems:"
+ "setScheme:"
+ "tap-to-radar"
+ "yyyy.MM.dd_HH-mm-ss"
- "User tapped alert, showing additional details"
- "font"
- "pointSize"
```
