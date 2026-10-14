## HomeWidgetLockScreen

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeWidgetLockScreen.appex/HomeWidgetLockScreen`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65648` | `0x67b50` | **`+0x2508`** |
| `__DATA.__bss` | `0x3818` | `0x3a18` | **`+0x200`** |
| `__TEXT.__swift5_typeref` | `0x328a` | `0x33be` | **`+0x134`** |
| `__TEXT.__const` | `0x3724` | `0x3814` | **`+0xf0`** |
| `__TEXT.__auth_stubs` | `0x1fd0` | `0x20a0` | **`+0xd0`** |
| `__TEXT.__cstring` | `0x1f5f` | `0x1ebf` | **`-0xa0`** |
| `__TEXT.__eh_frame` | `0x29a4` | `0x2a14` | **`+0x70`** |
| `__DATA_CONST.__auth_got` | `0xff0` | `0x1058` | **`+0x68`** |
| `__DATA_CONST.__got` | `0x5d0` | `0x628` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x13f8` | `0x1440` | **`+0x48`** |
| `__DATA.__data` | `0x1f30` | `0x1f70` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x13c6` | `0x1406` | **`+0x40`** |
| `__TEXT.__swift5_assocty` | `0x558` | `0x588` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x10d0` | `0x10f8` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x500` | `0x520` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x210` | `0x230` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x29c` | `0x2b4` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0xae8` | `0xaf8` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x1bc` | `0x1cc` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x6a9` | `0x6b9` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1ec` | `0x1fc` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x41a` | `0x427` | **`+0xd`** |
| `__TEXT.__swift5_fieldmd` | `0x878` | `0x884` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x1d8` | `0x1e0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x178` | `0x180` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1269.2.3.0.1
+1269.2.5.1.4

+  - /System/Library/Frameworks/_AppIntents_SwiftUI.framework/_AppIntents_SwiftUI

+  - /System/Library/PrivateFrameworks/HomeAppIntents.framework/HomeAppIntents

-  Functions: 1457
+  Functions: 1476

-  CStrings:  372
+  CStrings:  370
Symbols:
+ _swift_retain_x8
- _swift_release_x27
CStrings:
+ "...{%s} got values lockState: %ld, doorState: %ld, tamperedStatus: %ld, statusString: %s, iconName %s), isSecure: %{bool}d"
+ "HFCharacteristicValueDoorStateForcedOpen"
+ "HFStatusTitleDoor_Short_MultipleForcedOpen"
+ "lock.open.trianglebadge.exclamationmark.fill"
+ "supportsCHIP"
- "...{%s} got value: %ld, statusString: %s, iconName %s)"
- "HFCharacteristicValueLockMechanismStateJammed"
- "HFCharacteristicValueLockMechanismStateSecured"
- "HFCharacteristicValueLockMechanismStateUnknown"
- "HFCharacteristicValueLockMechanismStateUnsecured"
- "lock.trianglebadge.exclamationmark"
- "lock.trianglebadge.exclamationmark.fill"
```
