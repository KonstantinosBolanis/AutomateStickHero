# Solution1
It takes screenshots with mss and calculates the bar size. If bar_size >= distance then with threading the swipe action is stopped. (But the swipe functionallity even tho it has a duration let's say 3000ms in reality it is excecuted instantly but visually last 3 seconds. So it can not be stopped even if the script is forced stopped.
# FinalSolution
It measures the distance from the target and swipes accordingly. It is not perfect tho, but the highest score it achieved is 53 which is huge to human standars. 

# Importants!
1) Both files are using scrcpy library (for android control) and the script is in python. The .py is not appearing because i want to discourage people of using an incomplete script that is also not usable without changing some of it's values.
