## managedappdistributiond

> `/System/Library/Frameworks/ManagedAppDistribution.framework/Support/managedappdistributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d7c9c` | `0x6dd1e0` | **`+0x5544`** |
| `__DATA_CONST.__auth_ptr` | `0x5e60` | `0x1ae8` | **`-0x4378`** |
| `__TEXT.__cstring` | `0xf25d` | `0xfdfd` | **`+0xba0`** |
| `__DATA_CONST.__const` | `0x2f008` | `0x2f588` | **`+0x580`** |
| `__TEXT.__eh_frame` | `0x3a178` | `0x3a448` | **`+0x2d0`** |
| `__TEXT.__oslogstring` | `0x15d82` | `0x15ef2` | **`+0x170`** |
| `__TEXT.__unwind_info` | `0x124d0` | `0x125d0` | **`+0x100`** |
| `__TEXT.__const` | `0x3ffb0` | `0x40070` | **`+0xc0`** |
| `__TEXT.__swift5_typeref` | `0x659c` | `0x651c` | **`-0x80`** |
| `__TEXT.__swift_as_cont` | `0x3554` | `0x3584` | **`+0x30`** |
| `__DATA.__data` | `0x10f48` | `0x10f68` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x6ad5` | `0x6af5` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x48c0` | `0x48e0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1f58` | `0x1f70` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x75b8` | `0x75cc` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x19e4` | `0x19f8` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x17f0` | `0x1800` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x7060` | `0x7070` | **`+0x10`** |
| `__DATA.__common` | `0xef0` | `0xef8` | **`+0x8`** |
| `__DATA.__objc_const` | `0x6f00` | `0x6f08` | **`+0x8`** |
| `__DATA.__objc_data` | `0x1ea8` | `0x1ea0` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x3840` | `0x3848` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x141c` | `0x1424` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0xc38` | `0xc40` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x19f0` | `0x19ec` | **`-0x4`** |
| `__TEXT.__swift5_types` | `0xa80` | `0xa7c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-4.0.44.0.0
+4.1.9.0.0

-  Functions: 16573
-  Symbols:   3265
-  CStrings:  4061
+  Functions: 16667
+  Symbols:   3269
+  CStrings:  4095
Symbols:
+ _$s14MarketplaceKit17FetchDataResponseV0E0O19isEUMarketplaceFlowyAESbcAEmFWC
+ _$s14MarketplaceKit19InstallSheetContextV19isEUMarketplaceFlowSbvg
+ _$s14MarketplaceKit19InstallSheetContextV6itemID07versionG06source4type6logKey12learnMoreURL014authenticationE4Data025showBiometricsForAppStoreC019isEUMarketplaceFlowACSS_SSSgAC6SourceOAC0C4TypeOS2S10Foundation0Q0VSgS2btcfC
+ _$s14MarketplaceKit23FetchPrivateDataRequestV0F0O19isEUMarketplaceFlowyA2EmFWC
+ _$s22ManagedAppDistribution0aB6StatusV6ReasonO014couldNotVerifyB2IDyA2EmFWC
+ _$s22ManagedAppDistribution19MessageRegistrationO011marketplaceB7CatalogyA2CmFWC
+ _$s22ManagedAppDistribution19MessageRegistrationO07managedB7CatalogyA2CmFWC
- _$s14MarketplaceKit19InstallSheetContextV6itemID07versionG06source4type6logKey12learnMoreURL014authenticationE4Data025showBiometricsForAppStoreC0ACSS_SSSgAC6SourceOAC0C4TypeOS2S10Foundation0Q0VSgSbtcfC
- _$s22ManagedAppDistribution19MessageRegistrationO10appCatalogyA2CmFWC
- _OBJC_CLASS_$_BSProcessHandle
CStrings:
+ "Allow “@@developerName@@” to Install the App Marketplace “@@marketplaceName@@”?"
+ "Any apps installed from the marketplace will be managed by the developer and may give them access to data from those apps."
+ "Any apps installed will be managed by the developer and may give them access to your child's data from those apps."
+ "Any installed apps will be managed by the developer and may give them access to your data from those apps."
+ "Ignoring unregistered notification for %{public}s - app is still installed"
+ "ManagedAppDistribution.AskForException.YourChildsData.Body.V2"
+ "ManagedAppDistribution.DeveloperApproval.App.UnavailableFeatures.Body.EU"
+ "ManagedAppDistribution.DeveloperApproval.App.UnavailableFeatures.Title.EU"
+ "ManagedAppDistribution.DeveloperApproval.App.YourData.Body.EU"
+ "ManagedAppDistribution.DeveloperApproval.UnavailableFeatures.Body.EU"
+ "ManagedAppDistribution.DeveloperApproval.UnavailableFeatures.Title.EU"
+ "ManagedAppDistribution.DeveloperApproval.YourData.Body.EU"
+ "ManagedAppDistribution.InstallSheet.DeveloperApproval.Title.EU"
+ "ManagedAppDistribution.InstallSheet.Web.App.Body.NoLink.EU"
+ "ManagedAppDistribution.NotAllowed.Message.NoSettingsReference.EU"
+ "ManagedAppDistribution.NotAllowed.iPad.Message.NoSettingsReference.EU"
+ "ManagedAppDistribution.ReplaceSheet.AppStore.Body.NoLink.EU"
+ "ManagedAppDistribution.ReplaceSheet.Marketplace.Alternative.Body.NoLink.EU"
+ "ManagedAppDistribution.ReplaceSheet.Marketplace.Body.NoLink.EU"
+ "ManagedAppDistribution.ReplaceSheet.Web.App.Alternative.Body.NoLink.EU"
+ "ManagedAppDistribution.ReplaceSheet.Web.App.Body.NoLink.EU"
+ "No pinned app declaration found with identifier '%{public}s'"
+ "Unavailable App Store Features"
+ "Updates and purchases in this app will be managed by the developer “@@developerName@@”. Subscriptions and other features may no longer be supported by “@@currentDistributorName@@”. The information below was provided by the developer."
+ "Updates and purchases in this app will be managed by the developer “@@developerName@@”. The information below was provided by the developer."
+ "You will be able to directly install apps by “@@name@@” on this iPad from the web."
+ "You will be able to directly install apps by “@@name@@” on this iPhone from the web."
+ "Your App Store account, stored payment method, subscription management, and refund requests will not be available."
+ "Your in-app purchases and future updates for this app will be managed by App Store. Subscriptions and other features may no longer be supported by “@@currentDistributorName@@”. The information below was provided by the developer."
+ "Your in-app purchases and future updates for this app will be managed by “@@marketplaceName@@”. Subscriptions and other App Store features may no longer be supported. The information below was provided by the developer."
+ "Your in-app purchases and future updates for this app will be managed by “@@marketplaceName@@”. Subscriptions and other features may no longer be supported by “@@currentDistributorName@@”. The information below was provided by the developer."
+ "[%@] Client %{public}s is entitled to no library; refusing registration"
+ "[%@] Install failed with error: %{public}@"
+ "[ProgressCache] Can't update portions for untracked progress %{public}s"
+ "[ProgressCache] Updating progress portions for %{public}s to %{public}s"
+ "handleLaunchRequest(_:requiredDistributor:)"
+ "https://silverbullet.itunes.apple.com/content/e172e47e6c6349a6a03e21b0e4080e2c/app.jetpack"
+ "profileConnectionDidReceiveAllowCloudSyncChangedNotification:userInfo:"
+ "setDefaultMediaTypeForCurrentProcess:"
- "Any installed apps will be managed by the developer and may give them access to your child's data."
- "ManagedAppDistribution.AskForException.YourChildsData.Body"
- "No pinned declaration found with identifier '%{public}s'"
- "http://silverbullet.itunes.apple.com/content/e172e47e6c6349a6a03e21b0e4080e2c/app.jetpack"
- "managedPackageInstallationTaskInit"
```
