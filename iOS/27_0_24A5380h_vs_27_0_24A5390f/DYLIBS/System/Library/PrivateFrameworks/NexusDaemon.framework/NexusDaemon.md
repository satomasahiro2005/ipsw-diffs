## NexusDaemon

> `/System/Library/PrivateFrameworks/NexusDaemon.framework/NexusDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x73c30` | `0x73e80` | **`+0x250`** |
| `__TEXT.__cstring` | `0x13aa` | `0x1363` | **`-0x47`** |
| `__AUTH_CONST.__auth_got` | `0xdd0` | `0xde0` | **`+0x10`** |

### Other Changes

```diff

-900.48.0.0.0
+900.55.0.0.0

-  CStrings:  344
+  CStrings:  340
Functions:
~ sub_292424ee4 -> sub_29387bee4 : 6768 -> 6772
~ sub_29247ce64 -> sub_2938d3e68 : 2308 -> 2304
~ sub_29248c994 -> sub_2938e3994 : 1744 -> 1732
~ sub_2924902d0 -> sub_2938e72c4 : 4064 -> 4668
CStrings:
+ ", operations: {reg="
+ "}, requests: {reg="
- "\n== Request Registrations: "
- ", operations: {registered="
- "needsNetwork"
- "operations"
- "requests"
- "}, requests: {registered="
```
