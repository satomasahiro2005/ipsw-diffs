## tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7ecf4` | `0x80968` | **`+0x1c74`** |
| `__TEXT.__oslogstring` | `0xec00` | `0xef5b` | **`+0x35b`** |
| `__TEXT.__objc_methname` | `0x11fd7` | `0x1220a` | **`+0x233`** |
| `__TEXT.__cstring` | `0x111d7` | `0x113aa` | **`+0x1d3`** |
| `__TEXT.__objc_stubs` | `0xace0` | `0xaea0` | **`+0x1c0`** |
| `__DATA_CONST.__cfstring` | `0x83a0` | `0x8480` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0x17c0` | `0x1890` | **`+0xd0`** |
| `__TEXT.__gcc_except_tab` | `0x29fc` | `0x2a9c` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x502c` | `0x50b4` | **`+0x88`** |
| `__DATA_CONST.__objc_arraydata` | `0x14e0` | `0x1550` | **`+0x70`** |
| `__DATA.__objc_const` | `0x9dc0` | `0x9e20` | **`+0x60`** |
| `__DATA.__objc_selrefs` | `0x3428` | `0x3488` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x2690` | `0x26f0` | **`+0x60`** |
| `__DATA_CONST.__objc_intobj` | `0x5e8` | `0x648` | **`+0x60`** |
| `__DATA_CONST.__objc_dictobj` | `0xe60` | `0xeb0` | **`+0x50`** |
| `__TEXT.__dlopen_cstrs` | `0x47` | `0x90` | **`+0x49`** |
| `__TEXT.__objc_methtype` | `0x227a` | `0x22b4` | **`+0x3a`** |
| `__DATA.__bss` | `0x411` | `0x429` | **`+0x18`** |
| `__DATA_CONST.__objc_arrayobj` | `0xd8` | `0xf0` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x6d0` | `0x6d8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x428` | `0x430` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-903.0.0.0.0
+906.0.0.0.0

