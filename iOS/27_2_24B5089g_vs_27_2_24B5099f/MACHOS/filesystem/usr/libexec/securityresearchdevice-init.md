## securityresearchdevice-init

> `/usr/libexec/securityresearchdevice-init`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21778` | `0x222d8` | **`+0xb60`** |
| `__TEXT.__eh_frame` | `0x2008` | `0x20f0` | **`+0xe8`** |
| `__TEXT.__auth_stubs` | `0x1140` | `0x11a0` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xa2c` | `0xa6c` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x8a8` | `0x8d8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x220` | `0x248` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x830` | `0x850` | **`+0x20`** |
| `__TEXT.__const` | `0x9b8` | `0x9d0` | **`+0x18`** |
| `__DATA.__data` | `0x568` | `0x578` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x554` | `0x544` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x34c` | `0x340` | **`-0xc`** |
| `__TEXT.__swift_as_cont` | `0x19c` | `0x1a4` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0xdc` | `0xe4` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xa0` | `0xa4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-274.40.10.0.0
+274.40.12.0.0

-  Functions: 409
-  Symbols:   395
-  CStrings:  135
+  Functions: 418
+  Symbols:   404
+  CStrings:  136
Symbols:
+ _$s10Foundation21_BridgedStoredNSErrorPAAE4code4CodeQzvg
+ _$s10Foundation8URLErrorV22downloadTaskResumeDataAA0F0VSgvg
+ _$s10Foundation8URLErrorV4CodeV9cancelledAEvgZ
+ _$s10Foundation8URLErrorV4CodeVMa
+ _$s10Foundation8URLErrorV4CodeVSQAAMc
+ _$s10Foundation8URLErrorVAA21_BridgedStoredNSErrorAAMc
+ _$s10Foundation8URLErrorVMa
+ _$sSo12NSURLSessionC10FoundationE8download10resumeFrom8delegateAC3URLV_So13NSURLResponseCtAC4DataV_So0A12TaskDelegate_pSgtYaKF
+ _$sSo12NSURLSessionC10FoundationE8download10resumeFrom8delegateAC3URLV_So13NSURLResponseCtAC4DataV_So0A12TaskDelegate_pSgtYaKFTu
CStrings:
+ "resuming download from prior attempt (%ld-byte resume blob)"
```
