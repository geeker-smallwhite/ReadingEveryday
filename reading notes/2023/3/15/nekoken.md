# 金观涛 - 控制论与科学方法论

## 序言

辨喜 - 最伟大的东西是世界上最简单的东西，它和你自己存在一样简单。

控制论：解决化学问题，其实是一个控制方法问题。

控制论思想的源流：数学和物理的发展；生物学和生命科学的进展；人类思维规律的探讨。

## 第一章 控制和反馈

有始也者，有未始有始也者，有未始有夫未始有始也者 - 庄周

### 1.1 可能性空间

一切科学研究都必须有一个出发点。几何学的大厦建立在公理基础上，控制论和系统论的研究则开始于可能性空间。

可能性空间：使用不同原子排列方式组成的氨基酸的例子。

启发：世界上许多事物并不是从一开始就注定要发展成现在这个样子的，在事物发展的初期。它们往往有多种发展的可能性。由于条件或者纯粹机遇的关系，最终才沿着某一个特定的方向发展下去。既然事物的发展都是从最初的可能性开始的，就不能不使人们对它发生浓厚的兴趣，如果对它作更深一步的研究，可以发现它跟控制论中"控制"这个概念有着密切的关系。

控制论含义：关于控制的理论。

（1）被控制的对象必须存在着多种发展的可能性。如果事物的未来只有一种可能性，就无所谓控制了。比如光在真空中的传播速度是确定的，每秒299793公里，既不会高于这个速度也不会低于这个速度，只有一种可能性。因此人们不会说“控制了光在真空中传播速度：之类的话。某一事物在发展变化中的未来有哪些可能性，是由事物本身决定的。对于鸡蛋，它下一时刻面临的发展可能有鸡蛋、小鸡、碎鸡蛋等几种，而石头面临的可能性就完全不同。

（2）被控制的对象不仅必领存在多种发展的可能性，而且人可以在这些可能性中通过一定的手段进行选择，才谈得到控制。比如一座火山，它在下一时刻面临着爆发或不爆发两种可能性,但目前人类的能力还不能在这两种可能性中选择。所以，我们也不会说"控制了火山爆发"这样的话。所谓我们不能控制，就是无法选择或不存在选择的余地。

由此可见，控制的概念与事物发展的可能性密切相关。我们将事物发展变化中面临的各种可能性集合称为这个事物的**可能性空间**。它是控制论中最基本的概念。

例如：

1.鸡蛋会变成破蛋、鸡蛋和小鸡，至于事物具体发展成为可能性空间中哪一个状态，要看条件而定。当事物变到某一状态后，它又面临着新的可能性空间。一个事物发展过程中的可能性空间就像树枝一样向无限远处伸展。

2.世界上第一个认真考虑过事物可能性空间性质的可能是中国战国时期著名的哲学家杨朱。《列子》里有一个“歧路亡羊”的故事，说有一天杨朱的邻居走失了一只羊，许多人去找也没找回来。杨朱问邻居是怎么问事儿，邻居说：“岔路太多了,而且岔路之中又有岔路,不知道它到底跑到哪条路上去了。”杨朱听了很有感触，终日沉默无言，闷闷不乐。“歧路之中,又有歧焉”，这位哲学家所感叹和研究的，正是事物可能性空间这种重要的展开方式。

3.生物起源进化。生命的多样性来自连续不断的进化过程，在这个过程中一个种产生几个后代种，体现生物发展和适应环境的几种可能性。

生命之树：物种在其发展过程中按可能性空间展开的形象体现。

> 研究生物在一定条件下按可能性空间展开的方式，成为群体生物学的中心问题。
>
> 它回答现有动物、植物、真菌的种类和数量是如何来的，什么力量作用于这些群体使它们保持现状或发生变化，以及对某些物种发展的可能性可以作出哪些预测。

### 1.2 人通过选择改造世界

为什么事物的可能性空间是树枝状？

> 因为事物面临的可能性空间往往不止一个状态，事物变化具有不确定性。

事物的矛盾性，事物的可能性空间至少面临肯定自身和否定自身两种状态。事物在发展的过程中这样分化是不断进行着的，这样终究要形成“歧路之中，又有歧焉”的结果。

