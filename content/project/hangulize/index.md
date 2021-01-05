---
title: 한글화 on Web
summary: 숫자 및 영문자 알파벳 읽기 도구
tags:
- Deep Learning
- TTS
- Language Processing
date: "2021-01-05T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: "https://hangulize.z12.web.core.windows.net/"

image:
  caption: 웹페이지 캡쳐
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: ""
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

한국어 음성 합성기를 돌리기 위해서는 많은 기술이 필요하지만, 그 중에서도 가장 처음으로 입력 신호를 맞이하는 부분은 언어처리부. 말은 거창하지만 언어전처리 기능이 필요하다. 특히 합성기 훈련을 할 때 한글 글자로 변환해놓은 DB를 이용하기 때문에 당연히도 필요한 내용. 다만 이것도 복잡하게 하려면 끝도 없이 복잡하고, 쉽게 하려면 한없이 쉽다는 것이 문제라면 문제. 

본 과제는 아주, 간단한 형태의 음성 합성기에서 쓸만한 한글화 프로그램에 관한 것임. 이를 위해서 웹으로 구현하였고, 안되는 부분은 아래에 친절히 명시해놓았음. 그럼에도 안도는 녀석들이 분명히 있을꺼라, 오동작하는 녀석들은 쉽게 리포트할 수 있도록 리포트 기능을 마련하였음. 성동현 연구원과 작업한 두번째 내용이긴한데 그래도 먼저 릴리즈되는 결과물임.

향후에 학습으로 영단어 읽기나 규칙에 의해 영단어 읽기 등을 추가할까 생각중이나, 다른 부분들에 대한 우선순위 때문에 언제쯤 적용할지는 아직 미지수. 

앞으로 페이지에 엔진 version을 표기할 수 있도록 하는 것도 필요하겠다 싶기는 함.

feel free to visit the website

