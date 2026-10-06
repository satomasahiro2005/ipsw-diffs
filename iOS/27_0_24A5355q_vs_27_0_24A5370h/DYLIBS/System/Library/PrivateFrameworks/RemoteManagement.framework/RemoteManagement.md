## RemoteManagement

> `/System/Library/PrivateFrameworks/RemoteManagement.framework/RemoteManagement`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4be18` | `0x4bd30` | **`-0xe8`** |

### Other Changes

```diff

-621.0.0.502.1
+624.0.3.0.0
Functions:
~ -[ACAccountStore(RemoteManagement) _rm_AccountAssociatedWithRemoteManagementWithAccountTypeIdentifier:altDSID:] : 436 -> 432
~ -[ACAccountStore(RemoteManagement) rm_remoteManagementAccountForAltDSID:] : 348 -> 344
~ -[ACAccountStore(RemoteManagement) rm_remoteManagementAccountForDSID:] : 348 -> 344
~ -[ACAccountStore(RemoteManagement) rm_remoteManagementAccountForIdentifier:] : 348 -> 344
~ -[ACAccountStore(RemoteManagement) rm_remoteManagementAccountForEnrollmentURL:] : 348 -> 344
~ -[ACAccountStore(RemoteManagement) rm_remoteManagementAccountForProfileIdentifier:] : 348 -> 344
~ +[RMMDMHelper _enrollDDMChannelIfNeededWithController:profileIdentifier:enrollmentType:scope:username:personaID:error:] : 2160 -> 2192
~ -[RMXPCNotifications registerForEvents:] : 408 -> 404
~ sub_237e76a44 -> sub_239497a48 : 1596 -> 1592
~ sub_237e773f4 -> sub_2394983f4 : 1668 -> 1684
~ sub_237e78a80 -> sub_239499a90 : 476 -> 480
~ sub_237e78dac -> sub_239499dc0 : 280 -> 276
~ sub_237e7a038 -> sub_23949b048 : 704 -> 696
~ sub_237e7a834 -> sub_23949b83c : 692 -> 684
~ sub_237e7ad84 -> sub_23949bd84 : 412 -> 388
~ sub_237e7b0e0 -> sub_23949c0c8 : 348 -> 340
~ sub_237e7b278 -> sub_23949c258 : 352 -> 344
~ sub_237e7b3d8 -> sub_23949c3b0 : 388 -> 384
~ sub_237e7b55c -> sub_23949c530 : 368 -> 360
~ sub_237e7be14 -> sub_23949cde0 : 344 -> 340
~ sub_237e7bfc4 -> sub_23949cf8c : 328 -> 332
~ sub_237e7c10c -> sub_23949d0d8 : 236 -> 256
~ sub_237e7c1f8 -> sub_23949d1d8 : 256 -> 276
~ sub_237e7c35c -> sub_23949d350 : 240 -> 264
~ sub_237e7c460 -> sub_23949d46c : 224 -> 232
~ sub_237e7c57c -> sub_23949d590 : 244 -> 268
~ sub_237e7cbd0 -> sub_23949dbfc : 272 -> 284
~ sub_237e7cce0 -> sub_23949dd18 : 252 -> 276
~ sub_237e86c24 -> sub_2394a7c74 : 640 -> 624
~ sub_237e86ea4 -> sub_2394a7ee4 : 604 -> 588
~ sub_237e87364 -> sub_2394a8394 : 448 -> 456
~ sub_237e8a128 -> sub_2394ab160 : 496 -> 500
~ sub_237e8a318 -> sub_2394ab354 : 480 -> 492
~ sub_237e8a4f8 -> sub_2394ab540 : 488 -> 500
~ sub_237e8c504 -> sub_2394ad558 : 8744 -> 8396
~ sub_237e8e72c -> sub_2394af624 : 1576 -> 1592
~ sub_237e9b51c -> sub_2394bc424 : 116 -> 132
```
