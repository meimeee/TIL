# :computer: CLI   명령어

Unix 명령어 학습



## 단축키 명령어

- 취소 :  `ctrl + c`

* 터미널 청소 :  `ctrl + l`

* 단어 단위로 삭제 : `ctrl + w`

* 터미널 종료 : `ctrl + d`

* 상하 방향키 : 이전/다음 명령어 불러오기

* 좌우 방향키 : 커서 이동

  

## 프롬프트(prompt $)

**터미널의 $ 마크는 명령어 입력 준비 완료를 의미**

**즉, $ 마크가 없을 경우에는 명령어를 입력해도 제대로 동작하지 않음** 



# 폴더 

폴더는 단순히 파일/폴더를 묶어주는 역할을 함

## 폴더 생성하기

```
mkdir <dir_name>
```

## 폴더 이동하기

```
cd <dir_name>
```

## 폴더 삭제하기

```
#안전삭제
rm -r <dir_name>

# 강제삭제
rm -rf <dir_name>
```



# 파일

## 파일 생성하기

```
touch <filename> #확장자까지 반드시 작성
```

## 파일 삭제하기

```
rm <filename> 
```



## 파일 실행하기 (컴퓨터 기본 실행 프로그램)

```
# windows
start <filename>

# macOS + linux
open <filename>
```



## 복사 / 이동

## 복사 

```
cp <original> <copy_name>
```

## 이동

```
# 이름 바꾸기 
mv <original_name> <another_name>

# 이동하기
mv <original_name> <another_path>
```





