#### 1.11.2 (2019-01-24)

##### Chores

*  incrementing version number - v1.11.2 (757bff27)
*  incrementing version number - v1.11.1 (2104877c)
* **deps:**
  *  update node:8.15.0 docker digest to cb66110 (1719cd77)
  *  update dependency eslint-plugin-import to v2.15.0 (f7191eb9)
  *  update dependency eslint to v5.12.1 (d928c54d)
  *  update dependency @commitlint/cli to v7.3.2 (6ae2b972)
  *  update node.js to v8.15.0 (ac39fe90)
  *  update dependency eslint to v5.12.0 (f96ef7bb)
  *  update commitlint monorepo to v7.3.1 (50594118)
  *  update dependency smtp-server to v3.5.0 (00063708)
  *  update dependency husky to v1.3.1 (719995a4)
  *  update dependency eslint to v5.11.0 (#7151) (26f3bdbf)
  *  update dependency husky to v1.3.0 (eb606281)
  *  update dependency jsdom to v13.1.0 (60e9430b)
  *  update dependency eslint to v5.10.0 (#7084) (dae861da)
  *  update dependency husky to v1.2.1 (63f4b569)
  *  update node:8.14.0 docker digest to dd2381f (7449ae3e)
  *  update node.js to v8.14.0 (8a5a031d)
  *  update dependency lint-staged to v8.1.0 (dd7f8a14)
  *  update dependency husky to v1.2.0 (aee21628)
  *  update node:8.12.0 docker digest to 5dae8ea (0ef451dd)
  *  update dependency husky to v1.1.4 (95d6ab06)
  *  update dependency eslint to v5.9.0 (92441794)
  *  pin dependencies (b0483f21)
  *  update dependency eslint-config-airbnb-base to v13 (#6599) (64b9dabf)
  *  update node.js to v8.12.0 (fa3afbd2)
  *  update dependency husky to v1.1.3 (6cee5b8e)
  *  update dependency lint-staged to v8.0.4 (9d258668)
  *  update dependency lint-staged to v8.0.3 (aaa6fe9e)
  *  update dependency lint-staged to v8 (95d7a5fa)
  *  update dependency jsdom to v13 (52f141c9)
* **husky:**  setting up husky as recommended in docs (e8a3d929)

##### Documentation Changes

*  updated changelog for v1.11.1 (c04e192d)

##### New Features

*  new hook filter:user.logout (63061ffd)
*  explicit handling of SSO success and failure (059a4be2)
*  additional options for SSO plugins (2b9322e1)
*  get rid of disk access (ed5d2d6d)
*  support for one-click unsubscribe from email clients (#7203) (70a87d43)
*  added new hook `static:sockets.validateSession` (#7189) (0263b4da)
*  #7120 (f4ea2c43)
*  #7032 (0c1ac4d6)
*  small fixes (fef7e13c)
*  name topic controller (b9b9d8b2)
*  header (0cb9bba4)
*  more naming (ae0fe5e8)
*  give the rest of the middlewares names (f88db22c)
*  give names to more middlewares (fdfbcc6e)
*  give names to middlewares (53793e16)
*  change sortedSetsScore (d2c2d56f)
*  Allow getting logfile path from config (#7044) (f3e8e065)
*  remove uid:<uid>:ignored:cids (#7099) (263c9180)
*  cache category tag whitelist (78fa7340)
*  make user cards look less derpy (31bb2ae9)
*  added new middleware authenticateOrGuest (4fba1492)
*  closes #7070 (7ca62b83)
*  added README.md in languages folder (648964fa)
*  up composer (7eee8e1d)
*  allow array results (54c127d1)
*  #7023 (f581c052)
*  close #7002, console message if mismatched origins (89c025d1)
*  added changelog file to root of repo (e89b4fca)
*  enabling commitlint (c58a41ed)
*  allow disabling of GDPR features via ACP toggle, closes #6847 (4919e9ef)
* **deps:**  update bootstrap to v3.4.0 (#7106) (d1ea5d15)
* **email:**  don't escape html in notification bodies. (#7042) (d7c55bc3)

##### Bug Fixes

*  test (bc41848a)
*  #7235 (7064fd06)
*  use ACP config value for checking online status (ef0e7808)
*  log error to prevent headers already sent (a22a3a98)
*  #7289 timeago shorthand toggle fails on non-existant language (cee47f78)
*  #7276 improper request for client-noskin.css (5ee173c2)
*  #7274 incorrect handling of client script 404s (831d0795)
*  #7270 Flags graph label not translatable (8ceb35f5)
*  #7266 body does not contain skin class (f122fc44)
*  generate timeago codes from files (7524d3c3)
*  removal of timeago fallback middleware (#7259) (c831ff0d)
*  post queue notifs (ac655564)
*  added missing translation and error state for password change (51b5fb98)
*  #7236, header search stops working after header update (3859d417)
*  #7226, added placeholder styling for fa-nbb-none (87c2d108)
*  escape hook method (9328eeca)
*  #7216, hide taskbar on chat modal invocation on mobile (a70db885)
*  #7208 (428f587c)
*  #7054 (a662f118)
*  #7209 (b9833483)
*  missing notification (1a3838e1)
*  #7193, closes #7194 (7809ba28)
*  #https://github.com/barisusakli/nodebb-plugin-dbsearch/issues/49 (6f1fb4eb)
*  #7187 (28459d04)
*  #7176, FUOC on app.reskin() (954af0f0)
*  #7174 (9aa1aa68)
*  #7181 (0d409610)
*  #7142 (8da3b2a4)
*  #7179 (03299736)
*  #7169 Fixed logout being broken (b0eaa858)
*  #7167, composer and chat not closing on logout (629b3554)
*  shorter function (43e7cc0a)
*  #7162 (2da0a657)
*  uid filtering (72afc180)
*  dont crash if default cover is invalid (41fb5cca)
*  #7136 socket.disconnect() now called on invalid session (8e9de540)
*  RTL not respected when changed in user settings, related to #7146 (4873a339)
*  #7146 Better RTL handling on (de-)authentication (d81e0a5f)
*  #7118, invoking autoLocale middleware on logout (900f0a0b)
*  closes #6784 (#7137) (7fb29f42)
*  7100 (ab81cca7)
*  #7139 (3917022a)
*  #7116 (7e828404)
*  #7138 (29a85aec)
*  lint (b47f939b)
*  #7091, #7093 (69e0dbbf)
*  #7131 (d31684e8)
*  remove cache (b2a74b41)
*  loop (60390c01)
*  #7124 (4650a760)
*  unread badge (9f506268)
*  move the check to get methods (99e0895e)
*  #7115 (989879a6)
*  #6979 (29b63ae7)
*  upgrade script key (0eef3e1c)
*  remove log (00afc5b3)
*  #7108 (81697390)
*  dont save data for non-positive uids (62f01a83)
*  #7103 (f103390a)
*  dont update cid:<cid>:tids:votes if topic is pinned (2f57a4b9)
*  #7102 (d117df77)
*  #7102 (85a07e99)
*  don't explode if there is no css el (74d0e88d)
*  db info page (26ccd8f6)
*  logAttempt conditional (a6c8e0ab)
*  #7087, server-side protection against guest blocks (33d4956b)
*  don't crash in flags.validate if user blocked target (81aa3a0b)
*  dont send empty strings (555c092f)
*  #7085 (fe0f95a2)
*  #7086 (e55fb437)
*  wrong variable #7085 (71163421)
*  admins&mods when there are mutliple lines of users (de437e36)
*  refreshing settings page on save if language changed (ed46c5e2)
*  not calling authenticate middleware on resource direct access routes (eeaee8cc)
*  #7038, autoLocale logic not playing nicely with no-refresh auths (#7059) (5f3d1c76)
*  #7074 (2604cf63)
*  #7071 buildSkinAsset won't rebuild continuously (a07d9898)
*  #7063, logout code should do hard page nav to / or data.next (6df5668e)
*  #7061 (eab297bd)
*  skin not changing after login or logout, #7038 (28a1fa78)
*  #7040 (a63ddbe2)
*  #7041 (ec0c50d4)
*  #7043 (8d7c3897)
*  add missing render function (cb7c2d8c)
*  #7033 (8808a033)
*  #7037 (b86f1556)
*  #6991, add timeout for version Github request (43c3bb02)
*  #7030 (58d4376f)
*  added admin/manage/uploads to tx config (7357926f)
*  #7013, add cache buster to js-enabled.css (f6b92c1d)
*  removal of scroll anchoring code in favour of browser handling (98c14e0e)
*  custom navigation item not showing groups (d9452bf3)
*  flags detail page crash if reporter blocks author (d027207f)
*  #6922, skin assets not including plugin LESS files (a5022ce4)
*  #6921, allow square brackets in usernames (da10ca08)
*  interstitial redirects failing if done via ajaxify (3c8939a8)
*  username trim on login, closes #6894 (157bea69)
* **deps:**
  *  update dependency nodebb-widget-essentials to v4.0.13 (#7293) (22cbcc3e)
  *  update dependency mongodb to v3.1.13 (1aadbc3c)
  *  update dependency postcss to v7.0.14 (4d64de76)
  *  #7271, updating autoprefixer to latest version (a7af0198)
  *  #7270 (b48f1b4d)
  *  update dependency sharp to v0.21.3 (#7267) (8a64667f)
  *  theme upgrades for #7266 (5607261c)
  *  update dependency mongodb to v3.1.12 (eeab7d20)
  *  update dependency mongodb to v3.1.11 (#7252) (b5f188b6)
  *  update dependency validator to v10.11.0 (77dc8fc7)
  *  update dependency nodebb-plugin-composer-default to v6.1.21 (2fbb2614)
  *  update dependency postcss to v7.0.12 (f1842295)
  *  update dependency postcss to v7.0.11 (57bec2fb)
  *  update dependency sharp to v0.21.2 (8f3c4b09)
  *  update dependency postcss to v7.0.10 (82475fe5)
  *  update dependency postcss to v7.0.9 (f171c169)
  *  update dependency nodebb-theme-vanilla to v10.1.15 (ea059e89)
  *  update dependency nodebb-theme-persona to v9.1.10 (96482569)
  *  update dependency nodebb-theme-persona to v9.1.9 (bbe05043)
  *  update dependency nodebb-theme-vanilla to v10.1.14 (6cc5dbc8)
  *  update dependency nodebb-theme-persona to v9.1.8 (e5443690)
  *  update dependency pg-cursor to v2 (29acad42)
  *  update dependency diff to v4 (#7198) (84e228bb)
  *  update dependency nodebb-plugin-mentions to v2.5.2 (#7199) (0a647316)
  *  update dependency nodebb-plugin-markdown to v8.8.7 (90b4d40e)
  *  update dependency rimraf to v2.6.3 (f4cc3122)
  *  update dependency spider-detector to v1.0.19 (#7177) (0faba325)
  *  update dependency nodemailer to v5 (4993b03c)
  *  update dependency json-2-csv to v3 (80cee665)
  *  update dependency nodebb-plugin-composer-default to v6.1.20 (07bf0b98)
  *  update dependency nodebb-theme-persona to v9.1.7 (#7161) (c68d4ae8)
  *  update dependency nodebb-plugin-composer-default to v6.1.19 (#7159) (07af46ea)
  *  update dependency nodebb-plugin-composer-default to v6.1.18 (#7158) (584b45fc)
  *  update dependency validator to v10.10.0 (#7152) (8003bed8)
  *  update dependency nodebb-plugin-mentions to v2.5.0 (792dce14)
  *  update dependency nodebb-theme-persona to v9.1.6 (#7141) (325b0293)
  *  update dependency nodebb-plugin-dbsearch to v3.0.4 (ddd07c1a)
  *  update dependency nodebb-widget-essentials to v4.0.12 (#7133) (f614a44d)
  *  update dependency nodebb-plugin-mentions to v2.4.0 (9ab31d7e)
  *  update dependency postcss to v7.0.7 (7ef8c3fd)
  *  update dependency sharp to v0.21.1 (#7082) (bf75f3e3)
  *  update dependency nodebb-theme-vanilla to v10.1.13 (#7114) (fc5598b9)
  *  update dependency nodebb-theme-slick to v1.2.19 (#7113) (56ad43aa)
  *  update dependency nodebb-theme-persona to v9.1.5 (#7112) (953f8fe5)
  *  update dependency nodebb-plugin-composer-default to v6.1.17 (3bcfd7fc)
  *  update dependency nodebb-theme-persona to v9.1.4 (b6ad5fd4)
  *  update dependency nodebb-plugin-markdown to v8.8.6 (#7079) (46fb365d)
  *  update dependency nodebb-theme-persona to v9.1.3 (#7075) (d2aea57a)
  *  update dependency nodebb-theme-persona to v9.1.2 (42e792ab)
  *  update dependency nodebb-theme-persona to v9.1.1 (#7069) (bdb33056)
  *  update dependency postcss to v7.0.6 (6b5428c5)
  *  update dependency nodebb-plugin-composer-default to v6.1.14 (#7058) (e48ed6e0)
  *  update dependency nodebb-plugin-composer-default to v6.1.13 (#7057) (ada1d6d0)
  *  update dependency nodebb-plugin-composer-default to v6.1.12 (#7056) (9f9f72da)
  *  update dependency nodebb-plugin-composer-default to v6.1.11 (#7055) (89acb896)
  *  update dependency nodebb-theme-slick to v1.2.18 (#7049) (b6cb77c1)
  *  update dependency nodebb-theme-slick to v1.2.17 (#7048) (7334c45b)
  *  update dependency nodebb-theme-slick to v1.2.16 (#7047) (1cb1af0c)
  *  update dependency connect-mongo to v2.0.3 (#7046) (d0d0c7f0)
  *  update dependency nodebb-plugin-dbsearch to v3.0.3 (#7035) (adb1b5f3)
  *  update dependency lru-cache to v4.1.5 (#7031) (887582eb)
  *  update dependency socket.io to v2.2.0 (b9d49867)
  *  update dependency socket.io-client to v2.2.0 (824bd541)
  *  update dependency nodebb-plugin-dbsearch to v3.0.2 (#7028) (11f1b409)
  *  update dependency nodebb-plugin-dbsearch to v3.0.1 (#7027) (e71f443c)
  *  update dependency nodebb-theme-vanilla to v10.1.12 (cf928f44)
  *  update dependency nodebb-theme-persona to v9.1.0 (179be9ed)
  *  update dependency nodebb-theme-persona to v9.0.63 (#7019) (68ae3eb6)
  *  update dependency nodebb-plugin-markdown to v8.8.5 (d3ab7d1b)
  *  update dependency nodebb-theme-persona to v9.0.60 (#6984) (cbd50a80)
  *  update dependency nodebb-theme-vanilla to v10.1.10 (#6982) (4c769487)
  *  update dependency nodebb-theme-slick to v1.2.15 (#6981) (acaf1a05)
  *  update dependency nodebb-theme-persona to v9.0.59 (#6980) (5863bb2c)
  *  update dependency lru-cache to v4.1.4 (#6977) (375ab769)
  *  update dependency connect-mongo to v2.0.2 (#6975) (e1597b83)
  *  update dependency nodebb-plugin-markdown to v8.8.4 (84d1013d)
  *  update dependency nodebb-plugin-composer-default to v6.1.8 (fee7e336)
  *  update dependency nodebb-plugin-markdown to v8.8.3 (b182a195)
  *  update dependency nodebb-plugin-composer-default to v6.1.7 (#6966) (1101f327)
  *  update dependency nodebb-theme-persona to v9.0.58 (#6964) (6ade156b)
  *  update dependency mongodb to v3.1.10 (#6962) (662215fa)
  *  update dependency nodebb-theme-persona to v9.0.57 (#6956) (1bf1a439)
  *  update dependency nodebb-theme-persona to v9.0.55 (#6955) (e06683f7)
  *  update dependency nodebb-plugin-composer-default to v6.1.6 (c51ceaf0)
  *  update dependency nodebb-theme-persona to v9.0.54 (bb940b01)
  *  update dependency nodebb-plugin-mentions to v2.2.12 (#6936) (e12a803b)
  *  update dependency nodebb-theme-vanilla to v10.1.9 (#6935) (b480c321)
  *  update dependency nodebb-theme-slick to v1.2.14 (#6934) (9cdd5316)
  *  update dependency nodebb-theme-persona to v9.0.53 (#6933) (9ee1c2f8)
  *  update dependency nodebb-plugin-dbsearch to v2.0.23 (#6931) (dba1db9c)
  *  update dependency jsesc to v2.5.2 (511b4edc)
  *  update dependency validator to v10.9.0 (032caafa)
  *  update dependency spdx-license-list to v5 (a639b6b8)
  *  update dependency nodebb-theme-vanilla to v10.1.8 (eb0a322d)
  *  update dependency nodebb-theme-persona to v9.0.52 (6566a0cb)
  *  update dependency nodebb-plugin-dbsearch to v2.0.22 (#6916) (7808e58c)
  *  update dependency mongodb to v3.1.9 (#6914) (9a9f2af9)
  *  update dependency nodebb-theme-persona to v9.0.51 (e2274fe0)
  *  update dependency nodebb-theme-slick to v1.2.13 (3005428d)
  *  update dependency nodebb-theme-persona to v9.0.50 (#6902) (22140a20)
  *  update dependency nodebb-plugin-markdown to v8.8.2 (0b4c9a80)
  *  update dependency nodebb-theme-vanilla to v10.1.7 (3150a2fc)
  *  update dependency nodebb-theme-slick to v1.2.12 (#6881) (9bcda7f7)
  *  update dependency nodebb-theme-persona to v9.0.49 (#6880) (e0dc00da)
  *  update dependency nodebb-theme-persona to v9.0.48 (2b6f5eec)
* **i18n:**  pushed notifications source to tx, pulled fallbacks (8dd8370b)
* **uploads:**  ugly filenames on uploaded asset downloading (f96208a0)
* **acp:**
  *  small UI fixes for ACP privileges category selector (#6946) (57b39d5b)
  *  hard-to-discover dropdown selector in ACP (b3f96d28)
* **l10n:**  some translations (34cbd1fc)

##### Other Changes

* //github.com/NodeBB/nodebb-theme-persona/issues/363 (702be3f6)
* //github.com/NodeBB/NodeBB/issues/6433 (7e00d6b9)
*  #6408 (f0f30041)
*  #6425 (fbf52407)
* //github.com/NodeBB/NodeBB/issues/6073 (5da24b41)
*  #5862, setting chat list height even if no message list is present (bc9a1250)
* //github.com/Schamper/nodebb-plugin-poll/issues/86 (c0f39032)

##### Refactors

*  use loash when possible (#7230) (e1ca2d81)

##### Code Style Changes

*  lint fix (fbe6ccd7)
* **eslint:**
  *  match operator-linebreak preferences (ba619c7e)
  *  newlines in public/src as well (f7bd398e)
  *  enforcing newline on chained calls (95cc27f1)

#### 1.11.1 (2018-12-14)

##### Chores

*  incrementing version number - v1.11.1 (2104877c)
* **deps:**
  *  update dependency husky to v1.2.1 (63f4b569)
  *  update node:8.14.0 docker digest to dd2381f (7449ae3e)
  *  update node.js to v8.14.0 (8a5a031d)

##### New Features

*  Allow getting logfile path from config (#7044) (f3e8e065)
*  remove uid:<uid>:ignored:cids (#7099) (263c9180)
*  cache category tag whitelist (78fa7340)
*  make user cards look less derpy (31bb2ae9)
*  added new middleware authenticateOrGuest (4fba1492)
*  closes #7070 (7ca62b83)
*  added README.md in languages folder (648964fa)
*  up composer (7eee8e1d)
*  allow array results (54c127d1)
*  #7023 (f581c052)
*  close #7002, console message if mismatched origins (89c025d1)
*  added changelog file to root of repo (e89b4fca)
* **email:**  don't escape html in notification bodies. (#7042) (d7c55bc3)

##### Bug Fixes

*  #7108 (81697390)
*  dont save data for non-positive uids (62f01a83)
*  #7103 (f103390a)
*  dont update cid:<cid>:tids:votes if topic is pinned (2f57a4b9)
*  #7102 (d117df77)
*  #7102 (85a07e99)
*  don't explode if there is no css el (74d0e88d)
*  db info page (26ccd8f6)
*  logAttempt conditional (a6c8e0ab)
*  #7087, server-side protection against guest blocks (33d4956b)
*  don't crash in flags.validate if user blocked target (81aa3a0b)
*  dont send empty strings (555c092f)
*  #7085 (fe0f95a2)
*  #7086 (e55fb437)
*  wrong variable #7085 (71163421)
*  admins&mods when there are mutliple lines of users (de437e36)
*  refreshing settings page on save if language changed (ed46c5e2)
*  not calling authenticate middleware on resource direct access routes (eeaee8cc)
*  #7038, autoLocale logic not playing nicely with no-refresh auths (#7059) (5f3d1c76)
*  #7074 (2604cf63)
*  #7071 buildSkinAsset won't rebuild continuously (a07d9898)
*  #7063, logout code should do hard page nav to / or data.next (6df5668e)
*  #7061 (eab297bd)
*  skin not changing after login or logout, #7038 (28a1fa78)
*  #7040 (a63ddbe2)
*  #7041 (ec0c50d4)
*  #7043 (8d7c3897)
*  add missing render function (cb7c2d8c)
*  #7033 (8808a033)
*  #7037 (b86f1556)
*  #6991, add timeout for version Github request (43c3bb02)
*  #7030 (58d4376f)
* **deps:**
  *  update dependency nodebb-plugin-composer-default to v6.1.17 (3bcfd7fc)
  *  update dependency nodebb-theme-persona to v9.1.4 (b6ad5fd4)
  *  update dependency nodebb-plugin-markdown to v8.8.6 (#7079) (46fb365d)
  *  update dependency nodebb-theme-persona to v9.1.3 (#7075) (d2aea57a)
  *  update dependency nodebb-theme-persona to v9.1.2 (42e792ab)
  *  update dependency nodebb-theme-persona to v9.1.1 (#7069) (bdb33056)
  *  update dependency postcss to v7.0.6 (6b5428c5)
  *  update dependency nodebb-plugin-composer-default to v6.1.14 (#7058) (e48ed6e0)
  *  update dependency nodebb-plugin-composer-default to v6.1.13 (#7057) (ada1d6d0)
  *  update dependency nodebb-plugin-composer-default to v6.1.12 (#7056) (9f9f72da)
  *  update dependency nodebb-plugin-composer-default to v6.1.11 (#7055) (89acb896)
  *  update dependency nodebb-theme-slick to v1.2.18 (#7049) (b6cb77c1)
  *  update dependency nodebb-theme-slick to v1.2.17 (#7048) (7334c45b)
  *  update dependency nodebb-theme-slick to v1.2.16 (#7047) (1cb1af0c)
  *  update dependency connect-mongo to v2.0.3 (#7046) (d0d0c7f0)
  *  update dependency nodebb-plugin-dbsearch to v3.0.3 (#7035) (adb1b5f3)
  *  update dependency lru-cache to v4.1.5 (#7031) (887582eb)
  *  update dependency socket.io to v2.2.0 (b9d49867)
  *  update dependency socket.io-client to v2.2.0 (824bd541)
  *  update dependency nodebb-plugin-dbsearch to v3.0.2 (#7028) (11f1b409)
  *  update dependency nodebb-plugin-dbsearch to v3.0.1 (#7027) (e71f443c)
* **i18n:**  pushed notifications source to tx, pulled fallbacks (8dd8370b)

##### Code Style Changes

* **eslint:**  match operator-linebreak preferences (ba619c7e)

### 1.11.0 (2018-11-28)

##### Chores

* **deps:**
  *  update dependency lint-staged to v8.1.0 (dd7f8a14)
  *  update dependency husky to v1.2.0 (aee21628)
  *  update node:8.12.0 docker digest to 5dae8ea (0ef451dd)
  *  update dependency husky to v1.1.4 (95d6ab06)
  *  update dependency eslint to v5.9.0 (92441794)
  *  pin dependencies (b0483f21)
  *  update dependency eslint-config-airbnb-base to v13 (#6599) (64b9dabf)
  *  update node.js to v8.12.0 (fa3afbd2)
  *  update dependency husky to v1.1.3 (6cee5b8e)
  *  update dependency lint-staged to v8.0.4 (9d258668)
  *  update dependency lint-staged to v8.0.3 (aaa6fe9e)
  *  update dependency lint-staged to v8 (95d7a5fa)
  *  update dependency jsdom to v13 (52f141c9)
* **husky:**  setting up husky as recommended in docs (e8a3d929)

##### New Features

*  enabling commitlint (c58a41ed)
*  allow disabling of GDPR features via ACP toggle, closes #6847 (4919e9ef)

##### Bug Fixes

* **deps:**
  *  update dependency nodebb-theme-vanilla to v10.1.12 (cf928f44)
  *  update dependency nodebb-theme-persona to v9.1.0 (179be9ed)
  *  update dependency nodebb-theme-persona to v9.0.63 (#7019) (68ae3eb6)
  *  update dependency nodebb-plugin-markdown to v8.8.5 (d3ab7d1b)
  *  update dependency nodebb-theme-persona to v9.0.60 (#6984) (cbd50a80)
  *  update dependency nodebb-theme-vanilla to v10.1.10 (#6982) (4c769487)
  *  update dependency nodebb-theme-slick to v1.2.15 (#6981) (acaf1a05)
  *  update dependency nodebb-theme-persona to v9.0.59 (#6980) (5863bb2c)
  *  update dependency lru-cache to v4.1.4 (#6977) (375ab769)
  *  update dependency connect-mongo to v2.0.2 (#6975) (e1597b83)
  *  update dependency nodebb-plugin-markdown to v8.8.4 (84d1013d)
  *  update dependency nodebb-plugin-composer-default to v6.1.8 (fee7e336)
  *  update dependency nodebb-plugin-markdown to v8.8.3 (b182a195)
  *  update dependency nodebb-plugin-composer-default to v6.1.7 (#6966) (1101f327)
  *  update dependency nodebb-theme-persona to v9.0.58 (#6964) (6ade156b)
  *  update dependency mongodb to v3.1.10 (#6962) (662215fa)
  *  update dependency nodebb-theme-persona to v9.0.57 (#6956) (1bf1a439)
  *  update dependency nodebb-theme-persona to v9.0.55 (#6955) (e06683f7)
  *  update dependency nodebb-plugin-composer-default to v6.1.6 (c51ceaf0)
  *  update dependency nodebb-theme-persona to v9.0.54 (bb940b01)
  *  update dependency nodebb-plugin-mentions to v2.2.12 (#6936) (e12a803b)
  *  update dependency nodebb-theme-vanilla to v10.1.9 (#6935) (b480c321)
  *  update dependency nodebb-theme-slick to v1.2.14 (#6934) (9cdd5316)
  *  update dependency nodebb-theme-persona to v9.0.53 (#6933) (9ee1c2f8)
  *  update dependency nodebb-plugin-dbsearch to v2.0.23 (#6931) (dba1db9c)
  *  update dependency jsesc to v2.5.2 (511b4edc)
  *  update dependency validator to v10.9.0 (032caafa)
  *  update dependency spdx-license-list to v5 (a639b6b8)
  *  update dependency nodebb-theme-vanilla to v10.1.8 (eb0a322d)
  *  update dependency nodebb-theme-persona to v9.0.52 (6566a0cb)
  *  update dependency nodebb-plugin-dbsearch to v2.0.22 (#6916) (7808e58c)
  *  update dependency mongodb to v3.1.9 (#6914) (9a9f2af9)
  *  update dependency nodebb-theme-persona to v9.0.51 (e2274fe0)
  *  update dependency nodebb-theme-slick to v1.2.13 (3005428d)
  *  update dependency nodebb-theme-persona to v9.0.50 (#6902) (22140a20)
  *  update dependency nodebb-plugin-markdown to v8.8.2 (0b4c9a80)
  *  update dependency nodebb-theme-vanilla to v10.1.7 (3150a2fc)
  *  update dependency nodebb-theme-slick to v1.2.12 (#6881) (9bcda7f7)
  *  update dependency nodebb-theme-persona to v9.0.49 (#6880) (e0dc00da)
  *  update dependency nodebb-theme-persona to v9.0.48 (2b6f5eec)
*  added admin/manage/uploads to tx config (7357926f)
*  #7013, add cache buster to js-enabled.css (f6b92c1d)
*  removal of scroll anchoring code in favour of browser handling (98c14e0e)
*  custom navigation item not showing groups (d9452bf3)
*  flags detail page crash if reporter blocks author (d027207f)
*  #6922, skin assets not including plugin LESS files (a5022ce4)
*  #6921, allow square brackets in usernames (da10ca08)
*  interstitial redirects failing if done via ajaxify (3c8939a8)
*  username trim on login, closes #6894 (157bea69)
* **uploads:**  ugly filenames on uploaded asset downloading (f96208a0)
* **acp:**
  *  small UI fixes for ACP privileges category selector (#6946) (57b39d5b)
  *  hard-to-discover dropdown selector in ACP (b3f96d28)
* **l10n:**  some translations (34cbd1fc)

##### Code Style Changes

* **eslint:**
  *  newlines in public/src as well (f7bd398e)
  *  enforcing newline on chained calls (95cc27f1)

