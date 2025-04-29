![image](https://github.com/user-attachments/assets/1f46d374-7ad2-4e36-9ad5-eea802861f99)# raspberry-pi
Rasberry PI practice

라즈베리 파이 설치 과정

1-1 설치 준비
1. SD card 를 window PC에 연결
  
2. 포털 검색창에 라즈베리 파이 설치 검색 후 설치- 실행 - 설정 완료 후 대부분 YES 누르고 포맷 (20분 정도 소요)
   
3. 포맷 후 SD card 라즈베리파이에 삽입

4. 키보드, 마우스, 모니터 라즈베리파이에 연결

5. 부팅 후 부팅 되는 것 확인

1-2 설치 과정
1. vim 혹은 nano 와 같은 편집기 설치 (sudo apt ~~~)

2. 휴대폰으로 챗지피티에 "라즈베리파이 fcitx + 원하는 편집기 + 설치 방법" 입력
ex) 라즈베리파이 fcitx vim 설치 방법
sudo apt update
sudo apt install fcitx-hagul

3. 편집기 내용 모두 입력 후  Esc 누르고 :wq 입력하고 Enter : 한글 입력기 설치 완료

fcitx 설정 창에서 한글 입력기 설정 하기

sudo apt update
sudo apt install fonts-nanum 설치 후 
reboot  : 한글 뷰어

4. 한글 로케일 설정
sudo raspi-config 입력

5. 휴대폰으로 쳇지피티에 : "라즈베리파이 설치시 sudo raspi-config 를 실행 후 처음에 해야 하는 것" 검색



# SUMMARY

# 🍓 Raspberry Pi 설치 및 한글 환경 설정 가이드

---

## ✅ 설치 준비

### 1. SD 카드 PC에 연결
- **설명**: 라즈베리 파이 OS를 설치할 SD 카드를 PC에 연결합니다.
- **목적**: 포맷 및 OS 이미지를 설치하기 위해 필요합니다.

### 2. SD 카드 포맷
- **설명**: 기존 데이터 삭제 및 라즈베리 파이용 파일 시스템으로 초기화합니다.
- **방법**:
  - [Raspberry Pi Imager](https://www.raspberrypi.com/software/) 프로그램 사용 추천
  - 설치 도구에 따라 "YES"를 눌러 포맷 진행
- **소요 시간**: 약 10~20분
- **결과**: 깨끗한 빈 저장공간 확보

### 3. 포맷 완료 후 SD 카드 삽입
- **설명**: 포맷된 SD 카드를 라즈베리 파이에 삽입합니다.
- **주의**: SD 카드 방향을 잘 맞춰서 삽입해야 합니다.

### 4. 입력 장치 연결
- **설명**: 부팅 후 조작을 위해 키보드, 마우스를 연결합니다.
- **권장**: 유선 키보드와 마우스 사용 (초기 설정 시 무선 연결이 불안정할 수 있음)

### 5. 라즈베리 파이 부팅
- **설명**: 전원을 연결하여 부팅을 시작합니다.
- **결과**: 라즈베리 파이 로고와 초기 설정 화면이 나타나야 합니다.

---

## 🧰 필수 프로그램 설치

우선 Wi-FI 연결 후 

6. **패키지 업데이트**
  sudo apt update

7. 편집기 설치 (ex: vim, nano 등)
sudo apt install vim

8. 한글입력기(fcitx + hangul) 설치
sudo apt install fcitx-hangul

9. 한글 폰트 설치 후 재부팅
sudo apt install fonts-nanum

sudo reboot

![image](https://github.com/user-attachments/assets/a7059955-410b-4915-b23e-1d43ea982acf)



