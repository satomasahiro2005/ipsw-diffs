## Fitness

> `/private/var/staged_system_apps/Fitness.app/Fitness`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7557b0` | `0x75867c` | **`+0x2ecc`** |
| `__DATA.__bss` | `0x32b68` | `0x32e68` | **`+0x300`** |
| `__TEXT.__const` | `0x40944` | `0x40b64` | **`+0x220`** |
| `__DATA.__data` | `0x27e60` | `0x27f90` | **`+0x130`** |
| `__DATA.__objc_const` | `0x3ed08` | `0x3ee18` | **`+0x110`** |
| `__TEXT.__auth_stubs` | `0xea80` | `0xeb20` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x174f4` | `0x1758c` | **`+0x98`** |
| `__DATA.__objc_data` | `0x1b7a8` | `0x1b838` | **`+0x90`** |
| `__TEXT.__objc_stubs` | `0x1b900` | `0x1b980` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x32c98` | `0x32d10` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x1128c` | `0x11300` | **`+0x74`** |
| `__TEXT.__oslogstring` | `0xc49c` | `0xc50c` | **`+0x70`** |
| `__TEXT.__objc_methname` | `0x308d6` | `0x30936` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x82f06` | `0x82f64` | **`+0x5e`** |
| `__DATA_CONST.__auth_got` | `0x7550` | `0x75a0` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x15268` | `0x152b0` | **`+0x48`** |
| `__TEXT.__cstring` | `0x1930b` | `0x1933b` | **`+0x30`** |
| `__TEXT.__gcc_except_tab` | `0x1b78` | `0x1ba8` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x3a48` | `0x3a78` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x15dd3` | `0x15e03` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x8fc8` | `0x8fe8` | **`+0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x54f8` | `0x5518` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x636a` | `0x638a` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x1a04` | `0x1a1c` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x550` | `0x564` | **`+0x14`** |
| `__DATA_CONST.__got` | `0x4078` | `0x4088` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xeb0` | `0xeb8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xfd0` | `0xfd8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.1.35.0.0
+2027.1.36.0.0

-  Functions: 30365
-  Symbols:   6890
-  CStrings:  11546
+  Functions: 30390
+  Symbols:   6902
+  CStrings:  11557
Symbols:
+ _$s10Foundation12CharacterSetV11whitespacesACvgZ
+ _$s10Foundation12CharacterSetV13alphanumericsACvgZ
+ _$s10Foundation12CharacterSetV5unionyA2CF
+ _$s10Foundation12CharacterSetV8invertedACvg
+ _$s10Foundation17URLResourceValuesV12creationDateAA0E0VSgvg
+ _$s10Foundation17URLResourceValuesVMa
+ _$s10Foundation3URLV13DirectoryHintO03notC0yA2EmFWC
+ _$s10Foundation3URLV14resourceValues7forKeysAA011URLResourceD0VShySo16NSURLResourceKeyaG_tKF
+ _$s10Foundation3URLV4pathSSvg
+ _$s10Foundation4DataV5write2to7optionsyAA3URLV_So20NSDataWritingOptionsVtKF
+ _$sSy10FoundationE10components11separatedBySaySSGAA12CharacterSetV_tF
+ _NSURLCreationDateKey
CStrings:
+ "Could not write the share card to %s: %s"
+ "Share card produced no PNG data; sharing it in memory instead"
+ "_TtC10FitnessApp13ShareCardItem"
+ "com.apple.journal.JournalShareExtension"
+ "contentsOfDirectoryAtURL:includingPropertiesForKeys:options:error:"
+ "createDirectoryAtURL:withIntermediateDirectories:attributes:error:"
+ "encoded"
+ "fileURL"
+ "removeItemAtURL:error:"
+ "shareCard"
+ "temporaryDirectory"
```
