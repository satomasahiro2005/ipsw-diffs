## safetyalertsd

> `/usr/libexec/safetyalertsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfe1a8` | `0xfec18` | **`+0xa70`** |
| `__TEXT.__oslogstring` | `0x4359a` | `0x439b2` | **`+0x418`** |
| `__TEXT.__gcc_except_tab` | `0xef60` | `0xf034` | **`+0xd4`** |
| `__DATA_CONST.__cfstring` | `0x72c0` | `0x7300` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x4408` | `0x4448` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x89b8` | `0x8988` | **`-0x30`** |
| `__TEXT.__objc_stubs` | `0x3760` | `0x3780` | **`+0x20`** |
| `__TEXT.__cstring` | `0x7a5a` | `0x7a74` | **`+0x1a`** |
| `__TEXT.__auth_stubs` | `0x10b0` | `0x10c0` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x3e58` | `0x3e67` | **`+0xf`** |
| `__DATA.__objc_selrefs` | `0x1260` | `0x1268` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x868` | `0x870` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-70.0.20.0.0
+70.0.21.0.0

-  Functions: 3605
-  Symbols:   469
-  CStrings:  5108
+  Functions: 3611
+  Symbols:   470
+  CStrings:  5119
Symbols:
+ __ZNKSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE4findEcm
CStrings:
+ ".."
+ "pathComponents"
+ "{\"msg%{public}.0s\":\"#aa,downloadCodebook,unsafe codebook file name rejected\", \"codebookFileName\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#md,downloadManifest,unsafe manifest file name rejected\", \"id\":%{private, location:escape_only}s, \"fFileName\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#rm,#warning,downloadManifest,unsafe manifest file name rejected\", \"efficacyStr\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#sa_util,safePath,rejected current-dir component\", \"path\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#sa_util,safePath,rejected embedded null byte\", \"path\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#sa_util,safePath,rejected invalid utf8\", \"path\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#sa_util,safePath,rejected parent traversal\", \"path\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#sa_util,safePath,rejected trailing slash\", \"path\":%{private, location:escape_only}s}"
+ "{\"msg%{public}.0s\":\"#sapref,customerBuildGating\", \"active\":%{private}hhd}"
```
