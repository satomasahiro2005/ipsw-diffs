## CloudDocsUI

> `/System/Library/PrivateFrameworks/CloudDocsUI.framework/CloudDocsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2d284` | `0x2cacc` | **`-0x7b8`** |
| `__TEXT.__cstring` | `0x1b48` | `0x1974` | **`-0x1d4`** |
| `__AUTH_CONST.__cfstring` | `0x1f60` | `0x1de0` | **`-0x180`** |
| `__AUTH_CONST.__objc_const` | `0x7f10` | `0x7eb0` | **`-0x60`** |
| `__TEXT.__objc_methlist` | `0x3c28` | `0x3be0` | **`-0x48`** |
| `__DATA_CONST.__objc_selrefs` | `0x2b70` | `0x2b38` | **`-0x38`** |
| `__TEXT.__ustring` | `0x386` | `0x378` | **`-0xe`** |
| `__DATA.__objc_ivar` | `0x3ac` | `0x3a4` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xc48` | `0xc40` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 1180
-  Symbols:   2408
-  CStrings:  349
+  Functions: 1174
+  Symbols:   2399
+  CStrings:  337
Symbols:
- -[_UIDocumentPickerCell _showPickableDiagnostic]
- -[_UIDocumentPickerCell pickableDiagnosticGestureRecognizer]
- -[_UIDocumentPickerCell setPickableDiagnosticGestureRecognizer:]
- -[_UIDocumentPickerContainerItem pickabilityReason]
- -[_UIDocumentPickerContainerItem setPickabilityReason:]
- -[_UIDocumentPickerDocumentCell _showPickableDiagnostic]
- _CPIsInternalDevice
- _OBJC_IVAR_$__UIDocumentPickerCell._pickableDiagnosticGestureRecognizer
- _OBJC_IVAR_$__UIDocumentPickerContainerItem._pickabilityReason
CStrings:
- ", "
- "Bummer"
- "Container %@ declares types (%@), which doesn't overlap requested types (%@)"
- "Container declares type %@, which requested type %@ conforms to"
- "Container doesn't declare any types, so it's pickable by default"
- "Debug..."
- "Debug…"
- "Document picker is in a mode that doesn't allow picking items"
- "Internal diagnostic: Item is not pickable"
- "Internal diagnostic: Item is pickable"
- "Item %@ has nil type."
- "Item %@ has type %@, which does not conform to any of the allowed types (%@)"
```
