# 产品特点

## 多厂商设备适配，轻松实现全网设备统一管理

eSight支持华为服务器、存储、虚拟化、交换机、路由器、WLAN、防火墙、PON、eLTE、统一通信、智真、视频监控等设备以及应用系统和机房设施的统一管理，并预集成对HP、Cisco、H3C等第三方主流设备的管理能力。

<table cellpadding="4" cellspacing="0" summary="" id="ldx_function_tab01" class="boardFuncDetail" frame="border" border="1" rules="all"><caption><b>Table 1 </b>LQCP单板功能和特性（OTU模式）</caption>
<thead align="left">
<tr>
<th class="cellrowborder" valign="top" id="mcps1.2.5.1.1">功能和特性</th>

<th class="cellrowborder" colspan="3" valign="top" id="mcps1.2.5.1.2">描述</th>

</tr>

</thead>

<tbody>
<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">基本功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><p>LQCP单板客户侧可以接入四种信号，分别为OTU4/100GE/40GE/10GE，信号的相互转换如下：</p>
<p>线路400G:</p>
<ul><li>4 x OTU4 &lt;-&gt; 4 x ODU4 &lt;-&gt; 1 x ODUC4 &lt;-&gt; 1 x OTUC4</li><li>4 x 100GE &lt;-&gt;4 x ODU4 (Bit透明映射/MAC透明映射) &lt;-&gt; 1 x ODUC4&lt;-&gt;
 1 x OTUC4</li><li>4 x 40GE &lt;-&gt; 4 x ODU3（TTT+GMP）&lt;-&gt; 1 x ODUC4 &lt;-&gt; 1 x OTUC4</li><li>16 x 10GE LAN &lt;-&gt; 16 x ODU2(MAC透明映射) &lt;-&gt; 1 x ODUC4 &lt;-&gt;
