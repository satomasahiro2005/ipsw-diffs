## securepairingd

> `/usr/libexec/securepairingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x45bb4` | `0x467d4` | **`+0xc20`** |
| `__TEXT.__eh_frame` | `0x2b00` | `0x2b58` | **`+0x58`** |
| `__TEXT.__cstring` | `0xf67` | `0xf90` | **`+0x29`** |
| `__DATA_CONST.__got` | `0x2c8` | `0x2e0` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x16f4` | `0x170c` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x1710` | `0x1700` | **`-0x10`** |
| `__TEXT.__const` | `0x7798` | `0x7788` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0x814` | `0x824` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x166f` | `0x167f` | **`+0x10`** |
| `__DATA.__data` | `0x304a` | `0x3052` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xb90` | `0xb88` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x3c8` | `0x3d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1508` | `0x1510` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-58.0.0.0.0
+59.0.0.0.0

-  Functions: 1754
-  Symbols:   567
+  Functions: 1759
+  Symbols:   570
Symbols:
+ _$s9Tightbeam0A7MessageV4sizeySixSo10tb_error_taYKAA0A9EncodableRzlFZ
+ _$ss8DurationVMn
+ _$ss8DurationVN
+ _$ss8DurationVSEsWP
+ _$ss8DurationVSesWP
+ _swift_unexpectedError
- _$s9Tightbeam0A7DecoderV6decode2asS2bm_tF
- _$s9Tightbeam0A7DecoderV6decode2ass6UInt64VAGm_tF
- _$s9Tightbeam0A7MessageV4sizeySixAA0A9EncodableRzlFZ
CStrings:
+ "Invalid key value while decoding result type for exportPairingRecords"
+ "Invalid key value while decoding result type for isPaired"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
```
