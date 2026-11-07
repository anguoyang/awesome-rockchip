# Awesome Rockchip [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Rockchip boards, operating systems, AI toolchains, models, multimedia, development tools, and community resources — **actively maintained**.

[中文版 / Chinese version](README.zh.md)

Covers RK3588 / RK3588S, RK3576, RK3566 / RK3568, and RV1106 / RV1126.

**111 entries** · Last updated: 2026-11-08

Most Rockchip lists go stale. This one is run differently:

- **Pull requests get a first response within 48 hours** — merged, commented, or changes requested.
- **Links are checked automatically every week**, and dead links are fixed or removed in the monthly update round.
- **A maintenance round runs every month**: new entries, link fixes, and archived projects removed or marked.
- Entries are included on merit only. There are no paid placements.

## Contents

- [Boards & Vendors](#boards--vendors) — 16 entries
- [OS, Bootloader & Kernel](#os-bootloader--kernel) — 19 entries
- [RKNN, RKLLM & AI Toolchain](#rknn-rkllm--ai-toolchain) — 15 entries
- [Models & Deployment](#models--deployment) — 20 entries
- [Multimedia](#multimedia) — 14 entries
- [Development Tools](#development-tools) — 14 entries
- [Community, Docs & Learning](#community-docs--learning) — 13 entries

## Boards & Vendors

- [Rockchip Linux](https://github.com/rockchip-linux) - Rockchip's own open-source organisation, publishing the vendor kernel, boot components and multimedia code that nearly every RK board maker starts from.
- [Radxa](https://github.com/radxa) - Home of the ROCK board family, with board kernels, tools and sources for its RK3588, RK3576 and RK3566 single-board computers and compute modules.
- [Radxa ROCK 5B](https://radxa.com/products/rock5/5b/) - Radxa's flagship RK3588 board product page, covering its quad-display output, NVMe storage, 2.5GbE networking and 6 TOPS NPU.
- [Orange Pi](https://github.com/orangepi-xunlong) - Xunlong's official organisation for Orange Pi boards, including the RK3588S-based Orange Pi 5 line and its RK3566 boards.
- [Firefly](https://github.com/FireflyTeam) - Firefly's official organisation covering its RK3588 and RK3568 boards, core modules and Station-series mini PCs.
- [FriendlyARM / NanoPi](https://github.com/friendlyarm) - FriendlyElec's source hub for NanoPi and NanoPC boards, spanning RK3588 flagships, RK3576 models and the RK3568 router-oriented R5 series.
- [Khadas](https://github.com/khadas) - The organisation behind the Edge2 (RK3588S) and Edge (RK3399) boards, hosting their firmware, kernels and tooling.
- [Pine64](https://github.com/pine64) - PINE64's organisation for its community-driven Rockchip hardware, including the RK3566 Quartz64 line and the RK3588 QuartzPro64.
- [LubanCat](https://github.com/LubanCat) - Embedfire's LubanCat board organisation, with SDK manifests and images for its RK3588, RK3576 and RK3566/3568 development boards popular in China.
- [Banana Pi](https://github.com/BPI-SINOVOIP) - Sinovoip's Banana Pi organisation, which includes Rockchip boards such as the RK3588-based BPI-W3 and RK3568 router boards.
- [ASUS Tinker Board Linux](https://github.com/TinkerBoard-Linux) - ASUS's Linux organisation for Tinker Board models built on Rockchip SoCs, with Yocto manifests and build infrastructure.
- [Turing RK1](https://turingpi.com/product/turing-rk1/) - An RK3588 compute module in the Jetson pin layout, made to slot into Turing Pi cluster boards with up to 32GB of RAM per node.
- [Luckfox Pico](https://github.com/LuckfoxTECH/luckfox-pico) - SDK and examples for Luckfox's tiny RV1106 and RV1103 camera boards, aimed at low-cost Linux IP-camera and vision projects.
- [ArmSoM](https://github.com/ArmSoM) - ArmSoM's organisation with documentation and system sources for its RK3588 Sige series and RK3576 boards and core modules.
- [Radxa ROCK 5B Images (radxa-build)](https://github.com/radxa-build/rock-5b) - The build repository producing Radxa's official downloadable system images for the ROCK 5B.
- [Orange Pi Build](https://github.com/orangepi-xunlong/orangepi-build) - Xunlong's image build system that assembles the official Linux images shipped for Orange Pi boards, including the RK3588S models.

## OS, Bootloader & Kernel

- [Armbian Build Framework](https://github.com/armbian/build) - The build system behind Armbian images, offering maintained mainline-leaning support for many RK3588, RK3576 and RK356x boards.
- [Ubuntu Rockchip (Joshua Riek) (archived)](https://github.com/Joshua-Riek/ubuntu-rockchip) - Widely used Ubuntu 22.04 and 24.04 images for RK3588 and RK3588S boards; the repository is now archived, so treat it as a frozen baseline.
- [DietPi](https://github.com/MichaIng/DietPi) - A lightweight Debian-based system with automated software installs, supporting a range of Rockchip boards from NanoPi, Orange Pi and Radxa.
- [Radxa Kernel](https://github.com/radxa/kernel) - Radxa's vendor kernel tree carrying board support and fixes for the ROCK product line.
- [Rockchip Linux Kernel](https://github.com/rockchip-linux/kernel) - Rockchip's vendor BSP kernel, the reference tree from which most board makers derive their own kernels.
- [U-Boot (upstream)](https://github.com/u-boot/u-boot) - Upstream U-Boot, which boots a growing list of RK3588, RK3576 and RK356x boards without vendor forks.
- [Rockchip U-Boot](https://github.com/rockchip-linux/u-boot) - Rockchip's U-Boot fork aligned with its BSP releases, still referenced by many vendor SDKs.
- [Rockchip rkbin](https://github.com/rockchip-linux/rkbin) - The binary blobs every Rockchip boot flow needs, including DDR initialisation and trusted-firmware components per SoC.
- [EDK2 RK3588](https://github.com/edk2-porting/edk2-rk3588) - A UEFI firmware port for RK3588 boards that lets them boot standard ARM64 installers and operating systems like a small PC.
- [meta-rockchip (community)](https://github.com/JeffyCN/meta-rockchip) - A feature-rich Yocto layer for Rockchip platforms, notable for wiring up multimedia and graphics acceleration in custom builds.
- [meta-rockchip (Yocto Project)](https://git.yoctoproject.org/meta-rockchip) - The Yocto Project's own BSP layer for publicly available Rockchip boards, kept close to upstream kernel and bootloader versions.
- [Khadas Fenix](https://github.com/khadas/fenix) - Khadas's build environment that produces Ubuntu and Debian images for its boards, including the RK3588S-based Edge2.
- [OpenWrt (upstream)](https://github.com/openwrt/openwrt) - Upstream OpenWrt, whose rockchip target covers RK3568 and RK3588 networking boards such as the NanoPi R5 and R6 series.
- [OpenWrt Rockchip (quintus-lab)](https://github.com/quintus-lab/openwrt-rockchip) - Community OpenWrt builds packaged for Rockchip routers and boards, published as ready-to-flash firmware releases.
- [LibreELEC](https://github.com/LibreELEC/LibreELEC.tv) - The just-enough Kodi media-centre distribution, which builds Rockchip images as mainline kernel and video support mature.
- [Rockchip Android](https://github.com/rockchip-android) - The Android source organisation for Rockchip platforms; largely quiet in recent years, but still the reference layout for vendor Android trees.
- [Khadas Android Manifest](https://github.com/khadas/android_manifest) - The repo manifest tying together Khadas's Android sources for its boards, including the RK3588S Edge2.
- [Mesa](https://gitlab.freedesktop.org/mesa/mesa) - Upstream Mesa, home of the Panthor and Panfrost drivers that give RK3588 and RK356x GPUs open OpenGL and Vulkan support.
- [Collabora RK3588 Mainline Status](https://gitlab.collabora.com/hardware-enablement/rockchip-3588/notes-for-rockchip-3588/-/blob/main/mainline-status.md) - Collabora's running tracker of which RK3588 hardware blocks work in mainline Linux, U-Boot and Mesa, and which are still missing.

## RKNN, RKLLM & AI Toolchain

- [airockchip/rknn-toolkit2](https://github.com/airockchip/rknn-toolkit2) - Rockchip's main PC-side toolkit for converting and quantizing neural networks into RKNN format for current RK35xx and RV11xx NPUs.
- [rockchip-linux/rknn-toolkit](https://github.com/rockchip-linux/rknn-toolkit) - The first-generation RKNN conversion toolkit kept for older chips such as RK3399Pro and RK1808 that Toolkit2 does not cover.
- [airockchip/rknn3-toolkit](https://github.com/airockchip/rknn3-toolkit) - Rockchip's next-generation conversion toolkit aimed at its newer NPU generation beyond the RKNN2 device range.
- [airockchip/rknn-llm](https://github.com/airockchip/rknn-llm) - Rockchip's official stack for converting large language and vision-language models into RKLLM format and running them on the NPU.
- [rockchip-linux/rknpu2](https://github.com/rockchip-linux/rknpu2) - The second-generation NPU runtime SDK with the C API and libraries that load and execute RKNN2 models on the board.
- [leafqycc/rknn-cpp-Multithreading](https://github.com/leafqycc/rknn-cpp-Multithreading) - A C++ example framework that spreads RKNN inference across multiple threads to use several NPU cores at once.
- [swdee/go-rknnlite](https://github.com/swdee/go-rknnlite) - Go bindings for the RKNN Toolkit2 C API with worked examples covering detection and OCR models on RK35xx boards.
- [darkautism/rknn-rs](https://github.com/darkautism/rknn-rs) - Rust bindings over the RKNN runtime so Rust programs can load and run models on Rockchip NPUs.
- [darkautism/rkllm-rs](https://github.com/darkautism/rkllm-rs) - Rust bindings for the RKLLM runtime for embedding NPU language-model inference in Rust applications.
- [happyme531/ztu_somemodelruntime_ez_rknn_async](https://github.com/happyme531/ztu_somemodelruntime_ez_rknn_async) - An asynchronous Python runtime for RKNPU2 with an ONNX-Runtime-style interface and multi-core scheduling.
- [heyongxin233/YOLO-Pruning-RKNN](https://github.com/heyongxin233/YOLO-Pruning-RKNN) - A workflow that prunes YOLO models before RKNN conversion to trade a little accuracy for faster NPU inference.
- [daedaluz/rknn-docker](https://github.com/daedaluz/rknn-docker) - Ready-made Docker images that package the RKNN conversion and runtime environment so it can be used without a local install.
- [Hanzo-Huang/rkllm-docker](https://github.com/Hanzo-Huang/rkllm-docker) - A Docker setup for running RKLLM language models on RK3588 boards without manually assembling the runtime libraries.
- [GatekeeperZA/RKLLM-API-Server](https://github.com/GatekeeperZA/RKLLM-API-Server) - An OpenAI-style API server backed by RKLLM that can also pair a vision encoder with the language model for multimodal requests.
- [huonwe/rkllm_openai_like_api](https://github.com/huonwe/rkllm_openai_like_api) - A lightweight server that exposes an RKLLM model through endpoints shaped like the OpenAI API for easier client integration.

## Models & Deployment

- [airockchip/rknn_model_zoo](https://github.com/airockchip/rknn_model_zoo) - Rockchip's official collection of converted models and runnable Python and C demos spanning detection segmentation OCR face and speech tasks.
- [airockchip/rknn3-model-zoo](https://github.com/airockchip/rknn3-model-zoo) - The companion model collection for the RKNN3 generation with conversion scripts and inference examples for its supported tasks.
- [airockchip/ultralytics_yolov8](https://github.com/airockchip/ultralytics_yolov8) - Rockchip's fork of Ultralytics YOLOv8 adjusted so its detection head exports cleanly for RKNN conversion and quantization.
- [airockchip/ultralytics_yolo11](https://github.com/airockchip/ultralytics_yolo11) - Rockchip's fork of YOLO11 prepared for exporting RKNN-friendly models for the current NPU range.
- [airockchip/yolov5](https://github.com/airockchip/yolov5) - Rockchip's maintained YOLOv5 fork whose export path is tuned for conversion to RKNN and deployment on its NPUs.
- [Qengineering/YoloV8-NPU](https://github.com/Qengineering/YoloV8-NPU) - A C++ YOLOv8 implementation built around the RKNN runtime for RK3566 RK3568 and RK3588 boards such as Rock 5 and Orange Pi 5.
- [Qengineering/YoloV5-NPU](https://github.com/Qengineering/YoloV5-NPU) - A C++ YOLOv5 deployment for Rockchip NPUs that includes the conversion notes and post-processing needed to run it on the board.
- [wzxzhuxi/rknn-3588-npu-yolo-accelerate-saturated](https://github.com/wzxzhuxi/rknn-3588-npu-yolo-accelerate-saturated) - A YOLO acceleration project for RK3588 that pipelines work across all three NPU cores to push detection throughput higher.
- [LuckfoxTECH/luckfox_pico_rknn_example](https://github.com/LuckfoxTECH/luckfox_pico_rknn_example) - Luckfox's official RKNN examples for its RV1106 Pico boards showing small vision models running on a 0.5 TOPS NPU.
- [Qengineering/Qwen3-VL-2B-NPU](https://github.com/Qengineering/Qwen3-VL-2B-NPU) - A port of the Qwen3-VL 2B vision-language model that pairs an RKNN vision encoder with an RKLLM decoder on RK3588.
- [Qengineering/SmolVLM2-500M-NPU](https://github.com/Qengineering/SmolVLM2-500M-NPU) - A compact SmolVLM2 vision-language model packaged to answer questions about images entirely on the RK3588 NPU.
- [zyp0424/Qwen-Chat-Assistant](https://github.com/zyp0424/Qwen-Chat-Assistant) - A fully local voice-and-vision chat assistant for RK3588 that feeds camera frames through an RKNN vision model into an RKLLM Qwen3 model, with wake-word, speech recognition and synthesis stages.
- [NotPunchnox/rkllama](https://github.com/NotPunchnox/rkllama) - An Ollama-style server and client that runs RKLLM models on the NPU of RK3588 and RK3576 boards instead of the CPU.
- [kyshipit/eai-rk3588](https://github.com/kyshipit/eai-rk3588) - A plugin-based edge AI platform for RK3588 that drives a multi-threaded vision pipeline (RKNN YOLO and SCRFD) alongside RKLLM dialogue and speech synthesis from one YAML configuration.
- [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) - The widely used GGUF inference engine that many RK3588 owners run on the board's CPU cores as the flexible fallback next to RKLLM.
- [mlc-ai/mlc-llm](https://github.com/mlc-ai/mlc-llm) - A compiler-based LLM deployment framework that can target mobile GPUs such as the Mali GPU on RK3588 boards.
- [k2-fsa/sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) - An offline speech toolkit for recognition synthesis and diarization that includes support for running models on Rockchip NPUs.
- [jianglu/whisper_RK3588](https://github.com/jianglu/whisper_RK3588) - A Whisper speech-recognition port that runs an INT8 RKNN version of the model on the RK3588 NPU.
- [marty1885/paroli](https://github.com/marty1885/paroli) - A streaming text-to-speech server built on Piper that can optionally move part of its workload onto the RK3588 NPU.
- [anguoyang/rk-bench](https://github.com/anguoyang/rk-bench) - A set of standardized benchmark results for public RKNN models measured on RK3588 hardware.

## Multimedia

- [rockchip-linux/mpp](https://github.com/rockchip-linux/mpp) - Rockchip's official userspace media framework that talks to the VPU for hardware video encoding and decoding across its SoC family.
- [airockchip/librga](https://github.com/airockchip/librga) - Userspace library for the RGA 2D accelerator that handles image scaling, rotation, cropping and pixel-format conversion on Rockchip chips.
- [nyanmisaka/ffmpeg-rockchip](https://github.com/nyanmisaka/ffmpeg-rockchip) - FFmpeg fork that wires in rkmpp codecs and rkrga filters so transcoding jobs can stay on RK3588-class video hardware.
- [jellyfin/jellyfin-ffmpeg](https://github.com/jellyfin/jellyfin-ffmpeg) - Jellyfin's FFmpeg build carrying the full Rockchip transcoding pipeline, including rkmpp codecs, RGA scaling and tone-mapping support.
- [Jellyfin Rockchip VPU guide](https://jellyfin.org/docs/general/post-install/transcoding/hardware-acceleration/rockchip/) - Official Jellyfin documentation walking through RKMPP hardware transcoding setup and codec support on RK3588 and RK3588S boards.
- [libcamera-org/libcamera](https://github.com/libcamera-org/libcamera) - GitHub mirror of the libcamera stack, which ships an RkISP1 pipeline handler and IPA for cameras on Rockchip ISP1 hardware.
- [Kwiboo/linux-rockchip](https://github.com/Kwiboo/linux-rockchip) - Mainline-oriented kernel fork tracking DRM display and video-decoder enablement work for recent Rockchip platforms.
- [corenel/gstreamer-rga](https://github.com/corenel/gstreamer-rga) - Small GStreamer plugin that exposes the Rockchip RGA block so pipelines can offload image resizing and format conversion.
- [numbqq/rkaiq-rockchip-debs](https://github.com/numbqq/rkaiq-rockchip-debs) - Debian packaging for Rockchip's rkaiq camera tuning and 3A server components aimed at RK356x and RK3588 systems.
- [anguoyang/onvif-scan](https://github.com/anguoyang/onvif-scan) - Discovers ONVIF cameras on a local network and inventories their device information, media profiles and stream URIs into JSON and HTML reports.
- [JeffyCN/libv4l-rkmpp](https://github.com/JeffyCN/libv4l-rkmpp) - Plugin that presents Rockchip MPP codecs through a V4L2 interface so Chromium can hand browser video work to the VPU.
- [woodyst/rockchip-vaapi](https://github.com/woodyst/rockchip-vaapi) - VA-API backend that routes standard Linux video acceleration calls into MPP on RK3588 hardware.
- [tsukumijima/libmali-rockchip](https://github.com/tsukumijima/libmali-rockchip) - Debian packaging and mirror of the Mali userspace GPU driver used by Rockchip display and graphics stacks.
- [armsurvivors/kodi-rockchip-deb](https://github.com/armsurvivors/kodi-rockchip-deb) - Packaged Kodi builds for Armbian on Rockchip that can use either vendor-kernel rkmpp or mainline V4L2 request decoding.

## Development Tools

- [rockchip-linux/rkdeveloptool](https://github.com/rockchip-linux/rkdeveloptool) - Rockchip's open-source USB flashing command for Linux and macOS that writes loaders and images to devices in Maskrom or Loader mode.
- [xboot/xrock](https://github.com/xboot/xrock) - Cross-platform Maskrom utility for Rockchip SoCs that can dump, erase, and write flash and inspect DDR and chip information.
- [Radxa rkdeveloptool documentation](https://docs.radxa.com/en/zero/zero3/low-level-dev/rkdeveloptool) - Radxa's documentation for rkdeveloptool, explaining it as the open-source counterpart of upgrade_tool with Maskrom flashing examples.
- [KiwiPi RKDevTool guide](https://kiwipi.com/blog/rkdevtool/) - Vendor guide to downloading RKDevTool and using its Windows interface to flash full firmware packages or single partitions.
- [ThomasKaiser/sbc-bench](https://github.com/ThomasKaiser/sbc-bench) - Shell benchmark suite for single-board computers that checks clocks, thermals and storage behaviour, widely used to validate RK3588 boards.
- [anguoyang/rk-edge-doctor](https://github.com/anguoyang/rk-edge-doctor) - Diagnostics CLI for Rockchip boards that reports board health, checks RKNN models for CPU fallback and validates RTSP camera streams.
- [anguoyang/rk-deploy](https://github.com/anguoyang/rk-deploy) - Packages RKNN applications into versioned bundles and deploys them to Rockchip boards as systemd services over SSH, with rollback and fleet status checks.
- [orangepi-xunlong/wiringOP](https://github.com/orangepi-xunlong/wiringOP) - WiringPi-style C library adapted by Xunlong for GPIO and peripheral access on Orange Pi boards, including Rockchip-based models.
- [brgl/libgpiod](https://github.com/brgl/libgpiod) - C library and command-line tools for the Linux GPIO character device, the modern way to drive pins on Rockchip boards.
- [rm-hull/OPi.GPIO](https://github.com/rm-hull/OPi.GPIO) - Python GPIO package for Orange Pi boards that offers an RPi.GPIO-compatible interface on models built around Rockchip SoCs.
- [vsergeev/python-periphery](https://github.com/vsergeev/python-periphery) - Python library that reaches GPIO, I2C, SPI and serial ports through plain Linux interfaces, handy for peripheral work on RK boards.
- [tio/tio](https://github.com/tio/tio) - Minimal serial terminal program commonly used to sit on the UART debug console that Rockchip boards expose.
- [gahingwoo/RKDevelopTool-GUI](https://github.com/gahingwoo/RKDevelopTool-GUI) - Desktop graphical front end for Rockchip firmware flashing and partition tasks on macOS and Linux.
- [jjm2473/rktool-webusb](https://github.com/jjm2473/rktool-webusb) - Browser-based port of rkdeveloptool using WebAssembly and WebUSB to communicate with Rockchip devices in flashing modes.

## Community, Docs & Learning

- [Rockchip Open Source Document](https://opensource.rock-chips.com/) - Rockchip's own open-source wiki gathering TRMs, datasheets, board notes and software guides organised by SoC.
- [Radxa Documentation](https://docs.radxa.com/) - Radxa's maintained documentation centre with getting-started guides, OS installation and accessory tutorials for its Rockchip boards.
- [Radxa Community Forum](https://forum.radxa.com/) - Radxa's public support forum where users and staff troubleshoot Rock, Zero and CM series boards in the open.
- [Orange Pi Official Site](https://www.orangepi.org/) - Orange Pi's official site linking per-board manuals, schematics, tools and OS images for its RK3588 and RK3566 boards.
- [Firefly Wiki](https://wiki.t-firefly.com/en/ROC-RK3588-PC/started.html) - Firefly's product wiki documenting setup, SDK builds and peripheral configuration for its RK3588, RK3576 and RK3568 boards and modules.
- [FriendlyElec Wiki](https://wiki.friendlyelec.com/wiki/index.php?title=NPU) - FriendlyElec's wiki covering NanoPi and NanoPC setup plus practical RKNN and RKLLM walkthroughs for RK3576 and RK3588 boards.
- [Armbian Community Forums - Rockchip](https://forum.armbian.com/forum/85-rockchip/) - The Rockchip section of the Armbian forums, where mainline and vendor-kernel issues on community boards are worked through publicly.
- [PINE64 Wiki - ROCKPro64](https://wiki.pine64.org/index.php?title=ROCKPro64) - PINE64's community wiki documenting its Rockchip boards such as ROCKPro64 and Quartz64, from board layouts to software releases and datasheets.
- [Khadas Docs - Edge2](https://docs.khadas.com/products/sbc/edge2/start) - Khadas documentation for the Edge series, covering installation, firmware, device-tree overlays and NPU topics for the RK3588S-based Edge2.
- [awesome-RK3588 (choushunn)](https://github.com/choushunn/awesome-RK3588) - Another community-maintained list focused specifically on RK3588 resources, maintained independently of this list.
- [Jeff Geerling - RK3588 Writing](https://www.jeffgeerling.com/tags/rk3588) - Jeff Geerling's RK3588-tagged posts collecting his hands-on testing and commentary on Rockchip boards such as the Rock 5 series.
- [CNX Software - Rockchip RK35xx](https://www.cnx-software.com/category/processors/rockchip-rk35xx/) - CNX Software's RK35xx category tracking new Rockchip boards, modules and software developments as they are announced.
- [linux-rockchip Mailing List](http://lists.infradead.org/mailman/listinfo/linux-rockchip) - The infradead mailing list where upstream kernel patches and reviews for Rockchip platforms are discussed.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). In short: one line per entry (name + link + one-sentence description), the link must be live, and the project must be directly relevant to Rockchip platforms and either active in the last 12 months or a stable official baseline.

---

The list itself is released under [CC0 1.0](LICENSE) (public domain); linked projects keep their own licenses.
