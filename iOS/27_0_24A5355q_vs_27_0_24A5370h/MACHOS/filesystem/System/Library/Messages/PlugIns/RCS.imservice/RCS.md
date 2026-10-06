## RCS

> `/System/Library/Messages/PlugIns/RCS.imservice/RCS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10d684` | `0x10fcc0` | **`+0x263c`** |
| `__TEXT.__oslogstring` | `0x67f8` | `0x69a8` | **`+0x1b0`** |
| `__TEXT.__objc_stubs` | `0x5720` | `0x5800` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x5fc3` | `0x6073` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x4ff0` | `0x5090` | **`+0xa0`** |
| `__TEXT.__const` | `0x6398` | `0x6438` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0xa840` | `0xa8c0` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x1fa0` | `0x1fe0` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x18c0` | `0x18f8` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x980` | `0x9b8` | **`+0x38`** |
| `__TEXT.__swift5_reflstr` | `0x1674` | `0x16a4` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x1a1c` | `0x1a44` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x21cd` | `0x21f3` | **`+0x26`** |
| `__TEXT.__constg_swiftt` | `0x2428` | `0x244c` | **`+0x24`** |
| `__TEXT.__swift5_capture` | `0xc88` | `0xcac` | **`+0x24`** |
| `__DATA_CONST.__auth_got` | `0xfd8` | `0xff8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2883` | `0x28a3` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x9a8` | `0x99c` | **`-0xc`** |
| `__DATA_CONST.__auth_ptr` | `0x1588` | `0x1590` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x3be0` | `0x3bd8` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x1e4` | `0x1e8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x32c` | `0x330` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-1481.100.29.2.9
+1483.100.10.2.4

-  Functions: 3874
-  Symbols:   483
-  CStrings:  1661
+  Functions: 3883
+  Symbols:   490
+  CStrings:  1676
Symbols:
+ _CTRCSVendorReactionTypeIMDisliked
+ _CTRCSVendorReactionTypeIMEmphasized
+ _CTRCSVendorReactionTypeIMLaughed
+ _CTRCSVendorReactionTypeIMLiked
+ _CTRCSVendorReactionTypeIMLoved
+ _CTRCSVendorReactionTypeIMQuestioned
+ _OBJC_CLASS_$_IMClassicTapback
CStrings:
+ "Disposition type %ld is not in allowed set."
+ "No IMAssociatedMessageType for rcsReferenceType %s"
+ "No rcsReferenceType for tapback %s"
+ "Replicating message %s due to Live Photo aux image"
+ "Trying to create reaction metadata for a classic tapback with incorrect associatedMessageType: %lld"
+ "Unhandled addReaction vendorReactionType: %s"
+ "Unhandled removeReaction vendorReactionType: %s"
+ "ctErrorCode"
+ "downgradedFromServiceType"
+ "forceAutoBugCaptureWithDomain:subType:errorPayload:type:context:metadata:"
+ "initWithServiceName:fallbackGUIDs:encrypted:fromIdentifier:"
+ "isAuxImage"
+ "isEncrypted"
+ "rcs.Vendor-Reaction-Type"
+ "setCtErrorCode:"
+ "setCtErrorDomain:"
- "initWithServiceName:fallbackGUIDs:encrypted:"
```
