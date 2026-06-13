### 서버 
모드 추가
```
packwiz modrinth add 모드이름
```


서버 실행스크립트 젤앞에 이거 추가해서 ㄱㄱ 

```
git pull
packwiz refresh
```

---

### 클라이언트
(초기 세팅 1회만 하면 이후로 실행만하면됨) 

1. 프리즘런처 다운로드 https://prismlauncher.org/




2. add instance ->  아래와같이 설정 
<img width="935" height="780" alt="image" src="https://github.com/user-attachments/assets/27aa35ad-c1eb-44b6-81fd-484232dd160a" />


3. folder -> minecraft 안에 packwiz-installer-bootstrap.jar 다운로드 받은거 넣기 


4. Settings -> 커스텀 커맨드에 이거 복붙
   
```
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/EI-FIE/packwiz/main/pack.toml
```
   
<img width="912" height="842" alt="image" src="https://github.com/user-attachments/assets/d236b950-d18e-46bd-b0e7-c1778ffc7a1a" />


