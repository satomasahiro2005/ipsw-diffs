## SeymourHealth

> `/System/Library/PrivateFrameworks/SeymourHealth.framework/SeymourHealth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11b00` | `0x11d34` | **`+0x234`** |
| `__TEXT.__eh_frame` | `0xd78` | `0xde0` | **`+0x68`** |
| `__AUTH_CONST.__auth_got` | `0x870` | `0x890` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2d1` | `0x2f1` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x440` | `0x450` | **`+0x10`** |

### Other Changes

```diff

-2027.0.146.1.4
+2027.1.50.0.1

-  Functions: 234
-  Symbols:   272
+  Functions: 233
+  Symbols:   273
Symbols:
+ _objc_retain_x28
+ _symbolic _____y_____G 15MessageDispatch17XPCDispatchClientC 07SeymourD10Foundation011PersistenceA4CodeO
+ _symbolic _____y______G 15MessageDispatch17XPCDispatchClientC11ServiceTypeO 07SeymourD10Foundation011PersistenceA4CodeO
- _symbolic _____y_____G 15MessageDispatch17XPCDispatchClientC 28SeymourXPCServicesFoundation011PersistenceA4CodeO
- _symbolic _____y______G 15MessageDispatch17XPCDispatchClientC11ServiceTypeO 28SeymourXPCServicesFoundation011PersistenceA4CodeO
CStrings:
+ "queryWorkoutsUsingThreshold(_:excluding:excludesFitnessPlusSessions:limit:)"
- "queryWorkoutsUsingThreshold(_:excluding:)"
```
