# AF-原子级特征提取软件
# Atomic Scalar Features Tools   
###  --A custom filled chemical formula characteristics of the real-time software


声明：本软件为学术交流所用，运行密码为ICQMSicqms，请勿以任何形式用于商业用途，所有学术用户可以使用，欢迎加入AF，提出修改意见和一起完善。  

①本软件写成简单实用的exe程序，可在Win系统上直接使用。  
②本软件为提取简单化学式特征使用，暂不支持-”化学式中有括号，水合物符号，电子价等符号参与的化学式“若有特殊需求可联系作者，联系方式见控制台。  
③特征维度的限制为1000维度，维度是自己定制的(维度跟随你的特征文件)，10000是每行最多的字符，可以使用我们提供的元素物理基本性质的特征文件，也可以自定义自己添加想要使用的特征。  
④元素物理基本性质的特征文件，以magpie.csv为例(“https://www.nature.com/articles/npjcompumats201628） ”在这个csv我们采集了magpie中给出的元素基本物理量，具体特征见magpe原文）,请严格参照magpie.csv的文件输入格式，并在进行填充之前更正csv文件的名字为：Fillfeature.csv。  
⑤确保Fillfeature.csv(特征文件)和data.csv(要求里面只有化学式这一列，无其他多余字符)与exe软件处在同一个文件夹中。  
⑥运行软件，输入ICQMSicqms，得到out.csv文件，即提取化学式特征完成。  
⑦仿照example中有输入案例，将exe复制入文件夹运行，得到out.csv文件。  
⑧注意，当data.csv文件中出现了Fillfeature.csv没有的特征无法进行提取时，我们使用常见的填0的办法进行填充，当出现异常数据如分母为0时，特征计为-1。  
⑨特征文件中的特征填充请使用数字，如有字符等，请先自行分类用数字进行表征。  
⑩各个版本的目的不同，S版及其个版本适用于无结构信息的特征提取，T1.0版本适用于钙钛矿ABX3体系，T2.0适用于任何具有结构信息(如VASP软件中使用的POSCAR)的结构特征提取。  


关于Fillfeature.csv，这些文件是从其命名的软件包中提取出来的，感谢他们的奉献。  
在使用自定义Fillfeature.csv的时候，请务必严格按照magpie.csv的格式，在自定义的特征文件中不允许出现数字之外的符号，如有s,p,d电子轨道等特征，请自行对其变成数字上的表述。  
欢迎联系，以完善ele仓库中可用的特征，联系方式为邮件，邮箱地址见软件控制台。  




Instructions for use:
Disclaimer: This software is used for academic communication, and the running password is ICQMSicqms. It is not allowed to be used for commercial purposes in any form. All academic users have the right to use it.  
①This software is written as a simple and practical exe program, which does not need other supporting environment, but can be used directly on the Win system.  
②The software is used to extract the characteristics of simple chemical formula, temporarily does not support -- "chemical formula with brackets, hydrate symbols, symbols such as electron valence to participate in the chemical formula" if you have special needs can contact the author, contact information see the console.  
③The limit of feature dimension is 1000, the dimension is customized (the dimension follows your feature file), 10000 is the most characters per line, you can use the feature file of the basic nature of element physics we provide, you can also customize to add the features you want to use.    
④elements characteristics of the basic characteristics of physical files to pay-per-tweet. CSV, for example ("https://www.nature.com/articles/npjcompumats201628) in the CSV" we collected the elements of the basic physical quantities given in the pay-per-tweet, specific characteristics of the original magpe), please strictly follow pay-per-tweet. CSV file input format, and corrected before populate CSV file name is: Fillfeature. CSV.  
⑤Ensure fillfeature.csv (feature file) and data.CSV (require only the column of chemical formula and no other redundant characters) in the same folder as EXE software.  
⑥Run the software, input ICQMSicqms, get out. CSV file, namely extraction of chemical formula characteristics.  
⑦Copy the input case in example, copy EXe into the folder to run, and get the out.csv file.  
⑧It is noted that when Fillfeature appears in data.CSV file. CSV features cannot be extracted, we use the common method of 0 to fill, when abnormal data such as the denominator is 0, the feature is calculated as -1.  
⑨Pet-feature Files feature padding please use Numbers, if there are characters, etc., please use Numbers for self-classification first.
The S version and its versions are applicable to feature extraction without structural information, T1.0 version is applicable to perovskite ABX3 system, and T2.0 version is applicable to any structural feature extraction with structural information (such as POSCAR used in VASP software).
Regarding Fillfeature.csv, these CSV files are extracted from its named software package, thanks for their dedication.
When using custom Fillfeature.csv, please be sure to strictly follow the magpie.CSV format. Symbols other than Numbers are not allowed to appear in custom feature files, such as s, P, D electron orbit and other features.  
Welcome to contact us to improve the features available in ele warehouse. Contact us by email. See the software console for email address.  
