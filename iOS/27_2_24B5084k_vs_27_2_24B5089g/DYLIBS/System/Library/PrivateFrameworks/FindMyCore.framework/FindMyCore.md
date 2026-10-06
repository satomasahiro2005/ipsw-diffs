## FindMyCore

> `/System/Library/PrivateFrameworks/FindMyCore.framework/FindMyCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x109174` | `0x10a1c8` | **`+0x1054`** |
| `__TEXT.__eh_frame` | `0x7248` | `0x7310` | **`+0xc8`** |
| `__TEXT.__cstring` | `0x3bc8` | `0x3c68` | **`+0xa0`** |
| `__DATA.__bss` | `0x1a390` | `0x1a410` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0x8bb5` | `0x8c15` | **`+0x60`** |
| `__TEXT.__const` | `0x115dc` | `0x1163c` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x1181` | `0x1141` | **`-0x40`** |
| `__AUTH_CONST.__auth_got` | `0x1a48` | `0x1a80` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x4980` | `0x49b8` | **`+0x38`** |
| `__TEXT.__swift5_capture` | `0x568` | `0x580` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x4ec` | `0x504` | **`+0x18`** |
| `__DATA.__data` | `0x3de0` | `0x3dd0` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x27b6` | `0x27c6` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x49c1` | `0x49d1` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3718` | `0x3724` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xaa0` | `0xaa8` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2e4` | `0x2ec` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xe18` | `0xe1c` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x32c` | `0x330` | **`+0x4`** |

### Other Changes

```diff

-470.31.6.16.26
+470.31.6.16.30

-  Functions: 6144
-  Symbols:   2216
-  CStrings:  476
+  Functions: 6163
+  Symbols:   2219
+  CStrings:  480
Symbols:
+ _associated conformance 10FindMyCore15PlaySoundIntentV5ErrorO10Foundation09LocalizedG0AAsAD
+ _swift_asyncLet_begin
+ _swift_asyncLet_finish
+ _swift_asyncLet_get
+ _symbolic _____Sg 10FindMyCore17PublishedLocationV
- _OBJC_CLASS_$_NSNumberFormatter
- _swift_release_x11
CStrings:
+ "DEVICE_PLAYSOUND_INTENT_BLUETOOTH_OFF_ERROR"
+ "PERSON_ME_AND_OTHER_DEVICES"
+ "PERSON_ME_CELLULAR_WATCHES"
+ "PERSON_ME_OTHER_CELLULAR_WATCHES"
+ "default"
+ "kCLErrorDomainPrivate"
- "FindItemIntent: returning the newer of the two locations."
- "PERSON_ME_AND_OTHER_DEVICES_"
```
