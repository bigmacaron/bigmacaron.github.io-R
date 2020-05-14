## R 을 하면서  정리   

### 1.변수의 선언  
```
my_numeric <- 42      

my_numeric = 42  
```
둘다 같은 방식으로 변수 선언을 할수 있음  

### 2. 파이썬의 type()

python의 type() 과 유사한 class() 가 있음

### 3.vector 형식   

vector = c("하하","안녕",1)

### 4.factor 자료형  

levels 과 labels 용어 그대로 직관적인 의미를 가짐

레벨값을 정할수 있고 라벨링을 한다고 생각하면됨

예시)
```
sex_vector <- c("남", "여", "남")
factor_sex_vector <- factor(sex_vector)
factor_sex_vector
```
실행결과:  
```
>[1] 남 여 남

>Levels: 남 여
```
```
levels(factor_sex_vector) <- c("남성", "여성")
factor_sex_vector
```

실행결과:
```
[1] 남성 여성 남성
Levels: 남성 여성
```
