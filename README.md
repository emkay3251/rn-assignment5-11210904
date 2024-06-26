# rn-assignment5-11210904
 
# Mobile Application

A mobile application designed with a user-friendly interface, featuring a home screen, cards screen, statistics screen, and settings screen. The application supports a dark and light theme mode that can be toggled by the user.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [File Structure](#file-structure)
5. [Screens](#screens)
   - [HomeScreen](#homescreen)
   - [MyCardsScreen](#mycardsscreen)
   - [StatisticsScreen](#statisticsscreen)
   - [SettingsScreen](#settingsscreen)
6. [Navigation](#navigation)
7. [Theme Context](#theme-context)
8. [Custom Components](#custom-components)
9. [Dependencies](#dependencies)
10. [Contributing](#contributing)
11. [License](#license)

## Features

- Home screen with a user greeting and an overview of transactions.
- Cards screen displaying the user's cards.
- Statistics screen showing the user's financial statistics.
- Settings screen with options to access various settings and switch between light and dark themes.
- Theme setting persistence using AsyncStorage.

## Screens

### HomeScreen

The HomeScreen displays a greeting, user profile picture, search button, card image, action buttons (Send, Receive, Loan, Topup), and recent transactions.

### MyCardsScreen

The MyCardsScreen shows placeholder text for the user's cards.

### StatisticsScreen

The StatisticsScreen shows placeholder text for the user's financial statistics.

### SettingsScreen

The SettingsScreen offers options to navigate to different settings pages and a toggle switch for changing the theme.

## Navigation

The app utilizes a bottom tab navigator (react-navigation/bottom-tabs) to switch between the Home, My Cards, Statistics, and Settings screens.

## Theme Context

The app uses a context provider to handle the theme state (light or dark). The current theme is stored in AsyncStorage to ensure it persists between sessions.


## Screenshots

### Screenshot 1
![Screenshot 1](my-app\src\screenshots\Screenshot1.jpg)

### Screenshot 2
![Screenshot 2](my-app\src\screenshots\Screenshot2.jpg)

### Screenshot 3
![Screenshot 3](my-app\src\screenshots\Screenshot3.jpg)

### Screenshot 4
![Screenshot 4](my-app\src\screenshots\Screenshot4.jpg)

## Assets
![loan](my-app\src\assets\loan.png)
![home](my-app\src\assets\home.png)
![grocery](my-app\src\assets\grocery.png)
![Card](my-app\src\assets\Card.png)
![apple](my-app\src\assets\apple.png)
![send](my-app\src\assets\send.png)
![profile](my-app\src\assets\profile.png)
![topUp](my-app\src\assets\topUp.png)
![statictics](my-app\src\assets\statistics.png)
![spotify](my-app\src\assets\spotify.png)
![settings](my-app\src\assets\settings.png)
![search](my-app\src\assets\search.png)
![recieve](my-app\src\assets\recieve.png)
![myCards](my-app\src\assets\myCards.png)
![moneyTransfer](my-app\src\assets\moneyTransfer.png)