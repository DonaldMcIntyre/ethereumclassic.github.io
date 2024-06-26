---
title: "什么是51%攻击?"
date: 2023-11-21
author: Donald McIntyre
contributors: ["DonaldMcIntyre"]
tags: ["education"]
linkImage: ./banner-1.png
---

---
**由此收听本次内容:**

<iframe width="560" height="315" src="https://www.youtube.com/embed/9z5emMxIeo4?si=4afKKIi1rqjC7nV1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

![](./banner-1.png)

由于仍有许多人询问什么是51%攻击，以及以前发生在以太经典（ETC）上的事情，并对这些事情感到困惑，我们决定写下这篇文章，回答所有疑问并纠正所有困惑。

确实，在过去，ETC在成为较小、次要的区块链时曾两次遭受攻击。

这些攻击不是“黑客攻击”，而是有限的、非系统性的，这意味着ETC从未“崩溃”，这些攻击只影响受害者，而不是所有用户，也不会影响整个网络功能。

在接下来的章节中，我们将解释这些网络的历史，什么是51%攻击，以及为什么ETC现在比以往任何时候都更强大，因此极不可能再次发生这种类型的攻击。

## 在那之前是33%攻击

在比特币的发明和所谓的纳卡莫托共识的使用之前，该共识方法使用工作证明作为其共识方法，点对点网络管理数字货币是不可能的，因为它们很容易受到攻击。

