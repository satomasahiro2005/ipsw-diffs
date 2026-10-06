## geoanalyticsd

> `/System/Library/PrivateFrameworks/GeoAnalytics.framework/geoanalyticsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21f50` | `0x221d8` | **`+0x288`** |
| `__DATA_CONST.__cfstring` | `0x12760` | `0x12880` | **`+0x120`** |
| `__TEXT.__cstring` | `0xdac8` | `0xdb8d` | **`+0xc5`** |
| `__TEXT.__objc_methname` | `0x304d` | `0x3075` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x3660` | `0x3680` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xf20` | `0xf28` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2075.30.6.12.12
+2075.31.6.17.9

-  CStrings:  3343
+  CStrings:  3353
Functions:
~ sub_100000fc8 : 4544 -> 4580
~ sub_100002188 -> sub_1000021ac : 1212 -> 1224
~ sub_100005738 -> sub_100005768 : 26620 -> 26716
~ sub_10000de1c -> sub_10000deac : 3224 -> 2048
~ sub_10000eab4 -> sub_10000e6ac : 1252 -> 2852
~ sub_100010a44 -> sub_100010c7c : 1212 -> 1224
~ sub_100011cfc -> sub_100011f40 : 4092 -> 4128
~ sub_1000166c4 -> sub_10001692c : 248 -> 280
CStrings:
+ "DISPLAYED_VISITED_PLACES"
+ "SEARCH_LIST_ENGAGED_VISITED_PLACES"
+ "SEARCH_LIST_SHOWN_VISITED_PLACES"
+ "SNAPSHOT"
+ "SWIPE_LEFT_SHOWCASE"
+ "SWIPE_RIGHT_SHOWCASE"
+ "TAP_ITEM_VISITED"
+ "TIMELINE"
+ "WIDGETKIT_CONTENT_REQUESTED"
+ "capturePeriodicSettingsWithMapSettings:mapUiShown:mapsFeatures:mapsUserSettings:routingSettings:widgetConfiguration:"
+ "widgetConfiguration"
- "capturePeriodicSettingsWithMapSettings:mapUiShown:mapsFeatures:mapsUserSettings:routingSettings:"
```
