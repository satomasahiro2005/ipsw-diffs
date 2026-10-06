## SiriAppResolution

> `/System/Library/PrivateFrameworks/SiriAppResolution.framework/SiriAppResolution`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c3f4` | `0x1d584` | **`+0x1190`** |
| `__AUTH_CONST.__const` | `0x1638` | `0x1870` | **`+0x238`** |
| `__TEXT.__const` | `0x1170` | `0x12e0` | **`+0x170`** |
| `__DATA.__bss` | `0xa90` | `0xb90` | **`+0x100`** |
| `__TEXT.__oslogstring` | `0xc8e` | `0xd8e` | **`+0x100`** |
| `__TEXT.__constg_swiftt` | `0x938` | `0x9d0` | **`+0x98`** |
| `__TEXT.__swift5_fieldmd` | `0x574` | `0x5f4` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x786` | `0x7e8` | **`+0x62`** |
| `__AUTH_CONST.__auth_got` | `0x698` | `0x6e0` | **`+0x48`** |
| `__DATA.__data` | `0x410` | `0x450` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x436` | `0x464` | **`+0x2e`** |
| `__AUTH_CONST.__objc_const` | `0x6e8` | `0x708` | **`+0x20`** |
| `__TEXT.__cstring` | `0x763` | `0x783` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x830` | `0x850` | **`+0x20`** |
| `__AUTH.__data` | `0x338` | `0x348` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x120` | `0x130` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xd8` | `0xe8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xa0` | `0xb0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__swift5_protos` | `0x28` | `0x2c` | **`+0x4`** |

### Other Changes

```diff

-3600.28.13.0.0
+3605.14.1.0.0
+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Functions: 745
-  Symbols:   377
-  CStrings:  101
+  Functions: 779
+  Symbols:   393
+  CStrings:  103
Symbols:
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterRemoveObserver
+ _LSSystemApplicationType
+ _OBJC_CLASS_$_LSApplicationProxy
+ _OBJC_CLASS_$_NSArray
+ _OBJC_CLASS_$_NSExtension
+ ___swift_closure_destructor.67Tm
+ _associated conformance 17SiriAppResolution0aB20AuthorizationVerdictOSHAASQ
+ _dispatch_semaphore_create
+ _objc_release_x26
+ _swift_dynamicCastObjCClass
+ _symbolic $s17SiriAppResolution0A20AuthorizationReadingP
+ _symbolic So21OS_dispatch_semaphoreC
+ _symbolic _____ 17SiriAppResolution04StubA19AuthorizationReaderV
+ _symbolic _____ 17SiriAppResolution07IntentsA19AuthorizationReaderV
+ _symbolic _____ 17SiriAppResolution08ExcludedB8DecisionO
+ _symbolic _____ 17SiriAppResolution0aB20AuthorizationVerdictO
- ___swift_closure_destructor.41Tm
- _symbolic _____XMT 17SiriAppResolution08LSPluginA22KitExtensionMembershipC
CStrings:
+ "Only candidate %s needs Siri authorization; resolving to it so the guard can prompt"
+ "SiriKitExtensionMembership: _intents_findSiriEntitledAppsContainingAnIntentsExtension failed: %s"
+ "SiriKitExtensionMembership: discovered %ld Use-with-Siri toggle app(s)"
+ "TCCDirectSiriAppAccessReader: kTCCServiceSiriAccess deny-list invalidated; will refetch on next query"
+ "com.apple.TCC.kTCCServiceSiriAccess.authorization.changed"
- "SiriKitExtensionMembership: discovered %ld SiriKit host bundle(s)"
- "SiriKitExtensionMembership: plugin enumeration error: %s"
- "com.apple.intents-service"
```
