# Bad Apple Wave for XY Oscilloscope
> 在示波器 XY 模式播放 Bad Apple!!
> Play Bad Apple!! on oscilloscope XY mode

---

## 项目简介 | Introduction
**中文**
本项目包含用于示波器XY模式播放 Bad Apple!! 的立体声音频文件 `Bad_apple.wav`。
- 左声道（CH1）→ X轴（水平坐标）
- 右声道（CH2）→ Y轴（垂直坐标）
播放音频，示波器切换到XY模式，就可以直接在屏幕上画出 Bad Apple 的剪影动画。
原理：预先把视频轮廓坐标编码成立体声波形，属于矢量示波器艺术。

**English**
This repository contains a stereo wav file `Bad_apple.wav` for playing Bad Apple!! on an oscilloscope in XY mode.
- Left channel (CH1) → X axis (horizontal)
- Right channel (CH2) → Y axis (vertical)
Play the audio and switch your oscilloscope to XY mode, the silhouette animation of Bad Apple will be drawn on screen.
Principle: Video contour coordinates are pre-encoded into stereo waveform, a classic vector oscilloscope art.

---

## 硬件接线 | Hardware Connection
**中文**
1. 准备一根3.5mm耳机线，剥开外皮分出：左声道、右声道、地线
2. CH1（X通道）：接左声道
3. CH2（Y通道）：接右声道
4. 两个通道的地线共地
> 音量不要开太大，避免信号幅值超出示波器量程

**English**
1. Prepare a 3.5mm audio cable, split into left channel, right channel and GND
2. CH1 (X): Left audio channel
3. CH2 (Y): Right audio channel
4. Connect GND of both probes together
> Do NOT turn up volume too high, to avoid over-range

---

## 示波器设置 | Oscilloscope Settings
**中文**
1. 打开示波器，切换到 XY模式（不是普通Y-T波形模式）
2. 调节CH1、CH2电压档位，让画面大小合适
3. 开启低通滤波，减少噪点杂线
4. 电脑播放 `Bad_apple.wav`，微调音量控制画面大小

**English**
1. Switch oscilloscope to XY mode (NOT Y-T time mode)
2. Adjust CH1 / CH2 voltage scale to fit the screen
3. Turn on low-pass filter to reduce noise
4. Play `Bad_apple.wav` on PC, adjust volume to control amplitude

---

## 文件说明 | File Structure
**中文**