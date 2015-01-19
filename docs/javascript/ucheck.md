# uCheck
---

`radio`、`checkbox` 样式重写。

选框图标使用 Icon Font，如果你的浏览器不支持 Icon Font（**一些国内的产商就是有把正常的功能搞残的本事**），请谨慎使用。

## 使用演示

### 默认样式

`````html
<style>
  .am-ucheck-icons [class*="am-icon"] + [class*="am-icon"] {
    margin-left: 0;
  }
</style>

<div class="am-g">
  <div class="am-u-sm-6">
    <h3>复选框</h3>
    <label class="am-checkbox">
      <input type="checkbox" value="" data-am-ucheck> 没有选中
    </label>
    <label class="am-checkbox">
      <input type="checkbox" checked="checked" value="" data-am-ucheck checked>
      已选中
    </label>
    <label class="am-checkbox">
      <input type="checkbox" value="" data-am-ucheck disabled>
      禁用/未选中
    </label>
    <label class="am-checkbox">
      <input type="checkbox" checked="checked" value="" data-am-ucheck disabled
             checked>
      禁用/已选中
    </label>
  </div>

  <div class="am-u-sm-6">
    <h3>单选框</h3>
    <label class="am-radio">
      <input type="radio" name="radio1" value="" data-am-ucheck>
      未选中
    </label>
    <label class="am-radio">
      <input type="radio" name="radio1" value="" data-am-ucheck checked>
      已选中
    </label>

    <label class="am-radio">
      <input type="radio" name="radio2" value="" data-am-ucheck disabled>
      禁用/未选中
    </label>
    <label class="am-radio">
      <input type="radio" name="radio2" value="" data-am-ucheck checked
             disabled>
      禁用/已选中
    </label>
  </div>
</div>
`````
```html
<div class="am-g">
  <div class="am-u-sm-6">
    <h3>复选框</h3>
    <label class="am-checkbox">
      <input type="checkbox" value="" data-am-ucheck> 没有选中
    </label>
    <label class="am-checkbox">
      <input type="checkbox" checked="checked" value="" data-am-ucheck checked>
      已选中
    </label>
    <label class="am-checkbox">
      <input type="checkbox" value="" data-am-ucheck disabled>
      禁用/未选中
    </label>
    <label class="am-checkbox">
      <input type="checkbox" checked="checked" value="" data-am-ucheck disabled
             checked>
      禁用/已选中
    </label>
  </div>

  <div class="am-u-sm-6">
    <h3>单选框</h3>
    <label class="am-radio">
      <input type="radio" name="radio1" value="" data-am-ucheck>
      未选中
    </label>
    <label class="am-radio">
      <input type="radio" name="radio1" value="" data-am-ucheck checked>
      已选中
    </label>

    <label class="am-radio">
      <input type="radio" name="radio2" value="" data-am-ucheck disabled>
      禁用/未选中
    </label>
    <label class="am-radio">
      <input type="radio" name="radio2" value="" data-am-ucheck checked
             disabled>
      禁用/已选中
    </label>
  </div>
</div>
```

### 颜色变化

默认使用主色，如果需要调整颜色在 `.am-checkbox`/`.am-checkbox` 上添加颜色 class。

- `.am-secondary`
- `.am-success`
- `.am-warning`
- `.am-danger`

`````html
<div class="am-g">
  <div class="am-u-sm-6 am-u-md-3">
    <h3>复选框</h3>
    <label class="am-checkbox am-secondary">
      <input type="checkbox" value="" data-am-ucheck> 没有选中
    </label>
    <label class="am-checkbox am-secondary">
      <input type="checkbox" checked="checked" value="" data-am-ucheck checked>
      已选中
    </label>
  </div>

  <div class="am-u-sm-6 am-u-md-3">
    <h3>单选框</h3>
    <label class="am-radio am-secondary">
      <input type="radio" name="radio3" value="" data-am-ucheck> 未选中
    </label>
    <label class="am-radio am-secondary">
      <input type="radio" name="radio3" value="" data-am-ucheck checked> 已选中
    </label>
  </div>

  <div class="am-u-sm-6 am-u-md-3">
    <h3>复选框</h3>
    <label class="am-checkbox am-success">
      <input type="checkbox" value="" data-am-ucheck> 没有选中
    </label>
    <label class="am-checkbox am-success">
      <input type="checkbox" checked="checked" value="" data-am-ucheck checked>
      已选中
    </label>
  </div>

  <div class="am-u-sm-6 am-u-md-3">
    <h3>单选框</h3>
    <label class="am-radio am-success">
      <input type="radio" name="radio7" value="" data-am-ucheck> 未选中
    </label>
    <label class="am-radio am-success">
      <input type="radio" name="radio7" value="" data-am-ucheck checked> 已选中
    </label>
  </div>

  <div class="am-u-sm-6 am-u-md-3">
    <h3>复选框</h3>
    <label class="am-checkbox am-warning">
      <input type="checkbox" value="" data-am-ucheck> 没有选中
    </label>
    <label class="am-checkbox am-warning">
      <input type="checkbox" checked="checked" value="" data-am-ucheck checked>
      已选中
    </label>
  </div>

  <div class="am-u-sm-6 am-u-md-3">
    <h3>单选框</h3>
    <label class="am-radio am-warning">
      <input type="radio" name="radio4" value="" data-am-ucheck> 未选中
    </label>
    <label class="am-radio am-warning">
      <input type="radio" name="radio4" value="" data-am-ucheck checked> 已选中
    </label>
  </div>

  <!-- red -->
  <div class="am-u-sm-6 am-u-md-3">
    <h3>复选框</h3>
    <label class="am-checkbox am-danger">
      <input type="checkbox" value="" data-am-ucheck> 没有选中
    </label>
    <label class="am-checkbox am-danger">
      <input type="checkbox" checked="checked" value="" data-am-ucheck checked>
      已选中
    </label>
  </div>

  <div class="am-u-sm-6 am-u-md-3">
    <h3>单选框</h3>
    <label class="am-radio am-danger">
      <input type="radio" name="radio5" value="" data-am-ucheck> 未选中
    </label>
    <label class="am-radio am-danger">
      <input type="radio" name="radio5" value="" data-am-ucheck checked> 已选中
    </label>
  </div>
</div>
`````
```html
<label class="am-checkbox am-secondary">
  <input type="checkbox" value="" data-am-ucheck> 没有选中
</label>
<label class="am-checkbox am-secondary">
  <input type="checkbox" checked="checked" value="" data-am-ucheck checked>
  已选中
</label>

<label class="am-radio am-secondary">
  <input type="radio" name="radio3" value="" data-am-ucheck> 未选中
</label>
<label class="am-radio am-secondary">
  <input type="radio" name="radio3" value="" data-am-ucheck checked> 已选中
</label>
```

