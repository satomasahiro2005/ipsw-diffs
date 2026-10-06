## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19fdd0` | `0x19ffb0` | **`+0x1e0`** |
| `__TEXT.__oslogstring` | `0x390eb` | `0x3919e` | **`+0xb3`** |
| `__DATA_CONST.__const` | `0xa2d8` | `0xa318` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x95c0` | `0x9600` | **`+0x40`** |
| `__TEXT.__cstring` | `0xe5f5` | `0xe624` | **`+0x2f`** |
| `__TEXT.__objc_methname` | `0xfed6` | `0xff03` | **`+0x2d`** |
| `__TEXT.__objc_methlist` | `0x6eac` | `0x6ed4` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x73c0` | `0x73e0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x4830` | `0x4848` | **`+0x18`** |
| `__DATA.__bss` | `0x1618` | `0x1628` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x33c0` | `0x33d0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-1219.40.5.0.0
+1219.40.7.0.0

-  Functions: 8706
-  Symbols:   11697
-  CStrings:  8722
+  Functions: 8713
+  Symbols:   11709
+  CStrings:  8727
Symbols:
+ -[ACCTransportServer isConnectionEntitled:]
+ -[ACCTransportServer shouldAcceptConnection:]
+ -[NSXPCConnection(Entitlements) hasBooleanEntitlement:]
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(acc_internal_settings.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-e4efaeb33415a3dc2cd914cd52c49100.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-793af588241100d448ab0c941a00ed0b.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-53cf47e0d16744b32e0ddaab571d8d52.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-85a0a42e8ed52b843e1e8eb1781259f2.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-5143943fb0f3e9ebac8ecb0a5444ebce.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-7a25c217cbc7645c1a4170976fc9da22.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-b01b7e112ff08dc6f5e46cc111b0d342.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-8de872331bf81206aa052f08d480cbf3.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-d4311d9579330e64dcf0293f42d5abd5.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-dbe84c0853ad49101adfc97e28c7c5a5.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-e5ee669f1164fb663d0c66b1402ada1c.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-508b009b357848a3c1800e5599c91ff6.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-6ea30adac4fb9ab02cc3b39b963f6cc3.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-cfe5040b7e13b36ef269df8ca1eca8f1.o)
+ ___acc_internalSettings_isInternalBuild_block_invoke
+ _acc_internalSettings_boolForKey
+ _kCFACCUserDefaultsKey_AllowACCAuthProtocolOnAllTransport
+ _kCFACCUserDefaultsKey_AllowMFi4DevCertsOnProdDevice
+ _kCFACCUserDefaultsKey_DisableACCAuthProtocolOnInductive
+ _kCFACCUserDefaultsKey_EnableACCAuthProtocolOnNFC
+ _objc_msgSend$hasBooleanEntitlement:
+ _objc_msgSend$isConnectionEntitled:
+ acc_internalSettings_boolForKey
+ acc_internalSettings_isInternalBuild.isInternalBuild
+ acc_internalSettings_isInternalBuild.onceToken
+ acc_internal_settings.c
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-9900861efd199c4ae0383d2cecaa9352.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-2285d3d5c96b55ff0e63af7b5759975c.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-07a291e1a3661d09bd6db1aa3c433f52.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-6f5551b3d385a113e6290d8152b0ad48.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-b3f2b5440c0cd1c2edee4152dafbbffa.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-a71f983f2082b1671d64cccdd752fb2f.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-c4107dcd621e57c3b96260f48d606af9.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-2e729ea1ec0d925bec024ed752c8ca87.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-80a362488b0e4285b687e71fb8f13975.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-5bf8b67e5c72706425823b94e5a412cd.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-b657c2c2e5bf2bcf502b4681b1bc416f.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-353900df37f815d2857dfd000256c7ce.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-9e9d1baa40360e33d9ee94c4630fd410.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-30779dcd38afcac048e5a1263b4f4ffe.o)
- _ACCUserDefaultsKey_AllowACCAuthProtocolOnAllTransport
- _ACCUserDefaultsKey_AllowMFi4DevCertsOnProdDevice
- _ACCUserDefaultsKey_DisableACCAuthProtocolOnInductive
- _ACCUserDefaultsKey_EnableACCAuthProtocolOnNFC
CStrings:
+ "Unentitled XPC connection from pid %d! (Missing entitlement: '%@')! (API: ACCTransportClient / acc_transport_client)"
+ "acc_internalSettings: internal-only setting %{public}@ active"
+ "com.apple.private.accessories.transport-client"
+ "hasBooleanEntitlement:"
+ "isConnectionEntitled:"
```
