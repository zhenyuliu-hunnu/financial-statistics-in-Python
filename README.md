# 全部是 Python 代码的金融统计学课

> 人生苦短，我用 Python。

所有数据集已内置，不用再去下那个永远下不完的压缩包了。

部分代码由 AI 生成，运行没问题就不管了。

## 配置所需 Conda 环境

1. 用你任何可以做到的方式安装 Anaconda 或 miniconda

2. 将项目内的 `packages.txt` 和 `environment.yml` 保存到你知道路径怎么输入的位置

3. 进入命令行，创建新的名为 `lesson` 的 Conda 环境

```bash
conda create --name lesson python=3.8
```
4. 恢复环境配置
```bash
conda env update --name lesson --file <environment.yml 的路径>
```
5. 安装依赖包
```bash
conda install --name lesson --file <packages.txt 的路径>
```