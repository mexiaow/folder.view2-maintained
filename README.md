# FolderView2（维护版）

用于 Unraid `7+` 的 FolderView2 维护分支：在 Dashboard / Docker / VMs 页面把容器与虚拟机按“文件夹”分组展示，方便管理与整理。

## 安装（推荐）

在 Unraid WebUI：`Plugins` → `Install Plugin`，粘贴下面链接并安装：

`https://raw.githubusercontent.com/mexiaow/folder.view2-maintained/main/folder.view2.plg`

[![安装示例](img/plugin_install.png)]

## 备份与迁移

FolderView2 的配置通常在：

- `/boot/config/plugins/folder.view2/docker.json`
- `/boot/config/plugins/folder.view2/vm.json`

如果你是从更早的 `folder.view` 迁移，配置可能在：

- `/boot/config/plugins/folder.view/docker.json`
- `/boot/config/plugins/folder.view/vm.json`

建议更新/切换版本前先在插件页面导出，或手动备份上述文件。

## 更新说明（接管后）

- `2026.01.12.1`：修复 Unraid `7.2+` Dashboard 的 Docker 文件夹布局（展开后恢复横向网格自动换行）。

## 反馈

问题反馈与需求建议：`https://github.com/mexiaow/folder.view2-maintained/issues`

## 参考来源

上游参考仓库：`https://github.com/VladoPortos/folder.view2`
