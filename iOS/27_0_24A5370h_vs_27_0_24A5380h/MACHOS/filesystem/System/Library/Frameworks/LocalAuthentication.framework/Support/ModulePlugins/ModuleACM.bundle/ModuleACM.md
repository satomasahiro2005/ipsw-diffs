## ModuleACM

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/ModulePlugins/ModuleACM.bundle/ModuleACM`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x27cb` | `0x280d` | **`+0x42`** |
| `__TEXT.__objc_stubs` | `0x2680` | `0x26c0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0xa70` | `0xa80` | **`+0x10`** |
| `__TEXT.__text` | `0x20d18` | `0x20d28` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2319.0.16.502.1
+2319.0.33.0.1

-  Functions: 636
+  Functions: 637

-  CStrings:  922
+  CStrings:  924
Functions:
~ sub_158c : 576 -> 564
+ sub_17634
- sub_1764c
+ sub_17690
~ _LibCall_ACMContextVerifyPolicyAndCopyRequirementEx : 704 -> 716
~ _LibCall_ACMKernDoubleClickNotify : 172 -> 180
~ _LibCall_ACMContextVerifyPolicyEx : 196 -> 192
~ _LibCall_ACMSecContextVerifyPolicyAndCopyRequirementEx : 200 -> 196
~ _LibCall_ACMContextLoadFromImage : 464 -> 460
~ _LibCall_ACMSecSetBuiltinBiometry : 164 -> 172
CStrings:
+ "createContextWithExternalForm:"
+ "createContextWithFlags:contextRef:"
```
