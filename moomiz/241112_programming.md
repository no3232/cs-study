# 프로그래밍 
## 프로그래밍이란 뭐라고 생각하나요? 
프로그램을 만드는 행위

## 컴파일러는 뭐고 인터프리터는 뭔가요? 

### 컴파일러 
- 컴파일러는 프로그램 전체를 스캔하여 이를 모드 기계어로 번역한다.

- 특징 : 전체 코드를 스캔하는 과정에서 모든 오류를 한꺼번에 출력해주기 떄문에 실행전ㅇ에 오류를 알 수 있다. 
         대표적인 언어로 C, C++, JAVA 등이 있다. 

- 장점 : 전체를 스캔하기 때문에 컴파일러는 초기 스캔 시간이 오래걸리지만, 전체 실행 시간만 따지고 보면 인터프리터 보다 빠르다. 
컴파일러는 초기 스캔을 마치면 실행파일을 만들어 놓고 다음에 실행할 때 이전에 만들어 놓았던 실행 파일을 실행하기 때문이다.

- 단점 : 기계어 번역과정에서 더 많은 메모리를 사용한다. 

### 인터프리터 
- 프로그램 실행시 한 번에 한 문장씩 번역한다. 
- 특징: 프로그램을 실행 시키고 나서 오류를 발견하면 바로 실행을 중지 시킨다. 실행 후에 오류를 알 수 있다. 
        대표적인 언어로 Python, Ruby, javascript 등이 있다. 
- 장점: 컴파일러와 같은 오브젝트 코드 생성과정이 없기 때문에 메모리 효율이 좋다. 
- 단점: 한번에 한문장씩 번역후 실행 시키기 때문에 실행 시간이 느리다. 