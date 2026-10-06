## DiagnosticsKit

> `/System/Library/PrivateFrameworks/DiagnosticsKit.framework/DiagnosticsKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x20c4c` | `0x20da0` | **`+0x154`** |
| `__TEXT.__oslogstring` | `0x1bce` | `0x1c0a` | **`+0x3c`** |
| `__TEXT.__cstring` | `0x1cd9` | `0x1d12` | **`+0x39`** |
| `__AUTH_CONST.__cfstring` | `0xf20` | `0xf40` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x818` | `0x820` | **`+0x8`** |

### Other Changes

```diff

-102.0.0.0.0
+103.0.0.0.0

+  - /System/Library/Frameworks/Security.framework/Security

-  Symbols:   1933
-  CStrings:  353
+  Symbols:   1936
+  CStrings:  355
Symbols:
+ -[DKExtensionRequest _entitlementCheckResultForExtensionContext:entitlement:]
+ _CFRelease
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateWithAuditToken
- -[DKExtensionRequest _extensionContext:hasEntitlement:]
Functions:
~ -[DKExtensionRequest beginWithPayload:] : 1024 -> 1052
~ -[DKExtensionRequest _extensionContext:hasEntitlement:] -> -[DKExtensionRequest _entitlementCheckResultForExtensionContext:entitlement:] : 108 -> 396
~ -[DKExtensionRequest beginWithPayload:].cold.1 : 108 -> 132
CStrings:
+ "Unable to verify the diagnostic extension's entitlement."
+ "[RID: %@] Cannot start extension (error %ld)."
+ "[RID: %@] Unable to read extension entitlement '%{public}@': %{public}@"
- "[RID: %@] Cannot start extension. Entitlement is missing."
```
