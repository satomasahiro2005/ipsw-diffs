## Campo

> `/Applications/Campo.app/Campo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xed80` | `0xf478` | **`+0x6f8`** |
| `__TEXT.__objc_methname` | `0x17bc` | `0x18bc` | **`+0x100`** |
| `__DATA.__objc_const` | `0x930` | `0xa20` | **`+0xf0`** |
| `__TEXT.__objc_stubs` | `0x700` | `0x780` | **`+0x80`** |
| `__DATA.__data` | `0x8a8` | `0x918` | **`+0x70`** |
| `__DATA.__objc_data` | `0x300` | `0x358` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x634` | `0x68c` | **`+0x58`** |
| `__DATA.__objc_selrefs` | `0x518` | `0x558` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0xe90` | `0xed0` | **`+0x40`** |
| `__TEXT.__objc_classname` | `0x204` | `0x23c` | **`+0x38`** |
| `__DATA.__common` | `0x228` | `0x258` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0xd82` | `0xdb2` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x750` | `0x770` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1f0` | `0x210` | **`+0x20`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x17c` | `0x18c` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1c0` | `0x1cc` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x220` | `0x228` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x640` | `0x638` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-73.0.12.0.0
+73.0.24.102.0

-  Functions: 528
-  Symbols:   398
-  CStrings:  315
+  Functions: 517
+  Symbols:   404
+  CStrings:  329
Symbols:
+ _$s2os12OSSignposterV6loggerAcA6LoggerV_tcfC
+ _$s2os12OSSignposterVMa
+ _OBJC_CLASS_$_SiriActivationService
+ _OBJC_CLASS_$_SiriDismissalOptions
+ _objc_alloc
+ _objc_claimAutoreleasedReturnValue
CStrings:
+ "CPInterfaceControllerDelegate"
+ "Campo1"
+ "SiriDeactivationService"
+ "deactivateSiri"
+ "deactivationRequest:"
+ "initWithDeactivationOptions:animated:requestCancellationReason:dismissalReason:shouldTurnScreenOff:"
+ "service"
+ "siriCanActivate"
+ "templateDidAppear:animated:"
+ "templateDidDisappear:animated:"
+ "templateWillAppear:animated:"
+ "templateWillDisappear:animated:"
+ "v28@0:8@\"CPTemplate\"16B24"
+ "v28@0:8@16B24"
```
