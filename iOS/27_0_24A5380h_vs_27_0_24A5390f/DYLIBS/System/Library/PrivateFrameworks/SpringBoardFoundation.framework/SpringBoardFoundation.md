## SpringBoardFoundation

> `/System/Library/PrivateFrameworks/SpringBoardFoundation.framework/SpringBoardFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb96cc` | `0xb9720` | **`+0x54`** |
| `__TEXT.__cstring` | `0xed40` | `0xed74` | **`+0x34`** |
| `__AUTH_CONST.__cfstring` | `0xbf00` | `0xbf20` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x1a730` | `0x1a740` | **`+0x10`** |
| `__AUTH_CONST.__objc_doubleobj` | `0x500` | `0x510` | **`+0x10`** |

### Other Changes

```diff

-4626.103.0.0.0
+4630.1.102.0.0

-  CStrings:  2541
+  CStrings:  2543
Functions:
~ _OUTLINED_FUNCTION_22 : 20 -> 12
~ _OUTLINED_FUNCTION_21 : 12 -> 20
~ -[SBIdleTimerDefaults _bindAndRegisterDefaults] : 548 -> 608
~ _DeserializeCredential : 436 -> 460
CStrings:
+ "SBAmbientExtendedIdleTimer"
+ "ambientExtendedIdleTimer"
```
