# html-orientation-judge
judge html page in mobile is portrait screen or landscape screen

`在移动端想要判断页面是横屏还是竖屏，可以根据window.orientation参数来判断，在PC浏览器下是不支持orientation参数的。在监听移动端横竖屏变化的时候可以做一些自己想要处理的逻辑，这里通常是给页面增加或者删除某个class样式，以达到横竖屏样式兼容。`

| #       | mobile|    pc    |
|---------|-------|----------------|
| portrait| `0 \ 180`   |  undefined     |
|landscape| `90 \ -90`  |  undefined     |

