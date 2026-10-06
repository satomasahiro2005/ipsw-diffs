## PairedDeviceRegistry

> `/System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26968` | `0x26aec` | **`+0x184`** |
| `__DATA_DIRTY.__data` | `0xa20` | `0xa10` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x8da` | `0x8ca` | **`-0x10`** |
| `__DATA.__data` | `0xc88` | `0xc90` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x8d0` | `0x8c8` | **`-0x8`** |

### Other Changes

```diff

-1075.1.3.0.0
+1075.1.4.0.0
CStrings:
+ "deviceGroup not set for device %s; assuming .watch"
- "Failed to decode a valid DeviceGroup from raw value. Falling back to .invalid"
```
