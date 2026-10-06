## transparencyStaticKey

> `/usr/libexec/transparencyStaticKey`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b290` | `0x6b8e0` | **`+0x650`** |
| `__TEXT.__objc_methname` | `0x822c` | `0x82f8` | **`+0xcc`** |
| `__TEXT.__objc_stubs` | `0x6780` | `0x6800` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x7c30` | `0x7ca0` | **`+0x70`** |
| `__DATA_CONST.__const` | `0x20b0` | `0x2118` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x13fd` | `0x1454` | **`+0x57`** |
| `__DATA.__objc_selrefs` | `0x2448` | `0x2480` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x2998` | `0x29cc` | **`+0x34`** |
| `__TEXT.__unwind_info` | `0x27f0` | `0x2820` | **`+0x30`** |
| `__DATA.__objc_const` | `0xb590` | `0xb5a8` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xa88` | `0xa9c` | **`+0x14`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1766.0.60.0.0
+1766.40.47.0.0

-  Functions: 3720
+  Functions: 3733

-  CStrings:  2788
+  CStrings:  2799
CStrings:
+ "Cancelling scheduled flag %{public}@"
+ "Deferring scheduled flag %{public}@ by %f seconds"
+ "_onqueueCancelPendingFlagOnly:"
+ "_onqueueDeferPendingFlag:delayInSeconds:"
+ "_onqueueIsFlagScheduledOrCurrent:"
+ "cancelPendingFlagOnly:"
+ "deferBySeconds:"
+ "deferPendingFlag:delayInSeconds:"
+ "isFlagScheduledOrCurrent:"
+ "v32@0:8@\"NSString<KTFlagString>\"16d24"
+ "v32@0:8@16d24"
```
