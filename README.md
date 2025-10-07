# 👋 Hello World

```java
public class Developer {
    private String name = "Prateek Kumar";
    private String role = "Senior Software Engineer";
    private String location = "Bangalore, Karnataka, India";
    private String email = "prateekkumar1393@gmail.com";
    private String portfolio = "https://prateek-mureliya.github.io";
    private String linkedin = "https://www.linkedin.com/in/prateek-mureliya";
    
    private String[] languages = {
        "Java", "Python", "JavaScript", "TypeScript"
    };
    
    private String[] frameworks = {
        "Spring Boot", "React.js", "Next.js", "FastAPI", "Flask"
    };

    private String[] databases = {
        "MySQL", "MongoDb", "Redis", "Kafka", "Elasticsearch"
    };
    
    private String[] tools = {
        "Git", "Docker", "Kubernetes", "AWS Cloud (ELB, EC2, SQS, RDS, S3 and etc)"
    };
    
    public void aboutMe() {
        System.out.println("🚀 Passionate about building scalable applications");
        System.out.println("💡 Constantly learning new technologies");
        System.out.println("🗄️ Skilled at managing databases effectively");
    }
    
    public static void main(String[] args) {
        Developer me = new Developer();
        me.aboutMe();
    }
}
