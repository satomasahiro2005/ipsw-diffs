## SafariFoundation

> `/System/Library/PrivateFrameworks/SafariFoundation.framework/SafariFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35928` | `0x35d44` | **`+0x41c`** |
| `__TEXT.__oslogstring` | `0x1408` | `0x1708` | **`+0x300`** |
| `__DATA_CONST.__const` | `0x14b8` | `0x14e0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x1988` | `0x19a8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x21b8` | `0x21d0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x8a0` | `0x8b0` | **`+0x10`** |
| `__TEXT.__const` | `0x724` | `0x734` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0xee8` | `0xef0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1498` | `0x14a0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x12d0` | `0x12cc` | **`-0x4`** |

### Other Changes

```diff

-625.1.18.10.4
+625.1.20.10.3

-  Functions: 1408
-  Symbols:   2077
-  CStrings:  429
+  Functions: 1411
+  Symbols:   2080
+  CStrings:  438
Symbols:
+ -[SFAppAutoFillOneTimeCodeProvider _consumeOneTimeCode:suppressOnboarding:]
+ -[SFAppAutoFillOneTimeCodeProvider consumeMessagesOneTimeCodeWithGUID:suppressOnboarding:]
+ -[SFAppAutoFillOneTimeCodeProvider consumeOneTimeCode:suppressOnboarding:]
+ ___74-[SFAppAutoFillOneTimeCodeProvider consumeOneTimeCode:suppressOnboarding:]_block_invoke
+ ___90-[SFAppAutoFillOneTimeCodeProvider consumeMessagesOneTimeCodeWithGUID:suppressOnboarding:]_block_invoke
+ ___block_descriptor_48_e8_32s40w_e32_v32?0"NSString"8"NSDate"16q24ls32l8w40l8
+ ___block_descriptor_49_e8_32s40s_e5_v8?0ls32l8s40l8
+ __os_log_fault_impl
+ _initWithOptions:.lastAllocatedInstance
+ _objc_storeWeak
- -[SFAppAutoFillOneTimeCodeProvider _consumeOneTimeCode:]
- GCC_except_table53
- ___52-[SFAppAutoFillOneTimeCodeProvider initWithOptions:]_block_invoke_3
- ___52-[SFAppAutoFillOneTimeCodeProvider initWithOptions:]_block_invoke_4
- ___55-[SFAppAutoFillOneTimeCodeProvider consumeOneTimeCode:]_block_invoke
- ___71-[SFAppAutoFillOneTimeCodeProvider consumeMessagesOneTimeCodeWithGUID:]_block_invoke
- ___block_descriptor_40_e8_32w_e32_v32?0"NSString"8"NSDate"16q24lw32l8
CStrings:
+ "Allocating SFAppAutoFillOneTimeCodeProvider %p while %p is still live; we intend to only have one allocated per process"
+ "Creating EMOneTimeCodeAccelerator for SFAppAutoFillOneTimeCodeProvider %p"
+ "Deallocating SFAppAutoFillOneTimeCodeProvider %p"
+ "Discarded Mail one-time code on SFAppAutoFillOneTimeCodeProvider %p"
+ "EMOneTimeCodeAccelerator update block fired on SFAppAutoFillOneTimeCodeProvider %p (messageID=%{private}ld)"
+ "Received one-time code on SFAppAutoFillOneTimeCodeProvider %p but have no observers to notify"
+ "SFAppAutoFillOneTimeCodeProvider %p added observer %@; %lu observer%s remain"
+ "SFAppAutoFillOneTimeCodeProvider %p removed observer %@; %lu observer%s remain"
+ "Skipping EMOneTimeCodeAccelerator creation for SFAppAutoFillOneTimeCodeProvider %p (excluded by options)"
```
