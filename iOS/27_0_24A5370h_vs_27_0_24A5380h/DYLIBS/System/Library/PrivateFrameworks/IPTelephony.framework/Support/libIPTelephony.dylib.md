## libIPTelephony.dylib

> `/System/Library/PrivateFrameworks/IPTelephony.framework/Support/libIPTelephony.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4aabd0` | `0x4aafb0` | **`+0x3e0`** |
| `__TEXT.__oslogstring` | `0x4caba` | `0x4cd41` | **`+0x287`** |
| `__DATA.__bss` | `0x144` | `0x14` | **`-0x130`** |
| `__DATA_DIRTY.__bss` | `0xc78` | `0xda8` | **`+0x130`** |
| `__DATA.__data` | `0x378` | `0x268` | **`-0x110`** |
| `__DATA_DIRTY.__data` | `0x1c0` | `0x2d0` | **`+0x110`** |
| `__DATA.__common` | `0x108` | `0xa8` | **`-0x60`** |
| `__TEXT.__cstring` | `0x140b5` | `0x1410f` | **`+0x5a`** |
| `__DATA_DIRTY.__common` | `0x888` | `0x8e0` | **`+0x58`** |
| `__TEXT.__gcc_except_tab` | `0x41e34` | `0x41e80` | **`+0x4c`** |
| `__DATA_CONST.__const` | `0x3da8` | `0x3d98` | **`-0x10`** |
| `__TEXT.__const` | `0x1f83c` | `0x1f84c` | **`+0x10`** |

### Other Changes

```diff

-2756.0.0.0.0
+2761.1.0.0.0

-  CStrings:  8692
+  CStrings:  8705
Symbols:
+ GCC_except_table501
+ GCC_except_table503
+ GCC_except_table505
+ GCC_except_table511
+ GCC_except_table513
+ GCC_except_table515
+ GCC_except_table519
+ GCC_except_table522
+ GCC_except_table524
+ GCC_except_table531
+ GCC_except_table535
+ GCC_except_table537
+ GCC_except_table539
+ GCC_except_table543
+ GCC_except_table547
+ GCC_except_table553
+ GCC_except_table555
+ GCC_except_table565
+ GCC_except_table569
+ __ZN22SipRegistrationMetrics11kReasonNoneE
+ __ZNK8ImsPrefs52SkipReRegisterUponRatChangeWhenThereIsNoConnectivityEv
- GCC_except_table502
- GCC_except_table504
- GCC_except_table508
- GCC_except_table512
- GCC_except_table514
- GCC_except_table517
- GCC_except_table521
- GCC_except_table523
- GCC_except_table526
- GCC_except_table532
- GCC_except_table536
- GCC_except_table538
- GCC_except_table542
- GCC_except_table545
- GCC_except_table552
- GCC_except_table554
- GCC_except_table564
- GCC_except_table568
- __ZN12_GLOBAL__N_110ATM_REG_REE
- __ZN12_GLOBAL__N_119ATM_CALL_End_NormalE
- __ZN3xpceqIPKcEEbRKNS_4dict12object_proxyERKT_
CStrings:
+ "#D %{private, mask.hash}sDon't have a complete message yet datalen=%{public}zu bufSize=%{public}zu"
+ "#D %{private, mask.hash}sSuccess SIP %{public}s headerCount=%{public}zu bodyLength=%{public}zu"
+ "#E %{private, mask.hash}sDropping SIP %{public}s"
+ "#E %{private, mask.hash}sno sipstack %{public}s"
+ "#E %{private, mask.hash}sno sipstack: dropping SIP %{public}s"
+ "#E Dropping SIP %{public}s"
+ "#E Invalid SDP: %{public}s"
+ "#W %{private, mask.hash}sSuccess but no sip message"
+ "%{private, mask.hash}sSipTcpConnection::processDataFromSocket hasPartial=%{public,bool}d crlfInFlight=%{public,bool}d len=%{public}zu"
+ "%{private, mask.hash}sWill skip reregister due to no connectivity"
+ "%{private, mask.hash}srequesting abc snapshot for CT not recognizing chatbot with subdomain"
+ "CT failed to recognize chatbot"
+ "RCSChatbot"
+ "SkipReRegisterUponRatChangeWhenThereIsNoConnectivity"
- "%{private, mask.hash}sSipTcpConnection::processDataFromSocket hasPartial=%{bool}d crlfInFlight=%{bool}d"
```
