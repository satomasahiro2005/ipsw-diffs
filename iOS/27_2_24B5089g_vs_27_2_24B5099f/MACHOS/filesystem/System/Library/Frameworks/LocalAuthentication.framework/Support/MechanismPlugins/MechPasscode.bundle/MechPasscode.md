## MechPasscode

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/MechanismPlugins/MechPasscode.bundle/MechPasscode`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14490` | `0x145cc` | **`+0x13c`** |
| `__TEXT.__oslogstring` | `0x39d` | `0x3e0` | **`+0x43`** |
| `__TEXT.__objc_methname` | `0xced` | `0xd11` | **`+0x24`** |
| `__DATA_CONST.__got` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1b1` | `0x1bc` | **`+0xb`** |
| `__DATA.__objc_selrefs` | `0x440` | `0x448` | **`+0x8`** |
| `__TEXT.__const` | `0x190` | `0x198` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2b8` | `0x2c0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x410` | `0x418` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-2319.40.35.0.1
+2319.40.43.0.0

-  Functions: 500
-  Symbols:   376
-  CStrings:  470
+  Functions: 501
+  Symbols:   378
+  CStrings:  473
Symbols:
+ _LACErrorCodeUserFallback
+ _LACPolicyOptionDisableAutomaticPasscodeFallback
Functions:
~ sub_3204 : 244 -> 316
+ sub_3340
CStrings:
+ "%{public}@ declines the automatic fallback: the caller disabled it"
+ "B24@0:8@16"
+ "acceptsAutomaticFallbackAfterError:"
```
