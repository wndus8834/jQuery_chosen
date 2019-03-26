## jQuery_chosen

select에 항목이 많은 경우에 검색이 가능도록 하는 jQuery 플러그인이다.


사용 방법

1. select에 class나 id로 chosen-select를 적용한다.
```html
<select class="chosen-select">
```

2. jquery와 chosen 플러그인을 불러온다.
```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.4/jquery.min.js" type="text/javascript"></script>
<script src="chosen.jquery.js" type="text/javascript"></script>
```

3. 선택자로 지정해서 동작을 하게 한다.
```html
$(".chosen-select").chosen({no_results_text: "Oops, nothing found!"});
```

![ezgif-2-02bb5052299e](https://user-images.githubusercontent.com/38427658/55020824-02190f00-503b-11e9-810e-d8df733595aa.gif)


[참고 자료](https://github.com/harvesthq/chosen/releases)