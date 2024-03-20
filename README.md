# ChatGLM-6B-Fine-Tune

## 项目描述

本项目是一个大模型微调实践，通过部署清华开源的大语言模型ChatGLM，微调参数，准备个人数据集，对模型进行训练，打造一个使用起来更符合自身使用习惯的模型。以及学习和体验微调过程，对大语言模型有更加全面了解。

## 项目运行效果截图

<img src="https://github.com/LiuEhe/ChatGLM-6B-Fine-Tune/blob/main/img/img/1.jpg" width="400" height="220.5"><img src="https://github.com/LiuEhe/ChatGLM-6B-Fine-Tune/blob/main/img/img/2.jpg" width="400" height="220.5">
<img src="https://github.com/LiuEhe/ChatGLM-6B-Fine-Tune/blob/main/img/img/3.jpg" width="400" height="220.5">

## 功能
- 可与使用者进行交流对话。
- 详情请前往清华开源的[chatglm](https://github.com/THUDM/ChatGLM-6B)库。

## 依赖

- Python 3.10
- transformers  4.30.2
- bitsandbytes  0.39.1
- datasets
- !pip install -q git+https://github.com/huggingface/accelerate
- !pip install  -q git+https://github.com/huggingface/peft      使用最新版本非常重要，否则可能报错
- !pip install  -q git+https://github.com/lyhue1991/torchkeras 

## 使用

1. 将项目源码导入或者克隆到kaggle网站的notebook中。
2. 安装依赖
3. 请按书写的markdown有序运行。
4. webui部署，详情参考 开源大语言模型 [WebUI整合包 ChatGLM2-6B 和 WizardCoder-15B 中文对话和写代码模型] (https://www.bilibili.com/video/BV1jj411S7YD/?spm_id_from=333.337.search-card.all.click&vd_source=f0b7a51fdb322d20740f6c813143260c)


## 注意
- 运行chatglm模型，请务必确保所用库的版本号正确，避免运行失败问题。
- 采用kaggle，请进行手机认证，确保可以免费使用GPU（16G）资源。
- kaggle的主机磁盘仅19.5G，缓存区容量大，由于模型过大，请在最后部署在磁盘上，其余部署在缓存区中。
- 模型训练好后请上传至huggingface网站中。
- webui部署，请在webui整合包下载好后，将huggingface中自己微调的模型下载下来。放入models文件夹中。

