## libswiftRemoteMirror.dylib

> `/usr/lib/swift/libswiftRemoteMirror.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc5f4` | `0xdc8b4` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x7105` | `0x712c` | **`+0x27`** |

### Same-size Content Changes

- `__AUTH_CONST.__const`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-6.4.0.25.5
+6.4.0.27.101

-  Functions: 2091
-  Symbols:   2590
-  CStrings:  1642
+  Functions: 2092
+  Symbols:   2591
+  CStrings:  1643
Symbols:
+ __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE17decodeMangledTypeEPNS1_4NodeEjbb
+ __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE25decodeTypeSequenceElementIZNS5_17decodeMangledTypeEPNS1_4NodeEjbbEUlPKNS3_7TypeRefEE0_EENSt3__18optionalINS_15TypeLookupErrorEEES8_jT_
+ __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE25decodeTypeSequenceElementIZNS5_17decodeMangledTypeEPNS1_4NodeEjbbEUlPKNS3_7TypeRefEE_EENSt3__18optionalINS_15TypeLookupErrorEEES8_jT_
+ __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE28decodeMangledGenericArgumentEPNS1_4NodeEjb
- __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE17decodeMangledTypeEPNS1_4NodeEjb
- __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE25decodeTypeSequenceElementIZNS5_17decodeMangledTypeEPNS1_4NodeEjbEUlPKNS3_7TypeRefEE0_EENSt3__18optionalINS_15TypeLookupErrorEEES8_jT_
- __ZN5swift8Demangle9__runtime11TypeDecoderINS_10reflection14TypeRefBuilderEE25decodeTypeSequenceElementIZNS5_17decodeMangledTypeEPNS1_4NodeEjbEUlPKNS3_7TypeRefEE_EENSt3__18optionalINS_15TypeLookupErrorEEES8_jT_
CStrings:
+ "integer value where a type is required"
```
