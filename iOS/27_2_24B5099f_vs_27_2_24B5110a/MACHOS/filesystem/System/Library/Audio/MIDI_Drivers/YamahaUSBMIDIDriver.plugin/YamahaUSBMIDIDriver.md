## YamahaUSBMIDIDriver

> `/System/Library/Audio/MIDI Drivers/YamahaUSBMIDIDriver.plugin/YamahaUSBMIDIDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e20c` | `0x1e404` | **`+0x1f8`** |
| `__TEXT.__oslogstring` | `0x3c7e` | `0x3dde` | **`+0x160`** |
| `__TEXT.__cstring` | `0x839` | `0x8a2` | **`+0x69`** |
| `__DATA_CONST.__const` | `0xc48` | `0xc60` | **`+0x18`** |
| `__TEXT.__const` | `0x290` | `0x2a0` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xd9c` | `0xd98` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__cfstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-333.202.1.0.0
+333.203.0.0.0

-  CStrings:  354
+  CStrings:  359
Functions:
~ sub_603c : 448 -> 604
~ sub_6434 -> sub_64d0 : 2084 -> 2232
~ sub_13798 -> sub_138c8 : 3344 -> 3544
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
