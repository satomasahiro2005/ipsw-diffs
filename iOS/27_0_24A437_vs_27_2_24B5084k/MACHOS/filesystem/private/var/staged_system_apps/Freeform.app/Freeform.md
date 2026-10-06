## Freeform

> `/private/var/staged_system_apps/Freeform.app/Freeform`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__unwind_info` | `0x443d8` | `0x43e78` | **`-0x560`** |
| `__TEXT.__text` | `0x1465f2c` | `0x14662e8` | **`+0x3bc`** |
| `__DATA_CONST.__const` | `0x817b8` | `0x819c0` | **`+0x208`** |
| `__TEXT.__swift5_capture` | `0x11d50` | `0x11e20` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0x6c500` | `0x6c5a0` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0xc91f9` | `0xc9259` | **`+0x60`** |
| `__TEXT.__eh_frame` | `0x5813c` | `0x58194` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x57098` | `0x570e0` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x1b494` | `0x1b4cc` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x241d5` | `0x24205` | **`+0x30`** |
| `__DATA.__objc_const` | `0x9c660` | `0x9c680` | **`+0x20`** |
| `__TEXT.__cstring` | `0xc6935` | `0xc6955` | **`+0x20`** |
| `__DATA.__objc_data` | `0x4d468` | `0x4d480` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x25458` | `0x25470` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x387e8` | `0x38800` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x20770` | `0x20788` | **`+0x18`** |
| `__TEXT.__const` | `0x79b84` | `0x79b74` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x24f10` | `0x24f20` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_ivar`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-656.2.1.0.0
+656.40.5.0.0

-  - /System/Library/PrivateFrameworks/CoreUI.framework/CoreUI

-  Functions: 91619
-  Symbols:   7834
-  CStrings:  48751
+  Functions: 91636
+  Symbols:   7833
+  CStrings:  48755
Symbols:
+ _$s10AppIntents14SyncableEntityMp
+ _$s10AppIntents14SyncableEntityPAA0aD0Tb
- _$s10AppIntents15_SyncableEntityMp
- _$s10AppIntents15_SyncableEntityPAA0aD0Tb
- _OBJC_CLASS_$_CUICatalog
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/include/usd/pxr/base/tf/refPtr.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/include/usd/pxr/base/tf/weakPtrFacade.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/local/include/usd/pxr/usd/usd/object.h"
+ "Found an existing folder."
+ "^{CGColor=}24@0:8^{CGColor=}16"
+ "adaptedColorFor:canvasBackground:"
+ "invertColor:"
+ "newInvertedColorForColor:"
+ "p_dismissMiniFormatterForLassoSelection"
+ "profileConnectionDidReceiveAllowCloudSyncChangedNotification:userInfo:"
+ "setWantsVisibleKeyboardForWritingTools:"
+ "updateHUDLayoutForGeometryChange"
+ "writingToolsAreActive"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/usd/pxr/base/tf/refPtr.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/usd/pxr/base/tf/weakPtrFacade.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/usd/pxr/usd/usd/object.h"
- "^{CGColor=}28@0:8^{CGColor=}16B24"
- "adaptedColorFor:darker:"
- "adaptedModelColorFor:canvasBackground:"
- "adaptedRenderingColorFor:canvasBackground:"
- "newColorByAdjustingLightnessOfColor:darker:"
- "p_dismissMiniFormatterForLassoSelectionForRep:"
```
