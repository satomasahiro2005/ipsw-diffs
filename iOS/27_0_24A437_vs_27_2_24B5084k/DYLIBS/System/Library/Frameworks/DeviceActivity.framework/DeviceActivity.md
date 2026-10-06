## DeviceActivity

> `/System/Library/Frameworks/DeviceActivity.framework/DeviceActivity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x95478` | `0x97310` | **`+0x1e98`** |
| `__AUTH_CONST.__const` | `0x3020` | `0x32c0` | **`+0x2a0`** |
| `__DATA.__bss` | `0x4100` | `0x4380` | **`+0x280`** |
| `__TEXT.__const` | `0x3ac8` | `0x3c38` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x2e18` | `0x2ef8` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x14ab` | `0x157b` | **`+0xd0`** |
| `__TEXT.__swift5_capture` | `0x588` | `0x5f0` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0x1436` | `0x149c` | **`+0x66`** |
| `__DATA.__data` | `0x908` | `0x968` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x1a48` | `0x1aa0` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0xfd0` | `0x1014` | **`+0x44`** |
| `__TEXT.__constg_swiftt` | `0xe5c` | `0xe98` | **`+0x3c`** |
| `__DATA.__common` | `0x30` | `0x60` | **`+0x30`** |
| `__TEXT.__cstring` | `0xaee` | `0xb1e` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0xcd0` | `0xcf8` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x9e1` | `0xa01` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7f8` | `0x810` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x1e8` | `0x200` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x78` | `0x8c` | **`+0x14`** |
| `__TEXT.__swift5_proto` | `0x2f0` | `0x304` | **`+0x14`** |
| `__DATA_CONST.__const` | `0x100` | `0x110` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x118` | `0x120` | **`+0x8`** |

### Other Changes

```diff

-407.0.0.0.0
+407.1.4.0.0

-  Functions: 2452
-  Symbols:   789
-  CStrings:  175
+  Functions: 2506
+  Symbols:   802
+  CStrings:  182
Symbols:
+ ___swift_closure_destructor.65Tm
+ ___swift_memcpy4_4
+ _associated conformance 14DeviceActivity12EventStreamsV5BiomeV6SourceOSHAASQ
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _symbolic SDySS_____G 14DeviceActivity12EventStreamsV5BiomeV6SourceO
+ _symbolic SS______t 14DeviceActivity12EventStreamsV5BiomeV6SourceO
+ _symbolic _____ 14DeviceActivity12EventStreamsV5BiomeV6SourceO
+ _symbolic _____ So16os_unfair_lock_sV
+ _symbolic _____ s6UInt32V
+ _symbolic _____ySS_____G s18_DictionaryStorageC 14DeviceActivity12EventStreamsV5BiomeV6SourceO
+ _symbolic _____ySS______tG s23_ContiguousArrayStorageC 14DeviceActivity12EventStreamsV5BiomeV6SourceO
+ _symbolic _____y_____Sg_____G s13ManagedBufferCsRi__rlE 14DeviceActivity12EventStreamsV5BiomeV6SourceO So16os_unfair_lock_sV
+ _type_layout_string So16os_unfair_lock_sV
- ___swift_closure_destructor.244Tm
CStrings:
+ "BiomeSource.plist"
+ "Failed to read the Biome source: %{public}s"
+ "Failed to write the Biome source %{public}s: %{public}s"
+ "Set the Biome source to %{public}s"
+ "The Biome source is missing from %{public}s"
+ "demo"
+ "production"
```
