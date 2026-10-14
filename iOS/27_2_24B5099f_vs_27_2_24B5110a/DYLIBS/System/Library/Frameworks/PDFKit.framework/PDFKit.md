## PDFKit

> `/System/Library/Frameworks/PDFKit.framework/PDFKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbf848` | `0xbfaf8` | **`+0x2b0`** |
| `__AUTH_CONST.__objc_const` | `0xf120` | `0xf180` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0xb064` | `0xb094` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x7120` | `0x7138` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3ca0` | `0x3cb0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0xc7c` | `0xc88` | **`+0xc`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1537.1.2.0.0
+1537.1.4.0.0

-  Functions: 3768
-  Symbols:   7467
+  Functions: 3772
+  Symbols:   7474
Symbols:
+ -[PDFKitTextView _beginEditingSession]
+ -[PDFKitTextView _commitStringToModel:]
+ -[PDFKitTextView _replacementOverflowsWidget:inRange:forTextView:]
+ -[PDFKitTextView textViewDidBeginEditing:]
+ _OBJC_IVAR_$_PDFKitTextViewPrivate.isCommittingOwnEdit
+ _OBJC_IVAR_$_PDFKitTextViewPrivate.preEditValue
+ _OBJC_IVAR_$_PDFKitTextViewPrivate.sessionUndoRegistered
```
