XHXcodePlug
===========

收集xcode常用的插件和最新的插件，仅供参考，请不要吐槽。

收集适合我自己的插件哦！

####1、[SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander)是对用户自定义或者系统定义的枚举类变量做了处理，扩展switch自动补全所有case。                               
* 使用心得：当你写了一些比较多类型枚举类型的时，那就会要重复输入，好烦，就copy，但是用了这个之后，很快的就补全了，直接写实现代码


####2、[FuzzyAutocompletePlugin](https://github.com/FuzzyAutocomplete/FuzzyAutocompletePlugin)是代码补全的插件，提供对用户自定义方法或者系统api方法都可以预先提示。比如你想要UIImageView，你只需要输入uimv，就会出现提示
* 使用心得：当你输入的方法名关键字会涉及到所有系统或者用户定义方法关键字的时候，你就会有点烦，所以这个看人吧！如果想偷懒，但是还是需要技巧的，比如你想要UIImageView，如果你输入UIge，会很快查到，所以这个看人吧！


####3、[Reveal-Plugin-for-XCode](https://github.com/shjborage/Reveal-Plugin-for-XCode)是Reveal App的一个辅助插件，省去开发者的配置时间，从而达到最大的效果。
* 使用心得：当对一个需求比较特殊的时候，比如富文本显示复杂的数据，这时候可能需要对每行、每列、字体进行细节的调整，可以利用Reveal进行三维空间的查看，这只是对开发哦！如果你想破解别人的app，看别人app的某个功能时，通过它还是可以给予多少帮助的哈！看封装、看继承的基类是什么，具体[点击这里](http://c.blog.sina.com.cn/profile.php?blogid=cb8a22ea89000gtw)                          

####4、[XcodeBoost](https://github.com/fortinmike/XcodeBoost)对未预先定义的函数进行copy，注意了copy的代码里面没有函数的实现，直接复制函数名，而且会把函数原本的注释一起copy，所以我们不需要手工一个一个函数的copy到Interface的api里面了。
* 使用心得：这个插件对于我这个比较懒的程序员来说，还是有用的，比如在开发中，进度很赶，所以没有那么多时间来规划和设计，所以直接对每个功能的函数直接实现了，对于这样是不规范的，所以需要把公开的api放在.h添加相应的注释、把私有的方法放在.m的Interface里面，再添加注释，哇！看起来好很多了，说到添加注释，下面会介绍另外一个插件


