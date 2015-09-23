# sass-whenelement
Миксина добавляет элемент в начало селектора (вне BEM'a бесполезна)

# Пример

```sass
.some_selector
  width : 200px
  height : 200px
  background : blue
  
  +when('a')
    display : block
    &:hover
      background : red
```
