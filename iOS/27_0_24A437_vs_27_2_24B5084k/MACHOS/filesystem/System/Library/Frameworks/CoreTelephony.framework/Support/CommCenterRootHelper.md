## CommCenterRootHelper

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenterRootHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f94` | `0x5058` | **`+0x20c4`** |
| `__TEXT.__cstring` | `0x449` | `0x71c` | **`+0x2d3`** |
| `__TEXT.__gcc_except_tab` | `0x39c` | `0x658` | **`+0x2bc`** |
| `__TEXT.__auth_stubs` | `0x490` | `0x6b0` | **`+0x220`** |
| `__DATA_CONST.__const` | `0x2b0` | `0x450` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x1f9` | `0x34c` | **`+0x153`** |
| `__DATA_CONST.__auth_got` | `0x250` | `0x360` | **`+0x110`** |
| `__DATA_CONST.__cfstring` | `—` | `0xc0` | **`+0xc0`** |
| `__TEXT.__unwind_info` | `0x218` | `0x2b0` | **`+0x98`** |
| `__DATA.__data` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__const` | `0x2b0` | `0x2c0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA.__bss` | `—` | `0x4` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`

### Other Changes

```diff

-13487.7.0.0.0
+13494.0.0.0.0

-  Functions: 96
-  Symbols:   103
-  CStrings:  32
+  Functions: 122
+  Symbols:   139
+  CStrings:  105
Symbols:
+ _CFArrayCreate
+ _CFBooleanGetTypeID
+ _CFDictionaryGetValue
+ _CFGetTypeID
+ _CFRelease
+ _CFStringCompare
+ _CFStringGetTypeID
+ _MGCopyMultipleAnswers
+ _TelephonyUtilIsOversteerEnabled
+ __ZN3ctu2cf6assignERbPK11__CFBoolean
+ __ZN3xpc19dyn_cast_or_defaultERKNS_6objectEPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE21__grow_by_and_replaceEmmmmmmPKc
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6appendEPKcm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEE6insertEmPKcm
+ __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEC2ERKS5_mmRKS4_
+ __ZNSt3__19to_stringEi
+ __ZNSt3__1plIcNS_11char_traitsIcEENS_9allocatorIcEEEENS_12basic_stringIT_T0_T1_EEPKS6_RKS9_
+ ___CFConstantStringClassReference
+ ___assert_rtn
+ _ether_ntoa
+ _execv
+ _exit
+ _fork
+ _free
+ _freeifaddrs
+ _getifaddrs
+ _getpid
+ _kCFTypeArrayCallBacks
+ _malloc_type_malloc
+ _memchr
+ _memmove
+ _pthread_once
+ _setsid
+ _snprintf
+ _strlen
+ _waitpid
CStrings:
+ " "
+ "%"
+ "%s"
+ "%s%u"
+ "%s: Child pid: %d, Encountered error while waiting. Error: %s"
+ "%s: Child pid: %d, Exited with status: %d, exitStatus: %d"
+ "%s: Child pid: %d, Failed setsid"
+ "%s: Child pid: %d, Failed to execv. Retval: %d, Error: %s"
+ "%s: Failed to fork. Error: %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.2.Internal.sdk/usr/include/c++/v1/__hash_table:1855: libc++ Hardening assertion __p != end() failed: unordered container::erase(iterator) called with a non-dereferenceable iterator\n"
+ "/usr/local/bin/setupOversteerLaunchpad.sh"
+ "/usr/sbin/arp -s "
+ "/usr/sbin/ndp -s "
+ "0 < argc && argc <= MAX_ARGC"
+ "169.254.0."
+ "CarrierInstallCapability"
+ "CmdStruct"
+ "Command: %s"
+ "Couldn't find mac address for interface: %s"
+ "Desense"
+ "Interface"
+ "InternalBuild"
+ "Oversteer"
+ "ReleaseType"
+ "RootHelperServer.cpp"
+ "SetupOversteer"
+ "SetupV4RouterForOversteer"
+ "SetupV6RouterForOversteer"
+ "Unable to get interface addresses for: %s"
+ "V6Router"
+ "Vendor"
+ "VendorNonUI"
+ "argWithPidIdx < argc"
+ "argc == count"
+ "feth0"
+ "feth1"
+ "feth10"
+ "feth11"
+ "feth12"
+ "feth13"
+ "feth14"
+ "feth15"
+ "feth16"
+ "feth17"
+ "feth18"
+ "feth19"
+ "feth2"
+ "feth20"
+ "feth3"
+ "feth4"
+ "feth5"
+ "feth6"
+ "feth7"
+ "feth8"
+ "feth9"
+ "iface < kPeerOffset"
+ "pdp_ip0"
+ "pdp_ip1"
+ "pdp_ip10"
+ "pdp_ip11"
+ "pdp_ip12"
+ "pdp_ip13"
+ "pdp_ip14"
+ "pdp_ip15"
+ "pdp_ip2"
+ "pdp_ip3"
+ "pdp_ip4"
+ "pdp_ip5"
+ "pdp_ip6"
+ "pdp_ip7"
+ "pdp_ip8"
+ "pdp_ip9"
+ "setupV4RouterForOversteer_sync"
+ "setupV6RouterForOversteer_sync"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/include/c++/v1/__hash_table:1855: libc++ Hardening assertion __p != end() failed: unordered container::erase(iterator) called with a non-dereferenceable iterator\n"
```
