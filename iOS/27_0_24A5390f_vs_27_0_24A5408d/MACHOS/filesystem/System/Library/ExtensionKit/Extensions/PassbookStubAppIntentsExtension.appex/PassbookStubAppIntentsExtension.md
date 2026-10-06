## PassbookStubAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/PassbookStubAppIntentsExtension.appex/PassbookStubAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a4c` | `0x77d8` | **`+0x2d8c`** |
| `__DATA.__bss` | `0x1000` | `0x1a80` | **`+0xa80`** |
| `__TEXT.__const` | `0x9c8` | `0x10e0` | **`+0x718`** |
| `__DATA_CONST.__const` | `0x381` | `0x5d8` | **`+0x257`** |
| `__TEXT.__swift5_typeref` | `0x3ae` | `0x592` | **`+0x1e4`** |
| `__TEXT.__eh_frame` | `0x98` | `0x238` | **`+0x1a0`** |
| `__TEXT.__cstring` | `0x1f3` | `0x373` | **`+0x180`** |
| `__TEXT.__unwind_info` | `0x228` | `0x390` | **`+0x168`** |
| `__DATA.__data` | `0x1e8` | `0x320` | **`+0x138`** |
| `__TEXT.__constg_swiftt` | `0x118` | `0x20c` | **`+0xf4`** |
| `__TEXT.__swift5_assocty` | `0x108` | `0x1c0` | **`+0xb8`** |
| `__TEXT.__auth_stubs` | `0x710` | `0x7c0` | **`+0xb0`** |
| `__TEXT.__swift5_reflstr` | `0x1f3` | `0x2a3` | **`+0xb0`** |
| `__TEXT.__objc_methname` | `0x129` | `0x1d4` | **`+0xab`** |
| `__TEXT.__swift5_fieldmd` | `0x104` | `0x198` | **`+0x94`** |
| `__DATA.__common` | `0x18` | `0x78` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x390` | `0x3e8` | **`+0x58`** |
| `__TEXT.__swift5_proto` | `0x80` | `0xd4` | **`+0x54`** |
| `__DATA_CONST.__got` | `0x128` | `0x170` | **`+0x48`** |
| `__TEXT.__objc_stubs` | `0x140` | `0x180` | **`+0x40`** |
| `__TEXT.__swift_as_cont` | `0x4` | `0x20` | **`+0x1c`** |
| `__TEXT.__objc_methtype` | `—` | `0x15` | **`+0x15`** |
| `__TEXT.__swift_as_entry` | `0x8` | `0x1c` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x50` | `0x60` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x410` | `0x420` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x18` | `0x28` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x4` | `0x14` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-1689.3.0.0.0
+1695.1.2.0.0

-  Functions: 157
-  Symbols:   117
-  CStrings:  27
+  Functions: 275
+  Symbols:   127
+  CStrings:  41
Symbols:
+ _OBJC_CLASS_$_PKPaymentService
+ __NSConcreteStackBlock
+ _objc_retain_x19
+ _swift_allocError
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_release
+ _swift_willThrow
CStrings:
+ "End payment pairing"
+ "From Device Name"
+ "Name of the device that triggered the payment."
+ "Prewarm payment pairing"
+ "Remote payment session identifier"
+ "Remote payment token"
+ "The identifier used for a payment session."
+ "The remote payment token to be used."
+ "Type of payment being made."
+ "disbursement"
+ "notifyToContinueRemoteNetworkPaymentForSession:remoteLinkToken:paymentType:fromDeviceName:completion:"
+ "payment"
+ "removeContinueRemoteNetworkPaymentNotificationForSession:completion:"
+ "v20@?0B8@\"NSError\"12"
```
