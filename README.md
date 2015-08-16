基于metronic3.5的前后台简化模板
=======================
[demo地址](http://template.loveda.cn/metronic3/)

目录说明
-------------
默认根目录为后台管理模板，frontend目录为前台模板

后台插件说明
-------------
`core.min.css`
包含以下插件：

```
font-awesome.min.css
simple-line-icons.min.css
bootstrap.min.css
uniform.default.min.css
bootstrap-switch.min.css
jquery-ui-1.10.3.custom.min.css
```

`jquery.min.css`
包含以下插件：

```
jquery.tagsinput.css
jquery.nestable.css
```

`theme.min.css`
包含以下插件：

```
包含layout.css、metronic的plugin.css、圆角样式components-rounded.css
默认使用metronic的layout模板+darkblue.css主题
其他主题在css/themes目录下，可以在页面中包含的theme.min.css下方来替换新主题
```

`bootstrap.min.css`
包含以下插件：

```
bootstrap-colorpicker
bootstrap-datepaginator
bootstrap-datepicker
bootstrap-daterangepicker
bootstrap-datetimepicker
bootstrap-timepicker
```

`pages.min.css`
包含了所有metronic3.5的后台模板样式文件：

```
about-us.css、error.css、coming-soon.css、image-crop.css
inbox.css、invoice.css、lock.css、login3.css
news.css、portfolio.css、pricing-table.css、pricing-tables.css
profile.css、search.css、tasks.css、timeline.css、todo.css

```


`plugins.core.min.js`
包含以下插件：

```
jquery.min.js、jquery-migrate.min.js、jquery-ui-1.10.3.custom.min.js
bootstrap.min.js、bootstrap-hover-dropdown.min.js、jquery.slimscroll.min.js
jquery.blockui.min.js、jquery.cokie.min.js、jquery.uniform.min.js、

```

`app.min.js`
包含metronic的核心扩展文件：

```
metronic.js、layout.js、quick-sidebar.js、demo.js、datatable.js

```

`bootstrap.plugins.min.js`

包含以下插件：
```
jquery.tagsinput.min.js
bootstrap-colorpicker/js/bootstrap-colorpicker.js
bootstrap-daterangepicker/moment.min.js
bootstrap-datepicker/js/bootstrap-datepicker.js
bootstrap-daterangepicker/daterangepicker.js
bootstrap-datetimepicker/js/bootstrap-datetimepicker.min.js
bootstrap-timepicker/js/bootstrap-timepicker.min.js
bootstrap-datepaginator/bootstrap-datepaginator.min.js
bootbox/bootbox.min.js'
```


`jquery.plugins.min.js`
包含以下插件：
```
jquery.tagsinput.min.js
jquery.nestable.min.js
query.backstretch.min.js
jquery.zoom.min.js
jquery.easing.min.js
jquery.mockjax.min.js
jquery.parallax.min.js
jquery.pulsate.min.js
jquery.scrollTo.min.js
jquery.sparkline.min.js
jquery.input-ip-address-control-1.0.min.js
jquery-validation/js/jquery.validate.min.js
jquery-validation/js/additional-methods.min.js
jquery.md5.min.js
jquery.base64.min.js
```

其他自定义添加的插件在plugins目录下，核心文件中的图片、字体、富媒体资源均整合到对应
的images或img、fonts和media目录



前台插件说明
-------------
使用的metronic2的版本

`plugins.min.css`
包含以下插件：

```
font-awesome/css/font-awesome.min.css
bootstrap/css/bootstrap.min.css
bootstrap/css/bootstrap-theme.min.css
fancybox/source/jquery.fancybox.min.css
jquery-ui/jquery-ui.min.css
jquery-ui/jquery-ui.theme.min.css
bxslider/jquery.bxslider.min.css
layerslider/css/layerslider.min.css
uniform/css/uniform.default.min.css'
```
对于jquery-ui，使用1.11.4版本，仅包含core+slider需要的组件依赖包，使用的smoothness主题


`pages.min.css`
包含了metronic的style.css、style-metronic.css、style-responsive.css文件


`core.min.js`
包含以下插件：

```
jquery-1.10.2.min.js
jquery-migrate-1.2.1.min.js
bootstrap.min.js
back-to-top.min.js
jquery.slimscroll.min.js

```

`plugins.core.min.js`

包含以下插件：
```
fancybox/source/jquery.fancybox.pack.min.js
fancybox/source/helpers/*.min.js
bxslider/jquery.bxslider.min.js
jquery-easing-1.3.min.js
rateit/src/jquery.rateit.min.js
zoom/jquery.zoom.min.js
jquery-ui/jquery-ui.min.js
uniform/jquery.uniform.min.js
bootstrap-touchspin/bootstrap.touchspin.min.js
```


`pages.min.js`
包含metronic2的单页面范例所有js文件


layerslider插件在页面中单独引用，此组件仅在index.html、index-light-footer.html页面被引用

单页面插件说明
-------------
`core.min.js`

包含以下插件：
```
jquery.min.js
jquery-migrate.min.js
bootstrap.min.js
```

`plugins.min.js`

包含以下插件：
```
jquery.fancybox.pack.min.js
jquery-easying-1.3.min.js
jquery.parallax.min.js
jquery.scrollTo.min.js
jquery.nav.min.js
```

顶部轮播插件使用的是slider-revolution-slider