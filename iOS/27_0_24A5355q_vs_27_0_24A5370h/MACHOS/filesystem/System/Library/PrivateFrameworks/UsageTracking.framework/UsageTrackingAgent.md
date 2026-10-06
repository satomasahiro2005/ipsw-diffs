## UsageTrackingAgent

> `/System/Library/PrivateFrameworks/UsageTracking.framework/UsageTrackingAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x5a61` | `0x5b01` | **`+0xa0`** |
| `__TEXT.__text` | `0x727e4` | `0x72840` | **`+0x5c`** |
| `__TEXT.__oslogstring` | `0x56d6` | `0x5726` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x4520` | `0x4560` | **`+0x40`** |
| `__DATA.__objc_const` | `0x3050` | `0x3070` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1438` | `0x1448` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-401.0.0.0.0
+403.0.0.0.0

-  CStrings:  1436
+  CStrings:  1439
CStrings:
+ "B48@0:8@16@24r*32B40B44"
+ "Deferring warning for %{public}@/%{public}@/%{public}@ until it has activity"
+ "_notifyForBudgets:events:nextNotificationEventName:syncForImpendingBudgets:triggeredByActivity:"
+ "initWithApplicationTokens:exemptApplicationTokens:categoryTokens:webDomainTokens:exemptWebDomainTokens:threshold:includesPastActivity:warningTime:warnsOnlyDuringActivity:"
+ "initWithBundleIdentifiers:exemptBundleIdentifiers:categoryIdentifiers:webDomains:exemptWebDomains:threshold:includesPastActivity:warningTime:warnsOnlyDuringActivity:"
+ "setWarnsOnlyDuringActivity:"
+ "warnsOnlyDuringActivity"
- "B44@0:8@16@24r*32B40"
- "_notifyForBudgets:events:nextNotificationEventName:syncForImpendingBudgets:"
- "initWithApplicationTokens:exemptApplicationTokens:categoryTokens:webDomainTokens:exemptWebDomainTokens:threshold:includesPastActivity:"
- "initWithBundleIdentifiers:exemptBundleIdentifiers:categoryIdentifiers:webDomains:exemptWebDomains:threshold:includesPastActivity:"
```
