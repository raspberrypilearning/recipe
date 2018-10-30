## 색상 추가하기

레시피 페이지에 색상을 추가해 봅시다.

+ 우리는 이미 색상이 입혀진 텍스트를 추가하는 법에 대해 알고 있습니다. 아래 Code를 `style.css` 파일에 추가합니다. 그럼 페이지의 모든 글이 파란색으로 바뀔 것입니다.

    body {
        color: blue;
    }
    

![스크린샷](images/recipe-blue.png)

+ 브라우저는 `blue`, `yellow`, 심지어는 `lightgreen` 등의 색상도 인지합니다. **사실 이외에도 140개의 다른 색상이 지정되어 있다는 사실을 알고 계시나요?**

[jumpto.cc/colours](http://jumpto.cc/colours) 페이지에서 색상명을 알 수 있습니다. 여기서는 `tomato`, `firebrick`, `peachpuff` 등의 색상도 찾을 수 있습니다.

텍스트 색상을 `blue`에서 `tomato`으로 바꾸어 봅시다.

![스크린샷](images/recipe-tomato.png)

+ 브라우저에서 키워드로 지정된 색상은 140개밖에 안되지만, ** RGB 값으로는 1600만개의 다른 색상이 지정되어 있습니다!**

쓰고 싶은 색상이 있는경우 해당 색상의 빨간색, 초록색, 파란색의 값을 브라우저에 알려 주면 됩니다.

빨간색, 초록색, 파란색의 값은 `0`부터 `255`까지 분포해 있습니다.

![스크린샷](images/recipe-rgb-img.png)

아래 Code를 CSS Code에 추가하여, 배경을 옅은 노란색으로 바꾸어 봅시다:

    background: rgb(250,250,210);
    

![스크린샷](images/recipe-rgb.png)

+ 만약 원한다면 RGB 색상 값을 **16진수 색상값으로 변환할 수 있습니다.** 이 방법도 아까 사용했던 `rgb()`와 비슷한데, 다른 점은 `#`으로 시작한다는 점이고, 16진수 숫자를 사용하여 `00`부터 `ff`까지 빨간색, 초록색, 파란색의 값으로 지정할 수 있다라는 점입니다.

![스크린샷](images/recipe-hex-img.png)

아래 Code를 `rgb()` 대신 넣어 봅시다.

    background: #fafad2;
    

![스크린샷](images/recipe-hex.png)

아까와 같이 같은 옅은 노란색을 볼 수 있습니다.