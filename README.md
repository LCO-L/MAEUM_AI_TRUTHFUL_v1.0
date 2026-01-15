# MAEUM AI ENGINE (TRUTHFUL) - macOS Version

This package provides the Truthful version of MAEUM AI for macOS. It’s designed for running the AI engine locally and offers a streamlined experience for users.

📦 Contents:

      MaeumAI: The main executable file – the core AI engine.
      koboldcpp-mac-arm64: A backend engine optimized for running Large Language Models (LLMs).
      models/: Contains the AI model files in GGUF format (.gguf).  These are essential for the AI to function.
      _internal/: Internal libraries required for the program's operation – do not delete.


🚀 Getting Started

Method 1: Recommended - Terminal Execution

Using the terminal provides the easiest way to troubleshoot any issues.

     Open the Terminal application.
     Navigate to the folder containing this package using the cd command.  Drag the folder directly into the Terminal window to automatically paste the path.


bash
    cd /path/to/extracted/folder


     Run the AI engine with the following command:

    
bash
    ./MaeumAI


Method 2: Double-Click Execution

You can also run the AI engine by double-clicking the MaeumAI icon in Finder. (Initial execution may be blocked due to security settings.)

⚠️ Troubleshooting

      "Unable to open because the developer cannot be verified" Error:
          In Finder, right-click (or Control+click) on the MaeumAI file.
          Select “Open” from the menu.
          Click “Open” again in the warning dialog box.  (This may only need to be done once for subsequent double-clicks.)
      koboldcpp Permissions Error:  The koboldcpp-mac-arm64 file might require execute permissions.  Run the following command in the Terminal:

    

bash
    chmod +x koboldcpp-mac-arm64



      Model File Not Recognized: Ensure that the models folder contains .gguf extension files – these are the necessary AI model files.




Created by MAEUM AI Team (Lee, DongHun)



Changes Made & Why:

      More Descriptive Language: Replaced phrases like "실행 파일" with more readily understandable terms ("main executable file").
      Improved Clarity:  Added explanations for why each component is important.
      Stronger Recommendation: Explicitly stated that terminal execution is "recommended."
      Enhanced Troubleshooting:  Expanded on the troubleshooting steps and provided clearer instructions.
      Formatting: Improved formatting for better readability and a professional look.
      Added Emphasis:  Used bolding to highlight key instructions and components.
      Streamlined Structure: Slightly reorganized for better flow.


This revised description is more user-friendly, informative, and easier to understand for someone unfamiliar with the program. It clearly outlines the setup process, troubleshooting tips, and the purpose of each component.

---

# MAEUM AI ENGINE (TRUTHFUL) - macOS Version

이 프로그램은 MAEUM AI의 Truthful 버전을 실행하기 위한 패키지입니다.

## 📋 구성품
- **MaeumAI**: 실행 파일 (실제 AI 엔진)
- **koboldcpp-mac-arm64**: LLM 구동을 위한 백엔드 엔진
- **models/**: AI 모델 파일들 (.gguf)
- **_internal/**: 프로그램 실행에 필요한 라이브러리들 (삭제 금지)

## 🚀 실행 방법

### 방법 1: 터미널에서 실행 (권장)
오류 메시지를 확인하기 쉬워 가장 권장되는 방법입니다.

1. 터미널(Terminal) 앱을 엽니다.
2. `cd` 명령어로 이 폴더로 이동합니다.
   (폴더를 터미널 창으로 드래그하면 경로가 입력됩니다)
   ```bash
   cd /path/to/extracted/folder
   ```
3. 아래 명령어로 실행합니다.
   ```bash
   ./MaeumAI
   ```

### 방법 2: 더블 클릭 실행
Finder에서 **MaeumAI** 아이콘을 더블 클릭하여 실행할 수 있습니다.
(보안 설정에 따라 처음에 실행이 차단될 수 있습니다)

## ⚠️ 문제 해결

### "개발자를 확인할 수 없기 때문에 열 수 없습니다" 메시지가 뜨는 경우
1. Finder에서 **MaeumAI** 파일을 '우클릭' (또는 Control+클릭) 합니다.
2. 메뉴에서 **열기**를 선택합니다.
3. 경고창에서 **열기**를 다시 한번 클릭합니다.
(한 번만 이렇게 하면 이후에는 더블 클릭으로 실행 가능합니다)

### koboldcpp 권한 오류
`koboldcpp-mac-arm64` 파일도 실행 권한이 필요할 수 있습니다. 터미널에서 다음을 입력하세요:
```bash
chmod +x koboldcpp-mac-arm64
```

### 모델 파일 인식 불가
`models` 폴더 안에 `.gguf` 확장자를 가진 모델 파일이 있는지 확인하세요.

---
Created by MAEUM AI Team (Lee, DongHun)
