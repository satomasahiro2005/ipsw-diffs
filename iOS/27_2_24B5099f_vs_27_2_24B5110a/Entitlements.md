## 🔑 Entitlements

### filesystem

### AskPermissionUI

> `/Applications/AskPermissionUI.app/AskPermissionUI`

```diff

+	<key>adi-client</key>
+	<string>409835401</string>

+	<key>com.apple.private.adid</key>
+	<true/>

+		<string>com.apple.adid</string>

+		<string>com.apple.fairplayd.versioned</string>

+		<string>com.apple.mobileactivationd</string>

+	<key>fairplay-client</key>
+	<string>1445028844</string>

```
### ClarityPhotos

> `/Applications/ClarityPhotos.app/ClarityPhotos`

```diff

+	<key>com.apple.security.exception.files.home-relative-path.read-write</key>
+	<array>
+		<string>/Media/PhotoData/Caches/</string>
+		<string>/Media/PhotoData/PhotoCloudSharingData/</string>
+	</array>

```
### CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

```diff

+		<key>AddUser</key>
+		<dict>
+			<key>bleRSSIThresholdHint</key>
+			<integer>-45</integer>
+			<key>denyProductList</key>
+			<array>
+				<string>iPad7,11</string>
+				<string>iPad7,12</string>
+				<string>iPhone11,2</string>
+				<string>iPhone11,4</string>
+				<string>iPhone11,6</string>
+				<string>iPhone11,8</string>
+			</array>
+			<key>discoveryTypes</key>
+			<array>
+				<string>AddUser</string>
+			</array>
+			<key>sceneIdentifier</key>
+			<string>addUser</string>
+			<key>screenLocked</key>
+			<true/>
+			<key>setupDone</key>
+			<true/>
+			<key>systemUnlocked</key>
+			<true/>
+		</dict>

+				<dict>
+					<key>model</key>
+					<integer>5</integer>
+					<key>rssi</key>
+					<integer>-48</integer>
+				</dict>
+				<dict>
+					<key>model</key>
+					<integer>10</integer>
+					<key>rssi</key>
+					<integer>-45</integer>
+				</dict>
+				<dict>
+					<key>model</key>
+					<integer>11</integer>
+					<key>rssi</key>
+					<integer>-45</integer>
+				</dict>

+		<string>com.apple.MobileAsset.UAF.Siri.TextToSpeech</string>

+		<string>/Library/Caches/com.apple.homed/Snapshots/</string>

+		<string>com.apple.mobileasset.autoasset</string>

+		<string>com.apple.proactive.DefaultWidgetSuggester</string>

+		<string>com.apple.siri.orchestration.capabilities</string>
+		<string>com.apple.siri.uaf.service</string>
+		<string>com.apple.siri.uaf.subscription.service</string>

+		<string>com.apple.assistant.backedup</string>

+		<string>com.apple.proactive.DefaultWidgetSuggester</string>

```
### Diagnostic-8357

> `/Applications/DiagnosticsService.app/PlugIns/Diagnostic-8357.appex/Diagnostic-8357`

```diff

+	<key>com.apple.private.diagnostic-intelligence</key>
+	<true/>

+		<string>/private/var/mobile/Library/Logs/CrashReporter/</string>

+		<string>com.apple.diagnosticservicesd</string>

```
### HeadphoneProxService

> `/Applications/HeadphoneProxService.app/HeadphoneProxService`

```diff

+	<key>com.apple.corespeech.uitrainingservice</key>
+	<true/>

```
### HomeControlService

> `/Applications/HomeControlService.app/HomeControlService`

```diff

+	<key>com.apple.private.home.extension-host</key>
+	<true/>

+	<key>com.apple.private.tcc.manager.access.modify</key>
+	<array>
+		<string>kTCCServiceWillow</string>
+	</array>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceWillow</string>
+	</array>
+	<key>com.apple.runningboard.home-extensions</key>
+	<true/>

```

