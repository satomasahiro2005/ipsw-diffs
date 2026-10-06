## Diagnostic-8264

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8264.appex/Diagnostic-8264`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4888` | `0x4c18` | **`+0x390`** |
| `__TEXT.__objc_stubs` | `0xe80` | `0xfc0` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0xded` | `0xf0d` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x79c` | `0x896` | **`+0xfa`** |
| `__DATA_CONST.__cfstring` | `0x880` | `0x940` | **`+0xc0`** |
| `__TEXT.__objc_methtype` | `0x2c4` | `0x32a` | **`+0x66`** |
| `__DATA.__objc_const` | `0x620` | `0x680` | **`+0x60`** |
| `__TEXT.__cstring` | `0x820` | `0x877` | **`+0x57`** |
| `__DATA.__objc_selrefs` | `0x4b0` | `0x500` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x3c0` | `0x380` | **`-0x40`** |
| `__DATA_CONST.__got` | `0x160` | `0x130` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x35c` | `0x38c` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x1f0` | `0x1d0` | **`-0x20`** |
| `__DATA_CONST.__auth_ptr` | `0x18` | `—` | **`-0x18`** |
| `__TEXT.__gcc_except_tab` | `0x190` | `0x1a8` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x38` | `0x40` | **`+0x8`** |
| `__TEXT.__const` | `0x98` | `0xa0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1307.0.16.0.0
+1307.0.26.502.1

-  - /usr/lib/updaters/libT200Updater.dylib
-  Functions: 60
-  Symbols:   121
-  CStrings:  352
+  Functions: 68
+  Symbols:   111
+  CStrings:  379
Symbols:
+ _CFRelease
+ _OBJC_CLASS_$_CRBatteryUpdaterFactory
- _CFStringGetCStringPtr
- _T200GetBoardIdFromDT
- _T200UpdaterCreate
- _T200UpdaterExecCommand
- _T200UpdaterIsDone
- _kT200OptionRestoreInternal
- _kT200OptionUpdateType
- _kT200PreflightContextLimited
- _kT200SkipFirmwareMapStore
- _kT200TagDeferredCommit
- _kT200TagFWSkipSameVersion
- _kT200TagPreflightContext
CStrings:
+ "%@,Ticket"
+ "@\"<CRBatteryUpdaterProtocol>\""
+ "Battery firmware updater setup successful"
+ "DeferredCommit"
+ "FWSkipSameVersion"
+ "Failed to setup firmware updater with options during retry, error:%@"
+ "Failed to setup firmware updater with options, error:%@"
+ "Limited"
+ "No need to update battery FW"
+ "PreflightContext"
+ "RestoreInternal"
+ "SkipFirmwareMapStore"
+ "T@\"<CRBatteryUpdaterProtocol>\",&,N,V_updater"
+ "T^{__CFDictionary=},N,V_updaterOptions"
+ "UpdateType"
+ "^{__CFDictionary=}"
+ "^{__CFDictionary=}16@0:8"
+ "_updater"
+ "_updaterOptions"
+ "execCommand(kFWUpdaterCmdQueryInfo) returns successfully, but deviceInfoDict is nil"
+ "execCommand:input:output:error:"
+ "getBMUTicketForBatteryFWUpdateWithOptions:BMUTicket:error:"
+ "getBMUType"
+ "getBoardIdFromDT:error:"
+ "isDone:"
+ "self.updaterOptions failed to allocate"
+ "setUpdater:"
+ "setUpdaterOptions:"
+ "setupWithOptions:logFunction:error:"
+ "sharedInstance"
+ "updater"
+ "updater execCommand failed to query battery information:%@"
+ "updater failed to perform next stage: %@:%@"
+ "updater isDone failed:%@"
+ "updaterOptions"
+ "v24@0:8^{__CFDictionary=}16"
- "Created the Veridian Updater"
- "Failed to create %s obj::error:%@"
- "No need to update Veridian FW"
- "T200"
- "T200UpdaterExecCommand failed: %@:%@"
- "T200UpdaterExecCommand failed:%@"
- "Veridian symbols absent"
- "getBMUTicketForVeridianFWUpdateWithOptions:BMUTicket:error:"
- "updaterOptions failed to allocate"
```
