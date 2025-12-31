# 自动检测20+种格式：fancy.core.parsers
# - 结构化数据: JSON, YAML, TOML, XML, CSV
# - 配置文件: INI, .env, Properties
# - 日志文件: Nginx, Apache, Syslog, Docker
# - 代码文件: Python, JavaScript, Go, Rust
# - 数据库: SQL, PostgreSQL, MySQL输出
# 检测策略: 文件扩展名 + 内容特征 + 启发式分析

# 格式化特性：fancy.core.formatters
# 1. 语法高亮: 基于Pygments，支持256色和真彩色
# 2. 智能缩进: 自适应缩进，保留原始结构
# 3. 对齐优化: 自动对齐键值对、表格数据
# 4. 折叠/展开: 支持大结构折叠，交互式展开
# 5. 差异显示: 类似git diff的变更高亮
# 6. 行号显示: 可选绝对/相对行号
# 7. 彩虹括号: 嵌套括号彩色配对

# 主题特性：fancy.core.themes
# - 内置主题: dracula, monokai, solarized, nord, github, vs-code
# - 自定义主题: 支持TOML/YAML/JSON格式
# - 主题继承: 基础主题 + 覆盖
# - 环境适配: 自动检测终端颜色支持
# - 语法映射: 精细控制每个语法元素的颜色
# - 样式组合: 粗体、斜体、下划线、背景色

# 插件系统：fancy.plugins
# 1. 自动发现: 通过entry_points发现插件
# 2. 热加载: 开发时自动重载插件
# 3. 优先级: 插件执行顺序控制
# 4. 依赖管理: 插件间依赖关系
# 5. 配置继承: 插件配置继承主配置
# 6. 钩子系统: 预处理/后处理钩子

# 配置层次（高→低优先级）：fancy.config
# 1. 命令行参数
# 2. 环境变量 (FANCY_*)
# 3. 本地配置 (.fancy.toml, fancy.toml)
# 4. 项目配置 (pyproject.toml的[tool.fancy]节)
# 5. 用户配置 (~/.config/fancy/config.toml)
# 6. 全局配置 (/etc/fancy/config.toml)
# 7. 内置默认配置

# 渲染特性：fancy.core.renderers
# 1. 终端检测: 自动检测终端能力（颜色、宽度、Unicode）
# 2. 流式渲染: 大文件逐块渲染，低内存占用
# 3. 渐进显示: 优先渲染可见部分
# 4. 动画支持: 加载动画、进度指示
# 5. 交互模式: 键盘交互、鼠标支持（可选）
# 6. 分页输出: 类似less的分页浏览

# 实用工具：fancy.utils
# 1. ansi.py: ANSI转义序列管理
# 2. color.py: 颜色空间转换、调色板
# 3. helpers.py: 文本处理、宽度计算
# 4. validators.py: 输入验证、配置验证
# 5. terminal.py: 终端信息检测
