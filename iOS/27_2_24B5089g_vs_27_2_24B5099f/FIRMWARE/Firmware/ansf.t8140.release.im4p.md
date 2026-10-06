## ansf.t8140.release.im4p

> `Firmware/ansf.t8140.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e5e80` | `0x1e5f64` | **`+0xe4`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__TEXT.__const`
- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ sub_1d588 : 460 -> 496
~ sub_1d754 -> sub_1d778 : 448 -> 640
~ sub_1edd1c -> sub_1ede00 : 356 -> 368
CStrings:
+ "241.40.4~839"
+ "AppleStorageFirmwareASP3-241.40.4~839"
- "241.40.4~334"
- "AppleStorageFirmwareASP3-241.40.4~334"
```
