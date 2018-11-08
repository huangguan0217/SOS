::nh@::
SendInput {Raw}
(
自助维护台进去之后什么状态，能否用iDesk修复工具检测一下。
)
Return

::gy@::
SendInput {Raw}
(
您好，我是桌面云运营团队的同事，看到您在社区上关于：“”的反馈。
)
Return

F1::
SendInput {Raw}
(
现在用的什么终端？笔记本电脑还是台式主机电脑，还是那种TC（瘦客机）云盒子？
你使用的设备导致诊断的方向完全不同。
)
Return

::bl@::
SendInput {Raw}
(
http://3ms.huawei.com/hi/group/7171/wiki_4142039.html
)
Return

::dj@::
SendInput {Raw}
(
可以稍微加快点，后台在作死的催我，我在给你挡箭。。
)
Return

::jsb@::
SendInput {Raw}
(
记事本
)
Return

::wo@::
SendInput {Raw}
(
桌面云连接类问题集中发生在周一，很忙，前面有5个用户问题。
请耐心等，等我回复。
)
Return

::dl@::
SendInput {Raw}
(
TC断连问题，经常发生在TC的网络端口问题，也就是你本地，换一个工位测试一下，是否在周一的时候，那个网络端口流量所在的路由线路繁忙。

因为我不知道你在云上从事什么软件开发和调试什么参数，应用环境都不知道，我感觉你在掉线的时候，应该回忆一下是否有特定操作导致？

很简单：

- 如果掉线了，马上连，也可以连上，桌面云无故障，你本地的设备和网卡问题。

- 如果掉线了，马上连，依然连不上，还是各种报错，那就是云上故障。

(8-9成以上的TC断连都是本地工位网口故障。)

你可以拿到其他同事不掉线的工位网口上测试。
)
Return

::cs@::
SendInput {Raw}
(
http://support.huawei.com/hedex/hdx.do?docid=DOC1100354229&path=PBI1-7275736/PBI1-9855706/PBI1-9857348/PBI1-21686573
)
Return

::sfy@::
SendInput {Raw}
(
Hi, This is Desktop Cloud Team, due to the current limited Desktop Cloud resources, led to some server can't produce more VM for new employee, according to our operation policy:

(1). Please keep only one Desktop Cloud for your ordinary working and recycle other idle Desktop Cloud;
(2). If you want to keep multiple Desktop Cloud for your project, please describing te reasons, we are going to inform your department of third level supervisor, I'm really appreciate it. (Remark: $300/Year/VM)

Desktop Cloud Recycling link (Please submit by youself.):
http://w3.huawei.com/hicloud/portal/ReleaseDesktopAction.do?method=toCreateWorkflow&taskVO.workflowName=releaseVm&catagoryId=22&requestId=24
)
Return

F2::
SendInput {Raw}
(
- 问：通过【自助维护台】进去之后，系统当前现状？高阶桌面云用户用iDesk连接修复工具检测问题出来？
  答：
- 问：万一【自助服务台】是黑屏，请务必强制重启，等5分钟左右再去打开【自助维护台】。
  答：
- 问：最近有修改桌面云Path环境变量？
  答：
- 问：是否有禁用桌面云本地连接（网卡）还有http服务？
  答：

以上问题有助于我诊断问题，请答复。
)
Return

::ty@::
SendInput {Raw}
(
- 好吧，我这边看了，很难复现这个问题，因为我和你平时工作应用场景不一样。

- 待下次卡慢的问题复现的时候，拉我进入会议，你那边展示一下，这样，我可以邀请深圳绿区局点负责人，看下当前服务器所在的节点压力是否很高压。

- 上面提到内存小的问题，你是开发环境下，那个编程软件所占用内存很高？利用率大概多少个百分点？
   因需建议：去桌面云用户社区，申请内存调优，调整到16G的内存。
   地址：http://3ms.huawei.com/hi/group/7171/threads.html?t_type=ask
)
Return

