## VirtualAudio

> `/Library/Audio/Plug-Ins/HAL/VirtualAudio.plugin/VirtualAudio`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x51ba28` | `0x520f00` | **`+0x54d8`** |
| `__TEXT.__gcc_except_tab` | `0x5d220` | `0x5d66c` | **`+0x44c`** |
| `__TEXT.__oslogstring` | `0x559b8` | `0x55c1b` | **`+0x263`** |
| `__TEXT.__realtime` | `0x14af8` | `0x14c20` | **`+0x128`** |
| `__TEXT.__unwind_info` | `0x12bc0` | `0x12cb0` | **`+0xf0`** |
| `__DATA_CONST.__const` | `0x2c198` | `0x2c100` | **`-0x98`** |
| `__TEXT.__cstring` | `0x39ce1` | `0x39c98` | **`-0x49`** |
| `__DATA.__data` | `0x578` | `0x5b8` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x2f00` | `0x2f40` | **`+0x40`** |
| `__TEXT.__const` | `0xb1380` | `0xb1390` | **`+0x10`** |
| `__DATA.__bss` | `0x2c078` | `0x2c080` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__dof_Aggregate`
- `__TEXT.__dof_VirtualA0`
- `__TEXT.__dof_VirtualAu`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1435.1.3.0.0
+1444.0.0.0.0

-  Functions: 12769
+  Functions: 12794

-  CStrings:  12095
+  CStrings:  12105
CStrings:
+ "%25s:%-5d Bluetooth device %u: set %s=1 at publish (VA will drive SW volume)"
+ "%25s:%-5d Bluetooth device %u: set %s=1 at publish failed with %s (BT side may not have adopted yet)"
+ "%25s:%-5d Bluetooth device %u: skip %s at publish (VA policy will drive HW volume on this device)"
+ "%25s:%-5d Clearing custom mic attribution for bundle ID: %s"
+ "%25s:%-5d Device %s: swen=%u set; device advertises swsp=1 so BT-side software volume may still be active via swpe (publish-time)"
+ "%25s:%-5d Re-apply CPMS Power Gain Limit dB: Setting GraphParameter %s for AU %s. Power Limit = %fdB"
+ "%25s:%-5d Setting custom mic attribution for %s to bundle ID: %s"
+ "%25s:%-5d Skipping orientation update for {%s, %s}: AU not present in chain. Likely a configuration error — check the IODelegate plist entry against the chain's wired parameters."
+ "%25s:%-5d Slow AU Initialize for processor type '%s': %.0f ms"
+ "%25s:%-5d Using attributed bundle ID %s for audit token"
+ "%25s:%-5d rdar://177442666: error %s (%d) registering 'balt' listener on object %u"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1161: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1171: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:414: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:419: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:434: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:438: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:442: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:446: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:509: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
+ "@@ Strips Jun 13 2026 05:46:04"
+ "EnableBuiltInMicPlayAndRecordATV"
+ "catchup partnered"
+ "on-demand VAD prefers LP mic"
+ "on-demand VAD prefers LP mic: yes; "
+ "on_demand_vad_lp_mic"
- "%25s:%-5d ASSERTION FAILURE: \"relayListMutex held by the current thread.\""
- "%25s:%-5d EXCEPTION (kAudioHardwareUnspecifiedError) [inputControlDevice is NULL]: \"could not get codec device\""
- "%25s:%-5d EXCEPTION (std::logic_error): \"Invalid state encountered while trying to configure speech detection VAD\""
- "%25s:%-5d Re-apply CPMS Power Gain Limit dB: Setting GraaphParameter %s for AU %s. Power Limit = %fdB"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1146: libc++ Hardening assertion __position != end() failed: vector::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:1156: libc++ Hardening assertion __first <= __last failed: vector::erase(first, last) called with invalid range\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:413: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:418: libc++ Hardening assertion __n < size() failed: vector[] index out of bounds\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:433: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:437: libc++ Hardening assertion !empty() failed: front() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:441: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:445: libc++ Hardening assertion !empty() failed: back() called on an empty vector\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__vector/vector.h:494: libc++ Hardening assertion !empty() failed: vector::pop_back called on an empty vector\n"
- "@@ Strips May 23 2026 13:29:49"
- "Invalid state encountered while trying to configure speech detection VAD"
- "Postcondition failure: au && \"AU not present in DSP Chain\""
```
