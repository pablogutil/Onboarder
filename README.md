# 🧩 Interactive Onboarder

A sleek, multi-step onboarding form that collects structured user and company data in four progressive steps. Designed for SaaS user flows, CRMs, or any onboarding funnel.

## ✨ Features

- 4-step dynamic form with progress indicator
- Sections: Personal Info, Company, Goals, Review
- JSON preview on final step before submission
- Fully editable fields with inline validation
- Built with clean, responsive UI components

## 🧱 Tech Stack

- React (Vite + TypeScript)
- TailwindCSS
- State managed with React hooks
- JSON preview via `JSON.stringify()` on final step

## 📁 Folder Structure

src/
├── components/
│ └── Stepper, FormStep, JSONPreview
├── hooks/
│ └── useStepper.ts
├── pages/
│ └── Onboarding.tsx

markdown
Copy
Edit

## 🚀 Usage

1. Clone the repo  
2. `npm install`  
3. `npm run dev`

## 🧑‍💻 Use Cases

- SaaS product onboarding
- Client intake forms
- HR or internal team registration flows
