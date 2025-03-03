# Scripts

## 1.services
* 安装
```bash
bash <(curl -sL https://raw.githubusercontent.com/yinyihanbing/scripts/main/services/services.sh) -n ggweb -u root -g root -d "$(pwd)/bin" install
```
* 卸载
```bash
bash <(curl -sL https://raw.githubusercontent.com/yinyihanbing/scripts/main/services/services.sh) -n ggweb uninstall
```
* 启动
```bash
bash <(curl -sL https://raw.githubusercontent.com/yinyihanbing/scripts/main/services/services.sh) -n ggweb start
```
* 停止
```bash
bash <(curl -sL https://raw.githubusercontent.com/yinyihanbing/scripts/main/services/services.sh) -n ggweb stop
```
