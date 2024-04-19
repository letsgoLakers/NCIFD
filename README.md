# NCIFD:National Culture Large Language Model Fine-Tuning Dataset
NCIFD(National Culture Instruction-Following Dataset)是一个面向大模型的民族文化微调数据集，其中包含了151,159条数据，涵盖建筑、服饰、工艺、饮食、礼仪、语言、习俗七大领域的内容。

NCIFD数据集的构成主要分为两部分通过Self-Instruct框架构建的NCSI和Self-QA框架构建的NCQA。我们收集整理了《中国民族百科全书》、《中国服饰大典》等18本民族文化相关书籍，通过构建prompt利用大语言模型生成QA对并对生成的QA对进行质量筛查，从问题的清晰度、答案的完整性、准确性和明确性，以及问答对内容整体的独立性进行评估，将内容质量差的回答进行重写，最后得到NCSQ(National Culture Self-QA)数据集。利用整理的民族文化书籍，构建了包含饮食、礼仪、语言、习俗等七大领域的民族文化种子集NCSC(National Culture Seed Collection)，利用该种子的引导性通过Self-Instruct框架，利用大语言模型生成数据集，并对生成的数据进行质量筛查，最后得到NCSI(National Culture Self-Instruct)数据集

## 声明
为了进一步推动民族文化事业在大语言模型领域的发展，并满足该领域相关研究人员的数据需求，我们选择将NCIFD的一部分数据开放供研究使用。
该开放数据集包含10,000条数据，均匀涵盖了建筑、服饰、工艺、饮食、礼仪、语言、习俗等七个领域。其中NCQA包含8,000数据，NCSI包含2,000条数据。
公开数据集仅供学习研究之用。如果您打算在商业场景中使用，请联系作者获得许可，并在得到作者同意后使用相关语料。

## 文件说明
- NCIFD：调整好格式的数据集文件

我们的数据集以JSON 格式存储。每条数据包含指令（instruct)、补充信息（input)和回答结果（ouput)。


## 联系方式
电子邮箱：tracy.yuan.sun@gmail.com

