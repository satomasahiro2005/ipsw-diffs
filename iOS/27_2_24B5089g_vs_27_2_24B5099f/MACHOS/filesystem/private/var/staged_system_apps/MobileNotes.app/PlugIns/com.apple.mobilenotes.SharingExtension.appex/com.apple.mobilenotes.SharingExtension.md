## com.apple.mobilenotes.SharingExtension

> `/private/var/staged_system_apps/MobileNotes.app/PlugIns/com.apple.mobilenotes.SharingExtension.appex/com.apple.mobilenotes.SharingExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xafbb0` | `0xb0334` | **`+0x784`** |
| `__DATA_CONST.__const` | `0x4db8` | `0x4ec8` | **`+0x110`** |
| `__TEXT.__gcc_except_tab` | `0x6d4` | `0x744` | **`+0x70`** |
| `__TEXT.__cstring` | `0x3815` | `0x3875` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0xba40` | `0xba80` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0xf189` | `0xf1b9` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2540` | `0x2568` | **`+0x28`** |
| `__DATA.__bss` | `0x9d50` | `0x9d60` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x3a00` | `0x3a10` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x25c0` | `0x25d0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x12f0` | `0x12f8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xb00` | `0xb08` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x5a8` | `0x5b0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-3001.40.9.100.1
+3001.40.11.102.1

-  Functions: 3262
-  Symbols:   535
-  CStrings:  3222
+  Functions: 3270
+  Symbols:   537
+  CStrings:  3227
Symbols:
+ _OBJC_CLASS_$_NSNull
+ _dispatch_queue_attr_make_with_qos_class
CStrings:
+ "com.apple.notes.sharing-extension.image-preview-generation"
+ "generatePreviewWithAttachments:completion:"
+ "generateVideoPreviewUsingAttachment:completion:"
+ "ic_previewImageWithCompletion:"
+ "null"
+ "setObject:atIndexedSubscript:"
+ "v16@?0@\"ICSEMediaPreview\"8"
+ "v16@?0@\"UIImage\"8"
- "generatePreviewWithAttachments:"
- "generateVideoPreviewUsingAttachment:"
- "ic_previewImage"
```