::bq@::
SendInput {Raw}
(
搬迁其实很快的，数据华为自研的iDesk工具迁移，除了基本的办公应用软件默认自带，其余编程环境变量，额外的软件需要自己重新安装。
)
Return

::qx@::
SendInput {Raw}
(
Sorry, 机制被修改了，权限被收回，现在回收桌面云的主动权在用户手里。
)
Return

::cz@::
SendInput {Raw}
(
升腾TC（C92/CT5000/GI945）：

        （1）重启TC终端，启动时按住CTRL键不放，C92TC则需要不停的点按CTRL，进入TC的配置界面。

        （2）  然后再按CTRL＋U，直到现restored configuration.

        （3）  选中restored configration，按ENTER键，TC即会恢复出厂设置并重新启动。
 
 [备注：实达TC（ST5110）：在TC界面点击左下角开始--控制中心--恢复系统配置--确定即可]
)
Return

::tc@::
SendInput {Raw}
(
- 让用户【meikang WX606461】把盒子拿到其他工位上，同事正常连接桌面云上，测试，辨别：是盒子问题还是用户网口问题。

- 让用户【meikang WX606461】在其他同事工位TC盒子上登录，看下是否云上有问题，是否正常连接桌面云。里。
)
Return

::vda1@::
SendInput {Raw}
(
https://onebox.huawei.com/v/3e874c256e819d6a9884ebd56ac8c303
)
Return

::vda2@::
SendInput {Raw}
(
https://onebox.huawei.com/v/090b62b8c685f18f30af75f3ad7249c8
)
Return

::tz@::
SendInput {Raw}
(
Okay，我把所有名单统计完之后，会将【数据搬迁手册】依次通过邮件传达给大家。
)
Return

::cf@::
SendInput {Raw}
(
对，没错，我们只触发搬迁，哪怕锁屏，这个进度依然有序进行。
)
Return

::hdp@::
SendInput {Raw}
(
- 确保TC（云盒子）的系统版本补丁，有一行字，关于HDP的补丁信息，你待会可以检查一下，返回至桌面云登录界面（输入账号和密码地方），键盘上按Ctrl + Alt + A 可以弹出一个窗口，看下补丁信息，是否有HDP字样的补丁。（这种原因占比很大）
)
Return

::ms@::
SendInput {Raw}
(
@刘星? 用户【胡卫东(h00425507) 】频繁启动异常（表现为启动慢）联络我，已多次出现，15-20分钟，能进入系统后，CPU和内存使用占用率很低，波动不大，但操作异常缓慢，是否可以升级为华为自研云，便于北区用户【胡卫东】效率办公？
)
Return

::rx@::
SendInput {Raw}
(
请联系IT热线28560160，指定IT负责人为您处理，他们有各地区详细的IT问题处理人指定列表。
)
Return

::ls@::
SendInput {Raw}
(
https://onebox.huawei.com/p/1baf36d1174aa3ed3d94a1a45a123b1d
)
Return

::framework@::
SendInput {Raw}
(
https://onebox.huawei.com/p/1baf36d1174aa3ed3d94a1a45a123b1d
)
Return

::hda@::
SendInput {Raw}
(
https://onebox.huawei.com/p/95ce41311af78714374f3c3fa1d11f8e
)
Return

::xt@::
SendInput {Raw}
(
该用户的桌面云，预计最后一次重启时，有Windows Update （补丁）信息更新，伴随开机。但可能耗时很长，相对于平常桌面云重启时间来比，期间，可能人为的强制重启，导致进行特定补丁信息被中断安装（现在系统白屏，无法加载启动）。

结论：
安全模式也无法进入系统，则建议该用户重装系统电子流：http://w3.huawei.com/hicloud/request/resetDesktop.do?method=toCreateWorkflow&taskVO.workflowName=reBuildVm&catagoryId=22&requestId=28

（桌面云重装Windows 7系统，不影响用户C盘和其他盘符的数据，勿担心，这个不同于传统PC格盘重装系统）
备注：提交之后，指定IT负责人会处理该用户的请求。

注意事项：遇到电子流无法提交，请将“重装日期”，比当前时间快20分钟以上即可。
)
Return

