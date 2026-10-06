## com.apple.health.records.legacy-ingestion

> `/System/Library/PrivateFrameworks/HealthRecordServices.framework/XPCServices/com.apple.health.records.legacy-ingestion.xpc/com.apple.health.records.legacy-ingestion`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb5a0` | `0xba50` | **`+0x4b0`** |
| `__TEXT.__objc_methname` | `0x2a4e` | `0x2b60` | **`+0x112`** |
| `__TEXT.__objc_stubs` | `0x22e0` | `0x23c0` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x5d8` | `0x676` | **`+0x9e`** |
| `__DATA.__objc_selrefs` | `0xa48` | `0xa80` | **`+0x38`** |
| `__DATA_CONST.__const` | `0x388` | `0x3b0` | **`+0x28`** |
| `__TEXT.__cstring` | `0xd1d` | `0xd44` | **`+0x27`** |
| `__TEXT.__objc_methlist` | `0xe94` | `0xeac` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3a0` | `0x3a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7

-  Functions: 327
-  Symbols:   195
-  CStrings:  692
+  Functions: 330
+  Symbols:   197
+  CStrings:  702
Symbols:
+ _OBJC_CLASS_$_HDHealthRecordsIngestionServiceClient
+ _OBJC_CLASS_$__HKBehavior
CStrings:
+ "%{public}@ completed healthrecordsd refresh for account %{public}@ with %{public}@"
+ "%{public}@ refreshing credential via healthrecordsd for account %{public}@"
+ "_refreshBadCredentialViaHealthRecordsDaemon:completion:"
+ "_refreshCredentialViaRefreshTokenTask:completion:"
+ "features"
+ "initWithAccessToken:refreshToken:patientID:expiration:scope:"
+ "markCredentialAsBadAndRefresh:forAccountWithIdentifier:completion:"
+ "newTokenRefresh"
+ "sharedBehavior"
+ "v24@?0@\"HKFHIRCredential\"8@\"NSError\"16"
```
