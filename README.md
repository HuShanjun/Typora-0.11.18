# Typora 0.11.18

Typora 0.11.18 is the last free version of Typora, whose official download links have already expired.

As there has been a stable cracking solution for the latest versions, it is no longer recommended to use this outdated one.



修改注册表（一劳永逸，推荐）

1. 通过锁定注册表中的“最后检查时间”来骗过软件。
2. 按下键盘上的 Win + R键，输入 regedit并回车，打开注册表编辑器。
3. 在顶部地址栏粘贴：HKEY_CURRENT_USER\Software\Typora并回车。
4. 在右侧窗口中找到名为 LastBetaCheckTime的项（如果没有，就新建一个 DWORD (32位)​ 值，命名为 LastBetaCheckTime）。
5. 双击它，将数值数据改为 0（十六进制或十进制都可以）。
6. 右键左侧 Typora项 → 权限(Permissions)。
7. 选中你的当前用户（或 Users/ Administrators），下方权限框中勾选「拒绝(Deny) → 完全控制」和「拒绝 → 读取」（至少勾"完全控制"的拒绝）。

点击确定，重启电脑或重启 Typora 即可。