### 🆕 HomeProximityDynamicIslandUIService

> `/Applications/HomeProximityDynamicIslandUIService.app/HomeProximityDynamicIslandUIService`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.Home.ProximityDynamicIslandUIService</string>
	<key>com.apple.QuartzCore.secure-mode</key>
	<true/>
	<key>com.apple.developer.homekit</key>
	<true/>
	<key>com.apple.frontboard.launchapplications</key>
	<true/>
	<key>com.apple.homekit.private-spi-access</key>
	<true/>
	<key>com.apple.private.homekit.allow-secure-access</key>
	<true/>
	<key>com.apple.private.sessionkit.custom-platter-target</key>
	<true/>
	<key>com.apple.private.sessionkit.permitMultipleProcessInputs</key>
	<true/>
	<key>com.apple.private.sessionkit.sessionRequest</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceWillow</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.matter.native.xpc</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.matter.native.xpc</string>
	</array>
	<key>com.apple.springboard.remote-alert</key>
	<true/>
</dict>
</plist>

```
### HomeUIService

> `/Applications/HomeUIService.app/HomeUIService`

```diff

+	<key>com.apple.corespeech.uitrainingservice</key>
+	<true/>

+	<key>com.apple.security.exception.sysctl.read-only</key>
+	<array>
+		<string>kern.exclaves_status</string>
+	</array>

```
### InCallService

> `/Applications/InCallService.app/InCallService`

```diff

+	<key>com.apple.conversation-accessibility.required-host-entitlement</key>
+	<true/>

```
### Preferences

> `/Applications/Preferences.app/Preferences`

```diff

+	<key>com.apple.duetexpertd.assistant-actions</key>
+	<true/>

```
### Setup

> `/Applications/Setup.app/Setup`

```diff

+	<key>com.apple.corespeech.uitrainingservice</key>
+	<true/>

+	<key>com.apple.siri.VoiceShortcuts.xpc</key>
+	<true/>

```
### SharingViewService

> `/Applications/SharingViewService.app/SharingViewService`

```diff

+	<key>com.apple.corespeech.uitrainingservice</key>
+	<true/>

```
### Siri AI

> `/Applications/Siri AI.app/Siri AI`

```diff

+	<key>com.apple.carousel.nonmatchingsessions</key>
+	<true/>

+	<key>com.apple.private.appintents.live-entities.read</key>
+	<true/>

+		<string>com.apple.appintents.LiveEntityService</string>

+		<string>com.apple.carousel.sessionservice</string>

```
### AccessibilityUIServer

> `/System/Library/CoreServices/AccessibilityUIServer.app/AccessibilityUIServer`

```diff

+	<key>com.apple.AXMediaUtilitiesService-access</key>
+	<true/>

+		<string>com.apple.AXMediaUtilitiesService</string>

+		<string>com.apple.AXMediaUtilitiesService</string>

```
### CarPlay

> `/System/Library/CoreServices/CarPlay.app/CarPlay`

```diff

+	<key>com.apple.manageddeviced.managed-apps.read</key>
+	<true/>

+		<string>com.apple.manageddeviced.managed-apps</string>

```
### ClarityBoard

> `/System/Library/CoreServices/ClarityBoard.app/ClarityBoard`

```diff

+	<key>com.apple.manageddeviced.managed-apps.read</key>
+	<true/>

+		<string>com.apple.manageddeviced.managed-apps</string>

```
### CoreServicesUIAgent

> `/System/Library/CoreServices/CoreServicesUIAgent.app/CoreServicesUIAgent`

```diff

+	<key>com.apple.manageddeviced.managed-apps.read</key>
+	<true/>

+		<string>com.apple.manageddeviced.managed-apps</string>

```

### 🆕 MobileDevices-0004

> `/System/Library/CoreServices/CoreTypes.bundle/Contents/Library/MobileDevices-0004.bundle/MobileDevices-0004`

- No entitlements *(yet)*
### GameOverlayUI

> `/System/Library/CoreServices/GameOverlayUI.app/GameOverlayUI`

```diff

