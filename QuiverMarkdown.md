
Markdown cells support standard Markdown syntax as well as GitHub Flavored Markdown (GFM). Open the preview to see these rendered.

### Basics

# H1
## H2
### H3
#### H4
##### H5
###### H6

---

*italic*, **bold**, ~~Scratch this.~~

`inline code`

`package com.company;

public class Main {

    public static void main(String[] args) {
	// write your code here
        System.out.println("hello world");
    }
    }`
    
`{{ test
}
}`
`the bracket that outside the line will not be included'

### Lists

1. First ordered list item
2. Another item
* Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
1. Ordered sub-list
4. And another item.
5.  >SSSSS

### Quote


### Quote

> Peace cannot be kept by force; it can only be achieved by understanding.

### Links

[I'm an inline-style link](https://www.google.com)
http://example.com

You can also create a link to another note: (Note menu -> Copy Note Link -> Paste)
[01 - Getting Started](quiver-note-url/D2A1CC36-CC97-4701-A895-EFC98EF47026)

### Tables

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
|12|21|22222|


L1   | L2  | L3 | L4 | L5
----- | ----- | ------ | ----- | -----
<a href="#Moom" name="Moom">★</a>★★★★ | [Moom] | 窗口管理，多屏切换工具 | $10 | [#](http://mac.appstorm.net/reviews/productivity-review/moom-window-management-rethought/)
<a href="#iStat-Menus" name="iStat-Menus">★</a>★★★★ | [iStat Menus] | 实时显示系统状态、网速等 | $16 | [#](http://mac.appstorm.net/reviews/utilities/istat-menus-4-menubar-system-monitoring-improved/)
<a href="#Bartender" name="Bartender">★</a>★★★★ | [Bartender] | 自定义右上角 Menu 栏图标 | $15 | [#](http://www.macworld.com/article/2013739/mac-gems-bartender-helps-you-take-control-of-menu-bar-icons.html)

How to mark a BLUE star (by hylink): '<a href="#Bartender" name="Bartender">★</a>'



### GFM Task Lists

- [ ] a task list item
- [ ] list syntax required
- [ ] normal **formatting**, @mentions, #1234 refs
- [ ] incomplete
- [x] completed

### Inline LaTeX

You can use inline LaTeX inside Markdown cells as well, for example, $x^2$.









--------------------------LaTeX  seems does not work-----------------------------------------------------=-------------------------
LaTeX cells make it easy to typeset math equations. For example,

\begin{align}
\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} & = \frac{4\pi}{c}\vec{\mathbf{j}} \\
\nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\
\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\
\nabla \cdot \vec{\mathbf{B}} & = 0
\end{align}
