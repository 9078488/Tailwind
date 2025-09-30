# Get started with Tailwind CSS

https://tailwindcss.com/docs/installation/using-vite

只能把代码合并到vite.config.js，而不是删除掉原代码


把@import "tailwindcss";加入到index.css，删掉index.css里原来的全部代码，删掉app.css

不需要把<link href="style.css" rel="stylesheet">加到index.html里，在main.jsx里加上import './index.css' 就行

# VS Code插件

Tailwind CSS IntelliSense

Tailwind Fold

# Colors

https://tailwindcss.com/docs/colors

# Padding

https://tailwindcss.com/docs/padding

```
Use pt-<number>, pr-<number>, pb-<number>, and pl-<number> utilities like pt-6 and pr-4 to control the padding on one side of an element:
```

# margin

https://tailwindcss.com/docs/margin

# Width

https://tailwindcss.com/docs/width

# Hover, focus, and other states

https://tailwindcss.com/docs/hover-focus-and-other-states

# Responsive design

sm:flex-row

https://tailwindcss.com/docs/responsive-design

# grid-template-columns

https://tailwindcss.com/docs/grid-template-columns

# flex-wrap

https://tailwindcss.com/docs/flex-wrap

# font-size

https://tailwindcss.com/docs/font-size

# font-weight

https://tailwindcss.com/docs/font-weight

# text-align

https://tailwindcss.com/docs/text-align

# background-color

https://tailwindcss.com/docs/background-color

# border-width

divide-y divide-green-500

https://tailwindcss.com/docs/border-width#reversing-children-order

# min-width

min-w-full

https://tailwindcss.com/docs/min-width#using-a-percentage

# max-width

max-w-7xl

https://tailwindcss.com/docs/max-width#basic-example

# border

border:是否有边框

https://tailwindcss.com/docs/border-radius

# font-size

https://tailwindcss.com/docs/font-size

# overflow

# flex

https://tailwindcss.com/docs/flex

# flex-direction

https://tailwindcss.com/docs/flex-direction#column

--------------------------------------------------
--------------------------------------------------
--------------------------------------------------
# Core concepts

## Colors

# Backgrounds

## background-color

`bg-red-300`







--------------------------------------------------
--------------------------------------------------
--------------------------------------------------
以下是 Tailwind CSS 最常用、最核心的功能模块：

1. 布局与 Flexbox/Grid
这是构建页面结构的基础。

功能模块	常用工具类	作用
Flex 布局	flex, flex-row, flex-col	启用 Flexbox，并设置主轴方向（水平或垂直）。
对齐	justify-center, justify-between, items-center	控制 Flex 项目在主轴和交叉轴上的对齐方式（水平居中、两端对齐、垂直居中等）。
Grid 布局	grid, grid-cols-3, col-span-2	启用 Grid 布局，设置列数，以及元素占据的列数。
间距与空间	gap-4, space-x-4	控制 Flex/Grid 容器中子元素之间的间距。
块级与内联	block, inline, hidden	设置元素的显示类型，或隐藏元素。
2. 间距、尺寸与定位
用于控制元素的大小和位置。

功能模块	常用工具类	作用
内边距 (Padding)	p-4, px-6, pt-2	设置元素内部空间（全方位、水平、顶部）。
外边距 (Margin)	m-4, my-8, ml-auto, mx-auto	设置元素外部空间（全方位、垂直、左边距自动），实现水平居中。
宽度 (Width)	w-1/2, w-full, w-64, w-fit	设置元素的宽度（百分比、全宽、固定像素、适应内容）。
高度 (Height)	h-screen, h-20	设置元素的高度（如占满视口高度）。
定位	relative, absolute, top-0, right-4	设置元素的定位方式和偏移量。
3. 颜色、背景与边框
用于美化元素的外观。

功能模块	常用工具类	作用
背景颜色	bg-white, bg-blue-500, bg-gray-100	设置背景颜色（使用预设的颜色板和深度）。
文本颜色	text-gray-800, text-red-600	设置字体颜色。
边框	border, border-2, border-gray-300	设置边框的宽度和颜色。
圆角	rounded-lg, rounded-full	设置元素的圆角大小（大圆角、圆形/椭圆）。
4. 排版 (Typography)
用于控制文本和字体样式。

功能模块	常用工具类	作用
字体大小	text-sm, text-xl, text-5xl	设置字体大小。
字体粗细	font-normal, font-semibold, font-bold	设置字体粗细（普通、半粗、粗体）。
文本对齐	text-left, text-center, text-right	设置文本的水平对齐方式。
行高	leading-tight, leading-loose	设置文本的行高。
5. 响应式设计 (Responsive Design)
Tailwind 最强大的功能之一，用于针对不同屏幕尺寸应用不同的样式。

功能模块	常用工具类	作用
断点前缀	sm:, md:, lg:, xl:	sm:w-1/2 表示在小屏幕及以上宽度为 50%；lg:flex-row 表示在大屏幕及以上横向排列。
移动优先	无前缀的类（如 w-full, flex-col）始终是默认样式，sm: md: 等只在断点处覆盖默认样式。	
6. 状态与交互
用于处理用户交互和元素状态。

功能模块	常用工具类	作用
Hover 状态	hover:bg-blue-600, hover:scale-105	鼠标悬停时改变背景颜色或放大。
Focus 状态	focus:ring-2, focus:outline-none	元素获得焦点时应用样式（常用于表单输入）。
过渡与动画	transition, duration-300, ease-in-out	平滑地过渡样式变化（如 hover: 状态），设置过渡时间和缓动函数。

