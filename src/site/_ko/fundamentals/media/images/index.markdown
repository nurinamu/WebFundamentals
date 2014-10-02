---
layout: section
title: "이미지"
description: "설명하는데 천개의 단어보다 사진 한장이 나은 것처럼, 이미지는 모든 페이지의 중요한 역할을 합니다. 하지만 이미지는 종종 다운로드되는 용량의 대부분을 차지합니다. 반응형 웹 디자인을 통해 디바이스의 특성에 따라 우리의 레이아웃을 변경할 수 있을 뿐아니라 이미지 역시 변경할 수 있습니다."
introduction: "설명하는데 천개의 단어보다 사진 한장이 나은 것처럼, 이미지는 모든 페이지의 중요한 역할을 합니다. 하지만 이미지는 종종 다운로드되는 용량의 대부분을 차지합니다. 반응형 웹 디자인을 통해 디바이스의 특성에 따라 우리의 레이아웃을 변경할 수 있을 뿐아니라 이미지 역시 변경할 수 있습니다."
authors:
  - petelepage
translators:
  - nurinamu
article:
  written_on: 2014-04-30
  updated_on: 2014-04-30
  order: 1
collection: introduction-to-media
id: images
---

{% wrap content%}

<style>
  img, video, object {
    max-width: 100%;
  }

  img.center {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }
</style>

<div class="media media--video">
  <iframe src="https://www.youtube.com/embed/vpRsLPI400U?controls=2&modestbranding=1&showinfo=0&utm-source=crdev-wf" frameborder="0" allowfullscreen=""></iframe>
</div>

### 반응형 이미지

반응형 웹디자인은 디바이스 특성에 따른 레이아웃 변경만을 뜻하는 것이 아니고 컨텐츠 변경도 포함합니다.
예를들어 고해상도(2x) 화면에서 높은 선명도를 가지기 위해서는 고해상도의 그래픽을 필요로합니다.
50% 넓이의 이미지는 800px 너비의 브라우저에서 잘 동작할 것 입니다, 하지만 좁은 화면의 폰에서는 너무 넓은 자리를 차지하게될 것이고,
작은 화면으로 축소되었더라도 여전히 동일한 대역폭을 차지하고 있을 것입니다.

### 아트 디렉션

<img class="center" src="img/art-direction.png" alt="Art direction example"
srcset="img/art-direction.png 1x, img/art-direction-2x.png 2x">

어떨때는 이미지를 크게 변경해야할 때가 있습니다: 비율을 변경하고 이미지를 자르고 심지어 이미지 전체를 변경할때가 있습니다.
이런 경우에 변경되는 이미지는 보통 아트 디렉션 같은 것을 참고 합니다. 더 많은 예제를 확인하시려면
[responsiveimages.org/demos/](http://responsiveimages.org/demos/) 를 보십시요.

{% include modules/nextarticle.liquid %}

{% endwrap %}