1 x OTUC4</li><li>16 x 10GE LAN &lt;-&gt; 16 x ODU2e(IMP+BMP) &lt;-&gt; 1 x ODUC4 &lt;-&gt;
1 x OTUC4</li></ul>
<p>线路200G:</p>
<ul><li>2 x OTU4 &lt;-&gt; 2 x ODU4 &lt;-&gt; 1 x ODUC2 &lt;-&gt; 1 x OTUC2</li><li>2 x 100GE &lt;-&gt;2 x ODU4 (Bit透明映射/MAC透明映射) &lt;-&gt; 1 x ODUC2 &lt;-&gt;
1 x OTUC2</li><li>4 x 40GE &lt;-&gt; 4 x ODU3（TTT+GMP）&lt;-&gt; 2 x ODU4&lt;-&gt; 1 x ODUC2
&lt;-&gt; 1 x OTUC2</li><li>16 x 10GE LAN &lt;-&gt; 16 x ODU2(MAC透明映射) &lt;-&gt; 2 x ODU4&lt;-&gt;
1 x ODUC2&lt;-&gt; 1 x OTUC2</li><li>16 x 10GE LAN &lt;-&gt; 16 x ODU2e(IMP+BMP) &lt;-&gt; 2 x ODU4 &lt;-&gt;
1 x ODUC2&lt;-&gt; 1 x OTUC2</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">客户侧业务类型</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><p>100GE</p>
<p>OTU4</p>
<p>40GE</p>
<p>FC3200</p>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">OTN功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><ul><li>支持波分侧OTUC4和OTUC2接口。</li><li>采用ITU-T G.709建议的帧格式和开销处理。</li><li>ODU4层：<ul><li>客户侧接入100GE/40GE/10GE，支持PM和TCM功能。</li><li>客户侧接入OTU4，支持PM和TCM功能，PM和TCM层的非介入监视功能。</li></ul>
</li><li>ODU3层：<ul><li>客户侧接入40GE，支持PM和TCM功能。</li></ul>
</li><li>ODU2/ODU2e层：<ul><li>客户侧接入10GE LAN，支持PM和TCM功能。</li></ul>
</li><li>客户侧支持OTU4层的SM功能。</li><li>波分侧支持ODUC2和ODUC4层的PM和TCM功能。</li><li>波分侧支持OTUC2和OTUC4层的SM功能。</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">业务加密</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 ">支持<div class="note"><span class="notetitle"> NOTE: </span><div class="notebody">仅LQCP单板客户侧接入非OTU4业务时支持。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">波长可调功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 ">LQCP可实现波分侧光信号在扩展C波段的96波范围内可调。</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">波分侧信号谱宽</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><ul><li>400G 16QAM：75GHz flex / 100GHz fix</li><li>200G QPSK：75GHz flex / 100GHz fix</li><li>200G 8QAM：62.5GHz flex</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">ESC功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">PRBS功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 ">客户侧和波分侧支持PRBS功能。<div class="note"><span class="notetitle"> NOTE: </span><div class="notebody">仅当接入OTU4业务时，客户侧支持PRBS功能。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">LPT功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><p id="lpt"><a name="lpt"></a><a name="lpt"></a>支持</p>
<div class="note"><span class="notetitle"> NOTE: </span><div class="notebody">仅当接入10GE LAN业务时，客户侧支持LPT功能。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">纠错编码</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><div class="p"><ul><li>当接入100GE业务时，客户侧支持RS_FEC纠错编码。</li><li><p>TN11LQCPF12波分侧支持SDFEC纠错编码。</p>
</li></ul>
</div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">性能监视与告警监测</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><ul><li>客户侧支持40GE、100GE和OTU4业务的BIP8监视（OTU4的BIP8为突发模式），可以定位业务故障。</li><li>支持CD、PMD性能监测功能。</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">测试帧功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 ">仅客户侧接入100GE、40GE和10GE业务时支持。<div class="note"><span class="notetitle"> NOTE: </span><div class="notebody">采用以太网测试帧方式发送测试帧报文时，同一时刻只能支持一路接口发起测试帧。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">时延测量</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><div class="p">支持PM、TCM时延测量：<ul><li><p>支持上行高阶ODU通道PM/TCM时延测量。</p>
</li><li><p>客户侧非OTN业务，支持上行低阶ODU通道PM/TCM时延测量。</p>
</li><li><p>客户侧OTN业务，支持下行低阶ODU通道TCM时延测量。</p>
</li></ul>
</div>
 </td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">IEEE 1588v2</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">物理层时钟</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><p>当客户侧接入100GE时，Bit透明映射时支持同步以太透传，MAC透明映射时支持同步以太处理。</p>
<p>当客户侧接入10GE时，IMP+BMP映射时不支持同步以太透传，MAC透明映射时支持同步以太处理。<span>每个端口只支持第1通道的同步以太处理。</span></p>
<div class="note"><span class="notetitle"> NOTE: </span><div class="notebody"><p>16 x 10GE LAN &lt;-&gt;
16 x ODU2e(IMP+BMP)映射路径时不支持同步以太透传。</p>
</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">保护方式</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 "><ul><li>支持客户侧1+1保护。<div class="note"><span class="notetitle"> NOTE: </span><div class="notebody"><ul><li id="li_04"><a name="li_04"></a><a name="li_04"></a>客户侧接入100GE/40GE业务时，客户侧1+1保护只支持双端倒换，不支持单端倒换；客户侧接入OTU4业务时，客户侧1+1保护支持单端倒换。</li><li id="li_03"><a name="li_03"></a><a name="li_03"></a>客户侧使用MPO光模块接入业务时，不支持客户侧1+1保护。</li></ul>
</div></div>
</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">以太网业务映射模式</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.5.1.2 ">Bit透明映射ODU4、MAC透明映射ODU4、ODU3（TTT+GMP）、ODU2(MAC透明映射)、ODU2e(IMP+BMP)</td>

</tr>

<tr>
<td class="cellrowborder" rowspan="8" valign="top" width="16.666666666666664%" headers="mcps1.2.5.1.1 ">环回</td>

<td class="cellrowborder" rowspan="2" valign="top" width="35.333333333333336%" headers="mcps1.2.5.1.2 ">ODUk通道</td>

<td class="cellrowborder" valign="top" width="18.000000000000004%" headers="mcps1.2.5.1.2 ">线路400G</td>

