# Weekly Step Analysis Report

## Overview
This report summarizes my **step count** for the past 7 days, including *daily trends* and a comparison with friends.

~~I skipped tracking one day~~ Just kidding, I didn’t miss any days!

My step data is stored in a JSON file: `steps_week.json`

```csharp
// Example of parsing step data in C#
var steps = new int[] { 7320, 8450, 9020, 10000, 7880, 11050, 9230 };
Console.WriteLine("Average: " + steps.Average());
```
- Consistently met daily goal
- Highest steps on Saturday
  - Possibly due to weekend hike
- Walked more in the evenings

1. Gathered daily step data
2. Computed weekly average
3. Compared with friends

- [x] Sync data from smartwatch
- [ ] Generate final PDF report

| Day       | My Steps | Friend A | Friend B |
|-----------|----------|----------|----------|
| Monday    | 7320     | 8120     | 7010     |
| Tuesday   | 8450     | 7980     | 6900     |
| Wednesday | 9020     | 8800     | 7200     |
| Thursday  | 10000    | 9100     | 7500     |
| Friday    | 7880     | 8700     | 8100     |
| Saturday  | 11050    | 10200    | 9500     |
| Sunday    | 9230     | 8700     | 9300     |

See full documentation [here](https://example.com/full-report).

![Step Trend Chart](steps_chart.jpg)

> “Walking is the best possible exercise. Habituate yourself to walk very far.” — Thomas Jefferson
---
<!-- Data collected via HealthSync app and verified manually -->



