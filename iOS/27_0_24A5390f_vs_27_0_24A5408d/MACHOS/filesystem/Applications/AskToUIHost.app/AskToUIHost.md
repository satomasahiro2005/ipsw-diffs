## AskToUIHost

> `/Applications/AskToUIHost.app/AskToUIHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a38` | `0x2be4` | **`+0x1ac`** |
| `__DATA.__data` | `0x338` | `0x348` | **`+0x10`** |
| `__TEXT.__const` | `0x164` | `0x174` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x1ac` | `0x1bc` | **`+0x10`** |
| `__TEXT.__eh_frame` | `0x90` | `0x98` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x152` | `0x15a` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x100` | `0x108` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-93.0.0.0.0
+96.0.0.0.0

-  Functions: 44
+  Functions: 45
Symbols:
+ _$s15AAAFoundationUI30AAFExtensionHostViewControllerC7sceneID14extensionPoint0I16BundleIdentifier7context10resultType12dismissBlockACyxq_GSS_AA015AAFAppExtensionJ0_pSSxq_myq_Sg_s5Error_pSgtYactcfC
+ _$s7AskToUI0aB19ViewExtensionResultOMa
+ _$s7AskToUI0aB19ViewExtensionResultOMn
+ _$sSS10describingSSx_tclufC
+ _swift_release_x24
+ _swift_release_x28
- _$s15AAAFoundationUI30AAFExtensionHostViewControllerC7sceneID14extensionPoint0I16BundleIdentifier7context12dismissBlockACyxs5NeverOGSS_AA015AAFAppExtensionJ0_pSSxyAJSg_s5Error_pSgtYactcAJRs_rlufC
- _$ss5NeverOMn
- _objc_release_x27
- _objc_release_x28
- _swift_release_x21
- _swift_release_x23
CStrings:
+ "AskToViewExtension dismissed with result: %s"
- "AskToViewExtension dismissed"
```