::espace@::
SendInput {Raw}
(
C:\Users\xxxxxxxx\AppData\Roaming\eSpace_Desktop
)
Return

::gj@::
SendInput {Raw}
(
因为重启没法从系统分配的内存上重新加载，关机会完整的释放服务器上的节点，崭新加载你所拥有的资源。
)
Return

::vm@::
SendInput {Raw}
(
Hi, ，南京Y3的桌面云要下线了：

方式一：我看到你已经拥有另外一台：杭州非研发，绿云桌面云，你可将数据搬迁到杭州桌面云。

方式二：是否需要另外下发一台南京Y6（研发）的桌面云？
)
Return

::sd@::
SendInput {Raw}
(
您好，我们是桌面云团队，WeLink直播试点测试，请告知我们，你TC的IP地址，点桌面云最小化按钮，返回到TC最原始，登录界面，点击Start（开始）---Control Center（控制中心）---双击Network即可看到TC IP

或者，退回到登录界面，鼠标移动到如下图，可以看到TC的ip地址：

)
Return

::ly@::
SendInput {Raw}
(
桌面云请留言，因为有时候问题很多，一通电话，我可能处理别的用户桌面云问题，就很容易忽略了你的问题，因为没有文字记录。

)
Return

::yf@::
SendInput {Raw}
(
出差？

- 查询是否具备在iAccess下访问黄云（研发）的权限：
http://w3.huawei.com/soho/user_login.do

参考：http://its.huawei.com/servicedesk/itservice/#/caseDetail.html?docId=00151029621967042253005056b878c7&viewsource=search
)
Return
	
::wlan@::
SendInput {Raw}
(
若直接在公司园区，请连接wlanaccess2.0wifi，断开iaccess，认证spes
)
Return

::qf@::
SendInput {Raw}
(
查看你当前用的操作系统，区分旧云还是新云，点击下面，查看计算机名。
)
Return

::wh@::
SendInput {Raw}
(
工你好，关于武汉调研桌面云问题，看到关于：“”，运营团队在跟进该问题。
)
Return

::jy@::
SendInput {Raw}
(
新云如果没啥问题了，可以释放旧云了。

就几秒钟，填下释放电子流：http://w3.huawei.com/hicloud/portal/ReleaseDesktopAction.do?taskVO.workflowName=releaseVm&catagoryId=22&requestId=24&method=toCreateWorkflow
)
Return
	
::xz@::
SendInput {Raw}
(
Okay，那按照下面，在你的台式电脑或者便携笔记本上完成以下操作：

- 关闭Internet Explorer（IE）浏览器，在你的PC上先运行：ReceiverCleanupUtility_2.2.0.1.exe （下载地址：http://3ms.huawei.com/hi/group/7171/wiki_5113735.html）

- 后安装：citrixreceiver14.11.exe （安装期间，有个单点配置，跳过忽略，关闭它）

- 重启你的个人电脑（PC设备），打开Internet Explorer（IE）浏览器访问：https://yun.huawei.com/ 重新登录，测试结果告知我。
)
Return
	
::tcip@::
SendInput {Raw}
(
鼠标划至正上方--弹出的菜单栏--点击主页home page--回到TC界面--左下角开始--控制中心--网络--看到的TC ip地址，发我下，谢谢
)
Return

::wht@::
SendInput {Raw}
(
你指的【自助维护台】进不去：
1. 闪烁了一下，连自助维护台都的窗口都不弹出来？（通常发生在台式电脑 OR 便携笔记本电脑）
2. 通过【自助维护台】瞄了一下，发现系统一直卡在Windows 7的启动界面？
3. 弹出了【自助维护台】，但它提示报错（比如中断连接），这种只能强制重启你的办公桌面云。（我们接手也只能通过自助维护台处理）

哪种，回个数字给我即可。
)
Return

