## libSEUpdater.dylib

> `/usr/lib/updaters/libSEUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72608` | `0x72dd0` | **`+0x7c8`** |
| `__TEXT.__const` | `0xa5dc` | `0xaa0c` | **`+0x430`** |
| `__AUTH_CONST.__const` | `0x4588` | `0x4690` | **`+0x108`** |
| `__TEXT.__gcc_except_tab` | `0x857c` | `0x8614` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x1d18` | `0x1d70` | **`+0x58`** |
| `__TEXT.__cstring` | `0x8eab` | `0x8ed8` | **`+0x2d`** |

### Other Changes

```diff

-  Functions: 1577
-  Symbols:   2902
+  Functions: 1591
+  Symbols:   2928
Symbols:
+ GCC_except_table198
+ GCC_except_table199
+ GCC_except_table205
+ GCC_except_table211
+ GCC_except_table212
+ GCC_except_table213
+ GCC_except_table214
+ GCC_except_table228
+ GCC_except_table229
+ GCC_except_table238
+ GCC_except_table239
+ GCC_except_table247
+ GCC_except_table248
+ GCC_except_table253
+ GCC_except_table254
+ __ZN13SERestoreInfo15SN450DeviceInfoC2ERKNS_4BLOBE
+ __ZN13SERestoreInfo15SN450DeviceInfoD0Ev
+ __ZN13SERestoreInfo15SN450DeviceInfoD1Ev
+ __ZN13SEUpdaterUtil17SN450Image4SignerD0Ev
+ __ZN13SEUpdaterUtil17SN450Image4SignerD1Ev
+ __ZNK13SEUpdaterUtil17SN450Image4Signer13getSigningKeyEv
+ __ZNK13SEUpdaterUtil17SN450Image4Signer14getSigningCertEv
+ __ZNK13SEUpdaterUtil17SN450Image4Signer19getSigningAlgorithmEv
+ __ZNSt3__110unique_ptrIN13SEUpdaterUtil17SN450Image4SignerENS_14default_deleteIS2_EEED1B9fqe220106Ev
+ __ZNSt3__115allocate_sharedB9fqe220106IN13SERestoreInfo15SN450DeviceInfoENS_9allocatorIS2_EEJRKNS1_4BLOBEELi0EEENS_10shared_ptrIT_EERKT0_DpOT1_
+ __ZNSt3__120__shared_ptr_emplaceIN13SERestoreInfo15SN450DeviceInfoENS_9allocatorIS2_EEE16__on_zero_sharedEv
+ __ZNSt3__120__shared_ptr_emplaceIN13SERestoreInfo15SN450DeviceInfoENS_9allocatorIS2_EEE21__on_zero_shared_weakEv
+ __ZNSt3__120__shared_ptr_emplaceIN13SERestoreInfo15SN450DeviceInfoENS_9allocatorIS2_EEEC2B9fqe220106IJRKNS1_4BLOBEES4_Li0EEES4_DpOT_
+ __ZNSt3__120__shared_ptr_emplaceIN13SERestoreInfo15SN450DeviceInfoENS_9allocatorIS2_EEED0Ev
+ __ZNSt3__120__shared_ptr_emplaceIN13SERestoreInfo15SN450DeviceInfoENS_9allocatorIS2_EEED1Ev
+ __ZTIN13SERestoreInfo15SN450DeviceInfoE
+ __ZTIN13SEUpdaterUtil17SN450Image4SignerE
+ __ZTINSt3__120__shared_ptr_emplaceIN13SERestoreInfo15SN450DeviceInfoENS_9allocatorIS2_EEEE
+ __ZTSN13SERestoreInfo15SN450DeviceInfoE
+ __ZTSN13SEUpdaterUtil17SN450Image4SignerE
+ __ZTSNSt3__120__shared_ptr_emplaceIN13SERestoreInfo15SN450DeviceInfoENS_9allocatorIS2_EEEE
+ __ZTVN13SERestoreInfo15SN450DeviceInfoE
+ __ZTVN13SEUpdaterUtil17SN450Image4SignerE
+ __ZTVNSt3__120__shared_ptr_emplaceIN13SERestoreInfo15SN450DeviceInfoENS_9allocatorIS2_EEEE
+ __ZZNK13SEUpdaterUtil17SN450Image4Signer13getSigningKeyEvE10signingKey
+ __ZZNK13SEUpdaterUtil17SN450Image4Signer14getSigningCertEvE11signingCert
- GCC_except_table193
- GCC_except_table194
- GCC_except_table195
- GCC_except_table207
- GCC_except_table208
- GCC_except_table209
- GCC_except_table210
- GCC_except_table224
- GCC_except_table225
- GCC_except_table231
- GCC_except_table234
- GCC_except_table240
- GCC_except_table243
- GCC_except_table249
- GCC_except_table250
CStrings:
+ "SN450 detected based on manifest query response\n"
+ "UNDEFINED"
- " beta"
- "DEFINED"
```
