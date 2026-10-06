## axauditd

> `/System/Library/PrivateFrameworks/AccessibilityAudit.framework/Support/axauditd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc038` | `0xc140` | **`+0x108`** |
| `__TEXT.__oslogstring` | `0x2b8` | `0x341` | **`+0x89`** |
| `__TEXT.__cstring` | `0x7fc` | `0x836` | **`+0x3a`** |
| `__TEXT.__objc_stubs` | `0x2900` | `0x2920` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x398` | `0x3a8` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xd18` | `0xd20` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x360` | `0x368` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x31d6` | `0x31da` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-191.0.0.0.0
+192.1.0.0.0

-  Functions: 293
-  Symbols:   284
-  CStrings:  716
+  Functions: 296
+  Symbols:   285
+  CStrings:  720
Symbols:
+ _OBJC_CLASS_$_NSMutableSet
CStrings:
+ "%s: cycle detected in kAXRemoteParentAttribute chain; aborting walk"
+ "%s: kAXRemoteParentAttribute chain exceeded depth cap; aborting walk"
+ "set"
+ "void informAppOfFocusOnElement(AXElement *__strong, BOOL)"
```
