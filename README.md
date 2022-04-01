# Auto-Reload: No Intellij
### 1. Se for criar o projeto, se certificar que tem o plugin Spring Assistant instalado. E na hora da criação já selecionar: Spring Boot Devtools
### 2. Caso o projeto já exista, seguir os passos seguintes:
#### i. Ponha no POM:
```
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-devtools</artifactId>
    <optional>true</optional>
</dependency>
```
#### ii. Verificar se a opção check-box está marcada em: File -> Settings... –> Build, Execution, Deployment –> Compiler –> Build project automatically is selected
#### iii. File-> Settings... –> Advanced Settings -> marcar o checkbox: Allow auto-make to start even if developed application is currently running
