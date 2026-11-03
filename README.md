# TodoDaily

毎日のTodoや習慣を、日付が横に続くタイムラインで記録するAndroidアプリです。

## 概要

TodoDailyは、項目ごとの日々の状態を一覧で振り返るための記録アプリです。
運動、読書、家事など、記録したい項目と記録形式を自分で設定できます。

このリポジトリでは、インストール用APKと使い方を公開しています。

## 主な機能

- 日付を左右にスクロールして、過去や未来の記録を表示
- 2本指で拡大・縮小し、約7〜90日分の表示幅を調整
- 今日への移動、日付指定による移動、土日・日本の祝日の表示
- 項目の追加・編集・上下の並べ替え・非表示
- 削除済み項目の復元、確認付きの完全削除
- ON / OFF、シグナル、棒グラフ、GOOD / BAD、カスタム状態から記録形式を選択
- シグナル・棒グラフの段数や色、カスタム状態の文字や絵文字を設定
- タップまたは長押しによる記録の切り替え
- 記録の自動保存、JSONファイルへのバックアップと復元
- 端末設定に合わせたライト／ダーク表示

## ダウンロード・インストール

バージョン：1.0

[TodoDaily-v1.0.apkをダウンロード](https://github.com/otokame/TodoDaily/releases/download/v1.0/TodoDaily-v1.0.apk)

1. Android端末へAPKをダウンロードします。
2. ダウンロードしたAPKを開きます。
3. Androidから求められた場合は、使用したブラウザやファイルアプリに「この提供元のアプリを許可」などのインストール許可を設定します。項目名は端末により異なります。
4. インストール後、アプリ一覧から「TodoDaily」を起動します。

インストール許可は、インストール後に元へ戻せます。Google Play経由の配布ではありません。

以前のテスト版など、異なる署名のTodoDailyが入っている端末では上書きできません。先に既存版の「バックアップ」からJSONを書き出し、安全な場所に保存してください。既存版をアンインストールすると端末内の記録は消えます。新しい版をインストールした後、バックアップを復元できます。

## 使い方

初回は操作例として「朝のストレッチ」「水を飲む」「今日の調子」が用意されます。編集・削除して使えます。

1. 右下の「項目を追加」から、項目名と記録タイプを設定して保存します。
2. 項目と日付が交差するマスをタップすると、状態が順に切り替わります。設定で「長押しで切替」を選んだ場合は長押ししてください。
3. 日付のタイムラインを左右にドラッグして移動します。2本指で拡大・縮小できます。
4. 「今日へ移動」ボタンで今日の位置に戻れます。画面上部の日付から日付を指定して移動することもできます。
5. メニューの「項目の管理」で、項目の編集、上下ボタンによる並べ替え、非表示、削除・復元を行えます。
6. メニューの「設定」で記録操作を変更し、標準の14日表示に戻せます。

表示幅が狭くマスを安全に操作できないときは、まず対象日を拡大表示します。その時点では記録は変更されません。

## バックアップと復元

メニューの「バックアップ」を開きます。

- **書き出し**：項目、日別記録、操作設定、表示幅の設定を1つのJSONファイルに保存します。Androidのファイル選択画面で保存先を選んでください。
- **復元**：「ファイルを選択」からバックアップを開き、検証後の件数を確認して「置き換える」を押します。

**復元は現在のデータをすべて置き換えます。データの追加・統合ではありません。復元前に現在のデータも書き出してください。**

バックアップには非表示・削除済み項目や日別記録も含まれます。JSONは暗号化されていないため、保存場所や共有先にご注意ください。

## 注意事項

- 記録は端末内に保存されます。アンインストール、アプリのデータ削除、端末の故障に備えて、定期的にバックアップしてください。
- 非表示や通常の削除では記録を残しますが、「完全削除」した項目とその記録はアプリ内から元に戻せません。
- 日本の祝日はアプリ内で計算します。対象範囲は1948〜2150年で、範囲外は祝日情報を表示しません。祝日制度の変更にはアプリの更新が必要です。
- 記録タイプ、段数、カスタム状態を変更すると、新しい設定に合わない過去の記録が削除されることがあります。変更前にバックアップしてください。
- アプリの画面表示は日本語です。

## 権限とデータの取り扱い

- アプリ専用アカウントや独自サーバーへの登録は不要です。
- 項目、記録、設定は端末内に保存します。
- バックアップの保存先・読み込み元は利用者がAndroid標準のファイル選択画面で指定します。クラウドストレージを選ぶ場合、そのサービスの設定が適用されます。
- Androidの設定により、端末内の保存データがOSのバックアップや端末移行の対象になる場合があります。

## 動作環境

- Android 8.0（API 26）以上

## ライセンス

このソフトウェアはフリーソフトとして提供されます。個人・法人を問わず無償で使用できますが、著作権は作者に帰属します。再配布・改変・商用利用を希望される場合は、事前にご相談ください。

アプリに含まれる第三者製ライブラリの権利は、それぞれの権利者に帰属します。

## 免責事項

本ソフトウェアは無保証で提供され、明示的または黙示的な一切の保証を行いません。本ソフトウェアの使用または使用不能から生じるいかなる損害についても、作者は一切の責任を負いません。ご利用はすべてご自身の責任において行ってください。

---

# TodoDaily — Daily Activity and Habit Tracker

## Overview

Record daily tasks and habits on a horizontally scrolling date timeline. Create your own items for activities such as exercise, reading, or housework, and choose how to record each one.

This repository distributes an installable APK and usage instructions. The app interface is in Japanese.

## Main Features

- Scroll through dates across month and year boundaries
- Pinch to adjust the view to approximately 7–90 days
- Jump to today or a selected date; highlight weekends and Japanese holidays
- Add, edit, reorder, hide, delete, and restore items
- Choose ON / OFF, signal levels, bars, GOOD / BAD, or custom text and emoji states
- Configure levels and colors for signal and bar records
- Switch states by tapping or long-pressing
- Automatic local saving; JSON backup and restore
- Follow the device’s light or dark theme

## Download and Installation

Version: 1.0

[Download TodoDaily-v1.0.apk](https://github.com/otokame/TodoDaily/releases/download/v1.0/TodoDaily-v1.0.apk)

Download and open the APK on your Android device. If prompted, allow your browser or file manager to install apps from this source. Install the APK and launch **TodoDaily**. You can turn that installation permission off afterward. This is a direct distribution outside Google Play.

If a previous test build has a different signing certificate, Android will not install this APK over it. Export a JSON backup from the existing app before uninstalling it. Uninstalling removes local records; restore the exported backup after installing the new version.

## How to Use

On first launch, three example items are provided: morning stretching, drinking water, and daily condition. You can edit or delete them.

1. Select **項目を追加** (Add item) at the bottom right, enter a name, select a record type, and save.
2. Tap the cell for an item and date to cycle through its states. If long-press mode is selected, long-press instead.
3. Drag the date timeline horizontally and pinch with two fingers to zoom.
4. Use **今日へ移動** (Jump to today), or select the date at the top to jump to a specific date.
5. Open **項目の管理** (Manage items) from the menu to edit, reorder with up/down buttons, hide, delete, or restore items.
6. Open **設定** (Settings) to change the recording gesture or restore the standard 14-day view.

When cells are too narrow for safe input, the app first zooms in on the selected date without changing the record.

## Backup and Restore

Open **バックアップ** (Backup) from the menu.

- **書き出し** (Export) saves items, daily records, gesture settings, and zoom settings in one JSON file. Choose the destination with Android’s file picker.
- **ファイルを選択** (Select file) reads a backup. Review the validated item and record counts, then select **置き換える** (Replace).

**Restoring replaces all current data; it does not merge records. Export your current data before restoring a backup.**

Backups include hidden and deleted items and daily records. JSON backups are not encrypted; choose storage locations and recipients carefully.

## Notes and Data

- Records are stored locally. Export backups regularly to protect against uninstallation, app data deletion, or device failure.
- Hiding or ordinary deletion retains records. Permanently deleted items and their records cannot be restored within the app.
- Japanese holidays are calculated for 1948–2150. Dates outside that range have no holiday information. Holiday rule changes require an app update.
- Changing a record type, level count, or custom states can remove earlier records that are incompatible with the new settings. Export a backup before making such changes.
- No app account or registration with an app server is required.
- Backup locations are selected through Android’s standard file picker. If you select a cloud provider, that service’s settings apply.
- Android may include local data in OS backups or device transfers, depending on system settings.

## System Requirements

Android 8.0 (API 26) or later.

## License

This software is provided as freeware and may be used free of charge by individuals and organizations. Copyright remains with the author. Please contact the author in advance if you wish to redistribute, modify, or use it commercially. Third-party libraries remain the property of their respective rights holders.

## Disclaimer

This software is provided “as is”, without warranty of any kind, express or implied. The author shall not be held liable for any damages arising from its use or inability to use it. Use at your own risk.

