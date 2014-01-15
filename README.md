# layout

---

// 布局

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
  <div class="ali-field ali-flexbox-item">
    <div class="ali-field-input">
      <input type="text" maxlength="4" placeholder="短信验证码">
    </div>
  </div>
  <div class="ali-field ali-flexbox-item">
    <div class="ali-field-input">
      <input type="text" maxlength="4" placeholder="短信验证码">
    </div>
  </div>
  <div class="ali-field ali-flexbox-item">
    <div class="ali-field-input">
      <input type="text" maxlength="4" placeholder="短信验证码">
    </div>
  </div>
</div>
<div class="ali-flexbox">
  <div class="ali-flexbox-item">
    <button type="button" disabled="disabled" class="ali-button ali-button-disabled">重获验证码</button>
  </div>
  <div class="ali-flexbox-item">
    <button type="button" disabled="disabled" class="ali-button ali-button-disabled">重获验证码</button>
  </div>
</div>
````
