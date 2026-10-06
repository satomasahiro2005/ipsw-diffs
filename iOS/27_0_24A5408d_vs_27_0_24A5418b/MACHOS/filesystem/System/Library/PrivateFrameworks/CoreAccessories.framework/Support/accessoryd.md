## accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19c370` | `0x19cc00` | **`+0x890`** |
| `__DATA_CONST.__const` | `0xa070` | `0xa230` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0x37eff` | `0x3809a` | **`+0x19b`** |
| `__TEXT.__unwind_info` | `0x47c0` | `0x47e0` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1216.0.0.0.0
+1216.2.2.0.0

-  Functions: 8647
-  Symbols:   11666
-  CStrings:  8646
+  Functions: 8661
+  Symbols:   11669
+  CStrings:  8652
Symbols:
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-ccc7cff5b191b013cf5fb35cb64a23b0.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-dee892b8a883442591a56193ff213ab1.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-0643ae0983c6d6a4b3c8c09ad4d5f8af.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-7396cdf04cf0e11a5ee1deb7adf6cf6b.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-c7f8fa4991bd458cc9b68fe2b4a1b5be.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-154366ba21740639469c9f8dcb9992fd.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-b9ae2bf717c00f2781f7da0d14f0b822.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-0ccae82d708f96c89af9206b7d4cda6e.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-e613a10ccab0c60846c4010594257edb.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-4138e314e6afe7b9cda759c0c4f4f735.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-aa8122ee8b98ff5a46cb63f6ce2104cc.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-572af56cf296e19afd74df043de6f50b.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-66c9125dc4d0d3bb1cab06c98eb40567.o)
+ /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-aa8e6840769a65199b0616daf60f729c.o)
+ ____mfi4Auth_endpoint_releaseSourceUUIDsOnCancel_block_invoke
+ ___mfi4Auth_endpoint_create_block_invoke_2
+ __mfi4Auth_endpoint_create_block_invoke_2
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-decrypt-7dea482903b57a6ec7bbb597fd9a143c.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccm-encrypt-73cc0be84e7e9084c391c285bbebf8e5.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-4b50ba082eda75046db52eb1f15b3b0d.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_add-dea4bf4e6a7831a49d7abbedf381cc13.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_cmp-b22d9f70907d135f471bcda3b6aed074.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-19d3a1e1dea4c1af58e69da89264c589.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_mul-2205d10e42451cf738dbc30be60028a2.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_n-6d448ed408e129c120b78e6cb7b9dd34.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_set-e34160ba78d1e101e50fd7edad658145.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-2c8e0e3e42dc6d0f425847e59ba9dbad.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_shift_right-5e5d5b286b920ce64bb8f368882927cb.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-27548512dcf416a3492abba62f12d6a6.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub-f131f0de2a4586ca9b245ffa4fb5f385.o)
- /Library/Caches/com.apple.xbs/<UUID>/TemporaryDirectory.<TMP>/Binaries/CoreAccessories/install/Symbols/BuiltProducts/libAccessoryCore.a(ccn_sub1-a16a58efd676906a6c36bedb44becf9d.o)
CStrings:
+ "accAuthProtocol sendAuthSetupStart (manager2): connection gone for endpointUUID %@ !!"
+ "accAuthProtocol sendAuthSetupStart timer: no endpointUUID/connectionUUID for endpoint!!"
+ "authSetupStartTimer (manager2): connection gone for endpoint %@ !!"
+ "authSetupStartTimer: no endpointUUID/connectionUUID for endpoint!!"
+ "authTimer: connection gone for endpointUUID %@, no timeout to post"
+ "authTimer: endpoint not found for endpointUUID %@ !!"
+ "timerSource: endpoint %@ already gone, nothing to close"
- "accAuthProtocol sendAuthSetupStart timer: no endpointUUID for endpoint!!"
```
