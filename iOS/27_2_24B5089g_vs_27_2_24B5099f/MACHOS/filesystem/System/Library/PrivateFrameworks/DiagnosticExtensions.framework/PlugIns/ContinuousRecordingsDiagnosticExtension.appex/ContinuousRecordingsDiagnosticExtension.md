## ContinuousRecordingsDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/ContinuousRecordingsDiagnosticExtension.appex/ContinuousRecordingsDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x960` | `0xc4c` | **`+0x2ec`** |
| `__TEXT.__oslogstring` | `0x191` | `0x234` | **`+0xa3`** |
| `__TEXT.__objc_stubs` | `0x300` | `0x360` | **`+0x60`** |
| `__TEXT.__cstring` | `0x192` | `0x1e1` | **`+0x4f`** |
| `__DATA_CONST.__cfstring` | `0x100` | `0x140` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x28d` | `0x2be` | **`+0x31`** |
| `__TEXT.__auth_stubs` | `0x240` | `0x260` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0xc8` | `0xe0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x128` | `0x138` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x58` | `0x68` | **`+0x10`** |
| `__TEXT.__const` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x50` | `0x5c` | **`+0xc`** |
| `__TEXT.__objc_methtype` | `0x23` | `0x2e` | **`+0xb`** |
| `__TEXT.__unwind_info` | `0x78` | `0x80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`

### Other Changes

```diff

-10100.44.0.0.0
+10110.3.0.0.0

-  Functions: 12
-  Symbols:   104
-  CStrings:  54
+  Functions: 13
+  Symbols:   112
+  CStrings:  66
Symbols:
+ -[ContinuousRecordingsDiagnosticExtension expectedForceFlushFinishedCount]
+ -[ContinuousRecordingsDiagnosticExtension getVersion:]
+ _OBJC_CLASS_$_NSDictionary
+ _OBJC_CLASS_$_NSNumber
+ _objc_msgSend$expectedForceFlushFinishedCount
+ _objc_msgSend$getVersion:
+ _objc_msgSend$propertyForKey:
+ _objc_msgSend$unsignedIntValue
+ _objc_opt_isKindOfClass
+ _objc_release_x26
- -[ContinuousRecordingsDiagnosticExtension countActiveRecordingDevices]
- _objc_msgSend$countActiveRecordingDevices
CStrings:
+ "%@ continuous recording version %u is managed by %s"
+ "ContinuousRecordingVersion"
+ "DefaultProperties"
+ "Found %lu recording device(s): %lu legacy, HCR 2.0 daemon %s; expecting %lu force flush finished notification(s)"
+ "HCR 2.0"
+ "I24@0:8@16"
+ "No DefaultProperties for %@"
+ "Sending force flush command, expecting %lu force flush finished notification(s)"
+ "Successfully received %lu force flush finished notification(s)"
+ "absent"
+ "expectedForceFlushFinishedCount"
+ "getVersion:"
+ "legacy HCR"
+ "present"
+ "propertyForKey:"
+ "unsignedIntValue"
- "Found %lu active recording device(s)"
- "Sending force flush command to %lu HID continuous recording device(s)"
- "Successfully force flushed %lu HID continuous recording device(s)"
- "countActiveRecordingDevices"
```
