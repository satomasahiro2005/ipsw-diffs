## AccountSubscriber

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/XPCServices/AccountSubscriber.xpc/AccountSubscriber`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12784` | `0x13a84` | **`+0x1300`** |
| `__TEXT.__oslogstring` | `0xb0d` | `0xfd0` | **`+0x4c3`** |
| `__TEXT.__objc_methname` | `0x1c97` | `0x1e36` | **`+0x19f`** |
| `__TEXT.__objc_stubs` | `0x1f80` | `0x2100` | **`+0x180`** |
| `__TEXT.__cstring` | `0x104b` | `0x10e9` | **`+0x9e`** |
| `__DATA_CONST.__cfstring` | `0xca0` | `0xd20` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x910` | `0x978` | **`+0x68`** |
| `__TEXT.__objc_methlist` | `0x81c` | `0x86c` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x2be` | `0x2f1` | **`+0x33`** |
| `__TEXT.__unwind_info` | `0x3c8` | `0x3f8` | **`+0x30`** |
| `__TEXT.__const` | `0x78` | `0x88` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-624.0.10.0.0
+624.2.3.0.0

-  Functions: 280
+  Functions: 299

-  CStrings:  519
+  CStrings:  555
CStrings:
+ "(nil)"
+ "@32@0:8@16^@24"
+ "@48@0:8@16@24@32^@40"
+ "B32@0:8@16^@24"
+ "Failed to find transfer candidate for %{public}@: %{public}@"
+ "Failed to resolve user identity asset %{public}@ for declaration %{public}@: %{public}@"
+ "Failed to transfer profile-managed account %{public}@ for configuration %{public}@: %{public}@"
+ "Found profile-managed account %{public}@ matching email for transfer"
+ "Incorrect declaration class: %{public}@"
+ "Multiple profile-managed accounts (%lu) of type %@ match the requested email; refusing ambiguous transfer"
+ "No email address provided for profile-managed account lookup"
+ "No profile transfer candidate found among %lu accounts of type %{public}@"
+ "No profile-managed account matches email %{public}@ for declaration %{public}@"
+ "No transfer candidate for declaration %{public}@"
+ "No user identity asset reference in declaration %{public}@; skipping transfer candidate lookup"
+ "Profile account transfer to DDM"
+ "Refusing to transfer: %lu profile-managed candidates match (identifiers: %{public}@)"
+ "Resolved user identity has no email for declaration %{public}@; skipping transfer candidate lookup"
+ "Resolver returned nil userIdentity with no error for asset %{public}@ (declaration %{public}@)"
+ "Searching %lu accounts of type %{public}@ for profile transfer candidate"
+ "Transferred profile-managed account %{public}@ for configuration %{public}@"
+ "_transferProfileAccountForConfiguration:error:"
+ "accountsWithAccountType:"
+ "array"
+ "arrayWithCapacity:"
+ "caseInsensitiveCompare:"
+ "createInternalErrorWithDescription:"
+ "createNotImplementedErrorForFeature:"
+ "findProfileAccountToTransferForEmail:accountTypeIdentifier:store:error:"
+ "firstObject"
+ "length"
+ "mcProfileUUID"
+ "profileAccountToTransferForConfiguration:store:error:"
+ "transferProfileAccount: not implemented on this platform for account %{public}@"
+ "transferProfileAccount:error:"
+ "transferProfileAccountForConfiguration:error:"
```
