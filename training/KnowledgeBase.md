# 扩充语料库的训练方法

经过上面分析，可以得出英语学习最关键的内容就是**语料库**，其次就是语法（识别引擎）。

**语料库并不只是词汇，训练学习方法也并非简单的背单词。**

如果通过听力识别器输入语料，首先我们要能**区分口音**，比如当前语料的英式发音、美式发音、澳洲发音、印度发音是什么样。之后就是一些**连读、弱读和重音变化规则**。通过口音、连读和重音等规则正确解析得到词句短语之后，开始**进入解析器流程**。我们需要知道其中**每个单词的多重含义**，将其含义一个个的匹配放入上下文语境结合重音等得到最准确的含义。这时还可能遇到一些词典里没有的**新词或者老词新意**，比如 “给力”、“呵呵” 或者各种歪曲解释的 “不可描述” 的成语等，这些都是人们新造或者赋予了新意思的词，这些词意词典并不一定会收录但广泛在一个圈子里使用和交流，这就涉及到文化、俚语、流行语等。此外**还需要用语法进行下一步解析**，比如时态、标点、语气、句型句式等。

经过上面流程才可以解析出比较准确的意思，**做出回应还要逆向再来一遍**。

首先你要按照一定逻辑和结构**梳理好你想表达的意图**。这一步其实跟语言无关，中文阅读理解能力好的人，英文只要看懂了阅读理解能力也会很强，有条理的人不只是说话有条理，做事情也会很有条理和逻辑性。想好表达之后你就要开始**从语料库抽取最符合你意图的词句，并按照合适的语法进行组装**，这时候就可以看出一个人语料库大小和水平。比如：表达我喜欢一个梳妆台，只有最基础语料库的我只能说出：我喜欢这个桌子上有镜子的东西。这时，看到这句话的人可能知道你想表达喜爱一张桌子和镜子的东西，但不知道具体是什么。如果语料库里有更庞大的名词库和程度形容词，就可以说出：这就是我梦寐以求的带有地中海风格雕刻、椭圆梳妆镜的梳妆台。看到这句话你脑子里应该可以出现这个梳妆台大体的样子吧。之后，你**还需要发音说出来**，先从语料库里抽取对应的词句声音，再结合略读、弱读、重读等规则控制舌头、喉咙肌肉发出来对应的声音，至此算是完成一次对话。

上面只是听力识别器，视力识别器大同小异，无非是识别各种字体、大小写、标点符号等，不再赘述。

---

**通过上面分析可以得知，语料库里的每个语料通常需要以下信息：**

