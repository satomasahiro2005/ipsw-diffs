## SiriActivationFoundation

> `/System/Library/PrivateFrameworks/SiriActivationFoundation.framework/SiriActivationFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xfd0` | `0x1f8` | **`-0xdd8`** |
| `__DATA_DIRTY.__objc_data` | `0x1c8` | `0xfa0` | **`+0xdd8`** |
| `__DATA_DIRTY.__data` | `0x388` | `0xda0` | **`+0xa18`** |
| `__AUTH.__data` | `0x660` | `0x138` | **`-0x528`** |
| `__DATA.__data` | `0x1338` | `0xe70` | **`-0x4c8`** |
| `__DATA.__bss` | `0x13a0` | `0x1220` | **`-0x180`** |
| `__DATA_DIRTY.__bss` | `0x180` | `0x300` | **`+0x180`** |
| `__AUTH_CONST.__objc_const` | `0x59e0` | `0x5a10` | **`+0x30`** |
| `__TEXT.__cstring` | `0x442b` | `0x445b` | **`+0x30`** |
| `__DATA.__common` | `0x28` | `—` | **`-0x28`** |
| `__DATA_DIRTY.__common` | `0x38` | `0x60` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x3b20` | `0x3b40` | **`+0x20`** |
| `__TEXT.__text` | `0x3ad7c` | `0x3ad5c` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x27ec` | `0x2804` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x10d0` | `0x10e0` | **`+0x10`** |
| `__TEXT.__const` | `0x204c` | `0x205c` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1622` | `0x1616` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x3f0` | `0x3e8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1190` | `0x1188` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x354` | `0x358` | **`+0x4`** |

### Other Changes

```diff

-3600.55.10.0.0
+3600.55.26.0.0

-  Functions: 1907
-  Symbols:   2086
+  Functions: 1904
+  Symbols:   2084
Symbols:
+ -[SAFLongPressButtonContext buttonUpTimestamp]
+ -[SAFLongPressButtonContext setButtonUpTimestamp:]
+ _OBJC_IVAR_$_SAFLongPressButtonContext._buttonUpTimestamp
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 24SiriActivationFoundation36SAFSimpleAnonymousConnectionListenerC0D5State33_22D591E081B3BEBA2952509E3576E5DALLO
- ___swift_closure_destructor.51Tm
- _get_type_metadata 15Synchronization5MutexVy24SiriActivationFoundation05CampoD6ServerC5State33_9B53C717C553B2C5DB20B7C56B41FDA3LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy24SiriActivationFoundation05CampoD7ServiceC0fD10ClientPeer33_39AFFD0D01303096113D9013677705FELLC5StateVG noncopyable
- _get_type_metadata 24SiriActivationFoundation18SAFServiceDefiningRzl15Synchronization5MutexVyAA36SAFSimpleAnonymousConnectionListenerC0B5State33_22D591E081B3BEBA2952509E3576E5DALLOyx_GG noncopyable
- _get_type_metadata 24SiriActivationFoundation18SAFServiceDefiningRzl15Synchronization5MutexVySbG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "<SAFLongPressButtonContext contextOverride:%@ buttonDownTimestamp:%@ buttonUpTimestamp:%@ longPressBehavior: %@, activationEventInstrumentationIdentifier: %@>"
+ "buttonUpTimestamp"
- "!"
- "<SAFLongPressButtonContext contextOverride:%@ buttonDownTimestamp:%@ longPressBehavior: %@, activationEventInstrumentationIdentifier: %@>"
```
