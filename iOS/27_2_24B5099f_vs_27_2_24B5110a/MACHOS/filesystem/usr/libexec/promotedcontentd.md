## promotedcontentd

> `/usr/libexec/promotedcontentd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3da0c4` | `0x3da6cc` | **`+0x608`** |
| `__TEXT.__oslogstring` | `0x113ac` | `0x1153c` | **`+0x190`** |
| `__TEXT.__objc_methname` | `0x2711d` | `0x2721d` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x1a220` | `0x1a320` | **`+0x100`** |
| `__DATA.__objc_const` | `0x2b7e0` | `0x2b840` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x151f8` | `0x15258` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x9490` | `0x94d0` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0xf800` | `0xf840` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x1348` | `0x1370` | **`+0x28`** |
| `__TEXT.__cstring` | `0x15d35` | `0x15d55` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x1458` | `0x1460` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x70c8` | `0x70d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
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
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-557.2.13.0.0
+557.2.14.0.0

-  Functions: 11756
+  Functions: 11764

-  CStrings:  11682
+  CStrings:  11697
CStrings:
+ "Content for context %{public}@ with ID %{public}@ appeared on screen with no status to report."
+ "OnScreen metric with content identifier %{public}@ is collapsed while ready, but it did not finish loading while its slot was on screen. Not reporting AdLoadedTooLate. displayed: %{public}@"
+ "TB,V_becameReadyWhileOnScreen"
+ "TB,V_isOnScreen"
+ "_becameReadyWhileOnScreen"
+ "_isOnScreen"
+ "appearedOnScreen"
+ "becameReadyWhileOnScreen"
+ "b\xc1"
+ "hasBeenDisplayed"
+ "interfaceOffScreen"
+ "interfaceOnScreen"
+ "isOnScreen"
+ "setBecameReadyWhileOnScreen:"
+ "setIsOnScreen:"
+ "shouldSendAdSpaceStatusEvent: NOT sending ASE %{public}@ for content %{public}@ because the ad has already been displayed."
- "R\xc1"
```
