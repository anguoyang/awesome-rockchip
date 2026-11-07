# Awesome Rockchip（中文版）

> Rockchip 生态精选名单：板卡、操作系统、AI 工具链、模型、多媒体、开发工具与社区资源 —— **持续活跃维护**。

[English version](README.md)

覆盖 RK3588 / RK3588S、RK3576、RK3566 / RK3568、RV1106 / RV1126。

**共 111 条** · 最后更新：2026-11-08

## 维护承诺

多数 Rockchip 名单会慢慢过期，这份按另一套规矩运行：

- **外部 PR 48 小时内必有首次处理** —— 合并、评论或请求修改，三选一。
- **每周自动查链**，失效链接在每月更新轮次内修复或移除。
- **每月一轮固定更新**：新收录、查链修复、归档项目清理。
- 只按质量收录，不卖位置、没有付费推广条目。

## 板块

- 板卡与厂商 — 16 条
- 操作系统、引导与内核 — 19 条
- RKNN、RKLLM 与 AI 工具链 — 15 条
- 模型与部署 — 20 条
- 多媒体 — 14 条
- 开发工具 — 14 条
- 社区、文档与教程 — 13 条

## 板卡与厂商

- [Rockchip Linux](https://github.com/rockchip-linux) - 瑞芯微官方开源组织，发布厂商内核、启动组件与多媒体代码，是几乎所有 RK 板厂的起点。
- [Radxa](https://github.com/radxa) - ROCK 系列板卡的主页，包含其 RK3588、RK3576 与 RK3566 单板机和核心板的内核、工具与源码。
- [Radxa ROCK 5B](https://radxa.com/products/rock5/5b/) - Radxa 旗舰 RK3588 板的产品页，介绍其四屏输出、NVMe 存储、2.5GbE 网络与 6 TOPS NPU。
- [Orange Pi](https://github.com/orangepi-xunlong) - 迅龙软件官方组织，覆盖 Orange Pi 各板卡，包括 RK3588S 的 Orange Pi 5 系列与 RK3566 板型。
- [Firefly](https://github.com/FireflyTeam) - Firefly 官方组织，覆盖其 RK3588 与 RK3568 板卡、核心板模块与 Station 系列迷你主机。
- [FriendlyARM / NanoPi](https://github.com/friendlyarm) - FriendlyElec 的源码中心，覆盖 NanoPi 与 NanoPC 系列：RK3588 旗舰、RK3576 型号与主打路由的 RK3568 R5 系列。
- [Khadas](https://github.com/khadas) - Khadas 官方组织，托管 Edge2（RK3588S）与 Edge（RK3399）的固件、内核与工具。
- [Pine64](https://github.com/pine64) - PINE64 官方组织，维护其社区型瑞芯微硬件，包括 RK3566 的 Quartz64 系列与 RK3588 的 QuartzPro64。
- [LubanCat](https://github.com/LubanCat) - 野火 LubanCat 板卡组织，含其 RK3588、RK3576、RK3566/3568 开发板的 SDK 清单与镜像，在国内用户中很常见。
- [Banana Pi](https://github.com/BPI-SINOVOIP) - 香蕉派（Sinovoip）官方组织，包含 RK3588 的 BPI-W3 与 RK3568 路由板等瑞芯微型号。
- [ASUS Tinker Board Linux](https://github.com/TinkerBoard-Linux) - 华硕 Tinker Board 的 Linux 组织，维护基于瑞芯微 SoC 的 Tinker Board 型号的 Yocto 清单与构建基础设施。
- [Turing RK1](https://turingpi.com/product/turing-rk1/) - 采用 Jetson 引脚布局的 RK3588 计算模块，可插入 Turing Pi 集群主板，单节点最高 32GB 内存。
- [Luckfox Pico](https://github.com/LuckfoxTECH/luckfox-pico) - Luckfox 微型 RV1106 与 RV1103 摄像头板的 SDK 与示例，面向低成本 Linux IP 摄像头与视觉项目。
- [ArmSoM](https://github.com/ArmSoM) - ArmSoM 官方组织，提供其 RK3588 Sige 系列与 RK3576 板卡、核心板的文档与系统源码。
- [Radxa ROCK 5B Images (radxa-build)](https://github.com/radxa-build/rock-5b) - 生成 Radxa 官方可下载系统镜像的构建仓库，面向 ROCK 5B。
- [Orange Pi Build](https://github.com/orangepi-xunlong/orangepi-build) - 迅龙的镜像构建系统，组装 Orange Pi 各板卡的官方 Linux 镜像，包括 RK3588S 型号。

## 操作系统、引导与内核

- [Armbian Build Framework](https://github.com/armbian/build) - Armbian 镜像背后的构建系统，对众多 RK3588、RK3576 与 RK356x 板卡提供偏向主线的持续维护支持。
- [Ubuntu Rockchip (Joshua Riek) （已归档）](https://github.com/Joshua-Riek/ubuntu-rockchip) - 使用广泛的 RK3588 与 RK3588S 版 Ubuntu 22.04 / 24.04 镜像；仓库现已归档，应视作冻结基线。
- [DietPi](https://github.com/MichaIng/DietPi) - 轻量 Debian 系统，带自动化软件安装，支持 NanoPi、Orange Pi、Radxa 等多种瑞芯微板卡。
- [Radxa Kernel](https://github.com/radxa/kernel) - Radxa 的厂商内核树，承载 ROCK 产品线的板级支持与修复。
- [Rockchip Linux Kernel](https://github.com/rockchip-linux/kernel) - 瑞芯微厂商 BSP 内核，多数板厂自有内核的派生源头与参考树。
- [U-Boot (upstream)](https://github.com/u-boot/u-boot) - U-Boot 上游，无需厂商分支即可启动越来越多的 RK3588、RK3576 与 RK356x 板卡。
- [Rockchip U-Boot](https://github.com/rockchip-linux/u-boot) - 与瑞芯微 BSP 发布对齐的 U-Boot 分支，仍被许多厂商 SDK 引用。
- [Rockchip rkbin](https://github.com/rockchip-linux/rkbin) - 瑞芯微启动流程必需的二进制组件，包括各 SoC 的 DDR 初始化与可信固件部分。
- [EDK2 RK3588](https://github.com/edk2-porting/edk2-rk3588) - RK3588 的 UEFI 固件移植，让板子能像小 PC 一样启动标准 ARM64 安装程序与操作系统。
- [meta-rockchip (community)](https://github.com/JeffyCN/meta-rockchip) - 内容丰富的瑞芯微 Yocto 层，特点是为定制构建接好了多媒体与图形加速。
- [meta-rockchip (Yocto Project)](https://git.yoctoproject.org/meta-rockchip) - Yocto 项目自己的瑞芯微 BSP 层，面向公开发售的板卡，版本紧跟上游内核与引导程序。
- [Khadas Fenix](https://github.com/khadas/fenix) - Khadas 的构建环境，为其板卡生成 Ubuntu 与 Debian 镜像，包括 RK3588S 的 Edge2。
- [OpenWrt (upstream)](https://github.com/openwrt/openwrt) - OpenWrt 上游，其 rockchip 目标覆盖 NanoPi R5、R6 系列等 RK3568 与 RK3588 网络板卡。
- [OpenWrt Rockchip (quintus-lab)](https://github.com/quintus-lab/openwrt-rockchip) - 面向瑞芯微路由与板卡打包的社区 OpenWrt 构建，以可直接刷机的固件形式发布。
- [LibreELEC](https://github.com/LibreELEC/LibreELEC.tv) - 「刚刚够用」的 Kodi 媒体中心发行版，随着主线内核与视频支持成熟持续构建瑞芯微镜像。
- [Rockchip Android](https://github.com/rockchip-android) - 瑞芯微平台的 Android 源码组织；近年较安静，但仍是厂商 Android 代码树的参考布局。
- [Khadas Android Manifest](https://github.com/khadas/android_manifest) - 汇总 Khadas 各板卡 Android 源码的 repo 清单，包括 RK3588S 的 Edge2。
- [Mesa](https://gitlab.freedesktop.org/mesa/mesa) - Mesa 上游，Panthor 与 Panfrost 驱动所在地，为 RK3588 与 RK356x 的 GPU 提供开源 OpenGL 与 Vulkan 支持。
- [Collabora RK3588 Mainline Status](https://gitlab.collabora.com/hardware-enablement/rockchip-3588/notes-for-rockchip-3588/-/blob/main/mainline-status.md) - Collabora 持续维护的跟踪表，记录 RK3588 各硬件模块在主线 Linux、U-Boot 与 Mesa 中的可用状态与缺失项。

## RKNN、RKLLM 与 AI 工具链

- [airockchip/rknn-toolkit2](https://github.com/airockchip/rknn-toolkit2) - 瑞芯微主机端主工具包，把神经网络转换、量化为 RKNN 格式，面向现行 RK35xx 与 RV11xx 的 NPU。
- [rockchip-linux/rknn-toolkit](https://github.com/rockchip-linux/rknn-toolkit) - 第一代 RKNN 转换工具包，为 RK3399Pro、RK1808 等 Toolkit2 不覆盖的老芯片保留。
- [airockchip/rknn3-toolkit](https://github.com/airockchip/rknn3-toolkit) - 瑞芯微下一代转换工具包，面向 RKNN2 设备范围之外的新一代 NPU。
- [airockchip/rknn-llm](https://github.com/airockchip/rknn-llm) - 瑞芯微官方方案，把大语言模型与视觉语言模型转换为 RKLLM 格式并在 NPU 上运行。
- [rockchip-linux/rknpu2](https://github.com/rockchip-linux/rknpu2) - 第二代 NPU 运行时 SDK，含在板端加载、执行 RKNN2 模型的 C API 与库文件。
- [leafqycc/rknn-cpp-Multithreading](https://github.com/leafqycc/rknn-cpp-Multithreading) - C++ 示例框架，把 RKNN 推理分发到多线程以同时用上多个 NPU 核心。
- [swdee/go-rknnlite](https://github.com/swdee/go-rknnlite) - RKNN Toolkit2 C API 的 Go 绑定，附在 RK35xx 板卡上跑检测与 OCR 模型的完整示例。
- [darkautism/rknn-rs](https://github.com/darkautism/rknn-rs) - RKNN 运行时的 Rust 绑定，让 Rust 程序能在瑞芯微 NPU 上加载、运行模型。
- [darkautism/rkllm-rs](https://github.com/darkautism/rkllm-rs) - RKLLM 运行时的 Rust 绑定，用于在 Rust 应用中嵌入 NPU 语言模型推理。
- [happyme531/ztu_somemodelruntime_ez_rknn_async](https://github.com/happyme531/ztu_somemodelruntime_ez_rknn_async) - RKNPU2 的异步 Python 运行时，接口风格接近 ONNX Runtime，并带多核调度。
- [heyongxin233/YOLO-Pruning-RKNN](https://github.com/heyongxin233/YOLO-Pruning-RKNN) - 在 RKNN 转换前对 YOLO 模型剪枝的工作流，用少量精度换更快的 NPU 推理。
- [daedaluz/rknn-docker](https://github.com/daedaluz/rknn-docker) - 打包好的 RKNN 转换与运行时 Docker 镜像，免本地安装即可使用。
- [Hanzo-Huang/rkllm-docker](https://github.com/Hanzo-Huang/rkllm-docker) - 在 RK3588 板卡上运行 RKLLM 语言模型的 Docker 方案，无需手动拼装运行时库。
- [GatekeeperZA/RKLLM-API-Server](https://github.com/GatekeeperZA/RKLLM-API-Server) - 以 RKLLM 为后端的 OpenAI 风格 API 服务器，还可把视觉编码器与语言模型配对处理多模态请求。
- [huonwe/rkllm_openai_like_api](https://github.com/huonwe/rkllm_openai_like_api) - 轻量服务器，通过与 OpenAI API 形状相近的端点暴露 RKLLM 模型，方便客户端接入。

## 模型与部署

- [airockchip/rknn_model_zoo](https://github.com/airockchip/rknn_model_zoo) - 瑞芯微官方模型集合，含转换好的模型与可运行的 Python、C 示例，覆盖检测、分割、OCR、人脸与语音任务。
- [airockchip/rknn3-model-zoo](https://github.com/airockchip/rknn3-model-zoo) - RKNN3 世代的配套模型集合，含其支持任务的转换脚本与推理示例。
- [airockchip/ultralytics_yolov8](https://github.com/airockchip/ultralytics_yolov8) - 瑞芯微的 Ultralytics YOLOv8 分支，调整过检测头导出方式，便于 RKNN 转换与量化。
- [airockchip/ultralytics_yolo11](https://github.com/airockchip/ultralytics_yolo11) - 瑞芯微的 YOLO11 分支，已为现行 NPU 范围准备好 RKNN 友好的导出路径。
- [airockchip/yolov5](https://github.com/airockchip/yolov5) - 瑞芯微持续维护的 YOLOv5 分支，导出路径针对 RKNN 转换与 NPU 部署做了调整。
- [Qengineering/YoloV8-NPU](https://github.com/Qengineering/YoloV8-NPU) - 基于 RKNN 运行时的 C++ YOLOv8 实现，面向 Rock 5、Orange Pi 5 等 RK3566、RK3568 与 RK3588 板卡。
- [Qengineering/YoloV5-NPU](https://github.com/Qengineering/YoloV5-NPU) - YOLOv5 的瑞芯微 NPU 部署版，含在板端运行所需的转换说明与后处理代码。
- [wzxzhuxi/rknn-3588-npu-yolo-accelerate-saturated](https://github.com/wzxzhuxi/rknn-3588-npu-yolo-accelerate-saturated) - RK3588 的 YOLO 加速项目，把工作流水线化地压到三个 NPU 核心上以提高检测吞吐。
- [LuckfoxTECH/luckfox_pico_rknn_example](https://github.com/LuckfoxTECH/luckfox_pico_rknn_example) - Luckfox 官方 RKNN 示例，面向其 RV1106 Pico 板，演示小视觉模型在 0.5 TOPS NPU 上运行。
- [Qengineering/Qwen3-VL-2B-NPU](https://github.com/Qengineering/Qwen3-VL-2B-NPU) - Qwen3-VL 2B 视觉语言模型的移植：RKNN 视觉编码器配 RKLLM 解码器，运行在 RK3588 上。
- [Qengineering/SmolVLM2-500M-NPU](https://github.com/Qengineering/SmolVLM2-500M-NPU) - 小型 SmolVLM2 视觉语言模型封装，可完全在 RK3588 NPU 上回答关于图片的问题。
- [zyp0424/Qwen-Chat-Assistant](https://github.com/zyp0424/Qwen-Chat-Assistant) - 完全本地运行在 RK3588 上的多模态语音助手：摄像头画面经 RKNN 视觉模型提取特征后喂给 RKLLM 的 Qwen3 推理，含唤醒词、语音识别与合成全链路。
- [NotPunchnox/rkllama](https://github.com/NotPunchnox/rkllama) - Ollama 风格的服务器与客户端，在 RK3588、RK3576 板卡的 NPU 而非 CPU 上运行 RKLLM 模型。
- [kyshipit/eai-rk3588](https://github.com/kyshipit/eai-rk3588) - 插件化的 RK3588 边缘 AI 平台：单份 YAML 配置驱动多线程视觉流水线（RKNN YOLO、SCRFD），并集成 RKLLM 对话与语音合成。
- [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) - 广泛使用的 GGUF 推理引擎，许多 RK3588 用户用它在 CPU 核心上跑模型，作为 RKLLM 之外的灵活备选。
- [mlc-ai/mlc-llm](https://github.com/mlc-ai/mlc-llm) - 基于编译器的 LLM 部署框架，可面向移动 GPU，例如 RK3588 板卡上的 Mali GPU。
- [k2-fsa/sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) - 离线语音工具包，含识别、合成与说话人分离，并支持在瑞芯微 NPU 上运行模型。
- [jianglu/whisper_RK3588](https://github.com/jianglu/whisper_RK3588) - Whisper 语音识别移植，在 RK3588 NPU 上运行 INT8 RKNN 版本模型。
- [marty1885/paroli](https://github.com/marty1885/paroli) - 基于 Piper 的流式文字转语音服务器，可选择把部分工作负载移到 RK3588 NPU 上。
- [anguoyang/rk-bench](https://github.com/anguoyang/rk-bench) - 在 RK3588 硬件上实测的公开 RKNN 模型标准化跑分结果集。

## 多媒体

- [rockchip-linux/mpp](https://github.com/rockchip-linux/mpp) - 瑞芯微官方用户态媒体框架，对接 VPU 实现其全系 SoC 的硬件视频编解码。
- [airockchip/librga](https://github.com/airockchip/librga) - RGA 2D 加速器的用户态库，在瑞芯微芯片上做图像缩放、旋转、裁剪与像素格式转换。
- [nyanmisaka/ffmpeg-rockchip](https://github.com/nyanmisaka/ffmpeg-rockchip) - 接入 rkmpp 编解码与 rkrga 滤镜的 FFmpeg 分支，让转码任务留在 RK3588 级别的视频硬件上。
- [jellyfin/jellyfin-ffmpeg](https://github.com/jellyfin/jellyfin-ffmpeg) - Jellyfin 的 FFmpeg 构建，带完整的瑞芯微转码管线，包括 rkmpp 编解码、RGA 缩放与色调映射。
- [Jellyfin Rockchip VPU guide](https://jellyfin.org/docs/general/post-install/transcoding/hardware-acceleration/rockchip/) - Jellyfin 官方文档，讲解 RK3588 与 RK3588S 上 RKMPP 硬件转码的配置与编解码支持情况。
- [libcamera-org/libcamera](https://github.com/libcamera-org/libcamera) - libcamera 的 GitHub 镜像，含 RkISP1 管线处理器与 IPA，服务于瑞芯微 ISP1 硬件的摄像头。
- [Kwiboo/linux-rockchip](https://github.com/Kwiboo/linux-rockchip) - 偏主线的内核分支，跟踪新近瑞芯微平台的 DRM 显示与视频解码器使能工作。
- [corenel/gstreamer-rga](https://github.com/corenel/gstreamer-rga) - 小型 GStreamer 插件，暴露瑞芯微 RGA 模块，让管线能把图像缩放与格式转换卸载出去。
- [numbqq/rkaiq-rockchip-debs](https://github.com/numbqq/rkaiq-rockchip-debs) - 瑞芯微 rkaiq 摄像头调校与 3A 服务组件的 Debian 打包，面向 RK356x 与 RK3588 系统。
- [anguoyang/onvif-scan](https://github.com/anguoyang/onvif-scan) - 发现局域网内的 ONVIF 摄像头，盘点其设备信息、媒体 Profile 与流地址，输出 JSON 与 HTML 报告。
- [JeffyCN/libv4l-rkmpp](https://github.com/JeffyCN/libv4l-rkmpp) - 通过 V4L2 接口呈现 MPP 编解码的插件，让 Chromium 能把浏览器视频交给 VPU。
- [woodyst/rockchip-vaapi](https://github.com/woodyst/rockchip-vaapi) - VA-API 后端，把标准 Linux 视频加速调用转接到 RK3588 硬件上的 MPP。
- [tsukumijima/libmali-rockchip](https://github.com/tsukumijima/libmali-rockchip) - 瑞芯微显示与图形栈所用 Mali 用户态 GPU 驱动的 Debian 打包与镜像。
- [armsurvivors/kodi-rockchip-deb](https://github.com/armsurvivors/kodi-rockchip-deb) - 面向 Armbian 瑞芯微系统的 Kodi 打包构建，可选用厂商内核 rkmpp 或主线 V4L2 request 解码。

## 开发工具

- [rockchip-linux/rkdeveloptool](https://github.com/rockchip-linux/rkdeveloptool) - 瑞芯微官方开源 USB 刷机命令（Linux 与 macOS），向 Maskrom 或 Loader 模式的设备写入 loader 与镜像。
- [xboot/xrock](https://github.com/xboot/xrock) - 跨平台瑞芯微 Maskrom 工具，可转储、擦除、写入闪存，并查看 DDR 与芯片信息。
- [Radxa rkdeveloptool documentation](https://docs.radxa.com/en/zero/zero3/low-level-dev/rkdeveloptool) - Radxa 关于 rkdeveloptool 的文档，说明它是 upgrade_tool 的开源对应物，并给出 Maskrom 刷机示例。
- [KiwiPi RKDevTool guide](https://kiwipi.com/blog/rkdevtool/) - 厂商指南，介绍 RKDevTool 的下载与 Windows 界面用法，可刷整包固件或单个分区。
- [ThomasKaiser/sbc-bench](https://github.com/ThomasKaiser/sbc-bench) - 单板机 Shell 跑分套件，检查频率、温度与存储行为，常用于验证 RK3588 板卡。
- [anguoyang/rk-edge-doctor](https://github.com/anguoyang/rk-edge-doctor) - 瑞芯微板卡诊断 CLI，报告板卡健康、检查 RKNN 模型是否回退到 CPU、并验收 RTSP 摄像头码流。
- [anguoyang/rk-deploy](https://github.com/anguoyang/rk-deploy) - 把 RKNN 应用打包成版本化部署包，经 SSH 推送到瑞芯微板卡上以 systemd 服务运行，支持回滚与舰队状态巡检。
- [orangepi-xunlong/wiringOP](https://github.com/orangepi-xunlong/wiringOP) - 迅龙适配的 WiringPi 风格 C 库，用于 Orange Pi 板卡的 GPIO 与外设访问，含瑞芯微型号。
- [brgl/libgpiod](https://github.com/brgl/libgpiod) - Linux GPIO 字符设备的 C 库与命令行工具，在瑞芯微板卡上驱动引脚的现代做法。
- [rm-hull/OPi.GPIO](https://github.com/rm-hull/OPi.GPIO) - Orange Pi 的 Python GPIO 包，为瑞芯微 SoC 型号提供与 RPi.GPIO 兼容的接口。
- [vsergeev/python-periphery](https://github.com/vsergeev/python-periphery) - 通过 Linux 原生接口访问 GPIO、I2C、SPI 与串口的 Python 库，适合在 RK 板卡上做外设工作。
- [tio/tio](https://github.com/tio/tio) - 极简串口终端程序，常用于连接瑞芯微板卡暴露的 UART 调试控制台。
- [gahingwoo/RKDevelopTool-GUI](https://github.com/gahingwoo/RKDevelopTool-GUI) - 瑞芯微固件刷机与分区任务的桌面图形前端，支持 macOS 与 Linux。
- [jjm2473/rktool-webusb](https://github.com/jjm2473/rktool-webusb) - 用 WebAssembly 与 WebUSB 把 rkdeveloptool 移植到浏览器，与刷机模式下的瑞芯微设备通信。

## 社区、文档与教程

- [Rockchip Open Source Document](https://opensource.rock-chips.com/) - 瑞芯微官方开源 Wiki，汇总按 SoC 组织的 TRM、数据手册、板卡说明与软件指南。
- [Radxa Documentation](https://docs.radxa.com/) - Radxa 持续维护的文档中心，含其瑞芯微板卡的上手指南、系统安装与配件教程。
- [Radxa Community Forum](https://forum.radxa.com/) - Radxa 公开支持论坛，用户与官方人员在此公开排查 Rock、Zero 与 CM 系列板卡的问题。
- [Orange Pi Official Site](https://www.orangepi.org/) - Orange Pi 官方站点，链接各板卡的手册、原理图、工具与系统镜像，覆盖其 RK3588 与 RK3566 板型。
- [Firefly Wiki](https://wiki.t-firefly.com/en/ROC-RK3588-PC/started.html) - Firefly 产品 Wiki，记录其 RK3588、RK3576、RK3568 板卡与模块的设置、SDK 构建与外设配置。
- [FriendlyElec Wiki](https://wiki.friendlyelec.com/wiki/index.php?title=NPU) - FriendlyElec 的 Wiki，覆盖 NanoPi 与 NanoPC 的设置，以及面向 RK3576、RK3588 板卡的 RKNN 与 RKLLM 实操教程。
- [Armbian Community Forums - Rockchip](https://forum.armbian.com/forum/85-rockchip/) - Armbian 论坛的瑞芯微板块，公开讨论社区板卡上的主线与厂商内核问题。
- [PINE64 Wiki - ROCKPro64](https://wiki.pine64.org/index.php?title=ROCKPro64) - PINE64 社区 Wiki，记录 ROCKPro64、Quartz64 等瑞芯微板卡的布局、软件发布与数据手册。
- [Khadas Docs - Edge2](https://docs.khadas.com/products/sbc/edge2/start) - Khadas 的 Edge 系列文档，覆盖 RK3588S 的 Edge2 的安装、固件、设备树覆盖与 NPU 话题。
- [awesome-RK3588 (choushunn)](https://github.com/choushunn/awesome-RK3588) - 另一份社区维护的名单，专注于 RK3588 资源，与本名单相互独立。
- [Jeff Geerling - RK3588 Writing](https://www.jeffgeerling.com/tags/rk3588) - Jeff Geerling 以 RK3588 为标签的文章集合，收录他对 Rock 5 系列等瑞芯微板卡的实测与评论。
- [CNX Software - Rockchip RK35xx](https://www.cnx-software.com/category/processors/rockchip-rk35xx/) - CNX Software 的 RK35xx 分类，跟踪新发布的瑞芯微板卡、模块与软件动态。
- [linux-rockchip Mailing List](http://lists.infradead.org/mailman/listinfo/linux-rockchip) - infradead 邮件列表，讨论瑞芯微平台的上游内核补丁与评审。

## 参与贡献

见 [CONTRIBUTING.md](CONTRIBUTING.md)。简要规则：每条一行（名称 + 链接 + 一句描述），链接必须可达，项目须与 Rockchip 平台直接相关，且近 12 个月有活动或是官方稳定基线。

## 许可证

CC0 1.0 —— 见 [LICENSE](LICENSE)。名单本身进入公有领域；所链接项目保留各自许可证。
