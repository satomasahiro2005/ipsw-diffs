## HMFoundation

> `/System/Library/PrivateFrameworks/HMFoundation.framework/HMFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x98a7c` | `0xa1268` | **`+0x87ec`** |
| `__TEXT.__eh_frame` | `0x3278` | `0x3918` | **`+0x6a0`** |
| `__AUTH_CONST.__const` | `0x2338` | `0x26d0` | **`+0x398`** |
| `__TEXT.__const` | `0x3100` | `0x33e0` | **`+0x2e0`** |
| `__TEXT.__unwind_info` | `0x31f8` | `0x3418` | **`+0x220`** |
| `__DATA.__bss` | `0xaa0` | `0xca0` | **`+0x200`** |
| `__DATA.__data` | `0x27cc` | `0x29c4` | **`+0x1f8`** |
| `__TEXT.__constg_swiftt` | `0xe10` | `0xf5c` | **`+0x14c`** |
| `__TEXT.__swift5_typeref` | `0xb6e` | `0xc7a` | **`+0x10c`** |
| `__AUTH_CONST.__auth_got` | `0x1390` | `0x1460` | **`+0xd0`** |
| `__TEXT.__swift5_fieldmd` | `0x7c4` | `0x890` | **`+0xcc`** |
| `__TEXT.__cstring` | `0x31c7` | `0x3227` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x42a` | `0x48a` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x670` | `0x6b4` | **`+0x44`** |
| `__DATA_CONST.__got` | `0x820` | `0x850` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x228` | `0x254` | **`+0x2c`** |
| `__AUTH_CONST.__objc_const` | `0xe6b8` | `0xe6e0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1638` | `0x1660` | **`+0x28`** |
| `__TEXT.__swift_as_entry` | `0x19c` | `0x1c4` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `0x1c4` | `0x1ec` | **`+0x28`** |
| `__TEXT.__swift5_types` | `0xb4` | `0xc8` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x3148` | `0x3158` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x6c` | `0x7c` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x79c4` | `0x79cc` | **`+0x8`** |
| `__TEXT.__swift5_types2` | `—` | `0x4` | **`+0x4`** |
| `__TEXT.__oslogstring` | `0x8109` | `0x8107` | **`-0x2`** |

### Other Changes

```diff

-1493.1.5.1.1
+1514.0.0.0.1

-  Functions: 3668
-  Symbols:   5519
-  CStrings:  1427
+  Functions: 3802
+  Symbols:   5554
+  CStrings:  1430
Symbols:
+ +[HMFFlow flowWithPropagatedUUID:]
+ __IVARS__TtC12HMFoundation23CancellableContinuation
+ ___swift_assignWithCopy_strong
+ ___swift_assignWithTake_strong
+ ___swift_assign_boxed_opaque_existential_0
+ ___swift_cannot_copy_noncopyable_type
+ ___swift_destroy_strong
+ ___swift_initWithCopy_strong
+ ___swift_memcpy8_8
+ ___unnamed_3
+ _swift_initEnumMetadataMultiPayload
+ _swift_release_x9
+ _symbolic SDySSypGSg
+ _symbolic SS3key_t
+ _symbolic ScCySDySSypGSg______pG s5ErrorP
+ _symbolic ScCySDySSypGSg______pGSg s5ErrorP
+ _symbolic ScCyxq_G
+ _symbolic _____ 12HMFoundation17HMFMessagePayloadO
+ _symbolic _____ 12HMFoundation17HMFMessagePayloadO0C5ErrorO
+ _symbolic _____ 12HMFoundation23CancellableContinuationC
+ _symbolic _____ 12HMFoundation23CancellableContinuationC12ResumeHandleV
+ _symbolic _____ 12HMFoundation23CancellableContinuationC5State33_BC72CE195F1A792348A6ADCE471D45B6LLO
+ _symbolic _____ 12HMFoundation3HMFO12TimeoutErrorV
+ _symbolic _____ySDySSypGSg______pG 12HMFoundation23CancellableContinuationC s5ErrorP
+ _symbolic _____ySDySSypGSg______p_G 12HMFoundation23CancellableContinuationC5State33_BC72CE195F1A792348A6ADCE471D45B6LLO s5ErrorP
+ _symbolic _____ySSG s23_ContiguousArrayStorageC
+ _symbolic _____ySsG s23_ContiguousArrayStorageC
+ _symbolic _____y_____ySDySSypGSg______p_GG 15Synchronization5MutexVAARi_zrlE 12HMFoundation23CancellableContinuationC5State33_BC72CE195F1A792348A6ADCE471D45B6LLO s5ErrorP
+ _symbolic _____y_____yxq__GG 15Synchronization5MutexVAARi_zrlE 12HMFoundation23CancellableContinuationC5State33_BC72CE195F1A792348A6ADCE471D45B6LLO
+ _symbolic _____yxq_G 12HMFoundation23CancellableContinuationC
+ _symbolic _____yxq_G s6ResultOsRi_zRi0_zrlE
+ _symbolic ypSg
+ _type_layout_string 12HMFoundation17HMFMessagePayloadO0C5ErrorO
+ _type_layout_string 12HMFoundation3HMFO12TimeoutErrorV
+ _type_layout_string s8SendableRzs5ErrorR_r0_l12HMFoundation23CancellableContinuationC12ResumeHandleVyxq__G
CStrings:
+ "HMFCodablePropagatedFlowUUID"
+ "InternalErrorMarker"
+ "Operation timed out after "
+ "[%{public}@] inet_ntop() failed with '%s' (%d) for sockaddr_in6: %@"
+ "inet_ntop() failed with '%s' (%d) for sockaddr_in6: %@"
- "[%{public}@] inet_ntop() failed  with '%s' (%d) for sockaddr_in6: %@"
- "inet_ntop() failed  with '%s' (%d) for sockaddr_in6: %@"
```
