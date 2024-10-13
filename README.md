# SWE_2021_41_2024_2_week_6

## Week 4 assignment


---python
def isHappy(n):
  array = set()
  while n != 1:
    n = sum(int(digit)**2 for digit in str(n))
    if n in array:
      return False
    array.add(n)
  return True

 input_number = int(input("input: "))
 print(f"output: {isHappy(input_number)}")
---

---
### Week 5 assignment

