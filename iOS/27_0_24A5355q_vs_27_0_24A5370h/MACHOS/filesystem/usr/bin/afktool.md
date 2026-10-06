## afktool

> `/usr/bin/afktool`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e50` | `0x7e24` | **`-0x2c`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-736.0.0.502.1
+743.0.0.0.1
Functions:
~ sub_1000016c4 : 3676 -> 3672
~ sub_1000048d8 -> sub_1000048d4 : 996 -> 988
~ sub_10000520c -> sub_100005200 : 1940 -> 1936
~ sub_100006118 -> sub_100006108 : 508 -> 484
~ sub_1000075e4 -> sub_1000075bc : 1056 -> 1052
CStrings:
+ "AppleFirmwareKit ToolvRC_ProjectBuildVersion Jun 16 2026 00:00:47"
- "AppleFirmwareKit ToolvRC_ProjectBuildVersion Jun  3 2026 21:07:34"
```
