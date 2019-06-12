## 2019.5.13
#### 1. DeepDecision: A Mobile Deep Learning Framework for Edge Video Analytics.
>infocom 2018
1. augment reality (AR) devices, video
2. on smart-phones, AR applications
> 作者: 
> 加州大学, Riverside (Xukan Ran, Haolianz Chen)
> College of William and Marray (Xiaodan Zhu)
#### 2. A Computing Plateform for Video Crowdprocessing Using Deep Learning
>infocom 2018
1. optimize the performance on mobile devices with computational offload ...
> 作者：
> 北京大学 (Zongqing Lu)
> Army Research Lab (Kevin S.Chan)
> 宾州州立大学 (Thomas La Porta)

#### 3. Inferring Persistent Interdomain Congestion
>sigcomm 2018
读不懂？ 可读性差

#### 4. When the Dike Breaks: Dissecting DNS Defenses During DDoS (extended)
>IMC 2018
1. Dissect 剖析
> 作者：
> SIDN Labs and TU Delft (Giovance C.M. Moura)
> John Hiedemann (USC/Information Sciences Institute)
> SIDN Labs and University of Twente (Moritz Muller)

## 2019.5.14
#### 5. Three Bits Suffice: Explicit Support for Passive Measurement of Internet Latency in QUIC and TCP
> IMC 2018
1. 只需要3个bit，能测量包括TCP和QUIC在内的网络延迟
> 作者：
> ETH Zurich (Piet De Vaere, Tobias Buhler, Mirja Kuhlewind, Brian Trammell)

#### 6. Multilevel MDA-Lite Paris Traceroute
> IMC 2018

>作者：
> 法国索邦大学(Kevin Vermeulen)
> RIPE NCC (Stephen D.Strowes)
> 翻过索邦大学 Sorbonne(Olivier Fourmaux, Timur Friedman)
1. 问题：传统的Paris Traceroute and MDA (mutipath detection algorithm) 需要在trace的路径上传输大量的数据包，不适用于部署到除了Paris Traceroute 以外的平台上。
2. tracerotue 常被用来做故障排除troubleshoot, 长期的日常调查
3. 提出了能够减少开销同时保持低失败率的traceroute tool
4. Fakeroute, simulator
5. investigate the difference between 直接和简介probing for alias resolution
6. 目前工作主要考虑的是Ipv4的情况，未来考虑ipv6的情况

#### 7. Cloud Datacenter SDN Monitoring: Experiences and Challenges
>IMC 2018

>作者：
> 加州大学圣地亚哥分校(Arjun Roy, Deepak Bansal, David Brumley, Harish Kumar Chandrappa )

1. 问题：大部分工作研究：管理在数据中心物理设备产生的故障， 很少在logical overlay network的管理上(提供不同租户之间的强隔离=logical overlay network)
2. 描述了在建立一个cloud-based fault monitoring systems 的挑战，描述了 virtualization 是如何影响多租户数据中的故障管理的
3. 详细描述了会出现的一些问题

#### 8. A Case for Web Service Bandwidth Reduction on Mobile Devices with Edge-Hosted Personal Services
>infocomm 2018
>作者：
> SUNY Binghamton 美国纽约州内排名最高的大学
1. 一些web services中重复内容，headers多，small payload
2. 在保证运营商和用户的利益下，提出新的在边缘节点的专为单个用户提供不同服务的方法。并研究了部署。。。

## 2019.5.15
#### 9. Adaptive VNF Scaling and Flow Routing with Proactive Demand Prediction
>infocomm 2018
>作者:
>华中科技大学(Xincai Fei, Fangming Liu)
>NetX Lab 香港(Hong Xu)

## 2019.5.20
#### 10. Quality of Experience-based Routing of Video Traffic for Overlay and ISP Networks

>infocomm 2018
>作者:
>Universite Cote d’Azur(蔚蓝海岸大学) (Giacomo Calvigioni, Ramon Aparicio-Pardo, Lucile Sassatelli)
>华为法国研究所(Jeremie Leguay, Paolo Medagliani, Stefano Paris)

#### 11. Towards Stability Analysis of Data Transport Mechanisms: aFluid Model and an Application
>infocomm 2018
>作者：
>University of Massachusetts, Amherst(Gayane Vardoyan, C.V. Hollot, Don Towsley)

#### 12. PoiRoot: investigating the root cause of interdomain path changes
>sigcom 2013
>作者：
![](2019-05-20-21-45-24.png)
TODO

## 2019.6.2
#### 1. BGP Communities: Even more Worms in the Routing Can
![](2019-06-02-22-26-20.png)
快捷方式是：control + command + v 粘贴图片

## 2019.6.5
icc-2018
#### 1. Prompt Lightweight VPN Session Resumption for Rapid Client Mobility and MTD Enablement for VPN Servers
resumption 恢复

#### 2. eyeDNS: Monitoring a University Campus Network

## 2019.6.10
icc-2018
#### 1. Enhanced Session Table Architecture for Stateful Firewalls
stateful firewalls:提供数据包状态检查的防火墙

## 2019.6.11
icc-2018
#### 1. Monsieur Poirot: Detecting Botnets Using Re-Identification Algorithm and Nontrivial Feature Selection Technique
botnets: 主机网络， a botnet is a group of compromised hosts(bots) that are remotely commanded by an attacker through a command and control channel.
problem: modern botnets are migrating to P2P network
>作者
![](2019-06-11-10-13-59.png)

通过network flow 检测botnets， 特征分析，detect malicious traffic
Monsieur Poirot -detect other botnets

#### 2. Modeling Malware as a Language
malware: 恶意软件
恶意软件的检测， modeling malware as a language for the purpose of performing such semantic-based analysis
>作者
![](2019-06-11-16-28-55.png)

