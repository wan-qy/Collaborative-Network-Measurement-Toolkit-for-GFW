#对GFW进行DDoS

>我们一直不提这件事情。DDoS有很多问题。

>首先，DDoS是一个脏活。DDoS首先需要组织botnet，这种事情跟贩卖人口差不多，低级。

>其次，DDoS在任何国家都是非法的。2009年5月19日民用DNS攻击案，四个脚本小子荣获“破坏计算机信息系统”奖章。GFW可是号称国家信息海关、国家信息安全基础设施，攻击它，万一被抓了人命事儿小，你的开源项目没有人继续帮你做，多郁闷啊。

>再次，DDoS在战略上只会产生负面结果。在这个拔网线司空见惯的时代，推倒GFW，不但不会改善互联网审查的状况，反而可能造成实名制和金盾的崛起——一帮只会整人不懂技术的胡乱拔网线、军管互联网。《总论》就已经说过，双方需要的是一种斗争状况下的动态平衡。大家都得过且过，退避三舍，网民翻墙有方，GFW对上面有交代，就行了。最多偶尔之偶尔，逢年过节，比如国庆或者春节的时候，DDoS开个口子让大家出去遛一遛。

>当然，虽说问题多多，DDoS的可行性还是有的，GFW的计算规模总归还是有限的。2010年1月3日前后的“解封”据说就跟GFW北京被DDoS有关系。不过也不会详细讨论其方法，只是小字提一下……组织DDoS，先要对全国的网络拓扑很清楚，这就涉及网络测量的课题；也要对GFW的结构了解得很透彻，弱点在哪里，负载均衡算法是怎样的；怎样做最有效，是点射还是温水煮青蛙；怎样反反DDoS，怎样空对空射击。这些都需要学习。其次，DDoS的效果需要一套精细的评估体系，如果不成功需要快速改变策略。GFW不是常规的服务器，成功与否并不是那么显著。因此需要建立一个监测网，在全国不同的ISP对GFW的多种指标实施实时观测。比如不同协议下的阻断响应延迟，TCP的SYN超时和ACK超时时间，各个DNS服务器污染的情况，窗口值的增速等等。所以说这个事情要做也不简单。顺便一提，这个监测网所用监测工具，我们最初给它命名为Collaborative Network Measurement Toolkit for GFW，简写为CNMTG；当然了，这是一个自命名完成之后就停止开发的雾件。


From http://gfwrev.blogspot.sg/2010/03/gfw.html ，它不应该停止开发。“在这个项目上，Wall Breakers是大写的”。
