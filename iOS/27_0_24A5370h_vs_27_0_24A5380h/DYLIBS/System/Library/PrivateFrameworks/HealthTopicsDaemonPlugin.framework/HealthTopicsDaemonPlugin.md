## HealthTopicsDaemonPlugin

> `/System/Library/PrivateFrameworks/HealthTopicsDaemonPlugin.framework/HealthTopicsDaemonPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc2dc` | `0xe918` | **`+0x263c`** |
| `__AUTH_CONST.__objc_const` | `0x720` | `0x848` | **`+0x128`** |
| `__AUTH.__objc_data` | `0x120` | `0x1f0` | **`+0xd0`** |
| `__TEXT.__oslogstring` | `0x44d` | `0x51d` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x291` | `0x341` | **`+0xb0`** |
| `__DATA.__data` | `0x2f8` | `0x398` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x248` | `0x2dc` | **`+0x94`** |
| `__TEXT.__const` | `0x382` | `0x410` | **`+0x8e`** |
| `__TEXT.__objc_methlist` | `0x350` | `0x3d8` | **`+0x88`** |
| `__TEXT.__unwind_info` | `0x258` | `0x2e0` | **`+0x88`** |
| `__TEXT.__swift5_fieldmd` | `0x160` | `0x1e4` | **`+0x84`** |
| `__AUTH_CONST.__auth_got` | `0x690` | `0x710` | **`+0x80`** |
| `__TEXT.__eh_frame` | `0x78` | `0xf8` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x185` | `0x1f5` | **`+0x70`** |
| `__TEXT.__swift5_typeref` | `0x29e` | `0x30c` | **`+0x6e`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d8` | `0x230` | **`+0x58`** |
| `__TEXT.__cstring` | `0x214` | `0x254` | **`+0x40`** |
| `__AUTH.__data` | `—` | `0x30` | **`+0x30`** |
| `__DATA_DIRTY.__data` | `0x398` | `0x3c0` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x70` | `0x80` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x218` | `0x228` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x24` | `0x30` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0xdc` | `0xe4` | **`+0x8`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 175
-  Symbols:   308
-  CStrings:  34
+  Functions: 212
+  Symbols:   340
+  CStrings:  38
Symbols:
+ _OBJC_CLASS_$__TtC24HealthTopicsDaemonPlugin25TopicClientProcessMonitor
+ _OBJC_METACLASS_$__TtC24HealthTopicsDaemonPlugin25TopicClientProcessMonitor
+ __DATA__TtC24HealthTopicsDaemonPlugin25TopicClientProcessMonitor
+ __IVARS__TtC24HealthTopicsDaemonPlugin25TopicClientProcessMonitor
+ __METACLASS_DATA__TtC24HealthTopicsDaemonPlugin25TopicClientProcessMonitor
+ __OBJC_$_INSTANCE_METHODS__TtC24HealthTopicsDaemonPlugin25TopicClientProcessMonitor(HealthTopicsDaemonPlugin)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_HDProcessStateObserver
+ __OBJC_$_PROTOCOL_METHOD_TYPES_HDProcessStateObserver
+ __OBJC_$_PROTOCOL_REFS_HDProcessStateObserver
+ __OBJC_CLASS_PROTOCOLS_$__TtC24HealthTopicsDaemonPlugin25TopicClientProcessMonitor(HealthTopicsDaemonPlugin)
+ __OBJC_LABEL_PROTOCOL_$_HDProcessStateObserver
+ __OBJC_PROTOCOL_$_HDProcessStateObserver
+ ___swift_memcpy16_8
+ __swiftEmptyDictionarySingleton
+ _free
+ _objc_retain_x22
+ _objc_retain_x27
+ _objc_retain_x8
+ _swift_coroFrameAlloc
+ _swift_release_x27
+ _swift_retain_x27
+ _swift_unknownObjectUnownedLoadStrong
+ _swift_unknownObjectWeakAssign
+ _symbolic SDySSShy_____GG 16HealthTopicsCore17TopicRequestTokenV
+ _symbolic Sb
+ _symbolic So21HDProcessStateManagerCSgXw
+ _symbolic _____ 24HealthTopicsDaemonPlugin0cB16ProfileExtensionC12MonitorState33_1676B4BD17048E3ABB93601B06FE64E2LLV
+ _symbolic _____ 24HealthTopicsDaemonPlugin25TopicClientProcessMonitorC
+ _symbolic _____ 24HealthTopicsDaemonPlugin25TopicClientProcessMonitorC5State33_8A56A41A3200AF11720D1088D6636046LLV
+ _symbolic _____Sg 24HealthTopicsDaemonPlugin25TopicClientProcessMonitorC
+ _symbolic _____ySbG 15Synchronization5MutexVAARi_zrlE
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 24HealthTopicsDaemonPlugin0gF16ProfileExtensionC12MonitorState33_1676B4BD17048E3ABB93601B06FE64E2LLV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 24HealthTopicsDaemonPlugin25TopicClientProcessMonitorC5State33_8A56A41A3200AF11720D1088D6636046LLV
+ _type_layout_string 24HealthTopicsDaemonPlugin0cB16ProfileExtensionC12MonitorState33_1676B4BD17048E3ABB93601B06FE64E2LLV
+ _type_layout_string 24HealthTopicsDaemonPlugin25TopicClientProcessMonitorC5State33_8A56A41A3200AF11720D1088D6636046LLV
- _get_type_metadata 15Synchronization5MutexVySbG noncopyable
- _swift_retain_x28
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "HealthTopicsDaemonPlugin.TopicClientProcessMonitor"
+ "TopicClientProcessMonitor: canceling %ld requests for %{public}s (%{public}s)"
+ "TopicClientProcessMonitor: started monitoring %{public}s"
+ "TopicClientProcessMonitor: stopped monitoring %{public}s"
```
