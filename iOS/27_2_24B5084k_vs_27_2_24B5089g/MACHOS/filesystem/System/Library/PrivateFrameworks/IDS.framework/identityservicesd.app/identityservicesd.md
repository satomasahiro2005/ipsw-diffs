## identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaea42c` | `0xaeca0c` | **`+0x25e0`** |
| `__TEXT.__oslogstring` | `0x8add3` | `0x8b303` | **`+0x530`** |
| `__TEXT.__cstring` | `0x5b3f9` | `0x5b799` | **`+0x3a0`** |
| `__TEXT.__objc_methname` | `0x7d405` | `0x7d6a5` | **`+0x2a0`** |
| `__DATA_CONST.__cfstring` | `0x378e0` | `0x37a80` | **`+0x1a0`** |
| `__TEXT.__objc_stubs` | `0x4ad40` | `0x4aec0` | **`+0x180`** |
| `__TEXT.__gcc_except_tab` | `0x24b24` | `0x24c98` | **`+0x174`** |
| `__TEXT.__objc_methlist` | `0x2cb54` | `0x2cc1c` | **`+0xc8`** |
| `__TEXT.__unwind_info` | `0x17918` | `0x179d8` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x17278` | `0x172f0` | **`+0x78`** |
| `__TEXT.__objc_methtype` | `0x14509` | `0x14569` | **`+0x60`** |
| `__DATA.__objc_const` | `0x536d8` | `0x53720` | **`+0x48`** |
| `__DATA_CONST.__const` | `0x31758` | `0x31788` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x95a4` | `0x95d4` | **`+0x30`** |
| `__DATA.__objc_data` | `0xfd68` | `0xfd88` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x46c8` | `0x46e0` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x2358` | `0x2370` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x85dc` | `0x85f4` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x9ed4` | `0x9ee0` | **`+0xc`** |
| `__DATA.__common` | `0xe08` | `0xe10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2003.200.33.2.5
+2003.200.44.0.0

-  Functions: 32885
-  Symbols:   2980
-  CStrings:  33468
+  Functions: 32917
+  Symbols:   2983
+  CStrings:  33509
Symbols:
+ _kIDSOffGridEntitlement
+ _kIDSPairedDeviceManagerEntitlement
+ _kIDSPinnedIdentityEntitlement
CStrings:
+ "21:25:19"
+ "<%@> got kClientChannelMetadataType_SupportsLinkDraining %@"
+ "<%@> link:%@ didCancelDrainOfUnderlyingLinkID:%d linkUUID:%@"
+ "<%@> link:%@ willDisconnectUnderlyingLinkID:%d linkUUID:%@, reason: %d"
+ "<%@> need a client channel to send the event kClientChannelMetadataType_LinkDrainCancelled"
+ "<%@> need a client channel to send the event kClientChannelMetadataType_LinkDraining"
+ "AND is_donated = ? LIMIT 1;"
+ "Caller is neither a platform binary nor entitled {entitlement: %{public}@, signingID: %{public}@, connection: %@}"
+ "Failing creation of IDSDXPCOffGridMessenger collaborator {connection: %@}"
+ "Failing creation of IDSDXPCOffGridStateManager collaborator {connection: %@}"
+ "Failing creation of IDSDXPCPairedDeviceManager collaborator {connection: %@}"
+ "Firewall admitting %@ on service %@ because the sender is in the family circle"
+ "FirewallAllowsFamilyCircle"
+ "FirewallMultiCategory"
+ "LIMIT 1;"
+ "Missing pinned identity entitlement and not a platform binary -- failing creation of IDSDXPCPinnedIdentity collaborator {connection: %@}"
+ "Replaying stored messages for categories %@ after donation into category %u"
+ "SELECT COUNT(1) FROM firewall_record WHERE handle = ? AND category "
+ "SELECT COUNT(1) FROM firewall_record WHERE merge_id = ? AND category "
+ "Sep 13 2026"
+ "TB,N,VclientSupportsLinkDraining"
+ "_categoriesFromMask:"
+ "_firewallCategoriesToCheckForService:"
+ "_firewallFamilyCircleAllowsFromURI:service:"
+ "_isFirewallAllowsFamilyCircleEnabled"
+ "_isFirewallMultiCategoryEnabled"
+ "auditToken"
+ "clientSupportsLinkDraining"
+ "controlCategoriesAffectedByDonationInCategory:"
+ "didCancelDrainOfUnderlyingLinkID - alternateDelegate:%@, linkID:%d, linkUUID:%@"
+ "enforcedControlCategories"
+ "got control message: SuspendOTRNegotiationData, too short (%luB)."
+ "isAllowed:inAnyOfCategories:"
+ "isAllowed:inAnyOfCategories:isDonated:"
+ "kClientChannelMetadataType_SupportsLinkDraining should be %d byte, not %u bytes, field: %u"
+ "link:didCancelDrainOfUnderlyingLinkID:linkUUID:"
+ "link:underlyingConnectionDidFailWithLocalAddress:remoteAddress:errorCode:"
+ "link:willDisconnectUnderlyingLinkID:linkUUID:reason:"
+ "setClientSupportsLinkDraining:"
+ "v36@0:8@16c24@\"NSUUID\"28"
+ "v36@0:8@16c24@28"
+ "v44@0:8@16r^{sockaddr=CC[14c]}24r^{sockaddr=CC[14c]}32i40"
+ "willDisconnectUnderlyingLinkID - alternateDelegate:%@, linkID:%d, linkUUID:%@, reason: %d"
- "21:05:06"
- "Sep 11 2026"
```
