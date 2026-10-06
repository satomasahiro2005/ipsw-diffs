## CallHistory

> `/System/Library/PrivateFrameworks/CallHistory.framework/CallHistory`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b8d28` | `0x1b8d60` | **`+0x38`** |
| `__TEXT.__oslogstring` | `0x6349` | `0x6379` | **`+0x30`** |
| `__TEXT.__const` | `0x1e7d0` | `0x1e7e0` | **`+0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-145.100.7.2.1
+147.100.5.2.1
Functions:
~ -[CallDBManagerClient createHelperConnection] : 828 -> 824
~ -[CallDBManagerClient _createDatabaseIsPermanent:afterSyncHelperDidSucceed:] : 644 -> 692
~ -[CHRecentCall description] : 2124 -> 2140
~ +[CHPersistentStoreDescription persistentStoreDescriptionWithURL:processHandle:error:] : 748 -> 744
~ -[CallDBManagerClient _createDatabaseIsPermanent:afterSyncHelperDidSucceed:].cold.1 : 60 -> 112
~ -[CallDBManagerClient _createDatabaseIsPermanent:afterSyncHelperDidSucceed:].cold.4 : 112 -> 60
CStrings:
+ "147.100.5.2.1"
+ "147.100.5.2.1~16"
+ "Call History access requires data store access entitlement %@ or %@. This will be a hard error in the future."
+ "Client is missing the %@ and %@ entitlements (in future, one of these will be required)"
+ "createDatabase client (permanent:%{public}i) (syncHelperDidSucceed:%{public}i)"
- "145.100.7.2.1"
- "145.100.7.2.1~3"
- "Call History access requires data store access entitlement %@ or %@."
- "Not attempting to create helper connection because we're missing the %@ and %@ entitlements (one is required)"
- "createDatabase client (permanent:%{public}i)"
```
