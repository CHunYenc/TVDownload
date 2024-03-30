# TVDownload

感謝原作者, 但是因為我在 `Ubuntu Arm64` 的裝置上無法使用, 所以我將原作者的專案 Fork 下來.

解決方法有參考原分支上的 `Issue` 

https://github.com/hcjohn463/JableTVDownload/issues/94

> Windows 不確定可不可以使用, 反正主分支就是可以的, 我就不多做修改了.

## 建立虛擬環境 & 安裝套件

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```


## 下載 chrome driver

```bash
apt install chromium-chromedriver -y # ubuntu
apt install chromium-driver -y # Debian
```

## 使用

```bash
python3 main.py
```

## 未來想開發的功能

- [ ] 下載完同步至 OneDrive
- [ ] 同步完成後刪除本地端檔案