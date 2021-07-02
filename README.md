# TarkovSpawnNotifier
マッチメイキング完了時に通知を出します。
Notify when your matching completed.

# How To Use (JP)
1. [TarkovSpawnNotifier.zip](https://github.com/advancedbear/TarkovSpawnNotifier/archive/refs/heads/main.zip)をダウンロードし、展開します。
2. `TarkovSpawnNotifier.ps1` をメモ帳などで開き、以下の行を編集します。
    ```PowerShell
    $eft = "D:\Battlestate Games\eft\Logs"
    ```
    EFTをインストールしたパスを書いて上書き保存してください。
3. Escape From Tarkovの起動が完了した後、`start.bat`をダブルクリックして開始します。
    - PowerShellスクリプトを初めて使う場合、「実行ポリシーの変更」画面が表示されます。
    - [Y]キーを押して、変更を許可してください。
4. `Activated` が表示されれば、動作が開始しています！
    - マッチメイキング完了時に、バルーン通知が表示されます。
    - カウントダウン開始時に、バルーン通知が表示されます。（PMC出撃時のみ）

# How To Use (EN)
1. Download [TarkovSpawnNotifier.zip](https://github.com/advancedbear/TarkovSpawnNotifier/archive/refs/heads/main.zip) and Extract it..
2. Open `TarkovSpawnNotifier.ps1` with Notepad and Edit as below.
    ```PowerShell
    $eft = "D:\Battlestate Games\eft\Logs"
    ```
    Over-Write your EFT installed Path in this line.
3. Execute `start.bat` after launched "Escape from Tarkov".
    * When it's first time to use PowerShell Script, "Execution Policy Change" prompt will be shown.
    * Press [Y] key and Accept the execution policy.
4. When you can see `Activated`, it's Working!
    * When match making is finished, Baloon notification will be shown.
    * When starting countdown, Baloon notification will be shown. (ONLY PMC)