## com.apple.health.records

> `/System/Library/PrivateFrameworks/HealthRecordServices.framework/XPCServices/com.apple.health.records.xpc/com.apple.health.records`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x230c` | `0x2b78` | **`+0x86c`** |
| `__TEXT.__oslogstring` | `0x5af` | `0x80a` | **`+0x25b`** |
| `__TEXT.__objc_methname` | `0xad3` | `0xbdf` | **`+0x10c`** |
| `__TEXT.__objc_methtype` | `0x707` | `0x7d9` | **`+0xd2`** |
| `__TEXT.__objc_stubs` | `0x420` | `0x480` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x3cc` | `0x41c` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x290` | `0x2c0` | **`+0x30`** |
| `__DATA.__objc_const` | `0x480` | `0x498` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0xf0` | `0x108` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  Functions: 61
+  Functions: 71

-  CStrings:  172
+  CStrings:  189
CStrings:
+ "%{public}@: remote_decodeManifestOnContext failed with error: %{public}@"
+ "%{public}@: remote_decodeManifestOnContext finished successfully"
+ "%{public}@: remote_decodeManifestOnContext starting"
+ "%{public}@: remote_preprocessSMARTHealthLink failed with error: %{public}@"
+ "%{public}@: remote_preprocessSMARTHealthLink finished successfully"
+ "%{public}@: remote_preprocessSMARTHealthLink starting"
+ "%{public}@: remote_processJWEManifestFilesOnContext failed with error: %{public}@"
+ "%{public}@: remote_processJWEManifestFilesOnContext finished successfully"
+ "%{public}@: remote_processJWEManifestFilesOnContext starting"
+ "decodeManifestOnContext:error:"
+ "preprocessSMARTHealthLinkInSource:options:error:"
+ "processJWEManifestFilesOnContext:error:"
+ "remote_decodeManifestOnContext:completion:"
+ "remote_preprocessSMARTHealthLink:options:completion:"
+ "remote_processJWEManifestFilesOnContext:completion:"
+ "v32@0:8@\"HKClinicalHealthLinkProcessingContext\"16@?<v@?@\"HKClinicalHealthLinkProcessingContext\"@\"NSError\">24"
+ "v40@0:8@\"HKSignedClinicalDataSource\"16Q24@?<v@?@\"HKClinicalHealthLinkProcessingContext\"@\"NSError\">32"
```
