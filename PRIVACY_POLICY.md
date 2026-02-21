# プライバシーポリシー / Privacy Policy

最終更新日: 2025年2月11日  
Last Updated: February 11, 2025

---

## 日本語

### 1. はじめに
ForC（以下「本アプリ」）は、ユーザーのプライバシーを尊重し、個人情報の保護に努めます。本ポリシーでは、本アプリが収集する情報とその利用目的について説明します。

### 2. 収集する情報
#### 2.1 デバイストークン
本アプリは、トリガーを指定時刻に発火させるため、Firebase Cloud Messaging（FCM）のデバイストークンを取得します。このトークンは個人を特定できない技術的な識別子であり、サイレントプッシュ通知の送信にのみ使用されます。

#### 2.2 匿名認証ID
本アプリは、Firebase Anonymous Authenticationにより匿名のユーザーIDを生成します。このIDは個人を特定できず、デバイストークンとトリガーの発火時刻の管理にのみ使用されます。

#### 2.3 トリガーの発火時刻
サーバーには、トリガーの発火時刻（時・分）のみが保存されます。トリガーの条件内容（天気、ヘルスケア、サイコロなど）、アクション内容（カレンダーイベントのタイトル・メモなど）は一切サーバーに送信・保存されません。これらの情報はすべてお使いのデバイス内にのみ保存されます。

### 3. 収集しない情報
本アプリは以下の情報を収集しません。

- 氏名、メールアドレス、電話番号などの個人情報
- トリガーの条件内容（天気条件、ヘルスケア条件、サイコロ条件、位置条件の詳細）
- トリガーのアクション内容（カレンダーイベントのタイトル、メモ、カレンダーID）
- カレンダーの内容
- ヘルスケアデータ
- 正確な位置情報（天気取得のために一時的に使用しますが、サーバーには送信しません）

### 4. データの保存場所
- デバイス内: トリガーの全データ（条件、アクション、実行履歴）はお使いのデバイス内にのみ保存されます。
- サーバー（Firebase）: 匿名ユーザーID、デバイストークン、トリガーの発火時刻のみが保存されます。

### 5. 第三者サービス
本アプリは以下の第三者サービスを利用しています。

- Firebase（Google）: 匿名認証、プッシュ通知配信、発火時刻の管理
- RevenueCat: サブスクリプション管理
- Apple WeatherKit / OpenWeatherMap: 天気情報の取得

これらのサービスにはそれぞれ独自のプライバシーポリシーが適用されます。

### 6. データの削除
アプリの設定画面から「データをリセット」を実行すると、デバイス内の全データが削除されます。アプリをアンインストールすると、デバイス内のデータおよびサーバー上のトークン情報も無効化されます。

### 7. お問い合わせ
プライバシーに関するお問い合わせは、以下のメールアドレスまでご連絡ください。

namimon.mahjong@gmail.com

---

## English

### 1. Introduction
ForC ("the App") respects your privacy and is committed to protecting your personal information. This policy explains what information the App collects and how it is used.

### 2. Information We Collect
#### 2.1 Device Token
The App obtains a Firebase Cloud Messaging (FCM) device token to fire triggers at scheduled times. This token is a technical identifier that cannot identify you personally and is used solely for sending silent push notifications.

#### 2.2 Anonymous Authentication ID
The App generates an anonymous user ID via Firebase Anonymous Authentication. This ID cannot identify you personally and is used only to manage device tokens and trigger firing times.

#### 2.3 Trigger Firing Times
Only trigger firing times (hour and minute) are stored on the server. Trigger condition details (weather, health, dice, etc.) and action details (calendar event titles, notes, etc.) are never sent to or stored on the server. All such information is stored exclusively on your device.

### 3. Information We Do Not Collect
The App does not collect:

- Personal information such as name, email address, or phone number
- Trigger condition details (weather, health, dice, or location condition specifics)
- Trigger action details (calendar event titles, notes, calendar IDs)
- Calendar contents
- Health data
- Precise location (used temporarily for weather retrieval but never sent to the server)

### 4. Data Storage
- On device: All trigger data (conditions, actions, execution history) is stored only on your device.
- Server (Firebase): Only the anonymous user ID, device token, and trigger firing times are stored.

### 5. Third-Party Services
The App uses the following third-party services:

- Firebase (Google): Anonymous authentication, push notification delivery, firing time management
- RevenueCat: Subscription management
- Apple WeatherKit / OpenWeatherMap: Weather data retrieval

Each of these services has its own privacy policy.

### 6. Data Deletion
You can delete all on-device data by using "Reset Data" in the Settings screen. Uninstalling the app will remove on-device data and invalidate the server-side token information.

### 7. Contact
For privacy-related inquiries, please contact us at:

namimon.mahjong@gmail.com