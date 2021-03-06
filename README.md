# 信息系统项目管理师
> 复习了2个月考过了信息系统项目管理师，分数刚好过线（57 49 45），这里分享下相关笔记。  
> 建议先根据官方教材简单过一遍，然后开始刷真题背范文，遇到问题再回去翻教材。  
> 知识点主要分2块：信息技术和十大管理  





# 信息化和信息系统
##### 信息的质量属性（精完可及经验安）
1. 精确性
2. 完整性
3. 可靠性
4. 及时性
5. 经济性
6. 可验证性
7. 安全性


##### 信息化从小到大5个层次
1. 产品信息化
2. 企业信息化
3. 产业信息化
4. 国民经济信息化
5. 社会生活信息化

##### 国家信息化体系6要素
1. 信息资源。开发和利用是核心任务，是取得实效的关键，也是我国信息化的薄弱资源。
2. 信息网络。基础设施
3. 信息技术应用。是龙头 / 主阵地
4. 信息技术和产业。是信息化的物质基础
5. 信息化人才。是成功之本
6. 信息化政策法规和标准规范。是保障

##### 信息系统的生命周期
1. 系统规划（可行性分析与项目开发计划）
2. 系统分析（需求分析 提出逻辑模型  系统说明书）
3. 系统设计（概要设计 详细设计 ）
4. 系统实施（编码 测试）
5. 运行维护 
（还可以简化为立项 / 开发 / 运维 /消亡

##### 系统开发方法
1. 结构化方法（开发目标清晰化 / 工作阶段化。周期长 难以适应需求变化。）
2. 面向对象方法
3. 原型化方法（先根据初步需求快速建立一个系统模型，再次基础上与用户交流并最终实现。特点：周期短 成本低 用户参与度高）
4. 面向服务的方法（快速响应需求与环境变化，提高系统可复用性。）

##### OSI七层模型
1. 物理层
2. 数据链路层（帧 ｜交换机）
3. 网络层（IP ICMP ARP IGMP RARP ｜ 路由器 三层交换机）
4. 传输层（TCP UDP）
5. 会话层
6. 表示层（表示格式 JPEG ASCII）
7. 应用层（HTTP FTP SMTP）

##### 网络协议标准
IEEE 802.3以太网协议  802.11无线局域网

##### 网络存储技术
* 直接附加存储 DAS（直接将存储设备插到服务器上）
* 网络附加存储 NAS（即插即用 NFS）
* 存储区域网络 SAN  

##### 网络设计分层
核心层（网络主干） / 汇聚层（访问控制 过滤） / 接入层（面向用户）

##### 软甲工程
中间件
完成系统底层传输的集成，可以用CORBA
完成不同系统消息传递，可以用消息中间件
完成不同硬件和操作系统的集成，开源用J2EE

高可用性
MTTF 平均无故障时间
MTTR 平均维修时间
可用性 = MTTF / （MTTF + MTTR）


需求层次：业务需求（高层次目标要求） / 用户需求（用户具体目标） / 系统
需求获取：访谈 / 问卷调查 / 采样
需求分析：SA方法进行分析，建立模型核心是数据字典。（ER图表示数据模型 / 数据流图DFD表示功能模型 / 状态转换图STD表示行为模型。）
软件需求规格说明书 SRS ：包括范围 / 引用文件 / 需求 。。
需求分析过程：获取需求 / 需求分析 / 定义需求 / 需求验证

UML  统一建模语言：有四种关系，依赖 / 关联 / 泛化 / 实现。
UML14种图：类图 / 对象图 / 构件图 / 组合结构图 / 用例图 / 顺序图 / 通信图 / 定时图 / 状态图 / 活动图 / 部署图 / 制品图 / 包图 / 交互概览图
动态图：序列图 / 状态图 / 活动图 / 协作图（虚壮活血）
静态图：组件图 / 用例图 / 配置图 / 对象图 / 类图 （租用配对累）

类的关系：关联关系 / 依赖关系 / 泛化关系（继承）/ 共享聚集 / 组合聚集 / 实现关系
面向对象三个特征：封装 / 继承 / 多态
设计模式分为创建型 / 结构型 / 行为型

软件架构风格
* 数据流风格。 批处理和管道
* 调用_返回风格。主程序_子程序
* 独立构件风格。事件驱动
* 虚拟机风格。解释器
* 仓库风格。数据库系统/黑板

软件测试方法
* 静态测试 ，程序不运行，人工检测，代码检查等。
* 动态测试，程序运行，白盒测试黑盒测试

测试类型
* 单元测试
* 集成测试
* 确认测试
* 系统测试
* 配置项测试
* 回归测试

企业应用集成 EAI：包括表示集成（界面，黑盒） / 数据集成（白盒） / 控制集成（功能应用 黑盒） / 业务流程集成（过程） / 企业之间应用集成


##### 新技术
物联网
* 技术：传感器技术 （RFID）/ 嵌入式技术
* 三层：感知层 / 网络层 / 应用层
* 智慧城市5层功能：感知层 / 通信网络层 / 计算存储层 / 数据及服务支撑层 / 智慧应用层
*  智慧城市3个支撑体系：安全保障体系 / 建设和运营管理体系 / 标准规范体系 

5G 
速度1Gb 距离2公里

云计算类型
* IaaS 基础设施即服务
* Paas 平台即服务
* SaaS 软件即服务

大数据5V：Volume 大量 / Variety 多样 / Value 价值 / Velocity 高速 / Veracity 真实

