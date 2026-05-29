---
layout:     post
title:      知识诅咒和汉语思维对英文文档写作的负面影响
date:       2026-05-29
author:     Shiwei Shang
header-img: img/post-bg-coffee.jpeg
catalog: true
tags:
  - 技术文档写作
---

# 知识诅咒和汉语思维对英文文档写作的负面影响

这几天写文档的时候遇到了一个给UI缩放的控件，它长这样：- 100% +。它的作用就是把UI放大缩小，中间的百分数显示缩放的比例，鼠标单击这个百分数可以把缩放比例重置成100%。很简单的一个东西，我的初稿写成：
- Enlarges or reduces the UI and displays the zoom percentage. Click the zoom percentage to reset the UI to 100%.

发出去审稿之后收到一条反馈，认为enlarge和reduce这两个词有歧义，容易让人误解成把软件窗口放大或缩小，给出的意见是：
- Contains the controls that you use to adjust how large or small the UI content appears. Click the zoom percentage indicator to reset to 100%.

收到这条反馈，我就开始思考为什么会导致这个问题。思来想去，我认为：
- **我的汉语思维造成了这次模糊的表达**。在我描述它的作用时，我完全是按照平时说话那样表达，用“UI“概括UI上的各种元素，比如按钮，窗格，文字等。当时为了避免用zoom解释zoom controls，我还特意选择了enlarge和reduce，结果聪明反被聪明误，忽视了enlarge和reduce可能造成放大、缩小窗口的歧义。
  但也可能不是汉语思维，也许就是我单纯菜，不够细心。
- **知识诅咒造成了这次自查的疏漏**。就像我上一点说的，我丝毫没有察觉自己说“缩放UI“会有什么歧义，我写的时候是不假思索的。没想过有人会觉得这个东西是缩放窗口的，毕竟缩放窗口可以用鼠标拖拽，点最大化，最小化按钮。
经过这次，我收获到了几点：
- **同行审稿非常必要**。一个人有一个人的视角，别人会在你自己认为完美的东西上发现瑕疵。
- **AI无法完全替代人类**。我的初稿是在AI的辅助下完成的。我给它讲这个东西是什么，怎么用，让它修改我的描述，但是它还是没能捕捉到这个瑕疵，最后还是人工审稿看出来的。
- **汉语是比较依赖上下文的语言**。我们平时的表达包含很多省略的信息，但是我们绝大多数时间依然可以理解彼此，凭的就是上下文。但也许就是我的汉语不够好，所以写出来的英语也是不好的。需要做的是以后写东西一定确定好主谓宾，花更多时间检查这些方面。
以上就是我这次的反思和收获。
