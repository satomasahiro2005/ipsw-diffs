## locationd

> `/usr/libexec/locationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b31500` | `0x1b31fd0` | **`+0xad0`** |
| `__TEXT.__cstring` | `0x21129e` | `0x2115ae` | **`+0x310`** |
| `__DATA_CONST.__cfstring` | `0x444e0` | `0x44760` | **`+0x280`** |
| `__TEXT.__oslogstring` | `0x29356c` | `0x29376c` | **`+0x200`** |
| `__DATA_CONST.__objc_arraydata` | `0x1bb0` | `0x1c68` | **`+0xb8`** |
| `__DATA_CONST.__objc_arrayobj` | `0x978` | `0x9d8` | **`+0x60`** |
| `__TEXT.__const` | `0x166968` | `0x1669b8` | **`+0x50`** |
| `__DATA.__bss` | `0x12fa8` | `0x12fe8` | **`+0x40`** |
| `__DATA_CONST.__const` | `0xc1d38` | `0xc1d58` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3e8a0` | `0x3e8c0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x77b68` | `0x77b78` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xdaafc` | `0xdaaf0` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x25e8` | `0x25f0` | **`+0x8`** |
| `__TEXT.__init_offsets` | `0xc08` | `0xc0c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3186.0.21.0.0
+3186.0.22.0.0

-  Functions: 114233
-  Symbols:   2919
-  CStrings:  85403
+  Functions: 114244
+  Symbols:   2920
+  CStrings:  85429
Symbols:
+ _OBJC_CLASS_$_CLLocationCoordinate
CStrings:
+ "#Pinning Location unchanged (within range) and already authorized"
+ "#Pinning New Location has been preauthorized"
+ "#Pinning New Location received"
+ "#Pinning New location while already prompting for authorization."
+ "#Pinning Received a zero location!"
+ "#Pinning Received location is invalid. Let's have it dropped by next layers"
+ "/AppleInternal/Library/Frameworks/CoreAutomationDevice.framework"
+ "/AppleInternal/Library/LocationBundles/FenceTester.bundle"
+ "/AppleInternal/Library/LocationBundles/LocationMonitor.bundle"
+ "/System/Library/LocationBundles/SystemCustomization.bundle"
+ "/System/Library/LocationBundles/TimeZone.bundle"
+ "/System/Library/LocationBundles/WebBrowsingServices.bundle"
+ "/System/Library/PrivateFrameworks/HomeKitDaemon.framework"
+ "/System/Library/PrivateFrameworks/MobileWiFi.framework"
+ "01:48:49"
+ "02:00:00"
+ "HomeAccessory"
+ "Oct 10 2026"
+ "Oct 10 2026 01:54:15"
+ "com.apple.CalendarPebble"
+ "com.apple.Home"
+ "com.apple.Home.HomeWidgetTV"
+ "com.apple.MapKitTester"
+ "com.apple.PebbleSettingsApp"
+ "com.apple.WatchFacesWallpaperSupport.SnoopyPoster"
+ "com.apple.mobilesafari"
+ "com.apple.mobiletimer.WorldClocks"
+ "com.apple.reminders"
+ "com.apple.weather.nonPersonal"
+ "com.apple.weather.widget"
+ "{\"msg%{public}.0s\":\"#Pinning location changed, prompting for authorization\", \"previousLocation\":%{public, location:Encrypted_CLLocationCoordinate2D}.*P, \"newLocation\":%{public, location:Encrypted_CLLocationCoordinate2D}.*P}"
- "#Pinning Unsupported"
- "23:22:01"
- "23:32:40"
- "Sep 28 2026"
- "Sep 28 2026 23:27:21"
```
