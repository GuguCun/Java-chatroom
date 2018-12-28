 <center> <font face="微软雅黑" size="18px">在线聊天室</font> </center>
 <center> <font face="微软雅黑" size="18px">产品需求说明书</font> </center>

---
<br>

### <font face="微软雅黑"> > 版本历史 </font>


|  版本号 | 发起者 |  参与者     |  修改日期  |   备注   |
|:------:|:------:|:------------------------------:|:----------:|:--------:|
| PRE1.0 |  <font face="微软雅黑">杨林</font>  | <font face="微软雅黑">周诗燕、李荣霞、余江波、蒲亚军</font> | 12/27/2018 | <font face="微软雅黑">项目创建</font>|
| &nbsp; |        |                                |            |          |
| &nbsp; |        |                                |            |          |
| &nbsp; |        |                                |            |          |

<br>

### <font face="微软雅黑"> > 文档介绍 </font>

1. <font face="微软雅黑"> __文档目的__ </font>
    - <font face="微软雅黑"> 为开发小组成员、客户之间提供共同的协议而创立基础，描述用户软件的宏观需求 </font>
    - <font face="微软雅黑"> 根据客户要求，准确描述功能性和非功能性需求，给产品的需求规格说明书提供基础 </font>
    - <font face="微软雅黑"> 本说明书的预期读者为开发小组成员及甲方负责人。本说明能让甲方代表更好地了解本系统，减少彼此之间交流的困难和开发中因为需求不明确而产生的不必要的麻烦 </font>



2. <font face="微软雅黑">__文档范围__</font>
    - <font face="微软雅黑">适用于用户注册、用户登陆、用户列表管理、发送消息（私聊,广播）、接收消息、消息记录处理、用户退出功能的整个过程 </font>



3. <font face="微软雅黑">__适用对象__</font>
    - <font face="微软雅黑">项目经理</font>
    - <font face="微软雅黑">软件工程师</font>
    - <font face="微软雅黑">测试工程师 </font>

<br>

### <font face="微软雅黑"> > 产品介绍 </font>

1. <font face="微软雅黑"> __产品目的__ </font>
    - <font face="微软雅黑">本项目的开发是基于软件学院软件工程专业学生在学习《JAVA软件开发技术》或《C#软件开发技术(A)》课程后的一门实践课程，重在通过本项目的开发锻炼学生的编码能力，了解软件开发的整个过程，培养学生的逻辑思维能力，使学生养成良好的编程习惯和培养学生的团队合作意识</font>
    - <font face="微软雅黑">通过本项目的开发，不但巩固课堂上所学的面向对象的相关知识，同时也融入了当前市场流程的、适用的课堂上未讲授新技术（基于Socket的网络编程），从而增强学生的知识面，提高学生的学习兴趣和学习积极性</font>


2. <font face="微软雅黑">__面向用户群体__</font>
    - <font face="微软雅黑">本系统主要面向局域网的成员，能够帮助他们在局域网内进行沟通交流、可以群发和私聊等功能</font>


3. <font face="微软雅黑">__产品应当遵循的标准或规范__</font>
    -  <font face="微软雅黑">专业编号遵循国家统计规范</font>
    -  <font face="微软雅黑">数据库的设计遵循本项目要求的统一设计规范</font>
<br><br>

4. <font face="微软雅黑">__产品适用范围__</font>
- ✅
    - <font face="微软雅黑">多人线上聊天</font>
    - <font face="微软雅黑">点对点聊天</font>
- ❎
    - <font face="微软雅黑">在线语音聊天</font>
    - <font face="微软雅黑">在线视频通话</font>


<span>5.</span> <font face="微软雅黑">__角色及其作用__</font>

<table>
  <tr>
    <th width="20%"><font face="微软雅黑">角色名称</font></th>
    <th width="80%"><font face="微软雅黑">职责描述</font></th>
  </tr>
  <tr>
    <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">管理员</font></td>
    <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">负责管理本系统的聊天用户</font></td>
  </tr>
  <tr>
    <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">聊天者</font></td>
    <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">负责发送和接收聊天信息</font></td>
  </tr>
  <tr>
    <td>&nbsp;</td>
    <td></td>
  </tr>

</table>

6. <font face="微软雅黑">__产品的功能需求__</font>
- <font face="微软雅黑">功能需求表格</font>

