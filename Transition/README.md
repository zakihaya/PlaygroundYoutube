## 手順

- ViewController.swiftを削除


cocoapodsの初期設定

- プロジェクトのルートにcd
- Gemfileに gem 'cocoapods' を記入
- bundle install --path=vendor/bundle
- bundle exec pod init
- Podfileに pod 'PGFramework' を記入
- bundle exec pod install
- 1回XCodeを閉じて、Transition.xcworkspaceを開き直す


