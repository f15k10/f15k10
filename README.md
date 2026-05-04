# Hello there my name is jason :wave:

## 🚀 Current Status
I am currently open to new opportunities! I'm looking for a junior or mid-level role where I can put my Java and Spring Boot skills to work. If you're looking for a motivated developer who loves problem-solving, let's chat!

## How am I?
I have a Master's in Engineering Information and Communication Systems from the University of the Aegean, my academic journey culminated in a profound understanding of software development and ethical hacking.

__The skills honed in REST APIs , cybersecurity and software engineering practices.__

## What I know
<details>

<summary>Java :coffee: </summary>

### Why java?
Java was the first language that really "clicked" for me. It all started when I competed in IEEEXtreme, where I had a blast solving complex problems under pressure. You can check out my solutions here: [IEEExtreme-17.0](https://github.com/f15k10/IEEEXtreme-17.0-Java-)

Beyond the basics, I’ve become really interested in the Spring Boot ecosystem. The more I dig into the framework, the more cool libraries I find. Right now, I’m working on a project focused on file management (Save, Edit, Delete, Download). I’m currently deep-diving into the ```org.springframework.core.io.Resource``` library to handle file streams efficiently.

Currently studying: [Resource Library](https://docs.spring.io/spring-framework/reference/core/resources.html#resources-resource)
Also studying : [Java JDK21 NIO librarys](https://docs.oracle.com/en/java/javase/21/docs/api/java.base/java/nio/channels/Channel.html)

***Some Snip code of my code***
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
## 📫 How to reach me:
Just contantc me from my [Linkedin](www.linkedin.com/in/jason-argiantzis-48112521a)
<!--
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
