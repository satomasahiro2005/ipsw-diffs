## BridgeSecurePairing

> `/System/Library/PrivateFrameworks/BridgeSecurePairing.framework/BridgeSecurePairing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b410` | `0x3b468` | **`+0x58`** |
| `__TEXT.__const` | `0x1968` | `0x1978` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0xddd` | `0xded` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x938` | `0x930` | **`-0x8`** |

### Other Changes

```diff

-1350.1.0.0.0
+1355.0.0.1.0

-  Symbols:   344
+  Symbols:   343
Symbols:
- _objc_release_x28
Functions:
~ sub_24f0adbf8 -> sub_250790bf8 : 2416 -> 2428
~ sub_24f0af398 -> sub_2507923a4 : 248 -> 252
~ sub_24f0b2fd8 -> sub_250795fe8 : 2800 -> 2796
~ sub_24f0c9ed8 -> sub_2507acee4 : 1068 -> 1076
~ sub_24f0cb070 -> sub_2507ae084 : 252 -> 256
~ sub_24f0cb428 -> sub_2507ae440 : 252 -> 256
~ sub_24f0cb6fc -> sub_2507ae718 : 272 -> 276
~ sub_24f0cc1f4 -> sub_2507af214 : 260 -> 264
~ sub_24f0cc6b4 -> sub_2507af6d8 : 252 -> 256
~ sub_24f0cca40 -> sub_2507afa68 : 272 -> 276
~ sub_24f0cd19c -> sub_2507b01c8 : 1796 -> 1792
~ sub_24f0cf048 -> sub_2507b2070 : 280 -> 276
~ sub_24f0d0860 -> sub_2507b3884 : 900 -> 936
~ sub_24f0d1b94 -> sub_2507b4bdc : 524 -> 508
~ sub_24f0d1e1c -> sub_2507b4e54 : 1492 -> 1508
~ sub_24f0e4e80 -> sub_2507c7ec8 : 252 -> 256
~ sub_24f0e5194 -> sub_2507c81e0 : 272 -> 276
~ sub_24f0e53c4 -> sub_2507c8414 : 264 -> 268
~ sub_24f0e55e8 -> sub_2507c863c : 252 -> 256
CStrings:
+ "Pairing session reached terminal state"
+ "Secure Pairing Succeeded"
- "Pairing completed successfully"
- "Secure Pairing Completed"
```
