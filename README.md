# AtHome-AIWorkspace

## 👨‍💻 Projeto desenvolvido por:
[Rafael Torres Nantes](https://github.com/rafael-torres-nantes)

## Índice

* [📚 Contextualização do projeto](#-contextualização-do-projeto)
* [🛠️ Tecnologias/Ferramentas utilizadas](#%EF%B8%8F-tecnologiasferramentas-utilizadas)
* [📁 Estrutura do projeto](#estrutura-do-projeto)
* [📌 Como executar o projeto](#como-executar-o-projeto)

## 📚 Contextualização do projeto

Projeto com foco em inteligência artificial aplicada em ambiente doméstico. O repositório consolida diversos experimentos com bibliotecas de visão computacional, reconhecimento e síntese de voz, explorando ferramentas capazes de monitorar ambiente e interagir com usuários.

## 🛠️ Tecnologias/Ferramentas utilizadas

* Python
* OpenCV (`cv2`)
* MediaPipe
* SpeechRecognition (`speech_recognition`)
* pyttsx3
* Bibliotecas: `numpy`, `matplotlib`, `PIL`

## 📁 Estrutura do projeto

```
Object Recognition/
  └── object_recognition.py
People Recognition/
  ├── Basics/
  │   └── video_test.py
  └── Face Recognition/
      ├── detect.py
      ├── models/
      ├── requeriments.txt
      └── utils.py
Quizz/
  ├── main.py
  └── question_answer.py
Voice Recognition/
  ├── main.py
  ├── voice_emulation.py
  └── voice_recognition.py
```

## 📌 Como executar o projeto

Cada funcionalidade é um subprojeto isolado e possui dependências específicas como `opencv-python`, `mediapipe` e `SpeechRecognition`. Para utilizá-las, instale as dependências via `pip` e execute os scripts de ponto de entrada nas respectivas pastas, como `python detect.py` na pasta de Face Recognition, ou `python main.py` para testar os outros recursos.
