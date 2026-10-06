## ChronoKit

> `/System/Library/PrivateFrameworks/ChronoKit.framework/ChronoKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18fdcc` | `0x193a10` | **`+0x3c44`** |
| `__AUTH_CONST.__const` | `0x8550` | `0x8728` | **`+0x1d8`** |
| `__AUTH_CONST.__objc_const` | `0x8e20` | `0x8fc8` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0x4c53` | `0x4da3` | **`+0x150`** |
| `__TEXT.__swift5_reflstr` | `0x43ec` | `0x44ff` | **`+0x113`** |
| `__TEXT.__const` | `0xe3b8` | `0xe4b0` | **`+0xf8`** |
| `__DATA.__data` | `0x1010` | `0x1100` | **`+0xf0`** |
| `__TEXT.__eh_frame` | `0x6758` | `0x6840` | **`+0xe8`** |
| `__TEXT.__unwind_info` | `0x5070` | `0x5120` | **`+0xb0`** |
| `__TEXT.__swift5_fieldmd` | `0x453c` | `0x45e8` | **`+0xac`** |
| `__TEXT.__constg_swiftt` | `0x8080` | `0x8108` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x5400` | `0x5468` | **`+0x68`** |
| `__AUTH.__objc_data` | `0x280` | `0x2d0` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0xd34` | `0xd84` | **`+0x50`** |
| `__TEXT.__cstring` | `0x4913` | `0x4953` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1f28` | `0x1f58` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x6c8` | `0x6f8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xed8` | `0xef0` | **`+0x18`** |
| `__DATA.__bss` | `0x6dd0` | `0x6de0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x8b8` | `0x8c8` | **`+0x10`** |
| `__DATA.__common` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4b8` | `0x4bc` | **`+0x4`** |

### Other Changes

```diff

-749.0.2.0.0
+749.2.4.0.0

-  Functions: 7889
-  Symbols:   2383
-  CStrings:  876
+  Functions: 7947
+  Symbols:   2392
+  CStrings:  880
Symbols:
+ _OBJC_CLASS_$__TtC9ChronoKit30ApplicationAvailabilityMonitor
+ _OBJC_METACLASS_$__TtC9ChronoKit30ApplicationAvailabilityMonitor
+ __DATA__TtC9ChronoKit30ApplicationAvailabilityMonitor
+ __IVARS__TtC9ChronoKit13SmallLRUCache
+ __IVARS__TtC9ChronoKit30ApplicationAvailabilityMonitor
+ __METACLASS_DATA__TtC9ChronoKit30ApplicationAvailabilityMonitor
+ __OBJC_$_INSTANCE_METHODS__TtC9ChronoKit30ApplicationAvailabilityMonitor(ChronoKit)
+ __OBJC_CLASS_PROTOCOLS_$__TtC9ChronoKit30ApplicationAvailabilityMonitor(ChronoKit)
+ _symbolic $s9ChronoKit31ApplicationAvailabilityObserverP
+ _symbolic $s9ChronoKit33ApplicationAvailabilityMonitoringP
+ _symbolic SDyxq_G
+ _symbolic Shy_____y_____GGyc 14ChronoServices15TypedIdentifierV AA0D4TypeO6BundleO9ContainerO
+ _symbolic _____ 9ChronoKit13SmallLRUCacheC
+ _symbolic _____ 9ChronoKit30ApplicationAvailabilityMonitorC
+ _symbolic _____Sg 8Dispatch0A4TimeV
+ _symbolic _____Sg 8Dispatch0A8WorkItemC
+ _symbolic _____SgXw 9ChronoKit30ApplicationAvailabilityMonitorC
+ _symbolic _____Sg______t 8Dispatch0A8WorkItemC AA0A4TimeV
+ _symbolic _____XMT 9ChronoKit30ApplicationAvailabilityMonitorC
- _OBJC_CLASS_$__TtC9ChronoKit25ApplicationRemovalMonitor
- _OBJC_METACLASS_$__TtC9ChronoKit25ApplicationRemovalMonitor
- __DATA__TtC9ChronoKit25ApplicationRemovalMonitor
- __IVARS__TtC9ChronoKit25ApplicationRemovalMonitor
- __METACLASS_DATA__TtC9ChronoKit25ApplicationRemovalMonitor
- __OBJC_$_INSTANCE_METHODS__TtC9ChronoKit25ApplicationRemovalMonitor(ChronoKit)
- __OBJC_CLASS_PROTOCOLS_$__TtC9ChronoKit25ApplicationRemovalMonitor(ChronoKit)
- _symbolic $s9ChronoKit26ApplicationRemovalObserverP
- _symbolic $s9ChronoKit28ApplicationRemovalMonitoringP
- _symbolic _____ 9ChronoKit25ApplicationRemovalMonitorC
CStrings:
+ "ApplicationAvailabilityMonitor: Starting observation"
+ "ApplicationAvailabilityMonitor: app installs cancelled"
+ "ApplicationAvailabilityMonitor: app installs started"
+ "ApplicationAvailabilityMonitor: applications uninstalled"
+ "ApplicationAvailabilityMonitor: awaiting install %{public}ld - added %{public}s, removed %{public}s"
+ "ApplicationAvailabilityMonitor: ignored %{public}ld of %{public}ld uninstalled proxies - not an LSApplicationProxy, or no bundle identifier"
+ "ApplicationAvailabilityMonitor: invalidating"
+ "com.apple.chronod.application-availability-refresh"
- "ApplicationRemovalMonitor: Starting observation"
- "ApplicationRemovalMonitor: app installs cancelled"
- "ApplicationRemovalMonitor: applications uninstalled"
- "ApplicationRemovalMonitor: invalidating"
```
