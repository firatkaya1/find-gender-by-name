# find-gender-by-name
A simple npm library that help to find gender by turkish names

# Nedir ? 

Bu basit kütüphane, verilen türkçe ismin cinsiyetini bulması için oluşturulmuştur. Çalışma mantığı temel olarak, 2715 elemanlı türkçe isimlerin bulunduğu bir listeden cinsiyetlere göre eşleştirilip, aranan isme göre cinsiyeti getirmesidir. 

# Nasıl kullanılır ? 

Kütüphaneyi mevcut projenize indirmek için npm'den faydalanın.

```sh
npm install find-gender-by-name --save
```

İndirdikten sonra kullanmak istediğiniz alan da tanımlayın ve kullanın. 

```javascript
import { findGenderByName } from 'find-gender-by-name';

console.log(findGenderByName("FIRAT"));

```

Ekrana bastırılan çıktı basitce bir obje döndürmektedir. Bu obje, verdiğiniz ismi ve cinsiyeti gösterir. 

```
{name:"FIRAT",gender:"M"}
```


```sh
+-------------+---------+
| gender      |represent| 
+-------------+---------+
| Male        | M       | 
| Female      | F       | 
+-------------+---------+
```

## Browser Uyumlulukları

Gerekli minimum versiyonlar aşağıda listelenmiştir.

```sh
+--------------+----------+
| Browser      | Versiyon | 
+--------------+----------+
| Google Chrome| 45       | 
| Edge         | 12       | 
| Firefox      | 25       | 
| IE           | X        | 
| Opera        | 32       | 
| Safari       | 8        | 
| Nodejs       | 4.0.0    | 
| Edge         | 12       | 
+--------------+----------+
```

## Version

Bu kütüphanenin mevcut versiyonu 1.0.2'dir.

## License

MIT

Bir sorun ile karşılaşırsanız bana yazabilirsiniz.

[me@kayafirat.com](mailto:me@kayafirat.com?subject=[GitHub]%20find-gender-by-name)
