## BackgroundSystemTasks

> `/System/Library/PrivateFrameworks/BackgroundSystemTasks.framework/BackgroundSystemTasks`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x134a0` | `0x134fc` | **`+0x5c`** |
| `__TEXT.__cstring` | `0xb8f` | `0xbc2` | **`+0x33`** |
| `__DATA_CONST.__const` | `0x690` | `0x6a8` | **`+0x18`** |

### Other Changes

```diff

-2467.0.14.502.1
+2467.0.23.502.1

-  CStrings:  297
+  CStrings:  300
Functions:
~ +[BGSystemTaskRequest taskRequestWithDescriptor:withIdentifier:] : 5592 -> 5600
~ +[BGSystemTaskRequest purposeFromString:identifier:] : 212 -> 296
CStrings:
+ "EnablementPhase0"
+ "EnablementPhase1"
+ "EnablementPhase2"
```
