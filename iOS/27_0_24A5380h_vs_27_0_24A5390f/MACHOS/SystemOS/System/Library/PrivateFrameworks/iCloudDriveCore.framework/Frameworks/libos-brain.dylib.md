## libos-brain.dylib

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Frameworks/libos-brain.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x207668` | `0x20be74` | **`+0x480c`** |
| `__DATA.__bss` | `0x10cd0` | `0x11060` | **`+0x390`** |
| `__TEXT.__cstring` | `0x40d2` | `0x4362` | **`+0x290`** |
| `__TEXT.__const` | `0xcd48` | `0xcef8` | **`+0x1b0`** |
| `__DATA.__data` | `0x4fb0` | `0x5088` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x849d` | `0x855d` | **`+0xc0`** |
| `__DATA_CONST.__auth_ptr` | `0x3168` | `0x3210` | **`+0xa8`** |
| `__TEXT.__unwind_info` | `0x6258` | `0x62e0` | **`+0x88`** |
| `__TEXT.__eh_frame` | `0x117d8` | `0x11848` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x343d` | `0x349d` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x29d0` | `0x2a20` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x2e38` | `0x2e6c` | **`+0x34`** |
| `__TEXT.__constg_swiftt` | `0x44dc` | `0x450c` | **`+0x30`** |
| `__TEXT.__objc_methtype` | `0x11cf` | `0x11ff` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x52e2` | `0x5312` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x14f0` | `0x1518` | **`+0x28`** |
| `__TEXT.__swift5_proto` | `0x8d8` | `0x8f4` | **`+0x1c`** |
| `__TEXT.__swift_as_cont` | `0xcb4` | `0xcc4` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x2dc` | `0x2e0` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5140.0.0.0.2
+5168.0.5.0.2

-  Functions: 6913
-  Symbols:   2111
-  CStrings:  1513
+  Functions: 6960
+  Symbols:   2118
+  CStrings:  1524
Symbols:
+ __swift_closure_destructor.67Tm
+ _associated conformance 12common_brain16CommonBrainErrorO10Foundation09LocalizedE0AAs0E0
+ _associated conformance 12common_brain16CommonBrainErrorO10Foundation13CustomNSErrorAAs0E0
+ _associated conformance 8os_brain12OSBrainErrorO10Foundation09LocalizedD0AAs0D0
+ _associated conformance 8os_brain12OSBrainErrorO10Foundation13CustomNSErrorAAs0D0
+ _objc_release_x11
+ _symbolic ScCy_____Sg______pG So28NSFileProviderItemIdentifiera s5ErrorP
+ _symbolic _____ 8os_brain10SyncEngineC25CorrectiveActionOverrides33_0363D5EF121AC73FB9168692FD66EC54LLV
- __swift_closure_destructor.61Tm
CStrings:
+ "CommonBrainError.clientChangeTokenMismatch(expected: "
+ "CommonBrainError.creationPathMatchFound("
+ "CommonBrainError.emptyJobBatch"
+ "CommonBrainError.groupingKeyPathNotSet"
+ "CommonBrainError.hierarchyDepthUnknown"
+ "CommonBrainError.hierarchyTooDeep"
+ "CommonBrainError.invalidCompletionHandlerCallCount("
+ "CommonBrainError.invalidItemIDString("
+ "CommonBrainError.invalidOperationType(actual: "
+ "CommonBrainError.invalidPluginFieldValueType("
+ "CommonBrainError.invalidRecordFieldKeyType("
+ "CommonBrainError.invalidZoneIdentifier("
+ "CommonBrainError.methodNotImplemented"
+ "CommonBrainError.missingDestinationRecordEtag("
+ "CommonBrainError.missingRequiredInfo("
+ "CommonBrainError.permissionFailure"
+ "CommonBrainError.staleServerItem"
+ "CommonBrainError.unexpectedItemType(actual: "
+ "CommonBrainError.unexpectedShareState(actual: "
+ "CommonBrainError.unreachableError("
+ "CommonBrainError.zoneBlockedUnsupportedOS(zoneIdentifier: "
+ "OSBrainError.invalidContentSignature"
+ "OSBrainError.invalidFileProviderIdentifier("
+ "OSBrainError.invalidRecordType("
+ "OSBrainError.itemNotFoundAfterSyncDown("
+ "OSBrainError.noProgressMade(fields: "
+ "OSBrainError.unknownServerItemType("
+ "SyncEngine: Merged survivor content signature differs from local, marking needsDownload"
+ "SyncEngine: path-match conflict for %s merged into FP item %s; responding with that item"
+ "v24@?0@\"NSString\"8@\"NSError\"16"
+ "v56@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@?<v@?@\"NSString\"@\"NSError\">48"
- "clientChangeTokenMismatch(expected: "
- "creationPathMatchFound("
- "groupingKeyPathNotSet"
- "hierarchyDepthUnknown"
- "hierarchyTooDeep"
- "invalidCompletionHandlerCallCount("
- "invalidItemIDString("
- "invalidOperationType(actual: "
- "invalidPluginFieldValueType("
- "invalidRecordFieldKeyType("
- "invalidZoneIdentifier("
- "methodNotImplemented"
- "missingDestinationRecordEtag("
- "missingRequiredInfo("
- "permissionFailure"
- "unexpectedItemType(actual: "
- "unexpectedShareState(actual: "
- "unreachableError("
- "v56@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSString\"40@?<v@?@\"NSError\">48"
- "zoneBlockedUnsupportedOS(zoneIdentifier: "
```
