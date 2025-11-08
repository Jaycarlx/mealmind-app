# MealMind - Smart Meal Planning from What You Have

> Never stare at a full fridge wondering "what can I eat?" again.

## The Problem

Every morning, you wake up already tired. Not from lack of sleep, but from knowing you have to figure out what to eat. Even with ingredients at home, decision fatigue hits hard. Your fridge has ingredients. But your brain just... freezes.
"Do I have time to cook? What even goes together? Is this enough for a meal?"
So you skip breakfast. Order lunch. Feel guilty about wasting food at home. Traditional recipe apps assume you'll shop for missing items, but that's the last thing you want to do when you're already exhausted.

## The Solution (Why it matters)

MealMind suggests meals based on **exactly** what you already have in your kitchen, even when ingredients are limited or incomplete. 
Instead of "What do you want to cook?" we ask: **"What do you already have?"**

## What It Does

MealMind eliminates meal decision fatigue by:
- Scanning your pantry/fridge (photo → ingredient list)
- Suggesting 3 meals you can make RIGHT NOW
- Adapting recipes when ingredients are incomplete
- Learning your preferences over time

## Who It's For

- Young adults living alone struggling with daily meal decisions
- People who experience decision fatigue around food
- Anyone tired of food waste and unnecessary grocery trips
- Health-conscious individuals who want nutrition tracking without the hassle

## Key Features

### 1. **Constraint-Based Recipe Adaptation**
Want fried plantain but only have 2 tbsp of oil? MealMind suggests "stuffed plantain boats" (boiled, lightly roasted, then stuffed with eggs). You discover new meals instead of abandoning cravings.

### 2. **Three Smart Modes**
- **Abundance Mode**: Full pantry? Get varied meal suggestions.
- **Constraint Mode**: Limited ingredients? Get creative adaptations.
- **Discovery Mode**: Random items? Get unexpected combinations.

### 3. **Visual Pantry Tracking**
Snap a photo of your fridge. We identify ingredients and quantities so no manual typing for you.

### 4. **Preference Learning**
"Not feeling spicy today" gets remembered. The app adapts to your mood, energy level, and goals.

### 5. **Nutrition Integration**
Every suggestion includes macros and adapts to your fitness goals (weight loss, muscle gain, maintenance).

##  Tech Stack

- **Frontend**: React Native (iOS & Android)
- **Backend**: Node.js + Express
- **Database**: Firebase Realtime Database
- **AI/ML**: OpenAI API (GPT-4) for recipe adaptation
- **Computer Vision**: TensorFlow Lite for ingredient recognition
- **Image Storage**: Cloudinary

##  Platform Availability

**Launch Platform:** iOS & Android mobile apps (React Native)  
**Why Mobile-First:** Deciding what to cook happens in the kitchen, on your phone. Camera access for pantry scanning works best on mobile devices.

**Future:** Web companion app for desktop meal planning (Phase 2)

##  How It Works

1. Photograph your pantry/fridge or ingredients storage
2. AI identifies ingredients and quantities
3. Tell MealMind what you're craving (or say "surprise me")
4. Get 3 meal suggestions with recipes and macros
5. Choose one, mark it cooked, system learns your preferences

##  Design Preview

**User Flow**  
[View MealMind User Flow on Figma ->](https://www.figma.com/board/uWj92dPz71AgtFtTETJaek/MealMind-User-Flow?node-id=0-1&t=96Tusr2pMIURvkI3-1)


##  Why Now?

Three technology shifts make MealMind possible today:
1. **AI became accessible** - OpenAI's API (2023) puts recipe intelligence in any app
2. **Computer vision matured** - 95%+ accuracy in food recognition (2024) makes pantry scanning reliable
3. **Smartphones got powerful** - Modern cameras + on-device ML make real-time ingredient detection feasible

Plus, **behavior shifted**: Post-pandemic, 67% more people cook at home regularly but struggle with meal planning. The pain point is bigger than ever.

##  Success Metrics

- **40% meal conversion rate** (users actually cook suggested meals)
- **3x weekly active usage** (users return multiple times per week)


##  Contributing

Built by [@jaycarlx](https://github.com/jaycarlx) for HNG Internship Stage 4 PM Task