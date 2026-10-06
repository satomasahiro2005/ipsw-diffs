## SpringBoardFoundation

> `/System/Library/PrivateFrameworks/SpringBoardFoundation.framework/SpringBoardFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3a70` | `0x3980` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x230` | `0x320` | **`+0xf0`** |
| `__TEXT.__cstring` | `0xed7b` | `0xed40` | **`-0x3b`** |
| `__AUTH_CONST.__cfstring` | `0xbf20` | `0xbf00` | **`-0x20`** |
| `__TEXT.__text` | `0xb96e8` | `0xb96cc` | **`-0x1c`** |
| `__AUTH_CONST.__objc_const` | `0x1a740` | `0x1a730` | **`-0x10`** |
| `__DATA.__bss` | `0x940` | `0x938` | **`-0x8`** |

### Other Changes

```diff

-4621.0.0.0.0
+4626.103.0.0.0

-  Functions: 3866
+  Functions: 3867

-  CStrings:  2542
+  CStrings:  2541
Functions:
~ _OUTLINED_FUNCTION_45 : 12 -> 24
~ _OUTLINED_FUNCTION_44 : 16 -> 12
~ _OUTLINED_FUNCTION_10 : 12 -> 16
+ _OUTLINED_FUNCTION_10
~ -[SBApplicationDefaults _bindAndRegisterDefaults] : 992 -> 936
~ _OUTLINED_FUNCTION_46 : 24 -> 12
~ _OUTLINED_FUNCTION_47 : 12 -> 20
~ _OUTLINED_FUNCTION_48 : 20 -> 12
~ _OUTLINED_FUNCTION_53 : 12 -> 20
~ _OUTLINED_FUNCTION_56 : 20 -> 12
~ _OUTLINED_FUNCTION_57 : 12 -> 20
~ _OUTLINED_FUNCTION_59 : 20 -> 12
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 704 -> 716
~ _LibCall_ACMKernDoubleClickNotify : 172 -> 180
~ _LibCall_ACMContextVerifyPolicyEx : 196 -> 192
~ _LibCall_ACMSecContextVerifyPolicyAndCopyRequirementEx : 200 -> 196
~ _LibCall_ACMContextLoadFromImage : 464 -> 460
~ _LibCall_ACMSecSetBuiltinBiometry : 164 -> 172
CStrings:
- "updateRegionOfInterestOnTransactionBeginForResizingService"
```
