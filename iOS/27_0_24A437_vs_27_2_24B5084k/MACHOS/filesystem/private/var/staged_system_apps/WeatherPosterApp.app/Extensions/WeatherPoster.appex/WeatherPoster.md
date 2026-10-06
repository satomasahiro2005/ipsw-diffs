## WeatherPoster

> `/private/var/staged_system_apps/WeatherPosterApp.app/Extensions/WeatherPoster.appex/WeatherPoster`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ebdc` | `0x4fc34` | **`+0x1058`** |
| `__TEXT.__oslogstring` | `0x2ff5` | `0x30f5` | **`+0x100`** |
| `__DATA_CONST.__const` | `0x31f0` | `0x3240` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x13d7` | `0x1397` | **`-0x40`** |
| `__TEXT.__objc_stubs` | `0x17c0` | `0x1800` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0xcbc` | `0xce4` | **`+0x28`** |
| `__DATA.__objc_const` | `0x28b0` | `0x2890` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0xdd1` | `0xdb1` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1118` | `0x1138` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xcd8` | `0xcf0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xe60` | `0xe78` | **`+0x18`** |
| `__DATA.__data` | `0x21d8` | `0x21c8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x568` | `0x578` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2250` | `0x2260` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x3ded` | `0x3dfd` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xedc` | `0xed0` | **`-0xc`** |
| `__DATA_CONST.__auth_got` | `0x1130` | `0x1138` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x106c` | `0x1074` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1454.1.0.0.0
+1470.0.0.0.0

-  Functions: 1895
-  Symbols:   304
-  CStrings:  987
+  Functions: 1904
+  Symbols:   306
+  CStrings:  990
Symbols:
+ _NSRunLoopCommonModes
+ _OBJC_CLASS_$_CADisplayLink
+ _OBJC_CLASS_$_NSRunLoop
- _OBJC_CLASS_$_UIUpdateLink
CStrings:
+ "Rotation animation did not finish within %{public}fs; completing it without further display link updates; toOrientation=%{public}s"
+ "Updating orientation change without animating because no display link was available; newOrientation=%{public}s"
+ "addToRunLoop:forMode:"
+ "currentRunLoop"
+ "delay"
+ "displayLink"
+ "displayLinkFired:"
+ "displayLinkWithTarget:selector:"
+ "duration"
+ "rotationDisplayLinkProvider"
+ "setPreferredFramesPerSecond:"
- "addActionWithHandler:"
- "isManagerRendering"
- "rotationUpdateLinkProvider"
- "setEnabled:"
- "setPreferredFrameRateRange:"
- "updateLink"
- "updateLinkForView:"
- "v24@?0@\"UIUpdateLink\"8@\"UIUpdateInfo\"16"
```
