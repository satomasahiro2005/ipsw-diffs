## com.apple.DriverKit-AppleBCMWLAN

> `/System/Library/DriverExtensions/com.apple.DriverKit-AppleBCMWLAN.dext/com.apple.DriverKit-AppleBCMWLAN`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x291dec` | `0x2920c8` | **`+0x2dc`** |
| `__TEXT.__cstring` | `0x834d7` | `0x83612` | **`+0x13b`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 14198
+  Functions: 14201

-  CStrings:  13144
+  CStrings:  13148
CStrings:
+ "Oct  3 2026 15:40:08"
+ "[dk] %s@%d:ERROR: NAN attribute header runs past the end of the attribute list\n"
+ "[dk] %s@%d:ERROR: NAN attribute length %u exceeds the remaining attribute list\n"
+ "[dk] %s@%d:ERROR: NAN shared key descriptor body %u too short, minimum %u\n"
+ "[dk] %s@%d:ERROR: NAN shared key descriptor key data length %u exceeds body %u\n"
- "Oct  3 2026 20:55:39"
```
