# Automation Exercise - QA Testing Project

## Project Overview
This repository contains comprehensive testing artifacts for the Automation Exercise website testing project. The project includes manual UI testing, API testing, and test automation frameworks with detailed reporting and documentation.

**Testing Scope:**
- Manual UI Testing (BDD scenarios)
- API Testing (Postman collections)
- Test Automation https://github.com/Abanoub-youssef/GP_Automation_G4
- Database Testing
- Test Documentation and Reporting

## 📂 Quick Links to Major Files & Folders

| Category | File/Folder | Description |
|----------|------------|-------------|
| Documentation | [Project_Overview.docx](./QA_Project_Docs/Project_Overview.docx) | Overall project scope and objectives |
| Documentation | [Epic&User Stories.docx](./QA_Project_Docs/Epic&User%20Stories.docx) | Requirements and user stories |
| Documentation | [Test_Strategy.docx](./QA_Project_Docs/Test_Strategy.docx) | Testing approach and methodology |
| Documentation | [mockup.pdf](./QA_Project_Docs/mockup.pdf) | UI/UX designs and wireframes |
| Test Cases | [CartManagement.feature](./CartManagement.feature) | BDD scenarios for cart functionality |
| Test Cases | [sign-up&contact-use_BDD.txt](./sign-up&contact-use_BDD.txt) | BDD scenarios for registration & contact |
| Reports | [Summary_Report.docx](./Text_Reports/Summary_Report.docx) | High-level test summary and metrics |
| Reports | [Full_Execution_Report.docx](./Reports/Full_Execution_Report.docx) | Detailed test execution results |
| Reports | [Test_Completion_Report.docx](./Reports/Test_Completion_Report.docx) | Final test completion status |
| Defects | [Bug_Reports_Export.xlsx](./Text_Reports/Bug_Reports_Export.xlsx) | Defect tracking and management |
| API Tests | [API_Test_Collection.postman_collection.json](./postman/API_Test_Collection.postman_collection.json) | Postman API test collection |
| Automation | [AutomationExercise/](./AutomationExercise) | Selenium/TestNG automation framework | https://github.com/Abanoub-youssef/GP_Automation_G4 | https://github.com/Abanoub-youssef/GP_CUCUMBER
| Config | [pom.xml](./pom.xml) | Maven configuration for automation framework |
| Evidence | [Evidence/](./Evidence) | Screenshots and test evidence |
| Traceability | [Traceability_Matrix/](./Text_Reports/Traceability_Matrix) | Requirement-to-test case mapping |

## Repository Structure

The following tree diagram represents the high-level file and directory structure of the project:


├── 📁 Evidence/ # Test evidence and screenshots  
├── 📁 QA_Project_Docs/ # Project documentation  
│ ├── Epic&User Stories.docx  
│ ├── Project_Overview.docx  
│ ├── Project_Reading.docx  
│ ├── Test_Strategy.docx  
│ └── mockup.pdf  
├── 📁 Text_Reports/ # Test execution reports  
│ ├── Summary_Report.docx  
│ ├── API_Run_Report.json  
│ ├── Bug_Reports_Export.xlsx  
│ └── Traceability_Matrix/  
├── 📁 Reports/ # Comprehensive test reports  
│ ├── Full_Execution_Report.docx  
│ └── Test_Completion_Report.docx  
├── 📁 postman/ # API testing artifacts  
│ ├── globals/ # Postman global variables  
│ └── API_Test_Collection.postman_collection.json  
├── 📁 AutomationExercise/ # Test automation framework  
├── 📄 CartManagement.feature # BDD feature files  
├── 📄 sign-up&contact-use_BDD.txt # BDD scenarios  
├── 📄 pom.xml # Maven configuration  
└── 📄 README.md # This file  



## Test Artifacts Description

### 📋 Documentation
- **[Project_Overview.docx](./QA_Project_Docs/Project_Overview.docx)** - Overall project scope and objectives  
- **[Epic&User Stories.docx](./QA_Project_Docs/Epic&User%20Stories.docx)** - Requirements and user stories  
- **[Test_Strategy.docx](./QA_Project_Docs/Test_Strategy.docx)** - Testing approach and methodology  
- **[mockup.pdf](./QA_Project_Docs/mockup.pdf)** - UI/UX designs and wireframes  

