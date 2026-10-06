## lockdownmoded

> `/System/Library/PrivateFrameworks/LockdownMode.framework/lockdownmoded`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40e50` | `0x3f490` | **`-0x19c0`** |
| `__TEXT.__auth_stubs` | `0x1660` | `0x1520` | **`-0x140`** |
| `__DATA.__data` | `0x17fa` | `0x16da` | **`-0x120`** |
| `__TEXT.__eh_frame` | `0x10c8` | `0x1008` | **`-0xc0`** |
| `__DATA.__objc_const` | `0x1298` | `0x11e8` | **`-0xb0`** |
| `__DATA_CONST.__auth_got` | `0xb40` | `0xaa0` | **`-0xa0`** |
| `__DATA.__bss` | `0x1420` | `0x14a0` | **`+0x80`** |
| `__TEXT.__const` | `0x1500` | `0x1498` | **`-0x68`** |
| `__TEXT.__objc_classname` | `0x581` | `0x521` | **`-0x60`** |
| `__TEXT.__unwind_info` | `0x988` | `0x928` | **`-0x60`** |
| `__DATA.__objc_data` | `0x590` | `0x540` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0xd7c` | `0xd2c` | **`-0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x58c` | `0x540` | **`-0x4c`** |
| `__TEXT.__objc_stubs` | `0xf60` | `0xf20` | **`-0x40`** |
| `__TEXT.__swift5_typeref` | `0x8ab` | `0x871` | **`-0x3a`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x4b0` | **`-0x30`** |
| `__TEXT.__objc_methname` | `0x1a19` | `0x19e9` | **`-0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x378` | `0x360` | **`-0x18`** |
| `__TEXT.__swift5_reflstr` | `0x570` | `0x55d` | **`-0x13`** |
| `__DATA.__objc_selrefs` | `0x628` | `0x618` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x31f2` | `0x3202` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x98` | `0x90` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0xa8` | `0xac` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x84` | `0x80` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-122.0.0.0.0
+128.0.3.0.0

-  - /System/Library/Frameworks/CryptoKit.framework/CryptoKit

-  Functions: 786
-  Symbols:   634
-  CStrings:  676
+  Functions: 773
+  Symbols:   606
+  CStrings:  668
Symbols:
+ _$ss23CustomStringConvertibleP11descriptionSSvgTj
+ _$ss5Int32Vs23CustomStringConvertiblesWP
+ _SecItemDelete
+ _SecItemUpdate
+ _kSecAttrAccessGroup
+ _kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly
- _$s10Foundation13__DataStorageC12_deallocatorySv_SitcSgvg
- _$s10Foundation13__DataStorageC5bytes6lengthACSVSg_Sitcfc
- _$s10Foundation13__DataStorageC6_bytesSvSgvg
- _$s10Foundation13__DataStorageC7_lengthSivg
- _$s10Foundation13__DataStorageC7_offsetSivg
- _$s10Foundation13__DataStorageCMa
- _$s10Foundation4DataV14RangeReferenceCMa
- _$s10Foundation4DataVAA0B8ProtocolAAMc
- _$s10Foundation4DataVAA15ContiguousBytesAAWP
- _$s10Foundation4DataVMn
- _$s10Foundation4DataVSEAAMc
- _$s10Foundation4DataVSeAAMc
- _$s9CryptoKit0aB5ErrorO22incorrectParameterSizeyA2CmFWC
- _$s9CryptoKit0aB5ErrorOMa
- _$s9CryptoKit0aB5ErrorOs0C0AAMc
- _$s9CryptoKit12SymmetricKeyV15withUnsafeBytesyxxSWKXEKlF
- _$s9CryptoKit12SymmetricKeyV4dataACx_tc10Foundation15ContiguousBytesRzlufC
- _$s9CryptoKit12SymmetricKeyV4sizeAcA0cD4SizeV_tcfC
- _$s9CryptoKit12SymmetricKeyVMa
- _$s9CryptoKit12SymmetricKeyVMn
- _$s9CryptoKit16SymmetricKeySizeV7bits256ACvgZ
- _$s9CryptoKit16SymmetricKeySizeVMa
- _$s9CryptoKit3AESO3GCMO4open_5using14authenticating10Foundation4DataVAE9SealedBoxV_AA12SymmetricKeyVxtKAI0I8ProtocolRzlFZ
- _$s9CryptoKit3AESO3GCMO4seal_5using5nonce14authenticatingAE9SealedBoxVx_AA12SymmetricKeyVAE5NonceVSgq_tK10Foundation12DataProtocolRzAqRR_r0_lFZ
- _$s9CryptoKit3AESO3GCMO5NonceVMa
- _$s9CryptoKit3AESO3GCMO5NonceVMn
- _$s9CryptoKit3AESO3GCMO9SealedBoxV8combined10Foundation4DataVSgvg
- _$s9CryptoKit3AESO3GCMO9SealedBoxV8combinedAG10Foundation4DataV_tcfC
- _$s9CryptoKit3AESO3GCMO9SealedBoxVMa
- _$sSayxG10Foundation12DataProtocolABs5UInt8VRszlMc
- _$sSqMa
- _kSecAttrAccessibleAfterFirstUnlock
- _swift_getSingletonMetadata
- _swift_updateClassMetadata2
CStrings:
+ "Aborting sync without advancing token: DB persistence failed: %{private}s"
+ "Cannot sync exempt contacts: exemption store is unavailable: %{private}s"
+ "Error posting exemption revoked notification: %{private}s"
+ "Failed to decode value for account '%{public}s': %{private}s"
+ "Failed to encode value for account '%{public}s': %{private}s"
+ "Failed to fetch contact %{private}s: %{private}s"
+ "Failed to fetch contact change history: %{private}s"
+ "Failed to fetch contact for display name: %{private}s"
+ "Keychain load failed for account '%{public}s': %{private}s"
+ "Keychain store failed for account '%{public}s': %{private}s"
+ "Skipping change history event that couldn't be cast to CNChangeHistoryEvent."
+ "com.apple.lockdownmoded.contact-exemptions"
- "Aborting sync without advancing token: DB persistence failed"
- "Cannot sync exempt contacts: encrypted storage is unavailable: %{private}s"
- "Decryption failed: %{private}s"
- "Encryption failed: %{private}s"
- "Error posting exemption revoked notification: %s"
- "Failed to decode value for key '%{public}s': %{private}s"
- "Failed to encode value for key '%{public}s': %{private}s"
- "Failed to fetch contact %{private}s: %{public}s"
- "Failed to fetch contact change history: %{public}s"
- "Failed to fetch contact for display name: %{public}s"
- "Failed to load encryption key from Keychain: %d"
- "Failed to store encryption key in Keychain: %d"
- "Got change history event that couldn't be casted."
- "_TtC13lockdownmodedP33_1026648E6E232E33AEC9446A67A0129817KeychainBackedKey"
- "account"
- "cachedKey"
- "com.apple.lockdownmoded.exemptions"
- "dataForKey:"
- "service"
- "setURL:forKey:"
```
