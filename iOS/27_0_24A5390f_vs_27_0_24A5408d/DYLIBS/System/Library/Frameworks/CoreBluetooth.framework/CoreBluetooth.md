## CoreBluetooth

> `/System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd7c3c` | `0xd7e20` | **`+0x1e4`** |
| `__TEXT.__oslogstring` | `0x3124` | `0x320b` | **`+0xe7`** |
| `__TEXT.__cstring` | `0x1ae67` | `0x1ae81` | **`+0x1a`** |

### Other Changes

```diff

-2700.46.1.1.0
+2700.51.1.1.0

-  Functions: 5533
+  Functions: 5534

-  CStrings:  5111
+  CStrings:  5114
CStrings:
+ "MDE entitlement present, skipping TCC check, authStatus: CBManagerAuthorizationNotDetermined"
+ "MobileBluetooth-2700.51.1.1"
+ "Peripheral %@ attribute was %@, expected CBService"
+ "WARNING: Peripheral %@ attribute at handle %@ was %@, expected CBService — replacing"
+ "com.apple.developer.media-device-extension"
- "MobileBluetooth-2700.46.1.1"
- "MockA2DPActivity"
```