### 🧪 Test Cases & Scenarios
- **[CartManagement.feature](./CartManagement.feature)** - BDD scenarios for cart functionality  
- **[sign-up&contact-use_BDD.txt](./sign-up&contact-use_BDD.txt)** - BDD scenarios for user registration and contact forms  

### 📊 Test Reports
- **[Summary_Report.docx](./Text_Reports/Summary_Report.docx)** - High-level test summary and metrics  
- **[Full_Execution_Report.docx](./Reports/Full_Execution_Report.docx)** - Detailed test execution results  
- **[Test_Completion_Report.docx](./Reports/Test_Completion_Report.docx)** - Final test completion status  
- **[Bug_Reports_Export.xlsx](./Text_Reports/Bug_Reports_Export.xlsx)** - Defect tracking and management  
- **[API_Run_Report.json](./Text_Reports/API_Run_Report.json)** - API test execution results  

### 🤖 Automation & API Testing & Database test cases 
- **[pom.xml](./pom.xml)** - Maven dependencies for automation framework  
- **[API_Test_Collection.postman_collection.json](./postman/API_Test_Collection.postman_collection.json)** - Postman API test collection  
- **[AutomationExercise/](./AutomationExercise)** - Selenium/TestNG automation framework  -https://github.com/Abanoub-youssef/GP_Automation_G4 | https://github.com/Abanoub-youssef/GP_CUCUMBER
- **[postman/globals/](./postman/globals)** - Postman environment configurations  
- **[Database test cases ]
  
## 🚀 How to Use This Repository

### Viewing Test Documentation
1. Open `.docx` files in Microsoft Word or compatible viewers  
2. Review `.xlsx` files in Microsoft Excel for defect reports  
3. Check `QA_Project_Docs/` for project requirements and planning  

### Running API Tests
1. Import API_Test_Collection.postman_collection.json into Postman
2. Configure environment variables in postman/globals/
3. Execute collections and review API_Run_Report.json for results

### Executing Automation Tests

# Navigate to AutomationExercise directory
cd AutomationExercise
https://github.com/Abanoub-youssef/GP_Automation_G4/

# Run Maven tests
mvn test

# Generate test reports
mvn surefire-report:report

---

## 1. BDD Scenarios

- Open `.feature` files for Cucumber BDD scenarios
- Review `sign-up&contact-use_BDD.txt` for behavior-driven test cases
- Execute BDD tests using Cucumber framework

## 2. Test Coverage

| Test Type | Scope | Tools Used |
|---|---|---|
| Manual UI Testing | Functional, Integration, UAT | Manual execution, BDD scenarios |
| API Testing | REST API validation, Endpoints | Postman, Newman |
| Automation Testing | Regression, Smoke, Functional | Selenium, TestNG, Maven |
| Database Testing | Data integrity, Validation | SQL queries, DB validations |

## 3. Evidence & Traceability

- **Evidence Folder**: `Evidence/` folder contains test execution proofs and screenshots
- **Traceability Matrix**: `Traceability_Matrix/` maps requirements to test cases
- **Defect Tracking**: All defects tracked in `Bug_Reports_Export.xlsx`
- **Reporting**: Comprehensive reporting in `Text_Reports/` and `Reports/` directories

## 4. Project Team

| Role | Name | Responsibility |
|---|---|---|
| Testers | Ahmed Ayman Ali | Database testing. |
| Testers | Abanoub Youssef | Test case execution and defect reporting |
| Testers | Abdallah Sameer | POM structure. |
| Testers | Omar Alaa Eldin | API testing. |

## 5. Updates & Maintenance

### Version Control

- Update test cases when new features are added
- Maintain traceability matrix with requirement changes
- Version control for all test artifacts

### Maintenance Tasks

- Regularly update automation scripts for UI changes
- Keep Postman collections synchronized with API updates
- Refresh test data and environments as needed
- Update documentation with new findings and changes

### Best Practices

- Follow naming conventions for test files
- Document all test changes in reports
- Maintain evidence for all test executions
- Regular review and update of test strategy

## 6. Support

- **Test execution**: Review test strategy and documentation
- **Technical issues**: Check automation framework setup in `pom.xml`
- **API testing**: Refer to Postman collections and global configurations
- **Reporting**: Examine reports in `Text_Reports/` and `Reports/` directories

## 7. Project Metadata

| Field | Value |
|---|---|
| Last Updated | 14/11/2025 |
| Version | 1.0 |
| Project Status | Active |
| Testing Phase | Comprehensive Test Cycle |
