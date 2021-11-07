---vector container---
  
  - 삽입, 삭제에는 비효율적임.
  
  - ㅁㅁㅁㅁㅁ<- push_back(),pop_back() 맨 뒤쪽에서 삽입과 삭제 가능
  
 1. vector<int> v;
  
  : 비어있는 vector v를 생성.
  
 2. vector<int> v(N);
  
  : 0으로 초기화 된 N개의 원소를 가짐.
  
 3. vector<int> v2(v1);
  
  : v2는 v1 vector 복사
