# AA Catalog

## hugo project를 시작합니다. 

```bash
hugo new site docs
git init

```

## hugo-book 테마를 hugo 프로젝트 themes 폴더에 추가합니다.

```bash
cd HUGO_SITE_DIR/themes
git submodule add https://github.com/alex-shpak/hugo-book.git
git commit -m "submodule add hugo-book-theme"
git submodule update --init --recursive
```
### hugo 테마를 지정합니다. 
- `config.toml` 파일에서 테마를 지정합니다.
`theme = 'hugo-book'`

```bash
hugo server
```

- hugo 프로젝트 최상위 폴더로 돌아와서 오류없이 잘 뜨는지 확인합니다. 
- .gitignore 파일에 node_modules / resources / public 폴더를 추가합니다. 
- netlify.toml 파일에서 build version을 확인합니다.


## 국문 수정위치 
`content`

## 영문 수정위치
`content.en`

## Comments
- 국영문 content 구조가 잘 잡혀 있어서 배울점이 있음. 
- 뎁스가 깊은 aside에 대해서도 참조할 수 있음. md file 중심으로 사용하므로 shortcode 기준도 잘 잡혀 있음. 