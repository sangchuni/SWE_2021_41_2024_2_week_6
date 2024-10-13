# SWE_2021_41_2024_2_week_6

## Week 4 assignment
* https://github.com/sangchuni/-SWE_2021_41_2024_2_week_4-/blob/main/_%7B2020313735%7D_%7B%EA%B3%BD%EC%83%81%EC%B2%9C%7D.ipynb
<pre>
<code>
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
</code>
</pre>

* discription
---
## Week 5 assignment
>docker exec ossp-container cat /etc/os-release
>*discription

