# 문자열 구분자와 값 처리 프로그램

## 📥 입력값
- **문자열(String)** 타입의 입력을 받습니다.

---

## 🔍 구분자 정의
1. **기본 구분자**:  
   - 쉼표(`,`)와 세미콜론(`;`)

2. **커스텀 구분자**:  
   - **`//`와 `\n` 사이에 있는 문자**가 커스텀 구분자로 사용됩니다.  
     예) `//;\n1;2;3` → 커스텀 구분자: `;`

---

## 🛠️ 기능 요구 사항

### 입력값
- 문자열 타입의 입력을 받습니다.

### 구분자
- **기본 구분자**: 쉼표(`,`)와 세미콜론(`;`)
- **커스텀 구분자**: `//`와 `\n` 사이에 위치하는 문자

---

## 🛠️ 함수 정의

### 1. 구분자임을 확인하는 함수
- **기능**: 주어진 문자가 구분자인지 확인합니다.
- **입력**: 문자 (String)  
- **출력**: Boolean (구분자 여부)  

