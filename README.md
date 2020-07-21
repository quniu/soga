详细教程：[进入](https://github.com/sprov065/soga/wiki)

商业版价格：[进入](https://github.com/sprov065/soga/wiki/05-%E8%8E%B7%E5%8F%96%E5%95%86%E4%B8%9A%E7%89%88%E6%8E%88%E6%9D%83%E7%A0%81)

# soga 后端
soga 后端是一个支持 v2ray 和 trojan 的后端，社区版版最高支持88用户

## v2ray
soga 后端针对 v2ray 占内存的特点使用 C 语言特别优化了 v2ray 的内存占用，在相同用户数量和 alterId 下，相对于原版 v2ray 来说可节省 40-60% 的内存空间，用户数量越多，节省的内存就越多，用户较少则节省不明显。

## trojan
soga 同时实现了 trojan 协议，trojan 协议相对于 v2ray 来说更轻量和高效，在大量用户下也几乎不占多少内存，推荐优先选择 trojan。

## 支持的前端
|前端              |v2ray              |trojan           |
|------------------|------------------|------------------|
|sspanel-uim	   |√                 |√                 |
|v2board	   |√                 |√                 |
|WHCMS             |开发中             |计划中            |
|vnetpanel         |√                 |√                 |
|v2-ui             |计划中             |计划中            |


## 功能介绍
|功能              |v2ray              |trojan           |
|------------------|------------------|------------------|
|单端口多用户	   |√                 |√                 |
|用户流量统计	   |√                 |√                 |
|限速              |√                 |√                 |
|限连接数           |√                 |√                |
|服务器信息上报      |√                |√                 |
|在线人数上报        |√                |√                 |
|在线IP上报         |√                 |√                 |
|自动增删用户       |√                 |√                  |
|审计规则           |√                 |√                 |
|禁止封禁IP连接      |√                |√                 |
|中转规则           |√                 |√                 |
|自动申请tls证书     |√                 |√                 |
|自动续签tls证书     |√                 |√                 |
|dns流媒体解锁       |√                 |√                 |

## v2ray 支持的协议
|协议              |支持情况           |
|----------------- |------------------|
|tcp               |√                 |
|tcp+tls	       |√                 |
|ws                |√                 |
|ws+tls            |√                 |
|cdn+ws            |√                 |
|cdn+ws+tls        |√                 |

## trojan 支持的协议
|协议              |支持情况           |
|----------------- |------------------|
|trojan协议         |√                 |


## 对接方式
|对接方式           |v2ray             |trojan           |
|------------------|------------------|------------------|
|webapi     	   |√                 |√                 |
|数据库   	        |√                 |√                 |
|docker webapi     |√                 |√                 |
|docker 数据库     |√                 |√                 |

## 前端对接方式对照表
<table>
    <tr>
        <th>前端</th>
        <th>后端</th>
        <th>webapi</th>
        <th>数据库</th>
        <th>docker</th>
    </tr>
    <tr>
        <th rowspan="2">sspanel-uim</th>
        <td>v2ray</td>
        <td>√</td>
        <td>√</td>
        <td>√</td>
    </tr>
    <tr>
        <td>trojan</td>
        <td>√</td>
        <td>√</td>
        <td>√</td>
    </tr>
    <tr>
        <th rowspan="2">v2board</th>
        <td>v2ray</td>
        <td>√</td>
        <td>√</td>
        <td>√</td>
    </tr>
    <tr>
        <td>trojan</td>
        <td>√</td>
        <td>√</td>
        <td>√</td>
    </tr>
    <tr>
        <th rowspan="2">WHCMS</th>
        <td>v2ray</td>
        <td rowspan="2" colspan="3" align="center">开发中</td>
    </tr>
    <tr>
        <td>trojan</td>
    </tr>
    <tr>
        <th rowspan="2">vnetpanel</th>
        <td>v2ray</td>
        <td>√</td>
        <td rowspan="2" align="center">开发中</td>
        <td>√</td>
    </tr>
    <tr>
        <td>trojan</td>
        <td>√</td>
        <td>√</td>
    </tr>
    <tr>
        <th rowspan="2">v2-ui</th>
        <td>v2ray</td>
        <td rowspan="2">计划中</td>
        <td>×</td>
        <td rowspan="2">计划中</td>
    </tr>
    <tr>
        <td>trojan</td>
        <td>×</td>
    </tr>
</table>

加入我们：[Telegram群组](https://t.me/soga_v2ray)

加入我们：[Telegram通知频道](https://t.me/sogav2ray)
