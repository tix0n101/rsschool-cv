# Tihon Shoklev

![My Photo](https://www.shutterstock.com/image-vector/cartoon-dog-animated-character-full-600nw-2506326479.jpg)

---

##  Contact Information
- **Email:** antonsoklev@gmail.com    
- **Discord:** Tihon Shoklev (@tix0n101) 

---

## About Me
I am a motivated beginner frontend developer with a strong desire to learn and grow in the IT field.  
My goal is to become a professional software engineer and contribute to real-world projects.

I am responsible, detail-oriented, and enjoy solving problems. Currently, I am improving my skills in web development.

---

## Skills
- **Languages:** Python, C++, C#  
- **Version Control:** Git, GitHub  
- **Tools:** VS Community, Git Bash  

---

##  Code Example

**Codewars task: Write a method (or function, depending on the language) that converts a string to camelCase, that is, all words must have their first letter capitalized and spaces must be removed.**

```C#
using System.Text;
namespace Kata
{
  public static class Problem
  {
    public static string CamelCase(this string str)  
    {
      string[] words = str.Split();
      
      StringBuilder res = new StringBuilder();
      
      foreach (string word in words){
        if (word != ""){
         res.Append(char.ToUpper(word[0]));
        }
        if (word.Length > 1){
          res.Append(word.Substring(1).ToLower());
        }
      }
      return res.ToString();
    }
  }
}
```
---

##Work Experience

I don’t have commercial experience yet.

---

##Education

Current university student
RS School JavaScript / Frontend Course (in progress)
Python Course for beginners(https://stepik.org/course/58852)
Learning from online resources (YouTube, documentation, etc.)

---

##English

My English level is B1.
I practice English by watching videos, reading documentation, and sometimes communicating online.
