# 使用说明

启用flex布局

### 默认为子元素平均分配空间  
    <div class="flex-left">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
### 按需分配空间
     <div class="flex-left">
        <div class="unit-1-2"></div>
        <div class="unit-1-4"></div>
        <div class="unit-1-4"></div>
    </div>
### 子元素不足一的留下空白空间
    <div class="flex-left">
        <div class="unit-1-4"></div>
        <div class="unit-1-4"></div>
        <div class="unit-1-4"></div>
    </div>

## 定位
### 根据语意即可实现
    <div class="flex-left"><div>居左</div><div>
    <div class="flex-right"><div>居右</div><div>
    <div class="flex-top"><div>居上</div><div>
    <div class="flex-bottom"><div>居下</div><div>
    <div class="flex-center"><div>水平居中</div><div>
    <div class="flex-middle"><div>竖直居中</div><div>
    <div class="flex-right flex-middle"><div>竖直水平居中</div><div>

##垂直的FLEX布局

    <div class="flex-vertical"style="heigth:300px">
        <div></div>
        <div></div>
    <div>

#### tip:
* 启用换行 

`<div class= "flex-left flex-warp"><div>`
