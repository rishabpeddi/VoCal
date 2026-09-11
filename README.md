# VoCal — Cross-Platform Nutrition Tracking App

A cross-platform nutrition tracker that turns a voice or photo description of a meal into calorie and macro data.

## Features
- Native iOS app (SwiftUI) and Android app (Flutter), sharing one serverless backend on Cloudflare Workers with SQLite and caching
- Multi-stage food-resolution pipeline that converts voice/photo meal descriptions into calorie and macro data via cache, a fast-food database, LLM parsing, and USDA FoodData Central
- Google, Apple, and guest authentication with rate limiting to prevent API abuse
- Tested across both iOS and Android

## Team & Contributions
- **Rishab Peddi ([@Rishab274929](https://github.com/Rishab274929)):** Built the SwiftUI (iOS) and Flutter (Android) apps, the Cloudflare Workers backend, the food-resolution pipeline, and authentication/rate limiting
- **Eric Spencer ([@EricSpencer00](https://github.com/EricSpencer00)):** Co-developer
