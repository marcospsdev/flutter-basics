# Quiz em Flutter

Primeiro app em Flutter: um quiz de perguntas com pontuação e tela de resultado.

---

## Sumário

- [Visão geral](#visão-geral)
- [Stack e versões](#stack-e-versões)
- [Estrutura do projeto](#estrutura-do-projeto)
- [Primeiros passos](#primeiros-passos)
- [Autor](#autor)

---

## Visão geral

App de estudo dos fundamentos do Flutter e do Dart. Mostra uma pergunta por vez com as respostas como botões, soma a pontuação de cada resposta escolhida e, no final, exibe uma mensagem de resultado conforme a pontuação, com a opção de reiniciar o quiz.

Principais funcionalidades:

- Widgets com e sem estado (StatelessWidget e StatefulWidget)
- Componentes separados: questão, resposta, questionário e resultado
- Passagem de funções entre widgets (callbacks)
- Roda em Android, iOS, Web e desktop

Feito em 2026, nos estudos de Flutter.

---

## Stack e versões

| Categoria | Tecnologia | Versão |
| --- | --- | --- |
| Linguagem | Dart | 3 |
| Framework | Flutter (Material) | 3 |

---

## Estrutura do projeto

```
lib/
  main.dart           App, estado do quiz e lista de perguntas
  questionario.dart   Pergunta atual e respostas
  questao.dart        Texto da pergunta
  resposta.dart       Botão de resposta
  resultado.dart      Mensagem final e botão de reiniciar
```

---

## Primeiros passos

### Pré-requisitos

- Flutter SDK 3 ou mais recente (inclui o Dart)
- Um emulador Android/iOS, o Chrome ou o desktop para rodar

### Instalação

```bash
git clone https://github.com/marcospsdev/flutter-basics.git
cd flutter-basics
flutter pub get
flutter run
```

---

## Autor

**Marcos Paulo** · Desenvolvedor Full-Stack

- LinkedIn: [in/marcospsdev](https://www.linkedin.com/in/marcospsdev)
- GitHub: [@marcospsdev](https://github.com/marcospsdev)
