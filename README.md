# step

---

通用步骤条，有标准和迷你两套样式。支持二到五步。

> 步骤下面的文字最多写 6 个字，如果超出，请重置 ui-step 的 `overflow` 属性。

---

## 演示

`````html
<link type="text/css" rel="stylesheet" media="screen" href="./index.css">

<style>
.ui-step, .ui-ministep {
    margin: 30px 0;
}
</style>
`````

### 标准步骤条

````html
<ol class="ui-step ui-step-3">
    <li class="ui-step-start ui-step-done">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">1</i>
            <span class="ui-step-text">第一步</span>
        </div>
    </li>
    <li class="ui-step-active">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">2</i>
            <span class="ui-step-text">第二步</span>
        </div>
    </li>
    <li class="ui-step-end">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="iconfont ui-step-number">&#xF029;</i>
            <span class="ui-step-text">第三步第三步</span>
        </div>
    </li>
</ol>
````

### 四步

````html
<ol class="ui-step ui-step-4">
    <li class="ui-step-start ui-step-active">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">1</i>
            <span class="ui-step-text">第一步</span>
        </div>
    </li>
    <li class="">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">2</i>
            <span class="ui-step-text">第二步</span>
        </div>
    </li>
    <li class="">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">3</i>
            <span class="ui-step-text">第三步</span>
        </div>
    </li>
    <li class="ui-step-end">
        <div class="ui-step-line">-</div>    
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="iconfont ui-step-number">&#xF029;</i>
            <span class="ui-step-text">第四步</span>
        </div>
    </li>
</ol>
````

### 五步

````html
<ol class="ui-step ui-step-5">
    <li class="ui-step-start ui-step-done">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">1</i>
            <span class="ui-step-text">第一步</span>
        </div>
    </li>
    <li class="ui-step-done">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">2</i>
            <span class="ui-step-text">第二步</span>
        </div>
    </li>
    <li class="ui-step-done">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">3</i>
            <span class="ui-step-text">第三步</span>
        </div>
    </li>
    <li class="ui-step-active">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">4</i>
            <span class="ui-step-text">第四步</span>
        </div>
    </li>
    <li class="ui-step-end">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="iconfont ui-step-number">&#xF029;</i>
            <span class="ui-step-text">第五步</span>
        </div>
    </li>
</ol>
````

### 二步

````html
<ol class="ui-step ui-step-2">
    <li class="ui-step-start ui-step-active">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">1</i>
            <span class="ui-step-text">第一步</span>
        </div>
    </li>
    <li class="ui-step-end">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="iconfont ui-step-number">&#xF029;</i>
            <span class="ui-step-text">第二步</span>
        </div>
    </li>
</ol>
````

### 蓝色步骤条

````html
<ol class="ui-step ui-step-blue ui-step-3">
    <li class="ui-step-start ui-step-done">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">1</i>
            <span class="ui-step-text">第一步</span>
        </div>
    </li>
    <li class="ui-step-active">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="ui-step-number">2</i>
            <span class="ui-step-text">第二步</span>
        </div>
    </li>
    <li class="ui-step-end">
        <div class="ui-step-line">-</div>
        <div class="ui-step-icon">
            <i class="iconfont">&#xf02f;</i>
            <i class="iconfont ui-step-number">&#xF029;</i>
            <span class="ui-step-text">第三步第三步</span>
        </div>
    </li>
</ol>
````

### 迷你步骤条

````html
<ol class="ui-ministep">
    <li class="ui-ministep-item">
        <i class="iconfont">&#xf02f;</i>
        <i class="ui-ministep-number">1</i>
        <span class="ui-ministep-text">第一步</span>
    </li>
    <li class="ui-ministep-item ui-ministep-active">
        <i class="iconfont">&#xf02f;</i>
        <i class="ui-ministep-number">2</i>
        <span class="ui-ministep-text">第二步</span>
    </li>
    <li class="ui-ministep-item">
        <i class="iconfont">&#xf02f;</i>
        <i class="ui-ministep-number">3</i>
        <span class="ui-ministep-text">第三步</span>
    </li>
</ol>
````
