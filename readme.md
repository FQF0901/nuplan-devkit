
```
详见：https://blog.csdn.net/qq_37795208/article/details/142530245
cd /home/fqf/fqf_folder/01_Git/nuplan-devkit

conda create --name nuplan python=3.9
conda activate nuplan
pip install -e .
pip install -r ./requirements.txt
pip install -r requirements_torch.txt【服务器貌似需要ssl证书，所以改用：pip install --trusted-host download.pytorch.org --trusted-host data.pyg.org -r requirements_torch.txt】

pip install aioboto3
pip install retry
pip install aiofiles
pip install bokeh==2.4.1
```
