## 背景信息
由于 Webshell 服务器扩容更新，即日起 Webshell 代理 IP 地址将进行新旧更替。如需使用 Webshell 登录服务，请您在安全组中放通新增 Webshell 代理 IP 网段及用于远程登录的端口（默认为22端口）。
>?Webshell 登录方式请参见 [使用标准登录方式登录 Linux 实例（推荐）](https://cloud.tencent.com/document/product/213/5436)。 
>



## 调整详情
<table>
<tr>
<th style="width:55%">调整说明</th><th>包含 IP 地址/网段</th>
</tr>
<tr>
<td><b>2021年3月31日及之前</b>，新、旧代理 IP 地址/网段将并行使用。</td>
<td>81.69.102.0/24<br>
106.55.203.0/24<br>
101.33.121.0/24<br>
101.32.250.0/24<br>
115.159.198.247<br>
115.159.211.178<br>
119.28.7.195<br>
119.28.22.215<br>
119.29.96.147<br>
211.159.185.38</td>
</tr>
<tr>
<td><b>2021年4月1日及之后</b>，旧 IP 地址将不再使用，请您确保安全组中来源（入站）为新代理 IP 网段及远程登录端口已放通。</td>
<td>
81.69.102.0/24<br>
106.55.203.0/24<br>
101.33.121.0/24<br>
101.32.250.0/24<br>
</td>
</tr>
</table>


## 相关操作
- [使用标准登录方式登录 Linux 实例（推荐）](https://cloud.tencent.com/document/product/213/5436)
- [添加安全组规则](https://cloud.tencent.com/document/product/213/39740)
