## carkitd

> `/usr/libexec/carkitd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x7200` | `0x8000` | **`+0xe00`** |
| `__DATA_CONST.__objc_arraydata` | `0x910` | `0xdf0` | **`+0x4e0`** |
| `__TEXT.__text` | `0x94894` | `0x94cfc` | **`+0x468`** |
| `__TEXT.__cstring` | `0x63f2` | `0x67d2` | **`+0x3e0`** |
| `__TEXT.__oslogstring` | `0x11411` | `0x114d1` | **`+0xc0`** |
| `__TEXT.__objc_methname` | `0x18a14` | `0x18a74` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x1920` | `0x1960` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x115c0` | `0x11600` | **`+0x40`** |
| `__DATA.__objc_const` | `0x147d0` | `0x147f8` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x7b7c` | `0x7b9c` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x5090` | `0x50a0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-794.0.0.0.0
+797.0.0.0.0

-  Functions: 3425
+  Functions: 3427

-  CStrings:  6699
+  CStrings:  6817
CStrings:
+ "44C9FA31EC"
+ "4800702"
+ "4800703"
+ "4800704"
+ "4800705"
+ "4900000"
+ "5073"
+ "50730"
+ "507300"
+ "5074"
+ "50740"
+ "507400"
+ "5075"
+ "50750"
+ "507500"
+ "5076"
+ "50760"
+ "507600"
+ "50761"
+ "507610"
+ "5076100"
+ "5077"
+ "50770"
+ "507700"
+ "5078"
+ "50780"
+ "507800"
+ "5080"
+ "50800"
+ "508000"
+ "5090"
+ "50900"
+ "509000"
+ "50901"
+ "509010"
+ "5090100"
+ "5091"
+ "50910"
+ "509100"
+ "5091000"
+ "50911"
+ "509110"
+ "5091100"
+ "50912"
+ "509120"
+ "5091200"
+ "50913"
+ "509130"
+ "5091300"
+ "50914"
+ "509140"
+ "5091400"
+ "50915"
+ "509150"
+ "5091500"
+ "5092"
+ "50920"
+ "509200"
+ "5093"
+ "50930"
+ "509300"
+ "5094"
+ "50940"
+ "509400"
+ "5095"
+ "50950"
+ "509500"
+ "5097"
+ "50970"
+ "509700"
+ "5099"
+ "50990"
+ "509900"
+ "5100"
+ "51000"
+ "510000"
+ "51001"
+ "510010"
+ "5100100"
+ "CarPlay_ThemeAssetIdentifier"
+ "Drop 10"
+ "Drop 10 (Pre-release)"
+ "Drop 7.3"
+ "Drop 7.4"
+ "Drop 7.4 + Update 1"
+ "Drop 7.4 + Update 1 and 2"
+ "Drop 7.4 + Update 1 and AirPlay vulnerabilities patch"
+ "Drop 7.5"
+ "Drop 7.6"
+ "Drop 8"
+ "Drop 9"
+ "Drop 9.0.1"
+ "Drop 9.1"
+ "Drop 9.10"
+ "Drop 9.11"
+ "Drop 9.12"
+ "Drop 9.13"
+ "Drop 9.14"
+ "Drop 9.15"
+ "Drop 9.2"
+ "Drop 9.3"
+ "Drop 9.4"
+ "Drop 9.5 or 9.6"
+ "Drop 9.7 or 9.8"
+ "Drop 9.9"
+ "R18.1 + Update 1 and 2"
+ "R18.1 + Update 1, 2 and 3"
+ "R18.1 + Update 1, 2, 3 and 4"
+ "R18.1 + Update 1, 2, 3, 4 and 5"
+ "R19"
+ "Updating clusterAssetIdentifier to %{private}@ for %@"
+ "_deviceFeaturesForThemeAssetID:"
+ "_updateCoreAccessoriesInformationForVehicleAccessory:"
+ "deviceSupportedCarPlayFeaturesForThemeAssetID:"
+ "deviceSupportedCarPlayFeaturesForThemeAssetID: %{public}lu"
+ "deviceSupportedCarPlayFeaturesForThemeAssetID:reply:"
+ "fetched theme asset ID: %{private}@"
+ "fetching theme asset ID for endpoint: %{public}@"
+ "setThemeAssetIdentifier:"
+ "t8101"
+ "t8110"
+ "themeAssetIdentifier"
+ "vehicle declared theme asset ID: %{private}@"
- "_deviceFeatures"
- "_updateCarKeyInformationForVehicleAccessory:"
- "deviceSupportedCarPlayFeatures"
- "deviceSupportedCarPlayFeatures %{public}lu"
- "deviceSupportedCarPlayFeaturesWithReply:"
```
