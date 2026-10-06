## iapd

> `/System/Library/PrivateFrameworks/IAP.framework/Support/iapd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xed658` | `0xed820` | **`+0x1c8`** |
| `__DATA_CONST.__const` | `0x8930` | `0x8958` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x2190` | `0x21b0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x14ca4` | `0x14cbe` | **`+0x1a`** |
| `__TEXT.__unwind_info` | `0x4d68` | `0x4d80` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0x7d7c` | `0x7d90` | **`+0x14`** |
| `__DATA_CONST.__auth_got` | `0x10e0` | `0x10f0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2185.0.0.0.0
+2186.0.0.0.0

-  Functions: 4274
-  Symbols:   869
+  Functions: 4278
+  Symbols:   871
Symbols:
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
CStrings:
+ "BluetoothUpdateStatus_block_invoke"
+ "PostBluetoothConnectionStatusNotificationAboutKnownDevices_block_invoke"
- "BluetoothUpdateStatus"
- "PostBluetoothConnectionStatusNotificationAboutKnownDevices"
```