在1982年的[计算机科学论文](https://lamport.azurewebsites.net/pubs/byz.pdf)中证明，攻击这些网络的门槛仅为节点的33%。

![The Byzantine Gnerals Problem](./2.png)

这意味着如果参与的三台机器中有一台损坏了系统中传输的信息，整个系统可能会受到威胁。

这个问题被称为“拜占庭将军问题”。

## 现在是51%攻击

中本聪（Satoshi Nakamoto）的卓越发现是，使用工作证明，网络中每个数据块的密码印章或哈希本身就是一种新的共识机制形式，它可以使系统中的所有节点以一种去中心化的方式同步锁步。

通过使用这个需要大量计算工作和电力消耗的信号系统，攻击网络的门槛从参与机器的33%提高到了51%。

这更高的安全级别是比特币自问世以来一直无可争议地存在的原因。

中本聪创造的方法被称为“中本聪共识”。

## 以太经典发生了什么？

然而，即使在工作证明的区块链中，如比特币和ETC中，将门槛从33%提高到51%仍然意味着，如果有人获得51%的计算能力，这个强大的系统仍然可能受到攻击。

这就是在ETC作为较小次要区块链时发生的事情。

在2019年1月5日和7日，ETC网络遭受了两次51%攻击，然后在2020年8月，又发生了三次51%攻击。

在所有情况下，加密交易所成为攻击目标，它们在所谓的“双花”中损失了数百万美元，这是在这类区块链中只能实施的攻击。

## 什么是双花？

顾名思义，双花是指将同样的硬币花费两次。然而，这只是一个简单化的术语。

双花实际上是指窃贼可能在区块链的一个地址中拥有硬币，并将其转移到受害者那里，但然后他们可以使硬币再次出现在他们自己的地址中，从而欺骗受害者，并窃取一些有价值的东西。

他们这样做的方式是通过发送硬币进行正常交易，这将被包含在链中的一个块中，并且通过使用不包括原始交易的新块重新组织网络中的块，从而使硬币从受害者的帐户中消失。

如何实现这一点将在接下来的三个部分中解释。

## ETC节点如何达成共识

要了解51%或双花攻击（两者都是相同的）是如何实现的，重要的是要了解区块链中的节点如何在每13秒（在ETC的情况下）内达成链的完全相同状态的共识。

区块链不断接收新交易，这些交易被重新传输到系统中的所有节点。当一组称为矿工的节点收到交易时，它们将其积累成批次，然后用需要大量计算工作才能创建的密码印章密封它们，因此称为“工作证明”。当矿工创建印章时，他们得到密封的块并将其发送到网络的其余部分进行验证。当网络的其余部分验证交易正确且密码印章合法时，它们将该块包含为链上最新的块，或称为“区块链”。

实际上已经完成了大量工作的信息是所有节点需要知道的正确块。这是因为攻击者很难在没有如此庞大计算基础的情况下构建块。

## 具有最多工作完成的链的规则

有趣的是，每个块的工作证明相同的信息实际上是区块链始终统一并允许全球节点随时加入、离开并在没有审查或任何许可的情况下重新加入的原因。

他们可以通过简单地检查整个区块链中累积的工作完成情况来实现这一点。如果存在攻击性的替代区块链，则它们可以添加每个区块链中完成的总工作，并只需按照具有最多累积工作的那个链。因为攻击者链将很难建立如比特币或ETC那样庞大的计算基础，所以网络将始终趋向于正确和诚实的链。

因此，每轮完成的工作保持网络同步，而整个链历史中累积的工作加在一起则保持系统统一在一个单一的区块链后面。

## 51%攻击的描述

当攻击者能够暂时获得51%的挖矿计算能力时，问题就出现了。当发生这种情况时，他们确实有能力构建替代链以进行51%攻击或双花。

他们这样做的方式是选择一个受害者，比如一个加密交易所，然后向他们发送价值数百万美元的ETC，并将其兑换为另一种硬币，比如门罗（XMR）。当他们在交易所的账户中有数百万美元的XMR时，然后将所有XMR提取到门罗区块链上的他们自己的地址。

当他们完成对XMR的提取过程后，然后他们开始使用他们在ETC中的大型计算基础，该基础必须占网络总挖矿计算能力的51%或更多，从其最初的交易到交易所的区块开始构建替代区块链。

在这个替代链中，将具有比主链更多的累积工作，他们将实际上删除其ETC到交易所的原始交易。

当他们构建具有比主链更多累积工作的替代链时，他们将其发送到网络的其余节点。

由于上面解释的“具有最多工作完成的链的规则”，那么ETC网络中的所有节点都将放弃他们曾经工作过的主链，并立即采纳攻击者构建的新的替代链。

一旦整个网络迁移到攻击者的区块链，原始的交易到交易所的交易将消失。这意味着接收了数百万美元ETC的交易所现在不再在他们的地址中拥有这笔钱。他们刚刚消失了。

然而，攻击者链的窃贼现在将拥有两笔价值数百万美元的硬币：通过删除他们对交易所的原始交易而恢复的原始ETC和从交易所窃取的门罗区块链中的XMR。

这就是51%攻击或双花从受害者那里窃取钱的方式。

## 如何避免51%攻击？

即使它们不太可能在所有工作证明的区块链中发生，包括最大的比特币在内，也有几种避免51%攻击的策略：

**网络规模：** 最明显的一个，也是51%攻击零星且不太可能发生的原因是尽可能拥有最大的计算基础。一种货币越有吸引力，价格上涨，矿工将获得的奖励越多，矿工获得的奖励越多，哈希功率越大，攻击者越不可能实施双花。这就是规模如何保护工作证明的区块链的方式。

**在特定挖矿算法中领先：** 除了规模外，成为特定挖矿算法中的领先链也是一种良好的保护形式。当链在特定挖矿算法中排名第二或第三时，较大链的矿工可能会将他们的机器指向较小链并攻击它，因为对他们来说达到51%的计算能力可能相对轻松。这就是为什么ETC之前会受到攻击的原因，因为在它是工作证明网络时，在以太坊之后，它是其段中第二大的链。

**等待更多的确认：** 在用户级别上，等待更多的确认才考虑交易最终是保护自己免受双花的主要方法。这是因为在输入交易的块上创建更多的块，该交易就会变得更加安全。例如，如果我在最后一个块中收到了100 ETC，那么这笔交易比我在100,000个块之前收到的100 ETC更容易被反转。这是因为攻击者在执行双花之前必须重新做整个100,000块，再次花费所有那些电力和计算能力。

## 为什么ETC不太可能再次受到攻击

![](./3.png)

如果拥有更多的哈希功率能够为区块链带来更多的保护和安全性，那么在过去的14个月里，ETC已经变得更加安全。

这是因为以太坊在2022年9月从工作证明迁移到了权益证明，这导致许多滞留下来的矿工开始挖矿ETC。

正如在本节图表中所示，ETC的计算基础，以哈希率为衡量标准，从以太坊迁移时的约24 TH/s增加到了超过150 TH/s。

ETC不仅在其挖矿计算基础上取得了进展，而且已成为其哈希算法（ETCHash/ETHash）中的领先区块链，也是世界上最大的工作证明区块链。

这提供了另一层保护，使得ETC极不可能再次遭受双花攻击。

---

**感谢您阅读本期文章!**

了解更多有关ETC，欢迎访问: https://ethereumclassic.org
