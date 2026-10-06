## libIPTelephony.dylib

> `/System/Library/PrivateFrameworks/IPTelephony.framework/Support/libIPTelephony.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4abd1c` | `0x4abec4` | **`+0x1a8`** |
| `__TEXT.__oslogstring` | `0x4cbd8` | `0x4ccb8` | **`+0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x41f0c` | `0x41f10` | **`+0x4`** |

### Other Changes

```diff

-2772.1.0.0.0
+2774.0.0.0.0

-  CStrings:  8703
+  CStrings:  8706
Functions:
~ __ZN9SDPParser24parseTTYFormatParametersER18SDPMediaFormatInfotNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE : 812 -> 928
~ __ZN12SipUserAgent20initializeAuthClientEb : 1476 -> 1472
~ __ZN21SipRegistrationClient14handleResponseENSt3__110shared_ptrIK11SipResponseEENS1_I20SipClientTransactionEE : 5428 -> 5572
~ __ZN18IPTelephonyManager18_initializeFromSIMERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEERKN3ims11StackConfigE : 3660 -> 3852
~ __ZN18IPTelephonyManager17initializeFromSIMERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES8_RKN3ims11StackConfigENS0_10shared_ptrI8ImsPrefsEES8_ : 2228 -> 2204
CStrings:
+ "#E %{private, mask.hash}sSip stack not found %{public}s"
+ "#W %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport, and I am roaming: accepted."
+ "#W %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport: ignored! Will retry Registration."
+ "#W TTY with unexpected format parameters parsed: '%s'"
- "#W %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport: ignored. Will retry Registration."
```