<!--### Input Group 中使用

`````html
<div class="am-g">
  <div class="am-u-md-6">
    <div class="am-input-group">
      <span class="am-input-group-label">
        <label class="am-checkbox">
          <input type="checkbox" data-am-ucheck>
        </label>
      </span>
      <input type="text" class="am-form-field">
    </div>
  </div>
  <div class="am-u-md-6">
    <div class="am-input-group">
      <span class="am-input-group-label">
        <label class="am-radio">
          <input type="radio" data-am-ucheck>
        </label>
      </span>
      <input type="text" class="am-form-field">
    </div>
  </div>
</div>
`````

### Inline Form

<form class="am-form-inline">
  <div class="am-form-group">
    <input type="email" class="am-form-field" placeholder="电子邮件">
  </div>

  <div class="am-form-group">
    <input type="password" class="am-form-field" placeholder="密码">
  </div>

  <label class="am-checkbox">
    <input type="checkbox"  value="" data-am-ucheck> 记住我
  </label>
</form>
-->

### 结合表单验证插件

`````html
<form class="am-form" data-am-validator>
  <div class="am-form-group">
    <h3>装备<sup class="am-text-danger">*</sup> （至少 2 项，至多 4 项）</h3>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="ip" data-am-ucheck required minchecked="2" maxchecked="4"> iPhone
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="im" data-am-ucheck> iMac
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="mbp" data-am-ucheck> Macbook Pro
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="sf" data-am-ucheck> 苏菲·麻索
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="sur" data-am-ucheck> Surface
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="rb" data-am-ucheck> Razer Blade
    </label>
  </div>

  <div class="am-form-group">
    <h3>性别 <sup class="am-text-danger">*</sup></h3>
    <label class="am-radio">
      <input type="radio" name="radio10" value="male" data-am-ucheck required> 男
    </label>
    <label class="am-radio">
      <input type="radio" name="radio10" value="female" data-am-ucheck> 女
    </label>
    <label class="am-radio">
      <input type="radio" name="radio10" value="pig" data-am-ucheck> 人妖
    </label>
    <div>
      <div><button type="submit" class="am-btn am-btn-primary">提交</button></div>
</form>
`````
```html
<form class="am-form" data-am-validator>
  <div class="am-form-group">
    <h3>装备<sup class="am-text-danger">*</sup> （至少 2 项，至多 4 项）</h3>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="ip" data-am-ucheck required minchecked="2" maxchecked="4"> iPhone
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="im" data-am-ucheck> iMac
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="mbp" data-am-ucheck> Macbook Pro
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="sf" data-am-ucheck> 苏菲·麻索
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="sur" data-am-ucheck> Surface
    </label>
    <label class="am-checkbox">
      <input type="checkbox" name="cbx" value="rb" data-am-ucheck> Razer Blade
    </label>
  </div>

  <div class="am-form-group">
    <h3>性别 <sup class="am-text-danger">*</sup></h3>
    <label class="am-radio">
      <input type="radio" name="radio10" value="male" data-am-ucheck required> 男
    </label>
    <label class="am-radio">
      <input type="radio" name="radio10" value="female" data-am-ucheck> 女
    </label>
    <label class="am-radio">
      <input type="radio" name="radio10" value="pig" data-am-ucheck> 人妖
    </label>
    <div>
      <div><button type="submit" class="am-btn am-btn-primary">提交</button></div>
</form>
```

## 使用方式

### 通过 Data API

在 `radio`/`checkbox` 上添加 `data-am-ucheck` 属性。

```html
<label class="am-checkbox">
  <input type="checkbox" value="" data-am-ucheck> 没有选中
</label>

<label class="am-radio">
  <input type="radio" value="" data-am-ucheck> 没有选中
</label>
```

### 通过 JS

```javascript
$(function() {
  $('input[type='checkbox'], input[type='radio']').uCheck();
});
```

#### 方法

- `$().uCheck('check')`: 选中
- `$().uCheck('uncheck')`: 取消选中
- `$().uCheck('toggle')`: 切换选中状态
- `$().uCheck('disable')`: 禁用
- `$().uCheck('enable')`: 启动

## 参考链接

- [iCheck - Highly customizable checkboxes and radio buttons for jQuery and Zepto](https://github.com/fronteed/iCheck)
