# JetTrivia — Jetpack Compose

> **Course project.** Built while following an Android Jetpack Compose course (Udemy) — part of my Android learning path. My own products and case studies are on [okebenoithub.web.app](https://okebenoithub.web.app/en/).

A trivia quiz: answer questions one by one, with instant feedback and a running score.

## Features
- Questions loaded from a public trivia JSON dataset over the network.
- Tap an answer to see whether it is correct, then move to the next question.
- Progress through the quiz and a score.

## Built with
Kotlin · Jetpack Compose · Hilt · Retrofit + Gson · Coroutines · Material

## Architecture
MVVM with Hilt: a `QuestionsViewModel` loads questions through a repository and exposes a data-or-exception state to the UI.

## Run it
Open in Android Studio and run — no API key needed.

---

By **Benoit Presly Ndong Oke** — full-stack & mobile developer (Android · Web · Cloud).
Portfolio, case studies and CV: [okebenoithub.web.app](https://okebenoithub.web.app/en/) · [GitHub profile](https://github.com/OkeBenoitHub)
