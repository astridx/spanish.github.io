---
title: Wide tables
author: Tao He
date: 2022-06-26
category: Jekyll
layout: post
---

A wide tables needs to be wrapped into a `div` with class `table-wrapper`
to make sure it displayed as expected on mobile devices. For example,

```markdown
<div class="table-wrapper" markdown="block">

||Ir|Hablar|Comer|Ayudar (a)|Comprar|Hacer|Salir|Llamar (a)|
||:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|Quiero|1|2|3|4|5|6|7|8|
|?Quieres?|9|10|11|12|13|14|15|16|
|Voy a|17|18|19|20|21|22|23|24|
|?Vas a?|25|26|27|28|29|30|31|32|
|Tengo que|33|34|35|36|37|38|39|40|
|?Quieres?|41|42|43|44|45|46|47|48|

</div>
```

Will be rendered as

<div class="table-wrapper" markdown="block">

|title1|title2|title3|title4|title5|title6|title7|title8|
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|
|1|2|3|4|5|6|7|8|

</div>
