## 🔑 Entitlements

### filesystem

### AirDropUI

> `/Applications/AirDropUI.app/AirDropUI`

```diff

+	<key>com.apple.private.menubar.hide-live-activity-settings</key>
+	<true/>

```
### CarPlaySettings

> `/Applications/CarPlaySettings.app/CarPlaySettings`

```diff

+	<key>com.apple.managedconfiguration.profiled-access</key>
+	<true/>
+	<key>com.apple.managedconfiguration.profiled.profile-list-read</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/com.apple.ManagedSettings/EffectiveSettings.plist</string>
+	</array>

+		<string>com.apple.managedconfiguration.profiled</string>
+		<string>com.apple.managedconfiguration.profiled.public</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>.GlobalPreferences</string>

+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.configurationprofiles</string>
+	</array>

```
### CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

```diff

+				<dict>
+					<key>model</key>
+					<integer>3</integer>
+					<key>rssi</key>
+					<integer>-48</integer>
+				</dict>
+				<dict>
+					<key>model</key>
+					<integer>4</integer>
+					<key>rssi</key>
+					<integer>-48</integer>
+				</dict>

+	<key>com.apple.springboard.private.action-button-events</key>
+	<true/>

```
### Diagnostics

> `/Applications/Diagnostics.app/Diagnostics`

```diff

+	<key>com.apple.private.security.system-application</key>
+	<true/>

+	<key>com.apple.springboard.SystemUIScene</key>
+	<true/>

-	<key>com.apple.springboard.sceneaccessory.prototyping</key>
-	<true/>

```
### HomeControlService

> `/Applications/HomeControlService.app/HomeControlService`

```diff

+	<key>com.apple.private.homekit.delegate-granting</key>
+	<true/>

```
### MediaRemoteUIService

> `/Applications/MediaRemoteUIService.app/MediaRemoteUIService`

```diff

+	<key>com.apple.springboard.homeScreenIconStyle</key>
+	<true/>

```
### PassbookUISceneService

> `/Applications/PassbookUISceneService.app/PassbookUISceneService`

```diff

+	<key>com.apple.private.LocalAuthentication.SaveExtractableCredential</key>
+	<true/>

+	<key>com.apple.private.applecredentialmanager.allow</key>
+	<true/>

+	<key>com.apple.security.iokit-user-client-class</key>
+	<array>
+		<string>AppleCredentialManagerUserClient</string>
+	</array>

```
### PassbookUIService

> `/Applications/PassbookUIService.app/PassbookUIService`

```diff

+	<key>com.apple.private.LocalAuthentication.SaveExtractableCredential</key>
+	<true/>

+	<key>com.apple.private.applecredentialmanager.allow</key>
+	<true/>

+	<key>com.apple.security.iokit-user-client-class</key>
+	<array>
+		<string>AppleCredentialManagerUserClient</string>
+	</array>

```
### Preferences

> `/Applications/Preferences.app/Preferences`

```diff

+	<key>com.apple.private.healthcontentd</key>
+	<true/>

+		<string>com.apple.healthcontentd</string>

+		<string>access-ui-data-source</string>

```
### Siri AI

> `/Applications/Siri AI.app/Siri AI`

```diff

+		<string>com.apple.intelligenceflow.contextTool</string>

```
### CoreServicesUIAgent

> `/System/Library/CoreServices/CoreServicesUIAgent.app/CoreServicesUIAgent`

```diff

+	<key>com.apple.frontboard.launchapplications</key>
+	<true/>

```
### GameOverlayUI

> `/System/Library/CoreServices/GameOverlayUI.app/GameOverlayUI`

```diff

+	<key>com.apple.private.amsondevicestoraged</key>
+	<true/>

+		<string>com.apple.amsondevicestoraged.xpc</string>

```
### PhotosViewService

> `/System/Library/CoreServices/PhotosViewService.app/PhotosViewService`

```diff

+	<key>com.apple.springboard.opensensitiveurl</key>
+	<true/>

```
### SpringBoard

> `/System/Library/CoreServices/SpringBoard.app/SpringBoard`

