- 検索「wsl　インストール」  
    - WSL コマンドのインストール  
    右クリックして [ 管理者 として実行] を選択して管理者モードで PowerShell を開き、wsl --install コマンドを入力して、コンピューターを再起動します。  
    ```wsl --install```  

- 「VScode インストール」  

- 拡張機能  
    - python(microsoft)
    - jupyter
    - Remote Drvelopment(microsoft)  
        WSL: Windows上のLinux環境で開発するため。 
            - 左下の青いアイコン（>< のようなマーク）をクリック。  
            「Connect to WSL」 を選択。
        Dev Containers: Dockerコンテナの中を開発環境にするため。  
        Remote - SSH: 遠隔地のサーバーに接続して開発するため。  
        Remote - Tunnels: SSHサーバーを立てていないPCにも、Microsoftのトンネル経由で接続するため。  
    - Remote Explorer：vscodeを利用してssh接続を有効にするために必要
    - GitHub Actions：gitをvscode上で利用するため。
    - indent-rainbow：簡単に管理するため。

- requirements.txt
```
numpy==2.3.3
pandas==2.3.3
python-dateutil==2.9.0.post0
pytz==2025.2
six==1.17.0
tzdata==2025.2
ipykernel
matplotlib
black
scikit-lear
pingouin
```
