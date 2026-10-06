## txm.iphoneos.release.im4p

> `Firmware/txm.iphoneos.release.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x49c28` | `0x49c38` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__cstring`
- `__TEXT_BOOT_EXEC.__text`

### Other Changes

```diff
Functions:
~ sub_fffffff0170631ec : 200 -> 204
~ sub_fffffff017064f0c -> sub_fffffff017064f10 : 492 -> 504
CStrings:
+ "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Sat Sep 12 03:03:29 PDT 2026; root:AppleImage4_txm-374~8103/libimage4_TXM/RELEASE_ARM64E"
+ "Code Signing Monitor Image4 Module Version 7.0.0: Sat Sep 12 03:03:29 PDT 2026; root:AppleImage4_txm-374~8103/libimage4_TXM/RELEASE_ARM64E"
- "@(#)VERSION:Code Signing Monitor Image4 Module Version 7.0.0: Wed Sep  2 23:49:02 PDT 2026; root:AppleImage4_txm-374~7872/libimage4_TXM/RELEASE_ARM64E"
- "Code Signing Monitor Image4 Module Version 7.0.0: Wed Sep  2 23:49:02 PDT 2026; root:AppleImage4_txm-374~7872/libimage4_TXM/RELEASE_ARM64E"
```
