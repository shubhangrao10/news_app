<p align="center">
  <a href="" rel="noopener">
 <img src="https://i.imgur.com/U7K5i08.png" alt="Project logo"></a>
</p>
<h1 align="center"><span><img src="https://i.imgur.com/bNAhtTj.png" alt="Project logo" height = "25"></span> Orator</h1>

<div align="center">

![GitHub Repo stars](https://img.shields.io/github/stars/IvanSan2/Orator)
![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/IvanSan2/Orator)
![GitHub forks](https://img.shields.io/github/forks/IvanSan2/Orator)
![GitHub pull requests](https://img.shields.io/github/issues-pr/IvanSan2/Orator)
![GitHub watchers](https://img.shields.io/github/watchers/IvanSan2/Orator)

</div>

## 📑 Content

- [📑 Content](#-content)
- [📰 Description](#-description)
- [👀 Screenshots ](#-screenshots-)
- [⛓️ Dependencies ](#️-dependencies-)
- [🏁 Getting Started ](#-getting-started-)
  - [Prerequisites](#prerequisites)
  - [Installing](#installing)
- [🎲 Usage ](#-usage-)
- [⛏️ Built With ](#️-built-with-)
- [🗞️ API Credit ](#️-api-credit-)
- [✍️ Authors ](#️-authors-)

## 📰 Description

**Orator** is a simple News App built with Kotlin Jetpack Compose. In this app, there is a Home, Search, Favorites and Settings pages. Home page display animated carousel with 10 latest news and lists distributed by categories with news from newsdata.io. Also app provides you to chose one of the following languages: English, Russian, Hebrew, Arabic or by default all languages includig those listed. You can use the search page page for searching news by keywords. Additionally you can save news in favorites and they are stored in local room database as well as all previously loaded news from network, which means that app is working without connection to internet too. This app has design that adjusts to phone colors and themes and has gestures effects.

## 👀 Screenshots <a name = "screenshots"></a>

|              Dark theme              |             Light Theme              |              Dark theme              | Light Theme                          |
| :----------------------------------: | :----------------------------------: | :----------------------------------: | :----------------------------------- |
| ![](https://i.imgur.com/euTBgPV.jpg) | ![](https://i.imgur.com/53t30Lv.jpg) | ![](https://i.imgur.com/FPTL3aM.jpg) | ![](https://i.imgur.com/1l0MwtU.jpg) |
| ![](https://i.imgur.com/mn0Z48R.jpg) | ![](https://i.imgur.com/T9hqZIw.jpg) | ![](https://i.imgur.com/UezHhZR.jpg) | ![](https://i.imgur.com/p5isjKU.jpg) |

## ⛓️ Dependencies <a name = "dependencies"></a>

- NavCompose
- Hilt
- Lifecycle
- Coroutines
- Room database
- Retrofit
- Logger for retrofit
- Material3
- AsyncImage
- Accompanist pager
- Material extra icons
- Retrofitretry - _avoid error 429_

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development
and testing purposes.

### Prerequisites

> To run this app as well and see all features, you need to register at [NewsData.io](https://newsdata.io/) and get the ApiKey.

### Installing

1. Clone the project to your local machine.
2. Open the project with [Android Studio](https://developer.android.com/studio).
3. Run the project with emulator or build the APK **`( Build > Build Bundle(s)/APK(s) > Build APK(s) )`**
4. At settings screen (first screen that will load), enter your ApiKey from [NewsData.io](https://newsdata.io/)

## 🎲 Usage <a name="usage"></a>

Add Api key in setings screen **`(requared)`**, chose your language `(optional)` and enjoy 😉

## ⛏️ Built With <a name = "tech_stack"></a>

- [Kotlin](https://kotlinlang.org/) - Kotlin 1.8.10

## 🗞️ API Credit <a name = "api_credits">

- https://newsdata.io/

## ✍️ Authors <a name = "authors"></a>

- [@IvanSan2](https://github.com/IvanSan2) - Idea & Initial work
