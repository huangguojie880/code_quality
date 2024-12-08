<h1>代码质量评价</h1>

<h2>做什么</h2>

当一份代码出现在你面前时，有没有什么统一的规则，可以告诉你这个代码的质量。
该项目就是为了提供这样的一个规则。

<h2>怎么做</h2>

参考360电脑管家的给电脑打分的做法，它给电脑当前的综合状态打0到100分；分数越高电脑状态越好，这样即使是电脑小白也能对自己的电脑状况有所了解。给代码打分的规则如下：

1. 最低分是0分，最高分是100分。
2. 存在所有语言都需要遵守的打分规则。
3. 存在每个语言特色的打分规则。
4. 每个评价维度都会单独的打分。
5. 每个打分维度有一个[0, 100]的重要程度。
6. 总分由多个维度加权平均得到。


<h2>目标</h2>

1. 成为全世界通用的代码评价规则。
2. 客观、公正、专业。
3. 引导项目往好的方向发展。
4. 可衡量。
5. 和人的主观感受一致。
6. 高分数的代码是学习的对象。

<h2>关键分数点定义</h2>

<h3>代码质量</h3>

**0分的定义**

1. 空代码仓应该得0分。

**100分的定义**

1. 暂无。

**其它**

1. 一个存在代码的代码仓也可能是0分，说明其代码毫无价值（价值等于空代码仓）。
2. 分数的高低与项目的使用情况无关，一个被广泛使用的代码也可能分数很低。

<h3>维度重要性</h3>

**0分的定义**

1. 对评价代码质量毫无帮助。

**100分的定义**

暂无

**其它**

1. 重要性分100个等级，是为了防止有些重要的属性其衡量维度少，在综合评价上权重低。


<h2>组织原则</h2>

<h3>基于共识工作</h3>

项目应该基于共识工作，而不上基于个人的喜好。条款被吸收要达到绝大数赞同，应该在80%赞同的基础上。

<h3>从实际出发</h3>

项目中的规则，应该来自于人们在实际编码的经验的总结，而不是基于某种理论的推导。规则应该为最广大的程序员服务，而不是少部分的语言专家。脱离的实践的规则是没有生命力的，不能对实际的编码活动产生积极指导的规则是没有价值的。

分数应该符合大部分程序员对代码的判断，当大部分程序员认为这是一份好代码时，它的分数应该是高的。

<h3>鼓励所有人参与</h3>

规则要保持发展性，吸收最广大人群的观点。什么是好代码，什么是坏代码。一千人，会有一千个观点。所有人都可能提出合理的意见，所以该项目是一个入门门槛很低的项目。

我希望所有人都可以参与进来，提出自己的观点，项目应该要考虑最广大人群的声音。吸收合理的建议，给出反对的理由，引导大家写出好的代码。如果您的意见被吸收后，你的贡献将会出现在项目的贡献名单内。

<h2>说明</h2>

<h3>不提供实现</h3>

该项目参考C++的发布模式，即仅发布一个规则而不会提供一个实现。这样做的原因有：

1. 本人的能力有限，无法提供一个实现。
2. 没有官方的实现，就会鼓励更多人参与进来，提供有竞争力的实现。
3. 在规则上合作，在实现上竞争被证明是一个有效的模式。
4. 前期的精力应是努力制定出这样一个规则，且规则的变化也会很大。


<h3>关于C++</h3>

本人在实际的工作使用的语言主要是c++。所以，初期的规则都是我从使用C++的实践得出来的。有时，并未考虑到其它语言的情况。

但一些放在通用规则里的条款，虽然来自于C++一些使用经验，但其限制却是客观的。如函数的长度在50行左右的限制并不是来自C++，而是人的限制。如果一些语言天生在一些规则下分数很低，大概率是语言本身的问题，因为人的限制是客观存在的。

<h3>打分的好处</h3>

规则是不尽完美的，只能尽可能地保证其总体上合理的。打分就可以保证，一份代码在一个规则下不做的过分的差，它都可以拿到一定的分数。尽可能地去让一份好的代码拿高分，而不会因为在一些方面的不足导致其分数太低。

<h3>如何衡量规则的好坏</h3>

1. 好的规则应该可以准确地给出什么样的代码是0分和100分。
2. 有一个数据集存在，其是经过主观评价的，规则给其打的分应该和主观评价一致。

<h3>一些难点</h3>

1. 拥有良好组织结构的代码（合理的文件夹目录等），应该拿高分，而如何客观地衡量却是一个很难的点。