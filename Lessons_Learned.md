Lessons Learned – Parabank QA Project 

1. Introduction 

This document summarizes the lessons learned during the execution of the Parabank QA project. The goal is to highlight successes, challenges, and recommendations that can improve future QA engagements. 

2. Successes 

Clear documentation (PRD, RAD, Test Plan, Test Cases, Traceability Matrix, Defect Report, and Test Summary Report) ensured proper alignment with requirements. 

Systematic execution of functional (R1–R12) and non-functional (NFR1–NFR5) test cases provided wide coverage. 

Collaborative step-by-step GitHub integration improved version control and traceability of QA deliverables. 

Identified and documented defects effectively, leading to better system quality insights. 

3. Challenges 

Some mismatches between PRD requirements and implemented system functionality (registration flow and account lock behavior). 

Non-functional testing (performance, concurrency) required manual workarounds, slowing execution. 

GitHub workflow initially caused minor confusion around file tracking/untracked files. 

Inconsistent error handling in Parabank led to test failures that were not properly user-friendly (vague system error messages). 

4. Key Takeaways 

Requirements traceability (linking R1–R12 and NFR1–NFR5 to test cases) is critical in ensuring no requirement is left untested. 

Early validation of Test Environment setup would reduce wasted time debugging environmental vs. functional issues. 

Proper status color coding in test execution results made reporting and analysis faster and clearer. 

Incremental commits to GitHub proved more efficient than batching large sets of files. 

5. Recommendations for Future Projects 

Automate more test scenarios with tools like Selenium or JMeter for faster execution and better coverage. 

Establish a CI/CD pipeline to integrate test automation into GitHub workflows. 

Improve documentation structure by maintaining QA deliverables in dedicated folders. 

Enhance defect categorization with severity, priority, and reproducibility notes to streamline triage. 

6. Conclusion 

The Parabank QA project provided valuable insights into both functional and non-functional quality aspects of the system. By applying the lessons learned, future QA efforts can be made more efficient, accurate, and collaborative. 