## ansf.t8140.release.im4p

> `Firmware/ansf.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e5b5c` | `0x1e5e80` | **`+0x324`** |
| `__TEXT.__const` | `0x5b68` | `0x5d68` | **`+0x200`** |
| `__TEXT.shared` | `0xdfd4` | `0xe120` | **`+0x14c`** |
| `__DATA.__zerofill` | `0x20faa8` | `0x20fad8` | **`+0x30`** |
| `__DATA.__data` | `0x5c00` | `0x5bf8` | **`-0x8`** |
| `__TEXT.__cstring` | `0x25373` | `0x25376` | **`+0x3`** |
| `__DATA.core_globals` | `0x162` | `0x164` | **`+0x2`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`

### Other Changes

```diff

-  Functions: 1976
+  Functions: 1977

-  CStrings:  3965
+  CStrings:  3964
CStrings:
+ "241.40.4"
+ "241.40.4~95"
+ "AppleStorageFirmwareASP3-241.40.4~95"
+ "Sanitize Failed"
+ "Sweep stuck detected - aborting - channel %d, die %d, plane %d"
+ "Sweep was aborted - rejecting continuation command"
+ "sanitize cmd drop - not init"
- "241.0.12"
- "241.0.12~645"
- "Abort Pad: Flow %u , Band: %u"
- "AppleStorageFirmwareASP3-241.0.12~645"
- "Sanitize already in progress, phase=%d"
- "Sanitize drop - device in shutdown"
- "mark invalid band %u S %u"
- "mark valid band %u M %u"
```