不确定性是事物的矛盾性，从不确定性的角度来看待事物的发生和发展，是现代科学和经典决定论的一个重要区别。今大的物理学已不再仅仅处理那些必然发生的事情，而是处理那些最可能发生的事情了。今天的生物学也不再把某个物种的出现看作进化过程中必然的现象，而只把它们理解为可能发生的种族中的一员。这样一种思想从本世纪初统计物理学创立以来已经扎根于科学家的头脑。粗看之下它也许并不难于理解，但它确实是本世纪科学思想的一次革命。在经典的牛顿物理学里，宇宙被描述成一个结构严密的确定性机器，一切都是按照某种定律精确地发生的，未来的一切都是由过去的一切严格决定的。科学家意识到矛可能戳穿盾也可能截不穿盾这个简单的真理，走过了漫长道路。

事物发展的可能性空间，或事物的不确定性，是由事物内部的矛盾决定的。人们根据己的目的，改变条件，使事物沿着可能性空间内某种确定的方向发展，就形成控制。控制，归根结底是一个在事物可能性空间中进行有方向的选择的过程。人类的自然、实践活动都与选择相关。

控制的三个基本环节：

+ 了解事物面临的可能性空间是什么。如一个人得了病，他可能好转、恶化、死亡。
+ 在可能性空间中选择某一些状态为目标。如治病的目标是使病情好转。
+ 控制条件，使事物向既定的目标转化。

对于一个复杂的过程，事物的可能性空间不仅有许多状态，而且这些状态有复杂的展开方式，影响事物发展的条件也错综复杂。与之相应的选择过程也是复杂的，需要在事物发展的不同阶段控制不同的条件，同时注意各种条件之间的配合和状态的相关作用。

### 1.3 控制能力

例子：天花的控制。

**绝大多数控制过程，人们只是把可能性空间缩小到一定范围内达到控制的目的。如果任何控制过程都想以某个惟一状态为目标，不但没有必要，而且还会使控制失灵。**

> 关于这个特征的寓言：用网捕鸟。

第二个例子：恒温箱控制。

实行控制后，事物发展的可能性空间缩小，控制能力增强。

控制能力：实行控制前后的可能性空间。

如果某一事物的可能性空间为M，实行控制后，可能性空间缩小为m，那么控制能力就是M/m。如果可能性空间状态为无限多，并且互相连续，我们可以用面积大小的比例来表示它。

例：从天平称12个乒乓球中唯一的废品，智力游戏。

### 1.4 随机控制

碰运气——随机控制。

控制就是可能性空间缩小，随机控制是可能性空间缩小的过程。

特点：系统的可能性空间只有在达到目标值时才缩小，不达到目标值时，可能性空间不缩小。

例子：操场上碰指定的孩子。

设可能性空间a、b、c、d是4个状态，目标是c。第一次选择的结果是a，因a≠c，所以否定a，第二次选择的可能性空间是a、b、c、d。如果选中了c，就肯定结果，如果选中了a、b、d，就否定结果，继续选下去。

类似：一个一个试试看。

例子：草药、现代科学(生命起源)。

随机控制注意：速度问题、竹竿出城门问题、蒸汽机问题。

### 1.5 有记忆的控制

随机控制缺点在于不确定性，因此改进成有记忆的控制。

有记忆的控制可以排除证明不是目标的状态，这些状态将从下一个可能性空间中排除出去。

优点：可能性空间在到达目标值之前是随着选择次数逐一缩小的，提高控制效率。

注意点：别记错。

无论随机控制还是有记忆的控制，都必须注意事物发展的可能性空间本身是否存在着陷阱。在探索过程中，必须记住这些陷阱，避开这些陷阱。一旦进入了“死”这个状态，可能性空间就永远停留在这个状态。

在随机控制中，那些可能削弱我们控制能力的状态是不应该最先尝试的。

例子：分离金属。

要适当地考虑控制的顺序。

### 1.6 共轭控制

目的：扩大控制范围。

例子：曹冲称象。

数学公式：
$$
L^{-1}AL
$$
一般称作A过程的共轭过程，公式称为与A共轭的控制方法，它通过$L$和$L^{-1}$变换，把原来不能控制的事变为我们可以校制的A过程去完成。A的控制范围在实行了变换后扩大了。

### 1.7 负反馈调节

背景：选择了某一目标，但具备的控制方法达不到所需要的控制能力。

例子：老鹰抓兔子。

负反馈调节：减小目标差的过程，通过系统不断地把自己控制后果与目标作比较，使得目标差在一次一次控制中慢慢减少，最后达到控制的目的。作为一般的负反馈调节机制有两个环节：

