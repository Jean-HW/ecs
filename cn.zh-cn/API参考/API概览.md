# API概览<a name="ZH-CN_TOPIC_0124306060"></a>

弹性云服务器所提供的接口分为ECS接口与OpenStack原生接口。推荐您使用ECS接口。

## ECS接口说明<a name="section13231524145513"></a>

**表 1**  ECS接口说明

<a name="zh-cn_topic_0121588224_table5876102613294"></a>
<table><thead align="left"><tr id="zh-cn_topic_0121588224_row3878122616298"><th class="cellrowborder" valign="top" width="22.84%" id="mcps1.2.3.1.1"><p id="zh-cn_topic_0121588224_p68781126182914"><a name="zh-cn_topic_0121588224_p68781126182914"></a><a name="zh-cn_topic_0121588224_p68781126182914"></a><strong id="zh-cn_topic_0121588224_b125201844173712"><a name="zh-cn_topic_0121588224_b125201844173712"></a><a name="zh-cn_topic_0121588224_b125201844173712"></a>类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="77.16%" id="mcps1.2.3.1.2"><p id="zh-cn_topic_0121588224_p158781726112914"><a name="zh-cn_topic_0121588224_p158781726112914"></a><a name="zh-cn_topic_0121588224_p158781726112914"></a><strong id="zh-cn_topic_0121588224_b15203449370"><a name="zh-cn_topic_0121588224_b15203449370"></a><a name="zh-cn_topic_0121588224_b15203449370"></a>说明</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="zh-cn_topic_0121588224_row148781026122919"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p73459108266"><a name="p73459108266"></a><a name="p73459108266"></a>生命周期管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p73450100260"><a name="p73450100260"></a><a name="p73450100260"></a>包括弹性云服务器的创建、删除、查询等接口。</p>
</td>
</tr>
<tr id="zh-cn_topic_0121588224_row1987820263297"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p73459108269"><a name="p73459108269"></a><a name="p73459108269"></a>状态管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p1345191072617"><a name="p1345191072617"></a><a name="p1345191072617"></a>包括弹性云服务器的变更规格、重装/切换操作系统、自动恢复等接口。</p>
</td>
</tr>
<tr id="row11930129135114"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p1610133715115"><a name="p1610133715115"></a><a name="p1610133715115"></a>批量操作</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p99313295516"><a name="p99313295516"></a><a name="p99313295516"></a>包括批量启动、重启、关闭、修改弹性云服务器等接口。</p>
</td>
</tr>
<tr id="zh-cn_topic_0121588224_row87746166614"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p234531013261"><a name="p234531013261"></a><a name="p234531013261"></a>规格管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p63451010192612"><a name="p63451010192612"></a><a name="p63451010192612"></a>查询规格详情、规格的扩展信息等。</p>
</td>
</tr>
<tr id="zh-cn_topic_0121588224_row816313459617"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p1234511014266"><a name="p1234511014266"></a><a name="p1234511014266"></a>网卡管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><a name="ul122955216386"></a><a name="ul122955216386"></a><ul id="ul122955216386"><li>批量添加、删除弹性云服务器的网卡。</li><li>给弹性云服务器网卡绑定、解绑定私有IP地址。</li></ul>
</td>
</tr>
<tr id="zh-cn_topic_0121588224_row132213492619"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p7345510142613"><a name="p7345510142613"></a><a name="p7345510142613"></a>磁盘管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p1034591012264"><a name="p1034591012264"></a><a name="p1034591012264"></a>包括弹性云服务器的挂载、卸载、查询等接口。</p>
</td>
</tr>
<tr id="row15872192519537"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p487212257537"><a name="p487212257537"></a><a name="p487212257537"></a>元数据管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p9872102513534"><a name="p9872102513534"></a><a name="p9872102513534"></a>包括更新云服务器元数据和删除云服务器指定元数据的接口</p>
</td>
</tr>
<tr id="row13156184812615"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p1815684813264"><a name="p1815684813264"></a><a name="p1815684813264"></a>租户配额管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p715619482260"><a name="p715619482260"></a><a name="p715619482260"></a>查询租户的配额，包括配额限制、已使用配额等接口。</p>
</td>
</tr>
<tr id="row81561948102618"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p71569488265"><a name="p71569488265"></a><a name="p71569488265"></a>查询Job状态</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p58914097194855"><a name="p58914097194855"></a><a name="p58914097194855"></a>对于创建/删除云服务器、云服务器批量操作和网卡操作等异步API，可以通过该接口查询任务的执行状态。</p>
</td>
</tr>
<tr id="row4156748122612"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p18156114814269"><a name="p18156114814269"></a><a name="p18156114814269"></a>标签管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p15156148192614"><a name="p15156148192614"></a><a name="p15156148192614"></a>包括弹性云服务器二维标签的添加、删除、查询等接口。</p>
<p id="p917211491664"><a name="p917211491664"></a><a name="p917211491664"></a>支持批量添加、删除操作。</p>
</td>
</tr>
<tr id="row12159219517"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p91595116519"><a name="p91595116519"></a><a name="p91595116519"></a>密码管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p19159811456"><a name="p19159811456"></a><a name="p19159811456"></a>一键重置弹性云服务器密码。</p>
</td>
</tr>
<tr id="row1515624817263"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p1315604822616"><a name="p1315604822616"></a><a name="p1315604822616"></a>FPGA逻辑文件管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p915634822615"><a name="p915634822615"></a><a name="p915634822615"></a>包括注册、删除、查询FPGA镜像等接口，用于FPGA加速型云服务器。</p>
</td>
</tr>
<tr id="row11627123915553"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p763013394557"><a name="p763013394557"></a><a name="p763013394557"></a>云服务器组管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p663063925517"><a name="p663063925517"></a><a name="p663063925517"></a>包括创建、删除云服务器组接口、云服务器组添加成员、删除成员接口。</p>
</td>
</tr>
</tbody>
</table>

