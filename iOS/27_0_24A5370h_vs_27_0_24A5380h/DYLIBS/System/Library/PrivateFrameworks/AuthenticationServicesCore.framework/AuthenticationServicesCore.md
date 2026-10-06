## AuthenticationServicesCore

> `/System/Library/PrivateFrameworks/AuthenticationServicesCore.framework/AuthenticationServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0xd00` | `0x480` | **`-0x880`** |
| `__DATA_DIRTY.__objc_data` | `0x1d10` | `0x2590` | **`+0x880`** |
| `__DATA_DIRTY.__bss` | `0x1500` | `0x1a90` | **`+0x590`** |
| `__DATA.__bss` | `0x11550` | `0x10fd0` | **`-0x580`** |
| `__AUTH.__data` | `0x480` | `0x828` | **`+0x3a8`** |
| `__DATA.__data` | `0x2840` | `0x25a0` | **`-0x2a0`** |
| `__DATA_DIRTY.__data` | `0x1250` | `0x1170` | **`-0xe0`** |
| `__DATA.__common` | `0x1b0` | `0x148` | **`-0x68`** |
| `__DATA_DIRTY.__common` | `0x68` | `0xd0` | **`+0x68`** |
| `__TEXT.__text` | `0xc8558` | `0xc8508` | **`-0x50`** |
| `__AUTH_CONST.__cfstring` | `0x2040` | `0x2060` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x8c8` | `0x8d8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3cc1` | `0x3cd1` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1400` | `0x13f8` | **`-0x8`** |

### Other Changes

```diff

-625.1.20.10.3
+625.1.22.10.3

-  Symbols:   3395
-  CStrings:  785
+  Symbols:   3394
+  CStrings:  786
Symbols:
- _swift_willThrowTypedImpl
Functions:
~ ___79-[ASCAgent performSilentAuthorizationRequestsForContext:withCompletionHandler:]_block_invoke : 1684 -> 1704
~ ___52-[ASCAgent _credentialRequestedForCABLELoginChoice:]_block_invoke.431 -> ___52-[ASCAgent _credentialRequestedForCABLELoginChoice:]_block_invoke.434 : 388 -> 400
~ -[ASCAgent _authorizationCompletedWithCredential:error:] : 1904 -> 1896
~ sub_24f711438 -> sub_2542fb450 : 3940 -> 3964
~ sub_24f7124f0 -> sub_2542fc520 : 4904 -> 4884
~ sub_24f721de8 -> sub_25430be04 : 1876 -> 1872
~ sub_24f722698 -> sub_25430c6b0 : 504 -> 500
~ sub_24f73d974 -> sub_254327988 : 640 -> 608
~ sub_24f73dca8 -> sub_254327c9c : 708 -> 672
~ sub_24f7471c0 -> sub_254331190 : 2304 -> 2348
~ sub_24f758a1c -> sub_254342a18 : 1504 -> 1492
~ sub_24f758ffc -> sub_254342fec : 1608 -> 1576
~ sub_24f7957bc -> sub_25437f78c : 556 -> 524
CStrings:
+ "com.apple.ASApp-Catalyst"
```
