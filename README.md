# 🗺️ 災難後安心家訪地圖系統

> Interactive Relief Visit Maps for Post-Disaster Care

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://pichiu.github.io/relief-visit-map/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Mobile Friendly](https://img.shields.io/badge/Mobile-Friendly-blue)](https://pichiu.github.io/relief-visit-map/)

## 📖 專案簡介

這是一個為災難後安心家訪工作設計的互動式地圖系統，提供詳細的訪問路線規劃和地址分組資訊，協助志工進行有效率的關懷訪問。

### ✨ 主要功能
- 🗺️ **互動式地圖**：支援縮放、平移、標記點擊
- 📱 **響應式設計**：手機、平板、電腦完美適配
- 🎯 **精確定位**：每個地址都有精確的 GPS 座標
- 📊 **分組管理**：合理的訪問路線分組，提高關懷效率
- 🎨 **視覺化呈現**：不同顏色區分不同分組
- 🗺️ **路線規劃**：提供多種訪問模式以提升家訪效率

## 🌐 線上預覽

**主要連結：** https://pichiu.github.io/relief-visit-map/

### 📍 示範區域（DEMO）
- [七股區西寮里](https://pichiu.github.io/relief-visit-map/qigu/xiliao/) - ✅ 已完成

## 📁 專案結構

```
relief-visit-map/
├── README.md                     # 專案說明
├── LICENSE                      # 授權條款
└── 202507-danas/                # 2025年7月 丹娜絲颱風災後資料
    ├── qigu/                    # 七股區（示範區域）
    │   └── xiliao/              # 西寮里（DEMO）
    │       ├── ordered/         # 訪問路徑模式
    │       │   ├── overview.html    # 全區概覽
    │       │   ├── group-01.html    # 第1組
    │       │   ├── group-02.html    # 第2組
    │       │   └── group-03.html    # 第3組
    │       └── filter/          # 分組模式
    │           ├── overview.html    # 全區概覽
    │           ├── group-01.html    # 第1組
    │           ├── group-02.html    # 第2組
    │           └── group-03.html    # 第3組
    ├── beimen/                  # 北門區（規劃中）
    ├── jiangjun/                # 將軍區（規劃中）
    └── xuejia/                  # 學甲區（規劃中）
```

## 💻 技術架構

- **地圖引擎**: [Folium](https://folium.readthedocs.io/) + [Leaflet.js](https://leafletjs.com/)
- **地圖底圖**: OpenStreetMap
- **前端框架**: 純 HTML/CSS/JavaScript
- **部署平台**: GitHub Pages
- **響應式**: Bootstrap CSS Grid

## 🚀 使用方式

### 在線瀏覽
直接訪問 https://pichiu.github.io/relief-visit-map/

### 本地運行
```bash
# 克隆專案
git clone https://github.com/pichiu/relief-visit-map.git

# 進入專案目錄
cd relief-visit-map

# 使用任意 HTTP 伺服器運行
# 方法1: Python
python -m http.server 8000

# 方法2: Node.js
npx http-server

# 方法3: VS Code Live Server 擴展
# 安裝 Live Server 擴展後，右鍵點擊 index.html 選擇 "Open with Live Server"
```

## 📊 統計資訊

### 七股區西寮里（已完成）- 2025年7月 丹娜絲颱風災後
- **分組數量**: 3 組
- **涵蓋區域**: 西寮里全區
- **提供模式**: 多種訪問路線規劃模式

## 🤝 貢獻指南

歡迎貢獻新的地圖資料或改進現有功能！

### 貢獻步驟
1. Fork 本專案
2. 建立新的分支 (`git checkout -b feature/new-district`)
3. 提交你的變更 (`git commit -am 'Add new district maps'`)
4. 推送到分支 (`git push origin feature/new-district`)
5. 建立 Pull Request

### 資料格式
如需新增地圖資料，請確保包含：
- 地址清單（含門牌號碼）
- GPS 座標（WGS84 格式）
- 鄰別資訊
- 合理的分組建議

## 📝 更新日誌

### v1.0.0 (2025-07-XX)
- ✅ 完成七股區西寮里災後安心家訪地圖
- ✅ 建立響應式地圖系統
- ✅ 支援丹娜絲颱風災後資料結構

### 規劃中功能
- 🚧 北門區災後安心家訪地圖
- 🚧 將軍區災後安心家訪地圖  
- 🚧 學甲區災後安心家訪地圖
- 🚧 路線優化算法改進
- 🚧 訪問狀態追蹤功能

## 📄 授權條款

本專案採用 [MIT License](LICENSE) 授權條款。

## 📞 聯絡資訊

如有問題或建議，歡迎聯絡：
- 📧 Email: your.email@example.com
- 🐛 Issue: [GitHub Issues](https://github.com/pichiu/relief-visit-map/issues)

## 🙏 致謝

感謝以下資源和工具：
- [OpenStreetMap](https://www.openstreetmap.org/) 提供地圖資料
- [Folium](https://folium.readthedocs.io/) 地圖可視化工具
- [GitHub Pages](https://pages.github.com/) 免費託管服務

---

⭐ 如果這個專案對你有幫助，請考慮給一個 Star！

