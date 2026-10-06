## Books

> `/private/var/staged_system_apps/Books.app/Books`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7e66d8` | `0x7e8a0c` | **`+0x2334`** |
| `__TEXT.__cstring` | `0x2cba9` | `0x2cf5c` | **`+0x3b3`** |
| `__TEXT.__gcc_except_tab` | `0x46e8` | `0x482c` | **`+0x144`** |
| `__TEXT.__objc_stubs` | `0x427a0` | `0x42820` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x1a330` | `0x1a370` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x11d10` | `0x11d40` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x725e0` | `0x72600` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x8ea0` | `0x8eb8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x15ec0` | `0x15ed0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_catlist2`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 39914
-  Symbols:   2119
-  CStrings:  26086
+  Functions: 39964
+  Symbols:   2122
+  CStrings:  26110
Symbols:
+ _IOConnectCallStructMethod
+ _calloc
+ _swift_release_x11
CStrings:
+ "[_activeSessionID isEqual:session.sessionID]"
+ "[self.class initServiceConnection]"
+ "[session isKindOfClass:[PearlSecureFDRKeyUnwrapSession class]] && (self.cameraType == PearlSecureSessionCameraTypeIR)"
+ "bootNonce.length == sizeof(request.sensorBootNonce)"
+ "dataWithBytes:length:"
+ "getBytes:length:"
+ "hostEphemeralKeyData"
+ "hostIV"
+ "hostSignature"
+ "hostTag"
+ "responseLength == sizeof(response)"
+ "sensorEphemeralKey"
+ "sensorEphemeralKey.length == sizeof(request.sensorEphPublicKey)"
+ "sensorEphemeralKeySignature"
+ "sensorEphemeralKeySignature.length == sizeof(request.sensorEphPublicKeySig)"
+ "sensorEphemeralKeySignature.length == sizeof(request.unwrapOutputSensorSig)"
+ "sensorIV"
+ "sensorIV.length == sizeof(request.unwrapOutputSensorIV)"
+ "unwrappedSensorEncKey"
+ "unwrappedSensorEncKey.length == sizeof(request.unwrapOutputSensorEncKey)"
+ "unwrappedSensorEncKeyHmac"
+ "unwrappedSensorEncKeyHmac.length == sizeof(request.unwrapOutputSensorEncKeyHmac)"
+ "wrappedHostEncKey"
+ "wrappedHostEncKeyHmac"
```
