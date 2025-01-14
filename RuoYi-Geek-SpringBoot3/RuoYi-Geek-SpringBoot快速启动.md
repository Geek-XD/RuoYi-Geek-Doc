# 快速启动

## 项目下载到本地

利用git将项目从远程仓库拉取到本地，用VSCode打开文件夹

```
git clone https://gitee.com/geek-xd/ruoyi-geek-springboot3.git
```

## 配置数据库

rouyi-geek-springboot3 —— rouyi-admin —— src ——resources —— application-druid.yml ，按此路径，修改对应数据库用户名username和密码password、数据库名称ry

```
# 主库数据源
                MASTER:
                    url: jdbc:mysql://127.0.0.1/ry?useUnicode=true&characterEncoding=utf8&zeroDateTimeBehavior=convertToNull&useSSL=true&serverTimezone=GMT%2B8
                    username: root
                    password: 123456
```

运行数据库文件，此过程会用到sql文件的存储地址，即rouyi-geek-springboot3 ——  sql的路径

## 运行项目

VSCode中运行,出现RYGeek表示成功

# 联系我们：

### 技术交流群 QQ：744785891

欢迎所有对 RuoYi-Geek 感兴趣的开发者加入我们的社区😆！

<img src="https://foruda.gitee.com/images/1736235208931843340/f1b736ab_9844561.png" alt="QQ二维码" width="200"/>

### 商业合作😆

我们欢迎各类商业合作机会，无论是技术咨询、项目合作还是其他形式的合作，都期待与您携手共创未来。
如果您有兴趣，请通过以下方式联系我们：

<table>
  <tr>
    <td>
      <strong>QQ</strong><br/>
      QQ号：2086232477  
    </td>
    <td>
      <strong>微信</strong><br/>
      微信号：tantianming000  
    </td>
  </tr>
    <tr>
        <td>
            <img src="https://foruda.gitee.com/images/1736318136310918813/b2ebdfc0_9844561.png "qq.png"" alt="QQ二维码" width="200"/>
        </td>
        <td>
              <img src="https://foruda.gitee.com/images/1736318189364714229/a6020034_9844561.png "wx.png"" alt="微信二维码" width="200"/>
        </td>
    </tr>
</table>

我们期待着与您建立长期稳定的合作关系，并共同探索更多的可能性。
