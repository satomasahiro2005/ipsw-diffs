## 🔑 Entitlements

### filesystem

### ScreenTimeWidgetExtension

> `/Applications/Screen Time.app/PlugIns/ScreenTimeWidgetExtension.appex/ScreenTimeWidgetExtension`

```diff

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>

```
### ScreenTimeWidgetIntentsExtension

> `/Applications/Screen Time.app/PlugIns/ScreenTimeWidgetIntentsExtension.appex/ScreenTimeWidgetIntentsExtension`

```diff

+	<key>com.apple.private.familycircle</key>
+	<true/>

+	<key>com.apple.private.screen-time-settings</key>
+	<true/>

+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
+		<string>com.apple.familycircle.agent</string>
+		<string>com.apple.accountsd.accountmanager</string>

```
### CarPlay

> `/System/Library/CoreServices/CarPlay.app/CarPlay`

```diff

+	<key>com.apple.tailspin.dump-output</key>
+	<true/>

```
### MusicKitUI

> `/System/Library/CoreServices/MusicKitUI.app/MusicKitUI`

```diff

+	</array>
+	<key>com.apple.private.tcc.manager.check-by-audit-token</key>
+	<array>
+		<string>kTCCServiceMediaLibrary</string>

```
### accountsd

> `/System/Library/Frameworks/Accounts.framework/accountsd`

```diff

+	<key>com.apple.private.intelligenceplatform.client-identifier</key>
+	<string>com.apple.accountsd</string>

```
### amsengagementd

> `/System/Library/PrivateFrameworks/AppleMediaServicesUI.framework/amsengagementd`

```diff

+	<key>com.apple.security.hardened-process</key>
+	<true/>
+	<key>com.apple.security.hardened-process.dyld-ro</key>
+	<true/>
+	<key>com.apple.security.hardened-process.enhanced-security-version-string</key>
+	<string>2</string>
+	<key>com.apple.security.hardened-process.hardened-heap</key>
+	<true/>
+	<key>com.apple.security.hardened-process.platform-restrictions-string</key>
+	<string>2</string>

```
### accessoryd

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Support/accessoryd`

```diff

+	<key>com.apple.appprotectiond.read.access</key>
+	<true/>

```
### mediaremoted

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Support/mediaremoted`

```diff

+	<key>com.apple.networkd_privileged</key>
+	<true/>

+	<key>com.apple.private.necp.policies</key>
+	<true/>
+	<key>com.apple.private.nehelper.privileged</key>
+	<true/>

+		<string>com.apple.nehelper</string>

```
### migrationd

> `/System/Library/PrivateFrameworks/MigrationKit.framework/migrationd`

```diff

+	<key>com.apple.CommCenter.fine-grained</key>
+	<array>
+		<string>spi</string>
+	</array>

```
### ScreenTimeFollowUpExtension

> `/System/Library/PrivateFrameworks/ScreenTimeUI.framework/PlugIns/ScreenTimeFollowUpExtension.appex/ScreenTimeFollowUpExtension`

```diff

+	<key>com.apple.accounts.appleaccount.fullaccess</key>
+	<true/>
+	<key>com.apple.accounts.appleidauthentication.defaultaccess</key>
+	<true/>
+	<key>com.apple.accounts.idms.fullaccess</key>
+	<true/>
+	<key>com.apple.itunesstored.private</key>
+	<true/>
+	<key>com.apple.private.accounts.allaccounts</key>
+	<true/>
+	<key>com.apple.private.applemediaservices</key>
+	<true/>
+	<key>com.apple.private.contacts</key>
+	<true/>
+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>
+	<key>com.apple.private.familycircle</key>
+	<true/>

+	<key>com.apple.private.managed-settings.effective-read</key>
+	<true/>
+	<key>com.apple.private.screen-time</key>
+	<true/>
+	<key>com.apple.private.screen-time-settings</key>
+	<true/>
+	<key>com.apple.private.screen-time.persistence</key>
+	<true/>
+	<key>com.apple.private.security.storage.os_eligibility.readonly</key>
+	<true/>
+	<key>com.apple.private.usage-tracking</key>
+	<true/>

+	<key>com.apple.security.exception.files.absolute-path.read-only</key>
+	<array>
+		<string>/private/var/db/os_eligibility/eligibility.plist</string>
+	</array>
+	<key>com.apple.security.exception.files.home-relative-path.read-only</key>
+	<array>
+		<string>/Library/com.apple.ManagedSettings/EffectiveSettings.plist</string>
+	</array>

+		<string>com.apple.accountsd.accountmanager</string>

+		<string>com.apple.familycircle.agent</string>
+		<string>com.apple.ManagedSettingsAgent</string>
+		<string>com.apple.ScreenTimeAgent.private</string>
+		<string>com.apple.ScreenTimeAgent.settings</string>
+		<string>com.apple.ScreenTimeSettingsAgent.private</string>
+		<string>com.apple.UsageTrackingAgent.private</string>
+	</array>
+	<key>com.apple.security.exception.shared-preference.read-write</key>
+	<array>
+		<string>com.apple.DeviceActivity</string>
+	</array>
+	<key>com.apple.security.system-groups</key>
+	<array>
+		<string>systemgroup.com.apple.DeviceActivity</string>

```
### Bridge

