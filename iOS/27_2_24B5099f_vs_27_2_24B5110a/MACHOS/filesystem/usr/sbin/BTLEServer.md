## BTLEServer

> `/usr/sbin/BTLEServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7fce4` | `0x80334` | **`+0x650`** |
| `__TEXT.__objc_methname` | `0x1340d` | `0x134d2` | **`+0xc5`** |
| `__TEXT.__objc_stubs` | `0xd020` | `0xd0e0` | **`+0xc0`** |
| `__DATA.__objc_const` | `0xfcc8` | `0xfd58` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x7ed4` | `0x7f1c` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0xd9c0` | `0xd9f9` | **`+0x39`** |
| `__DATA.__objc_selrefs` | `0x4320` | `0x4350` | **`+0x30`** |
| `__TEXT.__const` | `0x900` | `0x920` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1c18` | `0x1c28` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x8a0` | `0x8ac` | **`+0xc`** |
| `__TEXT.__cstring` | `0x369f` | `0x36a0` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-  Functions: 3169
+  Functions: 3179

-  CStrings:  5273
+  CStrings:  5286
CStrings:
+ "Received UARP 0x02 report, but the UARP interface is nil"
+ "T@\"NSMutableData\",R,N,V_uarpData"
+ "T@\"NSObject<OS_dispatch_group>\",R,N,V_groupUARP"
+ "T@,&,N,V_uarp"
+ "_groupUARP"
+ "_uarp"
+ "_uarpData"
+ "getUARPHIDReportDescriptor"
+ "groupUARP"
+ "handleUARPData"
+ "setUarp:"
+ "uarp"
+ "uarpData"
```
