## ZoomWindow

> `/System/Library/AccessibilityBundles/ZoomWindow.axuiservice/ZoomWindow`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6cacc` | `0x6ccec` | **`+0x220`** |
| `__TEXT.__objc_methname` | `0x1153b` | `0x1160b` | **`+0xd0`** |
| `__TEXT.__objc_stubs` | `0xbdc0` | `0xbe40` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0xb4c` | `0xb94` | **`+0x48`** |
| `__DATA.__objc_const` | `0x79f0` | `0x7a20` | **`+0x30`** |
| `__TEXT.__auth_stubs` | `0x22d0` | `0x2300` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x4de8` | `0x4e10` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x38b8` | `0x38d8` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1178` | `0x1190` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x960` | `0x968` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1aa8` | `0x1ab0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x6a4` | `0x6a8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-913.3.1.0.0
+913.3.2.0.0

-  Functions: 2562
-  Symbols:   5028
-  CStrings:  3307
+  Functions: 2565
+  Symbols:   5040
+  CStrings:  3314
Symbols:
+ -[ZWEventProcessor _accessibilityShouldIgnoreEventRep:]
+ -[ZWEventProcessor disabledIDMappingRegistry]
+ -[ZWEventProcessor setDisabledIDMappingRegistry:]
+ GCC_except_table1137
+ GCC_except_table1155
+ GCC_except_table1202
+ GCC_except_table1246
+ GCC_except_table1267
+ GCC_except_table1269
+ GCC_except_table1271
+ GCC_except_table1273
+ GCC_except_table1275
+ GCC_except_table1371
+ GCC_except_table1545
+ GCC_except_table1556
+ GCC_except_table519
+ GCC_except_table674
+ GCC_except_table783
+ GCC_except_table819
+ OBJC_IVAR_$_ZWEventProcessor._disabledIDMappingRegistry
+ _AXEventHIDServiceDisableAccessibilityEventTranslationKey
+ _AXLogHID
+ _IOHIDServiceClientCopyProperty
+ _IOHIDServiceClientGetRegistryID
+ _objc_msgSend$_accessibilityShouldIgnoreEventRep:
+ _objc_msgSend$creatorHIDServiceClient
+ _objc_msgSend$disabledIDMappingRegistry
+ _objc_msgSend$setDisabledIDMappingRegistry:
- GCC_except_table1134
- GCC_except_table1152
- GCC_except_table1199
- GCC_except_table1243
- GCC_except_table1264
- GCC_except_table1266
- GCC_except_table1268
- GCC_except_table1270
- GCC_except_table1272
- GCC_except_table1368
- GCC_except_table1542
- GCC_except_table1553
- GCC_except_table516
- GCC_except_table671
- GCC_except_table780
- GCC_except_table816
CStrings:
+ "T@\"NSMutableDictionary\",&,N,V_disabledIDMappingRegistry"
+ "Zoom: HID service registryID=%@ DisableAccessibilityEventTranslation=%d"
+ "_accessibilityShouldIgnoreEventRep:"
+ "_disabledIDMappingRegistry"
+ "creatorHIDServiceClient"
+ "disabledIDMappingRegistry"
+ "setDisabledIDMappingRegistry:"
```
