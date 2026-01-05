# Ultra Lightweight Dehaze Methods for Robot Vision Using High-Level Synthesis

## 一、研究主題與背景

### 主題
- **Ultra Lightweight Dehaze Methods**

### 應用領域
- **Robot Vision（機器人視覺）**

### 核心技術
- **High-Level Synthesis（HLS）**

---

## 二、研究動機

- 環境霧氣會導致影像品質下降  
- 影像對比降低、細節喪失  
- 影響影像辨識、定位與導航精度  
- 機器人視覺系統需要**即時、低功耗、可部署**的去霧方法

---

## 三、High-Level Synthesis（HLS）概念

- 將 **C / C++ / SystemC** 程式碼  
- 自動轉換為 **RTL（Register Transfer Level）**
- 最終產出：
  - **VHDL / Verilog / IP Core**

### HLS 流程
C / C++ / SystemC
↓
Vivado HLS
↓
VHDL / Verilog / IP


### HLS 優點
1. 多種演算法可快速實現
2. 硬體面積較小
3. 高效能（平行化、管線化）
4. 大幅縮短開發時間與流程

---

## 四、FPGA 平台演進

### FPGA 類型
- FPGA
- SOPC FPGA
- SoC FPGA
- MPSoC FPGA
- Cloud FPGA
- RFSoC

> 整合程度持續提高，功能與應用場景愈來愈廣

---

## 五、RFSoC 與 FPGA 發展趨勢

### RFSoC 特點
- 整合 **ADC / DAC + FPGA**
- 低功耗
- 小型化
- 減少外部元件需求

### 製程與應用
- FPGA 製程進入 **7 nm / FinFET**
- 適合用於 **Cloud FPGA** 與高效能運算加速

---

## 六、PYNQ 與軟硬體整合

- **PYNQ**
  - 可使用 **Python** 控制 FPGA
  - 軟體友善、開發門檻低
  - 適合 AI 與影像處理應用
- 結合 HLS，有助於：
  - AI 模型加速
  - 視覺演算法硬體化
  - 快速原型設計

---