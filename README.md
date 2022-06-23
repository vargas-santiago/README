<h2>Santiago Vargas</h2>


<h2 align="center">About me</h2>
```java
class README {


    List<String> languages_and_tools = Arrays.asList(
            "Java", "Spring Boot" , "Git", "HTML", "CSS", 
            "AWS", "MongoDB", "Gradle", "Maven", "SQL", "Postman",
            "Oracle", "Swagger", "Intellij IDEA", "Visual Code",
            "Bash", "Github", "Linux", "Windows", "JSON", "Visual Basic", "Visual C#");
    
    String whoami = "I love anything to do with technology and how software is built. \n" + 
            "I am currently located in Boise, ID. From of Oct 2021 to July 2022 I \n" +
            "attended Bloom Bloom Institute of Technology. I mostly code in Java but have also made \n" +
            "small video games in Visual C#, Visual Basic, Dark Basic, and Lua. I have recently started \n" +
            "to learn the Rust programming language.";
    
    final String OPERATING_SYSTEM = "I used to only run windows but in the last year I have become \n" +
            "a die hard Linux enthusiast.";

    HashMap<String, String> socials = new HashMap<String, String>();
    
    socials.put("LinkedIn", "vargas-santiago");
    socials.put("GitHub", "vargas-santiago");
    socials.put("Email", "vargas-santiago@protonmail.com");

    public static void main(String[] args) {

        System.out.println("Who am I?");
        System.out.println(whoami);

        System.out.println("Preferred operating system:");
        System.out.println(OPERATING_SYSTEM);

        System.out.println("Socials:");
        socials.entrySet().forEach(entry -> {
            System.out.println(entry.getKey() + " " + entry.getValue());
        });

        System.out.println("Languages and Tools:");
        System.out.println(Arrays.toString(languages_and_tools.toArray()));
    }
}
```
