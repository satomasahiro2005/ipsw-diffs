## IDS

> `/System/Library/PrivateFrameworks/IDS.framework/IDS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bd37c` | `0x1bdc50` | **`+0x8d4`** |
| `__AUTH.__objc_data` | `0x2168` | `0x1bf0` | **`-0x578`** |
| `__DATA_DIRTY.__objc_data` | `0x1b80` | `0x20f8` | **`+0x578`** |
| `__TEXT.__oslogstring` | `0x1bdf8` | `0x1c0d8` | **`+0x2e0`** |
| `__AUTH_CONST.__cfstring` | `0x7740` | `0x77a0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x11b56` | `0x11bb6` | **`+0x60`** |
| `__AUTH_CONST.__objc_intobj` | `0x588` | `0x5b8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xdc44` | `0xdc64` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x5420` | `0x5438` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x6d50` | `0x6d68` | **`+0x18`** |
| `__AUTH_CONST.__objc_const` | `0x3da18` | `0x3da28` | **`+0x10`** |
| `__DATA.__bss` | `0x9a10` | `0x9a20` | **`+0x10`** |
| `__DATA.__data` | `0x2958` | `0x2948` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x7030` | `0x7040` | **`+0x10`** |

### Other Changes

```diff

-2003.200.33.2.5
+2003.200.44.0.0

-  Functions: 9515
-  Symbols:   1877
-  CStrings:  3892
+  Functions: 9518
+  Symbols:   1880
+  CStrings:  3908
Symbols:
+ _IDSDataChannelDrainingLinkKey
+ _IDSDataChannelDrainingReasonKey
+ _IDSDataChannelPreferenceSupportsLinkDrainingKey
CStrings:
+ "<%@> Can't find the linkContext of draining linkID %u"
+ "<%@> Can't find the linkContext of un-draining linkID %u"
+ "<%@> IDSDataChannelPreferenceSupportsLinkDrainingKey - client %s link draining"
+ "<%@> sent IDSDataChannelEventLinkDrainCancelled, linkID %u"
+ "<%@> sent IDSDataChannelEventLinkDraining, linkID %u, reason: %d"
+ "cancelDrainOfIDSDataChannelLinkContext: connection already closed"
+ "does not support"
+ "drainIDSDataChannelLinkContext: connection already closed"
+ "draining-link-key"
+ "draining-reason"
+ "got drain-cancelled linkID %d, linkUUID %@ (reason byte %d, unused)"
+ "got drainingLinkID %d, linkUUID %@, reason: %d"
+ "kClientChannelMetadataType_LinkDrainCancelled should be %d byte, not %u bytes, field: %u"
+ "kClientChannelMetadataType_LinkDraining should be %d byte, not %u bytes, field: %u"
+ "preference-supports-link-draining"
+ "supports"
```
