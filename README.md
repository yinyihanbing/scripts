# Scripts

## 1.services
* 安装
```bash
bash <(curl -sL https://raw.githubusercontent.com/yinyihanbing/scripts/main/services/services.sh) -n miniwebdir -u root -g root -d "$(pwd)/bin" -a miniwebdir install
```
* 卸载
```bash
bash <(curl -sL https://raw.githubusercontent.com/yinyihanbing/scripts/main/services/services.sh) -n miniwebdir uninstall
```
* 启动
```bash
bash <(curl -sL https://raw.githubusercontent.com/yinyihanbing/scripts/main/services/services.sh) -n miniwebdir start
```
* 停止
```bash
bash <(curl -sL https://raw.githubusercontent.com/yinyihanbing/scripts/main/services/services.sh) -n miniwebdir stop
```
