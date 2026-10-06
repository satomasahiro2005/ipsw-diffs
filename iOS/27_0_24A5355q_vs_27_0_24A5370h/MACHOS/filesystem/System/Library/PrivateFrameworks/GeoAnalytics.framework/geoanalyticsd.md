## geoanalyticsd

> `/System/Library/PrivateFrameworks/GeoAnalytics.framework/geoanalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fcc8` | `0x20138` | **`+0x470`** |
| `__DATA_CONST.__cfstring` | `0x124e0` | `0x12540` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x113e` | `0x118c` | **`+0x4e`** |
| `__TEXT.__objc_stubs` | `0x3540` | `0x3580` | **`+0x40`** |
| `__TEXT.__cstring` | `0xd8c5` | `0xd8fa` | **`+0x35`** |
| `__DATA_CONST.__got` | `0x278` | `0x2a8` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x2f7a` | `0x2f8c` | **`+0x12`** |
| `__DATA.__objc_selrefs` | `0xed8` | `0xee8` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x840` | `0x850` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x430` | `0x438` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x1078` | `0x1080` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x688` | `0x680` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2069.30.5.14.4
+2073.30.6.5.1

-  Functions: 391
-  Symbols:   233
-  CStrings:  3305
+  Functions: 392
+  Symbols:   240
+  CStrings:  3312
Symbols:
+ _GeoAnalyticsConfig_LastMetroAssetCatalogDownload
+ _GeoAnalyticsConfig_MetroAssetCatalogCheckInterval
+ _GeoAnalyticsConfig__debug_CancelInflightUploads
+ _GeoAnalyticsConfig__debug_NoMobileAssetPreloader
+ _GeoAnalyticsConfig__debug_NoUploader
+ _sqlite3_mprintf
+ _sqlite3_temp_directory
CStrings:
+ "FINDER_DENSITY"
+ "GEOAPUploader is administratively disabled"
+ "REORDER_ADD_STOP"
+ "TAP_ENRICHMENT_MARK"
+ "UTF8String"
+ "administratively canceling task %@"
+ "vacuum"
```
