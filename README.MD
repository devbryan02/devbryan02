# Desarrollador de Software

¡Hola! 👋 Soy un estudiante apasionado por el desarrollo de software. 
Actualmente, curso el 7to ciclo de Ingeniería de Sistemas 💻 y me enfoco en el backend con Java Spring. 
Siempre estoy buscando aprender y mejorar mis habilidades de programación 🚀

## Tecnologías

![Java](https://img.shields.io/badge/-Java-F89820?style=for-the-badge&logo=java&logoColor=F89820&labelColor=282828)
![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=6DB33F&labelColor=282828)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white&labelColor=282828)
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=282828)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=282828)

```java
import lombok.Builder;
import lombok.ToString;
import lombok.extern.slf4j.Slf4j;

@Slf4j
@Builder
@ToString
public class Developer {
    private String name;
    private String lastName;
    private String location;
    private String web;

    public static void main(String[] args) {
        Developer dev = Developer.builder()
            .name("Bryan")
            .lastName("Cárdenas")
            .location("AYACUCHO, PERÚ")
            .web("https://brayandev.vercel.app/")
            .build();
        log.info(dev.toString());
    }
}
```

## Contacto

- **Sitio Web**: [brayandev.vercel.app](https://brayandev.vercel.app/)
- **Ubicación**: Ayacucho, Perú
