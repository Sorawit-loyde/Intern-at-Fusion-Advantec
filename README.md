# Intern at Fusion Advantec

Line Chatbot with Gemini and Firebase

## Overview

This repository features a LINE chatbot built using JavaScript. The bot integrates Gemini (AI) and Firebase for messaging, persistence, and enhanced intelligence.

## Features

- LINE Messaging API integration
- Gemini AI-powered responses
- Firebase backend for data storage

## Requirements

- Node.js & npm
- LINE Messaging API account
- Firebase project & credentials

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Sorawit-loyde/Intern-at-Fusion-Advantec.git
   cd Intern-at-Fusion-Advantec
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Configure environment variables:**
   - Create a `.env` file with your LINE and Firebase credentials.
   - Example:
     ```
     LINE_CHANNEL_SECRET=your_channel_secret
     LINE_CHANNEL_ACCESS_TOKEN=your_access_token
     FIREBASE_API_KEY=your_firebase_key
     ```

## Usage

Start the chatbot server:
```sh
node index.js
```
Or, if using scripts:
```sh
npm start
```

## Setup

- Set up your LINE Messaging API channel.
- Set up a Firebase project and obtain credentials.
- Update `.env` or relevant config files.
