### 视频行为分析系统 v3

* 作者：北小菜 
* 官网：http://www.beixiaocai.com
* 邮箱：bilibili_bxc@126.com
* QQ：1402990689
* 微信：bilibili_bxc
* 哔哩哔哩主页：https://space.bilibili.com/487906612
* v1版本开源地址 https://gitee.com/Vanishi/BXC_VideoAnalyzer_v1
* v2版本开源地址 https://gitee.com/Vanishi/BXC_VideoAnalyzer_v2
* v3版本安装包下载地址 https://gitee.com/Vanishi/BXC_VideoAnalyzer_v3
* v4版本安装包下载地址 https://gitee.com/Vanishi/xcms

### v3.x 获取源码
* v3.x版本源码购买地址（淘宝） https://item.taobao.com/item.htm?id=746326947806
* v3.x版本源码购买地址（闲鱼） https://h5.m.goofish.com/item?id=744350097882
* 大家如果看到其他任何商家出售v3源代码，希望能够去举报，均是非法行为。后续将会对获取v3升级版本的源码，提高门槛，相信那些非法出售的商家可很难通过升级门槛，进而无法向用户提供升级版本。

### v3.46特别说明
* v3.46引入了视觉多模态大模型MiniCPM-o，由于MiniCPM-o的模型文件比较大，因此单独放在了网盘中，需要体验该功能的用户请前往网盘下载模型
* 【夸克网盘】模型下载地址：https://pan.quark.cn/s/de19d10e04a4
* 【百度网盘】模型下载地址：https://pan.baidu.com/s/1WZ6p3_MdCkeHlEA0pLRmMQ?pwd=xcxc
* 下载ggml-model-Q4_K_M.gguf和mmproj-model-f16.gguf，下载后分别拷贝至Analyzer/models目录下