-  Functions: 2801
-  Symbols:   502
-  CStrings:  5563
+  Functions: 2830
+  Symbols:   503
+  CStrings:  5608
Symbols:
+ _OBJC_CLASS_$_BSAuditToken
CStrings:
+ "#AuthorizationPromptServiceClient #Error received an error as a response error:%@ errorDescription:%@"
+ "%s #AuthorizationPromptServiceClient %@ for service %@ is %@ eligible for the full sheet prompt"
+ "%s: current lockstate=%llu (0=unlocked), waiting for next lock/unlock cycle"
+ "%s: failed to deserialize reminder queue plist: %{public}@"
+ "%s: failed to read reminder queue plist: %{public}@"
+ "%s: failed to serialize reminder queue plist: %{public}@"
+ "%s: failed to serialize updated reminder queue plist: %{public}@"
+ "%s: failed to write reminder queue plist to %{public}@: %{public}@"
+ "%s: failed to write updated reminder queue plist to %{public}@: %{public}@"
+ "%s: milestone override is not a string type"
+ "%s: no milestone override preference set"
+ "%s: no reminder queue plist found at %{public}@, nothing to restore"
+ "%s: restored %lu reminders from plist"
+ "%s: unknown service %{public}@ in plist, skipping"
+ "+[TCCDReminderMonitor milestoneOverrideFromDefaults]"
+ "-[TCCDReminderMonitor persistQueueToDisk]"
+ "-[TCCDReminderMonitor removeFromPersistedQueue:service:]"
+ "-[TCCDReminderMonitor restoreQueuedReminders]"
+ "0a"
+ "@\"LSApplicationRecord\""
+ "Applied milestone override from defaults: %{public}@"
+ "HKAuthorizationStore"
+ "HKHealthStore"
+ "HealthKit authorization reset failed for %{public}@, TCC record unchanged"
+ "HealthKit authorization reset for %@"
+ "HealthKit framework not available, cannot reset authorization for %{public}@"
+ "HealthKit reminder: user chose Continue to Allow for %{public}@"
+ "HealthKit reminder: user chose Remove Access for %{public}@, resetting authorization in healthd"
+ "HealthKit reset confirmed for %{public}@, writing DENIED to TCC"
+ "HealthKit reset succeeded but failed to write DENIED to TCC for %{public}@"
+ "NSHealthShareUsageDescription"
+ "Reminder prompt dismissed without user action for %{public}@, re-enqueueing"
+ "T@\"LSApplicationRecord\",R"
+ "TB,N,V_defersPromptDatabaseWrite"
+ "UPDATE access SET auth_value = ?, auth_reason = ? WHERE service = ? AND client = ? AND client_type = ?"
+ "_applicationRecord"
+ "_defersPromptDatabaseWrite"
+ "_performAsyncOperation:description:maxAttempts:retryDelaySecs:onSuccess:onFailure:attempt:"
+ "applicationRecord"
+ "applyMilestoneOverrideIfNeeded"
+ "com.apple.HealthKit.HealthKitTCCNotificationExtension"
+ "container identifier is: %@"
+ "d32@0:8i16i20d24"
+ "defersPromptDatabaseWrite"
+ "elapsedTimeFromLastReminder:lastModifiedTime:now:"
+ "found app sharing this group container."
+ "handlePromptResponse:forContext:"
+ "healthReminderMilestoneOverride"
+ "initWithHealthStore:"
+ "is"
+ "is not"
+ "kTCCServiceSiriAccess"
+ "milestoneOverrideFromDefaults"
+ "performAsyncOperation:description:maxAttempts:retryDelaySecs:onSuccess:onFailure:"
+ "persistQueueToDisk"
+ "reminderQueuePlistPath"
+ "reminder_queue.plist"
+ "removeFromPersistedQueue:service:"
+ "requestAuthorizationForService:auditToken:bundleId:usageDescription:includesLearnMore:completionHandler:"
+ "requestAuthorizationForService:auditToken:forBundleId:usageDescription:includeLearnMore:completionHandler:"
+ "resetAuthorizationStatusForBundleIdentifier:completion:"
+ "restoreQueuedReminders"
+ "setDefersPromptDatabaseWrite:"
+ "softlink:r:path:/System/Library/Frameworks/HealthKit.framework/HealthKit"
+ "v16@?0@?<v@?B@\"NSError\">8"
+ "v40@0:8@\"NSString\"16@\"NSData\"24@?<v@?@\"NSError\">32"
+ "v56@0:8@?16@24i32i36@?40@?48"
+ "v60@0:8@?16@24i32i36@?40@?48i56"
+ "v64@0:8@\"NSString\"16@\"BSAuditToken\"24@\"NSString\"32@\"NSString\"40@\"NSNumber\"48@?<v@?@\"NSNumber\"@\"NSError\">56"
+ "v84@0:8@16{?=[8I]}24@56@64C72@?76"
- "#AuthorizationPromptServiceClient #Error received an error as a response error:%@"
- "%s #AuthorizationPromptServiceClient %@ for service %@ is eligible for the full sheet prompt"
- "%s: current lockstate=%llu (0=unlocked)"
- "%s: lastReminded appears to be Unix timestamp, converting: %d"
- "%s: lastReminded is 0 for this record, now: %f last_modified: %d"
- "-[TCCDReminderMonitor reportResourceUsage:]_block_invoke"
- "NSSiriUsageDescription"
- "SetReminderMilestones"
- "SetReminderMilestones for %{public}@: %{public}@"
- "SetReminderMilestones for %{public}s: %{public}s"
- "SetReminderMilestones: missing service name or milestones string"
- "SetReminderMilestones: no valid milestone values in '%{public}@'"
- "SetReminderMilestones: not allowed on production builds"
- "SetReminderMilestones: unknown service '%{public}@'"
- "Vv40@0:8@\"NSString\"16@\"NSData\"24@?<v@?@\"NSError\">32"
- "Vv40@0:8@16@24@?32"
- "Vv56@0:8@\"NSString\"16@\"NSString\"24@\"NSString\"32@\"NSNumber\"40@?<v@?@\"NSNumber\"@\"NSError\">48"
- "Vv56@0:8@16@24@32@40@?48"
- "_performAsyncOperation:description:maxAttempts:retryDelaySecs:attempt:"
- "applicationIdentifier"
- "requestAuthorizationForService:bundleId:usageDescription:includesLearnMore:completionHandler:"
- "requestAuthorizationForService:forBundleId:usageDescription:includeLearnMore:completionHandler:"
- "setReminderMilestones:forServiceName:"
- "v44@0:8@?16@24i32i36i40"
- "v52@0:8@16@24@32C40@?44"
```
