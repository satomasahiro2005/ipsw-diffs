## DMCApps

> `/System/Library/PrivateFrameworks/DMCApps.framework/DMCApps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1758` | `0x18d0` | **`+0x178`** |
| `__TEXT.__text` | `0x366b4` | `0x366a8` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x558` | `0x560` | **`+0x8`** |

### Other Changes

```diff

-105.0.0.0.0
+107.0.0.0.0

-  Symbols:   316
+  Symbols:   317
Symbols:
+ _swift_release_x22
Functions:
~ sub_2214f2c84 -> sub_22236ac84 : 280 -> 276
~ sub_2214f59cc -> sub_22236d9c8 : 80 -> 76
~ sub_2214f8560 -> sub_222370558 : 944 -> 928
~ sub_2214f8d34 -> sub_222370d1c : 944 -> 928
~ sub_2214f92cc -> sub_2223712a4 : 628 -> 616
~ sub_2214f9728 -> sub_2223716f4 : 644 -> 640
~ sub_2214fb3b8 -> sub_222373380 : 3032 -> 3044
~ sub_2214fe074 -> sub_222376048 : 828 -> 812
~ sub_221504f48 -> sub_22237cf0c : 344 -> 340
~ sub_2215051a4 -> sub_22237d164 : 1332 -> 1312
~ sub_2215056d8 -> sub_22237d684 : 272 -> 288
~ sub_2215057e8 -> sub_22237d7a4 : 652 -> 672
~ sub_221506024 -> sub_22237dff4 : 328 -> 332
~ sub_221506d1c -> sub_22237ecf0 : 256 -> 276
~ sub_22150784c -> sub_22237f834 : 152 -> 164
CStrings:
+ " isPreservedAppFor(bundleID: String) called with bundleID: %{public}s!"
+ "App at path %{public}s does not match %{public}s"
+ "Calling self.removeAppForAppID: %{public}s"
+ "Could not ReadPList data from URL: %{public}s"
+ "Creating File on disk: %{public}s !!"
+ "Creating dmfRemoveAppRequest for app: %{public}s"
+ "DMF Fetch Apps Info request returned error: %{public}@!"
+ "DMF Fetch Apps Info request threw error: %{public}@!"
+ "Error creating Features/Migration/ Directory! Error: %{public}s"
+ "Error removing plist from Disk! Error: %{public}s"
+ "Failed to clear preserved apps list with error: %{public}@"
+ "Failed to get code identity for app %{public}s"
+ "Failed to get code identity for extension %{public}s"
+ "Failed to get record for app %{public}s"
+ "Failed to getArrayFromPlistOnDiskAt with Plist Error: %{public}@"
+ "Failed to remove app: %{public}s with error: %{public}@, continuing.."
+ "Failed to write plist: %{public}s, to disk with error: %{public}@ !"
+ "Got code identity %{public}@"
+ "Overriding code identity for bundle: %{public}s"
+ "Path %{public}s does not match record path %{public}s"
+ "ReadPlist(from: url) returned successfully with dict from %{public}s"
+ "ReadPlist(from: url) threw an error: %{public}@!"
+ "Remove App request for app: %{public}s on MDFConnection failed with error: %{public}@"
+ "Resolving which apps need to be removed from this list of preserved apps: %{public}s, based on the list of apps managed by the server: %{public}s !"
+ "Successfully retrieved %{public}ld AppIDs from disk! Returning Set..."
+ "Successfully returned from MDFConnection.perform(dmfRemoveRequest) for appID: %{public}s!"
+ "Successfully returned from self.fetchAppBundleIDs() with %{public}ld bundleIDs"
+ "The apps that need to be removed are: %{public}s"
+ "Unenroll status file exists but could not be removed! Error: %{public}@"
+ "Writing plist: %{public}s to url: %{public}s !"
+ "attempting to remove app: %{public}s on MDFConnection with request: %{public}@"
+ "beginning getPreservedAppIDArrayFromPlistOnDiskAt with url: %{public}s !"
+ "isPreservedAppFor(bundleID: String) returning %{bool,public}d for %{public}s"
+ "writeAppIDPlistToDiskWith failed with error: %{public}@!"
+ "writeAppIDPlistToDiskWith with empty array failed with error: %{public}@!"
+ "writeAppIDPlistToDiskWith with stringArray: %{public}s !"
- " isPreservedAppFor(bundleID: String) called with bundleID: %s!"
- "App at path %s does not match %{public}s"
- "Calling self.removeAppForAppID: %s"
- "Could not ReadPList data from URL: %s"
- "Creating File on disk: %s !!"
- "Creating dmfRemoveAppRequest for app: %s"
- "DMF Fetch Apps Info request returned error: %@!"
- "DMF Fetch Apps Info request threw error: %@!"
- "Error creating Features/Migration/ Directory! Error: %s"
- "Error removing plist from Disk! Error: %s"
- "Failed to clear preserved apps list with error: %@"
- "Failed to get code identity for app %s"
- "Failed to get code identity for extension %s"
- "Failed to get record for app %s"
- "Failed to getArrayFromPlistOnDiskAt with Plist Error: %@"
- "Failed to remove app: %s with error: %@, continuing.."
- "Failed to write plist: %s, to disk with error: %@ !"
- "Got code identity %@"
- "Overriding code identity for bundle: %s"
- "Path %s does not match record path %s"
- "ReadPlist(from: url) returned successfully with dict from %s"
- "ReadPlist(from: url) threw an error: %@!"
- "Remove App request for app: %s on MDFConnection failed with error: %@"
- "Resolving which apps need to be removed from this list of preserved apps: %s, based on the list of apps managed by the server: %s !"
- "Successfully retrieved %ld AppIDs from disk! Returning Set..."
- "Successfully returned from MDFConnection.perform(dmfRemoveRequest) for appID: %s!"
- "Successfully returned from self.fetchAppBundleIDs() with %ld bundleIDs"
- "The apps that need to be removed are: %s"
- "Unenroll status file exists but could not be removed! Error: %@"
- "Writing plist: %s to url: %s !"
- "attempting to remove app: %s on MDFConnection with request: %@"
- "beginning getPreservedAppIDArrayFromPlistOnDiskAt with url: %s !"
- "isPreservedAppFor(bundleID: String) returning %{bool}d for %s"
- "writeAppIDPlistToDiskWith failed with error: %@!"
- "writeAppIDPlistToDiskWith with empty array failed with error: %@!"
- "writeAppIDPlistToDiskWith with stringArray: %s !"
```
