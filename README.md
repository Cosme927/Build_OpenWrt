一、说明

    1、本仓库使用P3TERX大神脚本编译OpenWrt固件，对少许代码做了修改，并且根据自己需求集成了常用的软件包，没有多余插件。

    2、本仓库目前加入的设备有：x86、NanoPi R4S、NanoPi R2S、微加云、章鱼星球、N1、Newifi3、CanBox(CM520-79F)。
    
    3、微加云、章鱼星球、N1设备编译好的固件需配合Flippy打包源码打包后才能使用，不可直接使用。

二、固件特点

    1、固件默认IP：192.168.123.1，默认用户名：root，密码：password。
    
    2、所有固件均集成PassWall、动态DNS、网络唤醒、WatchCat插件，常用且实用。
    
    3、x86、NanoPi R4S、NanoPi R2S、微加云、章鱼星球、N1这几个设备的固件集成了薅羊毛所需的环境，包括但不限于Docker、
       Docker-Compose、Node.js、Node-NPM、Perl、Python3等。
    
三、文件-设备对照表

        NanoPi_R2S.config - 友善R2S
        NanoPi_R4S.config - 友善R4S
           Newifi3.config - 新路由三
            CanBox.config - 星际宝盒
             Vplus.config - 微加云、章鱼星球
               x86.config - x86
                N1.config - 斐讯N1
   
