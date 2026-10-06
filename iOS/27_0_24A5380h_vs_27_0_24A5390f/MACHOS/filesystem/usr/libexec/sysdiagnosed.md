## sysdiagnosed

> `/usr/libexec/sysdiagnosed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x61128` | `0x6132c` | **`+0x204`** |
| `__DATA_CONST.__cfstring` | `0x11600` | `0x11720` | **`+0x120`** |
| `__TEXT.__cstring` | `0x10c36` | `0x10cc9` | **`+0x93`** |
| `__TEXT.__objc_methname` | `0xa737` | `0xa78d` | **`+0x56`** |
| `__TEXT.__objc_stubs` | `0x93c0` | `0x9400` | **`+0x40`** |
| `__DATA_CONST.__objc_arrayobj` | `0x1410` | `0x1428` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x3f54` | `0x3f6c` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0x1825` | `0x183c` | **`+0x17`** |
| `__DATA.__objc_selrefs` | `0x29f0` | `0x2a00` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0xeb0` | `0xec0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1190` | `0x1198` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1598.0.0.0.0
+1598.0.4.0.0

-  Functions: 1773
+  Functions: 1775

-  CStrings:  4854
+  CStrings:  4866
CStrings:
+ "--report"
+ "/usr/local/bin/switchcl"
+ "@48@0:8@16@24I32I36@40"
+ "ContainerManager"
+ "OR_flags"
+ "Switch"
+ "TASK_TYPE_CONTAINER_MANAGER"
+ "getSwitchContainer"
+ "logs/ContainerManager"
+ "logs/Switch"
+ "switch_report.json"
+ "taskWithCommand:arguments:inBootstrapDomainOfUID:asUID:outputFile:"
```
