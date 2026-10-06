## CoreAIDelegates

> `/System/Library/SubFrameworks/CoreAIDelegates.framework/CoreAIDelegates`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x30100` | `0x33a38` | **`+0x3938`** |
| `__DATA.__bss` | `0x2280` | `0x2a00` | **`+0x780`** |
| `__TEXT.__const` | `0x18fc` | `0x1cbc` | **`+0x3c0`** |
| `__TEXT.__cstring` | `0x13cd` | `0x157d` | **`+0x1b0`** |
| `__TEXT.__eh_frame` | `0x16f0` | `0x1858` | **`+0x168`** |
| `__AUTH_CONST.__const` | `0x2298` | `0x23f8` | **`+0x160`** |
| `__TEXT.__swift5_typeref` | `0x558` | `0x630` | **`+0xd8`** |
| `__DATA.__data` | `0x630` | `0x6d0` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x980` | `0xa18` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x450` | `0x4e0` | **`+0x90`** |
| `__TEXT.__swift5_fieldmd` | `0x710` | `0x78c` | **`+0x7c`** |
| `__TEXT.__swift5_reflstr` | `0x63e` | `0x69e` | **`+0x60`** |
| `__TEXT.__swift5_proto` | `0x118` | `0x154` | **`+0x3c`** |
| `__AUTH_CONST.__objc_const` | `0x218` | `0x238` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xc70` | `0xc88` | **`+0x18`** |
| `__AUTH.__data` | `0x3b0` | `0x3c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2b0` | `0x2c0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA.__common` | `0x98` | `0xa0` | **`+0x8`** |

### Other Changes

```diff

-3600.75.3.0.0
+3600.79.1.0.0

-  Functions: 773
-  Symbols:   155
-  CStrings:  146
+  Functions: 818
+  Symbols:   153
+  CStrings:  152
Symbols:
+ _swift_retain_x26
- _swift_release_x26
- _swift_retain_x25
- _swift_retain_x28
CStrings:
+ "Application Support"
+ "Could not settle policy discrepancy, unable to open non-purgeable cache destination: "
+ "Could not settle policy discrepancy, unable to open purgeable cache destination: "
+ "Failed to conform existing specialized asset to persistent purge conditions for "
+ "Invalid number of keys found, expected one."
+ "Unable to resolve conflicting purge conditions for "
```
