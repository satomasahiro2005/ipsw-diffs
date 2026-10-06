## MechPasscode

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismPlugins/MechPasscode.bundle/MechPasscode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x143e8` | `0x14438` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0xce2` | `0xced` | **`+0xb`** |
| `__DATA_CONST.__got` | `0x1a8` | `0x1b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2319.0.16.502.1
+2319.0.33.0.1

-  Functions: 499
+  Functions: 500
Functions:
~ sub_3204 : 192 -> 244
+ sub_a35c
- sub_a334
+ sub_a3b8
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 704 -> 716
~ _LibCall_ACMKernDoubleClickNotify : 172 -> 180
~ _LibCall_ACMContextVerifyPolicyEx : 196 -> 192
~ _LibCall_ACMSecContextVerifyPolicyAndCopyRequirementEx : 200 -> 196
~ _LibCall_ACMContextLoadFromImage : 464 -> 460
~ _LibCall_ACMSecSetBuiltinBiometry : 164 -> 172
CStrings:
+ "allowsAuthenticationFallbacksForOptions:"
- "allowsAuthenticationFallbacks"
```
