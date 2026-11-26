# ROC工具箱 for CAXA 3D

本仓库仅用于发布 ROC工具箱 的安装包。

随机上色
<img width="2545" height="1496" alt="随机上色" src="https://github.com/user-attachments/assets/6c78676d-c48a-48bd-a105-6b9bbfa7c625" />
批量隐藏显示标准件
<img width="2545" height="1496" alt="批量隐藏显示标准件" src="https://github.com/user-attachments/assets/a804a0d6-9e3f-4f42-9b71-535f2aab2371" />
EXB转PDF
<img width="2545" height="1496" alt="EXB转PDF" src="https://github.com/user-attachments/assets/e98eecfe-c5ba-4a49-affb-e7384969e47d" />
零部关联工程图批量转PDF
<img width="2545" height="1496" alt="零部关联工程图批量转PDF" src="https://github.com/user-attachments/assets/70cedc4b-0ef3-4b1f-98f5-fa2267adc1e3" />


## 下载

当前最新版本：v2.2.0（前往 [Releases](../../releases) 查看全部版本）：

- `ROC_Toolbox_CAXA3D_vX.Y.Z.zip` —— 安装包
- `ROC_Toolbox_CAXA3D_vX.Y.Z.zip.sha256.txt` —— SHA-256 校验值

## v2.2.0 更新

- “打开”对话框新增文件名检索：列表下方输入关键字即可在当前文件夹中搜索
- 检索不区分大小写，与“快速过滤器”叠加生效，输入即时筛选、回车立即执行
- 状态栏同步显示检索结果的项数、零件数与部件数
- 在线更新流程优化：下载完成后先提示将强制关闭 CAXA 3D，确认后自动关闭并安装
- 安装完成后提示是否立即打开 CAXA 3D，选择“否”则关闭更新窗口

## v2.1.1 更新

- 修复“关闭其他”未统计/未关闭启动时自动新建的空文档（如“设计16”）的问题
- 改为枚举全部已打开文档（含未保存文档），确认提示中的窗口数量与实际标签页一致

## v2.1.0 更新

- 新增“关闭其他”：保留当前窗口，一键关闭其余所有已打开窗口
- 关闭前会提示待关闭窗口数量；若存在未保存修改的窗口，会额外警告并默认不继续
- 按钮仅在打开两个以上窗口时可用

## 安装

1. 解压下载的 zip 包
2. 关闭所有 CAXA 3D 窗口
3. 右键 `install.bat`，选择“以管理员身份运行”
4. 启动 CAXA 3D，插件会自动出现在“ROC工具箱”面板

v1.3.6 起支持**在线更新**：启动 CAXA 后自动静默检查（24 小时一次），也可在工具栏点“检查更新”手动升级。

## 环境要求

- CAXA 3D 实体设计 2024 及以上版本（x64）
- Windows 10 / 11

## 文件校验

```powershell
certutil -hashfile ROC_Toolbox_CAXA3D_v2.2.0.zip SHA256
```

## 说明

- 第三方扩展工具，与宿主软件官方无关联
- 个人非商用免费使用
- 商用授权与功能定制请联系：191232796@qq.com
