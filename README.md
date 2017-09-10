# GPUImageFilter

目前在项目中用到了滤镜处理，借助了GPUImage，感觉还行就把我的思路和制作过程写下来给大家分享一下。
代码非常简单，通俗易懂。

![效果图](https://github.com/sunjinshuai/GPUImageFilter/blob/master/GPUImageFilter.gif)

```
typedef NS_ENUM(NSInteger, GPUImageColormatrixFilterType) {
    GPUImageColormatrixFilterTypeORI = 0,   // 原图
    GPUImageColormatrixFilterTypeFUGU,      // 复古
    GPUImageColormatrixFilterTypeDANYA,     // 淡雅
    GPUImageColormatrixFilterTypeHEIBAI,    // 黑白
    GPUImageColormatrixFilterTypeLANGMAN,   // 薄暮
    GPUImageColormatrixFilterTypeJIUHONG,   // 酒红
    GPUImageColormatrixFilterTypeRUISE,     // 流年
    GPUImageColormatrixFilterTypeGETE,      // 哥特
    GPUImageColormatrixFilterTypeLANDIAO,   // 白露
    GPUImageColormatrixFilterTypeQINGNING,  // 少女
    GPUImageColormatrixFilterTypeGUANGYUN,  // 时光
    GPUImageColormatrixFilterTypeMENGHUAN,  // 维也纳
    GPUImageColormatrixFilterTypeYESE,      // 夜色
    GPUImageColormatrixFilterTypeLOMO,      // 布拉格
};
```
ps:
我是一个iOS的苦行僧，喜欢开源，平常也会在github上上传一些个人的项目，欢迎志同道合的朋友一起加入。
另外，如果我封装的这个控制器能帮到你，就star一下吧。