##### 网络安全
信息的安全属性：私密性 / 完整性 / 可用性 （CIA）
安全四个层次：设备安全 / 数据安全 / 内容安全 / 行为安全
网络安全基本要素：机密性 完整性 可用性 可控性 可审查性 (前三个CIA)

信息加密解密
* 对称加密 DES AES
* 非对称加密 RSA
* Hash
* 数字签名

##### 《信息安全等级保护管理办法》的5个保护等级
1. 第一级，破坏后，不损害国家安全 / 社会秩序。
2. 第二级，对社会秩序和公共利益造成损害，但不损害国家安全。
3. 第三级，。。或者对国家安全造成损害。
4. 第四级，。。或者对国家安全造成严重损害。
5. 第五级，。。会对国家安全造成特别严重损害。

##### 信息系统规划
信息技术服务标准体系ITSS ，包含 规划设计 / 部署实施 / 服务运营 / 持续改进监督管理等生命周期应遵循的标准。

信息系统规划抽象流程：1. 分析企业信息化现状 2.制定战略 3. 规划方案和架构
详细的步骤参考企业系统规划方法

##### 信息系统规划工具
1. 制定计划可用PERT图和甘特图
2. 访谈 会议
3. 联系企业组织结构和过程，用过程_组织（P_O）矩阵方法
4. 资源/数据 RD矩阵 （归纳数据）
5. 功能法，用IPO（input process output）图表示
6. CU矩阵（生成关系Create  使用关系User）