::dx@::
SendInput {Raw}
(
办公桌面云掉线，9成是用户TC所在的工位网络端口故障，你需要做的，是让掉线的用户，去其他正常办公的TC上登录自己的桌面云，如果也掉线，意味着云上故障，如果不掉线，如前面所说，工位网口问题，请联系本地IT网络查看，请甄别，测试结果告知我。
)
Return

::cp@::
SendInput {Raw}
(
磁盘拓容：
http://w3.huawei.com/hicloud/portal/modifyDiskAction.do?method=toCreateWorkflow&taskVO.workflowName=expandDisk&catagoryId=22&requestId=25
)
Return

::br@::
SendInput {Raw}
(
别人电脑（设备）上测试可以登录你的办公桌面云？
)
Return

::sl@::
SendInput {Raw}
(
换个思路，将你的TC盒子和同事的盒子互换到底是工位网口问题，还是盒子问题，这样清晰明了。
)
Return

::cui@::
SendInput {Raw}
(
Hi 工，关于用户【WX196910】的桌面云问题，我看到你是他责任人，但我通过很多方式，联系不到他。

名下这台桌面云：nkgy3twx1969101要下线，如没有数据，可以回收释放。（该服务器集群寿命到期维护了）
)
Return


::1@::
Sleep 150
; |-----------------------------------------------------|
m =   zwx627100         
; |-----------------------------------------------------|
mm = 3wzuw2#!
; |-----------------------------------------------------|
SendInput {Raw}
(
%m%
)	
Send {Tab}
Sleep 150
SendInput {Raw}
(
%mm%
)
Return

::11@::
; |-----------------------------------------------------|
mm = 3wzuw2#!
; |-----------------------------------------------------|
Sleep 150
SendInput {Raw}
(
%mm%
)
Return 

::2@::
Sleep 150

; |-----------------------------------------------------|
m =   l00472266
; |-----------------------------------------------------|
mm =  ljl@00472266
; |-----------------------------------------------------|
SendInput {Raw}
(
%m%
)
Send {Tab}
Sleep 150
SendInput {Raw}
(
%mm%`
)
Return

::22@::
; |-----------------------------------------------------|
mm =  ljl@00472266
; |-----------------------------------------------------|
Sleep 150
SendInput {Raw}
(
%mm%
)
Return

::3@::
Sleep 150
; |-----------------------------------------------------|
m =   ctuvds1
; |-----------------------------------------------------|
mm =  EDC4rfv5tgb.
; |-----------------------------------------------------|
SendInput {Raw}
(
%m%
)
Send {Tab}
Sleep 150
SendInput {Raw}
(
%mm%`
)
Return

