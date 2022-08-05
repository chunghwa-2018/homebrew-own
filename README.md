
## 使用 homebrew 安装 Java8 / 9 / 10 / 11

#### setp1:

```
$ brew install --cask homebrew/cask/java8
```

#### step2:

```
$ cd /usr/local/Homebrew/Library/Taps/homebrew/homebrew-cask-versions/Casks/
$ touch java8.rb
```

#### step3：

```
$ git clone git@github.com:chunghwa-2018/homebrew-own.git
$ cat java8.rb >> java8.rb
```

#### step4:

```
$ open -a Google\ Chrome.app

https://www.oracle.com/cn/java/technologies/

download java8 / 9 / 10 / 11 .dmg
```

#### step5:

```
$ vim java8.rb
```

- version

- sha256

- url

- pkg version

#### step6:

```
$ brew install --cask homebrew/cask/java8
```

#### step7:

```
$ java --version
```
