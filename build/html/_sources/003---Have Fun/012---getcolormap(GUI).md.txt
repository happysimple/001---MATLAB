# getcolormap(GUI)

1.初步绘图

```matlab
figure;
pcolor(peaks(50));
shading interp
colorbar;
```

2.打开GUI，选择心仪的`colormap`后点击`copy`

<img src="..\_static\010.png" alt="003" style="zoom:46%;" />

3.粘贴代码至脚本，并设置colormap

```matlab
% 第一行代码是粘贴过来的
mycolormap = customcolormap(linspace(0,1,8),mycolor(1,1));
colormap(mycolormap)
```
4.再次绘图

<img src="..\_static\011.png" alt="003" style="zoom:20%;" />


---

下载方式：

{download}`GUI源码<../_static/get_colormap.zip>`













