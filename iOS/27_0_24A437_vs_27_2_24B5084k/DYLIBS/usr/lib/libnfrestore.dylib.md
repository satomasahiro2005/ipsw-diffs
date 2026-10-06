## libnfrestore.dylib

> `/usr/lib/libnfrestore.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10cd0` | `0x10e64` | **`+0x194`** |
| `__TEXT.__oslogstring` | `0x20bf` | `0x217e` | **`+0xbf`** |
| `__TEXT.__cstring` | `0x2db2` | `0x2e61` | **`+0xaf`** |

### Other Changes

```diff

-370.42.1.0.0
+371.7.0.0.0

-  CStrings:  632
+  CStrings:  636
Functions:
~ sub_2c2ad4f60 -> sub_2c92bbf60 : 2112 -> 2516
CStrings:
+ "%s:%i Customer factory page is already locked with debug content. Nothing to do."
+ "%s:%i Customer factory page is locked without production content ! Skipping for older devices"
+ "%{public}s:%i Customer factory page is already locked with debug content. Nothing to do."
+ "%{public}s:%i Customer factory page is locked without production content ! Skipping for older devices"
+ "SN450V_FW_B0_02_01_015_rev48936220.bin"
+ "SN450V_FW_B1_03_01_815_rev49087064.bin"
- "SN450V_FW_B0_02_01_014_rev46800544.bin"
- "SN450V_FW_B1_03_01_814_rev46829584.bin"
```
