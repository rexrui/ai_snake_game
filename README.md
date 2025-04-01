# 贪吃蛇小游戏

这是一个使用 HTML、CSS 和 JavaScript 实现的贪吃蛇小游戏。玩家可以控制蛇移动，吃食物得分，还能调整游戏速度、重新开始游戏、保存和加载游戏记录。

## 功能特性
1. **基本游戏玩法**：玩家可以使用方向键控制蛇的移动方向，蛇吃到食物后身体会变长，得分增加。
2. **速度调节**：通过滑块可以调节游戏速度，从 0.25 到 16。
3. **重新开始**：点击“重新开始”按钮可以重置游戏。
4. **保存记录**：点击“保存记录”按钮可以保存当前游戏状态，包括蛇的位置、方向、食物位置、得分和速度。
5. **历史记录管理**：可以查看、加载和删除历史游戏记录。

## 安装和使用
### 安装
本项目无需安装，只需将项目文件下载到本地即可。

### 使用
1. 打开 `snake_game.html` 文件，即可开始游戏。
2. 使用方向键（上、下、左、右）控制蛇的移动方向。
3. 拖动“速度”滑块调节游戏速度。
4. 点击“重新开始”按钮重置游戏。
5. 点击“保存记录”按钮保存当前游戏状态。
6. 在“历史记录”区域可以加载或删除之前保存的游戏记录。

## 代码结构
### HTML (`snake_game.html`)
- 定义了游戏界面的结构，包括标题、游戏画布、控制按钮、得分板和历史记录区域。
- 引入了 Tailwind CSS 和 Font Awesome 图标库。
- 嵌入了 JavaScript 代码来实现游戏逻辑。

### CSS
- 使用内联样式定义了游戏界面的布局和样式，包括背景颜色、边框、按钮样式等。

### JavaScript
- 获取 HTML 元素的引用，如画布、按钮、滑块等。
- 定义游戏的基本变量，如蛇的位置、方向、食物位置、得分和速度。
- 实现了绘制蛇、食物和得分的函数。
- 实现了蛇的移动逻辑，包括穿越墙壁处理。
- 实现了游戏循环，定时更新游戏状态。
- 处理键盘事件，控制蛇的移动方向。
- 处理按钮点击事件，如重新开始、保存记录、加载记录和删除记录。

## 贡献
如果你想为这个项目做出贡献，可以按照以下步骤进行：
1. 克隆项目仓库。
2. 创建一个新的分支进行开发。
3. 提交你的代码并创建一个 Pull Request。

## 许可证
本项目采用 [MIT 许可证](https://opensource.org/licenses/MIT)。
