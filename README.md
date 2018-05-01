# Keras实现基于字符的语言模型

在阿里云p100 gpu实例上训练了大约一小时，已经可以生成句子，效果不是很理想。

发现keras实现NPL，代码确实很难写。

数据集下载地址：[百度云盘](https://pan.baidu.com/s/1LM3yIf0yFTH4xShfSDbZnA)

下载后解压到项目目录下即可

用keras训练后的权重下载地址：[百度云盘](https://pan.baidu.com/s/1W-kGx3chSoW7iccHx7R8QA)

下载后放到项目目录下即可

# Tensorflow实现基于词汇的语言模型

tensorflow_imp_vcab 目录下。

网络结构是：首先一个嵌入层，然后的两层LSTM，最后是softmax分类器。

这个网络嵌入层和lstm一起训练，所以很难训练，最后放弃了。也许用预训练的嵌入层效果会好一些。

# Tensorflow实现基于字符的语言模型

tensorflow_imp_char 目录下。

没有词嵌入层，直接是两层LSTM，最后是softmax分类器。

在阿里云p100竞价实例上训练，这个网络最后的效果还是不错的。

### 调出来的一些作品：

中国梦，万户兴隆兴国运；和谐社，千家福业展宏图。
中国梦想春风壮；百代雄风国梦强。
醉酒，一杯春水；花香，一片红尘。
醉酒，一盏春风来晚去；醉人，万家风雨梦无边。
醉酒，一壶一盏红花好；诗情，万里风霜柳絮情。
不知花落香千里；自有人间气万千。
长城不尽千山月；大海长存一片天。
昨夜西风，一枝红叶秋风里；初回北海，一曲东风北海中。
长天不见云中月；海水常来月下花。
长天高照千秋业；万古长留万古诗。
树下清风留古地；心前明月自无心。
玉树银花，一缕花香香玉液；黄山碧水，一声春色耀千秋。
叶落红尘花似老；花开柳岸水无情。
叶落红枫秋不尽；人生月色梦如空。
玉兔归来，一片春花开紫蝶；金龙舞起，九州万福万家春。
叶绿花红花作笑；风光柳絮柳含红。
树色清香花自在；清心雅韵月常浓。
