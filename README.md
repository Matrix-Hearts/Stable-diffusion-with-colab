# Stable-diffusion-with-colab
Stable diffusion with colab

**直接点开colab的代码，下面的只是补充说明和链接**

## Step1:
https://github.com/camenduru/stable-diffusion-webui-colab
colab源码
使用1-5的包

https://civitai.com/
模型网站

进入colab
## Step2:
https://github.com/nolanaatama?tab=repositories
一些代码案例
来自油管nolanaatama

```!cp -r '/content/drive/MyDrive/stable-diffusion/Lora/.' '/content/stable-diffusion-webui/models/Lora'```
从云端下载整个文件夹

```!cp "/content/drive/MyDrive/our_LoRA_folder/OURLORAFILE1.pt" "/content/stable-diffusion-webui/models/Lora"```
单独复制某个文件

```!rm -r "/forder/."```
删除整个文件夹(不可恢复)

```!curl -Lo /content/stable-diffusion-webui/models/Lora/animeoutlineV3-000008.safetensors https://huggingface.co/nolanaatama/nmlnrtstyl/resolve/main/nmlnrtstyl.safetensors```
从网站上下载nmlnrtstyl模型，存到Lora并命名。

Linux和Shell的操作https://www.runoob.com/linux/linux-file-content-manage.html

## To Do List
1 学习在colab中上传文件到github，主要是咒语style.css
2 现在从云盘上复制文件后 代码还是运行不起来

