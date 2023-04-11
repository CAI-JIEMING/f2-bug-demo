# f2-bug-demo

When there is content above the chart, it will cause the position where the legend triggers the click event to deviate from the rendered legend position

<img src="./images/f2-bug-demo.png" style="zoom:100%;" />

如图所示：图表上方如果有内容，会导致 图例legend 的展示位置与实际点击触发的位置不同，例如图片中添加了一个title，图例展示位置点击无效，在图例上方一点的位置点击才能触发点击事件