<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.5.1.2 ">不支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">线路200G：ODU4通道环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">支持<div class="note"><span class="notetitle"> NOTE: </span><div class="notebody">仅LQCP单板客户侧接入40GE/10GE业务时支持。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.2.5.1.1 ">波分侧</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">内环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">外环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.2.5.1.1 ">客户侧</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">内环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">外环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.2.5.1.1 ">通道环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">内环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">支持<div class="note"><span class="notetitle"> NOTE: </span><div class="notebody">仅LQCP单板客户侧接入10GE业务时支持。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.1 ">外环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.5.1.2 ">支持<div class="note"><span class="notetitle"> NOTE: </span><div class="notebody">仅LQCP单板客户侧接入10GE业务时支持。</div></div>
</td>

</tr>

</tbody>

</table>

## 组件化的架构，按需构建企业运维平台

eSight采用组件化架构，在统一的eSight管理平台之上，提供丰富多样的组件，客户可以根据自己的情况选择所需要的组件。


图 1 eSight组件化架构视图
![](zh-cn_image_0077089997.png "eSight组件化架构视图")

## 轻量级、Web化，减少系统维护与升级成本

eSight采用B/S架构，客户端无需安装任何插件，可随时随地访问。当系统升级或维护时只需更新服务器端软件，减少系统维护与升级成本。

<table id="ZH-CN_TOPIC_0073593155__t4213c7c44b664590968568f114d60c58" frame="border" rules="all"><thead><tr id="ZH-CN_TOPIC_0073593155__rfec87e98a079481f8d2d9ef4c3cc4ea6"><th  id="mcps1.3.3.3.1.3.1.1"><p id="ZH-CN_TOPIC_0073593155__a0498d3186b6242a39f5717647f01a42a"><strong id="ZH-CN_TOPIC_0073593155__zh-cn_topic_0044732447_b55367661540">符号</strong></p>
</th>
<th id="mcps1.3.3.3.1.3.1.2"><p id="ZH-CN_TOPIC_0073593155__a4acddcaddd5b4317a7f799339666b23b"><strong id="ZH-CN_TOPIC_0073593155__zh-cn_topic_0044732447_b498309011540">说明</strong></p>
</th>
</tr>
</thead>
<tbody><tr id="ZH-CN_TOPIC_0073593155__rbecf682699e04347b811b3067f1fdf69"><td  headers="mcps1.3.3.3.1.3.1.1 "><p id="ZH-CN_TOPIC_0073593155__aae6531d8aa584cf18641a8baea5a38f5"><span><img id="ZH-CN_TOPIC_0073593155__i1b7a36456dd84449b2e2c988ab84e555" src="zh-cn_image_0073592814.png" height="42.892500000000005" width="92.7675" title="点击放大" ></span></p>
</td>
<td headers="mcps1.3.3.3.1.3.1.2 "><pre>this is a code block</pre>用于警示紧急的危险情形，若不避免，将会导致人员死亡或严重的人身伤害。
</td>
</tr>
<tr id="ZH-CN_TOPIC_0073593155__rb94f1086aeff4e339ab13eb1f3e7adf7"><td  headers="mcps1.3.3.3.1.3.1.1 "><p id="ZH-CN_TOPIC_0073593155__a90dad36a6dde4fccadeb1b0b6784f888"><span><img id="ZH-CN_TOPIC_0073593155__i8ddb727469b54060aa7e49b40c88c172" src="zh-cn_image_0073592965.png" height="42.892500000000005" width="92.7675" title="点击放大" ></span></p>
</td>
<td headers="mcps1.3.3.3.1.3.1.2 "><p id="ZH-CN_TOPIC_0073593155__aea54f7234e674f858ae05a19618bc3ef">用于警示潜在的危险情形，若不避免，可能会导致人员死亡或严重的人身伤害。</p>
</td>
</tr>
<tr id="ZH-CN_TOPIC_0073593155__rfcc1e01e9054409e904d77423828b9cf"><td  headers="mcps1.3.3.3.1.3.1.1 "><p id="ZH-CN_TOPIC_0073593155__ab460855e71dd4365af58f3bc15bdff1d"><span><img id="ZH-CN_TOPIC_0073593155__i5ca9ca9542294c08b72eac5b5623c555" src="zh-cn_image_0073593150.png" height="42.892500000000005" width="92.7675" title="点击放大" ></span></p>
</td>
<td headers="mcps1.3.3.3.1.3.1.2 "><p id="ZH-CN_TOPIC_0073593155__a840f699b802c4b66b71911e6a1568f18">用于警示潜在的危险情形，若不避免，可能会导致中度或轻微的人身伤害。</p>
</td>
</tr>
<tr id="ZH-CN_TOPIC_0073593155__rac9dc157703543e390570e8cad3317d8"><td  headers="mcps1.3.3.3.1.3.1.1 "><p id="ZH-CN_TOPIC_0073593155__a17b99a9673324d37acf04a392f3cf8da"><span><img id="ZH-CN_TOPIC_0073593155__i4ca2a61a08ea4398988abe3647748236" src="zh-cn_image_0073593135.png" height="42.892500000000005" width="92.7675" title="点击放大" ></span></p>
</td>
<td headers="mcps1.3.3.3.1.3.1.2 "><p id="ZH-CN_TOPIC_0073593155__a80a0335b3c9442e7a881274973a59290">用于传递设备或环境安全警示信息，若不避免，可能会导致设备损坏、数据丢失、设备性能降低或其它不可预知的结果。</p>
<p id="ZH-CN_TOPIC_0073593155__a77baf6be7aab44b6a1c24039dc08d31b">“注意”不涉及人身伤害。</p>
</td>
</tr>
<tr id="ZH-CN_TOPIC_0073593155__r2b726dde6d4f4c6089ff5a19335b88a9"><td  headers="mcps1.3.3.3.1.3.1.1 "><p id="ZH-CN_TOPIC_0073593155__zh-cn_topic_0044732447_p752192515351"><span><img  id="ZH-CN_TOPIC_0073593155__if7d82a79c0814d76b76a2737939dd4c7" height="16.625" src="zh-cn_image_0073593027.png" width="49.875" title="点击放大"></span></p>
</td>
<td headers="mcps1.3.3.3.1.3.1.2 "><p id="ZH-CN_TOPIC_0073593155__zh-cn_topic_0044732447_p529620415351">用于突出重要/关键信息、最佳实践和小窍门等。</p>
<p id="ZH-CN_TOPIC_0073593155__ae020f41d433347c3b8f96483963fbd7b">“说明”不是安全警示信息，不涉及人身、设备及环境伤害信息。</p>
</td>
</tr>
</tbody>
</table>


