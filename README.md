# WhisperBox

基于 ESP32-S3 的智能 AI 语音助手，支持语音对话、IoT 设备控制、LVGL 图形界面交互。

## 功能特性

- **语音识别 (ASR)** — 豆包实时语音识别
- **大模型对话 (LLM)** — 扣子 (Coze) 智能体
- **语音合成 (TTS)** — 豆包语音合成
- **图形界面** — LVGL 9.3 触摸屏交互
- **IoT 控制** — RGB 灯光、屏幕亮度、音量/音色/语速调节

## 硬件平台

- ESP32-S3 (16MB Flash, PSRAM)
- ST7789 TFT LCD (240×320)
- MAX98357 I2S 音频输出
- I2S 数字麦克风
- WS2812 RGB LED

## 构建

使用 PlatformIO 构建，目标环境: `esp32-s3-devkitc-1`

```bash
pio run
pio run --target upload
```
