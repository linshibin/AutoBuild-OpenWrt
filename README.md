# AutoBuild-OpenWrt

Build OpenWrt firware [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) using GitHub Actions  
Hereby thank P3TERX for his amazing job: https://github.com/P3TERX/Actions-OpenWrt/

## Usage

- Sign up for [GitHub Actions](https://github.com/features/actions/signup)
- Fork [this GitHub repository](https://github.com/esirplayground/AutoBuild-OpenWrt)
- Click [.github/workflows] folder on the top of repo and you could see few workflow files, Each for one particular architecture(device).
- Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
- The build starts automatically. Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

[For the details please visit my Y2B Channel (in Chinese) | 视频教程](https://www.youtube.com/c/esirplayground)


在Lede的源码上增加了一个Lienol的PassWall。

感谢两位大神，感谢esirplayground的脚本和youtub的教程。

修改脚本自动添加Lienol的软件源，调用x86_64.config设置添加PassWall。

整个编译时间比较长

如果不需要VM、EFI编译可以在x86_64.config标注掉，这样时间会短一下。

薅一下微软的羊毛，不用本地搭建环境，也不需要全局科学上网。

第一次玩，谢谢观看。感谢大神！
