## askpermissiond

> `/System/Library/PrivateFrameworks/AskPermission.framework/Support/askpermissiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x514dc` | `0x51954` | **`+0x478`** |
| `__TEXT.__oslogstring` | `0x57b8` | `0x5880` | **`+0xc8`** |
| `__DATA_CONST.__cfstring` | `0x3080` | `0x30e0` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x18f8` | `0x1948` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x6d26` | `0x6d66` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x5860` | `0x58a0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x1360` | `0x1380` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3254` | `0x3274` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2944` | `0x295c` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x19e8` | `0x19f8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x9c0` | `0x9d0` | **`+0x10`** |
| `__TEXT.__const` | `0x650` | `0x660` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xc40` | `0xc50` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-130.0.25.0.0
+130.0.29.0.0

-  Functions: 1150
-  Symbols:   545
-  CStrings:  2129
+  Functions: 1154
+  Symbols:   547
+  CStrings:  2137
Symbols:
+ _CGContextScaleCTM
+ _CGContextTranslateCTM
CStrings:
+ "%{public}@: %@ (%@) Kill Switch: %d"
+ "%{public}@: AskTo Kill Switch ON *or* FeatureFlag disabled - Checking if we can send via PeopleClient"
+ "12:38:53"
+ "AskTo"
+ "Aug  4 2026"
+ "Bag is NIL when checking %@ (%@) kill switch - defaulting to allow"
+ "Completion Handler is NIL when checking %@ (%@) kill switch - ATB request won't be sent"
+ "Messages"
+ "Unhandled kill switch type: %ld - defaulting to allow"
+ "_checkKillSwitch:completionHandler:"
+ "_sendViaAskToFramework:"
+ "enable-ks-via-askto"
- "%{public}@: AskToIntegration Feature Flag disabled - Checking if we can send via PeopleClient"
- "%{public}@: canSendViaMessages: %d - kill switch: %d"
- "05:38:49"
- "Jul 11 2026"
```