* **多种口音的声音**，比如：英美澳印等。
* **不同词性和时态下，不同的发音和重音位置变化**，比如：`resume` 在名词下表简历，发音 [/ˈrez.ə.meɪ/](https://dictionary.cambridge.org/media/english/us_pron/e/eus/eus73/eus73812.mp3)，而动词表继续之前暂停的事情，发音 [/rɪˈzuːm/](https://dictionary.cambridge.org/media/english/us_pron/e/eus/eus73/eus73965.mp3)，如果你发错了声音，则会导致对方解读错误。
* **单词的多重含义**，比如：`current` 常见意思是形容词当下的，但实际上还有名词的 `水流、潮流` 等意思。曾经做阅读理解看到带有水流意思的句子一脸懵逼，没法用 `当下` 的意思来解释和理解这个句子。同样 `spring` 除了 `春天` 还有 `弹力、泉水` 等完全联想不到的意思。
* **同义词及其对比、反义词等**，因为你的回复可能需要否决或者加强观点，这些词可以帮助你更好更精准的表达。比如： `raise` 和 `rise` 有什么区别，什么场景下适用？还有 `under`、`beneath`、`underneath` 和 `below` 等，要怎么用。
* **语料相关的俚语、文化、衍生词等**。比如：`clump` 这个单词本意是草丛之类的意思，但是你可以搜下 Google 图片，<a href="../assets/clumped.jpg" target="_blank">形容词 clumped 还算正常</a>，但名词搜出来<a href="../assets/clump.jpg" target="_blank">完全变成了一种奇怪的生物</a>。因为这个单词正好是两个热门美国人物名字合起来的发音，所以老美虚构了一个人出来调侃。因此如果看到 twitter 上有这个单词，要多考虑下是不是在调侃政治人物。
* **相关的常见固定搭配和用法**。比如：`focus on` 和 `pay attention to` 区别以及介词的不同。
* **名词的单复数形态和动词的各种时态变形及其发音规则**。比如：`hair` 在不同词性下既可数又不可数，反过来说，也可以通过这个判断出此处 `hair` 要表达的意思。`s` 结尾通常有 `z`、`s` 和 `əz` 三个发音，`ed` 结尾也有 `d`、`t` 以及 `id` 等情况。`read` 更奇葩，过去式和过去分词都是 `read`，但是过去式发音变了，读作 `/red/`，换言之，需要通过这个发音来识别这个行为是过去发生的还是现在。

---

除了语料之外的语法，就靠单点专项突破，比如时态种类和规则、词性和句子组成结构以及时间和数字的组合规则和发音方法等等，这里不再赘述。

## 扩充语料库的训练方法实战

例如看到一个 `clump` 单词想要学习，可以这样做：

1. **第一遍开始认识单词：**
  * 通过 [Cambridge Dictionary](https://dictionary.cambridge.org/dictionary/english/clump) 查询单词意思，可以看到是否可数、各种**释义和对应的例句**、关联词和对比等等。[Merriam Webster](https://www.merriam-webster.com/dictionary/clump) 是美式在线字典，如有精力也可以作为知识补充，但是例句和界面不如 Cambridge Dictionary 好用。
  * 查看音标，尝试发音（需要先把音标练熟，参照下面教程），收听词典中给出的英式和美式的真人发音，看下自己的发音是否准确？哪里不对？是音标还是重音？练对为止。
  * 打开 [Forvo](https://forvo.com/word/clump/#en) 收听这个单词不同人的发音，可以尝试跟读以便录入自己的音频语料库。**也强烈推荐使用 [YouGlish](https://youglish.com/search/clump/us?)** ，它会搜索 Youtube 上面包含当前单词的视频，这样发音更贴合日常对话。
  * 打开 [Google Translate](https://translate.google.as/) 语音输入，尽量带上耳机或者用耳麦尝试发音，查看是否能稳定识别出当前单词。如果不能，请回到上面步骤，对 Google Translate 播放母语真人发音音频查看能否识别。如果母语真人发音可以识别，说明你的发音有问题，请重复上面步骤调整发音到可以识别为止。
  * 打开 Google 搜索，<a href="../assets/clump-google.jpg" target="_blank">输入当前单词 + vs 即可看到近义词和易混淆词汇</a>，搜索查看相关对比。
  * 不是特别抽象的单词，可以打开 Google 图片搜索进行搜索，通过图像加深记忆。我用图片搜索 `clump` 时，才发现了<a href="../assets/clump.jpg" target="_blank">两位候选人的合体</a>的意思。再举一个例子，`bay` 和 `gulf` 在词典里都有海湾的意思，那它们之间有什么区别吗？用 Google 图片搜索一下你就可以发现，<a href="../assets/gulf-bay.jpg" target="_blank">`gulf` 要比 `bay` 大的多</a>。
  * 将单词以及有趣的发现记录在 [Anki](https://apps.ankiweb.net/) 里面，<a href="../assets/add-to-anki.jpg" target="_blank">只需要点击 Add 并添加单词即可，也可以在下方多加一些注释</a>，可繁可简不需要花太多时间。将在后面的 QA 部分解释为什么要用 Anki。
2. **第二遍在 Anki 里面复习，看到单词尝试发音识别，尝试回忆相关的意思、用法以及图像，尽可能的回忆。如果感觉没问题那么就点击 Good 或者 Easy，否则就选择 Again 或者 Hard。如果掌握不好，请重复第一遍步骤加深记忆。**
3. 第三遍重复第二步。
4. 第 N 遍，已经基本掌握。

每隔一段时间应该导出一份单词列表，放在 [Danci88](http://www.danci88.com) 上面进行听写。这个工具虽然比较简陋，但是非常实用。通过听写可以看出对这个单词的掌握程度，如果你脑子瞬间出现这个单词则表示掌握了。

**值得注意的是，上面步骤是相对完整的学习步骤，在实际学习过程中针对不同类别的单词应该可繁可简**。比如我在 Anki 建立了 7 个语料库，分别是：

* **发音错题本**：第一眼看到单词发出的声音无法识别或者与实际发音不符。**这类单词要注重音标、发音识别、多语音辨音**等，要用 Google 翻译来识别测试。
* **听力单词本**：在听写或者听力时，没有听出并写出的词句。**这类单词要注重发音和听写训练。**
* **常见名词本**：例如国家、地区等。**这类单词只需注重发音和听力识别即可**，常见单词注重拼写以及了解相关文化历史，不常见甚至不需要去学怎么拼写，毕竟写的机会不多，而且可以轻易搜到。
* **拼写错题本**：这类单词认识意思、会读，但是拼写错了。其实很多常见的单词，都觉得习以为常，但真正让你拼写的时候却拿捏不准。**这类单词就要注重拼写和听写**，以及多在键盘上敲打建立肌肉记忆。
* **新单词本**：这个就是遇到的比较重要的新单词，需要按照上面流程进行学习。这类单词就是重复刷记忆。
* **熟词生僻意思单词本**：这个主要记录一些很熟悉的词的生僻意思。比如 `champion` 比较常见的是名词冠军，但其实也有动词捍卫的生僻意思。
* **连读训练本**：这个是在练习口语阅读或者复述句子时，觉得很绕口的词句。比如 `the very idea of a police force was seen as foreign as that is` 这句话。**这类语料要注重断句、重读、声调变化和气息控制，重复读到流畅即可。**

上面步骤好像很多，而且需要记忆的内容量好大，有什么技巧来快速稳定的记忆吗？

## 记忆单词、语料库唯一的银弹：重复训练

时间回到初中，我英语不是很好，路上遇到同行英语老师便问道学习英语有什么技巧吗？老师微笑说：**Practice、Practice and Practice**，我却不以为然，这应该是我走过的最大的弯路。

高中之后，为了提升记忆力，我做了很多尝试和训练。比如七田真的《超右脑照相记忆法》以及《魔术记忆》等，经常对着曼陀罗图片看、上学放学路上眨眼记车牌、瞬间记住一串手机号以及按照《魔术记忆》的联想技巧记忆一些东西，希望能练到过目不忘。看起来是挺神奇挺有效的，尤其是《魔术记忆》里面的“联想记忆法”、“定桩记忆法”、“记忆宫殿记忆法”等，随便一个人都可以快速记忆一串不相关的关键词。

正是如此，**这类英语学习速记技巧也成了各种网上学习平台割韭菜的视频教程**，还卖价不菲。通过几个单词联想让试看的观众觉得神奇，从而脑热买下教程，大部分人买了不看，即使看了练了也没啥用。

作为过来人回头来看，这完全是弯路，这些**速记方法大多是表演性质的，根本没法固化成自己的能力**。请你回忆一下，你为什么认识 `commit` 这个单词？是因为通过什么其他单词联想出来的吗？是因为通过某个图片关联想起来的吗？并不是，当你用 git 提交时，你几乎天天都遇到这个单词，同事天天交流用这个单词，正是一遍遍的在你面前出现、听到才让你非常熟练的掌握这个单词。如果你不认识 `commit` 这个单词，那么说说你是怎么记住你的那么长的身份证号码的？是通过对数字图像化、故事化编排的？还是大量重复见到和用到？

**你越早明白语言学习没有技巧，就会走越少的弯路、花越少的冤枉钱。**——这是我走过 13 年的弯路近期得出的结论。

通过重复训练得到的能力还会更持久，就像你的 QQ 号，即便过了这么多年没用应该还可以熟练的背出来吧。这也是为什么要用 Anki 的原因，具体介绍详见 QA 章节。