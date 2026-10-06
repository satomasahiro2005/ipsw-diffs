## Archetype

> `/System/Library/PrivateFrameworks/Archetype.framework/Archetype`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6204` | `0xa90fc` | **`+0x2ef8`** |
| `__DATA.__bss` | `0x24480` | `0x24700` | **`+0x280`** |
| `__TEXT.__const` | `0x14e90` | `0x150c8` | **`+0x238`** |
| `__TEXT.__oslogstring` | `0x6f1` | `0x791` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x3a55` | `0x3aeb` | **`+0x96`** |
| `__AUTH_CONST.__const` | `0xc368` | `0xc3f8` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x4870` | `0x48e0` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x4d58` | `0x4dc8` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x4728` | `0x4790` | **`+0x68`** |
| `__TEXT.__swift5_reflstr` | `0x2757` | `0x27ba` | **`+0x63`** |
| `__DATA.__data` | `0x30f8` | `0x3150` | **`+0x58`** |
| `__AUTH_CONST.__auth_got` | `0x968` | `0x9a8` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x32b0` | `0x32d4` | **`+0x24`** |
| `__TEXT.__swift5_proto` | `0x14a4` | `0x14b8` | **`+0x14`** |
| `__DATA_DIRTY.__data` | `0x1b10` | `0x1b20` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x514` | `0x518` | **`+0x4`** |

### Other Changes

```diff

-41.7.0.0.0
+41.11.0.0.0

-  Functions: 7835
-  Symbols:   176
-  CStrings:  430
+  Functions: 7893
+  Symbols:   179
+  CStrings:  431
Symbols:
+ _swift_bridgeObjectRelease_n
+ _swift_getAssociatedConformanceWitness
+ _swift_getAssociatedTypeWitness
CStrings:
+ "MailSmartReplyWritingStyleProfile: domainIdentifier mismatch — profile-level \"%s\" disagrees with %ld source document(s); first mismatched source domain: \"%s\""
```
