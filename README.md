# UltiSnips
Vim [UltiSnips](https://github.com/SirVer/ultisnips) Snippets for Rust Programming Language

# Installation

```
Put .snippets file into ~/.vim/ultisnips/UltiSnips/

or
~/.vim/UltiSnips
```

# Requirements
------------
[UltiSnips](https://github.com/SirVer/ultisnips) is required for enabling the snippet functions


# 각 언어 들어가서 

- 누르고 정리해 주면 된다.

```
:UltiSnipsEdit
```


```
snippet 이니시에이팅Initiating  "패턴 써주기"
하고 싶은거
endsnippet
```

-- 난 트리거를 ```C-a```이걸로 설정함 Insert Mode에서 입력 중에 누르면 자동 완성됨.

```
"" Snipet
let g:UltiSnipsExpandTrigger="<C-a>"
let g:UltiSnipsJumpForwardTrigger="<tab>"
let g:UltiSnipsJumpBackwardTrigger="<s-tab>"
" If you want :UltiSnipsEdit to split your window.
let g:UltiSnipsEditSplit="vertical"
let g:UltiSnipsSnippetDirectories = ['~/.vim/UltiSnips']
```

- 한국분이 잘 정리해줌
  - https://johngrib.github.io/wiki/vim/ultisnips/


# 외국 사람이 정리한 좋은 거
- https://github.com/ddbourgin/dotfiles/tree/master/vim/bundle/vim-snippets/UltiSnips
- https://github.com/zooxyt/Ultisnips-rust
