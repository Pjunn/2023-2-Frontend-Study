2장에서 Node.js를 설치하려 할때 brew를 이용해서 다운로드 하려고 했다. 검색을 통해 알아보니 nvm이라는 것을 알게 되었다.또한 brew install node로 brew를 통해 바로 node 를 설치하지 않는 것이 좋다는 것을 발견했다.<br>
### NVM(node version manager)
참고 1 : [블로그 링크](https://lynmp.com/ko/article/tb585d114096490055)<br>
참고 2 : [블로그 링크](https://renee.tistory.com/46)<br>
nvm은 Node.js의 버전 관리자, 그리고 같은 시스템 안에서 여러 Node.js를 사용하기 위해 버젼별로 Node.js 환경을 격리시키는 역할로 많이 사용된다고 한다. Python언어 같은 경우 pyenv와 비슷한것이라고 생각된다.<br>
brew install nvm 으로 brew를 통해 nvm을 설치해주었다. 이때 나의 경우에는 zsh shell 을 사용하고 있기 때문에 .zshrc 파일에 nvm 환경변수 설정을 해주었다. 그리고 nvm install --lts 명령어로 lts 버전의 node.js를 설치해주었다.<br>

