🧭 [목차로 돌아가기](./README.md) | 🧭 [이전: 00-Unity란무엇인가](./00-Unity란무엇인가.md) | 🧭 [다음: 02-Unity인터페이스살펴보기](./02-Unity인터페이스살펴보기.md)

# ⚙️ 01. Unity 설치하기

Unity 개발을 시작하려면 먼저 Unity Hub와 Unity Editor를 설치해야 합니다. Unity Hub는 여러 버전의 Unity Editor를 관리하고 프로젝트를 생성 및 관리하는 데 사용되는 런처 애플리케이션입니다.

## 📥 1. Unity Hub 설치

1.  **🌐 Unity 다운로드 페이지 접속**: 웹 브라우저를 열고 [Unity 공식 다운로드 페이지](https://unity.com/download)로 이동합니다.
2.  **🔽 Unity Hub 다운로드**: "Download Unity Hub" 버튼을 클릭하여 Unity Hub 설치 프로그램을 다운로드합니다.
    *   자신의 운영체제(Windows, macOS, Linux)에 맞는 버전을 다운로드해야 합니다. 이 가이드는 Windows를 기준으로 설명합니다.
3.  **🚀 Unity Hub 설치 프로그램 실행**: 다운로드한 설치 파일 (예: `UnityHubSetup.exe`)을 실행하고, 화면의 지시에 따라 설치를 진행합니다. 특별히 설정을 변경할 필요 없이 기본 옵션으로 설치하면 됩니다.
4.  **🔑 Unity Hub 실행 및 로그인**:
    *   설치가 완료되면 Unity Hub를 실행합니다.
    *   처음 실행하면 Unity 계정으로 로그인하라는 창이 나타납니다. 기존 Unity ID가 있다면 로그인하고, 없다면 "Create Unity ID"를 선택하여 새 계정을 만듭니다.
    *   로그인 후 라이선스 활성화 과정을 거칠 수 있습니다. 개인 사용자는 무료 Personal 라이선스를 사용하면 됩니다.

## 🛠️ 2. Unity Editor 설치 (Unity 6 기준)

Unity Hub를 통해 원하는 버전의 Unity Editor를 설치할 수 있습니다. 안정적인 개발을 위해서는 LTS (Long-Term Support) 버전을 사용하는 것이 좋지만, 최신 기능을 사용하고 싶다면 최신 정식 버전을 설치할 수도 있습니다. 여기서는 Unity 6를 기준으로 설명합니다.

1.  **▶️ Unity Hub 실행**: Unity Hub를 실행합니다.
2.  **📁 Editor 설치 탭 이동**: 왼쪽 메뉴에서 "Installs" 탭을 선택합니다.
3.  **➕ Editor 추가**: 오른쪽 상단의 "Install Editor" 버튼을 클릭합니다.
4.  **🔍 Unity 버전 선택**:
    *   설치 가능한 Unity 버전 목록이 나타납니다. "Official releases" 탭에서 원하는 Unity 6 버전을 찾아 선택합니다. (예: Unity 6.x.x 또는 Unity 2023.x LTS 등. 강의 시점의 최신 Unity 6 버전을 확인하는 것이 좋습니다.)
    *   일반적으로 가장 최신 LTS 버전이나, 특정 기능이 필요한 경우 해당 기능을 포함하는 최신 테크 스트림 버전을 선택할 수 있습니다. Unity 6의 새로운 기능을 사용하려면 Unity 6 버전을 선택해야 합니다.
    *   "Install" 버튼을 클릭합니다.
5.  **🧩 모듈 추가 (선택 사항)**:
    *   다음 화면에서는 선택한 Unity 버전에 추가할 모듈을 선택할 수 있습니다. 개발하려는 플랫폼에 맞춰 필요한 모듈을 선택해야 합니다.
        *   **필수**: 보통 "Microsoft Visual Studio Community [버전]" (C# 스크립팅용 IDE)은 자동으로 선택되거나 권장됩니다. 이미 설치되어 있다면 선택 해제해도 괜찮습니다.
        *   **플랫폼 지원**: Android Build Support, iOS Build Support, WebGL Build Support, Windows Build Support (IL2CPP) 등 만들고 싶은 게임의 타겟 플랫폼에 맞춰 선택합니다.
        *   **언어 팩**: Documentation을 한국어로 보고 싶다면 Korean을 선택할 수 있습니다.
    *   필요한 모듈을 선택한 후 "Continue" 또는 "Install" 버튼을 클릭합니다.
6.  **⏳ 설치 진행**: 선택한 Editor와 모듈의 다운로드 및 설치가 진행됩니다. 시간이 다소 걸릴 수 있으니 기다려 주십시오.

## ✅ 3. 설치 확인

-   설치가 완료되면 Unity Hub의 "Installs" 탭에 설치된 Unity Editor 버전이 표시됩니다.
-   이제 프로젝트를 생성하고 Unity 개발을 시작할 준비가 된 것입니다!

다음 문서에서는 Unity Editor의 기본적인 인터페이스에 대해 살펴보겠습니다. 

🧭 [목차로 돌아가기](./README.md) | 🧭 [이전: 00-Unity란무엇인가](./00-Unity란무엇인가.md) | 🧭 [다음: 02-Unity인터페이스살펴보기](./02-Unity인터페이스살펴보기.md) 