# Sonstiges

## border-radius

Mit border-radius kann man die Ecken eines Elements abrunden.

[Live-Beispiele](https://codepen.io/matuzo/pen/yYabeK?editors=110)

### Ein Wert für alle Seiten

```
div {
  border-radius: 20px;
}
```

### Zwei Werte

top-left und bottom-right / top-right und bottom-left

```
div {
  border-radius: 20px 10px;
}
```

### Drei Werte

top-left / top-right und bottom-left / bottom-right

```
div {
  border-radius: 20px 40px 10px;
}
```

### Vier Werte

top-left / top-right / bottom-right / bottom-left

```
div {
  border-radius: 20px 40px 10px 5px;
}
```

### Jede Seite einzeln

```
div {
  border-top-left-radius: 20px;
  border-top-right-radius: 40px;
  border-bottom-right-radius: 10px;
  border-bottom-left-radius: 5px;
}
```

### Unterschiedliche Radien horizontal und vertikal

```
div {
  border-radius: 20px/50px;
}
```

```
div {
  border-radius: 20px 30px 10px 8px/ 90px 5px 50px 20px;
}
```

### Kreise und Ellipsen

Man kann auch Prozentwerte angeben. Das ist speziell sehr brauchbar, wenn man Kreise und Ellipsen erzeugen will.

```
div {
  border-radius: 50%;
}
```
