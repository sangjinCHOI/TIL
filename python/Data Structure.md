# Data Structure

### 1. String

- .find(x) : x의 첫번째 위치 반환, 없으면 -1
- .index(x) : x의 첫번째 위치 반환, 없으면 error
- .replace(old, new[, count]) : old를 new로 count 갯수만큼
- .strip([chars]) : chars 제거, 지정하지 않으면 공백 제거
- .split([chars]) : chars을 기준으로 나누어 ''리스트''로 반환
- 'separator'.join(iterable) : separator로 합쳐 문자열로 반환
- .capitalize() : 맨앞글자 대문자
- .title() : ` or 공백 이후 대문자
- .upper() : 모두 대문자
- .lower() : 모두 소문자
- .swapcase() : 대문자 ↔ 소문자



### 2. list

- .append(x) : x를 list에 추가
- .extend(x) : x(iterable)를 list에 추가
- .insert(i, x) : x를 i 위치에 추가
- .remove(x) : x를 삭제
- .pop(i) : i 위치의 값을 삭제하며 해당 값을 반환, 지정되지 않으면 마지막 항목
- .clear() : 모든 항목 삭제
- .index(x) : x 값의 index 반환
- .count(x) : x 값의 갯수 반환
- .sort() : 정렬(원본 list도 변형, None 반환)
- .reverse() : 순서를 반대로



### 3. set

- .add(elem) : elem을 세트에 추가
- .update(*others) : other(iterable)을 추가
- .remove(elem) : elem을 세트에서 제거하고, 없으면 error
- .discard(elem) : elem을 세트에서 제거하고, 없어도 error 발생 X
- pop() : 임의의 원소 제거 및 반환



#### 4. dictionary

- .get(key[, default])  : key를 통해 value 반환, key가 없으면 None 반환(default 지정 시 default 반환)
- .pop(key[, default])  : key가 있으면 제거하고 반환, key가 없으면 error(default 지정 시 default 반환)

- .update(key='value') : 제공하는 key, value로 덮어쓰기