### 视频行为分析系统各版本介绍
| 版本号 | 介绍 |
| :----: | :----: |
| v1.0  | [查看v1.0介绍视频](https://www.bilibili.com/video/BV1dG4y1k77o) |
|   | [查看v1.0源码第1讲介绍视频](https://www.bilibili.com/video/BV1L84y177xc) |
|   | [查看v1.0源码第2讲介绍视频](https://www.bilibili.com/video/BV1984y1L7zB) |
| v2.0  | [查看v2.0介绍视频](https://www.bilibili.com/video/BV1CG411f7ak) |
| v3.0  | [查看v3.0介绍视频](https://www.bilibili.com/video/BV1Xy4y1P7M2) |
|   | 主要新增支持C++版openvino算法推理功能/后台管理全面升级 |
| v3.1  | [查看v3.1介绍视频](https://www.bilibili.com/video/BV1F64y1L7dq) |
|   | 主要新增支持C++版nvidia/tensorrt算法推理功能 |
| v3.2  | [查看v3.2介绍视频](https://www.bilibili.com/video/BV12g4y167u2) |
|   | 主要新增兼容Linux/intel/openvino |
|   | 【v3.2安装包下载链接】：https://pan.quark.cn/s/b8989d2cc312 |
| v3.3  | [查看v3.3介绍视频](https://www.bilibili.com/video/BV1pK421h74U) |
|   | 支持Windows/Linux + intel + openvino |
|  | 主要新增支持摄像头管理模块，升级播放器插件模块 |
|  | 【v3.3安装包下载链接】：https://pan.quark.cn/s/b8989d2cc312 |
| v3.40  | [查看v3.40介绍视频](https://www.bilibili.com/video/BV1tH4y1G775) |
|   | 支持Windows/Linux + 不限 + api |
|   | 主要新增支持API类型的算法调用模块，新增支持C++版dlib库 |
| v3.41  | [查看v3.41介绍视频](https://www.bilibili.com/video/BV1hJ4m1w7tP) |
|   | 支持Windows/Linux + intel,amd,rk3588等 + onnxruntime |
|   | 主要新增支持onnxruntime推理引擎，优化性能，onnxruntime可以支持AMD，RK3588等硬件 |
|   | 【v3.41安装包下载链接】：https://pan.quark.cn/s/b8989d2cc312 |
| v3.42  | [查看v3.42介绍视频](https://www.bilibili.com/video/BV1rf421v74R) |
|   | 支持Windows/Linux + intel,amd,rk3588等 + onnxruntime |
|   | 主要新增支持基于cnnlstm视频分类网络的算法模型 |
| v3.43  | [查看v3.43介绍视频](https://www.bilibili.com/video/BV14a2NYJE6i) |
|   | 支持Windows/Linux + intel,amd + openvino,onnxruntime  |
|   | 主要新增人员管理，人脸检测，人脸特征提取，人脸识别，无感考勤等功能 |
|   | 【v3.43安装包下载链接】：https://pan.quark.cn/s/b8989d2cc312 |
| v3.44  | [查看v3.44介绍视频](https://www.bilibili.com/video/BV14a2NYJE6i) |
|   | 新增支持rk3588/rk3576/rknpu推理加速/rga加速，详细介绍编译和部署全过程  |
| v3.45  | [查看v3.45介绍视频](https://www.bilibili.com/video/BV1wfCBYFEVD) |
|   | 主要支持openvino/tensorrt/onnxruntime推理yolo，部署要求：设备必须包含支持CUDA12.0的英伟达显卡  |
| v3.46  | 发布于2025/02/05 |
|   | 最大的特点是引入了多模态视觉大模型，基于lamma.cpp推理  |
| v4.x  | [v4.x安装包下载](https://beixiaocai.yuque.com/org-wiki-beixiaocai-vo72oa/xcms/e05dce83e5129785b9f316978a14b896)  |


### 相关视频

* [C++调用Python，支持传递图片格式的数据，支持调用Python版AI算法模型，C++传递Mat格式的图片数据到Python](https://www.bilibili.com/video/BV1Vd4y1p7GE)
* [Ubuntu20.04编译v3.2版本视频](https://www.bilibili.com/video/BV1Z94y1u7u8)


### v1,v2,v3 主要区别
* （1）v1和v2算法模型推理仅支持Python版OpenVINO，v3支持C++版本OpenVINO，TensorRT，ONNXRuntime，v1和v2支持yolo5和ssd检测算法，v3则支持yolo8
* （2）v1和v2仅支持检测到目标就触发报警。v3则支持选择指定目标触发周界入侵报警。
* （3）v1和v2分析器模块和算法模块是独立的，是C++和Python两种语言分别开发的两个完全独立的模块，分析器模块调用算法模块的接口实现计算。v3的分析器模块和算法模块是合并在一起的，全部都是C++开发。
* （4）后台管理模块，新增了合成报警视频的管理功能，可以对报警视频进行增删改查，布控中的视频产生的报警视频会出现在这个功能中。同时在布控过程中，支持绘制布控周界区域和选择监测分类。


### 快速体验程序

#### Windows版启动运行
* 第一步下载程序：点击 "克隆/下载"按钮->下载ZIP
* 第二步运行程序：下载ZIP后，解压ZIP，双击 VideoAnalyzer.exe启动程序，观察窗口提示如果没有报错，即表示启动成功
* 第三步打开程序：在浏览器输入 http://127.0.0.1:9001 系统默认账号 用户名：admin 密码：admin888
* 第四步停止程序：关闭启动程序窗口即可

#### Linux版启动运行
* 需要获取源码后编译运行

### 软件截图

<img width="720" alt="控制面板" src="https://gitee.com/Vanishi/images/raw/master/BXC_VideoAnalyzer_v3/v3.3/1.png">
<img width="720" alt="添加摄像头" src="https://gitee.com/Vanishi/images/raw/master/BXC_VideoAnalyzer_v3/v3.3/2.png">
<img width="720" alt="报警视频管理" src="https://gitee.com/Vanishi/images/raw/master/BXC_VideoAnalyzer_v3/v3.3/3.png">
<img width="720" alt="算法管理" src="https://gitee.com/Vanishi/images/raw/master/BXC_VideoAnalyzer_v3/v3.3/4.png">
<img width="720" alt="布控管理" src="https://gitee.com/Vanishi/images/raw/master/BXC_VideoAnalyzer_v3/v3.3/5.png">
<img width="720" alt="编辑布控" src="https://gitee.com/Vanishi/images/raw/master/BXC_VideoAnalyzer_v3/v3.3/6.png">
<img width="720" alt="播放算法视频流" src="https://gitee.com/Vanishi/images/raw/master/BXC_VideoAnalyzer_v3/v3.3/7.png">




