# MCU STM32 Learning
這是我學習嵌入式系統與 STM32F407 Discovery 開發板的完整紀錄。

## 學習資源與筆記
詳細的技術筆記、原理分析與 Debug 過程紀錄於 HackMD：
- [Lab0: 開發環境建置](https://hackmd.io/tjXVD66tTE2wT-CoQUvF4Q)

## 硬體環境 (Hardware)
- **MCU**: STM32F407VGT6 (ARM Cortex-M4)
- **Board**: STM32F407G-DISC1 (Discovery Board)
- **Debugger**: ST-LINK/V2 (On-board)
- **Peripherals**:
  - USB to TTL (CP2102)

## 專案目錄 (Labs)

| Lab | 名稱 | 描述 | 關鍵技術 |
| :---: | :--- | :--- | :--- |
| 00 | [STM32_envCreate](./STM32_envCreate) | 建立現代化開發環境 (CMake, CubeMX, VS Code) | Environment Setup |
| 01 | [Lab01_Blinky](./Lab01_Blinky) | 讓開發板上的 4 顆 LED 閃爍 (尚未建立) | GPIO Output |
| ... | ... | ... | ... |

## 開發環境 (Software)
- **IDE**: VS Code
- **Extensions**: STM32 VS Code Extension, CMake, Cortex-Debug
- **Toolchain**: ARM GCC Toolchain

## 參考資料
- **Gemini pro**
- **成大資工系-張大緯教授**: 嵌入式作業系統分析與實作課程講義。
- **成果筆記**: [連結](https://www.st.com/resource/en/user_manual/dm00039084-discovery-kit-with-stm32f407vg-mcu-stmicroelectronics.pdf)
- **教學影片**: [連結](https://www.bilibili.com/video/BV1s5411L7cD/?p=2&share_source=copy_web&vd_source=594a49870a6460f2745c6196d372f4d8)