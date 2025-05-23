## 4. 반응형 작업

### 4.1. 필수 체크 사항

- 아래 구문이 없으면 화면 체크를 못해서 반응형 곤란

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

- 포토샵 또는 Figma 로 디자인 제공되어짐(PC, 타블렛, 모바일)
- 가능 하면 큰 화면에서 모두 배치하고, 점점 줄여가면서 배치하기를 권장
- 필요하면 작업하면서 계속 @media 를 추가해 갑니다.

```css
/* 최대 크기 */
@media all and (max-width: 1280px) {
}
@media all and (max-width: 1024px) {
}
@media all and (max-width: 960px) {
}
@media all and (max-width: 760px) {
}
@media all and (max-width: 540px) {
}
```
