### 基本写法
```bash
@import url(variables.less);

.@{prefix}btn {
    display: inline-block;
    line-height: 1;
    white-space: nowrap;
    -webkit-appearance: none;
    text-align: center;
    box-sizing: border-box;
    transition: .1s;
    font-weight: 500;
    -moz-user-select: none;
    -webkit-user-select: none;
    -ms-user-select: none;
    color: @base-color;
    border-radius: @border-radius;
    outline: none;
    border: 1px solid @base-border-color;
    padding: 12px 20px;
    font-size: 14px;
    cursor: @cursor;
    // 状态切换
    &@{primary}{
        .color-hover(@@primary)
    }
    &@{success}{
        .color-hover(@@success)
    }
    &@{warning}{
        .color-hover(@@warning)
    }
    &@{danger}{
        .color-hover(@@danger)
    }
    &@{info}{
        .color-hover(@@info)
    }
}
```