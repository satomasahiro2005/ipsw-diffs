## AppleIDAMDriver

> `/System/Library/Audio/MIDI Drivers/AppleIDAMDriver.plugin/AppleIDAMDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c334` | `0x1c52c` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x39c8` | `0x3b28` | **`+0x160`** |
| `__TEXT.__cstring` | `0x827` | `0x890` | **`+0x69`** |
| `__DATA_CONST.__const` | `0xb60` | `0xb78` | **`+0x18`** |
| `__TEXT.__gcc_except_tab` | `0xc60` | `0xc5c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-333.202.1.0.0
+333.203.0.0.0

-  CStrings:  359
+  CStrings:  364
Functions:
~ sub_2454 : 448 -> 604
~ sub_26a0 -> sub_273c : 2084 -> 2232
~ sub_650c -> sub_663c : 3344 -> 3544
CStrings:
+ "%25s:%-5d USBDevice::LoadDescriptor - Refusing string descriptor bLength %d into a %zu byte buffer"
+ "%25s:%-5d [!]  FATAL: Could not retrieve Group Terminal Descriptors for USB MIDI interface %d alternate setting %d (error 0x%x)"
+ "%25s:%-5d [!]  FATAL: Expected %u byte(s) of group terminal block descriptors but got %u (error 0x%x)"
+ "%25s:%-5d [!]  FATAL: Rejecting Group Terminal Block descriptor header for USB MIDI interface %d alternate setting %d: %s (headerLength %u, buffer capacity %u): %s"
+ "%25s:%-5d [+] USBDevice::LoadGroupTerminalDescriptors(interface: %d, altSettingNumber: %d, buf:%p, bufCapacity:%zu, len:%d)"
+ "%25s:%-5d [-] USBDevice::LoadGroupTerminalDescriptors() - Refusing to request %u byte(s) into a %zu byte buffer"
+ "incomplete descriptor header"
+ "wTotalLength is not a whole number of descriptors"
+ "wTotalLength out of range"
- "%25s:%-5d      Unexpected group terminal descriptor length: %u"
- "%25s:%-5d      Unexpected total descriptor length: %u"
- "%25s:%-5d [!]  FATAL: Could not retrieve Group Terminal Descriptors for USB MIDI interface %d alternate setting %d. Expected header length %u but got %u"
- "%25s:%-5d [+] USBDevice::LoadGroupTerminalDescriptors(interface: %d, altSettingNumber: %d, buf:%p, len:%d)"
```
