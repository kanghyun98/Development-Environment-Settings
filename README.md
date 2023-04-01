## IDE

### VSCode

- [VSCode 다운로드](https://code.visualstudio.com/)



### VSCode Extensions

- Prettier
- ESlint
- Material Theme
- Material Icon Theme
- indent-rainbow
- Auto Rename Tag
- CSS Peek
- Git Lens
- Git Graph
- Bookmarks
- Live Server
- Markdown Preview Enhanced
- Auto Import



## Browser

### Browser List

- [Chrome](https://www.google.co.kr/chrome/?brand=YTUH&gclid=CjwKCAjwoIqhBhAGEiwArXT7K9Goaqyt7jmph7S1zphATxC-zjawwfMjqnEDG5ufBfH8ublWd0pesxoCvUwQAvD_BwE&gclsrc=aw.ds)
- [Whale](https://whale.naver.com/)
- [Edge](https://www.microsoft.com/ko-kr/edge?form=MA13FJ)



### Chrome Extensions

- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=ko)
- [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=ko)



## Corporation Tools

### Notion

- [Notion 가입](https://www.notion.so/signup)

- [Notion 다운로드](https://www.notion.so/ko-kr/desktop)



### Slack

- [Slack 가입](https://slack.com/intl/ko-kr/)
- [Slack 다운로드](https://slack.com/intl/ko-kr/downloads)



### Git

- [Git 다운로드](https://git-scm.com/download)

- Homebrew로 다운로드 (MacOS)

  ```
  $ brew install git
  
  // config
  $ git config —-global user.name “your_name_in_Eng”
  $ git config —-global user.email “your_adena_mail”
  $ git config —-list
  ```



## Runtime

### Node.js

- [Node.js 다운로드](https://nodejs.org/ko/download)

- Node.js 버전 변경

  ```
  // n 설치
  $ sudo npm i -g n
  
  // 버전 별 설치
  $ sudo n install lts
  $ sudo n install 16
  $ sudo n install 14
  
  // 활성화 가능 버전 목록 확인
  $ sudo n ls
  
  // 특정 노드 활성화
  $ sudo n
  ```

  

## Package Managers

### NPM

- Node.js 설치 시 자동으로 함께 설치



### Yarn

- Yarn 다운로드

  ```
  $ sudo npm install -g yarn
  ```

  

## ETC

### Homebrew (MacOS)

- Homebrew 다운로드

  ```
  $ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  
  // 설치 후 터미널에 뜨는 명령어들 실행 (아래는 예시)
  $ `echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/kanghyun/.zprofile`
  $ `eval "$(/opt/homebrew/bin/brew shellenv)”`
  
  // Cask 패키지 설치 (선택)
  $ brew install cask
  ```



### iTerm2

- [iTerm2 다운로드](https://iterm2.com/)

- Homebrew로 다운로드 (MacOS)

  ```
  $ brew install --cask iterm2
  ```

- 테마 설정

  ```
  // oh-my-zsh 설치
  $ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
  
  // Powerlevel10k 설치
  $ git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k 
  
  // zshrc에서 ZSH_THEME="powerlevel10k/powerlevel10k” 으로 변경
  $ vim ~/.zshrc
  
  // 좌상단 iterm2 > Preferences > Profiles > Colors > 좌하단 Color Presets > 테마 선택(Solarized Dark)
  
  // 재실행하여 configure 설정 진행 (or $ p10k configure)
  ```

- 예시

  <img width="762" alt="image" src="https://user-images.githubusercontent.com/70627979/229291018-682804af-3067-45d8-a957-9b5fadaab867.png">



### Postman

- [Postman 다운로드](https://www.postman.com/downloads/)