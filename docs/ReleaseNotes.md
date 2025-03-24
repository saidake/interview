# Table of Contents
[Back to Main Project README](../README.md)
- [Table of Contents](#table-of-contents)
- [Simi Docs 1.5.0 Release](#simi-docs-150-release)
    - [Java\_v1.4.0.pdf](#java_v140pdf)
- [Simi Docs 1.4.0 Release - Major Update to `Python_v1.1.0.pdf`](#simi-docs-140-release---major-update-to-python_v110pdf)
    - [Main Updates](#main-updates)
    - [Python\_v1.1.0.pdf](#python_v110pdf)
    - [Java\_v1.3.0.pdf](#java_v130pdf)
    - [SpringBoot\_v1.3.0.pdf](#springboot_v130pdf)
    - [Math\_v1.2.0.pdf](#math_v120pdf)
    - [WebFrameworks\_v1.2.0.pdf](#webframeworks_v120pdf)
    - [Internet\_v1.1.0.pdf](#internet_v110pdf)
- [Simi Docs 1.3.0 Release - Document Migration](#simi-docs-130-release---document-migration)
    - [Main Updates](#main-updates-1)
    - [Linux\_v1.1.0.pdf](#linux_v110pdf)
    - [SpringBoot\_v1.2.0.pdf](#springboot_v120pdf)
    - [Java\_v1.2.0.pdf](#java_v120pdf)
    - [Japanese\_v1.1.0.pdf](#japanese_v110pdf)
    - [Config\_v1.2.0.pdf](#config_v120pdf)
- [Simi 1.2.0 Release - Major Update to `SpringBoot_v1.1.0.pdf`](#simi-120-release---major-update-to-springboot_v110pdf)
    - [SpringBoot\_v1.1.0.pdf](#springboot_v110pdf)
    - [Java\_v1.1.0.pdf](#java_v110pdf)
    - [Node\_v1.1.0.pdf](#node_v110pdf)
    - [Config\_v1.1.0.pdf](#config_v110pdf)
# Simi Docs 1.5.0 Release
### Java_v1.4.0.pdf
* **Java / java.base / java.nio / file / Path**
  * `Path.of()` automatically handles platform-specific separators
* **Java / java.base / java.io / (character stream) / FileWriter**
  * Optimize the introduction.
* **Java / java.base / java.io / File**
  * Optimize the introduction.
* **Java / java.base / java.beans**
  * Optimize the introductions for all classes under the heading.
* **Java / java.base / java.awt**
  * Optimize the introductions for all classes under the heading.
* **Java / java.util / concurrent / locks / AbstractQueuedSynchronizer**
  * Simplify the explanation about the Node-based Queuing and Exclusive and Shared Modes mechanism.
# Simi Docs 1.4.0 Release - Major Update to `Python_v1.1.0.pdf`
### Main Updates
* Move outedated PDFs to the `temp` and `temppdf` folders.
* Rename the image title from *Simi Documentation* to *Simi Docs* for all PDF files.
* Replace *Author* with *Edited by* to maintain protection for the external sources and AI-generated content.
### Python_v1.1.0.pdf
* **Python / Concept**
  * Refine the conceptual content.
* **Python / Build-in Libraries / collections**
  * Introduce the usage of `Counter` method.
* **Python / Core / Constants and Variables**
  * Refine the introduction.
* **Python / Core / Data Type Conversion**
  * Refine the introduction.
* **Python / Core / Operators**
  * Refine the introduction.
* **Python / Features / Function**
  * Refine the introduction.
* **Python / Features / Class**
  * Optimize all content.
* **Python / Features / Excpetion**
  * Optimize all content.
* **Python / Features / Import package**
  * Optimize all content.
### Java_v1.3.0.pdf
* **Java / Features / Class / Usage**
  * Optmize the hightlight style.
* **Java / Core / Data Type Conversion / Common Data Type Conversion**
  * Optimize all content.
### SpringBoot_v1.3.0.pdf
* **SpringBoot / Third Party Package / Core / spring-boot-starter-security / Core**
  * Move `LogoutSuccessHandler` configuration to *SpringBoot / Third Party Package / spring-boot-starter-security / Configuration*. 
* **SpringBoot / Third Party Package / Core / spring-boot-starter-security / Core / Components**
  * Add usage examples for the four authentication methods in spring security.
* **SpringBoot / Third Party Package / Core / spring-boot-starter-security / Configuration**
  * Optimize the heading structure.
* **SpringBoot / Third Party Package / Core / spring-boot-starter-security / Configuration / SecurityFilterChain (Bean)**
  * Optimize configuration introduction for the latest spring security.
* **SpringBoot / Third Party Package / Extensions / junit / \[mockito-core\]**
  * Provide usage examples for the `OngoingStubbing#thenAnswer` method.
* **SpringBoot / Third Party Package / Extensions / junit / \[mockito-core\] / (annotation) / InjectMocks**
  * Initialize mock instances without using `@ExtendWith(MockitoExtension.class)`.
### Math_v1.2.0.pdf
* **Math / Calculation / Formulas / Logarithm**
  * Provide examples for the change of base formula.
* **Math / Calculation / Function Graph / Log-Linear**
  * Provide an image of a log-linear function.
### WebFrameworks_v1.2.0.pdf
* **WF / Npm Packages / Core / normalize.css**
  * Install `normalize.css` and import it to your project.
### Internet_v1.1.0.pdf
* **Internet / Network Model / OSI Model / Application Layer / HTTP**
  * Add clarification that CORS headers must be present in both preflight response and actual response.
  * Provide a CORS example involving the UI, Nginx and the server-side.
# Simi Docs 1.3.0 Release - Document Migration
### Main Updates
* Migrate core documents from Simi 1.2.0 Release to Simi Docs 1.3.0 Release.
* Rename `Node_v1.1.0.pdf` to `WebFrameworks_v1.1.0.pdf`.
* Rename `Algorithms_v1.1.0.pdf` to `Math_v1.1.0.pdf`.
* Use abbreviated first-level heading in `DatabaseAndMiddleware_v1.0.0.pdf`, `HTMLAndCSS_v1.0.0.pdf` and `WebFrameworks_v1.1.0.pdf`. 
### Linux_v1.1.0.pdf
* **Linux / Bash Script / Core**
  * Provide detailed explanation for commands like `make`, `make clean`, `make install` and `set`.
* **Linux / Bash Script / Statement / Function**
  * Provide usage examples for a bash function. 
* **Linux / Bash Script / Statement / Control Flow / while**
  * Provide usage examples for `IFS=`. 
* **Linux / Commands / Service / Service File**
  * Introduce options for configuring a systemctl service file.
### SpringBoot_v1.2.0.pdf
* **SpringBoot / Third Party Package / Extensions / junit / \[mockito-core\] / Mockito**
  * Use `doReturn` to return different values on consecutive calls.  
  * Use `verify(T, org.mockito.verification.VerificationMode)` to check the number of method calls.
* **SpringBoot / Third Party Package / Extensions / junit / \[mockito-core\] / (annotation) / Spy**
  * Difference between `@Spy` and `@Mock`. 
### Java_v1.2.0.pdf
* **Java / java.base / java.util / concurrent / locks / AbstractQueuedSynchronizer**
  * Add a usage example for the `newCondition()` method.
### Japanese_v1.1.0.pdf
* **Japanese / Verb / 簡体**
  * Provide a comprehensive explanation of the plain form.
* **Japanese / Verb / 敬体**
  * Provide a comprehensive explanation of the polite form.
### Config_v1.2.0.pdf
**Config / Java Environment / maven / Commands / mvn / Core**
  * How to pass environment variables to a Junit test.
# Simi 1.2.0 Release - Major Update to `SpringBoot_v1.1.0.pdf`
### SpringBoot_v1.1.0.pdf
* **SpringBoot / Third Party Package / spring-boot-starter-security**
  * Configure SecurityFilterChain for the new version of spring security. 
* **SpringBoot / org.springframework (spring) / web / annotation / RequestMapping**
  * Jackson is used for request bodies (`@RequestBody`) and response serialization (`@ResponseBody`).
* **SpringBoot / org.springframework (spring) / web / annotation / InitBinder**
  * Add usage examples for InitBinder annotation. 
* **SpringBoot_v1.1.0.pdf / Third Party Package / Servers / Temporal**
  * Introduce the core classes in the `temporal-serviceclient` and `temporal-sdk` dependencies.
* **SpringBoot_v1.1.0.pdf / Third Party Package / Extentions / junit / \[junit-jupiter-api\]**
  * Use `@ExtendWith` in Junit 5 and `@Rule` in Junit 4.

### Java_v1.1.0.pdf
* **Java / Concept / Java Environment / Version Features / Java 16 (March 221)**
  * Use the `record` operator in Java 16 and later.
* **Java / java.base / java.time / LocalDate**
  * Introduce the default date string format.
* **Java / java.base / java.text / SimpleDateFormat**
  * Add examples for "MM" and "dd" time format.
  * SimpleDateFormat is not thread-safe. 
* **Java / java.base / java.util / (Data Type) / (List) / List**
  * How to convert a primitive array to a list  
* **Java / java.base / java.util / (Data Operation) / Arrays**
  * `Arrays.stream` has a time complexity of O(n). 

### Node_v1.1.0.pdf
* **Node / React / Core / Import Components**
  * How to import various components in React.
* **Node / Configuration / tsconfig.json**
  * Introduce typescript configuration file. 
* **Node / Npm Packages / Cli Utils / craco**
  * Use craco to overwrite webpack configurations in a CRA project. 
* **Node / Npm Packages / Loader / Cli Utils / create-react-app**
  * Build-in Support in `create-react-app` package. 
* **Node / Npm Packages / Loader / less-loader**
  * Use styles in a React component.
* **Node / Npm Packages / Loader / sass-loader**
  * Use styles in a React component.

### Config_v1.1.0.pdf
* **Config / Work Environment / git / Configuration / .gitignore**
  * Explain the priority and rules for ignoring files in  `.gitignore`. 
* **Config / Work Environment / Nodejs / Commands / yarn**
  * Commonly used yarn commands.
