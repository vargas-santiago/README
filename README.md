<h2>Santiago Vargas</h2>


<h2 align="center">About me</h2>

```java
import java.util.Arrays;
import java.util.List;
import java.util.HashMap;

class README {


    static List<String> languages_and_tools = Arrays.asList(
            "Java", "Spring Boot" , "Git", "HTML", "CSS", 
            "AWS", "MongoDB", "Gradle", "Maven", "SQL", "Postman",
            "Oracle", "Swagger", "Intellij IDEA", "Visual Code",
            "Bash", "Github", "Linux", "Windows", "JSON", "Visual Basic", "Visual C#");
    
    static String whoami = "I love anything to do with technology and how software is built. \n" + 
            "I am currently located in Boise, ID. From of Oct 2021 to July 2022 I \n" +
            "attended Bloom Bloom Institute of Technology. I mostly code in Java but have also made \n" +
            "small video games in Visual C#, Visual Basic, Dark Basic, and Lua. I have recently started \n" +
            "to learn the Rust programming language.";
    
    static final String OPERATING_SYSTEM = "I used to only run windows but in the last year I have become \n" +
            "a die hard Linux enthusiast.";

    static HashMap<String, String> socials = new HashMap<>();
    
    public static void main(String[] args) {

        socials.put("LinkedIn", "vargas-santiago");
        socials.put("GitHub", "vargas-santiago");
        socials.put("Email", "vargas-santiago@protonmail.com");

        System.out.println("Socials:");
        System.out.println(socials + "\n");

        System.out.println("Who am I?");
        System.out.println(whoami + "\n");

        System.out.println("Preferred operating system:");
        System.out.println(OPERATING_SYSTEM + "\n");     

        System.out.println("Languages and Tools:");
        System.out.println(Arrays.toString(languages_and_tools.toArray()));
    }
}
```
