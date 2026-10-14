## launchd

> `/sbin/launchd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x169a6` | `0x16984` | **`-0x22`** |
| `__TEXT.__config` | `0x2a71` | `0x2a50` | **`-0x21`** |
| `__TEXT.__text` | `0x5bb5c` | `0x5bb40` | **`-0x1c`** |
| `__DATA.__common` | `0x7f0` | `0x7f8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_launchd`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3298.40.28.0.0
+3298.42.1.0.0

-  CStrings:  2836
+  CStrings:  2834
Functions:
~ sub_10004a1c4 : 2980 -> 2952
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sat Oct  3 23:05:26 PDT 2026; root:libxpc_executables-3298.42.1~6/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Sat Oct  3 23:05:26 PDT 2026; root:libxpc_executables-3298.42.1~6/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Sat Sep 26 06:06:59 PDT 2026; root:libxpc_executables-3298.40.28~39/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Sat Sep 26 06:06:59 PDT 2026; root:libxpc_executables-3298.40.28~39/launchd/RELEASE_ARM64E"
- "IgnoreCache"
- "launchd_no_cache="
```
