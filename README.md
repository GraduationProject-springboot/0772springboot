# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0772springboot商务安全邮箱邮件收发

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=127)


# 课题背景
随着计算机网络的发展，人与人之间信息传输的时间大为缩短。许多文件都是以电子邮件的形式来传送；通常使用过计算机的人，或多或少都会用到Email来传输信息。通过电子邮件，人们可以进行文字、图片、视频、声音、数据文件等的传递。随着Internet网和WWW网的广泛普及，电子邮件的使用迅速增多起来。电子邮件的使用不仅在数量上有突飞猛进的发展，其重要性日益增加。据IDC（国际文献资料中心）统计，目前全球电子邮箱总数已超过5亿。而据CNNIC（中国互联网络信息中心）的最新调查，中国网络用户拥有E-mail帐号的平均值为2.6个，用户平均每周收到电子邮件数为12.9封，发出电子邮件数为8.2封。这说明电子邮件已不只是电话的替代品，它可以而且已经在广泛地应用着。当然，电子邮件也为人们带来了不利的一面。由于其接收发送电子邮件很少受到限制，造成电脑病毒、大量的垃圾邮件盛行，甚至个人隐私及安全受到了严重的威胁。但是，电子邮件作为当今社会主要的信息传播载体，发展趋势不会因此而停止。
## 1.2 研究现状
邮件系统的核心部分是数据库，包括元数据MD（meta data）和用户数据UD（userdata）部分。一般在系统结构上将MD和UD服务器置于局域网，从物理结构上断绝了与外部的直接联系。内网用户发送的认证请求，由接收服务器（如webserver 或POP3 server）代理，通过内网专有协议访问用户数据库，确保操作安全可靠。内外网分开的结构也同时减轻了网络流量负担。

邮箱的用户模块应队对应相应的监护过程。若某一服务处理模块出现故障，与之通信的模块会自动停止数据传送，防止由于反复的连接尝试造成此服务模块的性能下降，保证系统其他模块的正常运作，不会因为故障服务模块产生连锁反应，这样可以正常的同步安全监护信息；同样若某服务程序模块因故障下线，由于模块具有服务监视功能，将会自动重起服务，并保存服务运行日志，方便管理员查阅，增强系统运行的可靠性。

固定的通信端口是主机安全运行的隐患，不法分子向通信端口发送大量非法数据，致使服务瘫痪。所以，支持隐蔽重要的服务端口、及时修改端口号、设置端口访问限制、主要系统内部服务通信协议自行开发设计、设计邮件系统的核心进程由非超级用户权限运行等措施，是邮件系统确保安全的手段。
## 1.3 研究内容
本课题研究的是安全商务邮箱，应用于一个局域网的商务集体，为了防止数据库的安全问题发生，取消了邮箱的注册功能，取而代之的是超级管理员，超级管理员拥有监护邮箱系统和增删用户的权限，本系统仅供商务内部使用，这样便于监视，同时为了防止外部的邮件攻击，采用了朴素贝叶斯安全算法，通过计算风险邮件的几率将垃圾邮件攻击置于服务器之外。
# 二、系统分析
## 2.1业务分析
普通用户用例图

![](/md/blog.003.png)

用户1用例图

![C:\Users\17977\Documents\Tencent Files\1648448894\Image\C2C\{BC8B49A1-E14F-BF51-ECB1-474C97EE4BD8}.jpg](/md/blog.004.jpeg "C:\Users\17977\Documents\Tencent Files\1648448894\Image\C2C\{BC8B49A1-E14F-BF51-ECB1-474C97EE4BD8}.jpg")



管理员用例图

![](/md/blog.005.png)
## （A. 业务分析是在系统开发之前，对系统未来使用情况的分析，主要通过用例图来描述，用例图要涵盖各种用户 角色；对于复杂或关键的业务，还可通过业务 流程图或协作图做进一步描述。画出用例图（为体现复杂工程，建设包含的用例数不少于10个），并加上详细的文字说明； B. 图形描述后，进行分析总结：这些业务有哪些特点？本课题将针对这些特点来开发系统）
## 2.2需求分析
### 2.2.1功能分析
### （经过业务分析，进一步分析归纳出系统有哪些功能点，即功能点分析，给出功能点列表）
### 2.2.2性能分析
### （分析本系统的业务特点，归纳出对性能的要求，比如响应时间、吞吐量，并发数...，等）
### 2.2.3安全性分析（可选）
### （分析本系统的业务特点，归纳出对安全性的要求，比如防信息串改、网络攻击...，等）
### 2.2.4开发环境分析
### （A.分析本课题属于哪种业务场景？为此选择哪些开发工具？B.说明系统运行对硬件和系统软件的要求都有哪些？）
## 2.3可行性分析
## （说明本系统的经济可行性及技术可行性。）
3. # 系统总体设计
## 3.1 功能模块设计
## （根据业务分析和功能点分析，设计系统功能模块，给出功能模块图，并进行详细文字说明。）

## 3.2 架构设计
## （A.说明本课题的业务场景或功能模块有哪些特点，因而采用哪种技术架构，或改进了哪种技术架构、或自行设计了哪种技术架构？  B.画出系统技术架构图,并进行详细文字说明）

## 3.3 数据库设计
## （画出E-R图，给出相关数据库表设计，并进行详细文字说明）
## 3.4 接口设计
## （A.本系统与用户的交互接口或界面设计； B.本系统与本机系统的接口设计，如日志设计等；C.系统各模块之间调用接口设计； D.数据库接口设计：如采用JDBC接口或MyBatis等。上述A、B、C、D可根据实际课题情况进行取舍）
## 3.5 安全性设计（可选）
## （如随机数字验证码、图形验证码、手机验证码、email验证码、防SQL注入等）

# 四、系统详细设计
## 4.1 对象设计
## （针对分析归纳出的主要对象画出一个类图，为体现复杂工程，建设包含的类不少于10个，并给出详细文字说明）

## 4.2 交互设计
## （类之间的交互用交互图或协作图来描述，建议交互图或协作图数量不少于5个，并给出详细文字说明）

## 4.3 流程设计
## （针对主要的模块或对象，画出程序流程图或状态图，有15个以上矩形框或判断框的程序流程图至少需要有5个，并给出详细文字说明）
5. # 系统实现
## 5.1编程规范
## （说明遵循了哪些编程规范，如驼峰命名法、适当的注释等）

## 5.2 配置管理（可选）
## （说明在系统实现过程中是否采用了配置、版本等代码管理？）

## 5.3 功能实现
（给出主要模块的实现截图，及其关键代码在附录中的编号（正文部分不放代码，关键代码都放到附录中，并给其编号），并给出详细文字说明）

# 系统测










