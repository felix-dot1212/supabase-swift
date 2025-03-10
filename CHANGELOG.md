# Changelog

## [2.27.0](https://github.com/felix-dot1212/supabase-swift/compare/v2.26.0...v2.27.0) (2025-03-10)


### Features

* add AdminAPI and deleteUser method ([#224](https://github.com/felix-dot1212/supabase-swift/issues/224)) ([7b55ec2](https://github.com/felix-dot1212/supabase-swift/commit/7b55ec27f81928793dcbfe4868f62eda6a7c90ce))
* add Android support ([#673](https://github.com/felix-dot1212/supabase-swift/issues/673)) ([f39d4d4](https://github.com/felix-dot1212/supabase-swift/commit/f39d4d48e4b0144faaf9582738d10cfa905205bd))
* add AuthStateChangeListenerRegistration type ([#248](https://github.com/felix-dot1212/supabase-swift/issues/248)) ([5751e78](https://github.com/felix-dot1212/supabase-swift/commit/5751e7881f033b54545caa54bd848757608dc717))
* add filter to RPC call ([#150](https://github.com/felix-dot1212/supabase-swift/issues/150)) ([6955615](https://github.com/felix-dot1212/supabase-swift/commit/695561578858b9ee87a19a84c47035b46c72bd82))
* Add optional "referencedTable" parameter to OR PostGREST filter ([#250](https://github.com/felix-dot1212/supabase-swift/issues/250)) ([86e2537](https://github.com/felix-dot1212/supabase-swift/commit/86e2537c7ca8a84aebafc82979817988610c1858))
* add reauthenticate method ([#271](https://github.com/felix-dot1212/supabase-swift/issues/271)) ([f097ad5](https://github.com/felix-dot1212/supabase-swift/commit/f097ad5ff2a7becdd1af591d57e44db21276429a))
* add Sendable conformances and fix warnings ([#260](https://github.com/felix-dot1212/supabase-swift/issues/260)) ([1e61293](https://github.com/felix-dot1212/supabase-swift/commit/1e61293e9495a6683510531cbc8241bad67e8b66))
* Add SupabaseLogger ([#219](https://github.com/felix-dot1212/supabase-swift/issues/219)) ([ab50120](https://github.com/felix-dot1212/supabase-swift/commit/ab5012067c2f1c1090e98a40f7294ffa589837d4))
* add third-party auth support ([#423](https://github.com/felix-dot1212/supabase-swift/issues/423)) ([8353787](https://github.com/felix-dot1212/supabase-swift/commit/8353787d9b972f6cf5ef06cb8bee1cf4be4856e0))
* **auth:** add `getLinkIdentityURL` ([#342](https://github.com/felix-dot1212/supabase-swift/issues/342)) ([e5298e4](https://github.com/felix-dot1212/supabase-swift/commit/e5298e4c8cd6c8dcc8ca991d2bc15cc4ae0d1cb7))
* **auth:** Add `signInAnonymously` ([#297](https://github.com/felix-dot1212/supabase-swift/issues/297)) ([4f51810](https://github.com/felix-dot1212/supabase-swift/commit/4f518106ad7ff32b97f99df6ff0f12dc73616a76))
* **auth:** add `signInWithOAuth` ([#299](https://github.com/felix-dot1212/supabase-swift/issues/299)) ([c89489c](https://github.com/felix-dot1212/supabase-swift/commit/c89489c72de5cd2401b5951fc6012817b53e6cf7))
* **auth:** add `signInWithSSO` method ([#289](https://github.com/felix-dot1212/supabase-swift/issues/289)) ([9dd170b](https://github.com/felix-dot1212/supabase-swift/commit/9dd170bee416d35fd0323ae59014e4db4254c219))
* **auth:** add captcha token to sign-in with password methods ([#276](https://github.com/felix-dot1212/supabase-swift/issues/276)) ([0f2b610](https://github.com/felix-dot1212/supabase-swift/commit/0f2b6103a325719cb917338ec74e848b2cc96b7e))
* **auth:** add convenience deep link handling methods ([#397](https://github.com/felix-dot1212/supabase-swift/issues/397)) ([0d3ce17](https://github.com/felix-dot1212/supabase-swift/commit/0d3ce1713de79b7ae594f22978af536051d901ee))
* **auth:** add isExpired variable to session type ([#399](https://github.com/felix-dot1212/supabase-swift/issues/399)) ([21b8225](https://github.com/felix-dot1212/supabase-swift/commit/21b8225c94ac28ef75c69ade21370c5cad4a8a7c))
* **auth:** add linkIdentity method ([#392](https://github.com/felix-dot1212/supabase-swift/issues/392)) ([6e0c6ed](https://github.com/felix-dot1212/supabase-swift/commit/6e0c6ed7f3c0d0508cd2e4c689cfd02065cd07f4))
* **auth:** add listUsers admin method ([#539](https://github.com/felix-dot1212/supabase-swift/issues/539)) ([1891df1](https://github.com/felix-dot1212/supabase-swift/commit/1891df168b596e4355c5f60352ebe35fc37b30de))
* **auth:** add MFA phone ([#496](https://github.com/felix-dot1212/supabase-swift/issues/496)) ([33894cb](https://github.com/felix-dot1212/supabase-swift/commit/33894cb18f6cb532e8f7866d692e12d9e5909308))
* **auth:** add new error codes ([#586](https://github.com/felix-dot1212/supabase-swift/issues/586)) ([1177c65](https://github.com/felix-dot1212/supabase-swift/commit/1177c658c81c5019cb7422683610491c461fe108))
* **auth:** add options for disabling auto refresh token ([#411](https://github.com/felix-dot1212/supabase-swift/issues/411)) ([97688bf](https://github.com/felix-dot1212/supabase-swift/commit/97688bfb24275364b2b91f8f0c65a54b00544ebd))
* **auth:** add resend method ([#190](https://github.com/felix-dot1212/supabase-swift/issues/190)) ([ae7bfc0](https://github.com/felix-dot1212/supabase-swift/commit/ae7bfc0cec70b87b81465f84ceb956723bfb0394))
* **auth:** add support for error codes and refactor `AuthError` ([#518](https://github.com/felix-dot1212/supabase-swift/issues/518)) ([e52b5e7](https://github.com/felix-dot1212/supabase-swift/commit/e52b5e7893b4a391fe1c1428e2dcc61e543ea68b))
* **auth:** add support for multiple auth instances ([#445](https://github.com/felix-dot1212/supabase-swift/issues/445)) ([46be47e](https://github.com/felix-dot1212/supabase-swift/commit/46be47e4793894fc2274a39868c0f90f018c3f9e))
* **auth:** add whatsapp channel option to signInWithOTP ([#287](https://github.com/felix-dot1212/supabase-swift/issues/287)) ([340d5f7](https://github.com/felix-dot1212/supabase-swift/commit/340d5f7b7f3d07959f9ef70c2767a9c279ec1f7b))
* **auth:** Adds `currentSession` and `currentUser` properties ([#373](https://github.com/felix-dot1212/supabase-swift/issues/373)) ([f989a08](https://github.com/felix-dot1212/supabase-swift/commit/f989a0884f3fe4d28f2325b3a689f282b27029d9))
* **auth:** link identity ([#274](https://github.com/felix-dot1212/supabase-swift/issues/274)) ([5826a35](https://github.com/felix-dot1212/supabase-swift/commit/5826a35c5b398ed9fedfb14ce7f588e2f773921c))
* **auth:** retry auth requests, and schedule next refresh retry in background ([#395](https://github.com/felix-dot1212/supabase-swift/issues/395)) ([ba4ae43](https://github.com/felix-dot1212/supabase-swift/commit/ba4ae43790edabf111a3ffad1e482f242e4beeed))
* auto-connect socket on channel subscription ([#208](https://github.com/felix-dot1212/supabase-swift/issues/208)) ([939719b](https://github.com/felix-dot1212/supabase-swift/commit/939719b20d44a1570d089253c98df80f572bc0d7))
* **database:** add select on query result ([#275](https://github.com/felix-dot1212/supabase-swift/issues/275)) ([85fd1f5](https://github.com/felix-dot1212/supabase-swift/commit/85fd1f588c6d2b1b1783c84a8f0008384ce441b7))
* edge functions support for custom domains and vanity domains ([#90](https://github.com/felix-dot1212/supabase-swift/issues/90)) ([54b3a9c](https://github.com/felix-dot1212/supabase-swift/commit/54b3a9c9a6991de276b3200e400912865da71106))
* expose PostgrestClient methods directly in SupabaseClient ([#336](https://github.com/felix-dot1212/supabase-swift/issues/336)) ([5d77507](https://github.com/felix-dot1212/supabase-swift/commit/5d77507e29f2df940fe8e42ed68dd482a2b03e38))
* expose Realtime options on SupabaseClient ([#377](https://github.com/felix-dot1212/supabase-swift/issues/377)) ([1905496](https://github.com/felix-dot1212/supabase-swift/commit/1905496b7357e0af7de11f59c19d8a005b490011))
* **functions:** add experimental invoke with streamed responses ([#346](https://github.com/felix-dot1212/supabase-swift/issues/346)) ([3997a40](https://github.com/felix-dot1212/supabase-swift/commit/3997a403fcb763d315bd921e85ab9c91625838f1))
* **functions:** add support for specifying function region ([#347](https://github.com/felix-dot1212/supabase-swift/issues/347)) ([d6d08e4](https://github.com/felix-dot1212/supabase-swift/commit/d6d08e400a98f467b3007687657d6c93895ab9d1))
* **functions:** invoke function with custom query params ([#376](https://github.com/felix-dot1212/supabase-swift/issues/376)) ([8279c92](https://github.com/felix-dot1212/supabase-swift/commit/8279c92040ee5937c9ab1715af2f3a2fa53673ed))
* **gotrue:** add scope to signOut ([#175](https://github.com/felix-dot1212/supabase-swift/issues/175)) ([b98708c](https://github.com/felix-dot1212/supabase-swift/commit/b98708c902e2f1640f4a1b4c93bb607c2e61b657))
* improve HTTP Error ([#372](https://github.com/felix-dot1212/supabase-swift/issues/372)) ([b4dad55](https://github.com/felix-dot1212/supabase-swift/commit/b4dad55bf87a4cf90b1be6f1abc9c56a344825da))
* improve logging on token refresh logic ([#410](https://github.com/felix-dot1212/supabase-swift/issues/410)) ([7769bdd](https://github.com/felix-dot1212/supabase-swift/commit/7769bddb23e4332a94e12cf4fd7fd4c914b5ff0f))
* mark `getURLForLinkIdentity` as experimental ([bf0c355](https://github.com/felix-dot1212/supabase-swift/commit/bf0c3559df4b723789557f145e38ffaa1f0cb61d))
* **postgrest:** add geojson, explain, and new filters ([#343](https://github.com/felix-dot1212/supabase-swift/issues/343)) ([d69789e](https://github.com/felix-dot1212/supabase-swift/commit/d69789ed0ccc2e14964ca63542bc0c1767a6d7e3))
* **postgrest:** add read-only mode for RPC ([#600](https://github.com/felix-dot1212/supabase-swift/issues/600)) ([b4ee9d8](https://github.com/felix-dot1212/supabase-swift/commit/b4ee9d85d8d38c994efd8ce151779cc42b7fb9bd))
* **postgrest:** allow switching schema ([#199](https://github.com/felix-dot1212/supabase-swift/issues/199)) ([02e0f96](https://github.com/felix-dot1212/supabase-swift/commit/02e0f962cbc7dd7542f56852d4e70ffe42066885))
* **postgrest:** rename foreignTable to referencedTable ([#166](https://github.com/felix-dot1212/supabase-swift/issues/166)) ([52c4597](https://github.com/felix-dot1212/supabase-swift/commit/52c4597ea3f21c272c4a10f8546c592980c01601))
* **postgrest:** set coder in SupabaseClientOptions ([#185](https://github.com/felix-dot1212/supabase-swift/issues/185)) ([a8cb895](https://github.com/felix-dot1212/supabase-swift/commit/a8cb895055e0690bde144d46919ab40a6f77328a))
* **postgrest:** set header on a per call basis ([#508](https://github.com/felix-dot1212/supabase-swift/issues/508)) ([a09f01a](https://github.com/felix-dot1212/supabase-swift/commit/a09f01ada0f2bcbe0a4a19f32ca5647091d3a120))
* **postgrest:** use `Date` when filtering columns ([#514](https://github.com/felix-dot1212/supabase-swift/issues/514)) ([389dad5](https://github.com/felix-dot1212/supabase-swift/commit/389dad55a0d3af406c64bcdc6b36d8ab24b5c186))
* prepare for v2 release ([#187](https://github.com/felix-dot1212/supabase-swift/issues/187)) ([ec63acc](https://github.com/felix-dot1212/supabase-swift/commit/ec63acc89785c3ae17702bb1ff2de8cd0d8ec265))
* re-add supabase init with a URL type ([d16fe31](https://github.com/felix-dot1212/supabase-swift/commit/d16fe315e6143e22ec623be19ac7e02fe3b670c5))
* **realtime:** add `system` event ([#589](https://github.com/felix-dot1212/supabase-swift/issues/589)) ([daf4db6](https://github.com/felix-dot1212/supabase-swift/commit/daf4db69c0f11acb5401866a7754eac82a8f2ea4))
* **realtime:** add closure based methods ([#345](https://github.com/felix-dot1212/supabase-swift/issues/345)) ([97ae688](https://github.com/felix-dot1212/supabase-swift/commit/97ae6883fada1531621e19a4576ba0930d1a21a9))
* **realtime:** add predefined filters instead of regular `String` ([#669](https://github.com/felix-dot1212/supabase-swift/issues/669)) ([880d278](https://github.com/felix-dot1212/supabase-swift/commit/880d278d448fce0645edc82c77e9f69ed00965ac))
* **realtime:** pull access token mechanism ([#615](https://github.com/felix-dot1212/supabase-swift/issues/615)) ([4912155](https://github.com/felix-dot1212/supabase-swift/commit/491215540f59ab47e34231ebacf220e43f216910))
* **realtime:** send broadcast events through HTTP ([#476](https://github.com/felix-dot1212/supabase-swift/issues/476)) ([aa02c22](https://github.com/felix-dot1212/supabase-swift/commit/aa02c225e099a04dcf4490c3a30e3efdb8dcfb08))
* rename onAuthStateChange to authStateChanges and add event key to posted notification ([#163](https://github.com/felix-dot1212/supabase-swift/issues/163)) ([1e9ac69](https://github.com/felix-dot1212/supabase-swift/commit/1e9ac69a6ca0ad7cba5aa220d4ad16e47c499118))
* **storage:** add `createSignedUploadURL` and `uploadToSignedURL` methods ([#290](https://github.com/felix-dot1212/supabase-swift/issues/290)) ([cceb8ce](https://github.com/felix-dot1212/supabase-swift/commit/cceb8cef0aa7e77ba15d045c597c663e7f61b76b))
* **storage:** add `createSignedURLs` method ([#273](https://github.com/felix-dot1212/supabase-swift/issues/273)) ([05533b1](https://github.com/felix-dot1212/supabase-swift/commit/05533b1c755328d23f142db153c9c3ba0e38b6de))
* **storage:** add info, exists, custom metadata, and methods for uploading file URL ([#510](https://github.com/felix-dot1212/supabase-swift/issues/510)) ([fe94a7c](https://github.com/felix-dot1212/supabase-swift/commit/fe94a7cd57074e0fc580cf0517648e4d5326b4b1))
* **storage:** copy objects between buckets ([102cfd3](https://github.com/felix-dot1212/supabase-swift/commit/102cfd3e4f20eb45557f250194e242c33ea13d26))
* **storage:** fill content-type based on file extension ([#400](https://github.com/felix-dot1212/supabase-swift/issues/400)) ([9f055d6](https://github.com/felix-dot1212/supabase-swift/commit/9f055d603ca757ae17defd8d80b6e94f103d351e))
* **storage:** move objects between buckets ([102cfd3](https://github.com/felix-dot1212/supabase-swift/commit/102cfd3e4f20eb45557f250194e242c33ea13d26))


### Bug Fixes

* add `columns` query param to insert and upsert methods ([#205](https://github.com/felix-dot1212/supabase-swift/issues/205)) ([1e6a50b](https://github.com/felix-dot1212/supabase-swift/commit/1e6a50b46aa38c781d8d377aa0be933336d95c10))
* add init with default options param ([#225](https://github.com/felix-dot1212/supabase-swift/issues/225)) ([89c7d84](https://github.com/felix-dot1212/supabase-swift/commit/89c7d845ccf2ddf1ea9400691c55e825e11aeb2f))
* Add private topic to Realtime ([#442](https://github.com/felix-dot1212/supabase-swift/issues/442)) ([0a5d832](https://github.com/felix-dot1212/supabase-swift/commit/0a5d8328af527edf3f85ded12248661b50243bb9))
* **auth:** `URLError` coercion for `RetryableError` causing session to be deleted ([#597](https://github.com/felix-dot1212/supabase-swift/issues/597)) ([23b8a3a](https://github.com/felix-dot1212/supabase-swift/commit/23b8a3a5e3d807328e90322904456138f75b0ca9))
* **auth:** add missing `@MainActor` ([#684](https://github.com/felix-dot1212/supabase-swift/issues/684)) ([1987a5d](https://github.com/felix-dot1212/supabase-swift/commit/1987a5d6ff2f966cd0f302cda6c7b8dadc6d15ba))
* **auth:** add missing channel param to signUp method ([#625](https://github.com/felix-dot1212/supabase-swift/issues/625)) ([fc802f0](https://github.com/felix-dot1212/supabase-swift/commit/fc802f00f468880d269218d30ad8f786eea3e430))
* **auth:** add missing figma, kakao, linkedin_oidc, slack_oidc, zoom, and fly providers ([#493](https://github.com/felix-dot1212/supabase-swift/issues/493)) ([76c7099](https://github.com/felix-dot1212/supabase-swift/commit/76c7099fd0b089ab7a9c0fe5e661e321d12ae0c8))
* **auth:** add missing is_anonymous field ([#355](https://github.com/felix-dot1212/supabase-swift/issues/355)) ([14541ee](https://github.com/felix-dot1212/supabase-swift/commit/14541ee6aecba9ea8d2097edabcb926de03b7527))
* **auth:** add missing nonce param when updating user ([#457](https://github.com/felix-dot1212/supabase-swift/issues/457)) ([eaf0cc9](https://github.com/felix-dot1212/supabase-swift/commit/eaf0cc9cacfeb0d9518acfac31e8b6f41a075498))
* **auth:** adds missing redirectTo query item to updateUser ([#380](https://github.com/felix-dot1212/supabase-swift/issues/380)) ([59dd66f](https://github.com/felix-dot1212/supabase-swift/commit/59dd66f24df031e960ec8683e285b24c7721738e))
* **auth:** auth event emitter being shared among clients ([#500](https://github.com/felix-dot1212/supabase-swift/issues/500)) ([4fd1f79](https://github.com/felix-dot1212/supabase-swift/commit/4fd1f794f4df24ebcfa68489185e7ea7c5c8c33f))
* **auth:** don't call removeSession prematurely ([#416](https://github.com/felix-dot1212/supabase-swift/issues/416)) ([8b8b728](https://github.com/felix-dot1212/supabase-swift/commit/8b8b728da9448f7212d480ff2df70a5382e969dc))
* **Auth:** emit initial session events ([#241](https://github.com/felix-dot1212/supabase-swift/issues/241)) ([515fc68](https://github.com/felix-dot1212/supabase-swift/commit/515fc6844c1f477c20a1df0faa38e027ffffd3a3))
* **auth:** expose KeychainLocalStorage with default init params ([#519](https://github.com/felix-dot1212/supabase-swift/issues/519)) ([40f6ea4](https://github.com/felix-dot1212/supabase-swift/commit/40f6ea46f4fb29b1d7dcf98c35b6fd7a905b8fa5))
* **auth:** extract both query and fragment from URL ([#365](https://github.com/felix-dot1212/supabase-swift/issues/365)) ([804efb4](https://github.com/felix-dot1212/supabase-swift/commit/804efb4afa358638f50a5ffa3b0b3d2aafa9542a))
* **auth:** header being overridden ([#379](https://github.com/felix-dot1212/supabase-swift/issues/379)) ([65e677a](https://github.com/felix-dot1212/supabase-swift/commit/65e677ac3ee398b61a3f5bb057937677fae0819c))
* **auth:** incorrect error when error occurs during PKCE flow ([#592](https://github.com/felix-dot1212/supabase-swift/issues/592)) ([6f9a6c4](https://github.com/felix-dot1212/supabase-swift/commit/6f9a6c498c6c2c71cf1381c4339b7be981570a1a))
* **auth:** make AuthClient an Actor ([#664](https://github.com/felix-dot1212/supabase-swift/issues/664)) ([43fa72e](https://github.com/felix-dot1212/supabase-swift/commit/43fa72e0633e0b9f5f52475feba936321bbac130))
* **auth:** mark identities last_sign_in_at field as optional ([#483](https://github.com/felix-dot1212/supabase-swift/issues/483)) ([216e271](https://github.com/felix-dot1212/supabase-swift/commit/216e2713931d029bcbdf4fe7d796c66d516fc300))
* **auth:** missing autoRefreshToken param in initializer ([#415](https://github.com/felix-dot1212/supabase-swift/issues/415)) ([2d57705](https://github.com/felix-dot1212/supabase-swift/commit/2d57705ffaa198fe0088c757ef946b477d816c34))
* **auth:** prevent from requesting login keychain password os macOS ([#455](https://github.com/felix-dot1212/supabase-swift/issues/455)) ([5d0e20e](https://github.com/felix-dot1212/supabase-swift/commit/5d0e20ebab3cc13ccef2146f7bbe363de205443b))
* **auth:** sign out regardless of request success ([#375](https://github.com/felix-dot1212/supabase-swift/issues/375)) ([5dcc642](https://github.com/felix-dot1212/supabase-swift/commit/5dcc64215440a66841f3bd056369f19550f70c1f))
* **auth:** sign out should ignore 403s ([#359](https://github.com/felix-dot1212/supabase-swift/issues/359)) ([01e318c](https://github.com/felix-dot1212/supabase-swift/commit/01e318c66b0c5f89b3649a81e8fc3df36030205d))
* **auth:** store code verifier in keychain ([#502](https://github.com/felix-dot1212/supabase-swift/issues/502)) ([ddf2643](https://github.com/felix-dot1212/supabase-swift/commit/ddf264370c85fcead3e9996c74be3742e58997e9))
* **auth:** store session directly without wrapping in StoredSession type ([#513](https://github.com/felix-dot1212/supabase-swift/issues/513)) ([47cdcdd](https://github.com/felix-dot1212/supabase-swift/commit/47cdcdd3132ab037a65a434f64c514b3df4a1e8f))
* **auth:** stored session backwards compatibility ([#294](https://github.com/felix-dot1212/supabase-swift/issues/294)) ([5bd5d88](https://github.com/felix-dot1212/supabase-swift/commit/5bd5d88bfba42bfef3a262d3e09362c6600ca67b))
* **auth:** use project ref as namespace for storing token ([#430](https://github.com/felix-dot1212/supabase-swift/issues/430)) ([de6ef4e](https://github.com/felix-dot1212/supabase-swift/commit/de6ef4e8e1957af66aed82290b45c0658ba191f1))
* **auth:** verify otp using token hash ([#451](https://github.com/felix-dot1212/supabase-swift/issues/451)) ([0dcfc80](https://github.com/felix-dot1212/supabase-swift/commit/0dcfc80d8e3be6ab2817d33812ee60900d43e026))
* concurrency warnings pre swift 6 support ([#428](https://github.com/felix-dot1212/supabase-swift/issues/428)) ([758c0ef](https://github.com/felix-dot1212/supabase-swift/commit/758c0ef74d6a16dc139db11d682a450cda083386))
* date formatter breaking change ([#435](https://github.com/felix-dot1212/supabase-swift/issues/435)) ([62abed1](https://github.com/felix-dot1212/supabase-swift/commit/62abed126d8baaba2f330b379ae81a17c0dcd08b))
* examples build error ([88468dd](https://github.com/felix-dot1212/supabase-swift/commit/88468dd1adf76d7887144f26c44bb7612006da8e))
* expose SupabaseClient headers ([#447](https://github.com/felix-dot1212/supabase-swift/issues/447)) ([02df44b](https://github.com/felix-dot1212/supabase-swift/commit/02df44b88b5ba052b4dba865a35990513592d291))
* **functions:** fix streamed responses ([#525](https://github.com/felix-dot1212/supabase-swift/issues/525)) ([e72981b](https://github.com/felix-dot1212/supabase-swift/commit/e72981b3cc66713ec5c51d41689392b92a46fa2e))
* **functions:** functions overrides headers ([#160](https://github.com/felix-dot1212/supabase-swift/issues/160)) ([5869466](https://github.com/felix-dot1212/supabase-swift/commit/5869466f290f766cda362d26c3c088c2af1090dc))
* **functions:** invoke with custom http method ([#367](https://github.com/felix-dot1212/supabase-swift/issues/367)) ([e782e5e](https://github.com/felix-dot1212/supabase-swift/commit/e782e5ed10594b61c9f44482404d209c565006a0))
* general auth improvements ([#561](https://github.com/felix-dot1212/supabase-swift/issues/561)) ([efc1b78](https://github.com/felix-dot1212/supabase-swift/commit/efc1b78b8eb84e78571db376611152215c82598c))
* **gotrue:** AuthResponse return non-optional user ([#174](https://github.com/felix-dot1212/supabase-swift/issues/174)) ([43f2b2f](https://github.com/felix-dot1212/supabase-swift/commit/43f2b2f7f02494c938e01ee168d11786c922af22))
* **gotrue:** decoding of error types ([#169](https://github.com/felix-dot1212/supabase-swift/issues/169)) ([d0bc0e1](https://github.com/felix-dot1212/supabase-swift/commit/d0bc0e1bd32a7398e4004fcd428e580135c660d8))
* **gotrue:** ignore 401 and 404 errors on sign out ([#179](https://github.com/felix-dot1212/supabase-swift/issues/179)) ([5744a3f](https://github.com/felix-dot1212/supabase-swift/commit/5744a3fa2d7147e1c5c82ddda6148a9c898bd9f2))
* invalid identifier for _Helpers target ([#414](https://github.com/felix-dot1212/supabase-swift/issues/414)) ([801ad67](https://github.com/felix-dot1212/supabase-swift/commit/801ad67515cd490d32b51e668f56934451c384b3))
* issue with MainActor isolated property on Swift 5.9 ([#577](https://github.com/felix-dot1212/supabase-swift/issues/577)) ([66668cb](https://github.com/felix-dot1212/supabase-swift/commit/66668cb3cc84376dcb55162bcd395aca876c9e7d))
* linux build ([#350](https://github.com/felix-dot1212/supabase-swift/issues/350)) ([4ab277f](https://github.com/felix-dot1212/supabase-swift/commit/4ab277fe2edbffd27fdfeeacc495a2f32f714077))
* Make the return value of accessToken nullable ([#641](https://github.com/felix-dot1212/supabase-swift/issues/641)) ([c823f52](https://github.com/felix-dot1212/supabase-swift/commit/c823f52dfdf382813fff16d35fbd24c5f4d809cb))
* manually percent encode query items to allow values with + sign ([#402](https://github.com/felix-dot1212/supabase-swift/issues/402)) ([1aece66](https://github.com/felix-dot1212/supabase-swift/commit/1aece665fedd7866099b7d74294c6602f03b1e4b))
* **postgrest:** avoid duplicated columns and prefer fields ([#463](https://github.com/felix-dot1212/supabase-swift/issues/463)) ([2568581](https://github.com/felix-dot1212/supabase-swift/commit/2568581d1096676013095794c70762f1dea2637c))
* **postgrest:** race condition when executing request ([#327](https://github.com/felix-dot1212/supabase-swift/issues/327)) ([6832d80](https://github.com/felix-dot1212/supabase-swift/commit/6832d801439074e304fc6e92f2b82f81c7088a5c))
* **postgrest:** race condition when setting fetchOptions and execute method call ([#325](https://github.com/felix-dot1212/supabase-swift/issues/325)) ([5d4c867](https://github.com/felix-dot1212/supabase-swift/commit/5d4c867d3ef70310fa781964cddcb9f220ebcf82))
* **postgrest:** update parameter of `is` filter to allow only `Bool` or `nil` ([#382](https://github.com/felix-dot1212/supabase-swift/issues/382)) ([e954f62](https://github.com/felix-dot1212/supabase-swift/commit/e954f62395d5bf9150a4ad77513e3c42f3955120))
* race condition when accessing SupabaseClient ([#386](https://github.com/felix-dot1212/supabase-swift/issues/386)) ([7167faf](https://github.com/felix-dot1212/supabase-swift/commit/7167fafc5a13ce7cdec965970b0842e901210cd0))
* realtime reconnection ([#261](https://github.com/felix-dot1212/supabase-swift/issues/261)) ([01c36aa](https://github.com/felix-dot1212/supabase-swift/commit/01c36aae986e27551dfca5f80dcabef1698756f5))
* **realtime:** add missing `onPostgresChange` overload ([#528](https://github.com/felix-dot1212/supabase-swift/issues/528)) ([bb4c274](https://github.com/felix-dot1212/supabase-swift/commit/bb4c274cf992b5ad2a0a7dbf8ffbd32b2c7d8b3f))
* **realtime:** add RealtimeSubscription and deprecate Subscription ([#542](https://github.com/felix-dot1212/supabase-swift/issues/542)) ([ba1dc00](https://github.com/felix-dot1212/supabase-swift/commit/ba1dc001170a8feb34e8e41a85a9061c80561047))
* **realtime:** Adds missing `.unsubscribed` status change ([#420](https://github.com/felix-dot1212/supabase-swift/issues/420)) ([efe0de6](https://github.com/felix-dot1212/supabase-swift/commit/efe0de6e6c901a8466c5c5ac375f91a094e455f5))
* **realtime:** allow to nullify access token ([49b219b](https://github.com/felix-dot1212/supabase-swift/commit/49b219b3b32dabbc5c3c419f22bb80a981d2767a))
* **realtime:** auto reconnect after calling disconnect, and several refactors ([#627](https://github.com/felix-dot1212/supabase-swift/issues/627)) ([4e1008b](https://github.com/felix-dot1212/supabase-swift/commit/4e1008b9032c0750d65e31ba9bd3069f59153083))
* **realtime:** crash when connecting socket ([#470](https://github.com/felix-dot1212/supabase-swift/issues/470)) ([e3647e6](https://github.com/felix-dot1212/supabase-swift/commit/e3647e6c7835040e6f8f5e35c366e920a048e612))
* **realtime:** deprecate `updateAuth` from channel ([49b219b](https://github.com/felix-dot1212/supabase-swift/commit/49b219b3b32dabbc5c3c419f22bb80a981d2767a))
* **realtime:** handle timeout when subscribing to channel ([#349](https://github.com/felix-dot1212/supabase-swift/issues/349)) ([b233356](https://github.com/felix-dot1212/supabase-swift/commit/b233356cd1379c8b127413812a626c6514f91ca8))
* **realtime:** lost `postgres_changes` on resubscribe ([#585](https://github.com/felix-dot1212/supabase-swift/issues/585)) ([b8f3bc1](https://github.com/felix-dot1212/supabase-swift/commit/b8f3bc1827774bcca06769c8063826d08ee5e353))
* **realtime:** prevent sending expired tokens ([#618](https://github.com/felix-dot1212/supabase-swift/issues/618)) ([08d1385](https://github.com/felix-dot1212/supabase-swift/commit/08d1385ffd519c8ed14560318ede3a58b6a5db36))
* **realtime:** remove jwt check ([#658](https://github.com/felix-dot1212/supabase-swift/issues/658)) ([96d6489](https://github.com/felix-dot1212/supabase-swift/commit/96d6489c0e1c1363cb3899f1268936f50daaf676))
* **realtime:** revert realtime token to apikey on user sign out ([#429](https://github.com/felix-dot1212/supabase-swift/issues/429)) ([a72c8e4](https://github.com/felix-dot1212/supabase-swift/commit/a72c8e47ef0e8d96c3df70211929e9ab24d14381))
* **realtime:** send access token to realtime on initial session ([#439](https://github.com/felix-dot1212/supabase-swift/issues/439)) ([b1b2fdb](https://github.com/felix-dot1212/supabase-swift/commit/b1b2fdb4a8bbd386e33aca0ff9cae6edbf5dbfac))
* **realtime:** Set default heartbeat interval to 25s ([#667](https://github.com/felix-dot1212/supabase-swift/issues/667)) ([0200fe4](https://github.com/felix-dot1212/supabase-swift/commit/0200fe4485f3df781aa8949cbd6ef8bf36e7c1a3))
* **realtime:** web socket message listener doesn't stop ([#284](https://github.com/felix-dot1212/supabase-swift/issues/284)) ([6c80207](https://github.com/felix-dot1212/supabase-swift/commit/6c802078b8c0087529d7d036687b206b5b277d77))
* remove kSecUseDataProtectionKeychain ([#574](https://github.com/felix-dot1212/supabase-swift/issues/574)) ([7189f5b](https://github.com/felix-dot1212/supabase-swift/commit/7189f5b3a01a60e5425120826c96de74482951ff))
* remove usage of `nonisolated(unsafe)` from codebase ([#638](https://github.com/felix-dot1212/supabase-swift/issues/638)) ([60526a3](https://github.com/felix-dot1212/supabase-swift/commit/60526a31ad7a2f9a6a822f6cf1ebde100bb702b8))
* replace to HTTPTypes Components from Helpers Components ([#564](https://github.com/felix-dot1212/supabase-swift/issues/564)) ([bc3fbc9](https://github.com/felix-dot1212/supabase-swift/commit/bc3fbc9152bd829387598f059d00bc89f13abb18))
* revert AnyJSON codable ([#580](https://github.com/felix-dot1212/supabase-swift/issues/580)) ([d47572d](https://github.com/felix-dot1212/supabase-swift/commit/d47572d7061d0db75820aa46382f4b860943e320))
* **storage:** cache control ([#551](https://github.com/felix-dot1212/supabase-swift/issues/551)) ([4d790b0](https://github.com/felix-dot1212/supabase-swift/commit/4d790b0974f8011d8d9e539ff779851fa125b014))
* **storage:** getSignedURLs method using wrong encoder ([#352](https://github.com/felix-dot1212/supabase-swift/issues/352)) ([67aa8bb](https://github.com/felix-dot1212/supabase-swift/commit/67aa8bb866775b8029dff10324294cbdafb984e6))
* **storage:** headers overridden ([#384](https://github.com/felix-dot1212/supabase-swift/issues/384)) ([a00d536](https://github.com/felix-dot1212/supabase-swift/commit/a00d5364a557a410fdcdfb71ad11f64a92abaa41))
* **storage:** list folders ([#454](https://github.com/felix-dot1212/supabase-swift/issues/454)) ([9264665](https://github.com/felix-dot1212/supabase-swift/commit/92646652e1048a18c476faea1cea8e243793dbfe))
* **storage:** list method using wrong encoder ([#405](https://github.com/felix-dot1212/supabase-swift/issues/405)) ([6fa0db7](https://github.com/felix-dot1212/supabase-swift/commit/6fa0db70ceac62ea68f69037d3963e6036cd15e7))
* Swift 6 now has URLSession async method ([#565](https://github.com/felix-dot1212/supabase-swift/issues/565)) ([de7b40a](https://github.com/felix-dot1212/supabase-swift/commit/de7b40a14d1bb5067f2e5c2eabc77f726422a935))
* Swift 6 warnings related to `@_unsafeInheritExecutor` attribute ([#549](https://github.com/felix-dot1212/supabase-swift/issues/549)) ([00c0753](https://github.com/felix-dot1212/supabase-swift/commit/00c0753ee55a98bcf7ba21071a1d54f1b7093902))
* throw generic HTTPError ([#368](https://github.com/felix-dot1212/supabase-swift/issues/368)) ([a6dc708](https://github.com/felix-dot1212/supabase-swift/commit/a6dc708f558ba243e1a4af9f326eeccbcd4d5a38))
* update Realtime auth when initialSession is emitted ([9191446](https://github.com/felix-dot1212/supabase-swift/commit/91914467dc0b2cc52a20d24ef0724628652a26e1))
* use LockIsolated on EventEmitter ([c899315](https://github.com/felix-dot1212/supabase-swift/commit/c899315f963c01cea12e9cb83493db2ce1523acc))

## [2.26.0](https://github.com/supabase/supabase-swift/compare/v2.25.0...v2.26.0) (2025-03-06)


### Features

* add Android support ([#673](https://github.com/supabase/supabase-swift/issues/673)) ([6ec2cdd](https://github.com/supabase/supabase-swift/commit/6ec2cdd994f80cc754f310b4aaf307671454f992))


### Bug Fixes

* **auth:** add missing `@MainActor` ([#684](https://github.com/supabase/supabase-swift/issues/684)) ([16ffdd4](https://github.com/supabase/supabase-swift/commit/16ffdd4a2f996626be8cb595ab6f31d94e8eeb4b))

## [2.25.0](https://github.com/supabase/supabase-swift/compare/v2.24.7...v2.25.0) (2025-02-20)


### Features

* **realtime:** add predefined filters instead of regular `String` ([#669](https://github.com/supabase/supabase-swift/issues/669)) ([3dc9b82](https://github.com/supabase/supabase-swift/commit/3dc9b82e90a5158664d163caeb397e220f58d8dd))

## [2.24.7](https://github.com/supabase/supabase-swift/compare/v2.24.6...v2.24.7) (2025-02-18)


### Bug Fixes

* **realtime:** Set default heartbeat interval to 25s ([#667](https://github.com/supabase/supabase-swift/issues/667)) ([14c590d](https://github.com/supabase/supabase-swift/commit/14c590d08898e5a3c1c131ad704966d73df7e538))

## [2.24.6](https://github.com/supabase/supabase-swift/compare/v2.24.5...v2.24.6) (2025-02-14)


### Bug Fixes

* **auth:** make AuthClient an Actor ([#664](https://github.com/supabase/supabase-swift/issues/664)) ([bdf1961](https://github.com/supabase/supabase-swift/commit/bdf19614b35b76281f2a50e785b6d21fa9578e40))

## [2.24.5](https://github.com/supabase/supabase-swift/compare/v2.24.4...v2.24.5) (2025-02-10)


### Bug Fixes

* **realtime:** remove jwt check ([#658](https://github.com/supabase/supabase-swift/issues/658)) ([4c95559](https://github.com/supabase/supabase-swift/commit/4c955592c58c7d0aafbd0c32ae8a85e213303caa))

## [2.24.4](https://github.com/supabase/supabase-swift/compare/v2.24.3...v2.24.4) (2025-01-16)


### Bug Fixes

* Make the return value of accessToken nullable ([#641](https://github.com/supabase/supabase-swift/issues/641)) ([af9b774](https://github.com/supabase/supabase-swift/commit/af9b77453892da562c444e94ff7538051a2dd0a4))

## [2.24.3](https://github.com/supabase/supabase-swift/compare/v2.24.2...v2.24.3) (2025-01-14)


### Bug Fixes

* remove usage of `nonisolated(unsafe)` from codebase ([#638](https://github.com/supabase/supabase-swift/issues/638)) ([3d87608](https://github.com/supabase/supabase-swift/commit/3d876089b2429389f0e16e4238cc11bd444a1254))

## [2.24.2](https://github.com/supabase/supabase-swift/compare/v2.24.1...v2.24.2) (2025-01-08)


### Bug Fixes

* **realtime:** auto reconnect after calling disconnect, and several refactors ([#627](https://github.com/supabase/supabase-swift/issues/627)) ([1887f4f](https://github.com/supabase/supabase-swift/commit/1887f4f376e172bb7fbcec84506fea6c4797fde7))

## [2.24.1](https://github.com/supabase/supabase-swift/compare/v2.24.0...v2.24.1) (2024-12-16)


### Bug Fixes

* **auth:** add missing channel param to signUp method ([#625](https://github.com/supabase/supabase-swift/issues/625)) ([3a36ab7](https://github.com/supabase/supabase-swift/commit/3a36ab74c4fbd9224c03dabd88046bba49b0de9c))

## [2.24.0](https://github.com/supabase/supabase-swift/compare/v2.23.0...v2.24.0) (2024-12-05)


### Features

* **realtime:** pull access token mechanism ([#615](https://github.com/supabase/supabase-swift/issues/615)) ([c88dd36](https://github.com/supabase/supabase-swift/commit/c88dd3675b8bc7da93c71847ff9ba9862323ff8d))


### Bug Fixes

* **realtime:** prevent sending expired tokens ([#618](https://github.com/supabase/supabase-swift/issues/618)) ([595277b](https://github.com/supabase/supabase-swift/commit/595277b5eb35b8b76bbb000d44fc221c4d3298f1))

## [2.23.0](https://github.com/supabase/supabase-swift/compare/v2.22.1...v2.23.0) (2024-11-22)


### Features

* **postgrest:** add read-only mode for RPC ([#600](https://github.com/supabase/supabase-swift/issues/600)) ([d81fc86](https://github.com/supabase/supabase-swift/commit/d81fc865409821dc0816c930d2d537a126b4fe06))

## [2.22.1](https://github.com/supabase/supabase-swift/compare/v2.22.0...v2.22.1) (2024-11-12)


### Bug Fixes

* **auth:** `URLError` coercion for `RetryableError` causing session to be deleted ([#597](https://github.com/supabase/supabase-swift/issues/597)) ([d67b7cf](https://github.com/supabase/supabase-swift/commit/d67b7cf850d43c2a8ecf39feedfc39528f55f139))

## [2.22.0](https://github.com/supabase/supabase-swift/compare/v2.21.0...v2.22.0) (2024-11-06)


### Features

* **auth:** add new error codes ([#586](https://github.com/supabase/supabase-swift/issues/586)) ([1721c08](https://github.com/supabase/supabase-swift/commit/1721c08c7710e0cba1390962441fe595b613072c))


### Bug Fixes

* **auth:** incorrect error when error occurs during PKCE flow ([#592](https://github.com/supabase/supabase-swift/issues/592)) ([84ce6f2](https://github.com/supabase/supabase-swift/commit/84ce6f29b2ee2192b57d8ff7c36af3378c696653))

## [2.21.0](https://github.com/supabase/supabase-swift/compare/v2.20.5...v2.21.0) (2024-11-05)


### Features

* **realtime:** add `system` event ([#589](https://github.com/supabase/supabase-swift/issues/589)) ([1176dea](https://github.com/supabase/supabase-swift/commit/1176dea4d90f353ae777a633fc079dedf98276ff))


### Bug Fixes

* **realtime:** lost `postgres_changes` on resubscribe ([#585](https://github.com/supabase/supabase-swift/issues/585)) ([fabc07d](https://github.com/supabase/supabase-swift/commit/fabc07dac833aa94e35bf932899dfb5d1a868cfb))

## [2.20.5](https://github.com/supabase/supabase-swift/compare/v2.20.4...v2.20.5) (2024-10-24)


### Bug Fixes

* issue with MainActor isolated property on Swift 5.9 ([#577](https://github.com/supabase/supabase-swift/issues/577)) ([7266b64](https://github.com/supabase/supabase-swift/commit/7266b64e1e0b58fc893693fa80872b6d77bf1555))
* revert AnyJSON codable ([#580](https://github.com/supabase/supabase-swift/issues/580)) ([bfb6ed7](https://github.com/supabase/supabase-swift/commit/bfb6ed7b9b69123dc5cc16458da62ee3546eaf98))

## [2.20.4](https://github.com/supabase/supabase-swift/compare/v2.20.3...v2.20.4) (2024-10-23)


### Bug Fixes

* **storage:** cache control ([#551](https://github.com/supabase/supabase-swift/issues/551)) ([8a2b196](https://github.com/supabase/supabase-swift/commit/8a2b19690cf165c80454ff6388cb9a202b04172c))

## [2.20.3](https://github.com/supabase/supabase-swift/compare/v2.20.2...v2.20.3) (2024-10-22)


### Bug Fixes

* remove kSecUseDataProtectionKeychain ([#574](https://github.com/supabase/supabase-swift/issues/574)) ([554f916](https://github.com/supabase/supabase-swift/commit/554f91689eb13c1a923a53bddb5d194e6b80328a))

## [2.20.2](https://github.com/supabase/supabase-swift/compare/v2.20.1...v2.20.2) (2024-10-17)


### Bug Fixes

* general auth improvements ([#561](https://github.com/supabase/supabase-swift/issues/561)) ([5f4c0f2](https://github.com/supabase/supabase-swift/commit/5f4c0f256c74beb47ce2a42951014504ba798dd6))
* replace to HTTPTypes Components from Helpers Components ([#564](https://github.com/supabase/supabase-swift/issues/564)) ([71dee2a](https://github.com/supabase/supabase-swift/commit/71dee2ac35204c40e11d7aa3c3c6f5def95520f9))
* Swift 6 now has URLSession async method ([#565](https://github.com/supabase/supabase-swift/issues/565)) ([5786dd6](https://github.com/supabase/supabase-swift/commit/5786dd6c06ceead5851fb6527a48d0cee48654af))

## [2.20.1](https://github.com/supabase/supabase-swift/compare/v2.20.0...v2.20.1) (2024-10-09)


### Bug Fixes

* **realtime:** add RealtimeSubscription and deprecate Subscription ([#542](https://github.com/supabase/supabase-swift/issues/542)) ([3a44f30](https://github.com/supabase/supabase-swift/commit/3a44f306f32aaf0a096c316f02995f0de649b991))
* **realtime:** allow to nullify access token ([45273e5](https://github.com/supabase/supabase-swift/commit/45273e5325f57c040030901cb269fff5c0a66974))
* **realtime:** deprecate `updateAuth` from channel ([45273e5](https://github.com/supabase/supabase-swift/commit/45273e5325f57c040030901cb269fff5c0a66974))
* Swift 6 warnings related to `@_unsafeInheritExecutor` attribute ([#549](https://github.com/supabase/supabase-swift/issues/549)) ([eab7a4a](https://github.com/supabase/supabase-swift/commit/eab7a4a7a494cfdf354ecd16373bbc05d4a0977f))

## [2.20.0](https://github.com/supabase/supabase-swift/compare/v2.19.0...v2.20.0) (2024-09-25)


### Features

* **storage:** add info, exists, custom metadata, and methods for uploading file URL ([#510](https://github.com/supabase/supabase-swift/issues/510)) ([d9ba673](https://github.com/supabase/supabase-swift/commit/d9ba673b882c84e5fae277510d147f52e22b861b))

## [2.19.0](https://github.com/supabase/supabase-swift/compare/v2.18.0...v2.19.0) (2024-09-24)


### Features

* **auth:** add listUsers admin method ([#539](https://github.com/supabase/supabase-swift/issues/539)) ([1851262](https://github.com/supabase/supabase-swift/commit/1851262b5c4eb8247c10e768be3f9110938db892))


### Bug Fixes

* **realtime:** add missing `onPostgresChange` overload ([#528](https://github.com/supabase/supabase-swift/issues/528)) ([95e249f](https://github.com/supabase/supabase-swift/commit/95e249f135702c502ac8c0edc7f437337458796b))

## [2.18.0](https://github.com/supabase/supabase-swift/compare/v2.17.1...v2.18.0) (2024-09-07)


### Features

* **auth:** add support for error codes and refactor `AuthError` ([#518](https://github.com/supabase/supabase-swift/issues/518)) ([7601e17](https://github.com/supabase/supabase-swift/commit/7601e17aa87cd832aee125095a89db2175364e35))


### Bug Fixes

* **functions:** fix streamed responses ([#525](https://github.com/supabase/supabase-swift/issues/525)) ([0631069](https://github.com/supabase/supabase-swift/commit/0631069ec71cfce0e1a56bb386a679c72e862c48))

## [2.17.1](https://github.com/supabase/supabase-swift/compare/v2.17.0...v2.17.1) (2024-09-02)


### Bug Fixes

* **auth:** expose KeychainLocalStorage with default init params ([#519](https://github.com/supabase/supabase-swift/issues/519)) ([c1095c9](https://github.com/supabase/supabase-swift/commit/c1095c95a2b01a3ad76a996e6c81ed8b25dab214))

## [2.17.0](https://github.com/supabase/supabase-swift/compare/v2.16.1...v2.17.0) (2024-08-28)


### Features

* **postgrest:** set header on a per call basis ([#508](https://github.com/supabase/supabase-swift/issues/508)) ([a15efb1](https://github.com/supabase/supabase-swift/commit/a15efb15a26c76d4bbc13e570c4841633ccd6177))
* **postgrest:** use `Date` when filtering columns ([#514](https://github.com/supabase/supabase-swift/issues/514)) ([1b0155c](https://github.com/supabase/supabase-swift/commit/1b0155c3d35c23ccefceffbb13eb36f2c5ec513f))


### Bug Fixes

* **auth:** store session directly without wrapping in StoredSession type ([#513](https://github.com/supabase/supabase-swift/issues/513)) ([5de2d8d](https://github.com/supabase/supabase-swift/commit/5de2d8da722183a3be80bfddd48637932e9cbc23))

## [2.16.1](https://github.com/supabase/supabase-swift/compare/v2.16.0...v2.16.1) (2024-08-14)


### Bug Fixes

* **auth:** auth event emitter being shared among clients ([#500](https://github.com/supabase/supabase-swift/issues/500)) ([83f3385](https://github.com/supabase/supabase-swift/commit/83f338502a242691bc6455819fc0599c5e2021c1))
* **auth:** store code verifier in keychain ([#502](https://github.com/supabase/supabase-swift/issues/502)) ([b86154a](https://github.com/supabase/supabase-swift/commit/b86154a9aa808f40f87de39e32cf48e40534662e))

## [2.16.0](https://github.com/supabase/supabase-swift/compare/v2.15.3...v2.16.0) (2024-08-12)


### Features

* **auth:** add MFA phone ([#496](https://github.com/supabase/supabase-swift/issues/496)) ([2e445f2](https://github.com/supabase/supabase-swift/commit/2e445f24ba1856dd7ebb57dfabbba45ec1e0f118))

## [2.15.3](https://github.com/supabase/supabase-swift/compare/v2.15.2...v2.15.3) (2024-08-06)


### Bug Fixes

* **auth:** add missing figma, kakao, linkedin_oidc, slack_oidc, zoom, and fly providers ([#493](https://github.com/supabase/supabase-swift/issues/493)) ([152f5ce](https://github.com/supabase/supabase-swift/commit/152f5ce8e14dd54ad70ab0184d9dcb9ead65d824))

## [2.15.2](https://github.com/supabase/supabase-swift/compare/v2.15.1...v2.15.2) (2024-07-30)


### Bug Fixes

* **auth:** mark identities last_sign_in_at field as optional ([#483](https://github.com/supabase/supabase-swift/issues/483)) ([c93cf90](https://github.com/supabase/supabase-swift/commit/c93cf90d60d7d6ed1ff04a6a51e72ab009f30795))

## [2.15.1](https://github.com/supabase/supabase-swift/compare/v2.15.0...v2.15.1) (2024-07-30)


### Bug Fixes

* **storage:** list folders ([#454](https://github.com/supabase/supabase-swift/issues/454)) ([4e9f52a](https://github.com/supabase/supabase-swift/commit/4e9f52a0257a8b6e747854a53553421322a947df))

## [2.15.0](https://github.com/supabase/supabase-swift/compare/v2.14.3...v2.15.0) (2024-07-29)


### Features

* add third-party auth support ([#423](https://github.com/supabase/supabase-swift/issues/423)) ([d760f2d](https://github.com/supabase/supabase-swift/commit/d760f2d28373e80c16e8e256bf2491780a820afc))
* **realtime:** send broadcast events through HTTP ([#476](https://github.com/supabase/supabase-swift/issues/476)) ([93f4ff5](https://github.com/supabase/supabase-swift/commit/93f4ff5d3504ec5cac7e51bff4923dab51adb04b))

## [2.14.3](https://github.com/supabase/supabase-swift/compare/v2.14.2...v2.14.3) (2024-07-19)


### Bug Fixes

* **realtime:** crash when connecting socket ([#470](https://github.com/supabase/supabase-swift/issues/470)) ([5cf4f56](https://github.com/supabase/supabase-swift/commit/5cf4f563c0cbc551d8e60f5e7f8a45034644580c))

## [2.14.2](https://github.com/supabase/supabase-swift/compare/v2.14.1...v2.14.2) (2024-07-13)


### Bug Fixes

* **postgrest:** avoid duplicated columns and prefer fields ([#463](https://github.com/supabase/supabase-swift/issues/463)) ([e4f85f3](https://github.com/supabase/supabase-swift/commit/e4f85f3512ce06e85d8ca2922f0a4ca011079c21))

## [2.14.1](https://github.com/supabase/supabase-swift/compare/v2.14.0...v2.14.1) (2024-07-11)


### Bug Fixes

* **auth:** add missing nonce param when updating user ([#457](https://github.com/supabase/supabase-swift/issues/457)) ([a087a6a](https://github.com/supabase/supabase-swift/commit/a087a6a872f0540f163e89bcab6839d0f1695fd8))
* **auth:** prevent from requesting login keychain password os macOS ([#455](https://github.com/supabase/supabase-swift/issues/455)) ([3e45b5a](https://github.com/supabase/supabase-swift/commit/3e45b5a79f7a33e7752102c31730b7604292cb89))

## [2.14.0](https://github.com/supabase/supabase-swift/compare/v2.13.9...v2.14.0) (2024-07-09)


### Features

* **auth:** add support for multiple auth instances ([#445](https://github.com/supabase/supabase-swift/issues/445)) ([6803ddd](https://github.com/supabase/supabase-swift/commit/6803ddd02aa02b34ee093725611710da4f7671c1))


### Bug Fixes

* **auth:** verify otp using token hash ([#451](https://github.com/supabase/supabase-swift/issues/451)) ([58ab9af](https://github.com/supabase/supabase-swift/commit/58ab9afb152d3701a63009cc83c392f97e5bdea1))

## [2.13.9](https://github.com/supabase/supabase-swift/compare/v2.13.8...v2.13.9) (2024-07-06)


### Bug Fixes

* expose SupabaseClient headers ([#447](https://github.com/supabase/supabase-swift/issues/447)) ([50fc325](https://github.com/supabase/supabase-swift/commit/50fc32501fe6fc229841f35511b672cd29364aaa))

## [2.13.8](https://github.com/supabase/supabase-swift/compare/v2.13.7...v2.13.8) (2024-07-04)


### Bug Fixes

* Add private topic to Realtime ([#442](https://github.com/supabase/supabase-swift/issues/442)) ([a491b29](https://github.com/supabase/supabase-swift/commit/a491b297ca4cf965e554632d0a9be4052844d6a8))

## [2.13.7](https://github.com/supabase/supabase-swift/compare/v2.13.6...v2.13.7) (2024-07-02)


### Bug Fixes

* **realtime:** send access token to realtime on initial session ([#439](https://github.com/supabase/supabase-swift/issues/439)) ([048e81b](https://github.com/supabase/supabase-swift/commit/048e81b9ca5a317ad4340c4bae60f556d9e31584))

## [2.13.6](https://github.com/supabase/supabase-swift/compare/v2.13.5...v2.13.6) (2024-07-01)


### Bug Fixes

* date formatter breaking change ([#435](https://github.com/supabase/supabase-swift/issues/435)) ([6b4cc2e](https://github.com/supabase/supabase-swift/commit/6b4cc2e7fc3b61960449a15d36ef732c8020f222))

## [2.13.5](https://github.com/supabase/supabase-swift/compare/v2.13.4...v2.13.5) (2024-06-28)


### Bug Fixes

* **auth:** use project ref as namespace for storing token ([#430](https://github.com/supabase/supabase-swift/issues/430)) ([82fa93d](https://github.com/supabase/supabase-swift/commit/82fa93d0c19de6baa6de4b02dd0cdf3a17a3f0cd))

## [2.13.4](https://github.com/supabase/supabase-swift/compare/v2.13.3...v2.13.4) (2024-06-28)


### Bug Fixes

* concurrency warnings pre swift 6 support ([#428](https://github.com/supabase/supabase-swift/issues/428)) ([bee6fa7](https://github.com/supabase/supabase-swift/commit/bee6fa70182cd750d4a9c2c107bc143470c4108b))
* **realtime:** revert realtime token to apikey on user sign out ([#429](https://github.com/supabase/supabase-swift/issues/429)) ([11c629f](https://github.com/supabase/supabase-swift/commit/11c629fce23ddc3ae82ba8f04814cb0841af0ae3))

## [2.13.3](https://github.com/supabase/supabase-swift/compare/v2.13.2...v2.13.3) (2024-06-17)


### Bug Fixes

* **realtime:** Adds missing `.unsubscribed` status change ([#420](https://github.com/supabase/supabase-swift/issues/420)) ([dc90fb6](https://github.com/supabase/supabase-swift/commit/dc90fb675e9b9ccf7733d28a4fcfc3e59416e119))

## [2.13.2](https://github.com/supabase/supabase-swift/compare/v2.13.1...v2.13.2) (2024-06-07)


### Bug Fixes

* **auth:** don't call removeSession prematurely ([#416](https://github.com/supabase/supabase-swift/issues/416)) ([00221a8](https://github.com/supabase/supabase-swift/commit/00221a84fbf026ab41911d23be01e8065a949989))

## [2.13.1](https://github.com/supabase/supabase-swift/compare/v2.13.0...v2.13.1) (2024-06-06)


### Bug Fixes

* **auth:** missing autoRefreshToken param in initializer ([#415](https://github.com/supabase/supabase-swift/issues/415)) ([32de22f](https://github.com/supabase/supabase-swift/commit/32de22ffa775bfc45f4077330de3dbe81b327f3e))
* invalid identifier for _Helpers target ([#414](https://github.com/supabase/supabase-swift/issues/414)) ([b2c8aee](https://github.com/supabase/supabase-swift/commit/b2c8aee894c7a9c729d66bd850f4ffa706a21ae3))

## [2.13.0](https://github.com/supabase/supabase-swift/compare/v2.12.0...v2.13.0) (2024-06-04)


### Features

* **auth:** add convenience deep link handling methods ([#397](https://github.com/supabase/supabase-swift/issues/397)) ([db7a094](https://github.com/supabase/supabase-swift/commit/db7a0949d2e2a7a16f0d684e11d569b7ad0bee8e))
* **auth:** add options for disabling auto refresh token ([#411](https://github.com/supabase/supabase-swift/issues/411)) ([24f6a76](https://github.com/supabase/supabase-swift/commit/24f6a7683f8154b6f7a0c80b6324717efdd95c76))
* improve logging on token refresh logic ([#410](https://github.com/supabase/supabase-swift/issues/410)) ([a8ed053](https://github.com/supabase/supabase-swift/commit/a8ed053c96eaf69146dc40bbec7702fe88077354))
* **storage:** fill content-type based on file extension ([#400](https://github.com/supabase/supabase-swift/issues/400)) ([569f445](https://github.com/supabase/supabase-swift/commit/569f4455bbde6e6ea1c6a7f630a1e1d66dc39bb0))


### Bug Fixes

* **realtime:** handle timeout when subscribing to channel ([#349](https://github.com/supabase/supabase-swift/issues/349)) ([a222dd4](https://github.com/supabase/supabase-swift/commit/a222dd4aad072917d44ba18232bb32c01b5e1c18))

## [2.12.0](https://github.com/supabase/supabase-swift/compare/v2.11.0...v2.12.0) (2024-05-26)


### Features

* **auth:** add isExpired variable to session type ([#399](https://github.com/supabase/supabase-swift/issues/399)) ([dcada1a](https://github.com/supabase/supabase-swift/commit/dcada1accae66793e0f4e046dd8620870b93b3dd))
* **auth:** retry auth requests, and schedule next refresh retry in background ([#395](https://github.com/supabase/supabase-swift/issues/395)) ([35ac278](https://github.com/supabase/supabase-swift/commit/35ac2784a71edbfcaf9bc3d9dab5f721c5ea2ba6))


### Bug Fixes

* manually percent encode query items to allow values with + sign ([#402](https://github.com/supabase/supabase-swift/issues/402)) ([a0ecb70](https://github.com/supabase/supabase-swift/commit/a0ecb70804f2a97aecb66499afad8ec3370815c6))
* **storage:** list method using wrong encoder ([#405](https://github.com/supabase/supabase-swift/issues/405)) ([f16989a](https://github.com/supabase/supabase-swift/commit/f16989a5b5bd5c6d769bfaff7e6ae076dc2d3ba5))

## [2.11.0](https://github.com/supabase/supabase-swift/compare/v2.10.1...v2.11.0) (2024-05-18)


### Features

* **auth:** add linkIdentity method ([#392](https://github.com/supabase/supabase-swift/issues/392)) ([7dfaa46](https://github.com/supabase/supabase-swift/commit/7dfaa466e305eb4e29fe7b8472c362bdeba6fa45))

## [2.10.1](https://github.com/supabase/supabase-swift/compare/v2.10.0...v2.10.1) (2024-05-15)


### Bug Fixes

* race condition when accessing SupabaseClient ([#386](https://github.com/supabase/supabase-swift/issues/386)) ([811e222](https://github.com/supabase/supabase-swift/commit/811e222dd486625eb9ba8937be139563bdc10d43))

## [2.10.0](https://github.com/supabase/supabase-swift/compare/v2.9.0...v2.10.0) (2024-05-14)


### Features

* expose Realtime options on SupabaseClient ([#377](https://github.com/supabase/supabase-swift/issues/377)) ([9cfafdb](https://github.com/supabase/supabase-swift/commit/9cfafdbb4a321dd523f33319bdd7e69e8d77a0ea))


### Bug Fixes

* **auth:** adds missing redirectTo query item to updateUser ([#380](https://github.com/supabase/supabase-swift/issues/380)) ([5d1a997](https://github.com/supabase/supabase-swift/commit/5d1a9970a2024a686a013873cb70eaae64ba4aa6))
* **auth:** header being overridden ([#379](https://github.com/supabase/supabase-swift/issues/379)) ([866a039](https://github.com/supabase/supabase-swift/commit/866a0395043030dd1574deb97360e2d47040efae))
* **postgrest:** update parameter of `is` filter to allow only `Bool` or `nil` ([#382](https://github.com/supabase/supabase-swift/issues/382)) ([4ba1c7a](https://github.com/supabase/supabase-swift/commit/4ba1c7a6c5a13c0a2b4b067aad5c747d7d621e93))
* **storage:** headers overridden ([#384](https://github.com/supabase/supabase-swift/issues/384)) ([b40c34a](https://github.com/supabase/supabase-swift/commit/b40c34a63fbbc0760d3f6e70ed7b69b08f9e70c8))

## [2.9.0](https://github.com/supabase/supabase-swift/compare/v2.8.5...v2.9.0) (2024-05-10)


### Features

* **auth:** Adds `currentSession` and `currentUser` properties ([#373](https://github.com/supabase/supabase-swift/issues/373)) ([4b01556](https://github.com/supabase/supabase-swift/commit/4b015565edbdb761ead8294ebb66d05da5a48b59))
* **functions:** invoke function with custom query params ([#376](https://github.com/supabase/supabase-swift/issues/376)) ([b4b9276](https://github.com/supabase/supabase-swift/commit/b4b9276512acccc673c36e35f06e69755e2a5dc7))
* improve HTTP Error ([#372](https://github.com/supabase/supabase-swift/issues/372)) ([ea25236](https://github.com/supabase/supabase-swift/commit/ea252365511773f93ef35bc2aa80c6098612de57))
* **storage:** copy objects between buckets ([69d05ef](https://github.com/supabase/supabase-swift/commit/69d05eff5dbb413b8b2a5ba565f7f5e19a6e0ab6))
* **storage:** move objects between buckets ([69d05ef](https://github.com/supabase/supabase-swift/commit/69d05eff5dbb413b8b2a5ba565f7f5e19a6e0ab6))


### Bug Fixes

* **auth:** sign out regardless of request success ([#375](https://github.com/supabase/supabase-swift/issues/375)) ([25178e2](https://github.com/supabase/supabase-swift/commit/25178e212dcc0dba4a712e9b7ec3ed93575efdf9))

## [2.8.5](https://github.com/supabase/supabase-swift/compare/v2.8.4...v2.8.5) (2024-05-08)


### Bug Fixes

* throw generic HTTPError ([#368](https://github.com/supabase/supabase-swift/issues/368)) ([782e940](https://github.com/supabase/supabase-swift/commit/782e940437a8a72d3243847c04fb37ef2f5fe7f0))

## [2.8.4](https://github.com/supabase/supabase-swift/compare/v2.8.3...v2.8.4) (2024-05-08)


### Bug Fixes

* **functions:** invoke with custom http method ([#367](https://github.com/supabase/supabase-swift/issues/367)) ([a283b68](https://github.com/supabase/supabase-swift/commit/a283b68cf49faa4c5bd2bb870e0840900fc7af35))

## [2.8.3](https://github.com/supabase/supabase-swift/compare/v2.8.2...v2.8.3) (2024-05-07)


### Bug Fixes

* **auth:** extract both query and fragment from URL ([#365](https://github.com/supabase/supabase-swift/issues/365)) ([e9c7c8c](https://github.com/supabase/supabase-swift/commit/e9c7c8c29002c9be1bf523deefc25e036d3c4a2a))

## [2.8.2](https://github.com/supabase/supabase-swift/compare/v2.8.1...v2.8.2) (2024-05-06)


### Bug Fixes

* **auth:** sign out should ignore 403s ([#359](https://github.com/supabase/supabase-swift/issues/359)) ([7c4e62b](https://github.com/supabase/supabase-swift/commit/7c4e62b3d0dcc6f307639abb3ef8ad792589fab1))

## [2.8.1](https://github.com/supabase/supabase-swift/compare/v2.8.0...v2.8.1) (2024-04-29)


### Bug Fixes

* **auth:** add missing is_anonymous field ([#355](https://github.com/supabase/supabase-swift/issues/355)) ([854dc42](https://github.com/supabase/supabase-swift/commit/854dc42659ed9c634271562b93169bb82e06890e))

## [2.8.0](https://github.com/supabase/supabase-swift/compare/v2.7.0...v2.8.0) (2024-04-22)


### Features

* **functions:** add experimental invoke with streamed responses ([#346](https://github.com/supabase/supabase-swift/issues/346)) ([2611b09](https://github.com/supabase/supabase-swift/commit/2611b091c871cf336de954f169240647efdf0339))
* **functions:** add support for specifying function region ([#347](https://github.com/supabase/supabase-swift/issues/347)) ([f470874](https://github.com/supabase/supabase-swift/commit/f470874f8dd8b0077a44e7243fc1d91993ae5fa9))
* **postgrest:** add geojson, explain, and new filters ([#343](https://github.com/supabase/supabase-swift/issues/343)) ([56c8117](https://github.com/supabase/supabase-swift/commit/56c81171d1e610e0286f7122522890d2b4001c2b))
* **realtime:** add closure based methods ([#345](https://github.com/supabase/supabase-swift/issues/345)) ([dfe09bc](https://github.com/supabase/supabase-swift/commit/dfe09bc804a06a06743884cbf56c5890409e9a87))


### Bug Fixes

* linux build ([#350](https://github.com/supabase/supabase-swift/issues/350)) ([e62ad89](https://github.com/supabase/supabase-swift/commit/e62ad891c80b037aada972f7c11e806f70c6aa50))
* **storage:** getSignedURLs method using wrong encoder ([#352](https://github.com/supabase/supabase-swift/issues/352)) ([d1b0672](https://github.com/supabase/supabase-swift/commit/d1b06728670ed2bb204693f69a81e584cd5c1a73))

## [2.7.0](https://github.com/supabase/supabase-swift/compare/v2.6.0...v2.7.0) (2024-04-16)


### Features

* **auth:** add `getLinkIdentityURL` ([#342](https://github.com/supabase/supabase-swift/issues/342)) ([202383d](https://github.com/supabase/supabase-swift/commit/202383d355dfaa9aab0e03680d9fedb9bdfc02d9))
* **auth:** add `signInWithOAuth` ([#299](https://github.com/supabase/supabase-swift/issues/299)) ([1290bcf](https://github.com/supabase/supabase-swift/commit/1290bcfb39fb156de0283888b47ba1532107f468))
* expose PostgrestClient methods directly in SupabaseClient ([#336](https://github.com/supabase/supabase-swift/issues/336)) ([aca50a5](https://github.com/supabase/supabase-swift/commit/aca50a557339f9872896b03988b737c56589fba7))


### Bug Fixes

* **postgrest:** race condition when executing request ([#327](https://github.com/supabase/supabase-swift/issues/327)) ([8063610](https://github.com/supabase/supabase-swift/commit/80636105e154a28f418f01f4af8b30987239b8f3))
* **postgrest:** race condition when setting fetchOptions and execute method call ([#325](https://github.com/supabase/supabase-swift/issues/325)) ([97d1900](https://github.com/supabase/supabase-swift/commit/97d1900d26272777f864803a0290573b39f47f00))

## [2.6.0](https://github.com/supabase-community/supabase-swift/compare/2.5.1...v2.6.0) (2024-04-03)


### Features

* **auth:** Add `signInAnonymously` ([#297](https://github.com/supabase-community/supabase-swift/issues/297)) ([4c25a3e](https://github.com/supabase-community/supabase-swift/commit/4c25a3eac392b319154ffb3d5d33a0686e3781a4))
