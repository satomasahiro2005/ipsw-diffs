## ClarityUIServer

> `/System/Library/AccessibilityBundles/ClarityUIServer.axuiservice/ClarityUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd6f0` | `0xee28` | **`+0x1738`** |
| `__TEXT.__oslogstring` | `0x674` | `0xdd4` | **`+0x760`** |
| `__TEXT.__eh_frame` | `0x390` | `0x3e0` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0xbc0` | `0xbe0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x840` | `0x860` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x5e8` | `0x5f8` | **`+0x10`** |
| `__TEXT.__const` | `0x95a` | `0x96a` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x340` | `0x350` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-168.2.0.0.0
+170.3.0.0.0

-  Functions: 266
-  Symbols:   180
-  CStrings:  237
+  Functions: 267
+  Symbols:   182
+  CStrings:  255
Symbols:
+ _objc_retain_x22
+ _objc_retain_x25
CStrings:
+ "AA: StartFlow - Blocked entering ClarityBoard: SIM PIN not supported."
+ "AA: StartFlow - Blocked entering ClarityBoard: Screen Time device unlock required."
+ "AA: StartFlow - Blocked entering ClarityBoard: alphanumeric passcode not supported."
+ "AA: StartFlow - Blocked entering ClarityBoard: device hasn't been unlocked since boot."
+ "AA: StartFlow - Blocked entering ClarityBoard: not set up."
+ "AA: StartFlow - Calling addContentViewController for blank view controller: %{public}s"
+ "AA: StartFlow - Checking %ld SIMs..."
+ "AA: StartFlow - ClarityUI loading screen frozen; calling setClarityBoardEnabled(true)."
+ "AA: StartFlow - Could not get profile connection"
+ "AA: StartFlow - Dismiss animation of existing presenting view controller completed; removing its content view controller."
+ "AA: StartFlow - Entering ClarityBoard."
+ "AA: StartFlow - Found SIM with PIN."
+ "AA: StartFlow - Found no SIMs."
+ "AA: StartFlow - Loading view presented; waiting to freeze ClarityUI loading screen."
+ "AA: StartFlow - No existing presenting view controller; attempting to present passcode for the first time."
+ "AA: StartFlow - No validation warnings; proceeding to enter ClarityBoard."
+ "AA: StartFlow - Passcode is correct: %{bool}d"
+ "AA: StartFlow - Passcode was already presented (existingPresentingViewController: %{public}s). Dismissing it."
+ "AA: StartFlow - Passcode was dismissed with reason: %ld"
+ "AA: StartFlow - Passcode was hidden."
+ "AA: StartFlow - Passcode was shown."
+ "AA: StartFlow - Presenting AXUIPasscodeViewController with parent: %{public}s"
+ "AA: StartFlow - Presenting passcode."
+ "AA: StartFlow - Received attempt-to-enter-ClarityBoard message from client: %{public}s"
+ "AA: StartFlow - Received restrictions PIN entry notification; success: %{bool}d"
+ "AA: StartFlow - Screen Time restrictions passcode is enabled; activating remote PIN UI."
+ "AA: StartFlow - Tried to show loading screen, but had no presenting view controller."
+ "AA: StartFlow - Unable to enter ClarityUI: %s"
+ "AA: StartFlow - Unable to fetch whether SIM had PIN: %@"
+ "AA: StartFlow - Unable to get info about SIMs: %@"
+ "AA: StartFlow - addContentViewController completion fired; blank view controller is now attached."
+ "AA: StartFlow - setClarityBoardEnabled(true) succeeded."
- "Checking %ld SIMs..."
- "Could not get profile connection"
- "Found SIM with PIN."
- "Found no SIMs."
- "Passcode is correct: %{bool}d"
- "Passcode was already presented. Dismissing it."
- "Passcode was dismissed with reason: %ld"
- "Passcode was hidden."
- "Passcode was shown."
- "Presenting passcode."
- "Tried to show loading screen, but had no presenting view controller."
- "Unable to enter ClarityUI: %s"
- "Unable to fetch whether SIM had PIN: %@"
- "Unable to get info about SIMs: %@"
```
