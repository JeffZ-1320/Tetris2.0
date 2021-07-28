# Tetris2.0
 Spring boot on VS Code
 
## March 14, 2021
Merge web page with tetris project.
I used https://spring.io/guides/gs/serving-web-content/ to relearn how to serve web contents with a controller class in springBoot. 
### Difference between @RestController vs @Controller
- @Controller usually goes with a @ResponseBody
- @RestController = @Controller + @ResponseBody
    - I would need to figure what @ResponseBody is 
### Why is my css not working for my html page in SpringBoot?
- While html files are stored in the ``Template`` folder, css files are stored in the ``static`` folder. 

> link rel="stylesheet" href=**"css/bootstrap.min.css"**
### Next up:
I should remove the greeting examples from my code. Then I should try to figure out how to do live update in springBoot. If more time was left, I should also speed up my js basics. 
