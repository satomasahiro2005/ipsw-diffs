## CFNetwork

> `/System/Library/Frameworks/CFNetwork.framework/CFNetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25639c` | `0x2563ec` | **`+0x50`** |
| `__DATA_DIRTY.__bss` | `0x9a8` | `0x9d0` | **`+0x28`** |
| `__DATA.__bss` | `0xd70` | `0xd50` | **`-0x20`** |

### Other Changes

```diff

-3890.100.1.0.0
+3892.100.1.0.0
Functions:
~ __ZN19URLConnectionLoader29ensureLoaderHasProtocolNoLockEP12NSURLRequest : 1088 -> 1104
~ __ZN19URLConnectionLoader20scheduleTimeoutTimerEv : 188 -> 200
~ __ZN27URLConnectionLoader_ClassicC1EP26InterfaceRequiredForLoaderRKN19URLConnectionLoader11ConfigFlagsEP19__NSURLSessionLocalPv : 396 -> 400
~ __ZN19URLConnectionLoader15touchConnectionEv : 464 -> 480
~ ____ZN19URLConnectionLoader15invalidateAsyncENSt3__110shared_ptrI23CoreSchedulingSetOneOffEE_block_invoke : 536 -> 552
~ __ZN19URLConnectionLoader41protocolDidReceiveAuthenticationChallengeEP19_CFURLAuthChallenge : 960 -> 976
```
