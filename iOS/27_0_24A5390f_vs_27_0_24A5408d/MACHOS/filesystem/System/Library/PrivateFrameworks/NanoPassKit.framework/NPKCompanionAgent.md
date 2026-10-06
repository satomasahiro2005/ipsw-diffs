## NPKCompanionAgent

> `/System/Library/PrivateFrameworks/NanoPassKit.framework/NPKCompanionAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42384` | `0x425b4` | **`+0x230`** |
| `__TEXT.__objc_stubs` | `0x7be0` | `0x7c60` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0xc4d2` | `0xc547` | **`+0x75`** |
| `__TEXT.__objc_methtype` | `0x3665` | `0x3606` | **`-0x5f`** |
| `__TEXT.__oslogstring` | `0x9bb6` | `0x9c0c` | **`+0x56`** |
| `__DATA.__objc_selrefs` | `0x28a8` | `0x28c8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xd60` | `0xd70` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3590` | `0x3580` | **`-0x10`** |
| `__DATA.__objc_const` | `0x5c28` | `0x5c20` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x6c0` | `0x6c8` | **`+0x8`** |

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
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1341.0.0.0.0
+1347.0.0.0.0

-  Symbols:   449
-  CStrings:  2742
+  Symbols:   450
+  CStrings:  2746
Symbols:
+ _NPKPairedOrPairingDeviceSupportsSEPassRelevancy
Functions:
~ sub_100013b1c : 1172 -> 1636
~ sub_100013fb0 -> sub_100014180 : 176 -> 208
~ sub_100018648 -> sub_100018838 : 512 -> 576
CStrings:
+ "Notice: Device does not support SE pass relevancy; suppressing relevancy for pass: %@"
+ "arrayWithCapacity:"
+ "npkRelevancyReasonText"
+ "passByPreservingDeviceOwnedSettingsFromExisting:onIncoming:"
+ "setReasonText:"
- "v36@0:8B16@\"PKAddCarKeyPassConfiguration\"20@?<v@?B@\"PKCarUnlockSupportedTerminal\"@\"NSError\">28"
```
