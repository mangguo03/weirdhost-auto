1、fork到自己的github仓库
2、获取续期项目链接地址

<img width="622" height="423" alt="6648f1ff31ea7d2fab0d92eac5372dd5" src="https://github.com/user-attachments/assets/12aa5b5e-ed4e-47c3-97a3-46024f74ed27" />

3、获取续期项目地址的网络cookie
在当前页面按 f12 进入 开发者页面

<img width="818" height="843" alt="e600f5a5fc9c380d2428f425bcfe4278" src="https://github.com/user-attachments/assets/36ba080f-e49c-420e-b842-1d60f8ac839f" />

4、给项目添加密钥
进入fork的项目，


在仓库页面的右上角，点击 ⚙️ Settings（设置）。
在左侧菜单中，找到并点击 Secrets and variables → Actions。
点击 New repository secret（新建仓库密钥） 按钮。
在 Name（名称） 输入框中填入：REMEMBER_WEB_COOKIE  内容填入获取的 cookie值

<img width="887" height="833" alt="499783c3c1094d3e5fb337b1d0236978" src="https://github.com/user-attachments/assets/22407e94-942b-4bc9-a3f6-510077425dd8" />

5、编辑代码 
关闭翻译 切换英文状态，否则会出现 语法错误
找到对应文件、进入进行编辑  
1是文件名称、地址
2是 续期项目链接地址
3是 项目页面韩文按钮，原来项目带空格的 ==使用node语言部署的项目 必须把空格都删除（7、109、110、118、124行的韩文空格都要删除），使用java语言部署的项目 不用删除空格

<img width="892" height="705" alt="9fdd1503127d7b79bede118ef2b810f7" src="https://github.com/user-attachments/assets/82a41e78-0015-4787-871d-afbe84e734ad" />

6、运行项目

<img width="945" height="418" alt="5f70c96b08006cde8dd83fb63426ec9c" src="https://github.com/user-attachments/assets/0bf84dc0-2071-4baa-901c-97569bbae6fd" />
