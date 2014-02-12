# layout

---

布局

---

## 演示

<link type="text/css" rel="stylesheet" media="screen" href="src/base.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/button.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/form.css">
<link type="text/css" rel="stylesheet" media="screen" href="src/layout.css">
<style type="text/css">
.demo {
    padding: 1rem;
    color: #fff;
    background-color: #6C97C2;
    height: 100%;
}
.ali-flexbox-vertical .ali-flexbox-item{
    margin: 2px 0;
    background: #6C97C2;
}
</style>

### grid
````html
<div class="ali-grid">
    <div class="ali-grid-item one-third"><div class="demo">A</div></div>
    <div class="ali-grid-item tow-thirds"><div class="demo">B</div></div>
</div>
<div class="ali-grid">
    <div class="ali-grid-item one-quarter"><div class="demo">A</div></div>
    <div class="ali-grid-item third-quarters"><div class="demo">B</div></div>
</div>
````

### flexbox
````html
<div class="ali-flexbox">
    <div class="ali-flexbox-item"><div class="demo">A</div></div>
    <div class="ali-flexbox-item"><div class="demo">B</div></div>
    <div class="ali-flexbox-item"><div class="demo">C</div></div>
    <div class="ali-flexbox-item"><div class="demo">D</div></div>
</div>
<div class="ali-flexbox">
    <div class="ali-flexbox-item"><div class="demo">A</div></div>
    <div class="ali-flexbox-item ali-flex2"><div class="demo">B</div></div>
    <div class="ali-flexbox-item ali-flex3"><div class="demo">C</div></div>
    <div class="ali-flexbox-item ali-flex4"><div class="demo">D</div></div>
    <div class="ali-flexbox-item ali-flex5"><div class="demo">B</div></div>
    <div class="ali-flexbox-item ali-flex6"><div class="demo">C</div></div>
    <div class="ali-flexbox-item ali-flex7"><div class="demo">D</div></div>
</div>
````

### flexbox(Vertical)
````html
<div class="ali-flexbox-vertical" style="height: 200px;">
    <div class="ali-flexbox-item ali-flex2"><div class="demo">A</div></div>
    <div class="ali-flexbox-item ali-flex5"><div class="demo">B</div></div>
    <div class="ali-flexbox-item ali-flex2"><div class="demo">C</div></div>
</div>
````
