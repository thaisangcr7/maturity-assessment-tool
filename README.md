# Regional Bank Digital Maturity Assessment

A browser-based digital maturity self-assessment for US regional and community banks. It asks 20 observable questions across five dimensions, scores each dimension 1–5, draws a radar chart, and reads the score *pattern* to give a strategic next move.

**Live tool:** https://thaisangcr7.github.io/maturity-assessment-tool/

## Dimensions
1. **Core & Customer Data**: data infrastructure
2. **Digital Channels**: customer interaction channels
3. **Operations & Lending Automation**: operational automation
4. **AI in Risk & Service**: AI/ML deployment
5. **Change & Talent Readiness**: organizational change capacity

## How it works
- There are four questions per dimension. Each answer option carries an integer value from 1 to 5, and a dimension's score is the average of its four answers.
- Results stay hidden until all 20 questions are answered.
- Results show the radar chart (Chart.js from jsDelivr), the two lowest dimensions (ties are broken in this order: Core & Customer Data → Change & Talent Readiness → AI in Risk & Service → Operations & Lending Automation → Digital Channels), and one of five Interpretation Guide profiles, or a fallback built on the lowest dimension.
- Questions, stage descriptions and profiles all live in one JavaScript data block at the top of the script, so the guide is maintained by editing data, not markup.
- It's a single self-contained `index.html`: no backend, no cookies, no local storage.

## Credits
This is a team-built tool by **Group 2, ISM 6346 Digital Business Transformation (USF, Fall 2026)**: Jorge Ayala (Framework Designer), Fabianne Santos (Question Author) and Sang Thai (Tool Builder). This copy is hosted individually by Sang Thai for the Week 5 Git & GitHub exercise.

Published by Sang Thai for ISM 6346 Week 5 (Git & GitHub Basics).
