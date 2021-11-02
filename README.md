# 前端常用框架&库收集

### 背景
现阶段前端开发中,大量的重复性工作或者关键技术都有现成的库来帮忙解决(如果你发现没有,那就是你没找到).   
现在解决问题的框架和库太多了,如何合理的使用这些框架库决定了你工作的效率的高低.    
对库使用的经验,对库底层代码研究的程度,对前端基础研究的程度构成了你的前端经验.  
为了方便查询解决方案,所以在这里分门别类的记录一下,希望能给大家也带来帮助.

### 常用框架分类

#### web 框架

| 框架 | 简介 |
| :--- | --- |
| [React](https://zh-hans.reactjs.org/) | 最流行的前端界面库 | 
| [Vue2](https://cn.vuejs.org/v2/guide/) | 流行的构建用户界面库，仅次于 React | 
| [Vue3](https://v3.cn.vuejs.org/guide/introduction.html) | vue2的升级版,添加了破坏性更改,采用 ts 重构|
| [Svelte](https://svelte.dev/) | 将声明组件转换为精准高效更新 DOM 的 JS 代码库 |
| [single-spa](https://single-spa.js.org/) | 主流的微前端框架 |

#### 图片处理框架
> 2020 十大 JS 图像处理库

|框架      | 简介|
|---|---|
|[Pica](http://nodeca.github.io/pica/demo/) | 此插件可助你减小大图的上传大小，从而节省上传时间。它允许你在浏览器中调整图像大小，响应迅速并且不会出现像素化，因为它会从 Web Workers、WebAssembly、createImageBitmap 方法以及纯 JavaScript 中自动选择最佳的可用技术。|
|[Lena.js](https://ourcodeworld.com/articles/read/515/how-to-add-image-filters-photo-effects-to-images-in-the-browser-with-javascript-using-lena-js)|这个炫酷的图像库虽然非常小，但其大约有 22 个图像滤镜，非常好玩。你还可以向 GitHub 仓库中创建并添加新滤镜|
|[Compressor.js](https://github.com/fengyuanchen/compressorjs)|这是一个简单的 JavaScript 图像压缩器，它使用浏览器原生的 canvas.toBlob API 来处理图像压缩。这使你可以在 0 到 1 之间设置压缩输出质量。|
|[Fabric.js](http://fabricjs.com/)|Fabric.js 允许你使用 JavaScript 在网页上的 HTML canvas 元素上轻松创建简单的形状，例如矩形、圆形、三角形和其他多边形，或者由许多路径组成的更复杂的形状。Fabric.js 还允许你使用鼠标来操纵这些对象的大小，位置和旋转。也可以使用 Fabric.js 库更改这些对象的属性，例如它们的颜色，透明度，网页上的深度位置，或选择这些对象的组。Fabric.js 还允许你将 SVG 图像转换为 JavaScript 数据，并直接在 canvas 元素中使用。|
|[Blurify](https://github.com/dabanlee/blurify)|这是一个很小的（约 2kb）库，用于模糊图片，并具有从 css 模式到 canvas 模式的优秀降级支持。该插件在以下三种模式下工作：1. css: 使用 filter 属性(默认); 2. canvas: 使用 canvas 到处 base64 格式; 3. auto: 优先使用 css 模式, 不支持则自动转换为 canvas 模式|
|[MergeImages](https://github.com/lukechilds/merge-images)|该库让你可以轻松地合成图像，而不会弄乱画布。有时，使用画布可能会有些痛苦，尤其是在你只需要一个画布上下文来执行相对简单的操作时（例如合并图像）。merge-images 将所有重复性任务抽象为一个简单的函数。图像可以彼此重叠和调换位置。该函数返回一个 Promise，并 resolve 一个 base64 数据类型的 URI。同时支持浏览器和 Node.js。|
|[Cropper.js](https://fengyuanchen.github.io/cropperjs/)|该插件是一个简单的 JavaScript 图像裁剪器，允许在可交互的环境中裁剪、旋转和缩放图像。它还允许设置纵横比。|
|[CamanJS](http://camanjs.com/)|这是 JavaScript 的画布操作库。其具有简单易用的接口与先进高效的图像/画布编辑技术。通过新滤镜和插件很容易进行扩展，并且它具有一系列的图像编辑功能，而这种功能还在不断增加。它完全无依赖，并可以同时在 Node.js 和浏览器中使用。你可以选择一组预设滤镜或手动更改属性（例如亮度，对比度，饱和度）以获得所需的结果。|
|[MarvinJ](https://github.com/gabrielarchanjo/marvinj)|MarvinJ 是派生自 Marvin 框架的纯 JavaScript 图像处理框架。MarvinJ 对于许多不同的图像处理应用程序而言，既简单又强大。Marvin 除了提供许多算法来控制颜色和外观，还具有自动检测特征的能力。其图像处理能力是基于图像的基础特征（例如边缘、拐角与形状）来实现的。此插件通过检测与分析对象的角点，从而定位场景中主要对象。基于这些功能，让它可以自动裁剪出对象。|
|[Grade](https://benhowdle89.github.io/grade/)|此 JavaScript 库从图像中的前 2 种主要颜色生成互补的渐变。这样，你就可以从图像中提取出渐变效果，来填充网站上的 div。这是一个易用的插件，可帮助你保持网站视觉上的优美。|
|[glfx.js](http://evanw.github.io/glfx.js/)|glfx.js 是一个提供了广泛功能的强大工具。不同于 Filtrr2 和 CamanJS，它遵守 WebGL 标准。非常赞的一点是，图像处理操作在显卡完成，因此可以实时运行。它主要的缺点是只支持最新版本的浏览器。除了基本的调节功能和炫酷效果外，glfx.js 提供了（模糊和包装功能）的列表。这样可以通过调整不同的参数来创建唯一的结果。|
|[Grafi.js](https://github.com/grafijs/grafi)|正如在它项目主页上所说的，grafi.js 是一个鼓励用户去了解图像处理是如何工作的库。源代码可以在 github 找到，并且它里面的很多注释，可以帮助你理解每个函数到底发生了什么。如果你在寻找一些提供更高级图像操作的库，也许 grafi.js 并不能够满足你的需求，但它可以让你了解图像处理是如何执行然后得到满意效果的。注意，涉及改变图像的方向或大小的操作不是由 grafi.js 提供的|
|[Jimp](https://github.com/oliver-moran/jimp)|像 CamanJS 一样，可以用于 NodeJS 和浏览器中，他不需要使用 HTML 元素（img或者canvas）,但需要从路径或URL读取图像。Jimp 提供了颜色调节和一些效果的函数清单。当然也提供了一些你可能在其他库错过的操作，比如调整尺寸，缩放以及旋转图像。图片也可以手动或自动裁减。在 Node 中使用，Jimp 则是一个非常强大的工具，可以让你在多个文件上执行链接操作，并储存修改的图像。|