+ 系统一旦出现目标差，便自动出现某种间减少目标差的反应。
+ 减少目标差的调节要一次一次地发挥作用，使得对目标的逼近能积累起来。

这两个条件如果不满足，就不能算完善的负反馈调节。

> 例子：电流熔断保护装置、高压锅释放压力，但都不是完全的负反馈调节，因为它不满足第二个调节。所以是半反馈调节。

### 1.8 负反馈如何扩大了控制能力

鹰：将鹰的位置可能性空间表示为平面上的点。目标用`m`表示，不断调整俯冲范围，控扩大控制能力。

实际应用：控制导弹打飞机。导弹配置红外线装置，配上电子计算机。

负反馈控制可以把某种有限的控制能力累积起来，扩大控制能力，每一次反馈，实际上都是将上一次作为输出的可能性空间作为输入，让控制机构在这个已经被缩小的范围内进行新的选择。

负反馈调节：做起来看。客观事物不断变化，边做边调整。

例子：居里夫妇发现镭的过程/教学的过程。

负反馈是一种趋向目的的行为。目的性更成为社会能动性意识。

### 1.9 正反馈与恶性循环

目标差不断增大的过程：负反馈。

例子：晋朝的人对诗。

正反馈耦合关系的系统：

<img src="/Users/zounuo/study/book/读书笔记/assets/image-20230224204026451.png" alt="image-20230224204026451" style="zoom:50%;" />

更多例子：军备竞赛。

正反馈现象也叫恶性循环。

例子：心脾两虚；炸药爆炸。

正负反馈也可以互相转换。

## 第二章 信息、思维和组织

雨果：有一种比海洋更大的景象，这便是天空。有一种比天空更大的景象，这便是人的内心活动。

### 2.1 什么是知道

历史的研究：20世纪科学家在研究通讯理论；两千多年前，哲学家庄子和惠子。

例子：庄子观鱼——什么是知道，怎样才能知道——人活的信息的过程，信息怎样传递、怎样获得信息的过程。

知道：可能性空间变大或变小。

> 在绝大多数情况下，可能性空间变小。

申农在创立信息的量的理论方面做了许多工作。

引入了概率。

采用负对数好处：只要可能性空间缩小了，获得的信息量总是正的，如果可能性空间没有变化，获得的信息量就为0。如果可能性空间扩大了，信息量为负值，人们原来对一件事比较确定的认识变得模糊起来。

实际应用中，使用以2为底的负对数计算信息量，单位称为比特。

一行文字由单个的字和标点符号组成，在拼音文字中则由字母和标点组成。在读到这行文字之前，我们对每一个单位将出现几十个字母中的哪一个是不知道的，读了之后每一个单位的可能性就确切地变为那个特定的字母。沿着这个思路我们可以算出一行文字的信息量或一整部作品的信息量。同样我们可以把一幅照片分解为平面上纵横排列的点，像报纸上的照片每个点实际只有白色和黑色两种可能,整幅照片的信息量就由所有点表示的信息量组成。这样任何一幅照片,绘画或者雕塑所包含的信息量都成为特定的，因而也就可以计算了。信息概念量化以后，人们找出了许多有关信息传递和存储的规律，使有关通讯和控制的理论变得既严密又精确，成为真正现代意义下的科学。

### 2.2 信息的传递

环节：信息源、传递信息的通道、信息接收者

庄子惠子就在争论信息能否传递的问题。

信息在传递的过程中称为信号。

信息的传递：可能性空间缩小过程的传递。信息源发生的确定性事件使它的可能性空间缩小。

传递信息跟控制有密切的关系——使可能性空间缩小的过程，

例：DNA的遗传信息。DNA结构确定会引发一系列可能性空间缩小，决定某一生物形态。

人类不能控制自己的心跳速度。

信息传递的新通道——残疾人。

例：纪昌学箭。(足够的信息量，才能控制目标)

**结论：知行合一。**

### 2.3 信息是一种客体吗

信息只有在传递中才有意义，不能脱离主体谈信息。

自然界大量信息过程都不依赖人的主观存在，但主客体之间的差别，只有在认识论范畴中有意义。

在认识过程中，信息是主客体之间的桥梁。

不可把人头脑加工，带有主观色彩的信息与客观事件混为一谈。