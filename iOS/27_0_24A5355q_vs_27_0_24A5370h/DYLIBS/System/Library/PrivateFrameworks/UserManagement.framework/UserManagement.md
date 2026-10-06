## UserManagement

> `/System/Library/PrivateFrameworks/UserManagement.framework/UserManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2a028` | `0x2a44c` | **`+0x424`** |
| `__TEXT.__cstring` | `0x49b5` | `0x4adb` | **`+0x126`** |
| `__AUTH_CONST.__cfstring` | `0x3ee0` | `0x3f80` | **`+0xa0`** |
| `__DATA_CONST.__const` | `0x8a8` | `0x920` | **`+0x78`** |
| `__TEXT.__unwind_info` | `0xd10` | `0xd30` | **`+0x20`** |

### Other Changes

```diff

-488.0.0.0.0
+490.0.0.0.0

-  Functions: 1172
+  Functions: 1174

-  CStrings:  612
+  CStrings:  618
CStrings:
+ "******** IX PersonaCreation hook returned error:%@, returning error ********"
+ "******** IX PersonaDeletion hook returned error:%@, ignoring ********"
+ "******** IX PersonaDeletion hook returned error:%@, returning error ********"
+ "Persona creation rollback XPC error: %@"
+ "Persona creation rollback failed: %@"
+ "Persona creation rollback succeeded"
+ "PersonaLifeCycleIXErrorEnforcement"
- "******** IX PersonaDeletion hook returned error:%@, ignoring for now ********"
```
