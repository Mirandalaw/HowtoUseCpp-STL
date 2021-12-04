
## *1. vector  Container*

  - 삽입, 삭제 비효율
<hr>

  ```#include<vector>``` : 헤더파일 추가.
  
  ```vector<(DataType)> v``` 
  
  Insert -> ```v.push_back(N)```
  
  Pop -> ```v.pop_back()```
  
  ```vector<pair<(DataType),(DataType)> v ```
  
  Insert -> ```v.push_back(make_pair(a,b))```
  
  Pop ->```v.pop_back()```
  
  ```vector<int> v(N)``` : 0으로 초기화 된 N개의 원소를 가짐.
  
  ```vector<int> v2(v1)``` : v2는 v1 vector 복사.
  
  ```vector<(DataType)>::iterator iter;
     for(iter = v.begin(); iter != v.end(); iter++){
        cout<<*iter<<'\n';  
      }
  ```
<hr/>

## *2. queue Container*

<hr/><hr>

  ```#include<queue>``` : 헤더파일 추가.
  
  ```queue<(DataType)> q``` 
