## SoftwareUpdateSettingsIntents

> `/System/Library/ExtensionKit/Extensions/SoftwareUpdateSettingsIntents.appex/SoftwareUpdateSettingsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17900` | `0x180cc` | **`+0x7cc`** |
| `__TEXT.__oslogstring` | `0x6b8` | `0x850` | **`+0x198`** |
| `__TEXT.__cstring` | `0x1235` | `0x1375` | **`+0x140`** |
| `__TEXT.__const` | `0x2944` | `0x2954` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x878` | `0x888` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-772.0.10.0.0
+772.0.20.0.0

-  Functions: 654
+  Functions: 656

-  CStrings:  153
+  CStrings:  160
Symbols:
+ _swift_bridgeObjectRelease_n
- _objc_retain_x28
CStrings:
+ "Apple Beta Software Program or Apple Developer Program"
+ "Beta Updates under Settings → General → Software Update"
+ "Finished to scan for update with results: %{public}s"
+ "General → Software Update"
+ "Intent getting the value of the Automatic Security Response Install: %{bool,public}d"
+ "Intent getting the value of the OS Automatic Download: %{bool,public}d"
+ "Intent setting the value of the Automatic Security Response Install to: %{bool,public}d"
+ "Intent setting the value of the OS Automatic Download to: %{bool,public}d"
+ "Open Software Update Settings"
+ "Perform Software Update Now"
+ "Perform Software Update Now under Settings → General → Software Update"
+ "Perform Software Update Tonight"
+ "Perform Software Update Tonight under Settings → General → Software Update"
+ "SUSettings Intents got SU Scan Results. Error: %{public}@; results: %{public}@"
+ "Software Update under Settings → General"
+ "The Apple Beta Software Program or Apple Developer Program available setting"
+ "developer update"
+ "developer updates"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => Auto update turned off by user request"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => Auto update turned on by user request"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => Finished to refreshBetaUpdates"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => Perform called with property value: %{bool,public}d"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => Starting to refreshBetaUpdates"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => Unable to create SUManagerClient instance"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => Unable to create SUSettingsStatefulUIManager"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => Unable to init SUManagerClient"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => User approved turning off the auto update"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => User needs to approved turning off the auto update since there is a scheduled update"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => User requested turning off the auto update"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => User requested turning on the auto update"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => finish to refreshBetaUpdates"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => returning %{public}s"
+ "🐞 %{public}s | %{public}s | line:%{public}ld => start to refreshBetaUpdates"
- "Finished to scan for update with results: %s"
- "Intent getting the value of the Automatic Security Response Install: %{bool}d"
- "Intent getting the value of the OS Automatic Download: %{bool}d"
- "Intent setting the value of the Automatic Security Response Install to: %{bool}d"
- "Intent setting the value of the OS Automatic Download to: %{bool}d"
- "Open Apple Beta Software Program or Apple Developer Program settings page"
- "Open Software Update settings page"
- "Perform Software Update now"
- "Perform Software Update tonight"
- "SUSettings Intents got SU Scan Results. Error: %@; results: %@"
- "The Apple Beta Software Program or Apple Developer Program available settings page"
- "🐞 %s | %s | line:%ld => Auto update turned off by user request"
- "🐞 %s | %s | line:%ld => Auto update turned on by user request"
- "🐞 %s | %s | line:%ld => Finished to refreshBetaUpdates"
- "🐞 %s | %s | line:%ld => Perform called with property value: %{bool}d"
- "🐞 %s | %s | line:%ld => Starting to refreshBetaUpdates"
- "🐞 %s | %s | line:%ld => Unable to create SUManagerClient instance"
- "🐞 %s | %s | line:%ld => Unable to create SUSettingsStatefulUIManager"
- "🐞 %s | %s | line:%ld => Unable to init SUManagerClient"
- "🐞 %s | %s | line:%ld => User approved turning off the auto update"
- "🐞 %s | %s | line:%ld => User needs to approved turning off the auto update since there is a scheduled update"
- "🐞 %s | %s | line:%ld => User requested turning off the auto update"
- "🐞 %s | %s | line:%ld => User requested turning on the auto update"
- "🐞 %s | %s | line:%ld => finish to refreshBetaUpdates"
- "🐞 %s | %s | line:%ld => returning %s"
- "🐞 %s | %s | line:%ld => start to refreshBetaUpdates"
```
