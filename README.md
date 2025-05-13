# tqs-lab-3-multi-layer-application-testing-solved
**TO GET THIS SOLUTION VISIT:** [TQS Lab 3-Multi-layer application testing Solved](https://www.ankitcodinghub.com/product/tqs-lab-3-multi-layer-application-testing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93887&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;TQS Lab 3-Multi-layer application testing Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
Lab 3 Multi-layer application testing (with Spring Boot)

</div>
</div>
<div class="layoutArea">
<div class="column">
Context and key points

Prepare

This lab is based on Spring Boot. Most of students already used the Spring Boot framework (in IES course).

If you are new to Spring Boot, then you need to develop a basic understanding or collaborate with a colleague. Learning resources are available at the Spring site.

Key Points

<ul>
<li>Isolate the functionality to be tested by limiting the context of loaded frameworks/components. For some use cases, you can even test with just standard unit testing.</li>
<li>@SpringBootTest annotation loads whole application context, but it is better (faster) to limit application contexts only to a set of Spring components that participate in test scenario.</li>
<li>@DataJpaTest only loads @Repository spring components, and will greatly improve performance by not loading @Service, @Controller, etc.</li>
<li>Use @WebMvcTest to test Rest APIs exposed through Controllers. Beans used by controller need to be mocked.
Explore
</li>
<li>AssertJ library to create expressive assertions in tests: https://assertj.github.io/doc/</li>
<li>Talk on Spring Boot tests (by Pivotal): https://www.youtube.com/watch?v=Wpz6b8ZEgcU</li>
</ul>
3.1 Employee manager example

Study the example concerning a simplified Employee management application (gs-employee- manager).

This application follows commons practices to implement a Spring Boot solution:

<ul>
<li>⎯ &nbsp;Employee: entity (@Entity) representing a domain concept.</li>
<li>⎯ &nbsp;EmployeeRepository: the interface (@Repository) defining the data access methods on the target entity, based on the framework JpaRepository. “Standard” requests can be inferred and automatically supported by the framework (no additional implementation required).</li>
<li>⎯ &nbsp;EmployeeService and EmployeeServiceImpl: define the interface and its implementation (@Service) of a service related to the “business logic” of the application. Elaborated decisions/algorithms, for example, would be implemented in this component.</li>
<li>⎯ &nbsp;EmployeeRestController: the component that implements the REST-endpoint/boundary (@RestController): handles the HTTP requests and delegates to the EmployeeService.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
8 | TQS LABS

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
45426 Teste e Qualidade de Software

</div>
</div>
<div class="layoutArea">
<div class="column">
The project already contains a set of tests.

Look up and study the following test scenarios:

Purpose/scope Strategy Notes

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
A/ Verify the data access services provided by the repository component. [EmployeeRepositoryTest]

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Slice the test context to limit to the data instrumentation (@DataJpaTest)

Inject a TestEntityManager to access the database; use this object to write to the database directly (no caches involved).

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
@DataJpaTest includes the @AutoConfigureTestDatabase. If a dependency to an embedded database is available, an in- memory database is set up. Be sure to include H2 in the POM.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
B/ Verify the business logic associated with the services implementation. [EmployeeService_UnitTest]

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Often can be achieved with unit tests, given one mocks the repository.

Rely on Mockito to control the test and to set expectations and verifications.

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Relying only in JUnit + Mockito makes the test a unit test, much faster that using a full SpringBootTest. No database involved.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
C/ Verify the boundary components (controllers); just the controller behavior. [EmployeeController_ WithMockServiceTest]

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Run the tests in a simplified and light environment, simulating the behavior of an application server, by using @WebMvcTest mode.

Get a reference to the server context with @MockMvc.

To make the test more localized to the controller, you may mock the dependencies on the service (@MockBean); the repository component will not be involved.

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
MockMvc provides an entry point to server-side testing. Despite the name, is not related to Mockito. MockMvc provides an expressive API, in which methods chaining is expected.

In principle, no database is involved.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
TQS LABS | 9

</div>
</div>
</div>
<div class="page" title="Page 10">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
D/ Verify the boundary components (controllers). Load the full Spring Boot application. No API client involved. [EmployeeRestControllerIT]

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Start the full web context (@SpringBootTest, with Web Environment enabled). The API is deployed into the normal SpringBoot context. Use the entry point for server- side Spring MVC test support (MockMvc).

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
This would be a typical integration test in which several components will participate (the REST endpoint, the service implementation, the repository, and the database).

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
E/ Verify the boundary components (controllers). Load the full application. Test the REST API with explicit HTTP client. [EmployeeRestControllerTemplateIT]

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Start the full web context (@SpringBootTest, with Web Environment enabled). The API is deployed into the normal SpringBoot context. Use a REST client to create realistic requests (TestRestTemplate)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Similar to the previous case, but instead of assessing a convenient servlet entry point for tests, uses an API client (so request and response un/marshaling will be involved).

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Note 1: both D/ and E/ load the full Spring Boot Application (auto scan, etc…). The main difference is that in D/ one accesses the server context through a special testing servlet (MockMvc object), while in E/ the requester is a REST client (TestRestTemplate).

Note 2: you may run individual tests using maven command line options. E.g.: $ mvn test -Dtest=EmployeeService*

Review questions: [answer in a readme.md file, in /lab3_1 folder]

<ol>
<li>a) &nbsp;Identify a couple of examples on the use of AssertJ expressive methods chaining.</li>
<li>b) &nbsp;Identify an example in which you mock the behavior of the repository (and avoid involving a database).</li>
<li>c) &nbsp;What is the difference between standard @Mock and @MockBean?</li>
<li>d) &nbsp;What is the role of the file “application-integrationtest.properties”? In which conditions will it be used?</li>
<li>e) &nbsp;the sample project demonstrates three test strategies to assess an API (C, D and E) developed with SpringBoot. Which are the main/key differences?</li>
</ol>
3.2 Cars service