<table>
<tr>
    <td rowspan="7"> 文件状态：<br/>
        [√] 草稿<br/>
        [√] 正在修改<br/>
        [√] 正式发布 </td>
    <td>文件标识：</td>
</tr>
<tr>
    <td>当前版本：</td>
    <td>2.7</td>
</tr>
<tr>
    <td>作    者：</td>
    <td></td>
</tr>
<tr>
    <td>创建日期：</td>
    <td></td>
</tr>
<tr>
    <td>最后更新：</td>
    <td></td>
</tr>
<tr>
    <td>密    级：</td>
    <td><a href="#ldx_function_new__ldx_function_tab01">请看表格1</td>
</tr>
<tr>
    <td>版权说明：</td>
    <td></td>
</tr>
</table>

<table cellpadding="4" cellspacing="0" summary="" id="ldx_function_new__ldx_function_tab01" class="boardFuncDetail" >
<thead align="left">
<tr>
<th class="cellrowborder" valign="top" id="mcps1.2.3.2.5.1.1">功能和特性</th>

<th class="cellrowborder" colspan="3" valign="top" id="mcps1.2.3.2.5.1.2">描述</th>

</tr>

</thead>

<tbody>
<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">基本功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><p>LQCP单板客户侧可以接入四种信号，分别为OTU4/100GE/40GE/10GE，信号的相互转换如下：</p>
<p>线路400G:</p>
<ul><li>4 x OTU4 &lt;-&gt; 4 x ODU4 &lt;-&gt; 1 x ODUC4 &lt;-&gt; 1 x OTUC4</li><li>4 x 100GE &lt;-&gt;4 x ODU4 (Bit透明映射/MAC透明映射) &lt;-&gt; 1 x ODUC4&lt;-&gt;
 1 x OTUC4</li><li>4 x 40GE &lt;-&gt; 4 x ODU3（TTT+GMP）&lt;-&gt; 1 x ODUC4 &lt;-&gt; 1 x OTUC4</li><li>16 x 10GE LAN &lt;-&gt; 16 x ODU2(MAC透明映射) &lt;-&gt; 1 x ODUC4 &lt;-&gt;
