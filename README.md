
# Eron Alves

[![Linkedin](https://img.shields.io/badge/-Connect-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/eron-alves-da-silva/)](https://www.linkedin.com/in/eron-alves-da-silva/)

### Custom Solution Analyst I at Capgemini

![Danny Phantom](https://media3.giphy.com/media/IpeYSEZshTefe/giphy.gif?cid=ecf05e477ihvxw1k80tmm2wvsdjlossuyn3tda2fb7yh099f&rid=giphy.gif&ct=g)

## About me

```java
package person

import java.util.Map;
import java.util.HashMap;

public class Me {
    private String name;
    private String actualCompany;
    private String twitterHandler;
    
    private Map<String, String[]> mainStack = new HashMap<>();
    private URL linkedin;
    
    public Me(){
      this.name = "Eron Alves da Silva"
      this.actualCompany = "Capgemini"
      this.twitterHandler = "masoxi22";
    
      this.mainStack.put("Java", {"Spring", "Jakarta"});
      this.mainStack.put("Typescript", {"Angular", "Express", "Koa"});
      
      try{
      
        this.linkedin = new URL("https://www.linkedin.com/in/eron-alves-da-silva/");
        
      } catch (MalformedURLException ex){
        System.out.println("Meu linkedin existe em!");
      }
    }
}
```
