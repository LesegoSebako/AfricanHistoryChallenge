Introduction to Mobile Application Development - Assignment 2

MODULE CODE - IMAD 5112 STUDENT NAME - LESEGO SEBAKO STUDENT NUMBER - ST 10493865

Github Link - https://github.com/LesegoSebako/AfricanHistoryChallenge

Youtube Link - https://youtu.be/B7CllPZsdk4

# African History Challenge

A simple quiz app that tests knowledge of key moments in African history with true/false questions.

## Features

- 5 true/false questions about African history
- Immediate feedback with explanations
- Score tracking and results review
- Clean Material 3 UI with themed colors

## Screens

1. **Welcome Screen**  
   - App introduction  
   - Start button

2. **Question Screen**  
   - True/False buttons  
   - Historical context for each question  
   - Progress indicator (X/5)

3. **Results Screen**  
   - Final score display  
   - Performance feedback  
   - Option to review or restart

4. **Review Screen**  
   - List of all questions  
   - Correct/incorrect indicators  
   - Explanations for each answer
   - Exit Button

## Technical Details

- **Architecture**: MVVM with ViewModel
- **State Management**: Compose mutableState
- **Navigation**: Compose Navigation
- **Data**: Hardcoded questions/answers in `QuizData.kt`

## Data Structure

```kotlin
// All questions and answers in arrays
val questions = arrayOf("Q1", "Q2"...)
val answers = booleanArrayOf(true, false...)
val explanations = arrayOf("Explanation1"...)

