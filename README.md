# Memoir 매뉴얼 한글 번역 프로젝트

## 조판 방법
[여기](http://wiki.ktug.org/wiki/wiki.php/KtugPrivateRepository?action=show&redirect=private)를 참고하여 `ktug` 저장소를 추가한 후,
```
tlmgr install arara-rules-ko
```
를 실행한다.
이후
```
arara -v memman-ko.tex
```
를 실행하여 조판하면 된다.

Mac 의 경우 gentium Fonts 관련하여 문제가 생길 수 있는데,
```bash
cd /Library/Fonts
ln -s /usr/local/texlive/2019/texmf-dist/fonts/truetype/public/gentium-tug/Gen .
```
하면 된다.
