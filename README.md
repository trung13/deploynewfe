
1. Cài đặt môi trường

    ```bash
    sudo apt-get update && sudo apt-get install -y vim python-pip curl git
    pip install docker-compose
    ```

2. Cài Docker 

   ```bash
   sudo curl -sSL get.docker.com | sh
   ```


3. Clone repo

    ```bash
    git clone -b 2.0 https://github.com/trunganh13/codevtDeploy.git && cd codevtDeploy
    ```

4. Khởi động

    ```bash
    docker-compose up -d
    ```

