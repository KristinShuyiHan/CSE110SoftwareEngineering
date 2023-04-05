# Hi! I am Shuyi Han, a potential SWE and CS educator.<img src="IMG_8927.JPG">



Currently a undergrad student at ***UCSD***, persuing degrees in  ***Cognitive Science*** and  ***Computer Science***. I am interested in ***CS, education, hoping to teach CS and  develope computing environments that facilitate learning in the future.***  
Right now, I am developing projects alongside with my classes and working on the outside of class ones. 

## :computer: Projects 
+ ###  TikTok-like Short Video App ### 

- [x] In developing process
- [ ] Fully developed

**Overview**
![](Screenshot%202023-04-05%20at%2011.30.18%20AM.png)
>Code Snippet


```
package com.imooc.utils;

import javax.servlet.http.HttpServletRequest;

public class IPUtil {

      @param request
      @return
    
    public static String getRequestIp(HttpServletRequest request) {
        String ip = request.getHeader("x-forwarded-for");
        if (ip == null || ip.length() == 0 || "unknown".equalsIgnoreCase(ip)) {
            ip = request.getHeader("Proxy-Client-IP");
        }
        if (ip == null || ip.length() == 0 || "unknown".equalsIgnoreCase(ip)) {
            ip = request.getHeader("WL-Proxy-Client-IP");
        }
        if (ip == null || ip.length() == 0 || "unknown".equalsIgnoreCase(ip)) {
            ip = request.getHeader("HTTP_CLIENT_IP");
        }
        if (ip == null || ip.length() == 0 || "unknown".equalsIgnoreCase(ip)) {
            ip = request.getHeader("HTTP_X_FORWARDED_FOR");
        }
        if (ip == null || ip.length() == 0 || "unknown".equalsIgnoreCase(ip)) {
            ip = request.getRemoteAddr();
        }
        return ip;
    }
}

```

Coverage of technological Stack
1. Springboot
2. Distributed Middleware
3. Nginx
4. Nacos
5. Extended Components
6. Cloud Expansion
7. Front-End technology: UniApp & UniCloud





+ ###  mock e-book system ###

- [x] In developing process
- [ ] Fully developed

Currently, I just start building this projects. I hope that the App can achieve functions like user login, rich text box wangeditor [links](https://www.wangeditor.com/en/),login verification, Number of document readings and likes, timed takss, knowledge base, WebSocket Website Notification
, and completes the display of relevant reports using e-charts. You can click on [here](http://wiki.courseimooc.com) to experience the project
## :books: Related Courses
## CS

+ CSE 8A & B Intro to Programming
+ CSE 12 Basic Data Struc & OO Design
+ CSE 15L Software Tools&Techniques Lab
+ CSE 20 Discrete Mathmetics
+ CSE 21 Math/Algorithm&System Analys
+ CSE 30 Computer Organiz&Systms Progrm
+ CSE 100 Advancaed Data Structures 
+ COGS 108 Data Science in Practice 
+ CSE 110 Software Engineering 
+ CSE 135 Online Database Analys&Application

## Education & Cogs

+ COGS 120 Interaction Design
+ COGS 121
+ COGS 123 Social Computing
+ EDS 124AR Teaching Computation in the Digital World
+ EDS 124BR Teaching Computational thinking to everyone

[Relative Link 1](README.md)
[Relative Link 2](.gitignore)


