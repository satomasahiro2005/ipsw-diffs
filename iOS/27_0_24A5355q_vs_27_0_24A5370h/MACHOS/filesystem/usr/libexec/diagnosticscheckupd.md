## diagnosticscheckupd

> `/usr/libexec/diagnosticscheckupd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x488d0` | `0x48e00` | **`+0x530`** |
| `__DATA.__objc_const` | `0xe088` | `0xe1f0` | **`+0x168`** |
| `__TEXT.__objc_stubs` | `0x5a80` | `0x5b20` | **`+0xa0`** |
| `__TEXT.__objc_methname` | `0x810e` | `0x816e` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x2e88` | `0x2ed8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x3784` | `0x37cc` | **`+0x48`** |
| `__TEXT.__cstring` | `0x2f59` | `0x2f29` | **`-0x30`** |
| `__DATA.__objc_data` | `0x1b50` | `0x1b78` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x16a0` | `0x1680` | **`-0x20`** |
| `__TEXT.__constg_swiftt` | `0x1514` | `0x1534` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x144d` | `0x146d` | **`+0x20`** |
| `__DATA_CONST.__objc_intobj` | `0xa38` | `0xa20` | **`-0x18`** |
| `__DATA.__data` | `0x27d0` | `0x27e0` | **`+0x10`** |
| `__TEXT.__objc_classname` | `0xba2` | `0xbb2` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x266b` | `0x267b` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x52c` | `0x53c` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xde4` | `0xdf0` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0xbe7` | `0xbf3` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x1dd8` | `0x1de0` | **`+0x8`** |
| `__DATA_CONST.__objc_arraydata` | `0x2c0` | `0x2b8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x12f8` | `0x12f0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
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

-1351.0.0.0.0
+1369.0.0.0.0

-  Functions: 1824
+  Functions: 1830

-  CStrings:  2369
+  CStrings:  2371
CStrings:
+ "@?24@0:8@?16"
+ "completionReenablingButtonEvents:"
+ "pendingPresentCompletion"
+ "setDiagnosticsAnimationState:"
- "com.apple.Diagnostics.DKViewControllerPresented"
- "testViewPresented:"
```
