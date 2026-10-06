## mDNSResponder

> `/usr/sbin/mDNSResponder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10abd0` | `0x10abd4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ _AdvertiseInterface : 1876 -> 1880
~ _mDNS_Execute : 25424 -> 25440
~ _putDomainNameAsLabels : 524 -> 528
~ _GetLargeResourceRecord : 1104 -> 1108
~ _SendResponses : 7588 -> 7592
~ _mDNSCoreReceiveNoUnicastAnswers : 18636 -> 18600
~ _GetRRDisplayString_rdb : 2864 -> 2868
~ _DNSMessageExtractRData : 1416 -> 1420
```
