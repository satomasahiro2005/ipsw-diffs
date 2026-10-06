## NanoTimeKitCompanion

> `/System/Library/AccessibilityBundles/NanoTimeKitCompanion.axbundle/NanoTimeKitCompanion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11ea8` | `0x12054` | **`+0x1ac`** |
| `__TEXT.__oslogstring` | `—` | `0xdf` | **`+0xdf`** |
| `__TEXT.__auth_stubs` | `0x640` | `0x680` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x330` | `0x350` | **`+0x20`** |
| `__TEXT.__const` | `0x48` | `0x50` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1035.0.0.0.0
+1038.0.0.0.0

-  Symbols:   1840
-  CStrings:  968
+  Symbols:   1844
+  CStrings:  970
Symbols:
+ _AXAIWhiteGloveLoggingEnabled
+ _AXLogCommon
+ __os_log_impl
+ _os_log_type_enabled
Functions:
~ -[NTKCFaceDetailSectionHeaderViewAccessibility isAccessibilityElement] : 8 -> 288
~ -[NTKCFaceDetailSectionHeaderViewAccessibility accessibilityLabel] : 148 -> 296
CStrings:
+ "rdar://166127771 NTKCFaceDetailSectionHeaderView accessibilityLabel titleLen=%lu subtitleLen=%lu labelLen=%lu"
+ "rdar://166127771 NTKCFaceDetailSectionHeaderView isAccessibilityElement titleLen=%lu subtitleLen=%lu hasLabel=%d"
```
