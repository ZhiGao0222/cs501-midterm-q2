# CS501 Q2 - ViewModel Counter App

This app demonstrates using a ViewModel and unidirectional data flow in Jetpack Compose.

## Features
- Displays a counter value
- Increment button updates the count
- State is managed inside a ViewModel
- UI updates automatically when the state changes

## Technologies Used
- Kotlin
- Jetpack Compose
- ViewModel
- mutableStateOf

## How it works
The counter state is stored inside a `CounterViewModel` using `mutableStateOf`.  
The composable reads the state from the ViewModel and displays it on the screen.  

When the button is clicked, the composable calls a function in the ViewModel to update the state.  
This follows a unidirectional data flow where data flows from the ViewModel to the UI, and user actions flow back to the ViewModel.

## AI Usage
ChatGPT was used to help clarify concepts such as ViewModel and unidirectional data flow.  
All code was written, modified, and tested independently.

## Author
Zhi Gao
