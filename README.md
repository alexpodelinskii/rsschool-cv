## 1. Name & Surname: 
### Alexandr Podelinskii
## 2. Date of birth:
### 9th, March, 1987
## 3. Contact Information
 1. Phone number: +375336240642
 2. E-mail: nikitik00787@gmail.com
## 4. Addres: 
###  Grodno (Belarus) 
## 5. Education:
### Belarusian National Technical University (INTERNATIONAL INSTITUTE OF DISTANCE EDUCATION), Graduate as an Information technology engineer, 2014
## 6. Summary:
#### I want to become a front-end developer. I really like programming, it allows me to learn something new every day. My strengths are curiosity, determination, perseverance.
## 7. Hard skills
 1. Programing language: JavaScript
 2. Working with:
     * HTML
     * CSS
     * React
     * Git
## 8. Soft skills:
* communicability
 * Self-Motivation
 * Responsibility 
 * Teamwork 
## 9. Language:
    Russian: native
    English, Poland: reading and translating ability
## 10. Code examples
Codewar cata [Playing with digits](https://www.codewars.com/kata/5552101f47fc5178b1000050)
```
function digPow(n, p){
  let arr = String (n).split('');
  arr.forEach(item => +item);
  let res = 0;
  for (let i=0; i<arr.length; i++){
   res += arr[i]**p;
    p++;
  }
  let a = res/n;
  if (parseInt(a)==a) {
    return a;
    } else return -1;
}   
```