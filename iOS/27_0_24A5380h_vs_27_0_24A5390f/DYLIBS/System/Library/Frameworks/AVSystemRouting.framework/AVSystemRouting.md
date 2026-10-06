## AVSystemRouting

> `/System/Library/Frameworks/AVSystemRouting.framework/AVSystemRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22c4c` | `0x22fdc` | **`+0x390`** |
| `__AUTH_CONST.__objc_const` | `0x2140` | `0x2278` | **`+0x138`** |
| `__AUTH.__data` | `0xba0` | `0xc50` | **`+0xb0`** |
| `__AUTH_CONST.__auth_got` | `0x680` | `0x710` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x9e8` | `0xa48` | **`+0x60`** |
| `__TEXT.__const` | `0x1988` | `0x19d8` | **`+0x50`** |
| `__TEXT.__cstring` | `0xc3a` | `0xc8a` | **`+0x50`** |
| `__DATA.__bss` | `0xca0` | `0xce0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0xcf0` | `0xd30` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x3ec` | `0x424` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x3b8` | `0x3e8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x9a0` | `0x9c0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x14c0` | `0x14e0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xdb4` | `0xdcc` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x766` | `0x77c` | **`+0x16`** |
| `__DATA.__data` | `0x660` | `0x670` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xac` | `0xb8` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0xa0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x7b8` | `0x7c0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x4c` | `0x54` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x635` | `0x634` | **`-0x1`** |

### Other Changes

```diff

-360.66.1.11.1
+360.70.2.0.0

-  Functions: 1067
-  Symbols:   905
-  CStrings:  133
+  Functions: 1081
+  Symbols:   927
+  CStrings:  137
Symbols:
+ -[AVSystemRoute description]
+ -[AVSystemRoute initWithCustomSystemCastingControllerImpl:protocolID:protocolType:routeSymbolName:routeDisplayName:]
+ -[AVSystemRouteEvent description]
+ GCC_except_table20
+ GCC_except_table29
+ GCC_except_table32
+ GCC_except_table36
+ GCC_except_table42
+ _FigNote_AllowInternalDefaultLogs
+ _NSStringFromClass
+ _OBJC_IVAR_$_AVSystemRoute._protocolType
+ _OBJC_IVAR_$_AVSystemRoute._routeDisplayName
+ _OBJC_IVAR_$_AVSystemRoute._routeSymbolName
+ _OUTLINED_FUNCTION_24
+ __DATA__TtC15AVSystemRoutingP33_9923179369F9DD5FC0D4384DC7CF877127_AVSystemRouteWrapperHolder
+ __IVARS__TtC15AVSystemRoutingP33_9923179369F9DD5FC0D4384DC7CF877127_AVSystemRouteWrapperHolder
+ __METACLASS_DATA__TtC15AVSystemRoutingP33_9923179369F9DD5FC0D4384DC7CF877127_AVSystemRouteWrapperHolder
+ ___swift_closure_destructor.250Tm
+ ___swift_closure_destructor.440Tm
+ ___swift_closure_destructor.469Tm
+ ___swift_closure_destructor.478Tm
+ _fig_note_initialize_category_with_default_work
+ _objc_getAssociatedObject
+ _objc_retain_x24
+ _objc_setAssociatedObject
+ _objc_sync_enter
+ _objc_sync_exit
+ _swift_dynamicCast
+ _swift_weakAssign
+ _symbolic _____ 15AVSystemRouting01_A18RouteWrapperHolder33_9923179369F9DD5FC0D4384DC7CF8771LLC
+ _symbolic _____ 15AVSystemRouting0aB12ErrorContextO
+ _symbolic _____SgXw 15AVSystemRouting0A5RouteC
+ _symbolic ypSg
- -[AVSystemRoute initWithCustomSystemCastingControllerImpl:protocolID:]
- GCC_except_table18
- GCC_except_table25
- GCC_except_table31
- GCC_except_table35
- GCC_except_table41
- _NSHelpAnchorErrorKey
- ___swift_closure_destructor.245Tm
- ___swift_closure_destructor.435Tm
- ___swift_closure_destructor.464Tm
- ___swift_closure_destructor.473Tm
CStrings:
+ "-AVCustomRoutingSystemController- %s: Called for media source: %{public}@"
+ "-AVCustomRoutingSystemController- %s: Sending event: %{public}@"
+ "<%@ %p reason=%@ route=%@>"
+ "<%@ %p routeDisplayName=%@>"
+ "Fallback title when the failing routing extension's display name is unavailable"
+ "Title shown when the connection to the remote application could not be established; the placeholder is the routing extension's display name"
+ "Unable to Connect"
+ "Unable to Connect with \""
+ "You can try again later."
+ "avcustomrouting_trace"
+ "com.apple.avrouting"
+ "com.apple.coremedia"
+ "q"
- "-AVCustomRoutingSystemController- %s: Called for media source: %{private}@"
- "-AVCustomRoutingSystemController- %s: Sending %{public}@ event."
- "Check network settings and try again."
- "Connection Failed"
- "Explanation of why the connection to the remote application failed"
- "Help anchor for connection failure errors"
- "Title shown when the connection to the remote application could not be established"
- "connectionFailed_failureReason"
- "connectionFailed_helpAnchor"
```
