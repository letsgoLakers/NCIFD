# NCIFD:National Culture Large Language Model Fine-Tuning Dataset
NCIFD(National Culture Instruction-Following Dataset)是由中央民族大学国家语言资源监测与研究少数民族语言中心构造的一个面向大模型的民族文化微调数据集，NCIFD数据集的构成主要分为两部分通过Self-Instruct框架构建的NCSI和Self-QA框架构建的NCQA。其中公开10,000条数据，涵盖建筑、服饰、工艺、饮食、礼仪、语言、习俗七大领域的内容。



## 声明
为了进一步推动民族文化事业在大语言模型领域的发展，并满足该领域相关研究人员的数据需求，我们选择将NCIFD的一部分数据开放供研究使用。
公开数据集仅供学习研究之用。如果您打算在商业场景中使用，请联系作者获得许可，并在得到作者同意后使用相关语料。

## 文件说明
- NCIFD：调整好格式的数据集文件
  
我们的数据集以JSON 格式存储。每条数据包含指令（instruct)、补充信息（input)和回答结果（ouput)。

具体例子如下：
   
    {
      
        "instruction": "根据输入中给定的节日，介绍其在中国少数民族中的庆祝方式和意义。",
      
        "input": "春节",
      
        "output": "春节是中国最重要的传统节日，也被称为农历新年。在中国少数民族中，春节有着不同的庆祝方式和意义。\n- 在汉族中，春节通常会进行大型家庭聚餐，赏花灯、放烟火等活动，并且会贴对联和挂红包等来祈求幸运和财富。\n- 在藏族中，春节被称为“扎西德勒”，意为“吉祥如意”。他们会穿上盛装，跳起特殊的舞蹈，同时还会举行马术比赛和射箭比赛。\n- 在傣族中，春节被称为“水节”，他们会在河边放生小龙虾，同时还会举行划龙舟比赛和打水仗等活动。\n总的来说，春节在中国少数民族中都具有团圆、祈福和欢乐的意义，是一种传承千年的文化传统。"
   
    }

## 联系方式
电子邮箱：tracy.yuan.sun@gmail.com