## OpenStack原生接口说明<a name="section117511017125616"></a>

**表 2**  OpenStack原生接口说明

<a name="table15502236145613"></a>
<table><thead align="left"><tr id="row205021536185618"><th class="cellrowborder" valign="top" width="22.84%" id="mcps1.2.3.1.1"><p id="p7502193611568"><a name="p7502193611568"></a><a name="p7502193611568"></a><strong id="b650216363566"><a name="b650216363566"></a><a name="b650216363566"></a>类型</strong></p>
</th>
<th class="cellrowborder" valign="top" width="77.16%" id="mcps1.2.3.1.2"><p id="p1450273610563"><a name="p1450273610563"></a><a name="p1450273610563"></a><strong id="b195029369567"><a name="b195029369567"></a><a name="b195029369567"></a>说明</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="row5503536205610"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p155039364561"><a name="p155039364561"></a><a name="p155039364561"></a>查询API版本信息</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><a name="ul1050314364565"></a><a name="ul1050314364565"></a><ul id="ul1050314364565"><li>查询API版本信息列表</li><li>查询指定API版本信息</li></ul>
</td>
</tr>
<tr id="row750319364568"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p9503183612561"><a name="p9503183612561"></a><a name="p9503183612561"></a>生命周期管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p8503173613562"><a name="p8503173613562"></a><a name="p8503173613562"></a>包括弹性云服务器的创建、删除、修改、查询等接口。</p>
</td>
</tr>
<tr id="row850317367568"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p1650315362568"><a name="p1650315362568"></a><a name="p1650315362568"></a>状态管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p17503236105619"><a name="p17503236105619"></a><a name="p17503236105619"></a>包括弹性云服务器的开机、关机、重启、锁定/解锁定、变更/回退变更规格等接口。</p>
</td>
</tr>
<tr id="row950383619562"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p15504173616565"><a name="p15504173616565"></a><a name="p15504173616565"></a>网络管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p1750414363569"><a name="p1750414363569"></a><a name="p1750414363569"></a>查询租户、弹性云服务器的网络等接口。</p>
</td>
</tr>
<tr id="row8504153645612"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p3504153615562"><a name="p3504153615562"></a><a name="p3504153615562"></a>镜像管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p3504336195617"><a name="p3504336195617"></a><a name="p3504336195617"></a>包括删除、查询镜像等接口。</p>
</td>
</tr>
<tr id="row950493618566"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p3504836165612"><a name="p3504836165612"></a><a name="p3504836165612"></a>安全组管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p185041736185614"><a name="p185041736185614"></a><a name="p185041736185614"></a>包括添加、移除、查询、创建、更新、删除安全组及安全组规则等接口。</p>
</td>
</tr>
<tr id="row13504103645616"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p15041236145617"><a name="p15041236145617"></a><a name="p15041236145617"></a>规格管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p6504173617564"><a name="p6504173617564"></a><a name="p6504173617564"></a>查询弹性云服务器的规格列表、详情等接口。</p>
</td>
</tr>
<tr id="row25041836195615"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p3504183620564"><a name="p3504183620564"></a><a name="p3504183620564"></a>网卡管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p450516362569"><a name="p450516362569"></a><a name="p450516362569"></a>包括添加、删除、查询弹性云服务器的网卡等接口。</p>
</td>
</tr>
<tr id="row20505123675616"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p450503610566"><a name="p450503610566"></a><a name="p450503610566"></a>磁盘管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p250516366566"><a name="p250516366566"></a><a name="p250516366566"></a>包括弹性云服务器的挂载、卸载、查询等接口。</p>
</td>
</tr>
<tr id="row650543635614"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p1950553620566"><a name="p1950553620566"></a><a name="p1950553620566"></a>元数据管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p250523615620"><a name="p250523615620"></a><a name="p250523615620"></a>包括更新、设置、删除、查询、获取、修改弹性云服务器元数据等接口。</p>
</td>
</tr>
<tr id="row250515369566"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p1050513610567"><a name="p1050513610567"></a><a name="p1050513610567"></a>租户配额管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p17505536185615"><a name="p17505536185615"></a><a name="p17505536185615"></a>查询租户配额。</p>
</td>
</tr>
<tr id="row19505113619562"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p205059367565"><a name="p205059367565"></a><a name="p205059367565"></a>密钥、密码管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p6505336125614"><a name="p6505336125614"></a><a name="p6505336125614"></a>包括查询、创建、删除SSH密钥等接口。</p>
</td>
</tr>
<tr id="row13505183675612"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p145051036145619"><a name="p145051036145619"></a><a name="p145051036145619"></a>浮动IP管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p05051436145616"><a name="p05051436145616"></a><a name="p05051436145616"></a>包括分配、移除、创建、查询、删除浮动IP等接口。</p>
</td>
</tr>
<tr id="row155052036195616"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p450513620563"><a name="p450513620563"></a><a name="p450513620563"></a>云服务器组管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p350553655614"><a name="p350553655614"></a><a name="p350553655614"></a>包括创建、查询、删除云服务器组等接口。</p>
</td>
</tr>
<tr id="row7123632195817"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p1212333295810"><a name="p1212333295810"></a><a name="p1212333295810"></a>云服务器操作管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p10123532135813"><a name="p10123532135813"></a><a name="p10123532135813"></a>包括查询云服务器操作行为列表、通过请求ID查询云服务器行为。</p>
</td>
</tr>
<tr id="row5715132815588"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p97159288586"><a name="p97159288586"></a><a name="p97159288586"></a>云服务器控制台管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p871522895818"><a name="p871522895818"></a><a name="p871522895818"></a>获取弹性云服务器的控制台日志等接口。</p>
</td>
</tr>
<tr id="row1350512368568"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p55053362567"><a name="p55053362567"></a><a name="p55053362567"></a>快照管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p85051836205620"><a name="p85051836205620"></a><a name="p85051836205620"></a>包括创建、查询、删除快照等接口。</p>
</td>
</tr>
<tr id="row20505173613560"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p3505143611561"><a name="p3505143611561"></a><a name="p3505143611561"></a>可用区</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p9505183611565"><a name="p9505183611565"></a><a name="p9505183611565"></a>查询可用区列表。</p>
</td>
</tr>
<tr id="row050573695613"><td class="cellrowborder" valign="top" width="22.84%" headers="mcps1.2.3.1.1 "><p id="p4505103635617"><a name="p4505103635617"></a><a name="p4505103635617"></a>标签管理</p>
</td>
<td class="cellrowborder" valign="top" width="77.16%" headers="mcps1.2.3.1.2 "><p id="p8505193645614"><a name="p8505193645614"></a><a name="p8505193645614"></a>包括弹性云服务器一维标签的创建、删除、查询等接口。</p>
</td>
</tr>
</tbody>
</table>