1 x OTUC4</li><li>16 x 10GE LAN &lt;-&gt; 16 x ODU2e(IMP+BMP) &lt;-&gt; 1 x ODUC4 &lt;-&gt;
1 x OTUC4</li></ul>
<p>线路200G:</p>
<ul><li>2 x OTU4 &lt;-&gt; 2 x ODU4 &lt;-&gt; 1 x ODUC2 &lt;-&gt; 1 x OTUC2</li><li>2 x 100GE &lt;-&gt;2 x ODU4 (Bit透明映射/MAC透明映射) &lt;-&gt; 1 x ODUC2 &lt;-&gt;
1 x OTUC2</li><li>4 x 40GE &lt;-&gt; 4 x ODU3（TTT+GMP）&lt;-&gt; 2 x ODU4&lt;-&gt; 1 x ODUC2
&lt;-&gt; 1 x OTUC2</li><li>16 x 10GE LAN &lt;-&gt; 16 x ODU2(MAC透明映射) &lt;-&gt; 2 x ODU4&lt;-&gt;
1 x ODUC2&lt;-&gt; 1 x OTUC2</li><li>16 x 10GE LAN &lt;-&gt; 16 x ODU2e(IMP+BMP) &lt;-&gt; 2 x ODU4 &lt;-&gt;
1 x ODUC2&lt;-&gt; 1 x OTUC2</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">客户侧业务类型</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><p>100GE</p>
<p>OTU4</p>
<p>40GE</p>
<p>FC3200</p>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">OTN功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><ul><li>支持波分侧OTUC4和OTUC2接口。</li><li>采用ITU-T G.709建议的帧格式和开销处理。</li><li>ODU4层：<ul><li>客户侧接入100GE/40GE/10GE，支持PM和TCM功能。</li><li>客户侧接入OTU4，支持PM和TCM功能，PM和TCM层的非介入监视功能。</li></ul>
</li><li>ODU3层：<ul><li>客户侧接入40GE，支持PM和TCM功能。</li></ul>
</li><li>ODU2/ODU2e层：<ul><li>客户侧接入10GE LAN，支持PM和TCM功能。</li></ul>
</li><li>客户侧支持OTU4层的SM功能。</li><li>波分侧支持ODUC2和ODUC4层的PM和TCM功能。</li><li>波分侧支持OTUC2和OTUC4层的SM功能。</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">业务加密</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持<div class="note"><span class="notetitle"> 说明： </span><div class="notebody">仅LQCP单板客户侧接入非OTU4业务时支持。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">波长可调功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 ">LQCP可实现波分侧光信号在扩展C波段的96波范围内可调。</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">波分侧信号谱宽</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><ul><li>400G 16QAM：75GHz flex / 100GHz fix</li><li>200G QPSK：75GHz flex / 100GHz fix</li><li>200G 8QAM：62.5GHz flex</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">ESC功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">PRBS功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 ">客户侧和波分侧支持PRBS功能。<div class="note"><span class="notetitle"> 说明： </span><div class="notebody">仅当接入OTU4业务时，客户侧支持PRBS功能。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">LPT功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><p id="ldx_function_new__lpt">支持</p>
<div class="note"><span class="notetitle"> 说明： </span><div class="notebody">仅当接入10GE LAN业务时，客户侧支持LPT功能。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">纠错编码</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><div class="p"><ul><li>当接入100GE业务时，客户侧支持RS_FEC纠错编码。</li><li><p>TN11LQCPF12波分侧支持SDFEC纠错编码。</p>
</li></ul>
</div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">性能监视与告警监测</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><ul><li>客户侧支持40GE、100GE和OTU4业务的BIP8监视（OTU4的BIP8为突发模式），可以定位业务故障。</li><li>支持CD、PMD性能监测功能。</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">测试帧功能</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 ">仅客户侧接入100GE、40GE和10GE业务时支持。<div class="note"><span class="notetitle"> 说明： </span><div class="notebody">采用以太网测试帧方式发送测试帧报文时，同一时刻只能支持一路接口发起测试帧。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">时延测量</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><div class="p">支持PM、TCM时延测量：<ul><li><p>支持上行高阶ODU通道PM/TCM时延测量。</p>
</li><li><p>客户侧非OTN业务，支持上行低阶ODU通道PM/TCM时延测量。</p>
</li><li><p>客户侧OTN业务，支持下行低阶ODU通道TCM时延测量。</p>
</li></ul>
</div>
 </td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">IEEE 1588v2</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">物理层时钟</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><p>当客户侧接入100GE时，Bit透明映射时支持同步以太透传，MAC透明映射时支持同步以太处理。</p>
