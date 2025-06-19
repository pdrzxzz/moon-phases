# 🌘 Moon Phases Visualizer

This project uses the astronomical library [**PyEphem**](https://pypi.org/project/ephem/) to calculate and visualize the Moon phases throughout the year **2025**. The main goal is to understand how the percentage of the Moon's illumination changes day by day and to highlight the key lunar events (New Moon, First Quarter, Full Moon, and Last Quarter).

## 🔧 Technologies Used

* `ephem`: astronomy library for calculating celestial bodies' positions and phases.
* `matplotlib`: visualization library used to create scatter plots with custom colors.

## 📊 What does the code do?

* Calculates the percentage of the Moon's surface illuminated for each day of the year 2025.
* Identifies the days of the main lunar events:

  * 🌑 New Moon
  * 🌓 First Quarter
  * 🌕 Full Moon
  * 🌗 Last Quarter
* Generates colorful scatter plots illustrating the lunar cycle across:

  * **January** (detailed view)
  * **Entire year of 2025** (overview)
* Detects interesting astronomical events such as **two same-phase events in a single month**, like in **August 2025**, which includes two First Quarters (on days 1 and 31).

## 📌 Important Note

> ⚠️ This code assumes that the year starts with a New Moon, which is not always the case. Therefore, results might not be 100% accurate for all years but still serve as a good visual approximation for astronomical and educational purposes.
