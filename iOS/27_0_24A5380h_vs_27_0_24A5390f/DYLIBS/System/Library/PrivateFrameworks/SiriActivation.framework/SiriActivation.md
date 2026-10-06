## SiriActivation

> `/System/Library/PrivateFrameworks/SiriActivation.framework/SiriActivation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f024` | `0x6f570` | **`+0x54c`** |
| `__AUTH_CONST.__objc_const` | `0xb068` | `0xb138` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x6ec4` | `0x6f54` | **`+0x90`** |
| `__TEXT.__cstring` | `0xca12` | `0xca82` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x2000` | `0x2050` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x90a8` | `0x90da` | **`+0x32`** |
| `__AUTH_CONST.__cfstring` | `0x4fe0` | `0x5000` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1e40` | `0x1e60` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x34d8` | `0x34f0` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x1800` | `0x1808` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa58` | `0xa60` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x388` | `0x390` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2c0` | `0x2c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x71c` | `0x720` | **`+0x4`** |

### Other Changes

```diff

-3600.55.26.0.0
+3600.55.30.0.0

-  Functions: 2870
-  Symbols:   4610
-  CStrings:  1789
+  Functions: 2880
+  Symbols:   4629
+  CStrings:  1792
Symbols:
+ +[SiriRaiseToSpeakContext supportsSecureCoding]
+ -[SASActivationRequest initWithRaiseToSpeakContext:]
+ -[SASActivationRequest isRaiseToSpeakRequest]
+ -[SiriActivationService activationRequestFromRaiseToSpeakWithContext:]
+ -[SiriRaiseToSpeakContext .cxx_destruct]
+ -[SiriRaiseToSpeakContext encodeWithCoder:]
+ -[SiriRaiseToSpeakContext initWithCoder:]
+ -[SiriRaiseToSpeakContext initWithRequestInfo:]
+ -[SiriRaiseToSpeakContext requestInfo]
+ -[SiriRaiseToSpeakContext speechRequestOptions]
+ GCC_except_table105
+ GCC_except_table163
+ GCC_except_table79
+ GCC_except_table99
+ _OBJC_CLASS_$_SiriRaiseToSpeakContext
+ _OBJC_IVAR_$_SiriRaiseToSpeakContext._requestInfo
+ _OBJC_METACLASS_$_SiriRaiseToSpeakContext
+ __OBJC_$_CLASS_METHODS_SiriRaiseToSpeakContext
+ __OBJC_$_INSTANCE_METHODS_SiriRaiseToSpeakContext
+ __OBJC_$_INSTANCE_VARIABLES_SiriRaiseToSpeakContext
+ __OBJC_$_PROP_LIST_SiriRaiseToSpeakContext
+ __OBJC_CLASS_RO_$_SiriRaiseToSpeakContext
+ __OBJC_METACLASS_RO_$_SiriRaiseToSpeakContext
- GCC_except_table103
- GCC_except_table162
- GCC_except_table78
- GCC_except_table98
CStrings:
+ "%s #activation Rejecting VT/RTS activation request since we have a Starting presentation"
+ "%s #activation activationRequestFromRaiseToSpeakWithContext"
+ "-[SiriActivationService activationRequestFromRaiseToSpeakWithContext:]"
+ "SiriActivationEventTypeRaiseToSpeak"
- "%s #activation Rejecting VT/RTS activation request since we have a Starting or Active presentation"
```
