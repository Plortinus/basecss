## 常用CSS记录

```css
//垂直居中
.v-center {
  position: absolute;
  top: 50%;
  -webkit-transform: translate(0,-50%);
  transform: translate(0, -50%);
}
//水平居中
.h-center {
  position: absolute;
  left: 50%;
  transform: translate(-50%, 0);
}
//全居中
.a-center {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}
```