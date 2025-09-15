![header](https://capsule-render.vercel.app/api?type=waving&height=300&color=0:667eea,100:a82da8&text=Gesture%20Mouse&textBg=false&fontColor=f8f9fa&animation=fadeIn&fontSize=70)

## 📝 프로젝트 소개

- **프로젝트 명**: 버추얼 마우스(Virtual Mouse)
- **앱(서비스) 명**: Gesture Mouse
- **서비스 목표**: 사용자의 손동작을 웹캠을 통해 실시간으로 인식하고, 이를 바탕으로 실제 마우스처럼 작동하는 버추얼 마우스 시스템을 개발하는 것.
- **기대효과**: 모든 컴퓨터 사용자들에게 발병될 수 있는 손목 터널 증후군 등을 예방할 수 있다.

<br />

## 💻 개발 환경
- **OS** : Windows11
- **IDE** : IntelliJ, VSCode
- **Language** : Python 3.12.10
- **주요 Package** : mediapipe 0.10.21, protobuf 4.25.6, cvzone 1.6.1, pip 25.1.1

<br />

## ✅ 앱 실행 전 필수 체크
***윈도우 11 기준 작성***
### 1. 설정 ➡️ 시스템 ➡️ 전원 ➡️ 전원 모드 '최고의 성능' 설정 확인
### 2. 설정 ➡️ Bluetooth 및 장치 ➡️ 카메라 ➡️ 사용할 카메라 외 전부 사용 안 함, 필요시 아래 사진을 참고하여 비디오 회전
![Image](https://github.com/user-attachments/assets/805e5f60-b087-4b1c-ab79-5e41dd187a09)

![Image](https://github.com/user-attachments/assets/5bf8874e-e035-4613-93d6-2a8cc03b136f)

<br />

## 🖼️ 화면 구성, 동작, 사용되는 제스처
|                                                   메인화면                                                   |                                                   설정화면                                                   |
|:--------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/099dd0c3-3e39-40aa-bab8-34de5b0f26fc" width="400"/> | <img src="https://github.com/user-attachments/assets/2acd312b-8159-43d6-a5c2-52d7ea88209c" width="400"/> |

|                                                   로그화면                                                   |                                             GitHub 사이드 메뉴 동작                                             |
|:--------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/2a3a7a88-d114-48eb-9a63-d1877cbc5587" width="400"/> | <img src="https://github.com/user-attachments/assets/774b66ff-d574-453f-8ac1-8ce11664965d" width="400"/> |

***

|                                                  실시간 동작                                                  |                                                   앱 동작                                                   |
|:--------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/c8f5e2f4-1f89-43b0-8797-7f0a599e2cc1" width="370"/> | <img src="https://github.com/user-attachments/assets/7345c92f-05b9-4f16-a00d-21c8210a875f" width="370"/> |

***

|                                                    클릭                                                    |                                                   더블클릭                                                   |                                                   우클릭                                                    |
|:--------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/dae12d5e-7d90-4615-9cef-2cff9be595a7" width="245"/> | <img src="https://github.com/user-attachments/assets/103eade9-81c0-4d49-9fe2-929568c38804" width="245"/> | <img src="https://github.com/user-attachments/assets/41852172-3f24-45c5-a2e4-a88fe7addb05" width="245"/> |

|                                                   드래그                                                    |                                         스크롤 업(손등) & 스크롤 다운(손바닥)                                          |
|:--------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/d79a07fb-8475-4532-876f-a4dd3eb0c8a8" width="250"/> | <img src="https://github.com/user-attachments/assets/47efdb85-edd4-4bc3-8bb2-44b1560c5ba4" width="250"/> |

<br />

## ⚙ 기술 스택(Tech Stack)
### Backend
<div>
<img alt="Static Badge" src="https://img.shields.io/badge/Python-%233776AB?style=flat-square&logo=python&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/Flask-%23000000?style=flat-square&logo=flask&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/OpenCV-%235C3EE8?style=flat-square&logo=opencv&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/MediaPipe-%230097A7?style=flat-square&logo=mediapipe&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/NumPy-%23013243?style=flat-square&logo=numpy&logoColor=white" height="30">
</div>

### Frontend
<div>
<img alt="Static Badge" src="https://img.shields.io/badge/Electron-%2347848F?style=flat-square&logo=electron&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/CSS-%23663399?style=flat-square&logo=css&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/JavaScript-%23F7DF1E?style=flat-square&logo=javascript&logoColor=white" height="30">
</div>

### System Control & Automation
- **PyAutoGUI, OneEuroFilter**

### Communication & Process Management

- **Axios, Node.js, Multiprocessing, Threading**

### Data Management & Storage

- **JSON, electron-store**

### Build & Development Tools
<div>
<img alt="Static Badge" src="https://img.shields.io/badge/electron--builder-%23000000?style=flat-square&logo=electronbuilder&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/npm-%23CB3837?style=flat-square&logo=npm&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/Git-%23F05032?style=flat-square&logo=git&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/Git_LFS-%23F64935?style=flat-square&logo=gitlfs&logoColor=white" height="30">
<img alt="Static Badge" src="https://img.shields.io/badge/GitHub-%23181717?style=flat-square&logo=github&logoColor=white" height="30">
</div>

<br />

## 🛠️ 프로젝트 아키텍쳐
![Image](https://github.com/user-attachments/assets/0167ee27-3867-47ea-8491-f4e31cd32698)

<br />

## 💁‍♂️ 프로젝트 팀원
|                                        PM, Backend, Frontend                                         |                                           Backend Support                                            |                                           Backend Support                                            |
|:----------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------:|
| <img src="https://avatars.githubusercontent.com/u/114599037?v=4" width="200" height="200" alt="이재민"> | <img src="https://avatars.githubusercontent.com/u/181239205?v=4" width="200" height="200" alt="정의현"> | <img src="https://avatars.githubusercontent.com/u/152354094?v=4" width="200" height="200" alt="한재호"> |
|                                   [이재민](https://github.com/Reysia)                                   |                                  [정의현](https://github.com/juhqwer)                                   |                                 [한재호](https://github.com/minmotion1)                                 |