<table>
    <tr>
        <th width="15%"><font face="微软雅黑">功能类别</font></th>
        <th width="15%"><font face="微软雅黑">功能名称</font></th>
        <th><font face="微软雅黑">描述</font></th>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">注册</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">注册</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">服务器根据用户输入的用户名进行注册，将用户信<>息保存在服务器的用户管理列表中（学生在实训时可根据情况保存信息到数据库中）</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">登陆</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">登陆</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">客户端运行，用户输入用户名登录到服务器，服务器需要做检测是否重复登录，如果时则向用户提示“用户已登录”的消息。如果成功登录，服务器将用户的登录信息保存到服务器端的用户列表，并将登录信息广播给其他的用户，提示XX进入系统</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;" rowspan="2"><font face="微软雅黑">发送消息</font></td>
        <td style="text-align: center; vertical-align: middle;" ><font face="微软雅黑">私聊</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">客户端在用户列表中选择一个好友时，将消息群发给这个用户 </font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">群聊</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">客户端在用户列表中选择好友为“所有”时，将消息群发给所有的在线用户；服务端则是将消息广播给所有的用户</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">转发消息</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">转发消息</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">服务器解析收到的消息，提取目的端用户名，并把消息转发到目的端。可分为私聊和群聊（广播）消息</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">接受消息</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">接受消息</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">客户端接受服务器发送或转发过来的消息并解析后做相关显示处理，如用户上线，则将上线的用户加到用户列表中，用户退出，则将退出的用户从用户列表中移除等；服务器接受消息并解析后做相关处理，如收到用户登录消息，则在服务端的用户列表中添加用户，并同时更新用户显示列表。当收到用户退出的消息，则在服务端的用户列表中移除用户，并同时更新用户列表，其他的消息则进行相应的转发</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">消息保存</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">消息保存</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">服务器在收到消息后将消息保存在文本文件中</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">退出</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">退出</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">客户端向服务器发出退出的消息，服务器把该客户信息从用户列表中删除，并更新在线用户列表</font></td>
    </tr>
</table>


- <font face="微软雅黑">功能结构层次图</font>

![img](https://i.loli.net/2018/12/28/5c258c22cbb79.jpg)
<br><br>


7. <font face="微软雅黑">__产品的非功能性需求__</font>
- <font face="微软雅黑">用户界面效果图</font>

    ![img](https://i.loli.net/2018/12/28/5c258f0d174f5.jpg)

<br>

- <font face="微软雅黑">服务器端效果</font>

    ![img](https://i.loli.net/2018/12/28/5c258f0cec42a.png)

<br><br><br>

- <font face="微软雅黑">软硬件环境需求</font>
<table>
    <tr>
        <th width="40%"><font face="微软雅黑">需求名称</font></th>
        <th width="60%"><font face="微软雅黑">详细要求</font></th>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">注册</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">用户名注册</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">登陆</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">查看数据库是否有账号及密码</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">接收消息</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">用户接受到其他用户的消息</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">回复消息</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">用户可以回复其他用户的消息</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">保存消息</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">默认自动保存用户消息,可删除</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">退出</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">退出聊天界面</font></td>
    </tr>
</table>

- <font face="微软雅黑">产品质量需求</font>
<table>
    <tr>
        <th width="30%"><font face="微软雅黑">需求名称</font></th>
        <th width="60%"><font face="微软雅黑">详细要求</font></th>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">正确性</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">确保发送消息和接收消息不丢失</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">健壮性</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">局域网内，并发数达到50个时程序运行稳定</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">可靠性</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">传输数据不丢失</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">性能、效率</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">无</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">易用性</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">界面简单大方</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">清晰性</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">无</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">安全性</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">可考虑数据传输的加密</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">可扩展性</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">在有条件的情况下、预留文件传输、语音聊天等接口</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">兼容性</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">兼容winxp、win7、win10</font></td>
    </tr>
    <tr>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">可移植性</font></td>
        <td style="text-align: center; vertical-align: middle;"><font face="微软雅黑">...</font></td>
    </tr>
</table>

8. <font face="微软雅黑">__其他需求__</font>
- <font face="微软雅黑">需求建模</font>
- <font face="微软雅黑">需求确认</font>

<br>

### <font face="微软雅黑">⌨️ 团队成员</font>



|                          ![y](https://i.loli.net/2018/12/28/5c25f29ba18a4.jpg)                           |                          ![z](https://i.loli.net/2018/12/28/5c25f267d7bec.jpg)                          |                          ![l](https://i.loli.net/2018/12/28/5c25f36f30cb6.jpg)                          |                            ![Y](https://i.loli.net/2018/12/28/5c25f36f3ba85.jpg)                             |                           ![p](https://i.loli.net/2018/12/28/5c25f36f2d665.jpg)                           |
|:--------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------:|
| <font face="微软雅黑">__杨林__<br>[<font face="微软雅黑">@Kaons</font>](https://github.com/Kaons)</font> | <font face="微软雅黑">__周诗燕__<br>[<font face="微软雅黑">@GuguCun](https://github.com/GuguCun)</font> | <font face="微软雅黑">__李荣霞__<br>[<font face="微软雅黑">@SanYueM](https://github.com/SanYueM)</font> | <font face="微软雅黑"> __余江波__<br>[<font face="微软雅黑">@YuJiangBo](https://github.com/YuJiangBo)</font> | <font face="微软雅黑"> __蒲亚军__<br>[<font face="微软雅黑">@xuebapu](https://github.com/xuebapu) </font> |
|                                  <font size="5"> ⚙️🔧 </font>                                        |                                  <font size="5"> 📝📖</font>                                       |                                  <font size="5"> 💬🎨</font>                                       |                                  <font size="5"> 📁🔍</font>                                          |                                  <font size="5"> 🤔💡</font>                                  |

<br>

### <font face="微软雅黑">🔗 [项目主页](https://github.com/Kaons/Java-chatroom)</font>
> <font face="微软雅黑">该项目是基于学校专周实训而建立的,使用语言为JAVA,数据库为MySQL,利用JAVA自带的包来绘制GUI, 开发时长为2个星期,利用GitHub来进行版本控制,通过五人以小组的形式对这几部分的整合来实现最终多人聊天室的功能.</font>
