# 體驗 Docker Compose 建置與執行

1. 下載範例程式

    ```ps1
    git clone https://github.com/duotify/ModernDotNet.git -b 20H2
    cd ModernDotNet
    ```

2. 建置多容器

    ```ps1
    docker-compose -f .\docker-compose.yml build
    ```

3. 啟動與刪除多容器

    ```ps1
    docker-compose -f .\docker-compose.yml up
    docker-compose -f .\docker-compose.yml down
    ```

4. 測試網站執行與 SQL Server 資料庫連接

    <http://localhost/>
