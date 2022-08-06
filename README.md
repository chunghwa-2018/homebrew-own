
## 使用 Homebrew 安装 Java8 / 9 / 10 / 11

#### setp1:

```
$ brew install --cask homebrew/cask/java8
```

#### step2：

```
$ git clone git@github.com:chunghwa-2018/homebrew-own.git
$ cd homebrew-own
$ mv java8.rb /usr/local/Homebrew/Library/Taps/homebrew/homebrew-cask-versions/Casks
```

[java8.rb](java8.rb)


#### step3:

```
$ open -a Google\ Chrome.app

https://www.oracle.com/cn/java/technologies/

download java8 / 9 / 10 / 11 .dmg
```

#### step4:

```
$ vim java8.rb
```

- version

<img src="./images/CleanShot 2022-08-06 at 11.09.57@2x.png" width="600px">

<img src="./images/CleanShot 2022-08-06 at 11.12.44@2x.png" width="200px">

<img src="./images/CleanShot 2022-08-06 at 11.03.25@2x.png" width="600px">

<img src="./images/CleanShot 2022-08-06 at 11.17.20@2x.png" width="800px">

- sha256

  <img src="./images/CleanShot 2022-08-06 at 11.24.17@2x.png" width="600px">

  ```shell
  $ openssl dgst -sha256 /jdk/jdk-8u43-macosx-x64.dmg
  ```

  替换 sha256 的值

- url

  <img src="./images/CleanShot 2022-08-06 at 11.30.45@2x.png" width="600px">

  ```
  $ vim java8.rb
  # 替换 url
  url file:///opt/jdk/jdk-8u221-macosx-x64.dmg
  ```

  

- pkg version

  双击打开 jdk-8u43-macosx-x64.dmg

  <img src="./images/CleanShot 2022-08-06 at 11.36.31@2x.png" width="300px">

  <img src="./images/CleanShot 2022-08-06 at 11.33.43@2x.png" width=600px;>

#### step5:

```
$ brew install --cask homebrew/cask/java8
```

#### step6:

```
$ java --version
```
