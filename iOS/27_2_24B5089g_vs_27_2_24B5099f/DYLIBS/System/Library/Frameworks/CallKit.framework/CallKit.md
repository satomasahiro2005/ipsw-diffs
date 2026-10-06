## CallKit

> `/System/Library/Frameworks/CallKit.framework/CallKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x68388` | `0x68fa0` | **`+0xc18`** |
| `__TEXT.__oslogstring` | `0x3d16` | `0x3e91` | **`+0x17b`** |
| `__TEXT.__cstring` | `0x641a` | `0x6557` | **`+0x13d`** |
| `__AUTH_CONST.__cfstring` | `0x43a0` | `0x4440` | **`+0xa0`** |
| `__TEXT.__gcc_except_tab` | `0x6f8` | `0x784` | **`+0x8c`** |
| `__DATA_CONST.__const` | `0xde0` | `0xe08` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1e10` | `0x1e28` | **`+0x18`** |

### Other Changes

```diff

-1406.200.62.0.0
+1406.200.81.0.0

-  Functions: 3259
-  Symbols:   5469
-  CStrings:  1014
+  Functions: 3269
+  Symbols:   5473
+  CStrings:  1031
Symbols:
+ GCC_except_table97
+ _OUTLINED_FUNCTION_5
+ ___94-[CXCallDirectoryStore migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:error:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56r64r_e20_B24?0?<B?^>8^16ls32l8r56l8r64l8s40l8s48l8
CStrings:
+ "DELETE FROM Extension WHERE bundle_id = ?"
+ "Deleting old extension"
+ "Executing migration"
+ "Failed to delete old extension: %@"
+ "Failed to update blocking entries: %@"
+ "Failed to update identification entries: %@"
+ "Failed to update new extension state: %@"
+ "Getting new extension's unique id"
+ "Getting old extension's data"
+ "New extension's unique id not found"
+ "Old extension not found"
+ "SELECT id FROM Extension WHERE bundle_id = ?"
+ "SELECT id, priority, state FROM Extension WHERE bundle_id = ?"
+ "UPDATE Extension SET priority = ?, state = ? WHERE bundle_id = ?"
+ "UPDATE PhoneNumberBlockingEntry SET extension_id = ? WHERE extension_id = ?"
+ "UPDATE PhoneNumberIdentificationEntry SET extension_id = ? WHERE extension_id = ?"
+ "Updating blocking entries"
+ "Updating identification entries"
+ "Updating new extension state"
- "Executing application migration"
- "UPDATE Extension SET bundle_id = ? WHERE bundle_id = ?"
```
