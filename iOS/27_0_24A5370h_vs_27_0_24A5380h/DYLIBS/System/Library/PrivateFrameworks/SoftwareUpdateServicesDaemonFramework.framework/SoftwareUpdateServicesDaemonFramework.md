## SoftwareUpdateServicesDaemonFramework

> `/System/Library/PrivateFrameworks/SoftwareUpdateServicesDaemonFramework.framework/SoftwareUpdateServicesDaemonFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xc30` | `0x190` | **`-0xaa0`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0xaa0` | **`+0xaa0`** |
| `__TEXT.__text` | `0x626e0` | `0x625b0` | **`-0x130`** |
| `__DATA.__bss` | `0xb8` | `0x38` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `—` | `0x80` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x1368` | `0x1340` | **`-0x28`** |
| `__AUTH_CONST.__objc_const` | `0x8198` | `0x81a8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x19e8` | `0x19e0` | **`-0x8`** |

### Other Changes

```diff

-1104.0.0.0.0
+1107.0.0.0.0

-  Functions: 2107
-  Symbols:   3372
+  Functions: 2106
+  Symbols:   3370
Symbols:
+ -[SUInstaller currentInstallOptions]
- -[SUDownloader networkChangedFromNetworkType:toNetworkType:]
- ___60-[SUDownloader networkChangedFromNetworkType:toNetworkType:]_block_invoke
- ___block_descriptor_44_e8_32s_e5_v8?0ls32l8
```
