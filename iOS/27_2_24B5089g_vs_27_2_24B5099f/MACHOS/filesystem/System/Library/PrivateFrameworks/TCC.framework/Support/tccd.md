## tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8fe24` | `0x9142c` | **`+0x1608`** |
| `__TEXT.__objc_methname` | `0x138f5` | `0x13c02` | **`+0x30d`** |
| `__TEXT.__oslogstring` | `0x11095` | `0x1135e` | **`+0x2c9`** |
| `__TEXT.__cstring` | `0x1366f` | `0x13838` | **`+0x1c9`** |
| `__TEXT.__objc_stubs` | `0xbb60` | `0xbd00` | **`+0x1a0`** |
| `__TEXT.__gcc_except_tab` | `0x31fc` | `0x32f4` | **`+0xf8`** |
| `__DATA.__objc_const` | `0xa758` | `0xa848` | **`+0xf0`** |
| `__DATA_CONST.__cfstring` | `0x8e40` | `0x8f00` | **`+0xc0`** |
| `__DATA_CONST.__const` | `0x2920` | `0x29b0` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x5754` | `0x57d4` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x3840` | `0x38b0` | **`+0x70`** |
| `__TEXT.__unwind_info` | `0x1ad8` | `0x1b10` | **`+0x38`** |
| `__DATA.__bss` | `0x441` | `0x459` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x770` | `0x784` | **`+0x14`** |
| `__DATA.__data` | `0x738` | `0x740` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4e0` | `0x4e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-919.0.0.0.0
+921.0.0.0.0

-  Functions: 3105
+  Functions: 3137

-  CStrings:  6055
+  CStrings:  6102
CStrings:
+ "%s: %{public}@ does not support reminder prompts, ignoring report-use"
+ "%s: HealthKit framework not available, no source name for %{public}@"
+ "%s: HealthKit knows no source name for %{public}@"
+ "%s: automaticTimeOverride=ForceDisabled, not surfacing reminder prompt"
+ "%s: could not create the authorization store for %{public}@"
+ "%s: missing client or service, refusing to enqueue"
+ "%s: no authorization records for %{public}@: %{public}@"
+ "%s: resolved %{public}@ to %{public}@"
+ "%s: source %{public}@ is not an installed bundle"
+ "%s: source fetch failed for %{public}@: %{public}@"
+ "%s: timed out fetching authorization records for %{public}@"
+ "%s: timed out resolving the source name for %{public}@"
+ "-[TCCDReminderMonitor healthSourceNameForBundleIdentifier:]"
+ "-[TCCDReminderMonitor healthSourceNameForBundleIdentifier:]_block_invoke"
+ "A2"
+ "AUTHREQ_CTX: msgID=%{public}@, function=%@, service=%@, query=%llu, client_dict=%@, daemon_dict=%@, attributed_bundle_id=%{public}@"
+ "Invalid attributed bundle identifier: %@"
+ "T@\"NSString\",C,N,V_attributedBundleIdentifier"
+ "T@\"NSString\",C,N,V_attributedDisplayName"
+ "T@\"NSString\",C,N,V_reminderDisplayBundleIdentifier"
+ "TB,N,V_supportsAttributedReportUse"
+ "TCCD_MSG_MESSAGE_OPTION_ATTRIBUTED_BUNDLE_IDENTIFIER_KEY"
+ "Tq,V_automaticTimeOverride"
+ "_attributedBundleIdentifier"
+ "_attributedDisplayName"
+ "_automaticTimeOverride"
+ "_reminderDisplayBundleIdentifier"
+ "_supportsAttributedReportUse"
+ "attributedBundleIdentifier"
+ "attributedDisplayName"
+ "automaticTimeOverride"
+ "characterAtIndex:"
+ "com.apple.os-eligibility-domain.change.carabus"
+ "display_client"
+ "fetchAuthorizationRecordsForBundleIdentifier:error:"
+ "fetchSourcesRequestingAuthorizationForTypes:completion:"
+ "healthSourceNameForBundleIdentifier:"
+ "identifier exceeds maximum length of %lu"
+ "identifier must be printable ASCII"
+ "identifier must be valid UTF-8"
+ "identifier must not be empty"
+ "reminderDisplayBundleIdentifier"
+ "setAttributedBundleIdentifier:"
+ "setAttributedDisplayName:"
+ "setAutomaticTimeOverride:"
+ "setReminderDisplayBundleIdentifier:"
+ "setSupportsAttributedReportUse:"
+ "supportsAttributedReportUse"
+ "v24@?0@\"NSSet\"8@\"NSError\"16"
+ "\xf0\xf0\xf0\xf01\xf0c"
- "A\""
- "AUTHREQ_CTX: msgID=%{public}@, function=%@, service=%@, query=%llu, client_dict=%@, daemon_dict=%@"
- "\xf0\xf0\xf0\xf0!\xf0c"
```