+	<key>com.apple.private.servicesintelligence</key>
+	<true/>

```

### 🆕 HomeDeveloperSettingsIntents

> `/System/Library/ExtensionKit/Extensions/HomeDeveloperSettingsIntents.appex/HomeDeveloperSettingsIntents`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.private.appintents.attribution.bundle-identifier</key>
	<string>com.apple.Preferences</string>
</dict>
</plist>

```
### QuickLookUIExtension

> `/System/Library/ExtensionKit/Extensions/QuickLookUIExtension.appex/QuickLookUIExtension`

```diff

+		<string>com.apple.visualintelligence.visual-action-prediction</string>

+	<key>com.apple.visualintelligence.private.visual-action-prediction</key>
+	<true/>

```
### TextInputAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/TextInputAppIntentsExtension.appex/TextInputAppIntentsExtension`

```diff

-<dict/>
+<dict>
+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.keyboard.preferences</string>
+		<string>com.apple.assistant.support</string>
+	</array>
+</dict>

```

### 🆕 HomeDeveloperSettings

> `/System/Library/PreferenceBundles/HomeDeveloperSettings.bundle/HomeDeveloperSettings`

- No entitlements *(yet)*
### CategoriesService

> `/System/Library/PrivateFrameworks/Categories.framework/XPCServices/CategoriesService.xpc/CategoriesService`

```diff

+	<key>com.apple.private.applemediaservices</key>
+	<true/>

```
### donotdisturbd

> `/System/Library/PrivateFrameworks/DoNotDisturbServer.framework/Support/donotdisturbd`

```diff

+	<key>com.apple.private.appintents.connection</key>
+	<true/>

```

### 🆕 MedicalIDFollowUpExtension

> `/System/Library/PrivateFrameworks/HealthAppSupport.framework/PlugIns/MedicalIDFollowUpExtension.appex/MedicalIDFollowUpExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.developer.healthkit</key>
	<true/>
	<key>com.apple.private.attribution.implicitly-assumed-identity</key>
	<dict>
		<key>type</key>
		<string>bundleID</string>
		<key>value</key>
		<string>com.apple.Health</string>
	</dict>
	<key>com.apple.private.followup</key>
	<true/>
	<key>com.apple.private.healthkit</key>
	<true/>
	<key>com.apple.private.healthkit.medicaliddata</key>
	<true/>
	<key>com.apple.private.tcc.allow-or-regional-prompt.overridable</key>
	<array>
		<string>kTCCServiceAddressBook</string>
	</array>
	<key>com.apple.private.tcc.allow.overridable</key>
	<array>
		<string>kTCCServiceCamera</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.corefollowup.agent</string>
		<string>com.apple.healthappd</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.private.healthkit.medicaliddata</string>
		<string>com.apple.private.healthkit</string>
	</array>
	<key>com.apple.springboard.opensensitiveurl</key>
	<true/>
</dict>
</plist>

```
### homed

> `/System/Library/PrivateFrameworks/HomeKitDaemon.framework/Support/homed`

```diff

+	<key>com.apple.intelligentrouting.recommendationservice</key>
+	<true/>

+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>

+	<key>com.apple.private.home.extension-host</key>
+	<true/>

+		<string>/private/var/containers/Bundle/</string>

+		<string>com.apple.intelligentroutingd.xpc.media</string>

+		<string>com.apple.audio.SystemSoundServer-iOS</string>

+	<key>com.apple.security.temporary-exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/containers/Bundle/</string>
+	</array>

```
### intelligencecontextd

> `/System/Library/PrivateFrameworks/IntelligenceFlowContextRuntime.framework/intelligencecontextd`

