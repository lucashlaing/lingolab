  # LingoLab

  A real-time NLP application for word classification, analysis, and collaborative correction, built with React and Firebase.

  ## Overview

  LingoLab lets users analyze and classify words in real time and collaboratively refine the results. It combines an OpenAI-powered NLP backend with a live Firebase datastore, and includes a PDF ingestion pipeline that
  extracts and tags document text with metadata for downstream analysis.

  ## Features

  - **Real-time word classification & analysis** — classifies and analyzes text on the fly using the OpenAI API
  - **Collaborative correction** — multiple users can review and correct classifications, with changes synced live via Firebase
  - **PDF ingestion pipeline** — parses uploaded PDFs, extracts text, and tags it with metadata
  - **Optimized retrieval** — a caching layer and vectorized retrieval queries cut redundant API calls, improving API efficiency by ~60%

  ## Tech Stack

  - **Frontend:** React
  - **Backend / NLP:** Python, OpenAI API
  - **Database & Auth:** Firebase (Firestore, real-time sync)

  ## Getting Started

  ### Prerequisites
  - Node.js and npm
  - Python 3.x
  - A Firebase project and an OpenAI API key

  ### Installation

  ```bash
  # clone the repo
  git clone https://github.com/SithuSoe04/lingolab.git
  cd lingolab

  # install frontend dependencies
  npm install

  # install backend dependencies
  pip install -r requirements.txt

  Configuration

  Create a .env file with your credentials:

  OPENAI_API_KEY=your_openai_key
  FIREBASE_API_KEY=your_firebase_key
  FIREBASE_PROJECT_ID=your_project_id

  Running

  # start the backend
  python app.py

  # start the frontend
  npm run dev
```