```diff

+	<key>com.apple.manageddeviced.managed-apps.read</key>
+	<true/>

+		<string>com.apple.manageddeviced.managed-apps</string>

```
### osanalyticshelper

> `/System/Library/CoreServices/osanalyticshelper`

```diff

+	<key>application-identifier</key>
+	<string>com.apple.osanalyticshelper</string>

+	<key>com.apple.application-identifier</key>
+	<string>com.apple.osanalyticshelper</string>

```
### AgeVerificationExtension

> `/System/Library/ExtensionKit/Extensions/AgeVerificationExtension.appex/AgeVerificationExtension`

```diff

+	<key>com.apple.private.biometrickit.allow-connect</key>
+	<true/>
+	<key>com.apple.private.biometrickit.allow-default</key>
+	<true/>
+	<key>com.apple.private.biometrickit.allow-match</key>
+	<true/>

```

### 🆕 BTAppDataMigration

> `/System/Library/ExtensionKit/Extensions/BTAppDataMigration.appex/BTAppDataMigration`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.bluetooth.system</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.server.bluetooth.general.xpc</string>
	</array>
</dict>
</plist>

```

### 🆕 FileProviderSupersededAppReplacement

> `/System/Library/ExtensionKit/Extensions/FileProviderSupersededAppReplacement.appex/FileProviderSupersededAppReplacement`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.fileprovider.acl-write</key>
	<true/>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.private.fileprovider.superseded-app-replacement</key>
	<true/>
</dict>
</plist>

```
### InferenceProviderService

> `/System/Library/ExtensionKit/Extensions/InferenceProviderService.appex/InferenceProviderService`

```diff

+	<key>com.apple.generativeexperiences.availabilityService</key>
+	<true/>
+	<key>com.apple.generativeexperiences.availabilityService.updateVersionGatingRules</key>
+	<true/>

+		<string>com.apple.generativeexperiences.availabilityService</string>

```

### 🆕 KeyboardAppMigration

> `/System/Library/ExtensionKit/Extensions/KeyboardAppMigration.appex/KeyboardAppMigration`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>kCFPreferencesAnyApplication</string>
	</array>
</dict>
</plist>

```

### 🆕 PerAppLanguageMigration

> `/System/Library/ExtensionKit/Extensions/PerAppLanguageMigration.appex/PerAppLanguageMigration`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.companionappd.connect.allow</key>
	<true/>
	<key>com.apple.companionappd.preferences.allow</key>
	<true/>
	<key>com.apple.localizationswitcher</key>
	<true/>
	<key>com.apple.nano.nanoregistry.generalaccess</key>
	<true/>
	<key>com.apple.private.security.no-container</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.localizationswitcherd</string>
		<string>com.apple.appconduitd.device-connection</string>
	</array>
	<key>platform-application</key>
	<true/>
</dict>
</plist>

```

### 🆕 PhotoLibraryInstallCoordinationExtension

> `/System/Library/ExtensionKit/Extensions/PhotoLibraryInstallCoordinationExtension.appex/PhotoLibraryInstallCoordinationExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.photos.service.internal.library</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServicePhotos</string>
	</array>
</dict>
</plist>

```
### PrivacyAppIntents

> `/System/Library/ExtensionKit/Extensions/PrivacyAppIntents.appex/PrivacyAppIntents`

```diff

+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>
+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/os_eligibility/eligibility.plist</string>
+	</array>

```
### ProximityReaderNFCExtension

> `/System/Library/ExtensionKit/Extensions/ProximityReaderNFCExtension.appex/ProximityReaderNFCExtension`

```diff

+	<key>com.apple.private.proximity-reader.engagement.customer</key>
+	<true/>

```

### 🆕 ScreenTimeAppDataMigrationExtension

> `/System/Library/ExtensionKit/Extensions/ScreenTimeAppDataMigrationExtension.appex/ScreenTimeAppDataMigrationExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.screen-time</key>
	<true/>
	<key>com.apple.private.screen-time-settings</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.ScreenTimeAgent.private</string>
		<string>com.apple.ScreenTimeSettingsAgent.private</string>
	</array>
</dict>
</plist>

```

