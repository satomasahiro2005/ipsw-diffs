## ContactsButtonXPCService

> `/System/Library/Frameworks/ContactsUI.framework/XPCServices/ContactsButtonXPCService.xpc/ContactsButtonXPCService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1a634` | `0x18cb0` | **`-0x1984`** |
| `__TEXT.__swift5_typeref` | `0x17f7` | `0x15b5` | **`-0x242`** |
| `__TEXT.__objc_stubs` | `0xbe0` | `0xaa0` | **`-0x140`** |
| `__TEXT.__auth_stubs` | `0x13f0` | `0x1330` | **`-0xc0`** |
| `__TEXT.__objc_methname` | `0x1051` | `0xfa1` | **`-0xb0`** |
| `__TEXT.__cstring` | `0x834` | `0x7b4` | **`-0x80`** |
| `__TEXT.__eh_frame` | `0x410` | `0x398` | **`-0x78`** |
| `__TEXT.__oslogstring` | `0x1517` | `0x14a7` | **`-0x70`** |
| `__DATA_CONST.__auth_got` | `0xa00` | `0x9a0` | **`-0x60`** |
| `__DATA.__objc_selrefs` | `0x428` | `0x3d8` | **`-0x50`** |
| `__DATA.__objc_const` | `0xbc8` | `0xc08` | **`+0x40`** |
| `__DATA.__objc_data` | `0x8a0` | `0x8e0` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x808` | `0x838` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x428` | `0x3f8` | **`-0x30`** |
| `__DATA.__data` | `0xb80` | `0xb60` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x378` | `0x358` | **`-0x20`** |
| `__TEXT.__const` | `0xbe0` | `0xc00` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x503` | `0x523` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x198` | `0x1b0` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x480` | `0x498` | **`+0x18`** |
| `__DATA.__bss` | `0x5a8` | `0x5b8` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x320` | `0x330` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x5ca` | `0x5ba` | **`-0x10`** |
| `__DATA.__common` | `0xc0` | `0xb8` | **`-0x8`** |
| `__TEXT.__swift_as_cont` | `0xc` | `0x10` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x10` | `0x14` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1461.100.1.0.0
+1463.200.41.0.0

-  Functions: 330
-  Symbols:   229
-  CStrings:  376
+  Functions: 322
+  Symbols:   221
+  CStrings:  361
Symbols:
- _OBJC_CLASS_$_CNAvatarImageRenderer
- _OBJC_CLASS_$_CNAvatarImageRenderingScope
- _OBJC_CLASS_$_NSPersonNameComponentsFormatter
- _OBJC_CLASS_$_UIScreen
- _UIImagePNGRepresentation
- _swift_retain_n
- _swift_retain_x22
- _swift_retain_x25
CStrings:
+ "#ContactsButton ImageRenderer returned nil for candidate '%s' at width %f"
+ "#ContactsButton computeUniformHeight produced 0 — all renders failed, uniform sizing compromised"
+ "Contradictory frame constraints specified."
+ "heightCandidates"
+ "initWithFloat:"
+ "minimumHeight"
- "#ContactsButton had contacts in it, but is somehow null??"
- "#ContactsButton many matches, first one is nil? %s"
- "#ContactsButton two matches, but one was missing a name? first %s  second %s"
- "#ContactsButton we have exactly one match, but unexpectedly the only item is nil"
- "MANY_MATCHES_BOTTOM_TEXT"
- "RIGHT_SIDE_TEXT_ADD"
- "RIGHT_SIDE_TEXT_VIEW"
- "THREE_TO_NINE_MATCHES_BOTTOM_TEXT"
- "TWO_MATCHES_BOTTOM_TEXT"
- "familyName"
- "givenName"
- "imageDataAvailable"
- "localizedStringFromPersonNameComponents:style:options:"
- "mainScreen"
- "phoneNumbers"
- "renderMonogramForString:scope:imageHandler:"
- "scale"
- "scopeWithPointSize:scale:rightToLeft:style:"
- "stringValue"
- "thumbnailImageData"
- "v16@?0@\"UIImage\"8"
```