```diff

-	<key>com.apple.developer.homekit</key>
-	<true/>

-	<key>com.apple.private.homekit</key>
-	<true/>

-		<string>com.apple.homed.xpc</string>

-		<string>com.apple.homed</string>

```
### com.apple.NeighborhoodActivityConduitService

> `/System/Library/PrivateFrameworks/NeighborhoodActivityConduit.framework/XPCServices/com.apple.NeighborhoodActivityConduitService.xpc/com.apple.NeighborhoodActivityConduitService`

```diff

+	<key>com.apple.conversation-accessibility.required-host-entitlement</key>
+	<true/>

+	<key>com.apple.private.assets.accessible-asset-types</key>
+	<array>
+		<string>com.apple.MobileAsset.phoneNumberResolver</string>
+	</array>

+	<key>com.apple.private.communicationsfilter</key>
+	<true/>

+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>

+	<key>com.apple.private.ids.idquery-cache</key>
+	<true/>

+	<key>com.apple.private.ids.phone-number-authentication</key>
+	<true/>

+	<key>com.apple.private.ids.report-spam-message</key>
+	<true/>

+	<key>com.apple.private.imcore.imremoteurlconnection</key>
+	<true/>
+	<key>com.apple.private.imcore.spi.database-access</key>
+	<true/>

+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/Caches/com.apple.businessservicesd/</string>
+	</array>

+		<string>com.apple.businessservicesd</string>
+		<string>com.apple.identityservicesd.idquery.embedded.auth</string>
+		<string>com.apple.incoming-call-filter-server</string>

+	<key>com.apple.system.get-alert-tone</key>
+	<true/>

```

### 🆕 pebbleplayd

> `/System/Library/PrivateFrameworks/PebblePlayDaemon.framework/pebbleplayd`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>com.apple.appprotectiond.read.access</key>
	<true/>
	<key>com.apple.avfoundation.allow-system-wide-context</key>
	<true/>
	<key>com.apple.avfoundation.allows-access-to-device-list</key>
	<true/>
	<key>com.apple.avfoundation.allows-set-output-device</key>
	<true/>
	<key>com.apple.developer.device-information.user-assigned-device-name</key>
	<true/>
	<key>com.apple.frontboard.launchapplications</key>
	<true/>
	<key>com.apple.linkd.registry</key>
	<true/>
	<key>com.apple.mediaremote.now-playing-read-access</key>
	<true/>
	<key>com.apple.private.MobileContainerManager.lookup</key>
	<dict>
		<key>appData</key>
		<true/>
	</dict>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.private.dmd.policy</key>
	<true/>
	<key>com.apple.private.mediaexperience.systemcontroller.allowappstoinitiateplayback</key>
	<true/>
	<key>com.apple.private.mobileinstall.allowedSPI</key>
	<array>
		<string>CreateSerializedPlaceholder</string>
	</array>
	<key>com.apple.runningboard.assertions.frontboard</key>
	<true/>
	<key>com.apple.runningboard.endowment-originator</key>
	<true/>
	<key>com.apple.runningboard.invalidateanyassertion</key>
	<true/>
	<key>com.apple.runningboard.launchprocess</key>
	<true/>
	<key>com.apple.runningboard.primitiveattribute</key>
	<true/>
	<key>com.apple.runningboard.targetidentities</key>
	<true/>
	<key>com.apple.runningboard.terminateprocess</key>
	<true/>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.mobile.installd</string>
		<string>com.apple.dmd.policy</string>
		<string>com.apple.lsd.xpc</string>
		<string>com.apple.linkd.registry</string>
		<string>com.apple.misagent</string>
		<string>com.apple.mobile.keybagd.UserManager.xpc</string>
		<string>com.apple.mobile.usermanagerd.xpc</string>
	</array>
	<key>com.apple.security.exception.shared-preference.read-write</key>
	<array>
		<string>com.apple.newscore</string>
		<string>com.apple.newscore2</string>
	</array>
	<key>com.apple.security.network.server</key>
	<true/>
	<key>com.apple.security.ts.read-any-bundle</key>
	<true/>