#### 3. A Dynamic Rate Adaptation Scheme for M2M Communications
M2M: machine-to-machine, IoT tech.
![](2019-06-11-16-42-03.png)
>作者
![](2019-06-11-16-59-29.png)
备注：没有过多了解

#### 4. Assessing Coverage and Throughput for D2D Communication
D2D: device to device, 不经过中间网络，直接通信，用途广泛，比如车与车之间，碰撞，距离等

提出了一个测量D2D coverage probability and average throughput 以及其他参数性能的 framework
why do this measurement?
> 句子：our contributions are three-fold

D2D通信指的是UE 不经过基站直接通信，M2M不仅包括UE还包括各种Machine之间的通信

> D2D refers to mobile devices like smart phones directly communicating with each other. M2M is a rather more generic term used for variety of device communicating with each other or through a network.
M2M refers to a communication paradigm that enable machines (objects) to communicate with each other with little or no human interaction
> 作者：
![](2019-06-11-21-02-27.png)

#### 5. An Optimized and Secure Authentication Scheme for Vehicular Ad Hoc Networks
Vehicular Ad Hoc Networks(VANETs)
验证方面，可读可不读
>author:
![](2019-06-11-21-18-39.png)

#### 6. Who Am I? Personality Detection Based on Deep Learning for Texts.
论文主题很有趣，作为趣闻来读
提出the structure of the texts online 对于性格的推测也很重要

#### 7. Urban Traffic Bottleneck Identification Based on Congestion Propagation
交通traffic， 定义了uraban traffic bottleneck， most significance(road segments that will lead more congestion cost in urban area, 然后提出了identification method)
Introduction 写得好
>author:
![](2019-06-11-21-51-26.png)

## 2019.6.12

#### 1. OPIU: Opinion Propagation in Online Social Networks Using Influential Users Impact
opinion propagation 分为两个重要factor, the influential users' effect and the neighbors' effect. 创建了一个新的模型来评价

很有意思的论文，没有太细看，online social network
>authors:
![](2019-06-12-09-17-01.png)

#### 2. A Data-Deduplication-Based Matching Mechanism for URL Filtering
关于URL filtering的算法大多是通过提升multiple matching来speed up，但是本文发现url中存在大量的重复URL，且比列高，随着URL数量增长，比例增长更大。所以基于hash tech. 来去重，以此speed up th filtering。
但是存在一些问题，一个是caching，一个是hash算法会有小概率的冲突率。
>authors:
![](2019-06-12-09-42-18.png)

#### 3. On the Secure Degrees of Freedom of 2 × 2 × 2 Multi-Hop Network with Untrusted Relays
Degrees of freedom(DoF): 自由度，以样本的统计量来估计总体的参数，样本中独立或能自由变化的数据个数
方差，样本减平均值得平方之和(一个由样本决定的衍生量)，对N个随机样本而言，其自由度为N-1
a + b = 6, 自由度为1， 只有a才能真正自由变换，b会被a选值得不同限制。

multi-hop MIMO relay networks with untrusted relays and confidential messages.
>authors:
![](2019-06-12-10-28-28.png)

#### 4. Sentinel: Defense Mechanism against DDoS Flooding Attack in Software Defined Vehicular Network
a new defense mechanism to detect flooding attack by time series analysis of packet flow and mitigate the attack creating a flow tree to find out the source of spoofed packets. 

结合SDN 与 Vehicle Ad Hoc Network（VANET）

>authors:
![](2019-06-12-10-41-36.png)

#### 5. Is DNS Ready for Ubiquitous Internet of Things?
ieee access-2019
主要是分析，没有看懂具体内容
>authors:
![](2019-06-12-14-24-41.png)

#### 6. An Energy-Efficient Location Prediction-Based Forwarding Scheme for Opportunistic Networks

Opportunistic Networks: OppNets, unstable topology, intermittent connectivity, and no guarantee of the existence of an end-to-end path. 不稳定的网络，节点移动，随机组成Ad hoc 网络。
在这样的网络中，源节点到目的节点的数据传输is a challenge

考虑了节点的剩余能量和基于传输可能性的location信息
比目前的很多种方法在节点剩余能量，dead nodes的个数，message delivery probability，average latency上效果更好。

>authors:
![](2019-06-12-14-44-36.png)

#### 7. Name-Based Routing with On-Path Name Lookup in Information-Centric Network.
ICN：将内容与终端位置剥离，通过发布/订阅来提供存储和多方通信等服务。
综合分布式和集中式的name announcement and name look up，设计了一种新的方式，是的通信开销小，存储效率高

不太明白下面图的意思：
![](2019-06-12-15-48-56.png)
>authors:
![](2019-06-12-15-26-39.png)

#### 8. Online Revenue Maximization in NFV-Enabled SDNs
常规文章，有一定价值，没有细看
dynamic admissions of delay-aware NFV-enabled requests in SDNs
几个challenges: max revenues by admitting as many requests as possible; meet diverse resource demands and delay requirements; find rouing paths.....
>authors:
![](2019-06-12-16-16-41.png)

#### 9. KORA: A Framework for Dynamic Consolidation & Relocation of Control Units in Virtualized 5G RAN
资源管理，分配
>authors:
![](2019-06-12-17-07-56.png)

#### 10.Distributed Placement and Online Optimization of Virtual Machines for Network Service Chains.
decentralized approach to reduce the time-average cost of NFV and the queue length.
>authors:
![](2019-06-12-19-10-41.png)

#### 11.Throughput Maximization of Delay-Sensitive Request Admissions via Virtualized Network Function Placements and Migrations
NFV, horizontal scaling by migrating existing VNF instances from their current locations to new locations; and (ii) vertical scaling by instantiating more VNF instances
>authors:
![](2019-06-12-19-46-36.png)