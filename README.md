# subconverter-cloudflare

subconverter-cloudflare

<p>
  <img src="https://img.shields.io/github/issues/jwyGithub/subconverter-cloudflare" alt='issues'>
  <img src="https://img.shields.io/github/license/jwyGithub/subconverter-cloudflare" alt='license'>
</p>

## 演示网站

-   [https://sub-convert.visitor-worker.workers.dev/](https://sub-convert.visitor-worker.workers.dev/) <br/>
-   [https://sub.visitor-vps.cloudns.ch/](https://sub.visitor-vps.cloudns.ch/)

## 环境变量

<table>
  <tr>
    <td>变量名</td>
    <td>说明</td>
    <td>变量值</td>
  </tr>
  <tr>
    <td>BACKEND</td>
    <td>后端转换地址</td>
    <td>默认https://url.v1.mk</td>
  </tr>
  <tr>
    <td>SUB_BUCKET</td>
    <td>KV名</td>
    <td></td>
  </tr>
  <tr>
    <td>LOCK_BACKEND</td>
    <td>是否禁用后端地址选择</td>
    <td>默认true</td>
  </tr>
  <tr>
    <td>REMOTE_CONFIG</td>
    <td>自定义远端配置,多个换行</td>
    <td>
        https://xxxxx1<br>
        https://xxxxx2
    </td>
  </tr>
</table>

### 请确保你的 SUB_BUCKET 的值和绑定的 kv 名称一致

![alt text](image.png) ![alt text](image-2.png)

### 更新日志

-   2024-07-18
    -   支持 sing-box 规则

### 鸣谢

-   [https://github.com/bulianglin/psub](https://github.com/bulianglin/psub)
-   [https://github.com/ACL4SSR/ACL4SSRs](https://github.com/ACL4SSR/ACL4SSR)

