## BackupAgent2

> `/usr/libexec/BackupAgent2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x907ec` | `0x90c98` | **`+0x4ac`** |
| `__TEXT.__cstring` | `0x18eed` | `0x18fb5` | **`+0xc8`** |
| `__TEXT.__oslogstring` | `0xdeda` | `0xdf81` | **`+0xa7`** |
| `__TEXT.__objc_methname` | `0xe7e3` | `0xe80d` | **`+0x2a`** |
| `__DATA_CONST.__cfstring` | `0x94e0` | `0x9500` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1418` | `0x1438` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0xc9a0` | `0xc9c0` | **`+0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0xd8` | `0xf0` | **`+0x18`** |
| `__DATA.__bss` | `0x220` | `0x230` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x110` | `0x120` | **`+0x10`** |
| `__TEXT.__const` | `0x4b8` | `0x4c8` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x2100` | `0x210c` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x1948` | `0x1940` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3038.0.0.0.0
+3039.0.1.0.0

-  Functions: 2452
+  Functions: 2455

-  CStrings:  5759
+  CStrings:  5763
CStrings:
+ "%@ is a local storage app domain - not removing from the disabled domains list"
+ "%s local files domains \"%{public}@\""
+ "AppDomain-com.apple.DocumentsApp"
+ "Failed to remove incomplete restore directories: %@"
+ "_dependentDomainsForDisabledDomains:"
+ "createIncompleteRestoreDirectoriesWithError:"
+ "removeIncompleteRestoreDirectoriesWithError:"
+ "removeIntermediateRestoreDirectoriesWithError:"
+ "syncDisabledDomainsWithInstalledAppDomains:persona:"
- "_subdomainNamesForAppDomainNames:"
- "_syncDisabledDomainsWithAllInstalledAppDomains:persona:"
- "allDisabledDomainNames"
- "cleanupRestoreDirectoriesWithError:"
- "createRestoreDirectoriesWithError:"
```
