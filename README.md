# Solution1
The script captures screenshots using the mss library to calculate the bar size. If the bar size is greater than or equal to the distance, the swipe action is stopped using threading. Note that even though the swipe function has a duration (e.g., 3000ms), it executes instantly but visually lasts for the specified duration. Therefore, the swipe action even tho it is stopped, it keeps happening for the specified duration.

# FinalSolution
The script measures the distance from the target and performs a swipe action accordingly. While it's not perfect, it has achieved a high score of 53, which is impressive by human standards.

# Important
Both scripts utilize the scrcpy library for Android control and are written in Python. The '.py' is not appearing on purpose so people are discouraged to use the imperfect scripts.
