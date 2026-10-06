## SecurePairingSession

> `/System/Library/PrivateFrameworks/SecurePairingSession.framework/SecurePairingSession`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9c08` | `0x9f58` | **`+0x350`** |
| `__TEXT.__eh_frame` | `0x1078` | `0x1108` | **`+0x90`** |
| `__TEXT.__cstring` | `0x377` | `0x3a7` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x468` | `0x478` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1c8` | `0x1d0` | **`+0x8`** |

### Other Changes

```diff

-67.5.0.0.0
+67.7.0.0.0

-  Symbols:   167
-  CStrings:  15
+  Symbols:   168
+  CStrings:  16
Symbols:
+ _swift_errorRetain
Functions:
~ sub_2a96d21a4 -> sub_2a93f31a4 : 140 -> 236
~ sub_2a96d2230 -> ___swift_instantiateConcreteTypeFromMangledNameV2 : 264 -> 84
~ ___swift_instantiateConcreteTypeFromMangledNameV2 -> sub_2a93f32e4 : 84 -> 364
~ sub_2a96d23e0 -> sub_2a93f34a4 : 268 -> 368
~ sub_2a96d26d8 -> sub_2a93f3800 : 232 -> 356
~ sub_2a96d3954 -> sub_2a93f4af8 : 140 -> 236
~ sub_2a96d39e0 -> sub_2a93f4be4 : 272 -> 372
~ sub_2a96d3af0 -> sub_2a93f4d58 : 260 -> 368
~ sub_2a96d3de0 -> sub_2a93f50b4 : 232 -> 356
CStrings:
+ "Unexpected exception while calling deriveSessionKeys: "
+ "Unexpected exception while calling isPaired: "
+ "Unexpected exception while calling revokeSession: "
+ "Unexpected exception while calling startSessionHandshake: "
- "Unexpected exception while calling deriveSessionKeys"
- "Unexpected exception while calling revokeSession"
- "Unexpected exception while calling startSessionHandshake"
```
