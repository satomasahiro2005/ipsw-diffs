## HSTouchHIDService

> `/System/Library/HIDPlugins/ServicePlugins/HSTouchHIDService.plugin/HSTouchHIDService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcf708` | `0xcfbcc` | **`+0x4c4`** |
| `__DATA_CONST.__cfstring` | `0x7560` | `0x7720` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0xc148` | `0xc1d9` | **`+0x91`** |
| `__DATA_CONST.__const` | `0x1db8` | `0x1e18` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0xeaa4` | `0xead0` | **`+0x2c`** |
| `__DATA_CONST.__objc_dictobj` | `0x230` | `0x258` | **`+0x28`** |
| `__DATA_CONST.__objc_intobj` | `0x6a8` | `0x6c0` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x4c4e` | `0x4c64` | **`+0x16`** |
| `__DATA_CONST.__objc_arraydata` | `0x508` | `0x518` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x48f8` | `0x4908` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-10100.40.2.0.0
+10100.44.0.0.0

-  Functions: 5284
-  Symbols:   7772
-  CStrings:  4184
+  Functions: 5287
+  Symbols:   7773
+  CStrings:  4199
Symbols:
+ ___48+[HSTouchHIDService matchService:options:score:]_block_invoke
+ ___48+[HSTouchHIDService matchService:options:score:]_block_invoke_2
+ ___block_descriptor_32_e19_"NSDictionary"8?0l
+ ___block_descriptor_36_e19_"NSDictionary"8?0l
- GCC_except_table109
- GCC_except_table75
- _OUTLINED_FUNCTION_17
CStrings:
+ "10100.44"
+ "AID"
+ "AirPlay"
+ "Audio"
+ "BT-AACP"
+ "Blocked Transport: %@"
+ "Bluetooth"
+ "BluetoothLowEnergy"
+ "FIFO"
+ "I2C"
+ "Inductive In-Band"
+ "SPI"
+ "SPU"
+ "Serial"
+ "com.apple.MultitouchSupport.TransportMatching"
+ "iAP"
- "10100.40.2"
```
