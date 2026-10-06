## com.apple.Photos.CPLDiagnose

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/XPCServices/com.apple.Photos.CPLDiagnose.xpc/com.apple.Photos.CPLDiagnose`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e044` | `0x1e17c` | **`+0x138`** |
| `__DATA_CONST.__cfstring` | `0x61c0` | `0x6260` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x6f3a` | `0x6fc7` | **`+0x8d`** |
| `__DATA.__objc_const` | `0x2b40` | `0x2b60` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4320` | `0x4300` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x1f30` | `0x1f40` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1448` | `0x1440` | **`-0x8`** |
| `__TEXT.__objc_methname` | `0x4e80` | `0x4e85` | **`+0x5`** |
| `__DATA.__objc_ivar` | `0x20c` | `0x210` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-912.0.235.0.0
+916.40.110.0.0

-  Functions: 702
+  Functions: 703

-  CStrings:  2016
+  CStrings:  2021
CStrings:
+ "-z"
+ "Getting state capture dictionary"
+ "[-o <outputfile>] [-l <librarypath>] [-s] [-S] [-t] [-d|-D] [-O] [-f <feature>] [-a <annotation>] [-z]%@%@"
+ "_forceTgzArchive"
+ "assetsd-statecapture.txt"
+ "force the legacy tgz archive format instead of AppleArchive."
+ "o:l:tdDa:f:LcsSOmPir:nb:z"
+ "statecapture"
- "[-o <outputfile>] [-l <librarypath>] [-s] [-S] [-t] [-d|-D] [-O] [-f <feature>] [-a <annotation>]%@%@"
- "boolForKey:"
- "o:l:tdDa:f:LcsSOmPir:nb:"
```
