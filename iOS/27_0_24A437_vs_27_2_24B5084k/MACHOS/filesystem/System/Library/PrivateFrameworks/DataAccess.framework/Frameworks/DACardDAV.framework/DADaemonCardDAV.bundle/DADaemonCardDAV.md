## DADaemonCardDAV

> `/System/Library/PrivateFrameworks/DataAccess.framework/Frameworks/DACardDAV.framework/DADaemonCardDAV.bundle/DADaemonCardDAV`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x244b4` | `0x2464c` | **`+0x198`** |
| `__TEXT.__oslogstring` | `0x374c` | `0x3857` | **`+0x10b`** |
| `__TEXT.__objc_methname` | `0x6bc4` | `0x6c46` | **`+0x82`** |
| `__TEXT.__objc_stubs` | `0x5a40` | `0x5ac0` | **`+0x80`** |
| `__TEXT.__cstring` | `0xa7e` | `0xabf` | **`+0x41`** |
| `__DATA.__objc_selrefs` | `0x1ac8` | `0x1ae8` | **`+0x20`** |
| `__TEXT.__const` | `0xf0` | `0x100` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2708.0.0.0.0
+2708.1.5.0.0

-  CStrings:  1566
+  CStrings:  1575
Functions:
~ sub_6944 : 2732 -> 3140
CStrings:
+ "Container save is sync token/ctag only; suppressing change notifications (records=%{public}d containerDirty=%{public}d)"
+ "Container save will post change notifications; reason: %{public}s (records=%{public}d tokens=%{public}d containerDirty=%{public}d flag=%{public}d)"
+ "abSaveDBSuppressingChangeNotifications"
+ "container properties changed"
+ "hasUserVisibleChanges"
+ "record changes"
+ "setSuppressChangeNotifications:"
+ "suppressSyncTokenChangeNotifications"
+ "suppression disabled"
```
