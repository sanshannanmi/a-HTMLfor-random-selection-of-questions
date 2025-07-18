# a-HTMLfor-random-selection-of-questions
# 一、前置介绍
## 作用：
通过ai上传包含题目、答案和标题的题库文件和抽题的html文件，告诉ai一段话即可进行整合输出一个直接个性化能用的随机抽题网页。
## 无门槛：
不需要自己手动写代码，也不需要能看懂代码，只要会用deepseek或通义之类的ai，复制粘贴以及创建.txt文件并改后缀为.html。
还是不懂的话可以看我的[B站视频](https://www.bilibili.com/video/BV15oTuzDEvw/?spm_id_from=333.1387.homepage.video_card.click)
## 运用范围：
不限制学科只要你想，初中阶段会适合一点。我主要用于复习课记填空知识点，你可以任意开发问答和选择。
# 二、使用准备：
1. 首先，你应该向我的文件“循环系统”一样，准备一个**题库文件**。题库文件需要有明显可区分的标题、题目和答案，用来给ai提取题库内容。![0](https://github.com/user-attachments/assets/dd0c68e2-f94d-4c09-800c-4b2b9c1243b1)
2. 其次，你只需要将你的题库文件和项目里的**抽题小白版.html**文件一起点击**上传文件**传给ai，关闭深度思考。
3. 在输入栏，复制下列这段话，点击发送:![1](https://github.com/user-attachments/assets/bd998cf5-78d4-44d2-a7af-a4ca146a9332)
> 我想通过html文件实现随机抽题，请你将我给的题库中的标题、题目和答案对应填充到“抽题小白版.html”文件的let questions部分。其中将标题放到“新分类”中，question是题目，answer是答案。我需要直接复制代码到HTML文件中使用。目前我给的框架只有两个分类替换，但我的题库可能不止两个标题，有需要的话你自己增加。
***
4. 这时候deepseek会将修改好的核心代码给你，看一下题库识别是否正确就可以。
5. 接着，补充发送下面这句话，让ai给你完整的代码：
> 我需要你将整个html文件的代码给我，我不想替换，而是直接全文复制。
6. 然后就可以得到全部的代码了。![3](https://github.com/user-attachments/assets/c21fb223-8070-49eb-814d-ab760ff928c7)
# 三、让代码变成运行的网页(看不懂可以去网上找教程，很简单)
1. 在随便哪个位置，右键新建一个.txt文件，名字随意
2. 将代码粘贴进去并保存
3. 右键“重命名”文件，将其后缀改为.html，此时会有弹窗提示改变了文件格式，点击“YES”。![4](https://github.com/user-attachments/assets/b2c7ea46-a139-47c6-9be0-31954942b4ae)
4. 运行即可查看效果。