::33@::
; |-----------------------------------------------------|
mm =  EDC4rfv5tgb.
; |-----------------------------------------------------|
Sleep 150`
SendInput {Raw}
(
%mm%
)
Return

::qx@::
SendInput {Raw}
(
额。张工，这个进度，如果实在会耽搁下午工作，可以点击取消，临近下班后，再去触发搬迁。一个晚上是可以的。
不用担心：
- 每次搬迁的启动，不受第一次影响，依然全盘扫描文件。
- 文件不会重复，iDesk会基于已传输过来的文件，略过迁移。
)
Return

::bj@::
SendInput {Raw}
(
桌面云分两种，一种是华为自研（HDP版本），还有就是你现在用的合作云（早期和Citrix合作的ICA版本），当时的CloudClient兼容Windows 7，时过境迁，往后桌面云都往自研方向发展，Citrix对Windows 10 的兼容很差，如果你依然需要使用USB的映射来调试手机，建议你使用安装Windows 7系统的PC（笔记本电脑或者台式机），或者申请一个TC云盒子，来支撑项目。
)

::deng@::
SendInput {Raw}
(
等，自助维护台（VNC）进去发现这种白屏，只能等，是Windows Update （推送的补丁更新），你关心的等待时间，1 - 3小时不等。
该页面别关，会自动进入系统的。
)
Return

::yz@::
SendInput {Raw}
(
去非办公桌面云（或者会议云也可以），因为我要验证你的桌面云，你的eSpace在桌面云上和我会议，又在我电脑上登录你的桌面云排查问题，会挤兑eSpace整个会议。
OR 同事eSpace也可以。
)
Return

::js@::
SendInput {Raw}
(
因为旧云【nkgy3x002273971】所在服务器整体下线，硬件更换。

所以新云【nkgy6x002273971】是代替你的旧云。因此有两个云。
)
Return

::km@::
SendInput {Raw}
(
办公桌面云不是用来开发的，如果大运量计算，和开发应用，请转计算云。
高耗能CPU和利用内存，建议转计算云。计算云的负载比办公桌面云要高很多。
我给你链接：http://its.huawei.com/servicedesk/itservice/#/caseDetail.html?docId=KT00002160&viewsource=search
)
Return

::cp@::
SendInput {Raw}
(
你指的是整个C盘？

会默认将路径为：C:\Users\z00194878\下面的文件拷贝过去。

将默认路径为：下载，桌面，图片，文档等文件随同搬迁过去。不用担心。

1. eSpace软件不受影响，文件会是默认搬迁过去，软件不用担心，这些基础类办公应用，新云都有。

2. Outlook，在新云上，首次使用，会第一次配置文件（很简单，按照提示点下一步即可），以前按月份攒下来的邮件文件。一般默认在D盘，会随着搬迁一同迁移过来，到时候，可以手动导入这些历史邮件（称为.pst文件），邮件不会有丢失的情况。
)
Return


::wh@::
SendInput {Raw}
(
工，在吗？

你名下2台南京云，所在服务器要下线：
 - NKGY2L640333
 - NKGY2L003254672

1. 你工作地在武汉，可将两台南京云的数据迁往武汉；

2. 或者迁往，你名下有【】云：lfgy2l003254671；
)
Return

::fw@::
SendInput {Raw}
(
在新云里访问旧云方式：

\\10.135.195.204\D$

比如访问D盘，在后面加个美元符号即可。

比如访问E盘：
\\10.135.195.204\E$
)
Return

::qy@::
SendInput {Raw}
(
- 我们一直在跟踪研发优化，需手动搬迁数据 + 安装软件确实比较耽误时间，无感知的平滑迁移工具非常有必要。
这个平滑迁移的需求，我们找桌面云研发-IT产品线提了几年的需求，一直不接收，今年再次跟研发提了这个强烈的需求，这次受理了需求，但上线时间还没定，所以这次还得您手动搬迁下。
)
Return

::hb@::
SendInput {Raw}
(
工，您好，我是桌面云运营团队的同事，看到您在社区上反馈：“”。
(1.)我们通过后台查询到您的云：（ctuy1）为R2版本。R2版本服务器较老，不再支持内存升级，建议切换至新云。
(2.)目前由于西区（成都）地区没有新云资源可以调配，我先将您录入系统作待调优名单，预计将于7月份左右上新一批硬件资源，届时为您升级，该方案是否可以接受？
)
Return

::nc@::
SendInput {Raw}
(
工，您好，名单已记录，下周会统一安排内存调优，调优完成后会以邮件形式通知给您；后续有问题可及时与我们反馈，竭诚为您服务~
)
Send {Home}
Send ^{,}
Return

::jc@::
SendInput {Raw}
(
检查步骤：您点击正上方[菜单栏] —— [主页(Home)] —— 回到TC最原始的界面 —— 键盘上按 Ctrl + Alt + A，会弹出一个参数窗口。
检查目的：看下系统OS版本号，有无AccessClient补丁。
)
Return

::jy@::
SendInput {Raw}
(
Okay, 我建议您通过： https://yun.huawei.com/pages/login.do?isLogout=1  登录一下。因为主要是后台的节点实时动态扫描名单。现在入职高峰期来了，本着循环使用IT资源，不常使用，桌面云将按释放处理。后续按需使用，可网上申请。
)
Return

::sf@::
SendInput {Raw}
(
就几秒钟，填下释放电子流链接：
http://w3.huawei.com/hicloud/portal/ReleaseDesktopAction.do?taskVO.workflowName=releaseVm&catagoryId=22&requestId=24&method=toCreateWorkflow
)
Return

::sj@::
SendInput {Raw}
(
好的，那您有数据需要迁移吗？没有的话，今天下班后台直接回收了。
)
Return

::f@::
SendInput {Raw}
(
还是那个搬迁进度，NKNY2南京旧云7.15前要释放咯。我怕你忘记了。
)
Return

::mt@::
SendInput {Raw}
(
明天下发新云，旧云、新云并存，到时候你会收到一封邮件，数据迁移手册+新云地址。等我邮件。
)
Return

::nj@::
SendInput {Raw}
(
您好，最近群发了搬迁通知邮件，可能您忙于项目，我在eSpace上通知您：由于您的桌面云属于（nkgy1），该组集群服务器的维护周期即将到期（南武云是2012年建设），届时将下架，为了更好的性能，我们为您安排至（nkgy6）的新云，并升级为：Windows 7 64位操作系统, 4核CPU，16G内存，80G系统C盘、其余数据盘（D盘等）容量保持一致，供您迁移数据，并且我们一对一支持解决搬迁中的问题。安排您近期搬迁（nkgy6）是否OK？（有问题随时在eSpace联系我）
)
Return

::mm1@::
SendInput {Raw}
(
我们在后台检查用户：【】的云状态，查询无法登陆的原因，请提供一下云账号登陆密码，谢谢。
)
Return

::mm2@::
SendInput {Raw}
(
我们在后台检查您的云状态，查询无法登陆的原因，请提供一下云账号登陆密码，谢谢。
)
Return

::w@::
SendInput {Raw}
(
对了，遇到不能登录问题，IT服务平台给出的修复指导，还是不够详细？
- 我刚才登录自主维护台，窗口很小，而且底部任务栏也消失，导致无法选择图标。
- 我们还在严格筛查IT给出的修复指导，所以，您的建议真的很重要，便于其他用户急速解决。
)
Return

::ph@::
SendInput {Raw}
(
平滑迁移，产品部在研发，但去年下半年出现数据丢失的问题，数据的安全性重新考虑后，暂停使用直接搬迁。
他们重新在定位问题所在，可能在未来重新上线这个服务，毕竟让用户来搬迁数据，是个耽搁效率的事。
)
Return

`::
Send !{Tab}
Return

