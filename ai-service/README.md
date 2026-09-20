# FitFlow AI Service

This folder contains the Artificial Intelligence and Machine Learning service for the FitFlow fitness application.

## Technology

- Python
- FastAPI
- Machine Learning
- REST API

## Responsibilities

The AI service is responsible for:

- Personalized workout recommendations
- Fitness recommendation processing
- Nutrition analysis
- User activity analysis
- AI-based fitness suggestions

## Personalized Workout Recommendations

The AI service receives user fitness information from the backend.

Example inputs include:

- User fitness goal
- Fitness level
- Available workout time
- Previous workout history
- User preferences
- Activity information

The service processes these inputs and generates personalized workout recommendations.

### Data Flow

```text
User
  ↓
React Native Application
  ↓
Node.js Backend
  ↓
Python/FastAPI AI Service
  ↓
Recommendation Model
  ↓
Personalized Workout
  ↓
Node.js Backend
  ↓
User Application