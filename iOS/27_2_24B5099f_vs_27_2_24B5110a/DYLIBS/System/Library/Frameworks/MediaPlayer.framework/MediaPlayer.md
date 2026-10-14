## MediaPlayer

> `/System/Library/Frameworks/MediaPlayer.framework/MediaPlayer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x276c0` | `0x276e0` | **`+0x20`** |
| `__TEXT.__text` | `0x38e9d8` | `0x38e9c0` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x28b7c` | `0x28b8c` | **`+0x10`** |
| `__TEXT.__cstring` | `0x31d48` | `0x31d56` | **`+0xe`** |
| `__AUTH_CONST.__objc_const` | `0x45c78` | `0x45c80` | **`+0x8`** |
| `__DATA.__bss` | `0xeb0` | `0xea8` | **`-0x8`** |
| `__DATA_CONST.__const` | `0xd980` | `0xd988` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x13a58` | `0x13a60` | **`+0x8`** |

### Other Changes

```diff

-4026.200.22.2.0
+4026.210.1.0.0

-  CStrings:  7439
+  CStrings:  7440
Functions:
~ sub_1a6f21740 -> sub_1a7088740 : 84 -> 88
~ -[MPAVEndpointRoute initWithEndpointFactory:] : 344 -> 308
~ +[MPAVRoute routeSubtypeForMRSubtype:mrType:] : 256 -> 264
CStrings:
+ "HomeAccessory"
```
