## Health

> `/private/var/staged_system_apps/Health.app/Health`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcca64` | `0xcd1b8` | **`+0x754`** |
| `__TEXT.__eh_frame` | `0x222c` | `0x230c` | **`+0xe0`** |
| `__DATA_CONST.__const` | `0x5ce8` | `0x5d60` | **`+0x78`** |
| `__TEXT.__objc_stubs` | `0x35e0` | `0x3580` | **`-0x60`** |
| `__TEXT.__oslogstring` | `0x2a6a` | `0x2a0a` | **`-0x60`** |
| `__TEXT.__swift5_capture` | `0x13f4` | `0x1438` | **`+0x44`** |
| `__TEXT.__auth_stubs` | `0x55b0` | `0x55f0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2700` | `0x2738` | **`+0x38`** |
| `__TEXT.__objc_methname` | `0x578d` | `0x575d` | **`-0x30`** |
| `__TEXT.__swift5_typeref` | `0x27c4` | `0x27e6` | **`+0x22`** |
| `__DATA.__data` | `0x5818` | `0x5838` | **`+0x20`** |
| `__DATA.__objc_const` | `0x37f8` | `0x37d8` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x2ae0` | `0x2b00` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x14d8` | `0x14f8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x547e` | `0x545e` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x13b8` | `0x13a0` | **`-0x18`** |
| `__TEXT.__const` | `0x58c4` | `0x58b4` | **`-0x10`** |
| `__TEXT.__swift_as_cont` | `0xac` | `0xbc` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1bf0` | `0x1be4` | **`-0xc`** |
| `__DATA.__objc_data` | `0x2250` | `0x2248` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x44` | `0x48` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x38` | `0x3c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-7027.0.64.0.0
+7027.0.67.2.1

-  Functions: 3649
-  Symbols:   2402
-  CStrings:  1696
+  Functions: 3661
+  Symbols:   2408
+  CStrings:  1690
Symbols:
+ _$sScI4next7ElementQzSgyYaKFTj
+ _$sScI4next7ElementQzSgyYaKFTjTu
+ _$sSo20NSNotificationCenterC10FoundationE13NotificationsC17makeAsyncIteratorAE0G0VyF
+ _$sSo20NSNotificationCenterC10FoundationE13NotificationsC8IteratorVMa
+ _$sSo20NSNotificationCenterC10FoundationE13NotificationsC8IteratorVScIACMc
+ _$sSo20NSNotificationCenterC10FoundationE13notifications5named6objectAbCE13NotificationsCSo0A4Namea_yXlSgtF
+ _UISceneDidActivateNotification
+ _swift_willThrowTypedImpl
- _$s7SwiftUI9CalistogaV9isEnabledSbvgZ
- _OBJC_CLASS_$_UISearchTab
CStrings:
+ "HABrowseShortcutTitle"
+ "browseTabGroup"
+ "setIsSidebarDestination:"
- "HASearchShortcutTitle"
- "[%s] searchTabGroup selected from searchTab, custom logic to ignore and reselect searchTab"
- "initWithViewControllerProvider:"
- "searchTab"
- "searchTabGroup"
- "setImage:"
- "setTag:"
- "square.grid.2x2.fill"
- "systemImage"
```
