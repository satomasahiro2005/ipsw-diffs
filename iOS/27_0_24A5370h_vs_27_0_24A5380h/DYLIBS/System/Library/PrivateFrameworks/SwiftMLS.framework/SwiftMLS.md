## SwiftMLS

> `/System/Library/PrivateFrameworks/SwiftMLS.framework/SwiftMLS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `—` | `0x2ac8` | **`+0x2ac8`** |
| `__AUTH.__data` | `0x4a48` | `0x22d0` | **`-0x2778`** |
| `__TEXT.__text` | `0x2acdac` | `0x2adf80` | **`+0x11d4`** |
| `__DATA.__bss` | `0x1b300` | `0x1ae80` | **`-0x480`** |
| `__DATA_DIRTY.__bss` | `—` | `0x480` | **`+0x480`** |
| `__DATA.__data` | `0x3398` | `0x3090` | **`-0x308`** |
| `__TEXT.__eh_frame` | `0x20130` | `0x20420` | **`+0x2f0`** |
| `__AUTH.__objc_data` | `0x2d8` | `0x48` | **`-0x290`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x290` | **`+0x290`** |
| `__TEXT.__oslogstring` | `0x6108` | `0x62e8` | **`+0x1e0`** |
| `__TEXT.__unwind_info` | `0xa3e0` | `0xa258` | **`-0x188`** |
| `__TEXT.__swift5_reflstr` | `0x5a91` | `0x5bb1` | **`+0x120`** |
| `__DATA.__common` | `0x580` | `0x4c0` | **`-0xc0`** |
| `__DATA_DIRTY.__common` | `—` | `0xc0` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x5f94` | `0x6000` | **`+0x6c`** |
| `__TEXT.__const` | `0x24d08` | `0x24d50` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x48e0` | `0x4908` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x10e0` | `0x1100` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x100` | `0x120` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3e6d` | `0x3e8d` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x38aa` | `0x38b8` | **`+0xe`** |
| `__AUTH_CONST.__auth_got` | `0x18d0` | `0x18d8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x618` | `0x61c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xc0c` | `0xc10` | **`+0x4`** |

### Other Changes

```diff

-341.0.4.0.0
+341.0.13.0.0

-  Functions: 10469
-  Symbols:   2107
-  CStrings:  817
+  Functions: 10525
+  Symbols:   2109
+  CStrings:  823
Symbols:
+ _swift_release_x10
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 8SwiftMLS0E0O0C0O12ReadEpochKeyV
CStrings:
+ "%s: No current state available, skipping continuity token commitment verification"
+ "%s: clearing cached commit metadata on advance to new state %s"
+ "%s: clearing cached commit metadata on era advance from %u to %u"
+ "%s: discarding cached commit for era %u because group is now at era %u"
+ "%s: rejecting non-advancing Welcome { current: %s, proposed: %s }"
+ "%s: rejecting same-era Welcome — local self credential is still valid (no §9.5.4 replacement authorized)"
+ "%s: rejecting same-era Welcome — new self credential is not a valid successor of current local self credential"
+ "Join failed, Welcome was previously consumed { ref: %s }"
+ "maxRetainedEpochsPerGroup"
- "%s: We could not verify the continuity token commitment in era advancement: %@"
- "%s: We could not verify the continuity token commitment in resync: %@"
- "We could not verify the continuity token commitment: %@"
```
