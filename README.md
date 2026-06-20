### 서버 

start script에서 똑같은 계층에서 

```
git clone https://github.com/EI-FIE/packwiz.git
```


./start.sh
```
cd "$(dirname "$0")"

cd packwiz
git pull
cd ..

java -jar packwiz-installer-bootstrap.jar -g -s server file://$(pwd)/packwiz/pack.toml

java -Xmx4G -jar fabric-server-launch.jar nogui
```





모드 추가
```
packwiz modrinth add 모드이름
```
이 레포지토리에 푸시 

서버 실행스크립트 젤앞에 이거 추가해서 ㄱㄱ 


```
git pull
packwiz refresh
```

---

### 클라이언트
(초기 세팅 1회만 하면 이후로 실행만하면됨) 

1. 프리즘런처 다운로드 https://prismlauncher.org/
2. 이것도 다운로드 https://github.com/packwiz/packwiz-installer-bootstrap/releases
<img width="870" height="361" alt="image" src="https://github.com/user-attachments/assets/6bba1809-e36b-422a-8526-9f89a81bd5af" />




3. add instance ->  아래와같이 설정 
<img width="935" height="780" alt="image" src="https://github.com/user-attachments/assets/27aa35ad-c1eb-44b6-81fd-484232dd160a" />


4. folder -> minecraft 안에 packwiz-installer-bootstrap.jar 다운로드 받은거 넣기 
<img width="949" height="582" alt="image" src="https://github.com/user-attachments/assets/82f9d585-1d0d-4c88-a253-f0601536c325" />
<img width="716" height="369" alt="image" src="https://github.com/user-attachments/assets/aedfaf8b-6970-4306-8727-6099e3b092fa" />


5. Settings -> 커스텀 커맨드에 이거 복붙
 <img width="707" height="356" alt="image" src="https://github.com/user-attachments/assets/0e4805f6-6360-4df1-9f73-fd3ef82ae3a2" />

   
```
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/EI-FIE/packwiz/main/pack.toml
```
   
<img width="912" height="842" alt="image" src="https://github.com/user-attachments/assets/d236b950-d18e-46bd-b0e7-c1778ffc7a1a" />


