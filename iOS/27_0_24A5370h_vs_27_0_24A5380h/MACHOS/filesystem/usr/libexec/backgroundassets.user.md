## backgroundassets.user

> `/usr/libexec/backgroundassets.user`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59a84` | `0x5a17c` | **`+0x6f8`** |
| `__TEXT.__oslogstring` | `0x6b73` | `0x6c83` | **`+0x110`** |
| `__TEXT.__objc_methname` | `0x9c3e` | `0x9cc4` | **`+0x86`** |
| `__TEXT.__eh_frame` | `0x530` | `0x4f8` | **`-0x38`** |
| `__DATA.__objc_const` | `0x5a10` | `0x5a40` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x598` | `0x5c0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x351c` | `0x3544` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x24a0` | `0x24c0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4180` | `0x41a0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x7820` | `0x7840` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1910` | `0x1900` | **`-0x10`** |
| `__TEXT.__const` | `0x1ad8` | `0x1ac8` | **`-0x10`** |
| `__DATA.__data` | `0x12e8` | `0x12e0` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x21b0` | `0x21b8` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xc98` | `0xc90` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1450` | `0x1448` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x6f4` | `0x6ee` | **`-0x6`** |
| `__DATA.__objc_ivar` | `0x3b4` | `0x3b8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-271.0.0.0.0
+274.0.0.0.0

-  Symbols:   701
-  CStrings:  2604
+  Symbols:   696
+  CStrings:  2609
Symbols:
- _$ss5NeverON
- _$ss5NeverOs5ErrorsWP
- _$sytN
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "%@ (%p)\nApp Bundle Identifier: %@\nDownloads (%lu): {\n"
+ "%@ (%p): [ID:%@, AppBundleID:%@, Necessity:%@]"
+ "A bundle record couldn’t be looked up for the app bundle identifier “%{public}@”: %{public}@"
+ "App Bundle Identifier: %@\nInitial (Optional Download Allowance: %llu\nInitial (Essential Download Allowance: %llu\nAmount Downloaded (Optional): %llu\nAmount Downloaded (Essential): %llu\nReceived Installing Notification: %@\nReceived Installed Notification: %@\nAllowed Domains: %@\nLast Check Time: %@\nApp Has Been Launched: %@\nLast Launch Time: %@\nExtension Runtime In Last 24h: %lf"
+ "App bundle identifier (%{public}@) is not valid Universal Type Identifier. Failing."
+ "App bundle identifier is nil or 0 length"
+ "App bundle identifier: %@\n"
+ "Application (%{public}@) is on-screen but suspended (no action taken)."
+ "Client Connection\nApp Bundle Identifier: %@\nClient Identifier: %@\nPID: %d\nIs Client App: %@"
+ "Creating a new streaming extractor for the download with the identifier “%{public}@” for the application with bundle identifier “%{public}@” because the download is for a managed asset pack…"
+ "Download queue (%{public}@) re-promoted %lu previously-demoted foreground downloads."
+ "Dropping download because app bundle identifier is invalid: %{public}@"
+ "Event (Canceled) dropped for client (%{public}@) failed because there is no app-info matching the bundle identifier."
+ "Extension for app-bundle identifier %{public}@ ran for %{public}.1f seconds."
+ "Failed to get bundle record for bundle identifier: %{public}@ error: %{public}@"
+ "Invalid app bundle identifier supplied: %@"
+ "Requested background activity for app-bundle identifier that is not known to BAAgentCore. %{public}@"
+ "Retrieving the manifest data source for the application with the bundle identifier “%{public}@” because it uses Apple hosting…"
+ "T@\"NSString\",&,N,V_appBundleIdentifier"
+ "T@\"NSString\",&,V_appBundleIdentifier"
+ "T@\"NSString\",R,V_appBundleIdentifier"
+ "TB,V_wasForegroundDownload"
+ "The application with bundle identifier “%{public}@” is ineligible for development overrides."
+ "The application with the bundle identifier “%{public}@” doesn’t use Apple hosting."
+ "The application with the bundle identifier “%{public}@” doesn’t use Managed Background Assets."
+ "The application with the bundle identifier “%{public}@” is configured to use Apple hosting."
+ "The application with the bundle identifier “%{public}@” lacks a string team identifier in its connection request."
+ "The application with the bundle identifier “%{public}@” uses Managed Background Assets with third-party hosting."
+ "The extension-point identifier, “%{public}@”, of the application extension with the bundle identifier “%{public}@” doesn’t match the expected extension-point identifier, “%{public}@”."
+ "The manifest URL for the application with the bundle identifier “%{public}@” was rewritten as “%{public}@”."
+ "The manifest data source for the application with the bundle identifier “%{public}@” couldn’t be retrieved: %{public}@"
+ "The manifest data source for the application with the bundle identifier “%{public}@” is “%ld”."
+ "The team identifier, “%{public}@”, in a connection request from the application with the bundle identifier “%{public}@” doesn’t match the recorded team identifier, “%{public}@”, for that application."
+ "Using the development-override URL “%{public}@” for the application with the bundle identifier “%{public}@”…"
+ "_appBundleIdentifierAllowsBackgroundActivity:"
+ "_connectionsForApplicationBundleIdentifier:"
+ "_downloaderExtensionForApplicationBundleIdentifier:cacheOnly:"
+ "_isAppInstalledForBundleIdentifier:"
+ "_wasForegroundDownload"
+ "downloaderExtensionForApplicationBundleIdentifier:cacheOnly:"
+ "initWithAppBundleIdentifier:delegate:"
+ "initWithContentRequest:appBundleIdentifier:installSource:downloads:"
+ "installationSourceFromAuditToken:applicationBundleIdentifier:"
+ "promoteAllPreviouslyDemotedDownloads"
+ "send-telemetry-event was called without specifying an app bundle identifier."
+ "setAppBundleIdentifier:"
+ "setWasForegroundDownload:"
+ "updateApplicationInformationForIdentifier:bundleURLPath:applicationRecordPtr:"
+ "wasForegroundDownload"
- "%@ (%p)\nApplication Identifier: %@\nDownloads (%lu): {\n"
- "%@ (%p): [ID:%@, AppID:%@, Necessity:%@]"
- "A bundle record couldn’t be looked up for the application identifier “%{public}@”: %{public}@"
- "App identifier is nil or 0 length"
- "Application Identifier: %@\nInitial (Optional Download Allowance: %llu\nInitial (Essential Download Allowance: %llu\nAmount Downloaded (Optional): %llu\nAmount Downloaded (Essential): %llu\nReceived Installing Notification: %@\nReceived Installed Notification: %@\nAllowed Domains: %@\nLast Check Time: %@\nApp Has Been Launched: %@\nLast Launch Time: %@\nExtension Runtime In Last 24h: %lf"
- "Application identifier (%{public}@) is not valid Universal Type Identifier. Failing."
- "Application identifier: %@\n"
- "Client Connection\nApp Identifier: %@\nClient Identifier: %@\nPID: %d\nIs Client App: %@"
- "Creating a new streaming extractor for the download with the identifier “%{public}@” for the application with the identifier “%{public}@” because the download is for a managed asset pack…"
- "Dropping download because application identifier is invalid: %{public}@"
- "Event (Canceled) dropped for client (%{public}@) failed because there is no app-info matching the identifier."
- "Extension for app identifier %{public}@ ran for %{public}.1f seconds."
- "Failed to get bundle record for identifier: %{public}@ error: %{public}@"
- "Invalid application identifier supplied: %@"
- "Requested background activity for application identifier that is not known to BAAgentCore. %{public}@"
- "Retrieving the manifest data source for the application with the identifier “%{public}@” because it uses Apple hosting…"
- "T@\"NSString\",&,N,V_applicationIdentifier"
- "T@\"NSString\",&,V_applicationIdentifier"
- "T@\"NSString\",R,V_identifier"
- "The application with the identifier “%{public}@” doesn’t use Apple hosting."
- "The application with the identifier “%{public}@” doesn’t use Managed Background Assets."
- "The application with the identifier “%{public}@” is configured to use Apple hosting."
- "The application with the identifier “%{public}@” is ineligible for development overrides."
- "The application with the identifier “%{public}@” lacks a string team identifier in its connection request."
- "The application with the identifier “%{public}@” uses Managed Background Assets with third-party hosting."
- "The extension-point identifier, “%{public}@”, of the application extension with the identifier “%{public}@” doesn’t match the expected extension-point identifier, “%{public}@”."
- "The manifest URL for the application with the identifier “%{public}@” was rewritten as “%{public}@”."
- "The manifest data source for the application with the identifier “%{public}@” couldn’t be retrieved: %{public}@"
- "The manifest data source for the application with the identifier “%{public}@” is “%ld”."
- "The team identifier, “%{public}@”, in a connection request from the application with the identifier “%{public}@” doesn’t match the recorded team identifier, “%{public}@”, for that application."
- "Using the development-override URL “%{public}@” for the application with the identifier “%{public}@”…"
- "_applicationIdentifier"
- "_applicationIdentifierAllowsBackgroundActivity:"
- "_applicationIdentifierIsInstalled:"
- "_connectionsForApplicationIdentifier:"
- "_downloaderExtensionForApplicationIdentifier:cacheOnly:"
- "bundleRecordWithApplicationIdentifier:error:"
- "downloaderExtensionForApplicationIdentifier:cacheOnly:"
- "initWithApplicationIdentifier:delegate:"
- "initWithContentRequest:applicationIdentifier:installSource:downloads:"
- "installationSourceFromAuditToken:applicationIdentifier:"
- "send-telemetry-event was called without specifying an application identifier."
- "setApplicationIdentifier:"
- "updateApplicationInformationForIdentifier:bundleURLPath:"
```
