## SFSymbols

> `/System/Library/PrivateFrameworks/SFSymbols.framework/SFSymbols`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__objc_arraydata` | `0x7b9c0` | `0x7c460` | **`+0xaa0`** |
| `__TEXT.__cstring` | `0x579ed` | `0x581bd` | **`+0x7d0`** |
| `__AUTH_CONST.__cfstring` | `0x5b260` | `0x5ba00` | **`+0x7a0`** |
| `__AUTH_CONST.__const` | `0x4c7f8` | `0x4ce18` | **`+0x620`** |
| `__TEXT.__text` | `0x26d7c` | `0x2700c` | **`+0x290`** |
| `__TEXT.__lazy_helpers` | `—` | `0xfc` | **`+0xfc`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x30` | `0xd8` | **`+0xa8`** |
| `__AUTH_CONST.__objc_dictobj` | `0x5ca8` | `0x5cd0` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x680` | `0x6a0` | **`+0x20`** |
| `__AUTH_CONST.__lazy_load_got` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x850` | `0x868` | **`+0x18`** |
| `__DATA.__bss` | `0x2480` | `0x2490` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x170` | `0x180` | **`+0x10`** |
| `__DATA.__data` | `0x528` | `0x534` | **`+0xc`** |
| `__DATA_CONST.__const` | `0x138` | `0x140` | **`+0x8`** |

### Other Changes

```diff

-201.0.0.0.0
+204.0.0.0.0

-  Functions: 744
-  Symbols:   497
-  CStrings:  11724
+  Functions: 752
+  Symbols:   519
+  CStrings:  11786
Symbols:
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _OBJC_CLASS_$_SOSiriAvailability
+ _OBJC_CLASS_$_SOSiriAvailability$lazyGOT
+ _OBJC_CLASS_$_SOSiriAvailability$lazyGOT$loadHelper_x8
+ _SFSEnsureCachedSiriMode
+ _SFSEnsureCachedSiriMode.once
+ _SFSLogWarn
+ _SFSRefreshCachedSiriMode
+ _SFSSiriCapabilitiesDidChange
+ _SOFetchSiriAvailability
+ _SOFetchSiriAvailability$lazyAuthGOT_IA_0
+ _SOFetchSiriAvailability$lazyAuthGOT_IA_0$loadHelper_x8
+ _SOFetchSiriAvailability$lazyAuthGOT_IA_ad_0
+ _SOFetchSiriAvailability$lazyLoadStub
+ ___SFSEnsureCachedSiriMode_block_invoke
+ __cachedSiriMode
+ __dyld_lazy_load
+ __os_log_impl
+ _kCoreGlyphsNameToRuntimeName
+ _lazyLoadFlag$SiriAvailability
+ _resolveRuntimeNameIfNeeded
CStrings:
+ "Failed to fetch siri availability"
+ "app.grid.2x2"
+ "app.grid.2x2.bottom.dashed"
+ "app.grid.2x2.bottom.dashed.fill"
+ "app.grid.2x2.topleading.dashed"
+ "app.grid.2x2.topleading.dashed.fill"
+ "app.grid.2x2.topleading.filled"
+ "apple.keynote.gen1"
+ "apple.keynote.gen2"
+ "apple.numbers.gen1"
+ "apple.numbers.gen2"
+ "apple.pages.gen1"
+ "apple.pages.gen2"
+ "apple.visual.intelligence.gen1"
+ "apple.visual.intelligence.gen2"
+ "apps.list.watchos"
+ "arrow.uturn.down.backward"
+ "arrow.uturn.down.forward"
+ "arrow.uturn.down.left"
+ "arrow.uturn.down.right"
+ "checkmark.circle.stack.horizontal"
+ "checkmark.circle.stack.horizontal.fill"
+ "circle.on.app.liquid.glass"
+ "circle.on.app.liquid.glass.fill"
+ "com.apple.siri.orchestration.capabilities.didChange"
+ "creditcard.badge.plus"
+ "creditcard.badge.plus.fill"
+ "cube.badge.paintbrush"
+ "cube.badge.paintbrush.fill"
+ "cube.plane.bottom.right.detached"
+ "cube.plane.bottom.right.detached.fill"
+ "eyedropper.and.sparkles"
+ "fuelpump.nozzle.and.drop"
+ "gauge.range.33to100.dotted.with.needle"
+ "info.circle.badge"
+ "info.circle.badge.fill"
+ "lock.video"
+ "lock.video.fill"
+ "menopause"
+ "motor.electric.vehicle"
+ "perimenopause"
+ "person.wave.2.inward"
+ "person.wave.2.inward.fill"
+ "photo.rectangle.dashed"
+ "play.rectangle.summary"
+ "rectangle.3.portrait.pano"
+ "rectangle.3.portrait.pano.fill"
+ "shoe.running.and.shadow.fill"
+ "siri.rectangle.dashed"
+ "square.grid.month"
+ "suspension.shock.and.exhaust.mode"
+ "text.short.and.text.long"
+ "trackpad"
+ "trackpad.fill"
+ "video.badge.shield.exclamationmark"
+ "video.badge.shield.exclamationmark.fill"
+ "viewfinder.and.person"
+ "waveform.house"
+ "waveform.house.fill"
+ "widget.small.badge.exclamationmark"
+ "wifi.classic"
+ "xmark.circle.stack.horizontal"
+ "xmark.circle.stack.horizontal.fill"
- "wifi.rounded.slash"
```