</dict>
</plist>

```
### callservicesd

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/callservicesd`

```diff

+	<key>com.apple.conversation-accessibility.required-host-entitlement</key>
+	<true/>

```
### siriactionsd

> `/System/Library/PrivateFrameworks/VoiceShortcuts.framework/Support/siriactionsd`

```diff

+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>

```
### Camera

> `/private/var/staged_system_apps/Camera.app/Camera`

```diff

+	<key>com.apple.private.avfoundation.capture.query-module-sealed-state.allow</key>
+	<true/>

```
### Games

> `/private/var/staged_system_apps/Games.app/Games`

```diff

+	<key>com.apple.private.servicesintelligence</key>
+	<true/>

```
### Home

> `/private/var/staged_system_apps/Home.app/Home`

```diff

+	<key>com.apple.corespeech.uitrainingservice</key>
+	<true/>

+	<key>com.apple.private.home.extension-host</key>
+	<true/>

+	<key>com.apple.private.tcc.manager.access.modify</key>
+	<array>
+		<string>kTCCServiceWillow</string>
+	</array>

+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceWillow</string>
+	</array>

+	<key>com.apple.runningboard.home-extensions</key>
+	<true/>

+	<key>com.apple.security.exception.sysctl.read-only</key>
+	<array>
+		<string>kern.exclaves_status</string>
+	</array>

```

### 🆕 HomeAppMessagesExtension

> `/private/var/staged_system_apps/Home.app/PlugIns/HomeAppMessagesExtension.appex/HomeAppMessagesExtension`

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>application-identifier</key>
	<string>com.apple.Home.HomeAppMessagesExtension</string>
	<key>com.apple.appprotectiond.guard.access</key>
	<true/>
	<key>com.apple.appprotectiond.read.access</key>
	<true/>
	<key>com.apple.developer.homekit</key>
	<true/>
	<key>com.apple.developer.homekit.background-mode</key>
	<true/>
	<key>com.apple.frontboard.launchapplications</key>
	<true/>
	<key>com.apple.linkd.registry</key>
	<true/>
	<key>com.apple.linkd.transcript.privileged</key>
	<true/>
	<key>com.apple.locationd.effective_bundle</key>
	<true/>
	<key>com.apple.locationd.usage_oracle</key>
	<true/>
	<key>com.apple.messages.private.AllowConversationIdentifierAccess</key>
	<true/>
	<key>com.apple.messages.private.AllowParticipantAddressAccess</key>
	<true/>
	<key>com.apple.private.appintents.extension-host</key>
	<true/>
	<key>com.apple.private.coreservices.canmaplsdatabase</key>
	<true/>
	<key>com.apple.private.homekit</key>
	<true/>
	<key>com.apple.private.homekit.diagnostics</key>
	<true/>
	<key>com.apple.private.tcc.allow</key>
	<array>
		<string>kTCCServiceWillow</string>
	</array>
	<key>com.apple.runningboard.launchprocess</key>
	<true/>
	<key>com.apple.runningboard.process-state</key>
	<true/>
	<key>com.apple.security.app-sandbox</key>
	<true/>
	<key>com.apple.security.exception.files.absolute-path.read-write</key>
	<array>
		<string>/private/var/mobile/Library/Caches/</string>
	</array>
	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/com.apple.PrivacyDisclosure/</string>
	</array>
	<key>com.apple.security.exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.appprotectiond.guard</string>
		<string>com.apple.appprotectiond.read</string>
		<string>com.apple.linkd.extension</string>
		<string>com.apple.linkd.registry</string>
		<string>com.apple.linkd.transcript</string>
		<string>com.apple.matter.native.xpc</string>
	</array>
	<key>com.apple.security.network.client</key>
	<true/>
	<key>com.apple.security.temporary-exception.files.home-relative-path.read-only</key>
	<array>
		<string>/Library/com.apple.PrivacyDisclosure/</string>
	</array>
	<key>com.apple.security.temporary-exception.mach-lookup.global-name</key>
	<array>
		<string>com.apple.appprotectiond.guard</string>
		<string>com.apple.appprotectiond.read</string>
		<string>com.apple.linkd.extension</string>
		<string>com.apple.linkd.registry</string>
		<string>com.apple.linkd.transcript</string>
		<string>com.apple.matter.native.xpc</string>
	</array>
