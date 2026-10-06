## MapsIntents

> `/System/Library/ExtensionKit/Extensions/MapsIntents.appex/MapsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59f38` | `0x5cec4` | **`+0x2f8c`** |
| `__TEXT.__oslogstring` | `0x1b39` | `0x1d2a` | **`+0x1f1`** |
| `__TEXT.__cstring` | `0x1dc5` | `0x1f25` | **`+0x160`** |
| `__DATA.__data` | `0x1ef8` | `0x1fe8` | **`+0xf0`** |
| `__TEXT.__const` | `0x50f4` | `0x51e4` | **`+0xf0`** |
| `__TEXT.__swift5_typeref` | `0x38a0` | `0x37b2` | **`-0xee`** |
| `__DATA_CONST.__cfstring` | `0x200` | `0x2c0` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x1440` | `0x1500` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x1de0` | `0x1e88` | **`+0xa8`** |
| `__TEXT.__objc_methname` | `0x4bf4` | `0x4c97` | **`+0xa3`** |
| `__TEXT.__swift5_fieldmd` | `0xb5c` | `0xbe8` | **`+0x8c`** |
| `__DATA.__bss` | `0x85c0` | `0x8640` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x1dd0` | `0x1e50` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x710` | `0x784` | **`+0x74`** |
| `__TEXT.__swift5_reflstr` | `0x129e` | `0x1312` | **`+0x74`** |
| `__TEXT.__unwind_info` | `0x15d8` | `0x1630` | **`+0x58`** |
| `__DATA_CONST.__auth_got` | `0xef8` | `0xf38` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x628` | `0x668` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xe38` | `0xe68` | **`+0x30`** |
| `__DATA_CONST.__objc_arraydata` | `0x88` | `0xb8` | **`+0x30`** |
| `__DATA_CONST.__objc_intobj` | `0x7b0` | `0x780` | **`-0x30`** |
| `__DATA_CONST.__objc_dictobj` | `—` | `0x28` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0xa60` | `0xa80` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0xc0` | `0xe0` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x808` | `0x820` | **`+0x18`** |
| `__DATA_CONST.__objc_doubleobj` | `0x3a0` | `0x3b0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xa0` | `0xa8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x428` | `0x42c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2972.30.6.12.58
+2972.31.6.17.21

-  Functions: 1555
-  Symbols:   278
-  CStrings:  1287
+  Functions: 1586
+  Symbols:   283
+  CStrings:  1305
Symbols:
+ _MapsFeature_IsEnabled_DrivingMultiWaypointRoutes
+ _MapsFeature_IsEnabled_Maps182
+ _MapsFeature_IsEnabled_Maps420
+ _OBJC_CLASS_$_NSConstantDictionary
+ _swift_release_n
+ _swift_retain_x28
- _objc_retain_x25
CStrings:
+ "CalculateETAIntent: Created directions URL - %s"
+ "CalculateETAIntent: Created map item URL - %s"
+ "CalculateETAIntent: Expected simultaneous light/dark snapshot but imageAsset was nil — falling back to a single appearance."
+ "CalculateETAIntent: Resolving map image set from snapshot image."
+ "CalculateETAIntent: Snippet layout forces dark scheme — returning dark snapshot only."
+ "Carry"
+ "Presubmission"
+ "Updating your route isn't supported for this type of navigation."
+ "_setAllowsSimultaneousLightDarkSnapshots:"
+ "expectedTimeOfDeparture"
+ "generateGeodesicDistanceImageSet(from:to:layout:)"
+ "generateMapImageSet(for:layout:)"
+ "https://apps.mzstatic.com/content/3e22681091624b6eaf72730309a89491/maps.jetpack"
+ "https://apps.mzstatic.com/content/cdcbf37fc6874dbf9112a58d7d53ce28/maps.jetpack"
+ "https://apps.mzstatic.com/content/e2206ce7479244289fdbee6d39042dd9/maps.jetpack"
+ "iOS Production"
+ "imageAsset"
+ "imageWithTraitCollection:"
+ "resolveTransportationType: idealTTF resolved .any → %s, but it lacks multi-waypoint support for %ld waypoints — upgrading to .driving"
+ "unregisterImageWithTraitCollection:"
+ "urlForMapItems:options:"
- "CalculateETAIntent: Created Maps URL - %s"
- "generateGeodesicDistanceSnapshot(from:to:layout:)"
- "generateMapSnapshot(for:layout:)"
```