RWin::
Send {Control Down}{Shift}{Control Up}
Return

AppsKey::^!z

::c@::
SendInput {Raw}
(
那您参考此案例清理C盘：http://3ms.huawei.com/hi/group/7171/wiki_5065795.html
因为内存增大，所映射需要的虚拟内存虚拟在C盘上的储存空间变大。  可以转移。
)
Return

F3::
Click 1589, 154,
Send {End}
Click 895, 1021,
Sleep 3000
Send ^{w}
Sleep 1000
Send {F1}
Return

F6::
Sleep 150
Send {Esc}
Click 1917, 992,
Click 729, 265
Send ^{c}
Sleep 1500
Send #{2}
Sleep 1500
Send ^{l}
Send ^{v}
Send {Enter}
Return

F7::
Click 1917, 992,
Click 480, 277,
Send ^{c}
Send +{x}
Sleep 200
Send ^{v}
Return

F8::
MouseMove 111, 205,
Click Down
MouseMove 665, 289,
Click
Sleep, 300
Send {Enter}
Sleep, 300
Return

F4::
Click 1917, 992,
Click 527, 241,
Send ^{c}
Send ^!z
Sleep 1000
Send ^{v}
Sleep 1000
Send {Enter}
Sleep 2000
SendInput {Raw}
(
工, Sorry, 南京云上周五回收，已经超出期限，请填下回收释放电子流链接：

http://w3.huawei.com/hicloud/portal/ReleaseDesktopAction.do?taskVO.workflowName=releaseVm&catagoryId=22&requestId=24&method=toCreateWorkflow
)
Return

F12::
Send ^{a}
Send {Delete}
Return

