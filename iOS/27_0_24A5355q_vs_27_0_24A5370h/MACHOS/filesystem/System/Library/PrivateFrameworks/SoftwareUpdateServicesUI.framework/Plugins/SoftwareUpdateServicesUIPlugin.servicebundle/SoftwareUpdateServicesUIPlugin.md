## SoftwareUpdateServicesUIPlugin

> `/System/Library/PrivateFrameworks/SoftwareUpdateServicesUI.framework/Plugins/SoftwareUpdateServicesUIPlugin.servicebundle/SoftwareUpdateServicesUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40b38` | `0x410f8` | **`+0x5c0`** |
| `__TEXT.__oslogstring` | `0x466b` | `0x4878` | **`+0x20d`** |
| `__DATA_CONST.__const` | `0x6b38` | `0x6d00` | **`+0x1c8`** |
| `__DATA_CONST.__cfstring` | `0x3440` | `0x3540` | **`+0x100`** |
| `__TEXT.__objc_stubs` | `0x5480` | `0x54e0` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x150` | `0x1a0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x610c` | `0x6147` | **`+0x3b`** |
| `__DATA.__objc_const` | `0x4848` | `0x4828` | **`-0x20`** |
| `__TEXT.__auth_stubs` | `0x460` | `0x480` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2b9c` | `0x2bbc` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1938` | `0x1950` | **`+0x18`** |
| `__TEXT.__cstring` | `0x3e3d` | `0x3e26` | **`-0x17`** |
| `__DATA_CONST.__auth_got` | `0x240` | `0x250` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x448` | `0x450` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x670` | `0x678` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x254` | `0x250` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-300.0.0.0.0
+302.0.0.0.0

-  Functions: 1002
-  Symbols:   316
-  CStrings:  2021
+  Functions: 1003
+  Symbols:   319
+  CStrings:  2039
Symbols:
+ __os_activity_create
+ __os_activity_current
+ _os_activity_scope_enter
+ _os_activity_scope_leave
- _CFNotificationCenterRemoveObserver
CStrings:
+ "Alert is already shown; not showing alert item for reason: %{public}@"
+ "Clearing OTA Reboot Alert State with reason: %{public}@"
+ "Dismissing alert for reason: %{public}@"
+ "Initial UI lock state: %{public}@"
+ "KnoxURLOverride"
+ "LayoutStateMonitor:init"
+ "LayoutStateMonitor:init finished"
+ "LayoutStateMonitor:init initial lock state = %{public}@"
+ "LayoutStateMonitor:init started"
+ "Not showing the alert now - will show it later"
+ "Should not show a post update alert; not showing alert item for reason: %{public}@"
+ "Showing alert item for reason: %{public}@"
+ "SpringBoard has started"
+ "SpringBoard just started"
+ "UI lock state changed: %{public}@"
+ "UI lock state changed: isUILocked=%{public}@"
+ "WKMSURLOverride"
+ "[_initializePostUpgradeNotification] Failed to register for notification: %s"
+ "[_setupAssistantFinished] Already dismissed"
+ "[_setupAssistantFinished] isUILocked: %d"
+ "[_showStartupAlertItemForReason] Already dismissed"
+ "[_uiLockStateChanged] Already dismissed"
+ "_initializePostUpdateNotification"
+ "com.apple.springboard.finishedstartup"
+ "inSetupModeOverride"
+ "initPostUpdateAlertControllerWithReason:"
+ "locked"
+ "locked -> unlocked"
+ "new layout: >>>\n%{public}@\ncontext: >>>\n%{public}@"
+ "postUpdateController initing for reason: %{public}@"
+ "preferences"
+ "unlocked"
+ "unlocked -> locked"
- "-[_SUSUIPostUpdateAlertController _setupAssistantFinished]_block_invoke"
- "-[_SUSUIPostUpdateAlertController _showStartupAlertItemForReason:]"
- "-[_SUSUIPostUpdateAlertController _uiLockStateChanged:]_block_invoke"
- "Alert is already shown; not showing alert item for reason: %@"
- "Clearing OTA Reboot Alert State with reason: %@"
- "Dismissing alert for reason: %@"
- "Received notification: %s"
- "SBSpringBoardDidLaunchNotification"
- "Should not show a post update alert; not showing alert item for reason: %@"
- "Showing alert item for reason: %@"
- "UI lock state changed: isUILocked=%@"
- "[%{public}s] Already dismissed"
- "_queue_isUILocked"
- "initPostOTAFollowUpController"
- "new layout: >>>\n%@\ncontext: >>>\n%@"
```
