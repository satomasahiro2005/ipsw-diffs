## biomesyncd

> `/usr/libexec/biomesyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4c598` | `0x4c544` | **`-0x54`** |
| `__DATA_CONST.__cfstring` | `0x47a0` | `0x4760` | **`-0x40`** |
| `__TEXT.__oslogstring` | `0x6b00` | `0x6ad4` | **`-0x2c`** |
| `__TEXT.__cstring` | `0x5aa2` | `0x5a7b` | **`-0x27`** |
| `__TEXT.__objc_methlist` | `0x3d04` | `0x3cf4` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x448` | `0x450` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x1760` | `0x1759` | **`-0x7`** |
| `__TEXT.__objc_methname` | `0xa7b1` | `0xa7b2` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-256.0.1.0.0
+258.0.0.0.0

-  Functions: 1656
-  Symbols:   357
-  CStrings:  3122
+  Functions: 1653
+  Symbols:   358
+  CStrings:  3120
Symbols:
+ _OBJC_CLASS_$_BMComputeSourceChangeReporter
CStrings:
+ "@\"<BMViewEventReporter>\""
+ "BMXPCSyncChangeReporter: stream %@ remote %@: failed to notify of changes: %@"
+ "BMXPCSyncChangeReporter: stream %@ remote %@: failed to notify of user deletions: %@"
+ "_eventReporter"
+ "streamDeletionWithStreamIdentifier:remoteName:error:"
+ "streamUpdatedWithStreamIdentifier:remoteName:error:"
- "%@:remotes:%@"
- "@\"<BMGDXPCCoordinationService>\""
- "BMCoordinationXPCSyncEventReporter: stream %@: failed to notify coordination service of changes: %@"
- "BMCoordinationXPCSyncEventReporter: stream %@: failed to notify coordination service of user deletions: %@"
- "GDXPCCoordinationService"
- "_coordinationService"
- "streamRemoteIdentifierForStreamName:deviceIdentifier:"
- "streamUpdatedWithStreamName:isDelete:error:"
```