F9::
Click 1085, 644
Click 937, 445
Send ^v
Click 1038, 643
Sleep 2500
Click 1038, 643
Return

F10::
Click 1087, 432
Click 1324, 322
Send ^v
Click 1034, 430
Sleep 2500
Click 1034, 430
Return

F11::
Sleep 150
Send {Esc}
Send {Esc}
Click 1917, 992,
Click 108, 221
Send ^{c}
Send ^!z
Sleep 1000
Send ^{v}
Sleep 1000
Send {Enter}
Sleep 2000
SendInput {Raw}
(
Hi，我是桌面云团队的，后台监控到您的桌面云已超过1个月未登录使用。根据桌面云回收规则，同时节省您部门经费，需将您的云回收，请问您是否有数据需要保留或者使用？默认今天下班回收清理。（桌面云收费标准：1951/VM/年，按月计费）
)
Return

::y@::
SendInput {Raw}
(
那就保留。继续使用啊，免得下次又是筛选出来，eSpace来说这个事情。
)
Return

::n@::
SendInput {Raw}
(
您看这样好吗，您不用的桌面云先释放了，后续出差时需要再申请。
因为现在资源真的十分紧张，很多新入职申请等着协调桌面云，又无新建资源预算，真的非常难。希望您能理解，非常感谢！
)
Return

::b@::
SendInput {Raw}
(
好的，那我这边帮您备注保留。
)
Return

::spes@::
SendInput {Raw}
(
只要你没有认为禁止“本地连接”或者调整网络设置，桌面云里任何网络不通的问题，请检查SPES（华为信息安全监控安软件）是否未认证（灰色），【自助维护台里操作】，点击 Windows 开始键菜单里，搜索“SPES”，打开它，并认证。
)
Return

::cc@::
SendInput {Raw}
(
您看这样好吗，您不用的桌面云先释放了，后续出差时需要再申请，因为您不用的每个月都在收您部门的费用。
马上进入新员工入职高峰期，今年新建资源也少，建议您先释放。希望您能理解，非常感谢！

)
Return

::m@::
SendInput {Raw}
(
那您下班时参考以下指导进行关机（非重启）生效：http://3ms.huawei.com/hi/group/7171/thread_7250521.html
)
Return

::q@::
SendInput {Raw}
(
如果数据盘不足的话，您可填写电子流申请扩容： http://w3.huawei.com/hicloud/portal/modifyDiskAction.do?taskVO.workflowName=expandDisk&catagoryId=22&requestId=25&method=toCreateWorkflow

)
Return

::z@::
SendInput {Raw}
(
Okay, 后续使用有什么问题可随时联系我，我们也会继续监控您桌面云的使用情况，争取为您提供更好的服务。希望您多多支持桌面云哦！

)
Return

!F4::
Click 1917, 992,
Click 220, 254,
Send ^{c}
Send ^!z
Sleep 1000
Send ^{v}
Sleep 1000
Send {Enter}
Sleep 2000
SendInput {Raw}
(
工啊，我是桌面云运维团队，为提升用户性能体验，我们分析了下部分用户的Top进程，显示您有使用IDEA，您在桌面云上使用有感觉卡吗？
)
Return

^F4::
Click 1917, 992,
Click 80, 240,
Send ^{c}
Send ^!z
Sleep 1000
Send ^{v}
Sleep 1000
Send {Enter}
Sleep 2000
SendInput {Raw}
(
Hi, We would like to remind you that Desktop Cloud Server located in Fray1 OR Frag1 will be out of lifecycle on 31st July!

Please according the guide which we send to you by Email to use new Desktop Cloud on Fray2 and Frag2 and transfer data to make sure it migrate smoothly.

Once you already completed migration to the new platform, please kindly release the previous ones(Unused virtual machine), Click Link Below: 
http://w3.huawei.com/hicloud/portal/ReleaseDesktopAction.do?taskVO.workflowName=releaseVm&catagoryId=22&requestId=24&method=toCreateWorkflow

Any questions please let me know, and thank for your great support!

)
Return




