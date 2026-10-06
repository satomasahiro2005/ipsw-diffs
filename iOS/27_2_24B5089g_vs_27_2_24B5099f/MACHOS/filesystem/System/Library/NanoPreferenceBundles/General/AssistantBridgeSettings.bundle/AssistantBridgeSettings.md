## AssistantBridgeSettings

> `/System/Library/NanoPreferenceBundles/General/AssistantBridgeSettings.bundle/AssistantBridgeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8070` | `0x82c8` | **`+0x258`** |
| `__TEXT.__objc_stubs` | `0x1920` | `0x1a00` | **`+0xe0`** |
| `__TEXT.__objc_methname` | `0x2012` | `0x20e4` | **`+0xd2`** |
| `__DATA.__objc_selrefs` | `0x840` | `0x878` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x3f8` | `0x420` | **`+0x28`** |
| `__DATA.__objc_const` | `0xa70` | `0xa90` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x460` | `0x480` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x7b4` | `0x7cc` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x240` | `0x250` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1e8` | `0x1f0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x60` | `0x64` | **`+0x4`** |
| `__TEXT.__objc_methtype` | `0x384` | `0x387` | **`+0x3`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3605.24.1.0.0
+3605.30.1.0.0

-  Functions: 185
-  Symbols:   159
-  CStrings:  507
+  Functions: 187
+  Symbols:   162
+  CStrings:  515
Symbols:
+ _PSFooterHyperlinkViewLinkSpecsKey
+ _objc_opt_isKindOfClass
+ _objc_retain_x5
CStrings:
+ "_assistantSectionsCollapsed"
+ "_assistantSectionsShouldCollapse"
+ "_refreshAskSiriFooterView"
+ "footerViewForSection:"
+ "getGroup:row:ofSpecifierID:"
+ "refreshContentsWithSpecifier:"
+ "removePropertyForKey:"
+ "setAssistantEnabled:forSpecifierID:withConfirmationAction:"
+ "table"
+ "v36@0:8B16@20@?28"
- "setAssistantEnabled:withConfirmationAction:"
- "v28@0:8B16@?20"
```
