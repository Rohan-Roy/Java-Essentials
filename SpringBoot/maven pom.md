# Spring Boot – Starter Parent
- Springboot starter parent provides default configurations for spring-based applications.
- spring-boot-starter-parent has spring-boot-dependencies as its parent and inherits depepdency management from it.
- Every springboot release provides a list of dependencies and versions that it supports. The dependency management feature of the starter-parent allows all the common dependencies to be used without the <version> tag in the pom.xml.

# Dependency Management
- Any springboot starter or other dependencies needed in a project can be included within the <dependency/> tags. All <dependency/> are in turn, declared within the <dependencies/> tags.
- To include dependency versions other than the ones included in spring-boot-starter-parent, <dependencyManagement/> tags can be used. 

# Managing Properties 
- spring-boot-starter-parent contains configurations for java compiler version, maven plugin version and dependencies' versions. These can be overridden inside the <properties/> tags.