<p>当客户侧接入10GE时，IMP+BMP映射时不支持同步以太透传，MAC透明映射时支持同步以太处理。<span>每个端口只支持第1通道的同步以太处理。</span></p>
<div class="note"><span class="notetitle"> 说明： </span><div class="notebody"><p>16 x 10GE LAN &lt;-&gt;
16 x ODU2e(IMP+BMP)映射路径时不支持同步以太透传。</p>
</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">保护方式</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 "><ul><li>支持客户侧1+1保护。<div class="note"><span class="notetitle"> 说明： </span><div class="notebody"><ul><li id="ldx_function_new__li_04">客户侧接入100GE/40GE业务时，客户侧1+1保护只支持双端倒换，不支持单端倒换；客户侧接入OTU4业务时，客户侧1+1保护支持单端倒换。</li><li id="ldx_function_new__li_03">客户侧使用MPO光模块接入业务时，不支持客户侧1+1保护。</li></ul>
</div></div>
</li></ul>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">以太网业务映射模式</td>

<td class="cellrowborder" colspan="3" valign="top" headers="mcps1.2.3.2.5.1.2 ">Bit透明映射ODU4、MAC透明映射ODU4、ODU3（TTT+GMP）、ODU2(MAC透明映射)、ODU2e(IMP+BMP)</td>

</tr>

<tr>
<td class="cellrowborder" rowspan="8" valign="top" width="16.666666666666664%" headers="mcps1.2.3.2.5.1.1 ">环回</td>

<td class="cellrowborder" rowspan="2" valign="top" width="35.333333333333336%" headers="mcps1.2.3.2.5.1.2 ">ODUk通道</td>

<td class="cellrowborder" valign="top" width="18.000000000000004%" headers="mcps1.2.3.2.5.1.2 ">线路400G</td>

<td class="cellrowborder" valign="top" width="30%" headers="mcps1.2.3.2.5.1.2 ">不支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">线路200G：ODU4通道环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持<div class="note"><span class="notetitle"> 说明： </span><div class="notebody">仅LQCP单板客户侧接入40GE/10GE业务时支持。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.2.3.2.5.1.1 ">波分侧</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">内环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">外环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.2.3.2.5.1.1 ">客户侧</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">内环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">外环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持</td>

</tr>

<tr>
<td class="cellrowborder" rowspan="2" valign="top" headers="mcps1.2.3.2.5.1.1 ">通道环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">内环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持<div class="note"><span class="notetitle"> 说明： </span><div class="notebody">仅LQCP单板客户侧接入10GE业务时支持。</div></div>
</td>

</tr>

<tr>
<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.1 ">外环回</td>

<td class="cellrowborder" valign="top" headers="mcps1.2.3.2.5.1.2 ">支持<div class="note"><span class="notetitle"> 说明： </span><div class="notebody">仅LQCP单板客户侧接入10GE业务时支持。</div></div>
</td>

</tr>

</tbody>

</table>

父主题： [产品介绍](zh-cn_topic_0073593153.md)

