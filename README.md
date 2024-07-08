
Skip to content
Navigation Menu

    CristianBaciu8
    /
    Proiect-Final

Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights

    Settings

    Releases Proiect 

manual_testing_project_jira_Elefant.ro Latest
@CristianBaciu8 CristianBaciu8 released this 02 Jul 21:55
Proiect
7bac5da

Testing Project for Elefant.ro

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: Elefant.ro website application

Tools used: Jira, Zephyr Squad.
Functional specifications:

The below stories was created in Jira and describes the functional specifications of the "Register and Add to cart" module, for which the final project is performed upon.

Screenshot 2024-06-29 213858

Screenshot 2024-06-29 214233

Here you can find the release that was created for this project:

Screenshot 2024-07-03 210550

Testing process

The test process was performed based on the standard test process as described below.

1.1 Test planning

The Test Plan is designed to describe all details of testing for all the modules from the Elefant.ro website application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (inserati link catre documentul cu planul de testare)
1.1.1. Roles asigned to the project and persons allocated

Project manager:     Ion Anache
Product owner:       Mihai Cretu
Software developer:  Costel Giocas
QA Engineer:         Cristian Baciu

1.1.2 Entry criteria defined

    The business requirements must be finalizate
    The roles must have been allocated
    The test plan must be finished and sent to the stakeholders
    The entry criteria and exit criteria must be defined
    The project risks must have been identified and mitigated

1.1.3 Exit criteria defined

    95% of the test can be executed
    not finding bugs of major severity in a specific period of time
    the existing bugs that were reported must have been fixed and followed by retesting and regression testing
    the deadline has been reached

1.1.4 Test scope

Tests in scope:

In order to fulfill the testing objectives we are only going to focus on Registration Module which has been placed in the scope of testing and has been targeted for improvement over the next 2 weeks.

From the point of view of the testing techniques we are going to use mostly blackbox testing with the following test design techniques:

equivalence partitioning
boundary value analysis
decision table

From a testing type perspective we are going to use non-functional testing where we are going to cover only usability testing and compatibility testing. Also, positive testing and negative testing are to be done, and (according to the needs) retesting and regression testing will be done when defects are going to be fixed or when modifications of any type are going to be brought to the code.

Tests not in scope:

We are not going to cover during the testing process any techniques related to whitebox testing.

Also, performance and security testing will not be performed during this session of testing.

From the perspective of the modules covered, any other functionality that is located outside of the login or register module are not to be tested.

1.1.5 Risks detected

Project risks:

R1: Errori software: erori sau defecte neasteptate in software-ul dezvoltat
R2: Depasiri bugetare: costuri care depasesc bugetul alocat
R3: Intreruperea lantului de aprovizionare: Intreruperi in furnizarea de materiale sau servicii necesare
R4: Dificultati in Integrarea noilor tehnologii cu sistemele existente
R5: Calitatea scazuta a codului

Product risks:

R6: Cartile pot fi deteriorate pe parcursul livrarii acestora
R7: Risc de tranzitii frauduloase prin intermediul siteului web
R8: Informatiile personale si de plata ale clientilor ar putea fi compromise daca site-ul este piratat
R9: Stocuri excesive sau insuficiente de produse

1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.
1.2 Test Monitoring and Control

Screenshot 2024-07-03 210550

Screenshot 2024-07-01 085454

Screenshot 2024-07-01 085237

1.3 Test Analysis

The testing process will be executed based on the application requirements.

You can find below an example of ten test conditions (out of a total of 16) that were created in the scope of this project:

Screenshot 2024-07-01 085454

1.4 Test Design

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here (inserati linkul catre fisierul cu testele, in format pdf, word sau csv)

1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

(inserati lista de elemente care sunt evaluate in etapa de implementare)

1.6. Test Execution

Test cases are executed on the created test Cycle summary: (inserati aici numele cycle-ului pe care l-ati creat)

Bugs have been created based on the failed tests. The complete bug reports can be found here:
Screenshot 2024-07-01 084631
Screenshot 2024-07-03 103810
Recording.2024-06-30.100049.mp4

The following is a summary of the bugs that have been found:

Screenshot 2024-07-03 211053

The following is a summary of the bugs that have been found:

Bug -> BCC-49

Priority: HIGH
Severity: Critical

Bug-> BCC-48

Priority: MEDIUM
Severity: Major

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

Test execution chart was generated and can be found below.

Screenshot 2024-07-01 090727

The final report shows that a number 12 tests have failed of a total of 16

A number of 2 total bugs were found, from which the priority is: 2 are medium.

In concluzie pentru testul site-ului Elefant.ro este ca acesta urmareste sa ofere o experienta optima de cumparaturi online

In cadrul proiectului efectuat au fost create 2 story-uri din care un story a fost acoperit cu 16 teste dintre care 12 au fost executate, al doilea story a fost executat cu 2 teste si in urma acestora au fost identificate 2 bug-uri de o severitate medie.
Assets 2
Loading
Footer
© 2024 GitHub, Inc.
Footer navigation

    Terms
    Privacy
    Security
    Status
    Docs
    Contact

Release manual_testing_project_jira_Elefant.ro · CristianBaciu8/Proiect-Final
