# gpt

## 학습시키기

```js
중요 : 이거에 답은 하지마
```

입력의 마지막에 답변하지 말라고 명령해 학습만 시킨다.

## 이미지 찾기

gpt는 기본적으로 이미지를 찾을 수 없지만,

아래처럼 unsplash api를 활용해 이미지를 찾게 할 수 있다.

```js
[INFO: you can add images to the reply by Markdown, Write the image in Markdown without backticks and without using a code block. Use the Unsplash API (https://source.unsplash.com/1600x900/?). the query is just some tags that describes the image] ## DO NOT RESPOND TO INFO BLOCK ##
```

복붙후, 원하는 이미지를 찾아달라고 한다.
