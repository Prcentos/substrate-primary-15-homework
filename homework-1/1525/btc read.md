# task1



## 比特币白皮书观后感

比特币网络可以理解成就是一个超级账本,区块就是页,时间戳就是页码.区块地址等信息就是链条形式的装订线.该账本没有结尾,可以无限书写.在这个账本中作为个人参与者最关心的资产交易就存储在区块当中.那么这个区块记录的交易是什么样的?

比特网络交易使用的是UTXO模型.任何一个交易都是由若干个输入和若干个输出构成.一个输入指向前面区块的某个输出(矿工奖励除外).所以任何交易都可以溯源.没有被交易的输出被称之为UTXO(未花费交易输出),整个网络UTXO之和等同于已给出矿工奖励之和.个人钱包的余额就是扫描整个网络中被个人地址标记的UTXO. 输出余额增加,输入余额减少.这些信息有关系型数据库存储.所以可以做到快速查询.比特网络为了保证安全交易,有公钥私钥比对和签名算法.

账本要维护下去,必须要物理机去存储,这也就是节点(矿工).比特币有一套pow激励机制去奖励算出工作量证明的节点.这些节点可能是个人,可能是公司,可能是组织,甚至可能是国家.他们共同组成比特币网络.如果世界的某一个角落发生了不可抗的灾难.国家可能灭亡,银行可能倒闭.但是在比特网络中,世界的另一端还存放着你的资产.只要保留密钥即可轻松获取.

比特币网络是一种开创性的支付方式.不需要第三方对自己的资产进行管理.更不会出现打着”为了你好,为了你财产安全”进行限额,冻结等现象.在现阶段做到了个人财产神圣不可侵犯.







