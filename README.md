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
>* PRETTY_NAME="Ubuntu 24.04.1 LTS"\
>  VERSION_ID="24.04"\
>  VERSION="24.04.1 LTS (Noble Numbat)"\
>  VERSION_CODENAME=noble\
>  ID=ubuntu\
>  ID_LIKE=debian\
>  HOME_URL="https://www.ubuntu.com/" \
>  UBUNTU_CODENAME=noble\
>  LOGO=ubuntu-logo\
>  

>docker exec ossp-container git --version
>* git version 2.43.0\

>docker exec ossp-container python3 --version
>* Python 3.12.3\

>docker inspect --format="{{ .HostConfig.Binds }}" ossp-container
>* [./ossp_host_dir:/mnt/ossp_container_dir]\

