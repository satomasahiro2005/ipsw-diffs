## HealthAppHealthDaemonSupport

> `/System/Library/PrivateFrameworks/HealthAppHealthDaemonSupport.framework/HealthAppHealthDaemonSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11ef0` | `0x13e38` | **`+0x1f48`** |
| `__TEXT.__eh_frame` | `0x5e8` | `0x798` | **`+0x1b0`** |
| `__AUTH_CONST.__const` | `0x1cb8` | `0x1df0` | **`+0x138`** |
| `__TEXT.__const` | `0x890` | `0x980` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x830` | `0x8e8` | **`+0xb8`** |
| `__TEXT.__unwind_info` | `0x610` | `0x6a8` | **`+0x98`** |
| `__TEXT.__constg_swiftt` | `0x34c` | `0x3c8` | **`+0x7c`** |
| `__AUTH.__data` | `0x50` | `0xc8` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x1fc` | `0x268` | **`+0x6c`** |
| `__AUTH.__objc_data` | `0x238` | `0x1d0` | **`-0x68`** |
| `__DATA_DIRTY.__objc_data` | `0x220` | `0x288` | **`+0x68`** |
| `__AUTH_CONST.__auth_got` | `0x548` | `0x598` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x1a3` | `0x1e3` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x298` | `0x2c8` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x11d` | `0x14a` | **`+0x2d`** |
| `__TEXT.__swift5_typeref` | `0x429` | `0x453` | **`+0x2a`** |
| `__DATA.__data` | `0x528` | `0x550` | **`+0x28`** |
| `__TEXT.__swift_as_cont` | `0x30` | `0x4c` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x1c` | `0x38` | **`+0x1c`** |
| `__TEXT.__swift5_types` | `0x38` | `0x44` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x1c` | `0x28` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x58` | `0x5c` | **`+0x4`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

+  - /usr/lib/swift/libswiftSynchronization.dylib

-  Functions: 696
-  Symbols:   337
-  CStrings:  28
+  Functions: 741
+  Symbols:   352
+  CStrings:  29
Symbols:
+ __DATA__TtC28HealthAppHealthDaemonSupport24MockUserInteractionStore
+ __IVARS__TtC28HealthAppHealthDaemonSupport24MockUserInteractionStore
+ __METACLASS_DATA__TtC28HealthAppHealthDaemonSupport24MockUserInteractionStore
+ ___swift_memcpy32_8
+ ___swift_project_boxed_opaque_existential_1
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_arrayInitWithTakeBackToFront
+ _swift_arrayInitWithTakeFrontToBack
+ _symbolic Say_____G 24HealthPlatformFoundation15UserInteractionV
+ _symbolic _____ 09HealthAppA13DaemonSupport0aB13LaunchHistoryO
+ _symbolic _____ 09HealthAppA13DaemonSupport24MockUserInteractionStoreC
+ _symbolic _____ 09HealthAppA13DaemonSupport24MockUserInteractionStoreC5State33_2D20CBEC808C64B0B89BDA1C416E6E5FLLV
+ _symbolic _____y_____G 15Synchronization5MutexVAARi_zrlE 09HealthAppC13DaemonSupport24MockUserInteractionStoreC5State33_2D20CBEC808C64B0B89BDA1C416E6E5FLLV
+ _type_layout_string 09HealthAppA13DaemonSupport24MockUserInteractionStoreC5State33_2D20CBEC808C64B0B89BDA1C416E6E5FLLV
CStrings:
+ "[%{public}s] Failed to fetch launch interactions: %{public}@"
```
