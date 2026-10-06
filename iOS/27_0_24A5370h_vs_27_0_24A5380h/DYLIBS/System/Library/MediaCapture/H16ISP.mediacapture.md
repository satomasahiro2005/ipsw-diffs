## H16ISP.mediacapture

> `/System/Library/MediaCapture/H16ISP.mediacapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d3150` | `0x1d31ec` | **`+0x9c`** |
| `__AUTH_CONST.__const` | `0x2dc0` | `0x2e38` | **`+0x78`** |
| `__TEXT.__const` | `0x2f1c8` | `0x2f208` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1dc09` | `0x1dbe4` | **`-0x25`** |
| `__DATA.__bss` | `0x139` | `0x121` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `0x998` | `0x9a8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x19a11` | `0x19a20` | **`+0xf`** |
| `__TEXT.__gcc_except_tab` | `0x63d8` | `0x63e4` | **`+0xc`** |
| `__DATA_DIRTY.__data` | `0x210` | `0x218` | **`+0x8`** |
| `__DATA.__common` | `0x34` | `0x30` | **`-0x4`** |

### Other Changes

```diff

-6.12.2.0.0
+6.14.1.0.0

-  Functions: 5946
-  Symbols:   8225
-  CStrings:  6405
+  Functions: 5952
+  Symbols:   8237
+  CStrings:  6407
Symbols:
+ GCC_except_table40
+ __ZN6H16ISP21H16ISPJasperDepthNode18prepareForTeardownEv
+ __ZN6H16ISP33H16ISPGraphExclavePostProcessNode14runPostProcessEj
+ __ZN6H16ISP33H16ISPGraphExclavePostProcessNode19onMessageProcessingEPNS_24H16ISPFilterGraphMessageE
+ __ZN6H16ISP33H16ISPGraphExclavePostProcessNodeC1EPNS_12H16ISPDeviceEj
+ __ZN6H16ISP33H16ISPGraphExclavePostProcessNodeC2EPNS_12H16ISPDeviceEj
+ __ZN6H16ISP33H16ISPGraphExclavePostProcessNodeD0Ev
+ __ZN6H16ISP33H16ISPGraphExclavePostProcessNodeD1Ev
+ __ZN6H16ISP33H16ISPGraphExclavePostProcessNodeD2Ev
+ __ZTIN6H16ISP33H16ISPGraphExclavePostProcessNodeE
+ __ZTSN6H16ISP33H16ISPGraphExclavePostProcessNodeE
+ __ZTVN6H16ISP33H16ISPGraphExclavePostProcessNodeE
+ ____ZN6H16ISP21H16ISPJasperDepthNode18prepareForTeardownEv_block_invoke
+ ___block_descriptor_104_e5_v8?0l
- ____ZN6H16ISP21H16ISPJasperDepthNode12onDeactivateEv_block_invoke
- ___block_descriptor_48_e5_v8?0l
CStrings:
+ "%s - Failed to run post process: err=%d\n"
+ "%s - post process run succeeded ch=%u reqid=0x%08x\n"
+ "%s - running post process ch=%u reqid=0x%08x\n"
+ "runPostProcess"
- "[Exclaves]: H16ISPGraphExclaveISPManagerNode::%s EK RGB ISP Manager POST PROCESS RunKit failed, ret=%d\n"
- "[Exclaves]: ISP POST PROCESS IDL Success: channel=%u, requestid=0x%08X\n"
```
