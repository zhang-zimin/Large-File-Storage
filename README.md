# LFS 测试项目

本项目用于试验和演示 Git LFS（Large File Storage）功能。

## 步骤
1. 初始化 Git 仓库
2. 安装并配置 Git LFS
3. 添加大文件进行测试

---

## 说明
- **跳过大文件下载**：如果你只想先克隆仓库但不下载大文件，可以使用如下命令（PowerShell 示例）：
  
  ```powershell
  $Env:GIT_LFS_SKIP_SMUDGE = 1; git clone https://github.com/zhang-zimin/Large-File-Storage.git
  ```

- **后续下载大文件**：克隆完成后，如需下载 LFS 管理的大文件，进入仓库目录后执行：

  ```sh
  git lfs pull
  ```
