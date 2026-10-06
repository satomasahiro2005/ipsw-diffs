## com.apple.iokit.IOTimeSyncFamily

> `com.apple.iokit.IOTimeSyncFamily`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x32410` | `0x32a78` | **`+0x668`** |
| `__TEXT.__os_log` | `0x8cdf` | `0x8f3a` | **`+0x25b`** |
| `__TEXT.__cstring` | `0x3ee0` | `0x4004` | **`+0x124`** |

### Other Changes

```diff

-1501.6.0.0.0
-  Functions: 1488
+1510.7.0.0.0
+  Functions: 1492

-  CStrings:  730
+  CStrings:  749
CStrings:
+ "  %s(%s): Egress Untimestamped Packet Count: %u, Count since last log entry: %u (timestamping type %u, untimestamped general message mask 0x%x)\n"
+ "  %s(%s): Failed to transmit message of type %s untimestamped packet with error 0x%08x\n"
+ "  %s(%s): Ignoring platform mask 0x%x, boot-arg set mask 0x%x\n"
+ "  %s(%s): No provider, cannot identify the Wi-Fi driver"
+ "  %s(%s): Skip egress timestamp request for general messages, mask 0x%x\n"
+ "  %s(%s): Wi-Fi driver CFBundleIdentifier is \"%s\", chipset %s"
+ "12111112122212121211222121122222121111211112111122222221111111212222222"
+ "1211111212221212121122212112222212111121111211112222222111111121222222211"
+ "1211111212221212121122212112222212111121111211112222222111111121222222222221"
+ "<unreadable>"
+ "AppleBCMWLAN"
+ "AppleCentauriAlpha"
+ "AppleSunriseWLAN"
+ "CFBundleIdentifier"
+ "Skip egress timestamp request for general messages, mask 0x%x\n"
+ "TransmittedEgressUntimestampedCounter"
+ "Unknown"
+ "UntimestampedGeneralMessageMask"
+ "com.apple.AppleSunriseWLAN"
+ "com.apple.DriverKit-AppleBCMWLAN"
+ "com.apple.driver.AppleCentauriAlpha"
+ "timesync_untimestamped_general"
- "121111121222121212112221211222221211112111121111222222211111112122222"
- "12111112122212121211222121122222121111211112111122222221111111212222211"
- "12111112122212121211222121122222121111211112111122222221111111212222222221"
```
