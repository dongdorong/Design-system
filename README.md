# Design system archive
- Design system 작업에 앞서 리서치한 부분들을 아카이브하는 공간입니다.

## :eight_spoked_asterisk: Design system?
- Product design 작업 시 일관된 design style을 전달하고 작업 시간을 줄이는 효율성을 주기 위해 Design system을 설계합니다.
- Design token을 사용하여 UI를 Component화 하여 관리합니다.
- Product가 커질수록 관리를 수월하게 할 수 있습니다.

## :open_file_folder: Design system research
- <a href="https://www.lightningdesignsystem.com/design-tokens/#category-color" target="_blank">Design Tokens</a>
- <a href="https://bi.spoqa.com/" target="_blank">스포카 Design Guideline</a>
- <a href="https://www.ibm.com/design/" target="_blank">IBM Design</a>
- <a href="https://carbondesignsystem.com/" target="_blank">Carbon design system</a>
- <a href="https://blog.toss.im/article/toss-designer-interview" target="_blank">TDS(toss design system)</a>
- <a href="https://brunch.co.kr/@creative/105" target="_blank">티몬 UI kit</a>
- <a href="https://programmers.co.kr/design/components" target="_blank">프로그래머스 design system</a>
- <a href="https://ui.class101.dev/" target="_blank">Class 101 UI Code</a>
- <a href="https://atlassian.design/" target="_blank">Atlassian Design system</a>
- <a href="https://designsystemsrepo.com/design-systems/" target="_blank">디자인 시스템 갤러리</a>
- <a href="https://www.duetds.com/" target="_blank">duetds Design system</a>
- <a href="https://socarframe.socar.kr/8bb3aba4a/p/480a5e-introduction" target="_blank">Socar Design system</a>
- <a href="https://polaris.shopify.com/" target="_blank">Shopify Design system</a>
- <a href="https://design.gitlab.com/" target="_blank">Gitlab Design system</a>

## :diamond_shape_with_a_dot_inside: Design system architecture

- Design Tokens
  - Color
  - Border radius 
  - Border width
  - Opacity
  - Box shadow
  - Spacing
  - Typography
    - Font family
    - Font weight
    - Line height
    - Font size
    - Letter spacing
    - Paragraph spacing
    - Text decoration
- Brand
  - Logo
- Icon
- Graphic Source
- Design Component
  - Grid
  - buttons
    - Default (outline)
    - Primary
    - Danger
    - Alert
    - Warning
    - Link
    - button group
    - button Block
    - button size
      - Large
      - Normal
      - Medium
      - Small
      - Extra small
  - Dropdown
  - Alerts
  - Forms
  - Table
  - Modal
  - Badge
  - Pagination
  - Collapse
  - List group
  - Tooltip
  - Card
  - Tab
  - Progress bar
  - Loading (Spinner) 
  - Swiper
  - Tag
  - Bottom Sheet
  - Dim

## :lips: Naming
- <a href="https://www.duetds.com/naming/" target="_blank">duetds naming 참고</a>
- <a href="https://www.figma.com/community/file/1108679668074690379" target="_blank">UI Kit 네이밍 참고</a>

```
[Root component name] = Button
[Type] = Primary, Outline primary, Outline gray, Ghost
[Size] = xs, sm, md, lg
[Extra parameters] = “{:Icon=None, Left, Right, Only}, {:Destructive=True/False}”
[State] = Default, Hover, Focus, Disabled
[Example] = Button/Primary/md/left/Hover
```

```
[Root component name] = Badge
[Type] = Primary, Error, Info, Success, Warning, Gray
[Size] =  xs, sm, md
[Extra parameters] = “{Theme=light,dark}, {Outline=True,False}”
[State] = N/A
[Example] = Badge/Success/sm/Light/False
```

## :speech_balloon: 디자인 시스템 관리 방법
<a href="https://www.slideshare.net/NaverEngineering/ss-238530809">마이리얼트립 디자인 리드 발표 자료 P17</a>
- 업데이트된 디자인 시스템 건에 대해서는 팀에게 노티하기
