# wrappers-easy-executor

* `gradlew`, `mvnw` 등을 쉽게 실행하게 해주는 실행기
* Linux/MacOS 등 전용

## gw
* 프로젝트 하위디렉토리 어디에서라도 `gw` 를 실행하면 부모디렉토리의 `gradlew` 명령을 찾아서 실행해준다.

### install
```
wget -O ~/.local/bin/gw "https://raw.githubusercontent.com/kwon37xi/wrappers-easy-executor/main/gw" && chmod +x ~/.local/bin/gw
```

### usage
```
# 프로젝트 하위 디렉토리에서
gw tasks
```

## mw
* 프로젝트 하위디렉토리 어디에서라도 `mw` 를 실행하면 부모디렉토리의 `mvnw` 명령을 찾아서 실행해준다.

### install
```
wget -O ~/.local/bin/mw "https://raw.githubusercontent.com/kwon37xi/wrappers-easy-executor/main/mw" && chmod +x ~/.local/bin/mw
```

### usage
```
# 프로젝트 하위 디렉토리에서
mw compile
```
