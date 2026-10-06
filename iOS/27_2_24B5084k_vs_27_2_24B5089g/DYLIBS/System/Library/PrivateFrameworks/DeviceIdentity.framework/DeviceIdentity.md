## DeviceIdentity

> `/System/Library/PrivateFrameworks/DeviceIdentity.framework/DeviceIdentity`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0xd4` | `0x4` | **`-0xd0`** |
| `__DATA_DIRTY.__data` | `0x20` | `0xf0` | **`+0xd0`** |
| `__TEXT.__text` | `0x1d9f0` | `0x1da00` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1145.40.4.0.0
+1145.40.5.0.0
Functions:
~ _X509ExtensionParseBasicConstraints : 208 -> 212
~ _X509ChainBuildPathPartial : 488 -> 500
CStrings:
+ "iOS Device Activator (MobileActivation-1145.40.5)"
- "iOS Device Activator (MobileActivation-1145.40.4)"
```
