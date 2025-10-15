# mdfile-sample
알겠어요! GitHub 마크다운(md) 파일에서 **영상과 사진**을 활용하는 방법을 샘플과 함께 만들어드릴게요.

---

````markdown
# GitHub 마크다운 예제: 사진과 영상 활용하기

## 1. 이미지 삽입하기

아래는 이미지 삽입 예시입니다.

![깃허브 로고](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

> 위 이미지는 GitHub 공식 로고입니다.

---

## 2. 영상 삽입하기 (YouTube 영상)

마크다운은 직접 영상을 삽입할 수 없지만, 링크 또는 임베드 방식으로 영상을 표시할 수 있습니다.

### 2-1. 영상 링크 삽입

[Git and GitHub Tutorial - YouTube](https://www.youtube.com/watch?v=RGOj5yH7evk)

### 2-2. 임베드 iframe (GitHub에서는 지원 안됨, 웹페이지용)

```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/RGOj5yH7evk" frameborder="0" allowfullscreen></iframe>
````

*참고: GitHub README.md에서는 HTML iframe 태그를 지원하지 않습니다.*

---

## 3. 직접 동영상 파일 첨부 및 재생

GitHub 마크다운에서는 직접 동영상 파일(.mp4 등)을 올리고 재생하는 기능은 제한적입니다. 하지만 저장소에 동영상 파일을 업로드한 뒤 링크를 걸어 접근할 수 있습니다.

예) 저장소 내 `videos/tutorial.mp4` 파일이 있을 때

[영상 보기](./videos/tutorial.mp4)

---

## 4. 요약

* 이미지는 `![대체텍스트](이미지URL)` 형식으로 삽입
* 영상은 YouTube 링크로 연결하거나 HTML iframe으로 임베드(하지만 GitHub에서는 미지원)
* 동영상 파일은 저장소에 올리고 링크로 접근 가능

---

> **참고 링크**
> [GitHub Flavored Markdown 가이드](https://guides.github.com/features/mastering-markdown/)

```

---

이대로 `.md` 파일로 저장해서 GitHub에 올리면, 이미지는 바로 보이고 영상은 링크 클릭으로 확인할 수 있어요.  

필요하면 이걸 기반으로 더 자세한 설명이나 실습용 문서도 만들어 드릴게요!
```