### 🆕 ScreenTimeSettingsAppDataMigrationExtension

> `/System/Library/ExtensionKit/Extensions/ScreenTimeSettingsAppDataMigrationExtension.appex/ScreenTimeSettingsAppDataMigrationExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.screen-time-settings</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.ScreenTimeSettingsAgent.private</string>
	</array>
</dict>
</plist>

```

### 🆕 AppleThunderboltSAT_TS

> `/System/Library/Extensions/AppleThunderboltSAT_TS.kext/AppleThunderboltSAT_TS`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.developer.device-information.user-assigned-device-name</key>
	<true/>
	<key>com.apple.private.kernel.get-kext-info</key>
	<true/>
</dict>
</plist>

```

### 🆕 SiriHealthFlowTools

> `/System/Library/FlowTools/Tools/SiriHealthFlowTools.flowtool/SiriHealthFlowTools`

- No entitlements *(yet)*
### assetsd

> `/System/Library/Frameworks/AssetsLibrary.framework/Support/assetsd`

```diff

+		<key>Photos</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Photos.Delete</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>

+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

+		<string>com.apple.biome.access.user</string>
+		<string>com.apple.biome.compute.source</string>

```
### FinanceImageProcessingService

> `/System/Library/Frameworks/FinanceKit.framework/XPCServices/FinanceImageProcessingService.xpc/FinanceImageProcessingService`

```diff

+		<string>com.apple.icloudmailagent.secret.xpc</string>

```
### HomeKitDiagnosticExtension

> `/System/Library/Frameworks/HomeKit.framework/PlugIns/HomeKitDiagnosticExtension.appex/HomeKitDiagnosticExtension`

```diff

+	<key>com.apple.security.app-sandbox</key>
+	<true/>

```

### 🆕 NEAppReplacement

> `/System/Library/Frameworks/NetworkExtension.framework/PlugIns/NEAppReplacement.appex/NEAppReplacement`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.nehelper.privileged</key>
	<true/>
	<key>com.apple.private.networkextension.configuration</key>
	<string>super</string>
</dict>
</plist>

```

### 🆕 PassbookStoragePlugin

> `/System/Library/PreferenceBundles/StoragePlugins/PassbookStoragePlugin.bundle/PassbookStoragePlugin`

- No entitlements *(yet)*
### agentstored

> `/System/Library/PrivateFrameworks/AgentSessionKitRuntime.framework/agentstored`

```diff

+	<key>com.apple.trial.client</key>
+	<array>
+		<string>INTELLIGENCE_PLATFORM_AGENTSESSIONKIT</string>
+	</array>

```
### AirPlaySenderService

> `/System/Library/PrivateFrameworks/AirPlaySenderKit.framework/XPCServices/AirPlaySenderService.xpc/AirPlaySenderService`

```diff

+	<key>com.apple.PairingManager.RemovePeer</key>
+	<true/>

```
### assistant_service

> `/System/Library/PrivateFrameworks/AssistantServices.framework/assistant_service`

```diff

+	<key>com.apple.maps.suggestions.sources</key>
+	<true/>

```
### CategoriesService

> `/System/Library/PrivateFrameworks/Categories.framework/XPCServices/CategoriesService.xpc/CategoriesService`

```diff

+	<key>fairplay-client</key>
+	<string>511712240</string>

```
### chronod

> `/System/Library/PrivateFrameworks/ChronoCore.framework/Support/chronod`

```diff

+		<string>com.apple.linkd.application-service</string>

```
### ACCHWComponentAuthService

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/XPCServices/ACCHWComponentAuthService.xpc/ACCHWComponentAuthService`

```diff

+	<key>com.apple.mobileactivationd.device-identifiers</key>
+	<true/>
+	<key>com.apple.mobileactivationd.spi</key>
+	<true/>

+	<key>com.apple.security.attestation.access</key>
+	<true/>
+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.mobileactivationd</string>
+	</array>

+	<key>keychain-access-groups</key>
+	<array>
+		<string>com.apple.mfiaccessory</string>
+	</array>

```
### DTServiceHub

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/DTServiceHub`

