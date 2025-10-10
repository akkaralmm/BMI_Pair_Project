# BMI_Pair_Project
BME Health Calculator Suite

This project is a simple but practical health tracking app. It brings together three tools most people use separately — a BMI calculator, a metabolic rate estimator, and a food log — and puts them into one place with a clean, tabbed interface.

How it’s set up
The app runs in a browser using Gradio, so users don’t need to install anything complicated.
The layout is split into three tabs: one for BMI, one for metabolic rate (BMR/TDEE), and one for food tracking.
A styled header and some custom CSS give it a polished look, so it feels more like a finished product than a rough script.

What each part does
BMI Calculator Users enter their height and weight (metric or imperial). The app calculates BMI, shows which category they fall into (underweight, normal, overweight, obesity), and even plots how their BMI changes over time.
Metabolic Rate (BMR/TDEE) With age, gender, height, weight, and activity level, the app estimates how many calories the body burns at rest (BMR) and in a day (TDEE). It also suggests calorie targets for maintaining, losing, or gaining weight.
Food & Calorie Tracker Users can log meals either by picking from a list of common foods or typing in their own. The app totals up the day’s calories, compares it to the TDEE target, and shows a 7‑day chart of intake.

How it works behind the scenes
Pandas keeps track of the data (BMI history, food logs).
Plotly makes the charts interactive and easy to read.
Gradio’s event system connects the buttons and inputs to the functions that do the calculations, so everything updates live when the user interacts.

Why it’s useful
Instead of juggling different calculators or apps, this suite gives a quick, all‑in‑one view of health metrics. It’s lightweight, easy to use, and good for anyone who wants to keep an eye on their health without getting lost in overly complex fitness apps.
Akkara Lamaimas 6813400, Nanticha Supmool 6813375 | EGBI
