---
title: "How To Wear Bright Shoes"
date: 2018-09-24T11:07:10+06:00
author: Mark Dinn
image : "images/blog/blog-post-3.jpg"
bg_image: "images/featue-bg.jpg"
categories: ["Legacy Support"]
tags: ["Android","Retro"]
plotly: true
description: "this is meta description"
draft: false
type: "post"
---


Lorem ipsum dolor sit amet, consectetur adipisicing elit. Velit vitae placeat ad architecto nostrum asperiores
vel aperiam, veniam eum nulla. Maxime cum magnam, adipisci architecto quibusdam cumque veniam fugiat quae. Lorem
ipsum dolor sit amet, consectetur adipisicing elit. Odio vitae ab doloremque accusamus sit, eos dolorum officiis
a perspiciatis aliquid. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod, facere. 

> Lid est laborum dolo rumes fugats untras. Etharums ser quidem rerum facilis dolores nemis omnis fugats vitaes
nemo minima rerums unsers sadips amets.. Sed ut perspiciatis unde omnis iste natus error

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laborum illo deserunt necessitatibus quibusdam sint,
eos explicabo tenetur molestiae vero facere, aspernatur sit mollitia perferendis reiciendis. Deleniti magni
explicabo sed alias fugit amet animi molestias ipsum maiores. Praesentium sint, id laborum quos. Tempora
inventore est, dolor corporis quis doloremque nostrum, eos velit culpa quasi labore. Provident laborum porro
nihil iste, magnam officia nemo praesentium autem, libero vel officiis. Omnis pariatur nam voluptatem voluptate
at officia repellat ea beatae eligendi? Mollitia error saepe, aperiam facere. Optio maiores deleniti veritatis
eaque commodi atque aperiam, debitis iste alias eligendi ut facilis earum! Impedit, tempore.

```
  .blog-classic {
  margin-bottom: 70px;
  padding-bottom: 70px;
  border-bottom: 1px solid #efefef;
  }
```
{{< load-plotly >}}

{{/*% plot plot2 %*/}}
var trace1 = {
  x: [1, 2, 3, 4],
  y: [10, 15, 13, 17],
  type: 'scatter'
};

var trace2 = {
  x: [1, 2, 3, 4],
  y: [16, 5, 11, 9],
  type: 'scatter'
};

data = [trace1, trace2];
fig = {
  data: data
}
{{/*% /plot %*/}}

