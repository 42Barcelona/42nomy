# 42nomy
Experimental FOSS project to provide stats to students to help them manage their autonomy

## Specifications

### Variables
- XP = total of winned xp (all cursus)
- CursusXP = total of winned xp for a specific cursus
- Speed = total xp (for a cursus) / duration (Nowadays - Begin_at) # We aim for the highest value of ActiveSpeed
- SpeedRatio = 1 - (1 / Speed)
- ActiveSpeed = total xp / total time logged
- ActiveSpeedRatio = 1 - (1 / ActiveSpeed) # We aim for the highest value of ActiveSpeed
- BH Amount = nb of days of BH left
- BHRatio = 1 - (1 / ActiveSpeed) # We aim for the highest amount of BH
- ClosesRatio 1 / nbOfCloses # We aim for the lowest amount of closes
- ProjectSpeed = (Nowadays - locked_at)
- ProjectAmount = AmountOfValidatedProjects
- ProjectAmountRatio = 1 - (1 / AmountOfValidatedProjects) # We aim for the highest amount of validated projects
- EvaluationAmount = AmountOfEvaluation

### Features

The software should match the following expectation:
- LeaderBoard by specific variable

### Scopes

We want for you to be able to select the scope you want:
- World Wide
- Country
- Campus
- Kickoff
- Pool

### Time Range

We would like also to have the possibility to filter the time range
- since the beginning
- By year
- By quarter
- By month
- By week
- Today

### Goals

Since not everyone aim the same goals in life, it's the same for your learning path

Let's make it possible to choose different goals like:
- The piscine (Discover Internet, Shell, C, peer2peer and 42 in general)
- The common Core (learn the polyvalent basis knowledge of programming that will allow you to do whatever you want)
- RNCP 6: Web & Modible Apps
- RNCP 6: Software
- RNCP 7: IT & Network
- RNCP 7: Architecture Data & DB
- Level 16 (Old Junior degree)
- Level 21 (Old senior degree)