> `/private/var/staged_system_apps/Bridge.app/Bridge`

```diff

+	<key>com.apple.generativeexperiences.availabilityService</key>
+	<true/>
+	<key>com.apple.generativeexperiences.availabilityService.waitlistStatus</key>
+	<true/>

-		<string>/Library/VoiceTrigger/SAT/</string>
+		<string>/Library/VoiceTrigger/</string>

+		<string>com.apple.generativeexperiences.availabilityService</string>

+		<string>com.apple.itunesstored</string>

```
### Fitness

> `/private/var/staged_system_apps/Fitness.app/Fitness`

```diff

+		<string>VasUgeSzVyHdB27g2XpN0g</string>

+		<string>/private/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles/Library/ConfigurationProfiles/UserSettings.plist</string>

+		<string>com.apple.private.health.respiratory</string>
+		<string>com.apple.private.health.age-gating</string>

```
### FitnessWidget

> `/private/var/staged_system_apps/Fitness.app/PlugIns/FitnessWidget.appex/FitnessWidget`

```diff

+	<key>com.apple.private.MobileGestalt.AllowedProtectedKeys</key>
+	<array>
+		<string>VasUgeSzVyHdB27g2XpN0g</string>
+	</array>
+	<key>com.apple.private.coreservices.canmaplsdatabase</key>
+	<true/>

+	<key>com.apple.private.healthkit.feature-availability.read-any</key>
+	<true/>
+	<key>com.apple.private.sleepd</key>
+	<true/>

+		<string>/private/var/containers/Shared/SystemGroup/systemgroup.com.apple.configurationprofiles/Library/ConfigurationProfiles/UserSettings.plist</string>

+		<string>com.apple.sleepd.sleepserver</string>

+	<key>com.apple.security.exception.shared-preference.read-only</key>
+	<array>
+		<string>com.apple.private.health.respiratory</string>
+		<string>com.apple.private.health.age-gating</string>
+	</array>

```
### Journal

> `/private/var/staged_system_apps/Journal.app/Journal`

```diff

+		<string>com.apple.generativeexperiences.availabilityService</string>

+		<string>com.apple.gms.availability</string>

```
### asd

> `/usr/libexec/asd`

```diff

+	<key>application-identifier</key>
+	<string>com.apple.asd</string>

+	<key>com.apple.private.generativesearch.client.search</key>
+	<true/>

+		<key>com.apple.asd</key>
+		<dict>
+			<key>Search</key>
+			<array>
+				<string>Mail</string>
+			</array>
+		</dict>

+		<string>com.apple.generativesearch.server.search</string>

```
### findmydeviced

> `/usr/libexec/findmydeviced`

```diff

+	<key>com.apple.TVRemoteCore</key>
+	<true/>

```
### sharingd

> `/usr/libexec/sharingd`

```diff

+		<key>orientation_1</key>
+		<dict>
+			<key>send-command</key>
+			<dict/>
+		</dict>

```


### AppOS

### AuthenticationServicesAgent

> `/usr/libexec/AuthenticationServicesAgent`

```diff

+	<key>com.apple.private.network.socket-delegate</key>
+	<true/>

```


