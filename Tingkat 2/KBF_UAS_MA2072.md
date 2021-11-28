# Tips!
008

## Persamaan Parametrik
```
<x-x0, y-y0, z-z0> = <a, b, c>t
```
```
C : r(t) = <x0, y0, z0> + <a, b, c>t
```

### Keterangan
```
<x, y, z>   : titik sembarang pada garis
<x0, y0, z0>: titik yang dilalui
<a, b, c>   : vektor arah
```

### Ps:
1. Jika ada 2 titik, dicari dulu vektor arahnya.
    ex: titik A dan titik B, maka (A-B) atau (B-A).
2. Tinjau titik awal, titik ujung, dan arah kurva melalui tes uji (tabel uji, ada di ppt Bu Dewi).

## Persamaan Garis Singgung Kurva
```
S(t0) = r(t0) + r'(t0).t
```

### Keterangan
```
f  = r(t)   = xi + yj + zk
f' = r'(t)  = ∂(r(t))/∂x + ∂(r(t))/∂y + ∂(r(t))/∂z
```

### Ps:
1. Persamaan garis singgung = d/dt (r(t)).
2. Persamaan kartesius : persamaan yang tidak ada parameterisasi. Caranya, hilangkan parameter (biasanya t).

## Vektor Gradien
```
∇f(x, y) = ∂(r(t))/∂x + ∂(r(t))/∂y

```

## Hubungan Vektor Gradien dan Vektor Singgung
```
∇f(x, y) (dot) r'(t) = 0
```

### Keterangan
```
(dot) = perkalian dot product
```

### Ps:
1. Vektor gradien   : vektor yang menyinggung suatu bangun.
2. Vektor singgung  : vektor yang menyinggung suatu bidang.
3. Vektor gradien **tegak lurus** dengan vektor singgung, sehingga dapat diselesaikan dengan teorema dot product.
4. Hasilnya skalar.

## Turunan Berarah
```
∂f/∂û = ∇f(x, y) (dot) û
```

### Keterangan
```
û   : vektor satuan di u
```

### Ps:
1. Hasilnya skalar.

## Turunan Berarah
```
∂T/∂t = ∇f(x, y) (dot) û
```