```diff

-	<integer>1</integer>
+	<integer>2</integer>

+	<key>com.apple.private.network.statistics</key>
+	<true/>

```
### LeakAgent

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/LeakAgent`

```diff

+	<key>com.apple.private.runtime-analysis-helper</key>
+	<true/>

```
### RemoteInjectionAgent

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/RemoteInjectionAgent`

```diff

+<?xml version="1.0" encoding="UTF-8"?>
+<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
+<plist version="1.0">
+<dict>
+	<key>com.apple.private.runtime-analysis-helper</key>
+	<true/>
+</dict>
+</plist>

```
### com.apple.dt.instruments.dtsecurity

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/XPCServices/com.apple.dt.instruments.dtsecurity.xpc/com.apple.dt.instruments.dtsecurity`

```diff

-	<integer>1</integer>
+	<integer>2</integer>

```
### DeviceConfigurationAgent

> `/System/Library/PrivateFrameworks/DeviceConfiguration.framework/DeviceConfigurationAgent`

```diff

-		<string>com.apple.deviceconfigurationd.consumer.private.async</string>
+		<string>com.apple.deviceconfigurationd.consumer.private</string>

+	<key>com.apple.security.ts.tmpdir</key>
+	<array>
+		<string>com.apple.DeviceConfigurationAgent</string>
+	</array>

```
### deviceconfigurationd

> `/System/Library/PrivateFrameworks/DeviceConfiguration.framework/deviceconfigurationd`

```diff

+	<key>com.apple.security.ts.tmpdir</key>
+	<array>
+		<string>com.apple.deviceconfigurationd</string>
+	</array>

```
### devicerecoveryd

> `/System/Library/PrivateFrameworks/DeviceRecovery.framework/Support/devicerecoveryd`

```diff

+	<key>com.apple.mobileactivationd.recovery-activation-record</key>
+	<true/>

```
### BluetoothHeadset

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/BluetoothHeadset.appex/BluetoothHeadset`

```diff

+		<string>com.apple.bluetoothuser.xpc</string>

```
### ContinuousRecordingsDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/ContinuousRecordingsDiagnosticExtension.appex/ContinuousRecordingsDiagnosticExtension`

```diff

+	<key>com.apple.system.diagnostics.iokit-properties</key>
+	<true/>

```
### IMDiagnosticExtension

> `/System/Library/PrivateFrameworks/DiagnosticExtensions.framework/PlugIns/IMDiagnosticExtension.appex/IMDiagnosticExtension`

```diff

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.MobileSMS.CKDNDList</string>
+	</array>

```
### donotdisturbd

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/Support/donotdisturbd`

```diff

+		<string>com.apple.linkd.application-service</string>

```
### generativeexperiencesd

> `/System/Library/PrivateFrameworks/GenerativeExperiencesRuntime.framework/generativeexperiencesd`

```diff

+		<string>com.apple.siriactionsd.xpc</string>

+	<key>com.apple.toolkit.request-immediate-indexing.allow</key>
+	<true/>

+	<key>fairplay-client</key>
+	<string>511712240</string>

```
### healthcontentd

> `/System/Library/PrivateFrameworks/HealthContent.framework/healthcontentd`

```diff

-		<string>com.apple.storeservices.itfe</string>

```
### homed

> `/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Support/homed`

```diff

+		<key>com.apple.home-monitoring</key>
+		<string>com.apple.homekit</string>

```
### identityservicesd

> `/System/Library/PrivateFrameworks/IDS.framework/identityservicesd.app/identityservicesd`

```diff

+	<key>com.apple.rapport.AccessPolicy</key>
+	<true/>
+	<key>com.apple.rapport.EndpointContext</key>
+	<true/>

+		<string>com.apple.rapport.AccessPolicy</string>

+	<key>com.apple.tailspin.dump-output</key>
+	<true/>

```
### imagent

> `/System/Library/PrivateFrameworks/IMCore.framework/imagent.app/imagent`

```diff

-		<string>com.apple.MobileSMS.CKDNDList</string>

+		<string>com.apple.MobileSMS.CKDNDList</string>

```
### installcoordinationd

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/Support/installcoordinationd`

