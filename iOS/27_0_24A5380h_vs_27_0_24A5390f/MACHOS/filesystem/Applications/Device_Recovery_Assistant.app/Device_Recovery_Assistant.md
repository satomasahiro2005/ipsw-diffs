## Device Recovery Assistant

> `/Applications/Device Recovery Assistant.app/Device Recovery Assistant`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e18c` | `0x1e4c0` | **`+0x334`** |
| `__TEXT.__oslogstring` | `0x34ef` | `0x35a0` | **`+0xb1`** |
| `__TEXT.__objc_methname` | `0x88a2` | `0x8928` | **`+0x86`** |
| `__TEXT.__objc_stubs` | `0x6120` | `0x6180` | **`+0x60`** |
| `__TEXT.__cstring` | `0x3553` | `0x35aa` | **`+0x57`** |
| `__DATA.__objc_const` | `0x64c8` | `0x64f8` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x2260` | `0x2280` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2d18` | `0x2d38` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x200` | `0x204` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methtype`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-148.0.0.0.0
+149.0.0.0.0

-  Functions: 781
+  Functions: 785

-  CStrings:  2328
+  CStrings:  2339
CStrings:
+ "%{public}s: Power down UI dismissed (programmatic)."
+ "%{public}s: Programmatically dismissing power down UI."
+ "%{public}s: dismissPowerDown called but power down UI is not visible."
+ "-[DREAlertManager dismissPowerDown]"
+ "-[DREAlertManager dismissPowerDown]_block_invoke"
+ "T@\"NSString\",&,N,V_defaultLanguageCode"
+ "_defaultLanguageCode"
+ "defaultLanguageCode"
+ "dismissPowerDown"
+ "setDefaultLanguageCode:"
+ "valueForKey:"
```
