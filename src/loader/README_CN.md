# Loader Usage

```typesctript
  import { LOADER_DIRECTIVES } from 'angularx-semantic-ui/compangularx-semantic-uionents'
```
```html
  <div (click)="toggleLoader()">
    <lsu-loader [active]="active" [loaderText]="loaderText" [loaderSize]="loaderSize"></lsu-loader>
  </div>
```

# Options
- active: 可选，控制Loader显隐
- loaderText: 可选，提示文字
- loaderSize: 可选，Loader尺寸[mini | small | medium | large]

# Methods
- show: 显示 loader 
- hide: 隐藏 loader