```diff

+	<key>com.apple.manageddeviced.managed-apps.read</key>
+	<true/>

+		<string>com.apple.manageddeviced.managed-apps</string>

```
### intelligenceflowd

> `/System/Library/PrivateFrameworks/IntelligenceFlowRuntime.framework/intelligenceflowd`

```diff

+	<key>com.apple.private.mediaexperience.systemcontroller.allowappstoinitiateplayback</key>
+	<true/>

```
### intentrecommendd

> `/System/Library/PrivateFrameworks/IntentRecommendRuntime.framework/intentrecommendd`

```diff

+	<key>com.apple.private.appintents.connection</key>
+	<true/>

+		<string>com.apple.linkd.application-service</string>

```
### navd

> `/System/Library/PrivateFrameworks/MapsSupport.framework/navd`

```diff

+	<key>com.apple.maps.suggestions.sources</key>
+	<true/>

```
### com.apple.photos.VideoConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/XPCServices/com.apple.photos.VideoConversionService.xpc/com.apple.photos.VideoConversionService`

```diff

+	<key>com.apple.TapToRadarKit.service-access</key>
+	<true/>

+	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.TapToRadarKit.service</string>
+	</array>

```
### migrationd

> `/System/Library/PrivateFrameworks/MigrationKit.framework/migrationd`

```diff

+	<key>com.apple.duet.activityscheduler.allow</key>
+	<true/>

```
### accessoryupdaterd

> `/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/Support/accessoryupdaterd`

```diff

-	<key>keychain-access-groups</key>
-	<array>
-		<string>apple</string>
-	</array>

```
### auearlyboot

> `/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/Support/auearlyboot`

```diff

-	<key>keychain-access-groups</key>
-	<array>
-		<string>apple</string>
-	</array>

```
### UARPUpdaterServiceLegacyAudio

> `/System/Library/PrivateFrameworks/MobileAccessoryUpdater.framework/XPCServices/UARPUpdaterServiceLegacyAudio.xpc/UARPUpdaterServiceLegacyAudio`

```diff

-	<key>keychain-access-groups</key>
-	<array>
-		<string>apple</string>
-	</array>

```
### NTKFaceSnapshotService

> `/System/Library/PrivateFrameworks/NanoTimeKit.framework/XPCServices/NTKFaceSnapshotService.xpc/NTKFaceSnapshotService`

```diff

+		<string>com.apple.conversation-intelligence.service</string>
+		<string>com.apple.EligibilityQuorum.com.apple.AudioIntelligence</string>

```
### nanotimekitcompaniond

> `/System/Library/PrivateFrameworks/NanoTimeKit.framework/nanotimekitcompaniond`

```diff

+		<string>com.apple.conversation-intelligence.service</string>
+		<string>com.apple.EligibilityQuorum.com.apple.AudioIntelligence</string>

```
### com.apple.NeighborhoodActivityConduitService

> `/System/Library/PrivateFrameworks/NeighborhoodActivityConduit.framework/XPCServices/com.apple.NeighborhoodActivityConduitService.xpc/com.apple.NeighborhoodActivityConduitService`

```diff

+	<key>com.apple.linkd.registry</key>
+	<true/>

+		<string>com.apple.linkd.registry</string>

```
### passd

> `/System/Library/PrivateFrameworks/PassKitCore.framework/passd`

```diff

+	<key>com.apple.generativeexperiences.availabilityService</key>
+	<true/>

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/eligibilityd/eligibility.plist</string>
+	</array>

+		<string>com.apple.generativeexperiences.availabilityService</string>

+		<string>kCFPreferencesAnyApplication</string>
+		<string>com.apple.gms.availability</string>

```
### ScreenTimeSettingsAgent

> `/System/Library/PrivateFrameworks/ScreenTimeSettingsFoundation.framework/ScreenTimeSettingsAgent`

```diff

+	<key>com.apple.private.tcc.allow</key>
+	<array>
+		<string>kTCCServiceAddressBook</string>
+	</array>

```
### spaceattributiond

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/spaceattributiond`

```diff

