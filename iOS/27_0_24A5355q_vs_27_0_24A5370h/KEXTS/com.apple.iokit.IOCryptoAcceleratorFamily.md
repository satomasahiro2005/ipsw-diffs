## com.apple.iokit.IOCryptoAcceleratorFamily

> `com.apple.iokit.IOCryptoAcceleratorFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x320` | **`+0x320`** |
| `__TEXT_EXEC.__text` | `0x372c` | `0x3798` | **`+0x6c`** |

### Other Changes

```diff

-135.0.0.0.0
+137.0.0.0.0
Functions:
~ sub_fffffff009f1f5b8 -> sub_fffffff009f9d848 : 100 -> 132
~ __ZN16IOAESAccelerator17createSpecialKeysEv : 1764 -> 1812
~ __ZN26IOAESAcceleratorUserClient13_internalTestEv : 1540 -> 1532
~ sub_fffffff009f20eb4 -> sub_fffffff009f9f18c : 56 -> 60
~ __ZN16IOAESAccelerator10performAESEP18IOMemoryDescriptorS1_yP7IOAESIV14IOAESOperationP12IOAESKeyDatayyPFvPviES7_ : 1312 -> 1344
```
