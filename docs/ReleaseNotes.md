# Table of Contents
[Back to Main Project README](../README.md)
- [Table of Contents](#table-of-contents)
- [Simi](#simi)
  - [Simi Docs 1.3.0 Release - Linux\_v1.1.0.pdf](#simi-docs-130-release---document-migration)
    - [Linux\_v1.1.0](#linux_v110pdf)
    - [SpringBoot\_v1.2.0](#springboot_v120pdf)
    - [Java\_v1.2.0](#java_v120pdf)
    - [Japanese\_v1.1.0](#japanese_v110pdf)
    - [Config\_v1.2.0](#config_v120pdf)
  - [Simi 1.2.0 Release - SpringBoot\_v1.1.0.pdf](#simi-120-release---springboot_v110pdf)
    - [SpringBoot\_v1.1.0.pdf](#springboot_v110pdf)
    - [Java\_v1.1.0.pdf](#java_v110pdf)
    - [Node\_v1.1.0.pdf](#node_v110pdf)
    - [Config\_v1.1.0.pdf](#config_v110pdf)
# Simi
## Simi Docs 1.4.0 Release 
### Math_v1.1.0.pdf
* **Math / Calculation / Formulas / Logarithm**
  * Provided examples for the change of base formula.
* **Math / Calculation / Function Graph / Log-Linear**
  * Provide an image of a log-linear function.
### WebFrameworks_v1.2.0.pdf
* **WF / Npm Packages / Core / normalize.css**
  * How to install `normalize.css` and import it to your project.
### SpringBoot_v1.3.0.pdf
* **SpringBoot / Third Party Package / spring-boot-starter-security / Core**
  * Moved `LogoutSuccessHandler` configuration to *SpringBoot / Third Party Package / spring-boot-starter-security / Configuration*. 
* **SpringBoot / Third Party Package / spring-boot-starter-security / Core / Components**
  * Added usage examples for the four authentication methods in spring security.
* **SpringBoot / Third Party Package / spring-boot-starter-security / Configuration**
  * Optimized the heading structure.
* **SpringBoot / Third Party Package / spring-boot-starter-security / Configuration / SecurityFilterChain (Bean)**
  * Optimized configuration introduction for the latest spring security.
## Simi Docs 1.3.0 Release - Document Migration
### Main Updates
* Migrated core documents from Simi 1.2.0 Release to Simi Docs 1.3.0 Release.
* Renamed `Node_v1.1.0.pdf` to `WebFrameworks_v1.1.0.pdf`.
* Renamed `Algorithms_v1.1.0.pdf` to `Math_v1.1.0.pdf`.
* Used abbreviated first-level heading in `DatabaseAndMiddleware_v1.0.0.pdf`, `HTMLAndCSS_v1.0.0.pdf` and `WebFrameworks_v1.1.0.pdf`. 
### Linux_v1.1.0.pdf
* **Linux / Bash Script / Core**
  * Provide detailed explanation for commands like `make`, `make clean`, `make install` and `set`.
* **Linux / Bash Script / Statement / Function**
  * Provide usage examples for a bash function. 
* **Linux / Bash Script / Statement / Control Flow / while**
  * Provided usage examples for `IFS=`. 
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
## Simi 1.2.0 Release - SpringBoot_v1.1.0.pdf
### SpringBoot_v1.1.0.pdf
* **SpringBoot / Third Party Package / spring-boot-starter-security**
  * Configure SecurityFilterChain for the new version of spring security. 
* **SpringBoot / org.springframework (spring) / web / annotation / RequestMapping**
  * Jackson is used for request bodies (`@RequestBody`) and response serialization (`@ResponseBody`).
* **SpringBoot / org.springframework (spring) / web / annotation / InitBinder**
  * Added usage examples for InitBinder annotation. 
* **SpringBoot_v1.1.0.pdf / Third Party Package / Servers / Temporal**
  * Introduce the core classes in the `temporal-serviceclient` and `temporal-sdk` dependencies.
* **SpringBoot_v1.1.0.pdf / Third Party Package / Extentions / junit / \[junit-jupiter-api\]**
  * Using `@ExtendWith` in Junit 5 and `@Rule` in Junit 4.

### Java_v1.1.0.pdf
* **Java / Concept / Java Environment / Version Features / Java 16 (March 221)**
  * Using the `record` operator in Java 16 and later.
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
