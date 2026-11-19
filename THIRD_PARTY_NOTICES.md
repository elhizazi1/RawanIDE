# Third-Party Software Notices — RawanIDE

RawanIDE uses third-party software. The copyright and licensing of RawanIDE itself are separate from the rights of the third-party authors listed here. **This document does not grant a license to RawanIDE's proprietary code, branding, or assets.**

This notice is based on the project's Gradle `releaseRuntimeClasspath` report (Gradle 9.3.1, 19 November 2026). The inventory below is a **resolved Gradle dependency inventory**, not a verified list of all files shipped in the final APK. Gradle BOMs, constraints, and platform metadata may appear even when they do not contribute packaged code. The report does not reveal copied source, bundled assets, native binaries, or other manually included third-party code.

## Identified third-party licenses and sources

| Software | Version in report | License / upstream declaration | Source |
|---|---|---|---|
| Sora Editor (`io.github.rosemoe:editor`) | 0.24.7 | GNU Lesser General Public License 2.1 (LGPL-2.1); exact artifact metadata | https://central.sonatype.com/artifact/io.github.rosemoe/editor/0.24.7 |
| Dhizuku API (`io.github.iamr0s:Dhizuku-API`) | 2.5.4 | MIT | https://github.com/iamr0s/Dhizuku-API/blob/main/LICENSE |
| Shizuku API/provider (`dev.rikka.shizuku`) | 13.1.5 | Apache License 2.0 (upstream project) | https://github.com/RikkaApps/Shizuku |
| libsu core (`com.github.topjohnwu.libsu`) | 6.0.0 | Apache License 2.0 (upstream project) | https://github.com/topjohnwu/libsu |
| JGit (`org.eclipse.jgit`) | 6.10.0.202406032230-r | Eclipse Distribution License 1.0 (EDL-1.0; BSD-style), upstream stable-6.10 branch | https://eclipse.googlesource.com/jgit/jgit/+/refs/heads/stable-6.10 |
| NanoHTTPD (`org.nanohttpd:nanohttpd`) | 2.3.1 | BSD 3-Clause (upstream project) | https://github.com/NanoHttpd/nanohttpd/blob/master/LICENSE.md |

The LGPL-2.1 license text for Sora Editor is available at https://www.gnu.org/licenses/old-licenses/lgpl-2.1.txt and its source is available at https://github.com/Rosemoe/sora-editor . Distribution of an application incorporating this library may entail obligations beyond crediting its authors, including providing applicable source or modifications and enabling relinking where required by the license. These obligations are not satisfied solely by this Markdown file. The license and notices of Dhizuku's separately installed application are not the same as those of the Dhizuku API.

Other software in the inventory includes AndroidX/Compose, Kotlin and coroutines, Firebase/Google SDKs, Square (OkHttp, Retrofit, Moshi), Coil, Tink, AndroidSVG, SLF4J, Commons Codec, and their dependencies. Their individual licenses and any required notices must be determined from their exact distributed artifacts and applicable SDK terms; no single license is asserted for all of them here.

## Full resolved Gradle module inventory

This appendix preserves the distinct `group:artifact:version` entries reported in the supplied release runtime dependency tree, deduplicated by group and artifact. It does not by itself establish copyright attribution or license compliance.

