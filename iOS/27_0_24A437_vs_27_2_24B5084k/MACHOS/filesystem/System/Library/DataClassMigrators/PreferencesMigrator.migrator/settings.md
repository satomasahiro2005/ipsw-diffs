## settings

> `/System/Library/DataClassMigrators/PreferencesMigrator.migrator/settings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17524` | `0x1ab24` | **`+0x3600`** |
| `__DATA.__bss` | `0x3a00` | `0x3e80` | **`+0x480`** |
| `__TEXT.__const` | `0x1f70` | `0x21e0` | **`+0x270`** |
| `__TEXT.__eh_frame` | `0x94c` | `0xb44` | **`+0x1f8`** |
| `__TEXT.__auth_stubs` | `0xd30` | `0xe60` | **`+0x130`** |
| `__DATA.__data` | `0xb40` | `0xc48` | **`+0x108`** |
| `__TEXT.__unwind_info` | `0x728` | `0x7e0` | **`+0xb8`** |
| `__DATA_CONST.__auth_got` | `0x6a0` | `0x738` | **`+0x98`** |
| `__DATA_CONST.__const` | `0xb30` | `0xbc0` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x65c` | `0x6e2` | **`+0x86`** |
| `__TEXT.__cstring` | `0x1524` | `0x15a4` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x3ec` | `0x438` | **`+0x4c`** |
| `__TEXT.__swift5_fieldmd` | `0x448` | `0x480` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x1d0` | `0x1f4` | **`+0x24`** |
| `__DATA_CONST.__auth_ptr` | `0x328` | `0x348` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x569` | `0x589` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x2a0` | `0x2b8` | **`+0x18`** |
| `__TEXT.__swift_as_cont` | `0x4c` | `0x58` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x44` | `0x4c` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x3c` | `0x44` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`

### Other Changes

```diff

-2027.0.10.401.0
+2027.1.4.0.0

-  Functions: 529
-  Symbols:   409
-  CStrings:  110
+  Functions: 576
+  Symbols:   433
+  CStrings:  111
Symbols:
+ _$s10Foundation11JSONEncoderC16OutputFormattingV10sortedKeysAEvgZ
+ _$s10Foundation11JSONEncoderC16OutputFormattingV13prettyPrintedAEvgZ
+ _$s10Foundation11JSONEncoderC16OutputFormattingVMa
+ _$s10Foundation11JSONEncoderC16OutputFormattingVMn
+ _$s10Foundation11JSONEncoderC16OutputFormattingVs10SetAlgebraAAMc
+ _$s10Foundation11JSONEncoderC16outputFormattingAC06OutputD0VvsTj
+ _$s10Foundation13__DataStorageC6_bytesSvSgvg
+ _$s10Foundation13__DataStorageC7_lengthSivg
+ _$s10Foundation13__DataStorageC7_offsetSivg
+ _$s10Foundation4DataV13_copyContents12initializingAC8IteratorV_SitSrys5UInt8VG_tF
+ _$s10Foundation4DataV8IteratorVMa
+ _$s10Foundation4DataVN
+ _$s12SettingsHost0A16SearchResultItemV16uniqueIdentifierSSvg
+ _$sSS18_fromUTF8RepairingySS6result_Sb11repairsMadetSRys5UInt8VGFZ
+ _$sSo11CSUserQueryC12SettingsHostE08allItemsB02inABSaySSG_tFZ
+ _$ss10SetAlgebraPyxqd__ncSTRd__7ElementQyd__ACRtzlufCTj
+ _$ss15ContiguousArrayV28_allocateBufferUninitialized15minimumCapacitys01_abD0VyxGSi_tFZ
+ _$ss19_HasContiguousBytesMp
+ _$ss19_HasContiguousBytesP010withUnsafeC0yqd__qd__SWKXEKlFTj
+ _$ss19_HasContiguousBytesP09_providesbC6NoCopySbvgTj
+ _$ss22_minimumMergeRunLengthyS2iF
+ _$ss5UInt8VMn
+ _memcpy
+ _swift_dynamicCast
CStrings:
+ "Dump the entire search index of a given Settings application as a stable, sorted JSON array (for diffing two builds)."
```
