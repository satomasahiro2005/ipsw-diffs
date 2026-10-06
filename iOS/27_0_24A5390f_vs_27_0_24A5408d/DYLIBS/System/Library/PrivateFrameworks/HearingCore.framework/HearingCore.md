## HearingCore

> `/System/Library/PrivateFrameworks/HearingCore.framework/HearingCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8384` | `0x843c` | **`+0xb8`** |
| `__TEXT.__cstring` | `0xb79` | `0xbe6` | **`+0x6d`** |
| `__AUTH_CONST.__cfstring` | `0xda0` | `0xdc0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x848` | `0x860` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x1b8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x9a0` | `0x9a8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x320` | `0x328` | **`+0x8`** |

### Other Changes

```diff

-536.0.0.0.0
+539.1.0.0.0

-  Functions: 251
-  Symbols:   658
-  CStrings:  173
+  Functions: 252
+  Symbols:   663
+  CStrings:  175
Symbols:
+ +[HCUtilities processCanUseBluetooth]
+ GCC_except_table141
+ GCC_except_table147
+ GCC_except_table165
+ GCC_except_table187
+ GCC_except_table212
+ GCC_except_table224
+ GCC_except_table229
+ GCC_except_table236
+ GCC_except_table250
+ _OBJC_CLASS_$_CBManager
+ _notify_cancel
+ _xpc_bool_get_value
+ _xpc_copy_entitlement_for_self
- GCC_except_table140
- GCC_except_table146
- GCC_except_table164
- GCC_except_table186
- GCC_except_table211
- GCC_except_table223
- GCC_except_table228
- GCC_except_table235
- GCC_except_table249
Functions:
~ -[HCDatabaseManager init] : 292 -> 300
+ +[HCUtilities processCanUseBluetooth]
~ ___25-[HCDatabaseManager init]_block_invoke : 124 -> 120
~ -[HCDatabaseManager dealloc] : 112 -> 136
CStrings:
+ "NSBluetoothAlwaysUsageDescription"
+ "Protected data available; performing deferred database setup"
+ "com.apple.bluetooth.system"
- "Auth changed"
```
