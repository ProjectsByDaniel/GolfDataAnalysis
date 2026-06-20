# Golf Performance Analysis Project

## Overview

This project is a personal golf performance dataset designed to analyse scoring trends across multiple rounds and holes.

The dataset tracks performance over time, including:

* Score per hole
* Number of putts
* Par values
* Yards
* Stroke index (difficulty rating)

The goal is to identify patterns in performance and highlight strengths and weaknesses across different hole types.

---

## Dataset Structure

### Hole Information Table

| Column       | Description                                    |
| ------------ | ---------------------------------------------- |
| HoleID       | Unique identifier for each hole (1–18)         |
| Par          | Expected number of strokes                     |
| Yards        | Hole length in yards                           |
| Stroke Index | Difficulty ranking (1 = hardest, 18 = easiest) |

---

### Round Performance Table

| Column         | Description                  |
| -------------- | ---------------------------- |
| Round Date     | Date of round played         |
| HoleID         | Links to hole information    |
| Strokes        | Total shots taken            |
| Score          | Score relative to par        |
| Number of Puts | Number of putts on the green |

---

## Key Metrics

* Average score per round: **24.2**
* Performance tracked across **4+ rounds**
* Breakdown by:

  * Hole difficulty (stroke index)
  * Par type (3, 4, 5)
  * Putting performance

---

## Key Insights

* Par 3 holes show the strongest performance overall.
* Par 5 holes are also relatively strong, likely due to shorter effective approach shots.
* Par 4 holes are the most inconsistent scoring category.
* Holes **3 and 18** show consistently low putting numbers, suggesting strong green performance on those holes.
* Holes **1, 2, 9, 13, and 15** show higher putt counts and weaker scoring performance.
* Hole **15** is consistently the weakest hole across all rounds and may benefit from a more conservative strategy.

---

## Observations

* Early-round performance tends to be weaker, suggesting a warm-up effect.
* Back nine holes show increased consistency in some rounds.
* Performance variability suggests opportunity for improvement in consistency rather than skill ceiling.

---

## Skills Demonstrated

* Data collection and structuring
* Descriptive analytics
* Pattern recognition
* Sports performance analysis
* Basic statistical reasoning

---

## Summary

This project demonstrates how raw sports performance data can be structured and analysed to identify strengths, weaknesses, and trends over time.
