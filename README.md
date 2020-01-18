# 区块链

---

## 密码学（数据的安全）

### 哈希算法

>单向性

>抗篡改能力

>抗碰撞能力

### 非对称加密


## 分布式账本（数据的存储）

[什么是分布式账本](https://mp.weixin.qq.com/s?__biz=MzUxODk1OTA0OA==&mid=2247485997&idx=1&sn=92b93dd12fc586311207c83b32823255&chksm=f981b08acef6399cf8bc9bf5da323587bb773665ae22c7b16db7e4609266029f96243749107e&scene=0&xtrack=1&key=ebbdd804d597c249ccfc81d6c6e85ba3747cca98d8de8a478e352a1d28d3ab0c0bd6659cc3eb89f2e10e4e25380cb0acd9c4902de4bf8730b6562be5c18e0de6f523a624fcac91fa2e582a2694a8dfbd&ascene=1&uin=MjAzNDY1ODcwMg%3D%3D&devicetype=Windows+10&version=62070158&lang=zh_CN&exportkey=AcCKv30f7uXDEXpluuy9ZyY%3D&pass_ticket=bsOi98qwF0uGoGAaJNml9Hc1IPDB7TRF7ImnX1qC0scVZPr7accRbvWvGNBoOiOH)

## 共识机制（数据的处理）

>避开了[拜占庭将军问题](https://mp.weixin.qq.com/s?__biz=MzUxODk1OTA0OA==&mid=2247486019&idx=1&sn=29d41e922261f055345c23ad6927a6bd&chksm=f981b0e4cef639f20ba474323fe09a12bc9f02334500b545ced6821e878620256e8c9c436373&scene=0&xtrack=1&key=9ecd34f3bc5b51bcb6b80c6f7cb5e35738804220f4c2ad4cba088bde6c0e5ec55c3e2c682b5f5a6c74f75cf2e09255ca5bfc1b5d291d09bd3cc3019f1b70e656b0fdb63628dd77c83d6869bbeb221cc3&ascene=1&uin=MjAzNDY1ODcwMg%3D%3D&devicetype=Windows+10&version=62070158&lang=zh_CN&exportkey=AeL%2BCuth0h%2Bq%2BikVIxm%2Bc9E%3D&pass_ticket=UGCHR3zToo%2Fd2y%2BkQ4JHQoWRb%2FodqadVLLyGY2BLNcd42Ct8v4nuzxa2tH%2F7UjTB)，解决了分布式账本中每个节点如何记账 和 不同节点间如何交换信息达成一致 这2个问题。

1. PoW (Proof of Work) 共识机制

    1. 竞争记账（算力竞赛），获得记账权的节点所打包的区块会连接到链上，并被全网其他节点记入到个各自的小账本中

    2. 它也是BTC的挖矿原理，获得记账权的节点能得到一定的BTC作为奖励

    3. 除非有人掌握全网51%以上的算力，否则整个网络的任何东西都是无法被篡改的

2. PoS (proof of Stake) 共识机制

    1. 权益记账，提高了节点处理数据的门槛（如必须抵押一定数量的代币）
    2. 谁持有的代币多，谁就越容易获得出块的权利
    3. 它解决了PoW中的资源浪费、效率低下等问题；但很容易造成强者恒强的局面
     
## 智能合约（数据的应用）


<img src="https://graph.baidu.com/resource/112ef5058cdcafacac76a01575717065.jpg" />