# uploadView
基于jquery的图片上传预览功能

## 实例
```
                $("#up").uploadView({
                    uploadBox: '#bigBox',//设置上传框容器
                    showBox : '#preview',//设置显示预览图片的容器
                    width : 82, //预览图片的宽度，单位px
                    height : 82, //预览图片的高度，单位px
                    allowType: ["jpeg", "jpg", "bmp", "png"], //允许上传图片的类型
                    maxSize :2, //允许上传图片的最大尺寸，单位M
                    success:function(e){
                        //
                    }
                });
            
```
