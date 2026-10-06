## Device Recovery Assistant

> `/Applications/Device Recovery Assistant.app/Device Recovery Assistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f230` | `0x1f290` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x63c0` | `0x63e0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x8bba` | `0x8bcb` | **`+0x11`** |
| `__DATA.__objc_selrefs` | `0x2338` | `0x2340` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2f00` | `0x2f08` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x364d` | `0x3650` | **`+0x3`** |
| `__TEXT.__cstring` | `0x3643` | `0x3644` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-142.0.0.0.0
+144.0.0.0.0

-  Functions: 812
+  Functions: 813

-  CStrings:  2388
+  CStrings:  2389
CStrings:
+ "%{public}s: recovery menu screen will appear"
+ "-[SceneDelegate recoveryMenuViewControllerWillAppear:]"
+ "recoveryMenuViewControllerWillAppear:"
+ "viewWillAppear:"
- "%{public}s: recovery menu screen appeared"
- "-[SceneDelegate recoveryMenuViewControllerDidAppear:]"
- "recoveryMenuViewControllerDidAppear:"
```