</dict>
</plist>

```
### SafariLinkExtension

> `/private/var/staged_system_apps/MobileSafari.app/Extensions/SafariLinkExtension.appex/SafariLinkExtension`

```diff

+	<key>com.apple.private.security.storage.Safari</key>
+	<true/>
+	<key>com.apple.security.application-groups</key>
+	<array>
+		<string>group.com.apple.safari.pebble</string>
+	</array>
+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/Safari/</string>
+	</array>

```
### MobileSafari

> `/private/var/staged_system_apps/MobileSafari.app/MobileSafari`

```diff

+		<string>/System/Library/PrivateFrameworks/MobileSafariUI.framework</string>

+		<string>group.com.apple.safari.pebble</string>

```
### airplayd

> `/usr/libexec/airplayd`

```diff

+	<key>com.apple.private.coreaudio.borrowaudiosession.allow</key>
+	<true/>

```
### cameracaptured

> `/usr/libexec/cameracaptured`

```diff

+	<key>com.apple.private.coreaudio.borrowaudiosession.allow</key>
+	<true/>

```
### locationd

> `/usr/libexec/locationd`

```diff

+	<key>com.apple.locationd.stored_location</key>
+	<true/>

```
### merchantd

> `/usr/libexec/merchantd`

```diff

+	<key>com.apple.private.corewifi</key>
+	<true/>

```
### nearbyd

> `/usr/libexec/nearbyd`

```diff

+	<key>com.apple.AccessorySensorManager</key>
+	<true/>

+	<key>com.apple.aop.hid-driver.user-client</key>
+	<dict>
+		<key>eclipse</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>
+		<key>orientation_1</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>
+	</dict>

+	<key>com.apple.backlight.allowsActivationObservation</key>
+	<true/>

+	<key>com.apple.hid.system.fast-path-motion-event-privileged</key>
+	<true/>

+	<key>com.apple.locationd.asmanager</key>
+	<true/>

+	<key>com.apple.locationd.motion_alarms-system-client</key>
+	<true/>

+	<key>com.apple.private.breadboard.privacy.read</key>
+	<array>
+		<string>passive-camera</string>
+	</array>

+	<key>com.apple.private.hid.client.motion-event-privileged</key>
+	<true/>

+		<string>com.apple.breadboardservices</string>
+		<string>com.apple.AccessorySensorManager</string>
+		<string>com.apple.BacklightServices.backlight</string>

```
### replayd

> `/usr/libexec/replayd`

```diff

+	<key>com.apple.backboardd.touchStreams</key>
+	<true/>

+	<key>com.apple.private.skylight.event-tap.direct-touch</key>
+	<true/>

```
### sharereportingd

> `/usr/libexec/sharereportingd`

```diff

+	<key>com.apple.developer.icloud-container-environment</key>
+	<string>Production</string>

```
### tipsd

> `/usr/libexec/tipsd`

```diff

+		<string>com.apple.EligibilityQuorum.com.apple.AudioIntelligence</string>

```
### tvremoted

> `/usr/libexec/tvremoted`

```diff

+	<key>com.apple.icloud.findmydeviced.localfindable</key>
+	<true/>

+		<string>com.apple.icloud.findmydeviced.localfindable</string>

```


### AppOS

### webbookmarksd

> `/usr/libexec/webbookmarksd`

```diff

+	<key>com.apple.private.appintents.attribution.bundle-identifier</key>
+	<string>com.apple.mobilesafari</string>

```


