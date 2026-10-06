## PairedDeviceRegistry

> `/System/Library/PrivateFrameworks/PairedDeviceRegistry.framework/PairedDeviceRegistry`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26348` | `0x2692c` | **`+0x5e4`** |
| `__DATA.__bss` | `0x8a0` | `0x620` | **`-0x280`** |
| `__DATA_DIRTY.__bss` | `0x10` | `0x290` | **`+0x280`** |
| `__DATA_DIRTY.__data` | `0x950` | `0xa20` | **`+0xd0`** |
| `__DATA.__data` | `0xd10` | `0xc78` | **`-0x98`** |
| `__TEXT.__cstring` | `0x216b` | `0x21eb` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x17e0` | `0x1820` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x91a` | `0x8da` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x4b0` | `0x4c0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x8e8` | `0x8f0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x8c8` | `0x8d0` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x2c8` | `0x2cc` | **`+0x4`** |

### Other Changes

```diff

-1075.1.0.0.0
+1075.1.1.0.0

-  Functions: 1101
-  Symbols:   2611
-  CStrings:  375
+  Functions: 1105
+  Symbols:   2618
+  CStrings:  376
Symbols:
+ _$s20PairedDeviceRegistry0C5_ImplC6notify19deviceColletionDiff5state8oldStateySo018NRDeviceCollectionH0C_AA0cK0VAKtFyyXEfU_yyYbcfU_Tf2nnnnnnin_n
+ _$s20PairedDeviceRegistry0C5_ImplC6notify19deviceColletionDiff5state8oldStateySo018NRDeviceCollectionH0C_AA0cK0VAKtFyyXEfU_yyYbcfU_Tf2nnnnnnin_nTA
+ _$sSo9PDRDeviceCMaTm
+ _$ss17_NativeDictionaryV20_copyOrMoveAndResize8capacity12moveElementsySi_SbtFSS_ypTg5
+ _$ss17_NativeDictionaryV4copyyyFSS_ypTg5
+ _$ss17_NativeDictionaryV7_insert2at3key5valueys10_HashTableV6BucketV_xnq_ntFSS_ypTg5
+ _$ss17_NativeDictionaryV8setValue_6forKey8isUniqueyq_n_xSbtFSS_ypTg5
+ _PDRDidEnterCompatibilityStateNotification
+ _PDRNotificationKeyCompatibilityState
- _$s20PairedDeviceRegistry0C5_ImplC6notify19deviceColletionDiff5state8oldStateySo018NRDeviceCollectionH0C_AA0cK0VAKtFyyXEfU_yyYbcfU_Tf2nnnnnni_n
- _$s20PairedDeviceRegistry0C5_ImplC6notify19deviceColletionDiff5state8oldStateySo018NRDeviceCollectionH0C_AA0cK0VAKtFyyXEfU_yyYbcfU_Tf2nnnnnni_nTA
CStrings:
+ "com.apple.watch.paireddeviceregistry.didentercompatibilitystate"
+ "com.apple.watch.paireddeviceregistry.pdr.compatibilityState"
- "Informing delegate about compatibility state change (N/A)"
```