+		<string>com.apple.coremedia.figvirtualcapturecard.xpc</string>

```
### imageplaygroundd

> `/System/Library/PrivateFrameworks/SuggestedImage.framework/Support/imageplaygroundd`

```diff

+	<key>com.apple.private.biome.client-identifier</key>
+	<string>com.apple.imageplaygroundd</string>
+	<key>com.apple.private.biome.read-only</key>
+	<array>
+		<string>Photos.Delete</string>
+	</array>

+	<key>com.apple.private.intelligenceplatform.client-identifier</key>
+	<string>com.apple.imageplaygroundd</string>
+	<key>com.apple.private.intelligenceplatform.use-cases</key>
+	<dict>
+		<key>com.apple.imageplaygroundd.PhotosDelete.reader</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>Photos.Delete</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>
+	</dict>

-		<string>com.apple.biome.access.user</string>
+		<string>com.apple.biome.compute.publisher.service.user</string>

+	<key>com.apple.security.ts.mobile-keybag-access</key>
+	<true/>

```
### tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

```diff

+		<string>read</string>

```
### callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

```diff

+	<key>com.apple.private.tcc.manager.access.read</key>
+	<array>
+		<string>kTCCServiceSiriAccess</string>
+	</array>

```
### siriactionsd

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Support/siriactionsd`

```diff

+		<string>com.apple.private.alloy.contextsync</string>
+		<string>com.apple.private.alloy.contextsync.local</string>

```
### webprivacyd

> `/System/Library/PrivateFrameworks/WebPrivacy.framework/webprivacyd`

```diff

+	<key>com.apple.private.imcore.imremoteurlconnection</key>
+	<true/>

+	<key>com.apple.security.exception.mach-lookup.global-name</key>
+	<array>
+		<string>com.apple.duetactivityscheduler</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.ids</string>
+		<string>com.apple.webprivacyd</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.webkit.bag</string>
+	</array>

```
### itunescloudd

> `/System/Library/PrivateFrameworks/iTunesCloud.framework/Support/itunescloudd`

```diff

+	<key>com.apple.private.appintents.connection</key>
+	<true/>

+		<string>com.apple.linkd.application-service</string>

```

### 🆕 SuggestedActionsSettings

> `/System/Library/Settings/SuggestedActionsSettings.settings/SuggestedActionsSettings`

- No entitlements *(yet)*
### AppleTV

> `/private/var/staged_system_apps/AppleTV.app/AppleTV`

```diff

+	<key>com.apple.runningboard.tv</key>
+	<true/>

```
### Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

```diff

+	<key>com.apple.developer.avfoundation.multitasking-camera-access</key>
+	<true/>

```
### FindMy

> `/private/var/staged_system_apps/FindMy.app/FindMy`

```diff

+	<key>com.apple.developer.declared-age-range</key>
+	<true/>

+	<key>com.apple.developer.ubiquity-kvstore-identifier</key>
+	<string>com.apple.findmy</string>

+	<key>com.apple.private.ageRange</key>
+	<true/>

```
### Fitness

> `/private/var/staged_system_apps/Fitness.app/Fitness`

```diff

+	<key>com.apple.chrono.descriptorEnablement</key>
+	<array>
+		<string>com.apple.Fitness.FitnessWidget</string>
+	</array>

+	<key>com.apple.chronoservices</key>
+	<true/>

+	<key>com.apple.private.feedback.drafting</key>
+	<true/>

+		<string>com.apple.chronoservices</string>

+		<string>com.apple.feedbackd.centralized-feedback</string>

```
### Games

> `/private/var/staged_system_apps/Games.app/Games`

```diff

+	<key>com.apple.private.amsondevicestoraged</key>
+	<true/>

+		<string>com.apple.amsondevicestoraged.xpc</string>

```
### Health

> `/private/var/staged_system_apps/Health.app/Health`

```diff

+	<key>com.apple.locationd.place_inference</key>
+	<true/>

```
### Home

> `/private/var/staged_system_apps/Home.app/Home`

```diff

+	<key>com.apple.private.homekit.delegate-granting</key>
+	<true/>

```
### GenerativePlaygroundAppIntents

