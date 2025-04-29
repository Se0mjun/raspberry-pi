![image](https://github.com/user-attachments/assets/1f46d374-7ad2-4e36-9ad5-eea802861f99)# raspberry-pi
Rasberry PI practice

라즈베리 파이 설치 과정

1. SD card 를 PC에 연결
  
2. 대부분 YES 누르고 포맷 (20분 정도 소요)
   
3. 포맷 후 SD card 라즈베리파이에 삽입

4. 키보드, 마우스 USB 삽입

5. 부팅 후 부팅 되는 것 확인

6. vim 혹은 nano 와 같은 편집기 설치 (sudo apt ~~~)

8. 챗지피티에 라즈베리파이 fcitx + 원하는 편집기 + 설치 방법 입력
ex) 라즈베리파이 fcitx vim 설치 방법
sudo apt update
sudo apt install fcitx-hagul

편집기 내용 모두 입력 후  Esc 누르고 :wq 입력하고 Enter : 한글 입력기 설치 완료

fcitx 설정 창에서 한글 입력기 설정 하기

sudo apt update
sudo apt install fonts-nanum 설치 후 
reboot  : 한글 뷰어

한글 로케일 설정
sudo raspi-config 입력

쳇지피티에 : "라즈베리파이 설치시 sudo raspi-config 를 실행 후 처음에 해야 하는 것" 검색


# 🍓 Raspberry Pi 설치 및 한글 환경 설정 가이드

## ✅ 설치 준비

1. **SD 카드 PC에 연결**
   - SD 카드 리더기를 사용해 연결

2. **SD 카드 포맷**
   - 대부분 `YES` 선택 후 포맷 진행  
   - 포맷 시간: 약 20분 소요

3. **포맷 완료 후 SD 카드 삽입**
   - 라즈베리 파이에 포맷된 SD 카드 삽입

4. **입력 장치 연결**
   - 키보드 및 마우스를 USB 포트에 연결

5. **라즈베리 파이 부팅**
   - 전원을 연결하고 정상 부팅 확인

---

## 🧰 필수 프로그램 설치

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