# 十大管理及其他
![93C7A6CD-B97B-4FAB-AB56-637291B2C0D5](https://user-images.githubusercontent.com/2595251/102708725-97fccf00-42df-11eb-9718-59f474e86cda.png)


### 项目管理基础
项目是为提供一项独特产品/服务或成功所做的临时性努力。

特点：
1. 临时性：有确定的开始和结束时间
2. 独特的产品 / 服务或成果
3. 逐步完善
4. 资源约束
5. 目的性

项目目标特点：多目标性 / 优先性 / 层次性。

组织结构：
* 职能型（传统，如技术部 市场部）
* 项目型（项目经理权利大）
* 矩阵型（权利中，多头领导，弱矩阵偏职能，强矩阵偏项目）

信息系统典型生命周期模型
* 瀑布模型：计划 -> 需求分析 -> 设计 -> 编码 -> 测试 ->运行维护（结构化方法）
* 螺旋模型：原型实现与瀑布模型结合。四个象限：制定计划 / 风险分析 / 实施工程 /  客户评估 （强调风险分析，适合复杂 / 高风险系统）
* 迭代模型：水平方向为初始/ 细化 /构造 / 移交。核心工作流业务建模 / 需求获取 / 分析&设计 / 实现 /测试 / 部署
* V模型：由左右两边组成，左边代表开发活动，右边代表测试活动，用于需求明确且变更不频繁。见下图
* 原型化模型：快速开发一个原型系统，然后反复修改实现用户需求。
* 敏捷开发模型：是一种以人为核心 / 迭代 / 循序渐进的开发方法。


PDCA循环： 计划Plan -> 执行Do -> 检查Check -> 行动 Act

项目管理5大过程组
1. 启动过程组
2. 计划过程组
3. 执行过程组
4. 监督与控制过程组
5. 收尾过程组



### 项目立项管理
项目立项一般包括提交项目建议书 / 项目可行性研究 / 项目招标与投标等功能。

项目建议书：又称立项申请，是项目建设单位向上级部门提交申请的文件。（内容：项目必要性 / 市场预测 / 建设必须的条件 ）
项目招投标：
项目可行性研究内容：技术 / 经济 / 运行环境  /其他 。

可行性研究3个阶段：初步可行性研究 / 详细可行性研究 / 可行性研究报告
详细可行性研究方法：指数估算 / 因子估算  / 增量净效益法


项目论证：。。分析，为项目决策提供依据。
项目论证3个阶段：机会研究 / 初步可行性研究 / 详细可行性研究
项目评估：在可行性研究的基础上，由【第三方】进行评价分析和论证。


### 项目整体管理
项目管理包括范围 / 进度。。等几个方面，这些方面是互相影响与制约的。一般情况下先制定一个初步的整体计划，然后详细制定各个分计划。


过程：
1. 制定项目章程（输入：协议 / 项目工作说明书 / 商业论证 / 事和组 。输出：项目章程。工具：专家判断 / 引导技术）
2. 制定项目管理计划 （输入：项目章程 / 其他过程的输出结果 / 事和组。输出：项目管理计划。工具：专家判断 / 引导技术）
3. 指导与管理项目执行（要求项目经理和团队采取多种行动执行项目管理计划，完成项目范围说明书中明确的工作。输入：项目管理计划 / 批准的变更请求 / 事和组。输出：可交付成果 / 工作绩效数据。工具：项目管理信息系统 / 会议）
4. 项目监控工作（采取纠正或预防措施控制项目的实施效果。输入：项目管理计划 / 进度预测 / 确认的变更 / 工作绩效信息 。输出：变更请求 / 绩效报告。工具：分析技术 / 项目管理信息系统）
5. 整体变更控制（项目很少会准确地按照项目管理计划进行，因而变更控制必不可少。输入：项目管理计划 / 变更请求。输出：批准的变更请求 / 变更日志。工具：变更控制工具）
6. 结束项目阶段（输入：管理的计划 / 验收的可交付成果。输出：最终产品移交 / 组织过程资产更新。工具：会议）

项目章程是正式批准项目的文件。授权项目经理动用组织资源，章程是由【外部】签发的。
章程内容：项目目的原因 / 成果标准 / 总体要求 / 项目描述 / 主要风险 / 进度计划 / 预算 / 审批要求 / 委派的项目经理及其职责和职权 / 发起人姓名和职权 

项目管理计划确定了执行 / 监视 / 控制和结束项目的方式与方法。是其他各子计划制定的依据和基础，它从整体上指导项目工作的有序进行。(是项目基准)
（主要内容：项目背景 / 项目干系人 / 总体技术方案 / 所选项目生命周期 / 进度计划 / 项目预算 / 沟通管理计划。。）

项目收尾包含：项目验收 / 产品或成果移交 / 合同收尾 / 经验总结 / 更新组织过程资产 / 释放团队资源。
收尾需要提交的文件：需求规格说明书 / 系统设计说明书 / 项目质量验收报告 / 参考手册和用户指南 / 软硬件产品说明书。

项目选择方法
1. 净现值分析（未来现金流入流出都折算成现值）
2. 投资收益率 ROI = （收益 - 成本）/ 成本
3. 投资回收期分析

### 项目范围管理
项目范围（scope）是为了达到项目目标，交付产品，项目规定要做的工作。

范围管理过程
* 规划范围管理（编制范围管理计划，书面描述将如何定义 确认和控制项目范围的过程。输入：项目管理计划 / 章程。输出：范围管理计划。工具：专家判断 / 会议）
* 收集需求（为实现项目目标而确定 记录并管理干系人的需求的过程。输入：范围管理计划 / 干系人管理计划。输出：需求文件 / 需求跟踪矩阵。工具：访谈 / 研讨会）
* 定义范围（制定项目和产品详细描述的过程。输入：范围管理计划 / 需求文件。输出：项目范围说明书。工具：产品分析 / 研讨会）
* 创建WBS（将项目可交付成果和工作分解为较小的组件的过程。输入：范围管理计划 / 范围说明书。输出：范围基准。 工具：分解 / 专家判断）
* 确认范围（正式验收【已完成】的项目可交付成果的过程。输入：需求文件 / 确认的可交付成果。输出：验收的可交付成果 / 工作绩效信息。工具：检查）
* 控制范围（监督和管理范围变更。输入： 需求文件 / 绩效数据。输出：工作绩效信息 / 变更请求。工具：偏差分析）

项目范围说明书内容：产品范围描述 / 验收标准 / 可交付成果 / 制约因素 / 假设条件
工作包：是位于WBS每条分支最底层的可交付成果或项目工作组成部分。（8/80原则：至少8小时完成，总完成时间不应大于80小时）

工作分解结构Work Breakdown Structure。
范围基准：范围说明书 / WBS / WBS词典

WBS步骤：
* 识别和分析可交付成果
* 确定WBS的结构和编排方法
* 自上而下逐层细化分解
* 为WBS组件制定和分配标识编码
* 核实可交付成果分解的程度是恰当的

分解实践：
* 按项目生命周期各阶段作为第二层，可交付放第三层，需求 / 设计 / 程序 
* 按可交付成果放第二层，OA系统 / 人事系统

分解注意事项
1. WBS必须是面向可交付成果的。
2. 符合项目范围。（下层所有元素之和必须100%代表上一级元素
3. 底层应该支持计划和控制。（不但支持项目管理计划，还要让管理层能监视和控制进度和预算
4. 元素必须有人负责，并只由一个人
5. 作为指导而不是原则。（控制在4-6层，一个工作单元只能从属一个上层单元
6. 应包含项目管理工作，也要包含外包
7. 编制需要所有主要干系人参与
8. 并非一成不变

如何防止项目范围蔓延：
* 收集需求彻底理解客户需求 / 
* 变更请求都书面记录，不接受口头 / 
* 编制范围管理计划并规划控制流程 / 
* 规范确认范围过程，必须接受干系人评审 / 
* 强调完工时间重要性。


### 项目进度管理

过程
1. 规划进度管理（输入：项目管理计划 / 项目章程 / 事和组 。 输出：进度管理计划。工具：分析技术 / 会议）
2. 定义活动 （就是为了完成工作包所需进行的工作，是工作包的进一步分解。输入：进度管理计划 / 范围基准 。 输出：活动清单 / 活动属性。 工具：分解 ）
3. 排列活动顺序（是识别和记录项目活动之间关系的过程。输入：进度管理计划 / 活动清单。输出：【进度网络图】，前导图 箭线图。工具：关系绘图）
4. 估算活动资源（估算执行各项活动所需材料 人员 设备的种类及数量的过程。输入：活动清单 / 资源日历。输出：活动资源需求 / 资源分解结构RBS。工具和技术：专家判断）
5. 估算活动持续时间（根据资源估算结果来估算完成单项活动所需时间的过程。输入：活动清单 / 资源日历。输出：活动持续时间估算）
6. 制定进度计划（输入：进度管理计划 / 活动清单 /进度网络图 。输出：项目进度计划。图：甘特图 ）
7. 控制进度（监督项目活动状态，更新项目进展。输入：进度管理计划 / 工作绩效数据。输出：工作绩效信息 / 变更请求）

活动：就是为了完成工作包所需进行的工作，是工作包的进一步分解。

控制进度，缩短工期的方法：赶工 / 并行施工 / 使用高素质人员 /降低活动要求 / 改进方法 / 加强质量管理减少返工。

工作量工期估算：
1. Delphi法（专家评估
2. 类比估算法（与历史项目比较，成本低 / 准确度差）
3. 参数估算法（基于历史数据和项目参数，准确度取决于参数数据可靠性）
4. 储备分析（时间储备应对项目不确定性）

活动排序工具
1. 确定依赖关系
2. 前导图法 PDM（开始 结束 4种关系）
3. 箭线图法 ADM（箭线表示活动 / 节点表示事件， 双代号）
4. 提前量与滞后量（FS+15 ，finish后15天才可以start）

确定依赖关系：
1. 强制性依赖关系（法律或合同要求的或工作内在性质决定的。
2. 选择性依赖关系（具体应用领域的最佳实践或基于项目某些特殊性质而设定。
3. 外部依赖关系（项目活动与非项目活动之间的关系
4. 内部依赖关系（项目活动之间的紧前关系

制定项目进度计划的技术和工具
1. 关键路径法CPM （是项目中时间最长的活动顺序，决定着最短工期）
2. 关键链法CCM（建立在关键路径之上， 设置了缓冲，关键链末端为项目缓冲，其他为接驳缓冲）
3. 资源优化技术（资源平衡，会改变关键路径，一般延长。资源平滑，不会改变关键路径，活动只在浮动时间内延迟）
4. 进度压缩（赶工 快速跟进）
5. 计划评审技术 PERT（Program Evaluation and Review Technique），又叫三点估算。

三点估算：
OT 乐观时间 MT最可能时间 PT悲观时间
期望：(OT + 4MT + PT)/6   标准差: (OT - PT)/6 
正态分布 一个标准差 68%  2个95% 三个 99%

* 自由浮动时间：在不延误其【紧后】进度活动最早开始日期的前提下，某进度活动可以推迟的时间量。 = 后面活动的最早开始时间ES - 自己的最早结束时间EF
* 总浮动时间：在不延误项目【完成日期】或违反进度制约因素的前提下，某进度活动可以推迟的总时间量。 = 最晚开始时间-最早开始时间 = 最晚完成时间-最早完成时间
 
关键路径上总时差和自由时差为0
关键路径：从起点到终点历时最长的路径。（总工期）
虚工作是不占任何时间和资源的，只是为了让逻辑关系更加明确



### 项目成本管理
项目全过程所耗用的各种成本的总和称为项目成本。
成本管理就是要确保在批准的预算内完成项目。

应急储备：包含在成本基准内的一部分预算，应对已识别风险。
管理储备：特别留出的预算，应对不可预见的工作。
成本基准：经批准的按时间安排的成本支出计划。（不包含管理储备）
成本预算 = 成本基准 + 管理储备

过程
1. 规划成本（为规划和管理项目成本而制定政策和文档的过程。输入：项目管理计划 / 章程 / 事和组 。输出：成本管理计划）
2. 估算成本（对完成项目活动所需资金进行近似估算的过程。输入：成本管理计划 / 人力资源技术 / 范围基准。 输出：活动成本估算。）
3. 制定预算（汇总所有单个活动或工作包的成本估算，建立一个经批准的成本基准的过程。输入：成本管理计划 / 活动成本估算。输出：成本基准 / 项目资金需求。工具技术：成本汇总 / 专家判断）
4. 控制成本（监督项目状态，更新项目成本，管理成本基准变更。输入：项目管理计划 / 项目资金需求。输出：工作绩效信息 / 成本预测）

成本管理计划：描述将如何规划 / 安排和控制项目成本。成本管理过程及其工具与技术应记录在成本管理计划中。

成本估算步骤：1.分析成本构成，2.根据构成估算每一科成本大小，3.分析结果协调比例关系。

成本分析技术：
1. 技术分析（回收期 / 投资回报率 / 净现值）
2. 专家判断
3. 会议
4. 类比估算
5. 参数估算
6. 三点估算
7. 储备分析

成本管理技术
1. 成本汇总
2. 储备分析
3. 历史关系
4. 资金限制平衡
5. 挣值管理（重要）
6. 预测
7. 完工尚需绩效指数 TCPI
8. 绩效审查
9. 项目管理软件

一致性成本：在项目期间用于防止失败的费用。（检查 / 培训等）
非一致性成本：项目期间和项目完成后用于处理失败的费用。（返工 / 保修）

BAC 基线预算成本，【不含管理储备】
挣值分析的三个基本参数包括：计划值（PV）、 实际成本（AC）和挣值（EV 已完成工作量的预算成本）。四个评价指标包括： 进度偏差 SV、 成本偏差（CV）、成本执行指标（CPI）和进度执行指标（SPI）。
CV = EV - AC （ <0则成本超支）
SV = EV - PV    (<0则计划滞后)
CPI = EV / AC （>1 节省，如到了第5天，实际成本AC是500，但已经完成了第10天的工作量如EV 10天1000，按CPI=2，说明以100的成本创造了200元的价值）
SPI = EV/ PV （>1 提前）
ETC 待完工估算  = BAC - EV 非典型，如突然生病，病好之后绩效就恢复 = (BAC-EV)/CPI 典型，如招到水平低程序员，后面一直偏差
EAC 完成预估 AC+ETC （已发生成本+待发生成本）
（记忆 C Cost 成本 S Schedule 进度）


### 项目质量管理
质量定义：
ISO ：反映实体满足主体明确和隐含需求的能力的特性总和。
国家标准：一组固有特性满足要求的程度。

质量管理是确定质量方针 / 目标 / 职责 。

过程
1. 规划质量管理（是识别项目的质量要求和标准，并准备对策确保符合质量要求的过程。输入：项目管理计划 / 干系人等级册 / 风险等级册。输出：质量管理计划 / 质量测量指标 / 过程改进计划）
2. 实施质量保证（是审计质量要求和质量控制测量结果，确保采用合理的质量标准和操作性定义的过程。输入：质量管理计划。输出：变更请求 / 项目管理计划更新）
3. 控制质量（监督并记录质量活动执行结果，以便评估绩效，并推荐必要的变更过程。输入：质量管理计划 / 质量测量指标 /。绩效数据。 输出：质量控制测量结果 / 绩效信息）

质量管理计划：是描述如何实施组织的质量政策，以及项目团队准备如何达到项目的质量要求。
质量测量指标例子：准时性 / 故障率 / 可用性 / 可靠性 / 测试覆盖率等。
过程改进计划：详细说明对项目管理过程和产品开发过程进行分析的各个步骤，以识别增值活动。


质量保证旨在建立对未来输出（正在进行的工作）将在完工时满足特定的需求和期望的信心。（论文：质量小组对分析 / 设计 / 开发等过程进行质量审计，评估是否符合公司质量策略。如发现文档评审时不够积极）

技术和工具
* 规划阶段的技术：1. 成本收益分析法 2. 质量成本法 3. 标杆对照 4. 实验设计
* 执行阶段的技术：1. 质量审计 2. 过程分析  |? 3.七种基本质量工具 4. 检查 5. 抽样统计

质量审计用来确定项目活动是否遵循了组织和项目的政策与程序。
评审是对执行情况的一个了解审查和批准。

老7种工具：
1. 因果图（又叫鱼骨图，用来追溯问题来源
2. 流程图
3. 核查表
4. 帕累托：用于识别造成大多数问题的少数重要原因。
5. 直方图
6. 控制图（实时展示项目进展
7. 散点图（2个变量之间的关系

新7种工具：
* 亲和图（产出有组织的创意
* 过程决策程序图PDPC （目标与达成此目标的步骤关系
* 关联图（包含交互逻辑复杂情形中创新解决问题
* 树形图（表现层次分解结构
* 优先矩阵（排列出备选方案的优先顺序
* 活动网络图（箭头图 ，包含活动箭线图和活动节点图
* 矩阵图（展示关系强弱

CMMI（软件过程管理最著名的是能力成熟度模型）
包含连续式表示法与阶段表示法
连续模型按功能划分为：过程管理 / 项目管理 / 工程 / 支持
阶段式模型
1. CMMI1 初始级。过程随意混乱
2. CMMI2 已管理级。满足规定的标准与规程
3. CMMI3 已定义级。清晰的说明与理解
4. CMMI4 已量化管理级。量化目标
5. CMMI5 优化级。不断改进其过程
2种模型逻辑等价，进行评测结论相同。

ISO9000 质量管理原则：领导作用 / 过程方法 / 管理的系统方法 / 与供方互利的关系 / 基于事实的决策方法 / 持续改进 / 全员参与 / 以顾客为关注焦点

工作中质量措施：制定科学质量管理计划 / 建立质量保证体系 / 明确质量目标 / 明确质量标准规范 / 配备质量测量人员 / 加强控制与评审 / 安排充分测试

案例：使用有经验的质量人员 / 科学制定质量管理计划 / 重视测试 / 加强质量控制 / 重视质量保证 / 建立质量规范和标准 / 缺陷统计分析 / 成员质量培训 / 质量方面沟通 / 

### 项目人力资源管理
项目中的所有活动，归根结底都是由人来完成的。如何发挥人的作用，对于项目的成败起着至关重要的作用。
领导者工作涉及三方面：确定方向 / 统一思想 /激励和鼓舞

过程：
1. 规划人力资源管理（识别和记录项目角色_职责_所需技能/报告关系，并编制人员配备管理计划。输入：项目管理计划 / 活动资源需求 。 输出：人力资源管理计划。工具技术：专家判断 / 会议）
2. 组建项目团队（确认人力资源的可用情况，并为开展活动而组建团队。输入：人力资源管理计划。 输出：项目人员分派 / 资源日历。工具技术：预分派 / 谈判 / 招募 / 虚拟团队）
3. 建设项目团队（提高工作能力，改善团队氛围，以提高项目绩效。输入：人力资源管理计划 / 人员分派。 输出：团队绩效评价。工具技术：培训 / 团建 / 集中办公）
4. 管理项目团队（跟踪团队成员工作表现，解决问题并管理团队变更，以优化项目绩效。输入：人力资源管理计划 / 人员分派。 输出：变更请求 / 项目管理计划更新。工具：观察对话 / 冲突管理）

人力资源管理计划内容：角色与职责 / 项目结构图 / 人员配备管理计划

建设工具：培训 / 团建 / 认可与奖励 / 人事评测工具

人力资源管理工具和理论
* 虚拟团队（远程办公）
* 集中办公
* 团队发展阶段（形成 / 震荡 / 规范 / 发挥 / 解散 ｜ 加人或少人都是重新开始）
* 人际关系技能（领导力 / 激励 。。）
* 权力（职位权力 / 奖励权力 / 惩罚权力。。 ｜尽量避免惩罚权力）
* 冲突管理
* 激励理论（下面4个都是激励
* 马斯洛需求层次理论（生理 安全 社交 尊重 自我实现）
* 赫茨伯格双因素理论（1保健因素 2激励因素 ）
* X理论和Y理论（X：人天性好逸恶劳，缺乏进取 。 Y：相反。记忆X叉，Y Yes）
* 期望理论（一个目标对人的激励程度受2因素影响：1目标效价2期望值）

冲突特点：正常的 / 团队问题 / 应公开 / 应聚焦问题 / 聚焦现在

5中冲突解决方法
1. 撤退&回避 （将问题推迟 / 推给其他人）
2. 缓和&包容  （单方面退让）
3. 妥协&调解  （双方各退一步，一定程度满意，没有完全满意）
4. 强迫&命令  （利用权力强行解决紧急问题，一方赢一方输）
5. 合作&解决  （最理想结果）


记录成员的角色职责格式
* 层级型  规定高层次角色。
* 矩阵型 RAM，最直观，一个例子是RACI矩阵
* 文本型 ，适合详细记录

### 项目沟通

与项目成功最重要的4个因素是：主管层的支持 / 用户参与 / 有经验的项目经理 / 清晰的业务目标。这些因素都依赖项目经理和团队有良好的沟通能力。

沟通管理过程：
1. 规划沟通管理（根据干系人的信息需要和要求制定项目沟通方式和计划。输入：项目管理计划 / 干系人登记册。输出：沟通管理计划。工具技术：会议 / 沟通需求分析 ）
2. 管理沟通（根据计划，处置项目信息，促进项目干系人之间实现有效率的沟通。输入：沟通管理计划。输出：项目沟通。工具技术：沟通技术 / 信息管理系统）
3. 控制沟通（对沟通进行监督和控制，确保干系人对信息的需求。输入：沟通管理计划。输出：工作绩效信息。工具技术：会议 / 信息管理系统）

沟通管理计划内容：干系人的沟通需求 / 沟通的信息 / 发布信息的原因 。。
沟通渠道：正式 / 非正式
面对面沟通最有效

沟通方法：
* 交互式（会议 / 电话 
* 推式 （ 确保信息发送。 邮件 / 日志
* 拉式（信息量大受众多的情况 。企业内网 / 在线课堂

沟通渠道计算  n(n-1)/2 数量级n^2

### 干系人管理
项目干系人管理是指对项目干系人需求和期望的识别，并通过沟通上的管理来满足其需要 / 解决其问题。
好处：赢得更多资源 / 预测干系人对项目影响  。

干系人管理过程
1. 识别干系人（输入：项目章程 / 采购文件。输出：干系人登记手册。工具技术：干系人分析 / 会议）
2. 规划干系人管理（输入：项目管理计划 / 干系人登记手册。 输出：干系人管理计划。工具技术：会议 / 专家判断）
3. 管理干系人（与干系人进行沟通，以满足他的需求与期望，解决实际出现的问题。输入：干系人管理计划 / 沟通管理计划 / 变更日志 。输出：问题日志 / 变更请求。工具技术：沟通方法 / 人际关系技能）
4. 控制干系人参与（监督干系人的关系，调动干系人参与的过程。输入：项目管理计划 / 问题日志 / 绩效数据。输出：工作绩效信息 / 变更请求。工具技术：信息系统 / 会议）

干系人登记手册：用于记录已经识别的干系人的相关详细信息，包括基本信息 / 评估信息 / 干系人分类。（项目中干系人可能发生变化）

工具：专家判断 / 会议

干系人分类模型
* 权力 / 利益方格
* 权力 / 影响方格
* 影响 / 作用方格
* 凸显模型 ：权力 / 紧迫 / 合法性进行分类 （3维）




### 项目风险管理

项目风险是一种不确定事件或状况，一旦发生，会对至少一个项目目标如时间 / 成本 / 范围目标产生积极或消极影响。

基本属性：随机性 / 相对性 / 可变性

只能管理已知风险
识别风险是一项反复过程

过程
1. 风险管理规划（指决定如何进行项目风险管理活动的过程。输入：项目管理计划 / 章程  。输出：风险管理计划。工具技术：专家判断 / 会议）
2. 风险识别（哪些风险会影响项目。输入：风险管理计划 / 成本计划 / 进度计划。输出：风险登记册。）
3. 定性风险分析（对概率和影响进行评估和汇总，进而对风险进行排序。输入：风险管理计划。输出：风险登记册更新）
4. 定量风险分析（就识别的风险对项目总体目标的影响进行定量分析。输入：风险管理计划。输出：风险登记册更新）
5. 风险应对规划（针对项目目标制定提高机会/降低威胁的方案和行动。输入：风险管理计划 / 风险登记册。输出：项目管理计划更新 / 风险登记册更新）
6. 风险控制（跟踪已识别风险，识别新风险，实施风险应对计划。输入：风险管理计划 / 风险登记册。输出：工作绩效信息 / 变更请求）

风险管理计划：方法论 / 角色与职责 / 预算 / 风险类别 / 风险概率和影响的定义 / 跟踪。

识别风险工具：文档审查 / SWOT / 假设分析 / 专家判断 / 德尔菲法（专家达成一致）
定性风险工具：风险概率和影响评估 / 概率和影响矩阵 / 风险分类 / 专家判断
定量风险工具：定量分析和建模 / 预期货币价值分析 EMV / 决策树分析

规划风险工具技术：
消极风险应对策略：回避（改变计划） / 转嫁 / 减轻（看到冗余就是） / 接受
积极风险应对策略：开拓 / 分享 /提高 

风险控制工具技术：风险再评估 / 风险审计 / 偏差和趋势分析

风险值 = 概率 * 影响


### 项目采购管理
企业仅靠自身已无力应对激烈的竞争，而应借助供应链的力量，整合各成员企业的资源优势，形成整体竞争力。

过程：
1. 规划采购（采购什么，何时采购，如何采购。输入：项目管理计划 / 需求文档。输出：采购计划 / 采购工作说明书。工具：市场调研 / 自制外购分析）
2. 实施采购（选择合适的供方。输入：采购计划 / 采购文件。输出：合同。工具：投标人会议 / 广告）
3. 控制采购（管理采购关系，监督合同执行。输入：采购文件 / 合同。输出：工作绩效信息。工具：采购绩效评审）
4. 结束采购（输入：合同。输出：合同收尾。工具：采购审计）

采购货物入库3个条件：
1. 检验合格的产品，《进货检验记录单》作为办理入库条件之一。
2. 库房核对项目准确无误。
3. 供应商提供的运货单和到货证明。

供应商选择三大因素：价格 / 质量 / 服务。

招标
公开公平公正 / 不受地域限制 / 分公开和邀请招标 / 招标人有权选择代理机构 /   邀请应当3个以上 / 招标文件不得标明特定供应商 / 标底必须保密 / 给予投标人编制投标文件不少于20日 / 修改已发出招标文件应当在提交投标文件截止日至少15日前

投标
投标少于3个重新招标 / 投标文件截止时间后的拒收 / 截止前可修改或撤回投标文件 / 联合体去投标按资质等级较低的算 / 不得低于成本 / 评标5人以上单数 / 评标技术经济专家不少于2/3 / 追加补充不得超过10%

中标
中标后放弃应承担法律责任 / 中标通知书发出30日内签合同 

政府采购法
方式：公开招标（主要） / 邀请招标 / 竞争性谈判 / 单一来源采购 / 询价 / 其他
采购文件保存15年

符合以下情形，可采用竞争谈判：没有供应商投标或招标未成立 / 不能确定详细规格 / 招标时间不能满足用户紧急需要 / 不能事先计算出总额。
符合以下情形，可采用单一来源：只有唯一供应商 / 紧急情况不能从其他供应商采购 / 保证项目一致继续从原供应商采购

### 合同管理
类型：
* 按范围划分：总承包 / 单项承包 / 分包合同
* 付款方式：总价（范围明确） / 成本补偿 （范围很不清楚）/ 工料合同（范围不是很清楚，快速签合同）

签字盖章生效，成立地点为签字盖章地。

管理过程
1. 签订管理
2. 履行管理
3. 变更管理
4. 档案管理
5. 违约索赔管理

索赔流程：提出索赔（28天内），报送资料 ，监理答复（28天内） ，监理逾期答复后果 ， 持续索赔 ， 仲裁与诉讼

### 文档 / 配置  / 知识 
文档
三类文档 ： 开发 / 产品 / 管理
文档质量分四级：1最低限度文档 / 2内部 / 3工作 / 4正式 

配置项分为基线配置（设计文档_源码 ， 向开发开放权限）和非基线配置（计划_报告，向PM CCB开放）
配置库分为：开发库（动态库） / 受控库（主库，阶段成果） / 产品库（静态库，最终产品）
CCB 配置控制委员会（不是常设机构，可以一个人甚至兼职） 
CMO 配置管理员（编写配置计划 / 进行配置管理活动）
配置管理工具：SVN Git

配置管理主要活动：
1. 制定配置管理计划
2. 配置标识
3. 配置控制
4. 配置状态报告
5. 配置审计
6. 配置管理和交付

软件版本：X.YZ（正在修改）/ 0.YZ（草稿） / X.Y（正式）

软件产品的6个质量特性：功能性 / 可靠 / 易用 / 效率 / 可维护 / 可移植 （6大21小）
软件生存周期过程：主要过程 / 支持过程 / 组织过程。


商标有效期10年，期满需要继续使用的期满前6个月申请续展。
发明专利保护期20年，新型和外观设计专利10年
作者的署名权 / 修改权 / 保护作品完整权的保护期不受限制
软件著作权保护期50年



### 项目变更管理
变更管理，是指在项目过程中，由于一些原因对项目的功能 / 方法 /进度等方面做出改变。

组织机构：CCB（Change Control Board）项目控制委员会
通过评审手段决定是否变更，但不提供方案。

并不是所有变更都要提交给CCB

变更管理涉及角色包括：项目经理 / CCB / 变更执行人 / 配置管理员


工作程序：
1. 提出变更申请
2. 对变更初审
3. 变更方案论证（供CCB决策
4. 项目管理委员会审查
5. 发出通知并组织实施
6. 变更实施的监控
7. 变更效果评估
8. 判断变更后的项目是否已纳入正常轨道

### 安全管理
五大要素：认证 / 权限 / 完整 / 加密 / 不可否认

安全策略7定：定方案 / 定岗 /定位 / 定员 / 定目标 / 定制度 / 定工作流程

计算机信息系统5个安全保护等级：
1. 用户自主保护级（适用普通用户
2. 系统审计保护级（需要保密的重要单位
3. 安全标记保护级（地方国家机关
4. 结构化保护级（中央国家机关
5. 访问验证保护级（国防关键部门

访问控制2个重要过程：认证过程 / 授权过程
访问控制授权方案：DAC自主访问控制 / ACL访问控制列表 / MAC 强制访问控制 / RBAC基于角色的反问控制

CC标准安全审计6个部分：
安全审计自动响应功能 / 自动生成 / 分析 / 浏览 / 事件选择 / 存储 




### 其他

项目集：经过协调管理以获取单独管理所无法取得的收益的一组相关联的项目 / 子项目集和项目集活动。
项目管理：应用知识 / 过程 / 技能和工具对【项目活动】进行管理，以便满足项目需求。
项目集管理：应用知识 / 过程 / 技能和工具对【所包含项目】进行管理，以便满足项目集需求，并能获取采用单一项目管理方式所达不到的收益和控制。
组合管理：一组或多组项目组合进行管理，以达成组织的战略。

项目组合治理5个子过程：
1. 制定项目组合管理计划
2. 定义项目组合
3. 优化项目组合
4. 批准项目组合
5. 执行项目组合监督

项目组合管理实施过程：
1. 评估当前状态
2. 定义愿景
3. 实施过程
4. 改进过程




### 管理科学
最小生成树，直接关键路径
最短路径，Dijkstra算法
网络流，依次选条路径，扣除这条路径的最大流量，最后相加
决策：乐观（大中取大）/  悲观 （小中取大）/  后悔值准则（比较最大后悔值选最小）/ 其他不需要看
线性规划
后悔值：先算较好较差等的后悔值（最大的依次减去），再确定每个方案的最大后悔值，取最大后悔值最小的

### 论文模板

背景 - 过度 - 论点 - 结尾
每个过程：what 做什么/ why 为什么做 / who 谁来做 / how怎么做

【背景】2019年6月，我作为项目经理参与了某零售连锁公司的新零售平台信息系统建设项目，该项目投资共200万元人民币，建设工期为6个月，通过该项目的建设，建立了线上与线下结合的一体化平台，从而完成了电商平台和实体零售店的优化升级，实现了该公司从传统零售向新零售快速转型的战略目标。该项目涉及了公司在全省的60多个实体连锁店以及500万的顾客。该系统主要实现了以下功能：1.线上的购物平台，包括电商购物网站/APP以及微信小程序购物。2.线下无人自助零售终端，确保顾客在实体店能通过无人终端扫描商品完成自助购物。3.PDA配货扫描，实现商品配货运输全过程状态扫描。4.后台管理与ERP数据集成平台，后台基础数据维护以及与ERP数据统一交互。
该系统采用前后端分离的架构开发，服务端基于JAVA语言开发，数据库采用Mysql，使用Spring boot作为应用的基础框架。前端UI基于Javascript / CSS / HTML5等标准技术进行开发，通过AJAX通讯机制进行接口请求并渲染，使用Git作为配置管理工具。项目采用矩阵型组织结构，从各职能部门抽调主干成员，组成专门的项目团队 ，其中产品小组3人，开发小组10人，测试小组5人，运维小组3人。
【过度】由于本项目的顺利上线涉及到业务的考核，因此在本项目中，XX管理尤为重要，在本项目中，我作为项目经理除了对其他管理领域进行恪尽职守的管理外，特别对XX管理从如下几个方面进行了管理。
【论点如】
1. 规划xx管理，好的计划是成功实施项目的基础，作为项目管理计划的一部分，xx计划是关于xx的指南。
在该项目中，我非常重视xx管理计划的制定。项目启动后，就尽快对项目的xx做出规划，以保证满足项目要求的合适资源。
计划制定采用会议形式，全员参与。团队成员尽早参与，既可以使他们对项目规划工作贡献专业技能，又可以增强他们对项目的责任感和成就感。会议中，个成员踊跃发言，对项目的xx进行分析。
最终在全体参与下，最终完成一份详细的 / 科学的管理计划。
计划包含：。。。
用于指导项目如何 （后续过程。。）
2. 通过对公司组织过程资产的查询，我们发现公司有许多类似项目的管理经验可以参考，因此项目的大部分活动都选择了类比估算法。
xx活动是关键活动，我们考虑了风险因素，选择了三点估算方法。经过专家和开发成员讨论，认为乐观。。悲观。。
估算成本，三个步骤，不同的科目采用不同的成本估算方法。硬件采购部咨询市场价格 ， 软件类比估算和专家评估。
3. 控制xx，管理xx是跟踪团队的xx，提供反馈，解决问题并管理变更，以优化项目绩效的过程。作为项目的管理着，需密切关注xx
我们每周召开一次例会，各小组汇报本周工作进展。
每两周我们进行一次挣值分析，将PV（计划值）/AC（实际值）和EV挣值绘制成S曲线，进行项目偏差分析和趋势分析，根据分析结果采取相应的控制措施。SPI=0.98 CPI=0.8
私自增加了某功能，针对这种情况，首先向这名成员强调了范围基准及变更流程的重要性。其次，针对多出来的功能，要求走变更流程。
最后我们对从x到xx的整个过程进行系统的审查，找出可供其他项目借鉴的成功经验，形成组织过程资产
	
【结尾】经过我们团队不懈的努力，历时半年，本项目终于于2019年12月，通过了组织的验收，提升了该零售连锁公司的整体运营服务水平，得到了甲方的好评。本项目的成功得益于我成功的XX管理，采用了科学的xx管理方法 / 工具和技术 。当然，在本项目中，还有一些不足之处，比如：在项目的实施过程中，由于项目组1名成员因为自身原因突然离职，导致项目的团队建设出现一些小问题不过，经过我后期的纠偏，并没有对项目产生什么影响。在后续的学习和工作中，我将不断的充电学习，和同行进行交流，提升自己的业务和管理水平，能够更好地完成信息系统管理工作。