> `/private/var/staged_system_apps/Image Playground.app/Extensions/GenerativePlaygroundAppIntents.appex/GenerativePlaygroundAppIntents`

```diff

+		<string>com.apple.ciphermld</string>

```
### Maps

> `/private/var/staged_system_apps/Maps.app/Maps`

```diff

+	<key>com.apple.chronoservices</key>
+	<true/>

+	<key>com.apple.maps.suggestions.donations</key>
+	<true/>
+	<key>com.apple.maps.suggestions.predictions</key>
+	<true/>

+	<key>com.apple.maps.suggestions.sources</key>
+	<true/>

-		<string>com.apple.chrono.widgetcenterconnection</string>
+		<string>com.apple.chronoservices</string>

```
### GeneralMapsWidget

> `/private/var/staged_system_apps/Maps.app/PlugIns/GeneralMapsWidget.appex/GeneralMapsWidget`

```diff

+	<key>com.apple.maps.suggestions.donations</key>
+	<true/>
+	<key>com.apple.maps.suggestions.predictions</key>
+	<true/>
+	<key>com.apple.maps.suggestions.signalpipeline</key>
+	<true/>
+	<key>com.apple.maps.suggestions.sources</key>
+	<true/>

+	<key>com.apple.rootless.storage.proactivepredictions</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/DuetExpertCenter/streams/</string>
+	</array>

```
### Music

> `/private/var/staged_system_apps/Music.app/Music`

```diff

+	<key>com.apple.appleaccount.identity.read</key>
+	<true/>

+		<string>com.apple.aa.identity.xpc</string>

```
### Passbook

> `/private/var/staged_system_apps/Passbook.app/Passbook`

```diff

+	<key>com.apple.private.LocalAuthentication.SaveExtractableCredential</key>
+	<true/>

+	<key>com.apple.private.applecredentialmanager.allow</key>
+	<true/>

+		<string>AppleCredentialManagerUserClient</string>

```
### Shortcuts

> `/private/var/staged_system_apps/Shortcuts.app/Shortcuts`

```diff

+	<true/>
+	<key>com.apple.runningboard.assertions.shortcuts</key>

```
### ContinuityCaptureAgent

> `/usr/libexec/ContinuityCaptureAgent`

```diff

+	<key>com.apple.private.avfoundation.capture.toggle-continuity-capture</key>
+	<true/>

```
### aidearlyboot

> `/usr/libexec/aidearlyboot`

```diff

-	<key>keychain-access-groups</key>
-	<array>
-		<string>apple</string>
-	</array>

```
### airplayd

> `/usr/libexec/airplayd`

```diff

+	<key>com.apple.PairingManager.RemovePeer</key>
+	<true/>

```
### asktod

> `/usr/libexec/asktod`

```diff

+	<key>adi-client</key>
+	<string>2132707621</string>

+	<key>com.apple.ams.bag</key>
+	<true/>

+	<key>com.apple.itunesstored.private</key>
+	<true/>
+	<key>com.apple.keystore.absinthe</key>
+	<true/>
+	<key>com.apple.keystore.sik.access</key>
+	<true/>

+	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
+	<array>
+		<string>UniqueDeviceID</string>
+		<string>SerialNumber</string>
+	</array>

+	<key>com.apple.private.applemediaservices</key>
+	<true/>

+		<string>/Library/HTTPStorages/</string>
+		<string>/Library/com.apple.AppleMediaServices/PersistedBags/</string>

+		<string>com.apple.mobile.keybagd.xpc</string>
+		<string>com.apple.fairplayd.versioned</string>

+	<key>com.apple.store.ams.bag</key>
+	<true/>
+	<key>fairplay-client</key>
+	<string>511712240</string>

```
### audioanalyticsd

> `/usr/libexec/audioanalyticsd`

```diff

+	<key>com.apple.security.temporary-exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.assistant.backedup</string>
+	</array>

```
### biomesyncd

> `/usr/libexec/biomesyncd`

```diff

-	<key>com.apple.intelligenceplatform.Coordination</key>
-	<true/>

-		<string>com.apple.intelligenceplatform.Coordination</string>

+		<string>com.apple.biome.compute.source</string>
+		<string>com.apple.biome.compute.source.user</string>

```
### dasd