Consider the case in which you will develop an API for a car information system.

Implement this scenario, as a Spring Boot application.

Consider using the Spring Boot Initializr to create the new project (either online or may be integrated in your IDE);

Add the dependencies (starters) for: Developer Tools, Spring Web, Spring Data JPA and H2 Database.

Use the structure modeled in the class diagram as a (minimal) reference.

In this exercise, try to force a TDD approach: write the test first; make sure the project can compile without errors; defer the actual implementation of production code as much as possible.

This approach will be encouraged if we try to write the tests in a top-down approach: start from the controller, then the service, then the repository.

<ol>
<li>a) &nbsp;Create a test to verify the Car [Rest]Controller (and mock the CarService bean), as “light” as possible. Run the test.</li>
<li>b) &nbsp;Create a test to verify the CarService (and mock the CarRepository). This can be a standard unit test with mocks.</li>
<li>c) &nbsp;Create a test to verify the CarRepository persistence. Be sure to include an in-memory database dependency in the POM (e.g.: H2).</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
10 | TQS LABS

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
45426 Teste e Qualidade de Software

d) Having all the previous tests passing, implement an integration test to verify the API. Suggestion:

use the approach “E/” discussed in the previous project (Employees).

Note:

Although the Service in this example is quite trivial (just delegates to repository), in a larger application, we would expect the “services” to implement more complex, interesting, and mission- critical business logic, e.g.: “find a car that provides a suitable replacement for some given car [e.g.: as a courtesy car]”.

3.3 Integration

[Continue in the same project of the previous exercise.] Adapt the integration test to use a real database. E.g.:

<ul>
<li>Run a mysql instance and be sure you can connect (for example, using a Docker container)</li>
<li>Change the POM to include a dependency to mysql [optionally remove H2].</li>
<li>Add the connection properties file in the resources of the “test” part of the project (see the application-integrationtest.properties in the sample project)</li>
<li>Use the @TestPropertySource and deactivate the @AutoConfigureTestDatabase.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
</div>
