# GMI - 精神疾病指南

这是一个基于 MkDocs 构建的精神疾病指南网站，提供关于抑郁症、焦虑症、躁狂症、双向情感障碍、人格分裂和精神分裂症的详细信息。

## 功能特点

- 📚 详细的疾病介绍和症状分级
- 💊 全面的治疗方法和资源
- 🎯 清晰的导航结构
- 📱 响应式设计
- 🚀 自动部署到 GitHub Pages

## 本地开发

### 环境要求

- Python 3.x
- pip

### 安装依赖

```bash
pip install -r requirements.txt
```

### 本地预览

```bash
mkdocs serve
```

访问 `http://127.0.0.1:8000` 查看网站。

### 构建静态文件

```bash
mkdocs build
```

## 部署到 GitHub Pages

### 自动部署

本项目已配置 GitHub Actions 自动部署。当代码推送到 `main` 或 `master` 分支时，会自动构建并部署到 GitHub Pages。

### 手动设置步骤

1. **Fork 或上传项目到 GitHub**

2. **启用 GitHub Pages**
   - 进入仓库的 Settings
   - 找到 Pages 选项
   - Source 选择 "GitHub Actions"

3. **推送代码**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

4. **查看部署状态**
   - 在 Actions 标签页查看工作流运行状态
   - 部署成功后，网站将在 `https://your-username.github.io/repository-name` 可用

## 项目结构

```
GML/
├── docs/                    # 文档源文件
│   ├── index.md            # 首页
│   ├── depression.md       # 抑郁症
│   ├── anxiety.md          # 焦虑症
│   ├── mania.md            # 躁狂症
│   ├── bipolar.md          # 双向情感障碍
│   ├── personality_disorder.md  # 人格分裂
│   ├── schizophrenia.md    # 精神分裂症
│   └── treatment.md        # 治疗资源
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions 工作流
├── mkdocs.yml              # MkDocs 配置文件
├── requirements.txt        # Python 依赖
└── README.md              # 项目说明
```

## 导航结构

- **首页**: 项目介绍和导航
- **疾病介绍**: 
  - 抑郁症
  - 焦虑症
  - 躁狂症
  - 双向情感障碍
  - 人格分裂
  - 精神分裂症
- **治疗资源**: 治疗方法和支持资源

## 免责声明

本指南仅供教育和信息目的，不能替代专业医疗建议、诊断或治疗。如有心理健康问题，请咨询合格的医疗专业人员。

## 紧急联系

如果您或他人面临紧急心理健康危机，请立即联系：
- 中国：400-161-9995（北京危机干预热线）
- 全国：12320（卫生热线）
- 紧急情况：120（急救）

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目。

## 许可证

本项目仅供学习和参考使用。