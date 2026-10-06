## CommCenterMobileHelper

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenterMobileHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6e1d4` | `0x6f54c` | **`+0x1378`** |
| `__TEXT.__oslogstring` | `0x35b2` | `0x38f7` | **`+0x345`** |
| `__DATA_CONST.__const` | `0x68c8` | `0x6b90` | **`+0x2c8`** |
| `__TEXT.__cstring` | `0x6721` | `0x65a1` | **`-0x180`** |
| `__TEXT.__unwind_info` | `0x3898` | `0x39d0` | **`+0x138`** |
| `__TEXT.__const` | `0xd4d2` | `0xd5c2` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x8e80` | `0x8f54` | **`+0xd4`** |
| `__TEXT.__objc_stubs` | `0x2900` | `0x2920` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x498` | `0x4a8` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x23a1` | `0x23b1` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xb78` | `0xb80` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-13466.3.0.0.0
+13473.1.0.0.0

-  Functions: 2932
-  Symbols:   621
-  CStrings:  1724
+  Functions: 2997
+  Symbols:   623
+  CStrings:  1735
Symbols:
+ _NSUnderlyingErrorKey
+ _OBJC_CLASS_$_CKDatabaseSubscription
+ __ZNSt3__19to_stringEm
- _objc_retain_x27
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ ":"
+ "Database subscription already exists: %@"
+ "Database subscription created: %@"
+ "Dropping superseded save for %{private}s"
+ "Failed to create database subscription %@: %@"
+ "Failed to set up QuickSwitch database subscription: %d"
+ "Fetch - Manatee identity lost during query for zone: %@"
+ "Fetch - Manatee identity lost for zone: %@"
+ "QuickSwitch-Database"
+ "Save - Manatee identity lost fetching record: %@"
+ "Save - Manatee identity lost for zone: %@"
+ "Save - Manatee identity lost on retry: %@"
+ "Save - Manatee identity lost saving record: %@"
+ "Save pending for %{private}s"
+ "Subscribe - Could not recreate deleted zone: %@ with error: %@"
+ "Subscribe - Manatee identity lost creating zone: %@"
+ "Subscribe - Manatee identity lost for zone: %@"
+ "Subscribe - Manatee identity lost recreating deleted zone: %@"
+ "Subscribe - Zone recreated after user deletion: %@, subscribing"
+ "Subscribe - zone was deleted by user: %@, recreating and signaling data loss"
+ "initWithSubscriptionID:"
+ "saveRecord starting for %{private}s"
+ "subscribe database changes: %s"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1146: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:413: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:418: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:441: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/optional:1121: libc++ Hardening assertion this->has_value() failed: optional operator-> called on a disengaged value\n"
- "Dropping superseded save for %s"
- "Manatee identity lost in %s for zone: %s"
- "Save pending for %s"
- "fetch-query"
- "fetch-zone"
- "save-conflict-retry"
- "save-fetch"
- "save-record"
- "save-zone"
- "saveRecord starting for %s"
- "subscribe-zone"
```
