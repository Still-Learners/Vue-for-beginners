# 01 - Introduction to Vue.js

## 🎯 Objective
Get a basic understanding of what Vue.js is and how it works with a simple example using a CDN (no installation required).

## 📌 Topics Covered
- What is Vue.js?
- Using Vue via CDN
- Vue instance basics
- Data binding with `{{ message }}`

## 🚀 How to Run
1. Download or clone this folder.
2. Open `index.html` in your browser.

## 🧠 Notes
- We're using Vue 3 with CDN (`unpkg.com/vue@3`).
- `createApp()` is used to initialize the app.
- `data()` is where we declare reactive data.

# 02 - Project Setup with Vue 3 + Vite

## 🎯 Objective
Set up a Vue 3 project using Vite — a fast, modern build tool.

## 📌 Topics Covered
- Installing Vite
- Vue 3 project structure
- Running the development server

## 🛠 Prerequisites
- [Node.js](https://nodejs.org/) installed
- A terminal/command prompt

## 🚀 Steps to Run

### 1. Create Project
```bash
npm create vite@latest my-vue-app -- --template vue
```
### 2. Navigate to Project
```bash
cd my-vue-app
```
### 3. Install Dependencies
```bash
npm install
```
### 4. Run the Dev Server
```bash
npm run dev

```
# 03 - Template, Script, and Style in Vue

## 🎯 Objective
Learn about the structure of a Single File Component (SFC) in Vue, which includes:
- `<template>`: Handles the HTML layout
- `<script>`: Handles the logic
- `<style>`: Handles the styling

## 📌 Topics Covered
- Using data inside templates with `{{ }}`
- Declaring component logic in the `<script>` block
- Scoped styling with `<style scoped>`

## 🚀 How to Run
1. Make sure you're inside a Vite Vue project (e.g., from `02-project-setup`).
2. Replace the contents of `App.vue` and create the `HelloWorld.vue` file as shown.
3. Run the project:
```bash
npm run dev
```