# Nutrition Knowledge Notes

**Project:** FitVerse AI

**Version:** 1.0

**Status:** Completed

**Last Updated:** July 2026

---

# Table of Contents

1. Introduction
2. Calories
3. Macronutrients
4. Micronutrients
5. Glycemic Index
6. Body Mass Index (BMI)
7. Basal Metabolic Rate (BMR)
8. Total Daily Energy Expenditure (TDEE)
9. Portion Size Estimation
10. Food Density
11. Application in FitVerse AI
12. References

---

# Introduction

A strong understanding of nutrition science is essential for developing an AI-powered nutrition assistant. While FitVerse AI is not intended to diagnose or treat medical conditions, it must provide users with meaningful nutritional information based on recognized dietary principles.

This document summarizes the core nutrition concepts that will guide the application's features, recommendation engine, and calorie estimation pipeline.

---

# Calories

## Definition

A calorie (kcal) is a unit of energy that measures the amount of energy provided by food and beverages.

The human body uses calories to perform essential functions such as:

- Breathing
- Digestion
- Blood circulation
- Physical activity
- Exercise
- Brain function

---

## Energy Balance

Body weight is primarily influenced by the relationship between calories consumed and calories expended.

### Calorie Surplus

Calories consumed > Calories burned

Result:
- Weight gain

---

### Calorie Deficit

Calories consumed < Calories burned

Result:
- Weight loss

---

### Maintenance

Calories consumed ≈ Calories burned

Result:
- Stable body weight

---

## Importance in FitVerse AI

The application will estimate calorie intake from meals and compare it against each user's daily calorie target.

---

# Macronutrients

Macronutrients are nutrients required in large quantities and provide energy.

---

## Protein

### Functions

- Muscle repair and growth
- Enzyme production
- Hormone production
- Immune system support

### Energy

1 gram = 4 kcal

### Sources

- Eggs
- Chicken
- Fish
- Milk
- Paneer
- Lentils
- Beans
- Soy products

---

## Carbohydrates

### Functions

- Primary source of energy
- Supports brain function
- Fuels physical activity

### Energy

1 gram = 4 kcal

### Types

Simple carbohydrates

- Sugar
- Candy
- Soft drinks

Complex carbohydrates

- Rice
- Oats
- Whole grains
- Potatoes

---

## Fat

### Functions

- Hormone production
- Vitamin absorption
- Cell structure
- Long-term energy storage

### Energy

1 gram = 9 kcal

### Healthy Sources

- Nuts
- Seeds
- Avocados
- Olive oil

---

# Micronutrients

Micronutrients are nutrients required in smaller amounts but are essential for normal body function.

They include:

## Vitamins

Examples:

- Vitamin A
- Vitamin B Complex
- Vitamin C
- Vitamin D
- Vitamin E
- Vitamin K

---

## Minerals

Examples:

- Calcium
- Iron
- Zinc
- Magnesium
- Potassium
- Sodium

---

## Importance

Micronutrients support:

- Bone health
- Blood production
- Immunity
- Nerve function
- Metabolism

---

## Application in FitVerse AI

Future versions may estimate micronutrient intake and identify possible nutritional deficiencies.

---

# Glycemic Index (GI)

## Definition

The Glycemic Index measures how quickly carbohydrate-containing foods raise blood glucose levels after consumption.

---

## Categories

Low GI:
≤ 55

Medium GI:
56–69

High GI:
≥ 70

---

## Examples

Low GI

- Lentils
- Chickpeas
- Oats

High GI

- White bread
- Sugary drinks
- White rice

---

## Importance

Foods with a lower GI generally produce a slower rise in blood glucose levels and may provide more sustained energy.

---

## Application in FitVerse AI

Future recommendation systems may suggest lower-GI alternatives when appropriate.

---

# Body Mass Index (BMI)

## Definition

BMI estimates body weight relative to height.

Formula:

BMI = Weight (kg) / Height² (m²)

---

## Classification

| BMI | Category |
|------|----------|
| <18.5 | Underweight |
| 18.5–24.9 | Normal |
| 25–29.9 | Overweight |
| ≥30 | Obese |

---

## Limitations

BMI does not distinguish between:

- Muscle mass
- Fat mass
- Bone density

As a result, it may not accurately represent body composition for athletes or highly muscular individuals.

---

## Application in FitVerse AI

BMI may be used as an initial health indicator during user onboarding but should not be the sole basis for recommendations.

---

# Basal Metabolic Rate (BMR)

## Definition

BMR is the amount of energy the body requires to perform essential physiological functions while at complete rest.

These include:

- Heart function
- Breathing
- Brain activity
- Temperature regulation

---

## Factors Affecting BMR

- Age
- Sex
- Height
- Weight
- Muscle mass
- Genetics

---

## Application

BMR forms the foundation for calculating a user's daily calorie requirements.

---

# Total Daily Energy Expenditure (TDEE)

## Definition

TDEE represents the total number of calories a person burns in one day.

It includes:

- BMR
- Physical activity
- Exercise
- Digestion (Thermic Effect of Food)

---

## Activity Levels

| Activity | Multiplier |
|----------|------------|
| Sedentary | 1.2 |
| Lightly Active | 1.375 |
| Moderately Active | 1.55 |
| Very Active | 1.725 |
| Extremely Active | 1.9 |

---

## Application

FitVerse AI will estimate personalized calorie goals using TDEE.

---

# Portion Size Estimation

## Definition

Portion size estimation determines how much food is present in an image.

---

## Why It Is Challenging

Images lack depth information, making it difficult to estimate:

- Volume
- Weight
- Density

Foods with similar appearances can have significantly different masses and calorie contents.

---

## Possible Techniques

- Reference objects
- Depth estimation
- AI-based volume estimation
- Multi-view imaging

---

## Importance

Accurate portion estimation is one of the biggest challenges in AI-based calorie estimation.

---

# Food Density

## Definition

Food density describes how much mass or nutritional value exists within a given volume.

---

## Types

### Calorie Density

Calories per gram of food.

Examples:

Low calorie density:

- Cucumbers
- Watermelon
- Lettuce

High calorie density:

- Peanut butter
- Chocolate
- Nuts

---

### Nutrient Density

Foods rich in vitamins and minerals relative to their calorie content.

Examples:

- Spinach
- Broccoli
- Blueberries

---

## Application

Understanding food density enables more meaningful nutritional recommendations than calorie counts alone.

---

# Application in FitVerse AI

These nutrition concepts directly support several planned features:

- Personalized calorie goals
- Meal analysis
- Macronutrient tracking
- AI-generated nutrition insights
- Progress monitoring
- Goal-based recommendations
- Future micronutrient analysis

Rather than simply reporting calories, FitVerse AI aims to help users understand the nutritional quality of their meals.

---

# Key Takeaways

- Calories measure energy intake.
- Macronutrients provide energy and support body functions.
- Micronutrients are essential for health despite being required in smaller amounts.
- BMI provides a general assessment but has important limitations.
- BMR estimates resting energy needs.
- TDEE estimates total daily calorie requirements.
- Portion estimation is a major computer vision challenge.
- Food density influences both calorie estimation and nutritional quality.

---

# References

- USDA FoodData Central
- World Health Organization (WHO)
- Harvard T.H. Chan School of Public Health
- Academy of Nutrition and Dietetics