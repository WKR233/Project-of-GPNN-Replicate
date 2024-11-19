# Project-of-GPNN-Replicate
PKU Cognitive Reasoning Project of GPNN
## Original Project
Link: https://github.com/SiyuanQi-zz/gpnn
也可以直接下载我们的代码库。
## Problems:
1. 原项目过于老旧:
   ```
   "This repository is developed under CUDA8.0 and pytorch3.1 in python2.7"
   ```
   因此，代码不能跑通，且依赖库也需要降低版本，需要使用conda，即使这样也可能有无法获取到的包。例如，原项目提供的古早版本的pytorch链接已经失效。
2. 数据集的问题
   原项目提供的Google Drive链接已经失效，也就意味着无法下载tmp文件夹（其中有weights和dataset）。那么数据只能手动下载。目前找到的数据有VCOCO和Hico，未能找到CAD120，而且也不能保证数据格式符合原代码的需求。
## Tasks
0. 看论文。
1. 研究Github的配置和提交代码，注意不要覆盖主分支。
2. 尝试下载代码，配置环境。
3. 寻找数据集。
4. 如果无法跑通原代码，需要手动改写到支持python>=3.7。
