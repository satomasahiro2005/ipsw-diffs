## installcoordinationd

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/Support/installcoordinationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0xb050` | `0xb4d0` | **`+0x480`** |
| `__TEXT.__text` | `0xa05b8` | `0xa03dc` | **`-0x1dc`** |
| `__DATA.__objc_data` | `0x1240` | `0x1318` | **`+0xd8`** |
| `__DATA_CONST.__const` | `0x2d40` | `0x2e08` | **`+0xc8`** |
| `__DATA.__data` | `0xdb0` | `0xe70` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0xd60c` | `0xd57c` | **`-0x90`** |
| `__TEXT.__cstring` | `0x169fa` | `0x16a7a` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x530` | `0x5a0` | **`+0x70`** |
| `__TEXT.__objc_classname` | `0x986` | `0x9f6` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x511c` | `0x5184` | **`+0x68`** |
| `__TEXT.__const` | `0x580` | `0x5e0` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x1b30` | `0x1ae0` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0xb8` | `0x100` | **`+0x48`** |
| `__TEXT.__swift5_capture` | `0x178` | `0x1c0` | **`+0x48`** |
| `__TEXT.__swift5_typeref` | `0x35e` | `0x39a` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0x2610` | `0x2648` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x64` | `0x98` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0x12` | `0x45` | **`+0x33`** |
| `__DATA_CONST.__auth_got` | `0xda8` | `0xd80` | **`-0x28`** |
| `__TEXT.__objc_stubs` | `0xa680` | `0xa660` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x2892` | `0x28a5` | **`+0x13`** |
| `__DATA_CONST.__auth_ptr` | `0xa8` | `0xb8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x598` | `0x5a8` | **`+0x10`** |
| `__DATA_CONST.__objc_protolist` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x3118` | `0x3110` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1c0` | `0x1c8` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xc` | `0x10` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-849.40.2.502.1
+849.40.4.0.1

-  Functions: 3235
-  Symbols:   639
-  CStrings:  5090
+  Functions: 3245
+  Symbols:   638
+  CStrings:  5092
Symbols:
+ _$s19ExtensionFoundation03AppA7ProcessVMn
+ _$sBOWV
+ _swift_deletedMethodError
+ _swift_getSingletonMetadata
+ _swift_isaMask
+ _swift_updateClassMetadata2
- _$sSD10FoundationE34_conditionallyBridgeFromObjectiveC_6resultSbSo12NSDictionaryC_SDyxq_GSgztFZ
- _$sSD10FoundationE36_unconditionallyBridgeFromObjectiveCySDyxq_GSo12NSDictionaryCSgFZ
- _$sSS21_builtinStringLiteral17utf8CodeUnitCount7isASCIISSBp_BwBi1_tcfC
- _IXLoadInfoPlistFromBundleAtURL
- __swift_stdlib_bridgeErrorToNSError
- _swift_getDynamicType
- _swift_retain_x24
CStrings:
+ " to replace data: it does not speak IXAppReplacementProtocol"
+ "%ld migration(s) across %ld extension(s) failed while replacing %@ with %@"
+ "%s: failed to launch for %@ -> %@: %s"
+ "%s: failed to replace data for %@ -> %@ [%s]: %s"
+ "05:57:49"
+ "@32@0:8@\"NSString\"16#24"
+ "IXSDataReplacementExtensionSessionProtocol"
+ "Sep 12 2026"
+ "T@\"<IXSPropertyListProtocol>\",R"
+ "The extension reported failure migrating "
+ "_TtC20installcoordinationd34IXSDataReplacementExtensionSession"
+ "bundleRecordForApplicationIdentifier:error:"
+ "extensionBundleID"
+ "installcoordinationd.IXSDataReplacementExtensionSession"
+ "makeSessionForExtensionWithRecord:error:"
+ "process"
- " reported failure during app replacement "
- "%ld of %ld extension(s) failed to replace data for %@ -> %@"
- "%s: %@"
- "%s: failed to replace data for %@ -> %@: %s"
- "20:46:02"
- "Failed to communicate with app replacement extension %@: %@"
- "Failed to read the app replacement keys out of %s's Info.plist: %s"
- "Ignoring %s in %s's Info.plist: expected a number, found %s"
- "Sep  9 2026"
- "appReplacementEntitlementName"
- "bundleRecordWithApplicationIdentifier:error:"
- "dataReplacementInfoPlistForExtensionWithRecord:"
- "dataReplacementOrderKey"
- "replaceDataForRequest:usingExtensionWithRecord:error:"
```
