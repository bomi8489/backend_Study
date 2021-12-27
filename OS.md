# OS의 일반적인 작동 원리

## OS(operating system)
- computer hardware(CPU, I/O)를 관리해주면서 동시에 여러 application들이 작동할 수 있는 환경을 제공해주는 software


## OS의 역할
- 프로그램들이 자원을 필요로 할 때 ```자원을 할당```
  - CPU 시간
  - 메모리 공간
  - 파일 저장 공간
  - 입출력장치

- 각각 자원을 할당받은 프로그램들이 서로의 영역을 침범하지 않게 하고, 컴퓨터의 부적절한 사용을 방지하는 ```제어프로그램의 역할```


## OS의 구조
### 1. Multiprogramming
- 여러 작업들이 동시에 메모리에 올라가게 됨
- ```두 개의 작업```을 수행할 때  ```작업1```이 CPU를 사용한 후 I/O를 수행할 때  ```작업2```는 대기중인 CPU를 사용함으로 유연성을 제공하여 효율성을 높임


### 2. Multitasking
- ```Job Scheduling```을 통해 어떤 작업들이 메모리에 올라갈지 결정
- ```CPU Scheduling```을 통해 어떤 작업들을 CPU에서 수행할지 결정
  - Scheduling : 자원을 효율적으로 할당하기 위한 알고리즘
- ```swapping```을 통한 프로세스 교체
  - Swapping : 주기억장치에 적재한 하나의 프로세스와 보조기억장치에 적재한 다른 프로세스의 메모리를 교체하는 기법

## OS의 작동원리
### interrupt-driven
- H/W interrupts
- S/W interrupts

#### Dual-Mode Execution
- ㅇㅇ

#### Timer
- ㅇㅇ

