#### Installation
* update nuget for visual studio
  > Update your NuGet Package Manager extension. Go to Tools->Extensions and Updates and select  Updates->Visual Studio Gallery. Update the NuGet Package Manager extension. Then try to install the package after Visual Studio gets restarted
#### Tips
* .NET Standard包与.NET Framework包
* 安装artifactory oos版本
    * [artifactory oos](https://jfrog.com/open-source/#artifactory)
    * [使用Artifactory简单搭建本地library仓库](https://blog.csdn.net/lablenet/article/details/64905370)
    * [使用Artifactory搭建私有Maven仓库](https://blog.csdn.net/zcmain/article/details/78135660)
    * [使用 Artifactory 搭建 Maven 私服](https://www.jianshu.com/p/dfd02fa239e2)
    * pku**901
    * proxy key: mark_artifactory_key
    * host:mark_artifactory_host
    * port:8081
    * <nonProxyHosts>在Maven的Setting.xml文件中的设置
  * create nuget package from dlls(tow ways)
    * [Create nuget package from dlls](https://stackoverflow.com/questions/43277715/create-nuget-package-from-dlls)
    * [NuGet Package Explorer](https://github.com/NuGetPackageExplorer/NuGetPackageExplorer)
    * nuget.ext
* C++ dll打包问题
  * [CoApp](http://coapp.org/)
  * [创建c++的nuget库](https://blog.csdn.net/bjrxyz/article/details/51781640)
  * [NuGet for C++](https://blogs.msdn.microsoft.com/vcblog/2013/04/26/nuget-for-c/)
  * [coapp packages](https://www.nuget.org/profiles/coapp/)
  * [Tutorials for building packages](http://coapp.org/pages/tutorials.html)
  * [How to Build a Package](http://coapp.org/tutorials/building-a-package.html)
  * [AutoPackage Script Guide](http://coapp.org/reference/autopackage-ref.html)
  * [Find-Build-Share-Use: Using NuGet for C and C++ Libraries](https://www.youtube.com/watch?v=PKp61HsnG4U)
* install pwowershell tool for vs2017
  * click menu of 'extensions and update'
  * search powershell 
  * download
  * close window to install
#### 问题
* 如何安装package
* 如何上传自己编译的package
* 如何更新自己编译的package
* 是否可以将已存在的dll（没有源代码，或者不通过修改源代码方式），上传为package
* dll的组装问题，即dll的层次结构（如dll插件）
* 依赖包可以递归安装
* 
#### 参考
* [NuGet 简介-微软官方文档](https://docs.microsoft.com/zh-cn/nuget/what-is-nuget)
* [NuGet Blog](https://blog.nuget.org/)