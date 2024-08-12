# Using Firebase Genkit for detecting emotions in Text , Speech and Face

# Usecase :

Difficulty understanding emotions in multiple modalities like Face , Speech and Text forms important markers in the diagnosis of Autism spectrum Disorder(ASD) . This project aims to help autistic individuals identify emotions in multiple modalities using Gemini .

## Demo Video
[genkit.webm](https://github.com/user-attachments/assets/2407074a-cf99-4fbf-acb1-17a1c093a084)

## 
Setting it up:

`npm i -g genkit`

`mkdir firebase-genkit && cd firebase-genkit`

`npm init -y`

> Copy `index.js` and `index.ts` file or modify those if want to create own flow

`genkit init`

`gcloud services enable aiplatform.googleapis.com`

`export GCLOUD_PROJECT=<your project ID>`

`export GCLOUD_LOCATION=us-central1`

`genkit start`
