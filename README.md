
在 GitHub 仓库中，进入右上角Settings

在侧边栏找到Secrets and variables，点击展开选择Actions，点击New repository secret
在 GitHub 仓库中，创建一个名为 ACCOUNTS_JSON 的 Secret，将 JSON 格式的账号密码字符串作为它的值。例如：  
[  
  { "username": "qishihuang", "password": "zhanghao", "panelnum": "3" },  
  { "username": "zhaogao", "password": "daqinzhonggong", "panelnum": "1" },  
  { "username": "heiheihei", "password": "shaibopengke", "panelnum": "2" }  
]
