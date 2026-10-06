## softposreaderd

> `/usr/libexec/softposreaderd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41de1c` | `0x4236c4` | **`+0x58a8`** |
| `__TEXT.__oslogstring` | `0xcb7e` | `0xce1e` | **`+0x2a0`** |
| `__TEXT.__eh_frame` | `0xc924` | `0xcab4` | **`+0x190`** |
| `__TEXT.__cstring` | `0x1187b` | `0x119bb` | **`+0x140`** |
| `__DATA_CONST.__const` | `0x181e0` | `0x18280` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x4dc0` | `0x4e48` | **`+0x88`** |
| `__DATA.__data` | `0xc788` | `0xc7e8` | **`+0x60`** |
| `__DATA.__objc_data` | `0x21a8` | `0x21f8` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x4230` | `0x4280` | **`+0x50`** |
| `__TEXT.__const` | `0x882d0` | `0x88320` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x428d` | `0x42dd` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x7910` | `0x794c` | **`+0x3c`** |
| `__DATA.__common` | `0x898` | `0x8c0` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x2120` | `0x2148` | **`+0x28`** |
| `__DATA.__objc_const` | `0x9178` | `0x9190` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x3a0` | `0x3b0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-50.30.0.0.0
+50.31.1.0.0

-  Functions: 6131
-  Symbols:   1683
-  CStrings:  3552
+  Functions: 6165
+  Symbols:   1688
+  CStrings:  3581
Symbols:
+ _$s7SPRCore8LockFileC04withB0yxxyKXEKlFTj
+ _$s7SPRCore8LockFileC10storageURL4nameAC10Foundation0E0V_SStKcfc
+ _$s7SPRCore8LockFileCMa
+ _$sSL2geoiySbx_xtFZTj
+ _objc_retain_x9
+ _swift_dynamicCastClass
- _$sSS7SPRCoreE13isValidBase64SbyF
CStrings:
+ "Deleted persisted BAA identity (key=%s)"
+ "LockFile error: %@"
+ "No cert chain in openSession response — cached HPKE cert still valid"
+ "No value found for key: "
+ "Open session attempt %ld of %ld failed, retrying"
+ "Persisted new BAA identity, leaf fingerprint=%s"
+ "Stored UnifiedReader cert chain successfully"
+ "baaReMinted"
+ "begin SE manager session acquire"
+ "begin SE manager session acquire (install)"
+ "begin cert verify"
+ "begin install scripts"
+ "begin open session HTTP"
+ "certVerifyTime"
+ "end SE manager session acquire"
+ "end SE manager session acquire (install)"
+ "end cert verify"
+ "end install scripts"
+ "end open session HTTP"
+ "eventsPerBatch"
+ "installScriptsTime"
+ "lastReMintCompletedAt"
+ "lockFile"
+ "openSessionHTTPTime"
+ "seManagerSessionAcquireTime"
+ "unified_reader_cert_verify"
+ "unified_reader_install_scripts"
+ "unified_reader_open_session_http"
+ "unified_reader_se_manager_session_acquire"
```
