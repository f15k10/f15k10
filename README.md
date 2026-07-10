# Hello there my name is jason 

##  Current Status
I am currently open to new opportunities! I'm looking for a junior or mid-level role where I can put my Java and Spring Boot skills to work.

## Who am I?
I have a Master's in Engineering Information and Communication Systems from the University of the Aegean, my academic journey culminated in a profound understanding of software development and ethical hacking.

__The skills honed in REST APIs , cybersecurity and software engineering practices.__

## What I know
<details>

<summary>Java</summary>

### Why java?
Java was the first language that really "clicked" for me. It all started when I competed in IEEEXtreme, where I had a blast solving complex problems under pressure. You can check out my solutions here: [IEEExtreme-17.0](https://github.com/f15k10/IEEEXtreme-17.0-Java-)

Beyond the basics, I’ve become really interested in the Spring Boot ecosystem . The more I dig into the framework, the more cool libraries I find. Right now, I’m working on a project focused on file management (Save, Edit, Delete, Download). I’m currently deep-diving into the ```org.springframework.core.io.Resource``` library to handle file streams efficiently.

Currently studying: [Resource Library](https://docs.spring.io/spring-framework/reference/core/resources.html#resources-resource)
Also studying : [Java JDK21 NIO librarys](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/nio/channels/Channel.html)

***Some Snip code of my project***
```
@Nullable
private static Resource getBytesFile(Path filePath) {
    try {
        FileSystemResource file = new FileSystemResource(filePath);

        if (file.exists() && file.isReadable()) {
            return file;
        }
        return null;

    } catch (Exception e) {
        log.error("Error accessing file at {}: ", filePath, e);
        return null;
    }
}
```
</details>

<details>
<summary>C++</summary>
    
  With C++ I deep dive in to implementing algorithm's to be efficient as possible in a complicated problems, I started with leetcode solving problems like (Dynamic programming ,sliding window ,binary search, queue , HashMap , HashSet problems) those were the main problems i wanted to solve on leetcode , also I enjoy using librarys on C++ such as ```cstdint``` , ```cmath```,```algorithm```,```array``` those specific librarys I use theme for mathematical problems. 

</details>

<details>
    <summary>Database</summary>
    
Design: Transforming business requirements into optimized ER Diagrams.

Development: Building relational (SQL) and non-relational (NoSQL) databases from the ground up.

Performance: Using indexing strategies to reduce latency and improve execution speed.

Stack: MySQL, MariaDB, and MongoDB.

</details>


<details>
    <summary>Rust</summary>
    
I am currently exploring the Rust ecosystem to expand my understanding of systems-level safety and performance. My primary focus is learning the mechanics of the Borrow Checker and the ownership model to understand how to achieve memory safety without a garbage collector. To put these concepts into practice, I am working toward building my first high-performance CLI tools, using these projects as a hands-on way to navigate the language's nuances and low-level engineering principles for the first time.
    
</details>


##  How to reach me:
Just contact me from my [Linkedin](www.linkedin.com/in/jason-argiantzis-48112521a)

