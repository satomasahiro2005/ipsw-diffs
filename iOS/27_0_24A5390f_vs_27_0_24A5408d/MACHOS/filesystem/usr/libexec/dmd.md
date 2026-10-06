## dmd

> `/usr/libexec/dmd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81558` | `0x822c0` | **`+0xd68`** |
| `__TEXT.__oslogstring` | `0xb2a0` | `0xb69f` | **`+0x3ff`** |
| `__TEXT.__cstring` | `0x54ae` | `0x57ff` | **`+0x351`** |
| `__DATA_CONST.__cfstring` | `0x5800` | `0x5920` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0xe980` | `0xea00` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x1186f` | `0x118ed` | **`+0x7e`** |
| `__TEXT.__auth_stubs` | `0xf00` | `0xf60` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x790` | `0x7c0` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x41a0` | `0x41c0` | **`+0x20`** |
| `__TEXT.__const` | `0x168` | `0x180` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x13e0` | `0x13e8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-260.0.0.0.0
+261.2.5.0.0

-  Functions: 3220
-  Symbols:   919
-  CStrings:  4522
+  Functions: 3231
+  Symbols:   926
+  CStrings:  4548
Symbols:
+ _MOScreenTimeShieldPolicyBlocked
+ _close
+ _fts_close
+ _fts_open
+ _fts_read
+ _lstat
+ _open
CStrings:
+ "Requested application %{public}@ is exempt from the application-category shield because its associated site %{private}@ is excluded from the web-category shield"
+ "Requested website %{sensitive}@ is excepted (%{private}@ excluded from the web-category shield); dropping any associated-app direct shield so it does not re-shield via its app"
+ "Requested website %{sensitive}@ is exempt from the web-category shield because its associated app %{public}@ is excluded from the application-category shield"
+ "applicationShieldPolicies"
+ "dmd data vault: dmd_vaultDied_childUnreadable (errno=%d)"
+ "dmd data vault: dmd_vaultDied_cleanButFailed (errno=%d)"
+ "dmd data vault: dmd_vaultDied_dirUnreadable (errno=%d)"
+ "dmd data vault: dmd_vaultDied_notDirectory (errno=%d)"
+ "dmd data vault: dmd_vaultDied_openOther (errno=%d)"
+ "dmd data vault: dmd_vaultDied_ownerOther (errno=%d)"
+ "dmd data vault: dmd_vaultDied_ownerRoot (errno=%d)"
+ "dmd data vault: dmd_vaultDied_statENOENT (errno=%d)"
+ "dmd data vault: dmd_vaultDied_statOther (errno=%d)"
+ "dmd data vault: dmd_vaultDied_symlink (errno=%d)"
+ "excludesIdentifier:"
+ "policyByAddingExcludedIdentifiers:"
+ "policyByRemovingIdentifiers:minimumPriority:"
+ "void dmd_vaultDied_childUnreadable(int)"
+ "void dmd_vaultDied_cleanButFailed(int)"
+ "void dmd_vaultDied_dirUnreadable(int)"
+ "void dmd_vaultDied_notDirectory(int)"
+ "void dmd_vaultDied_openOther(int)"
+ "void dmd_vaultDied_ownerOther(int)"
+ "void dmd_vaultDied_ownerRoot(int)"
+ "void dmd_vaultDied_statENOENT(int)"
+ "void dmd_vaultDied_statOther(int)"
+ "void dmd_vaultDied_symlink(int)"
- "Failed to enable data vault: %@ (%d)"
```
