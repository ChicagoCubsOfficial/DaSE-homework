**项目**
- 多模态情感分析
**SETUP**
- This implementation is based on Python 3. To run the code, you need the following dependencies:

torch==1.10.0
torchvision==0.11.0
numpy==1.19.2
pandas==1.1.5
scikit-learn==0.24.2
matplotlib==3.1.1
Pillow==8.0.1
tqdm==4.64.0
chardet==4.0.0
To install all required dependencies, you can simply run the following command:

   pip install -r requirements.txt
   
**项目介绍**
- 本实验旨在设计一个多模态融合模型
- 通过文本和图像数据的联合学习
- 进行情感分类任务（positive, neutral, negative）
- 同时通过消融实验验证单模态和多模态的性能差异。
**文件结构**
- 文件夹里含有一份实验报告。
- 代码文件夹
- 文件夹中包含代码、测试集结果文件。
- 代码按照改变参数进行划分，划分的参数和代码内容将在代码文件夹名称上显示。（例如，名为“学习率”的文件夹里就是测试学习率所需要的代码）
- 测试集结果文件在名称上体现内容（例如epoch=30，就是改变epoch并等于30的代码输出的结果文件），当然，也可以在代码的输出文件里看到每段代码对应的测试集接过文件（csv）。
- 测试集中有一个csv是最优结果，已在标题上说明，查看结果就查看此csv即可。
- requirements.txt #项目所需的python软件包
- README.md #项目文档
**环境要求**
- 需要的python软件包在'requirements.txt'中列出，您可以通过txt中进行挑选安装。
**运行程序**
- 依照给定requirements环境。
- 运行程序。
- 结合实验报告，进行实验结果的查看、考证、理解。
