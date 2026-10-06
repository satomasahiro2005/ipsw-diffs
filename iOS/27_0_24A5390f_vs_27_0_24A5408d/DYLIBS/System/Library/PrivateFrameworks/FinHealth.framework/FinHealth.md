## FinHealth

> `/System/Library/PrivateFrameworks/FinHealth.framework/FinHealth`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xcb54` | `0x1015c` | **`+0x3608`** |
| `__AUTH_CONST.__const` | `0x2d0` | `0x500` | **`+0x230`** |
| `__TEXT.__eh_frame` | `0x1e0` | `0x3d8` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x336` | `0x489` | **`+0x153`** |
| `__TEXT.__swift5_capture` | `—` | `0xd4` | **`+0xd4`** |
| `__TEXT.__unwind_info` | `0x350` | `0x408` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x430` | `0x4a0` | **`+0x70`** |
| `__TEXT.__cstring` | `0xf27` | `0xf73` | **`+0x4c`** |
| `__TEXT.__swift_as_cont` | `0x38` | `0x6c` | **`+0x34`** |
| `__TEXT.__const` | `0x25a` | `0x288` | **`+0x2e`** |
| `__AUTH_CONST.__objc_const` | `0xb10` | `0xaf0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x268` | `0x288` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x54` | `0x6c` | **`+0x18`** |
| `__TEXT.__swift_as_entry` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x18` | `0x28` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x50` | `0x44` | **`-0xc`** |
| `__DATA_DIRTY.__objc_data` | `0x208` | `0x210` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x129` | `0x12b` | **`+0x2`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1.9.1.28.0
+1.9.1.29.0

-  Functions: 266
-  Symbols:   534
-  CStrings:  117
+  Functions: 324
+  Symbols:   550
+  CStrings:  126
Symbols:
+ ___swift_closure_destructor
+ ___swift_closure_destructor.22Tm
+ ___swift_closure_destructor.28Tm
+ __swift_dead_method_stub
+ __swift_implicitisolationactor_to_executor_cast
+ _swift_allocError
+ _swift_arrayDestroy
+ _swift_deallocObject
+ _swift_deletedAsyncMethodErrorTu
+ _swift_deletedMethodError
+ _swift_isaMask
+ _swift_lookUpClassMethod
+ _swift_release_x19
+ _swift_release_x24
+ _swift_release_x27
+ _swift_release_x28
+ _swift_release_x8
+ _symbolic Sb
+ _symbolic _____ 10Foundation4DateV
+ _symbolic _____ 10Foundation4UUIDV
- ___swift_allocate_boxed_opaque_existential_0
- ___swift_project_boxed_opaque_existential_0
- _swift_allocBox
- _symbolic ScCyyt_____G s5NeverO
CStrings:
+ "%s: XPC connection error: %s"
+ "%s: XPC request completed"
+ "%s: sending XPC request"
+ "XPC connection to finhealthd interrupted"
+ "didReceiveUpdates"
+ "forceEntityGroups"
+ "forceEntityGroups: reply error: %s"
+ "forceIncomeInsight"
+ "forceIncomeInsight: reply error: %s"
+ "upcomingPayments"
+ "upcomingPayments: received %ld results for accountID: %s"
+ "upcomingPayments: reply error for accountID: %s: %s"
+ "withXPCProxy(_:_:)"
- "Interrupted"
- "_createCheckedContinuation(_:)"
- "_createCheckedThrowingContinuation(_:)"
- "error = %s"
```
