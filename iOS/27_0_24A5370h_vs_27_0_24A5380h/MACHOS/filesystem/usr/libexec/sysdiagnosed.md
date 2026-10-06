## sysdiagnosed

> `/usr/libexec/sysdiagnosed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60f60` | `0x61128` | **`+0x1c8`** |
| `__TEXT.__objc_methname` | `0xa602` | `0xa737` | **`+0x135`** |
| `__DATA_CONST.__cfstring` | `0x11540` | `0x11600` | **`+0xc0`** |
| `__TEXT.__objc_stubs` | `0x9320` | `0x93c0` | **`+0xa0`** |
| `__DATA_CONST.__got` | `0x3d8` | `0x470` | **`+0x98`** |
| `__TEXT.__cstring` | `0x10bd5` | `0x10c36` | **`+0x61`** |
| `__TEXT.__objc_methlist` | `0x3f1c` | `0x3f54` | **`+0x38`** |
| `__DATA.__objc_const` | `0x5388` | `0x53b8` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x16d0` | `0x1700` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x17f5` | `0x1825` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x29c8` | `0x29f0` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x13e8` | `0x13c0` | **`-0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0xe90` | `0xeb0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xb78` | `0xb90` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0x13f8` | `0x1410` | **`+0x18`** |
| `__TEXT.__oslogstring` | `0x80fa` | `0x8111` | **`+0x17`** |
| `__DATA.__objc_ivar` | `0x474` | `0x478` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0xdac` | `0xda8` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1593.0.0.0.0
+1598.0.0.0.0

-  Functions: 1767
-  Symbols:   502
-  CStrings:  4839
+  Functions: 1773
+  Symbols:   505
+  CStrings:  4854
Symbols:
+ _container_copy_sandbox_token
+ _sandbox_extension_consume
+ _sandbox_extension_release
CStrings:
+ "-O"
+ "/usr/local/bin/anetest"
+ "<TMPOUTPUTDIR>/ane.anetrace"
+ "@48@0:8@16@24@32@?40"
+ "@64@0:8@16@24@32@40@48@?56"
+ "ANETraceBuffer"
+ "Could not consume sandbox extension for identifier %@ : %m"
+ "T@?,C,N,V_completionHandler"
+ "_completionHandler"
+ "anetest_stdout.txt"
+ "completionHandler"
+ "getBackgroundPowerLogContainer"
+ "getSearchdiagnoseContainer"
+ "getSimplePathArrayContainer:withContainerName:andDestination:completionHandler:"
+ "getSimplePathArrayContainer:withContainerName:andDestination:withOffsets:sizes:completionHandler:"
+ "logs/ANE"
+ "setCompletionHandler:"
- "Received canceling, ending browsing"
- "countDisplays"
```
