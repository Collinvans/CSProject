# CSProject

Group Leader: Collin Van Sweden 

Classes: 
1. Time
   The other components are functions, not classes:
   1. display_script
   2. check_typing
   3. main
   4. calculate_wpm
   5. calculate_accuracy

Test: https://replit.com/@9709097/TypingTest#main.py

Diagram: 
+-------------------+
|       Typing      |
+-------------------+
| - script: str     |
+-------------------+
| + __init__(script: str) |
| + display_script() -> None |
| + check_typing() -> int |
| + main() -> None |
| + calculate_wpm(elapsed_time: float) -> int |
| + calculate_accuracy(errors: int) -> float |
+-------------------+