{{/* plot figure1 >*/}}
fig = {"data":[{"x":["1024x1024x1","512x512x2","256x256x4","128x128x8","64x64x16","32x32x32","16x16x64","8x8x128","4x4x256","2x2x512","1x1x1024"],"y":[5.319377513,3.730183194,3.492960513,3.416568462,3.406160365,3.404795796,3.401629099,3.403963371,3.406568944,3.403851128,3.401489335],"name":"1 workers"},{"x":["1024x1024x1","512x512x2","256x256x4","128x128x8","64x64x16","32x32x32","16x16x64","8x8x128","4x4x256","2x2x512","1x1x1024"],"y":[5.105426336,2.403512541,1.769243872,1.720678808,1.705878765,1.702246865,1.705907853,1.731687894,1.819791773,1.954560985,3.404077505],"name":"2 workers"},{"x":["1024x1024x1","512x512x2","256x256x4","128x128x8","64x64x16","32x32x32","16x16x64","8x8x128","4x4x256","2x2x512","1x1x1024"],"y":[4.665434148,1.840141806,1.23159353,1.156602142,1.139298289,1.135465838,1.145931396,1.190932724,1.324346159,1.955651422,3.401555276],"name":"3 workers"},{"x":["1024x1024x1","512x512x2","256x256x4","128x128x8","64x64x16","32x32x32","16x16x64","8x8x128","4x4x256","2x2x512","1x1x1024"],"y":[3.277424857,1.508889857,1.000251994,0.877004851,0.855757891,0.851836168,0.859728354,0.902649372,1.012687753,1.955834209,3.404003372],"name":"4 workers"},{"x":["1024x1024x1","512x512x2","256x256x4","128x128x8","64x64x16","32x32x32","16x16x64","8x8x128","4x4x256","2x2x512","1x1x1024"],"y":[2.687810723,1.299930746,0.848919389,0.71687461,0.697146793,0.686797944,0.695021475,0.733307298,0.782258103,1.958691928,3.406197102],"name":"5 workers"},{"x":["1024x1024x1","512x512x2","256x256x4","128x128x8","64x64x16","32x32x32","16x16x64","8x8x128","4x4x256","2x2x512","1x1x1024"],"y":[2.419063112,1.172598442,0.770078822,0.636418239,0.59517132,0.58758251,0.598871324,0.655497364,0.722161112,1.955789037,3.40305645],"name":"6 workers"},{"x":["1024x1024x1","512x512x2","256x256x4","128x128x8","64x64x16","32x32x32","16x16x64","8x8x128","4x4x256","2x2x512","1x1x1024"],"y":[1.991583443,1.033091053,0.712726608,0.605582734,0.578420338,0.577574125,0.580463384,0.652894185,0.691949137,1.970116638,3.452580344],"name":"7 workers"},{"x":["1024x1024x1","512x512x2","256x256x4","128x128x8","64x64x16","32x32x32","16x16x64","8x8x128","4x4x256","2x2x512","1x1x1024"],"y":[1.942149854,0.947873093,0.683032395,0.605635427,0.575207906,0.573205018,0.580969231,0.653116053,0.72285752,1.954330764,3.407772597],"name":"8 workers"}],"layout":{"title":"Benchmark results","yaxis":{"title":"s/op","type":"log","autorange":true},"shapes":[{"type":"line","xref":"paper","yref":"y","y0":3.40394218,"x0":0,"y1":3.40394218,"x1":1,"line":{"width":1}},{"type":"line","xref":"paper","yref":"y","y0":1.70197109,"x0":0,"y1":1.70197109,"x1":1,"line":{"width":1}},{"type":"line","xref":"paper","yref":"y","y0":1.1346473933333334,"x0":0,"y1":1.1346473933333334,"x1":1,"line":{"width":1}},{"type":"line","xref":"paper","yref":"y","y0":0.850985545,"x0":0,"y1":0.850985545,"x1":1,"line":{"width":1}},{"type":"line","xref":"paper","yref":"y","y0":0.680788436,"x0":0,"y1":0.680788436,"x1":1,"line":{"width":1}},{"type":"line","xref":"paper","yref":"y","y0":0.5673236966666667,"x0":0,"y1":0.5673236966666667,"x1":1,"line":{"width":1}}],"margin":{"l":25,"r":5,"b":75,"t":50,"pad":4}},"config":{"responsive":true}}
{{/*< /plot >*/}}

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ex error esse a dolore, architecto sapiente, aliquid
commodi, laudantium eius nemo enim. Enim, fugit voluptatem rem molestiae. Sed totam quis accusantium iste
nesciunt id exercitationem cumque repudiandae voluptas perspiciatis, consequatur quasi, molestias, culpa odio
adipisci. Nesciunt optio fugiat iste quam modi, ex vitae odio pariatur! Corrupti explicabo at harum qui
doloribus, sit dicta nemo, dolor, enim eum molestias fugiat obcaecati autem eligendi? Nisi delectus eaque
architecto voluptatibus, unde sit minus quae quod eligendi soluta recusandae doloribus, officia, veritatis
voluptatum eius aliquam quos. Consectetur, nisi? Veritatis totam, unde nostrum exercitationem tempora suscipit,
molestias, deserunt ipsum laborum aut iste eaque? Vitae delectus dicta maxime non mollitia? Sapiente eos a quia
eligendi deserunt repudiandae modi molestias tenetur autem pariatur ullam itaque, quas eveniet, illo quam rerum
ex obcaecati voluptatum nesciunt incidunt culpa provident illum soluta. Voluptas possimus nesciunt inventore
perspiciatis neque fugiat, magnam natus repellendus praesentium eum voluptatum, alias incidunt, tempora
reprehenderit recusandae et numquam itaque ratione dolor voluptatibus in commodi ut! Neque deserunt nostrum
commodi dolor natus quo, non vitae deleniti, vero voluptatem error aspernatur veniam expedita numquam amet quia
in dolores velit esse molestiae! Iusto architecto accusantium quisquam recusandae quod vero quia.
