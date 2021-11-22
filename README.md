
# Hugo Plantuml功能插件

用于转化 plantuml 代码块为图片，效果如[博客][L1]

使用方法,编写代码块：

    ```puml
    @startuml

    class Car {
    color
    model
    +start()
    #run()
    #stop()
    }

    Car <|- Bus
    Car *-down- Tire
    Car *-down- Engine
    Bus o-down- Driver

    @enduml
    ```

## 后续计划

目前功能基本满足使用，不过对过长代码块可能请求比较慢，后续计划在本地生成图片，官方代码库有相关的功能分支待还没合并

- [ ]: 本地生成SVG
- [ ]: 图片和源代码的切换

<!-- links -->

[L1]:https://zone.dnfn.tech/post/ddc9e90cd9852e2ffeb3f84ed81fe3f6/