<p align="center" >
   <samp>
   Hi 👋, I'm  <em>Madhu Aala</em>.
   <br/> Java Developer | ₿lockchain Ξnthusiast. <br/>
   </samp>
</p>

<p align="center">
   <a href="https://twitter.com/madhu_aala">
   <img align="center" alt="Madhu's Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg"/>
   </a>
   &nbsp;&nbsp;&nbsp;&nbsp;
   <a href="https://www.linkedin.com/in/madhu-aala">
   <img align="center" alt="Madhu's LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg"/>
   </a>
</p>

<!--
   <p align="center">
     <img src="https://github.com/madhu/madhu/raw/master/cover-madhu.png" />
   </p>
-->
   
```js
/**
 * 
 * @author: Madhu Aala
 */

package com.java.bio;

public class MyProfile {
  private final String name;
  private String title;
  private String[] skills;
	
public MyProfile(String name, String title, String[] skills) {
  this.name = name;
  this.title = title;
  this.skills = skills;
}
public void displayProfile() {
  System.out.println("Name: " + name + "\n" + "Title: " + title + "\n" + "Technical Skills:");
  for (String techSkills : skills) {
  System.out.println("> " + techSkills);
  }
}
public static void main(String[] args) {
  String name = "Madhu Aala";
  String title = "Java Developer";
  String[] skills = {
   "Language: Java",
   "Database: Oracle SQL",
   "Framework: Struts",
   "Web Technologies: HTML, CSS & JS",
   "Development Tools: Eclipse",
   "Version Control System: CVS & Github",
   "API Testing: Postman"
};
MyProfile myProfile = new MyProfile(name, title, skills);
  myProfile.displayProfile();
  }
}
```
<div align="center">
  <p>
	<img src="https://github-readme-streak-stats.herokuapp.com/?user=madhu-aala" alt="madhu-aala" />
	<img src="https://github-readme-stats.vercel.app/api?username=madhu-aala&show_icons=true&locale=en" alt="madhu-aala" />
  </p>

  [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=madhu-aala&show_icons=true&layout=compact&hide_border=true)](https://github.com/madhu-aala/github-readme-stats)
</div>
