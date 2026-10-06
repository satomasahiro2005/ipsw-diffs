## SystemExtensions

> `/System/Library/Frameworks/SystemExtensions.framework/SystemExtensions`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc08` | `0xb00` | **`-0x108`** |
| `__TEXT.__oslogstring` | `0x24` | `0xa6` | **`+0x82`** |
| `__TEXT.__cstring` | `0x18d` | `0x11c` | **`-0x71`** |
| `__AUTH_CONST.__cfstring` | `0x180` | `0x120` | **`-0x60`** |
| `__DATA_CONST.__got` | `0x60` | `0x70` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x150` | `0x148` | **`-0x8`** |

### Other Changes

```diff

-224.0.2.0.0
+224.0.4.0.0

-  Symbols:   132
-  CStrings:  15
+  Symbols:   129
+  CStrings:  12
Symbols:
+ _NSPOSIXErrorDomain
+ _NSUnderlyingErrorKey
+ _objc_retain_x23
+ _objc_retain_x8
- _CFBooleanGetTypeID
- _CFBooleanGetValue
- _CFGetTypeID
- _SecTaskCopyValueForEntitlement
- _SecTaskCreateFromSelf
- _objc_release_x8
- _objc_retain_x25
Functions:
~ -[OSSystemExtensionsWorkspace systemExtensionsForApplicationWithBundleID:error:] : 1388 -> 1124
CStrings:
+ "Driver approval state query failed: caller is missing the com.apple.developer.system-extension.install entitlement"
+ "Failed to fetch driver approval states: %{public}@"
+ "Missing the com.apple.developer.system-extension.install entitlement"
- "%{public}@"
- "DriverManagement returned nil for %@"
- "Failed to create SecTask"
- "Missing the %@ entitlement"
- "Require com.apple.developer.system-extension.install:true in entitlement"
- "com.apple.developer.system-extension.install"
```
