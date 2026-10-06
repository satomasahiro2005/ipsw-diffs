## ClarityBoardFoundation

> `/System/Library/PrivateFrameworks/ClarityBoardFoundation.framework/ClarityBoardFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe27c` | `0xe6f8` | **`+0x47c`** |
| `__TEXT.__cstring` | `0x9ee` | `0xa72` | **`+0x84`** |
| `__AUTH_CONST.__cfstring` | `0x800` | `0x880` | **`+0x80`** |
| `__AUTH_CONST.__auth_got` | `0x6f0` | `0x710` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x338` | `0x358` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x238` | `0x250` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x470` | `0x488` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x6f8` | `0x708` | **`+0x10`** |
| `__DATA.__bss` | `0x410` | `0x420` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x420` | `0x430` | **`+0x10`** |
| `__TEXT.__const` | `0x780` | `0x790` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x274` | `0x284` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x36c` | `0x374` | **`+0x8`** |

### Other Changes

```diff

-165.0.0.0.0
+168.0.0.0.0

-  Functions: 400
-  Symbols:   461
-  CStrings:  104
+  Functions: 406
+  Symbols:   472
+  CStrings:  109
Symbols:
+ +[CLFLog(ClarityBoardAdditions) secureCameraIndicatorLog]
+ _CLBClientIdentifierForClientPid
+ _CLBSystemIntentsBundleIdentifier
+ _CLBWorkflowKitBackgroundShortcutRunnerBundleIdentifier
+ __AXSClarityBundleIdentifierForStandardBundleIdentifier
+ ___57+[CLFLog(ClarityBoardAdditions) secureCameraIndicatorLog]_block_invoke
+ _fmod
+ _objc_retain_x24
+ _objc_retain_x25
+ _secureCameraIndicatorLog.LogObject
+ _secureCameraIndicatorLog.OnceToken
CStrings:
+ ", test runner launch: "
+ "com.apple.SystemIntents"
+ "com.apple.WorkflowKit.BackgroundShortcutRunner"
+ "pid:%d"
+ "secureCameraIndicator"
```