> `/usr/libexec/dasd`

```diff

+	<key>com.apple.private.iokit.batterydataprecise</key>
+	<true/>

+	<key>com.apple.private.powersource-read</key>
+	<true/>

```
### demod

> `/usr/libexec/demod`

```diff

+	<key>com.apple.private.corespotlight.internal</key>
+	<true/>

```
### diagnosticextensionsd

> `/usr/libexec/diagnosticextensionsd`

```diff

+		<string>group.com.apple.diagnosticextensionsd</string>

+		<string>group.com.apple.diagnosticextensionsd</string>

+		<string>group.com.apple.diagnosticextensionsd</string>

```
### duetexpertd

> `/usr/libexec/duetexpertd`

```diff

+	<key>com.apple.private.appintents.connection</key>
+	<true/>

```
### feedbackd

> `/usr/libexec/feedbackd`

```diff

+		<key>FeedbackDonationBulkDelete</key>
+		<dict>
+			<key>Streams</key>
+			<array>
+				<string>Feedback.TextToTextEvaluationData</string>
+				<string>Feedback.TextToImageEvaluationData</string>
+				<string>Feedback.TextImageToImageEvaluationData</string>
+			</array>
+		</dict>

+		<string>/tmp/</string>

```
### inputanalyticsd

> `/usr/libexec/inputanalyticsd`

```diff

+		<key>GeneratedImageFailureReason</key>
+		<dict>
+			<key>Streams</key>
+			<dict>
+				<key>GenerativeExperiences.GeneratedImageFeatures.FailureReason</key>
+				<dict>
+					<key>mode</key>
+					<string>read-write</string>
+				</dict>
+			</dict>
+		</dict>

```
### mdmd

> `/usr/libexec/mdmd`

```diff

+	<key>com.apple.DeviceRecovery.Control</key>
+	<true/>
+	<key>com.apple.DeviceRecovery.RestrictEraseAndUpdate</key>
+	<true/>

```
### memoryanalyticsd

> `/usr/libexec/memoryanalyticsd`

```diff

+	<key>com.apple.trial.client</key>
+	<array>
+		<string>MEMORY_ANALYSIS_MODEL_LOADING</string>
+	</array>

```
### rapportd

> `/usr/libexec/rapportd`

```diff

+	<key>com.apple.rapport.AccessPolicy</key>
+	<true/>

+		<string>com.apple.rapport.AccessPolicy</string>

```
### remindd

> `/usr/libexec/remindd`

```diff

+	<key>com.apple.duet.activityscheduler.allow</key>
+	<true/>

```
### routined

> `/usr/libexec/routined`

```diff

+		<string>MOMENTS_TRIAL</string>

```
### securepairingd

> `/usr/libexec/securepairingd`

```diff

+	<key>com.apple.TapToRadarKit.service-access</key>
+	<true/>

+		<string>/private/var/mobile/tmp/com.apple.audiomxd/AudioCapture/adm/</string>

```
### toolkitd

> `/usr/libexec/toolkitd`

```diff

+	<key>com.apple.private.ids.messaging</key>
+	<array>
+		<string>com.apple.private.alloy.contextsync</string>
+		<string>com.apple.private.alloy.contextsync.local</string>
+	</array>

```
### tvremoted

> `/usr/libexec/tvremoted`

```diff

+	<key>com.apple.private.homekit.home-location</key>
+	<true/>
+	<key>com.apple.private.homekit.location</key>
+	<true/>

```
### uarpassetmanagerd

> `/usr/libexec/uarpassetmanagerd`

```diff

-	<key>keychain-access-groups</key>
-	<array>
-		<string>apple</string>
-	</array>

```
### uarpd

> `/usr/libexec/uarpd`

```diff

-	<key>com.apple.security.hardened-process.checked-allocation</key>
-	<true/>
-	<key>com.apple.security.hardened-processs.checked-allocations.soft-mode</key>
+	<key>com.apple.security.hardened-process.checked-allocations</key>

```


