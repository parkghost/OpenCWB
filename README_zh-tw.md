<a href="https://www.buymeacoffee.com/tsunglung" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="30" width="120"></a>

中央氣象局-開放資料平臺 [Opendata CWB](https://opendata.cwb.gov.tw/index) 支援 Home Assistant


這個整合是基於 [OpenWeatherMap](https://openweathermap.org) ([@csparpa](https://pypi.org/user/csparpa), [pyowm](https://github.com/csparpa/pyowm)) 所做的開發。

## 安裝

你可以用 [HACS](https://hacs.xyz/) 來安裝這個整合。 步驟如下 custom repo: HACS > Integrations > 3 dots (upper top corner) > Custom repositories > URL: `tsunglung/OpenCWB` > Category: Integration

或是手動複製 `opencwb` 資料夾到你的 config 資料夾的  `custom_components` 目錄下。

然後重新啟動 Home Assistant.

# 設置

**在 Opendata CWB 申請 API 授權碼**
1. 打開 [Opendata CWB](https://opendata.cwb.gov.tw/devManual/insrtuction) 的網站
2. 註冊/登入您的帳號
3. 取得您個人的 API 授權碼

# 設定

**請使用 Home Assistant 整合設定**


1. 從 GUI. 設定 > 整合 > 新增 整合 > OpneCWB
   1. 如果 OpenCWB 沒有出現在清單裡，請 重新整理 (REFRESH) 網頁。
   2. 如果 OpenCWB 還是沒有出現在清單裡，請清除瀏覽器的快取 (Cache)。
2. 輸入 API 授權碼.
3. 輸入台灣的郷鎮市的名稱。 請參考在 [文件](https://opendata.cwb.gov.tw/opendatadoc/CWB_Opendata_API_V1.2.pdf) 附錄 A 裡的名稱。

<img src="https://github.com/tsunglung/OpenCWB/blob/master/linepay.jpg" alt="Line Pay" height="200" width="200"><img src="https://github.com/tsunglung/OpenCWB/blob/master/jkopay.jpg" alt="JKo Pay" height="200" width="200">