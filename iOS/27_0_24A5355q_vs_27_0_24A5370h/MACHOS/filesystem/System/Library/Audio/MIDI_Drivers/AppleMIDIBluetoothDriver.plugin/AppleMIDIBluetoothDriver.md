## AppleMIDIBluetoothDriver

> `/System/Library/Audio/MIDI Drivers/AppleMIDIBluetoothDriver.plugin/AppleMIDIBluetoothDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x76f` | `0x4d2` | **`-0x29d`** |
| `__TEXT.__text` | `0xd740` | `0xd854` | **`+0x114`** |
| `__TEXT.__gcc_except_tab` | `0x430` | `0x448` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x6c0` | `0x6b0` | **`-0x10`** |
| `__TEXT.__realtime` | `0x348` | `0x338` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x540` | `0x550` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x370` | `0x368` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-328.0.0.0.0
+329.0.0.0.0

-  Functions: 329
-  Symbols:   158
-  CStrings:  578
+  Functions: 328
+  Symbols:   157
+  CStrings:  576
Symbols:
- __ZNSt3__132__internal_log_hardening_failureEPKc
CStrings:
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/c++/previous/list:1420: libc++ Hardening assertion __p != end() failed: list::erase(iterator) called with a non-dereferenceable iterator\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS27.0.Internal.sdk/usr/local/include/c++/previous/span:525: libc++ Hardening assertion __idx < size() failed: span<T>::operator[](index): index out of range\n"
```
