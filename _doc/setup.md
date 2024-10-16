## 기본 설정(next.js, shadcn)

```sh
# create next project 설치 옵션 지정
cd C:\JnJ-soft\Projects\internal
npx create-next-app@latest next-youtube-tool --typescript --eslint --tailwind --app --src-dir --import-alias "@/*" --use-npm

# shadcn-ui 설치 https://ui.shadcn.com/docs/cli
cd next-youtube-tool
npx shadcn@latest init -d -y
```

## github

```sh
cd C:\JnJ-soft\Projects\internal\next-youtube-tool
github -e pushRepo -u jnjsoftweb -n next-youtube-tool -d "Youtube tool by NEXT.JS"
```

### .vscode, prettierrc, _doc 복사

```
C:\JnJ-soft\Projects\internal\_next_template\_doc
C:\JnJ-soft\Projects\internal\_next_template\.vscode
C:\JnJ-soft\Projects\internal\_next_template\.prettierrc
```
