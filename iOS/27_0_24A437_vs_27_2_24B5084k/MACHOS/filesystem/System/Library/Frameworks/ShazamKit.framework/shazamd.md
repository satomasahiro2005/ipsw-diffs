## shazamd

> `/System/Library/Frameworks/ShazamKit.framework/shazamd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5d1e8` | `0x5d4f4` | **`+0x30c`** |
| `__TEXT.__objc_stubs` | `0xd2c0` | `0xd3c0` | **`+0x100`** |
| `__TEXT.__objc_methname` | `0x1115f` | `0x111ef` | **`+0x90`** |
| `__DATA.__objc_selrefs` | `0x3b88` | `0x3bc8` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x2680` | `0x26c0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x565b` | `0x569b` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2d07` | `0x2d37` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x998` | `0x9b0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x62d4` | `0x62e4` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-427.0.48.0.0
+427.2.4.0.0

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 2130
-  Symbols:   599
-  CStrings:  3996
+  Functions: 2131
+  Symbols:   602
+  CStrings:  4007
Symbols:
+ _OBJC_CLASS_$_RBSProcessPredicate
+ _OBJC_CLASS_$_RBSProcessState
+ _OBJC_CLASS_$_RBSProcessStateDescriptor
CStrings:
+ "Could not fetch process states for Siri audio daemons due to error: %@"
+ "com.apple.corespeechd"
+ "com.apple.sirittsd"
+ "descriptor"
+ "initSystemTapWithFormat:excludePIDs:"
+ "numberWithInt:"
+ "pid"
+ "predicateMatchingAnyPredicate:"
+ "predicateMatchingJobLabel:"
+ "process"
+ "siriAudioProcessIdentifiers"
+ "statesForPredicate:withDescriptor:error:"
- "initSystemTapWithFormat:"
```
