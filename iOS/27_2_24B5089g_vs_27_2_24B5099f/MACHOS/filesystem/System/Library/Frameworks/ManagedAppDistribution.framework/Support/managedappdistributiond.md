## managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e014c` | `0x6e1098` | **`+0xf4c`** |
| `__TEXT.__oslogstring` | `0x15f02` | `0x16022` | **`+0x120`** |
| `__DATA.__bss` | `0x2ef30` | `0x2efb0` | **`+0x80`** |
| `__DATA_CONST.__const` | `0x2f560` | `0x2f5d0` | **`+0x70`** |
| `__TEXT.__const` | `0x40070` | `0x400e0` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x3a758` | `0x3a770` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x75cc` | `0x75e0` | **`+0x14`** |
| `__DATA.__data` | `0x10f90` | `0x10f80` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x7080` | `0x7090` | **`+0x10`** |
| `__TEXT.__cstring` | `0xfdfd` | `0xfe0d` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x35fc` | `0x3608` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x3850` | `0x3858` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x126b0` | `0x126b8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x19ec` | `0x19f0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0xa7c` | `0xa80` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xc48` | `0xc4c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4.1.11.0.0
+4.1.14.0.0

-  Functions: 16702
+  Functions: 16717

-  CStrings:  4095
+  CStrings:  4098
Symbols:
+ _$s10Foundation4DateV2leoiySbAC_ACtFZ
- _$s10Foundation4DateVSLAAMc
CStrings:
+ "ManagedAppDistribution.AskForException.Prompt.Body.Web.V2"
+ "ManagedAppDistribution.InstallSheet.AppStore.Body.NoLink.V2"
+ "Pending marketplace expiration fired for %s, but it is no longer pending. Ignoring."
+ "Received application unregistered notification for %{public}s (isPlaceholder: %{bool,public}d)"
+ "Skipping cleanup for %{public}s - unregistered notification was for a placeholder"
+ "The information below was provided by the developer."
+ "Your content restrictions are enabled. Updates and purchases in this app will be managed by the developer “@@developer@@”, who provided the information below."
+ "[%@] Client %s not found in registry for registration: %s"
- "ManagedAppDistribution.AskForException.Prompt.Body.Web"
- "ManagedAppDistribution.InstallSheet.AppStore.Body.NoLink"
- "Received application unregistered notification for %{public}s"
- "Verify the information before installing."
- "Your content restrictions are enabled. Updates and purchases in this app will be managed by the developer “@@developer@@”. Verify the information below before installing."
```
