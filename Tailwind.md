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

## Responsive design

`md:w-32 lg:w-48`

## Hover, focus, and other states

`hover:bg-yellow-600`

`focus:bg-cyan-600`：用于按钮、文本框等

## Colors

# Flexbox & Grid

## grid-template-columns

`grid`:激活grid容器

`grid-cols-2`

## gap

`gap-8`

`gap-x-16` 

`gap-y-20`

## align-items

`items-center`

# Spacing

## padding

`px-30`

`py-30`

## margin

`mx-auto`：主要作用是将一个块级元素（block-level element）在其父容器中水平居中

# Sizing

## max-width

`max-w-7xl`

## height

`h-96`

# Typography

## font-size

`text-lg`

## font-weight

`font-bold`

## letter-spacing

`tracking-wider`

## line-height

`leading-10`

## text-align

`text-left`

`text-center`

`text-right`

## color

`text-white`

`text-green-600`

## text-transform

`capitalize`

# Backgrounds

## background-color

`bg-red-300`

# Borders

`border` 添加边框

## border-radius

`rounded-lg`

## border-width

`border-3"`

## border-color

# Transitions & Animation

## transition-duration 

`hover:text-emerald-600 duration-300`











