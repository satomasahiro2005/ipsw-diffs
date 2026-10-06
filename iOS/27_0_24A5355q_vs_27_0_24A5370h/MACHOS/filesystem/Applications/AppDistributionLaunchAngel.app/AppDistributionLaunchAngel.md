## AppDistributionLaunchAngel

> `/Applications/AppDistributionLaunchAngel.app/AppDistributionLaunchAngel`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4eeec` | `0x4fc00` | **`+0xd14`** |
| `__TEXT.__oslogstring` | `0x1a62` | `0x1af2` | **`+0x90`** |
| `__TEXT.__eh_frame` | `0x1e50` | `0x1ed0` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x2060` | `0x20d0` | **`+0x70`** |
| `__TEXT.__objc_stubs` | `0x1cc0` | `0x1d20` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x1a78` | `0x1ac8` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x37c9` | `0x3819` | **`+0x50`** |
| `__TEXT.__cstring` | `0x103b` | `0x107b` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1040` | `0x1078` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x1b9e` | `0x1bbe` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xcd0` | `0xce8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x608` | `0x620` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x628` | `0x640` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xf00` | `0xf18` | **`+0x18`** |
| `__DATA.__objc_data` | `0x16a8` | `0x16b8` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0xef4` | `0xf04` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xb90` | `0xb9c` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4.0.30.0.0
+4.0.33.0.0

-  Functions: 1115
-  Symbols:   868
-  CStrings:  907
+  Functions: 1125
+  Symbols:   877
+  CStrings:  914
Symbols:
+ _$s14MarketplaceKit30VirtualMachineUnsupportedAlertO5titleSSvgZ
+ _$s14MarketplaceKit30VirtualMachineUnsupportedAlertO7messageSSvgZ
+ _$s14MarketplaceKit30VirtualMachineUnsupportedAlertO8okButtonSSvgZ
+ _$s14MarketplaceKit33ADDeviceIsRunningInVirtualMachineSbyF
+ _$ss9_typeName_9qualifiedSSypXp_SbtF
+ _OBJC_CLASS_$_UIAlertAction
+ _OBJC_CLASS_$_UIAlertController
+ _swift_release_x9
+ _swift_retain_x26
+ _swift_task_getMainExecutor
- _swift_retain_x23
CStrings:
+ "Incorrect actor executor assumption; Expected same executor as "
+ "[%s] Alternative distribution is unsupported in a virtual machine"
+ "[%s] Install reported a failure; dismissing confirmation sheet"
+ "actionWithTitle:style:handler:"
+ "addAction:"
+ "alertControllerWithTitle:message:preferredStyle:"
+ "v16@?0@\"UIAlertAction\"8"
```