- `androidx.activity:activity:1.10.1`
- `androidx.activity:activity-compose:1.10.1`
- `androidx.activity:activity-ktx:1.10.1`
- `androidx.annotation:annotation:1.11.0`
- `androidx.annotation:annotation-experimental:1.4.1`
- `androidx.annotation:annotation-jvm:1.11.0`
- `androidx.appcompat:appcompat:1.6.1`
- `androidx.appcompat:appcompat-resources:1.6.1`
- `androidx.arch.core:core-common:2.2.0`
- `androidx.arch.core:core-runtime:2.2.0`
- `androidx.autofill:autofill:1.0.0`
- `androidx.biometric:biometric:1.1.0`
- `androidx.browser:browser:1.4.0`
- `androidx.collection:collection:1.6.0`
- `androidx.collection:collection-jvm:1.6.0`
- `androidx.collection:collection-ktx:1.6.0`
- `androidx.compose:compose-bom:2024.09.00`
- `androidx.compose.animation:animation:1.7.2`
- `androidx.compose.animation:animation-android:1.7.2`
- `androidx.compose.animation:animation-core:1.7.2`
- `androidx.compose.animation:animation-core-android:1.7.2`
- `androidx.compose.foundation:foundation:1.7.2`
- `androidx.compose.foundation:foundation-android:1.7.2`
- `androidx.compose.foundation:foundation-layout:1.7.2`
- `androidx.compose.foundation:foundation-layout-android:1.7.2`
- `androidx.compose.material:material-icons-core:1.7.0`
- `androidx.compose.material:material-icons-core-android:1.7.0`
- `androidx.compose.material:material-icons-extended-android:1.7.0`
- `androidx.compose.material:material-ripple:1.7.0`
- `androidx.compose.material:material-ripple-android:1.7.0`
- `androidx.compose.material3:material3-android:1.3.0`
- `androidx.compose.runtime:runtime:1.7.2`
- `androidx.compose.runtime:runtime-android:1.7.2`
- `androidx.compose.runtime:runtime-saveable:1.7.2`
- `androidx.compose.runtime:runtime-saveable-android:1.7.2`
- `androidx.compose.ui:ui:1.7.2`
- `androidx.compose.ui:ui-android:1.7.2`
- `androidx.compose.ui:ui-geometry:1.7.2`
- `androidx.compose.ui:ui-geometry-android:1.7.2`
- `androidx.compose.ui:ui-graphics:1.7.2`
- `androidx.compose.ui:ui-graphics-android:1.7.2`
- `androidx.compose.ui:ui-text:1.7.2`
- `androidx.compose.ui:ui-text-android:1.7.2`
- `androidx.compose.ui:ui-tooling-preview-android:1.7.2`
- `androidx.compose.ui:ui-unit:1.7.2`
- `androidx.compose.ui:ui-unit-android:1.7.2`
- `androidx.compose.ui:ui-util:1.7.2`
- `androidx.compose.ui:ui-util-android:1.7.2`
- `androidx.concurrent:concurrent-futures:1.1.0`
- `androidx.core:core:1.18.0`
- `androidx.core:core-ktx:1.18.0`
- `androidx.core:core-viewtree:1.0.0`
- `androidx.credentials:credentials:1.5.0`
- `androidx.credentials:credentials-play-services-auth:1.5.0`
- `androidx.cursoradapter:cursoradapter:1.0.0`
- `androidx.customview:customview:1.0.0`
- `androidx.customview:customview-poolingcontainer:1.0.0`
- `androidx.datastore:datastore:1.1.7`
- `androidx.datastore:datastore-android:1.1.7`
- `androidx.datastore:datastore-core:1.1.7`
- `androidx.datastore:datastore-core-android:1.1.7`
- `androidx.datastore:datastore-core-okio:1.1.7`
- `androidx.datastore:datastore-core-okio-jvm:1.1.7`
- `androidx.datastore:datastore-preferences:1.1.7`
- `androidx.datastore:datastore-preferences-android:1.1.7`
- `androidx.datastore:datastore-preferences-core:1.1.7`
- `androidx.datastore:datastore-preferences-core-android:1.1.7`
- `androidx.datastore:datastore-preferences-external-protobuf:1.1.7`
- `androidx.datastore:datastore-preferences-proto:1.1.7`
- `androidx.drawerlayout:drawerlayout:1.0.0`
- `androidx.emoji2:emoji2:1.3.0`
- `androidx.emoji2:emoji2-views-helper:1.3.0`
- `androidx.exifinterface:exifinterface:1.3.7`
- `androidx.fragment:fragment:1.5.7`
- `androidx.graphics:graphics-path:1.0.1`
- `androidx.interpolator:interpolator:1.0.0`
- `androidx.lifecycle:lifecycle-common:2.8.7`
- `androidx.lifecycle:lifecycle-common-java8:2.8.7`
- `androidx.lifecycle:lifecycle-common-jvm:2.8.7`
- `androidx.lifecycle:lifecycle-livedata-core:2.8.7`
- `androidx.lifecycle:lifecycle-process:2.8.7`
- `androidx.lifecycle:lifecycle-runtime:2.8.7`
- `androidx.lifecycle:lifecycle-runtime-android:2.8.7`
- `androidx.lifecycle:lifecycle-runtime-compose:2.8.7`
- `androidx.lifecycle:lifecycle-runtime-compose-android:2.8.7`
- `androidx.lifecycle:lifecycle-runtime-ktx:2.8.7`
- `androidx.lifecycle:lifecycle-runtime-ktx-android:2.8.7`
- `androidx.lifecycle:lifecycle-viewmodel:2.8.7`
- `androidx.lifecycle:lifecycle-viewmodel-android:2.8.7`
- `androidx.lifecycle:lifecycle-viewmodel-compose:2.8.7`
- `androidx.lifecycle:lifecycle-viewmodel-compose-android:2.8.7`
- `androidx.lifecycle:lifecycle-viewmodel-ktx:2.8.7`
- `androidx.lifecycle:lifecycle-viewmodel-savedstate:2.8.7`
- `androidx.loader:loader:1.1.0`
- `androidx.localbroadcastmanager:localbroadcastmanager:1.0.0`
- `androidx.navigation:navigation-common:2.8.9`
- `androidx.navigation:navigation-common-ktx:2.8.9`
- `androidx.navigation:navigation-compose:2.8.9`
- `androidx.navigation:navigation-runtime:2.8.9`
- `androidx.navigation:navigation-runtime-ktx:2.8.9`
- `androidx.profileinstaller:profileinstaller:1.4.0`
- `androidx.resourceinspection:resourceinspection-annotation:1.0.1`
- `androidx.room:room-common:2.7.0`
- `androidx.room:room-common-jvm:2.7.0`
- `androidx.room:room-ktx:2.7.0`
- `androidx.room:room-runtime:2.7.0`
- `androidx.room:room-runtime-android:2.7.0`
- `androidx.savedstate:savedstate:1.2.1`
- `androidx.savedstate:savedstate-ktx:1.2.1`
- `androidx.sqlite:sqlite:2.5.0`
- `androidx.sqlite:sqlite-android:2.5.0`
- `androidx.sqlite:sqlite-framework:2.5.0`
- `androidx.sqlite:sqlite-framework-android:2.5.0`
- `androidx.startup:startup-runtime:1.1.1`
- `androidx.tracing:tracing:1.2.0`
- `androidx.vectordrawable:vectordrawable:1.1.0`
- `androidx.vectordrawable:vectordrawable-animated:1.1.0`
- `androidx.versionedparcelable:versionedparcelable:1.1.1`
- `androidx.viewpager:viewpager:1.0.0`
- `androidx.webkit:webkit:1.14.0`
- `com.caverock:androidsvg-aar:1.4`
- `com.github.topjohnwu.libsu:core:6.0.0`
- `com.google.accompanist:accompanist-drawablepainter:0.32.0`
- `com.google.android.gms:play-services-auth:21.5.1`
- `com.google.android.gms:play-services-auth-api-phone:18.0.2`
- `com.google.android.gms:play-services-auth-base:18.0.10`
- `com.google.android.gms:play-services-auth-blockstore:16.4.0`
- `com.google.android.gms:play-services-base:18.5.0`
- `com.google.android.gms:play-services-basement:18.9.0`
- `com.google.android.gms:play-services-fido:21.0.0`
- `com.google.android.gms:play-services-identity-credentials:16.0.0-alpha02`
- `com.google.android.gms:play-services-tasks:18.2.0`
- `com.google.android.libraries.identity.googleid:googleid:1.1.1`
- `com.google.android.play:core-common:2.0.3`
- `com.google.android.play:integrity:1.3.0`
- `com.google.android.recaptcha:recaptcha:18.6.1`
- `com.google.code.findbugs:jsr305:3.0.2`
- `com.google.code.gson:gson:2.10.1`
- `com.google.crypto.tink:tink-android:1.13.0`
- `com.google.errorprone:error_prone_annotations:2.26.0`
- `com.google.firebase:firebase-annotations:16.2.0`
- `com.google.firebase:firebase-appcheck-interop:17.0.0`
- `com.google.firebase:firebase-auth:23.2.1`
- `com.google.firebase:firebase-auth-interop:20.0.0`
- `com.google.firebase:firebase-bom:33.12.0`
- `com.google.firebase:firebase-common:21.0.0`
- `com.google.firebase:firebase-common-ktx:21.0.0`
- `com.google.firebase:firebase-components:18.0.0`
- `com.google.guava:listenablefuture:1.0`
- `com.googlecode.javaewah:JavaEWAH:1.2.3`
- `com.squareup.moshi:moshi:1.15.2`
- `com.squareup.moshi:moshi-kotlin:1.15.2`
- `com.squareup.okhttp3:logging-interceptor:4.10.0`
- `com.squareup.okhttp3:okhttp:4.12.0`
- `com.squareup.okio:okio:3.9.0`
- `com.squareup.okio:okio-jvm:3.9.0`
- `com.squareup.retrofit2:converter-moshi:2.12.0`
- `com.squareup.retrofit2:retrofit:2.12.0`
- `commons-codec:commons-codec:1.17.0`
- `dev.rikka.shizuku:aidl:13.1.5`
- `dev.rikka.shizuku:api:13.1.5`
- `dev.rikka.shizuku:provider:13.1.5`
- `dev.rikka.shizuku:shared:13.1.5`
- `io.coil-kt:coil:2.7.0`
- `io.coil-kt:coil-base:2.7.0`
- `io.coil-kt:coil-compose:2.7.0`
- `io.coil-kt:coil-compose-base:2.7.0`
- `io.coil-kt:coil-gif:2.7.0`
- `io.coil-kt:coil-svg:2.7.0`
- `io.github.iamr0s:Dhizuku-API:2.5.4`
- `io.github.rosemoe:editor:0.24.7`
- `javax.inject:javax.inject:1`
- `org.eclipse.jgit:org.eclipse.jgit:6.10.0.202406032230-r`
- `org.jetbrains:annotations:23.0.0`
- `org.jetbrains.kotlin:kotlin-android-extensions-runtime:1.9.22`
- `org.jetbrains.kotlin:kotlin-parcelize-runtime:1.9.22`
- `org.jetbrains.kotlin:kotlin-reflect:1.8.21`
- `org.jetbrains.kotlin:kotlin-stdlib:2.4.10`
- `org.jetbrains.kotlin:kotlin-stdlib-common:2.4.10`
- `org.jetbrains.kotlin:kotlin-stdlib-jdk7:1.9.0`
- `org.jetbrains.kotlin:kotlin-stdlib-jdk8:1.9.0`
- `org.jetbrains.kotlinx:kotlinx-coroutines-android:1.10.2`
- `org.jetbrains.kotlinx:kotlinx-coroutines-bom:1.10.2`
- `org.jetbrains.kotlinx:kotlinx-coroutines-core:1.10.2`
- `org.jetbrains.kotlinx:kotlinx-coroutines-core-jvm:1.10.2`
- `org.jetbrains.kotlinx:kotlinx-coroutines-play-services:1.10.2`
- `org.jetbrains.kotlinx:kotlinx-serialization-bom:1.6.3`
- `org.jetbrains.kotlinx:kotlinx-serialization-core:1.6.3`
- `org.jetbrains.kotlinx:kotlinx-serialization-core-jvm:1.6.3`
- `org.jspecify:jspecify:1.0.0`
- `org.nanohttpd:nanohttpd:2.3.1`
- `org.slf4j:slf4j-api:1.7.36`

## Distribution and attribution limitations

- Third-party copyright, license, and NOTICE files that must accompany redistribution should be included in the appropriate distribution materials, including where applicable within the app. Links in this document do not replace required full license texts or notices.
- LGPL-2.1 obligations for Sora Editor require a distribution-specific review, particularly for static inclusion in an Android APK, any modifications, corresponding library source, and relinking provisions.
- Google/Firebase SDK terms may contain contractual requirements separate from open-source license obligations.
- The report alone cannot confirm all libraries, native code, fonts, media, or other resources embedded in the shipped APK.
- This document records known dependencies and sources; it is not a legal certification or a representation that all distribution obligations have already been fulfilled.
