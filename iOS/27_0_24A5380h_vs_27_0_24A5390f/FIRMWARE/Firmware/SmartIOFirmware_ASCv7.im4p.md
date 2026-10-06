## SmartIOFirmware_ASCv7.im4p

> `Firmware/SmartIOFirmware_ASCv7.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA._rtk_boot` | `0x1000` | `0x2000` | **`+0x1000`** |
| `__TEXT.__text` | `0x1a904` | `0x1a880` | **`-0x84`** |
| `__TEXT.__cstring` | `0x1064` | `0x1062` | **`-0x2`** |

### Same-size Content Changes

- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__TEXT.__const`
- `__TEXT._rtk_mtab`

### Other Changes

```diff
CStrings:
+ "!MIDR: 0x%x"
- "!MIDR: 0x%llx"
```
