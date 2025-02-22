# Assignment2

# Requirement

The system shall allow developers to categorize training questions separately from answers
The system shall provide an interface for developers to search and filter categorized training data.
The system shall analyze training data to detect biases.
The system shall provide recommendations to balance training data.
The system shall allow end users to provide feedback on training data quality.
The system shall allow users to validate the correctness of categorized data.

# Project Context
The AI Training Data Management System faces these main issues :
Developers find it hard to keep training questions and answers separate.
Ensuring that training data is fair and unbiased is challenging.
A lack of structure makes AI model training inefficient.
Handling large amounts of training data by hand takes too much time and can lead to mistakes
Stakeholders – AI Developers, Data Scientists, End Users (Customers)

## Assumption
1.	Developers need an organized way to store training questions and answers separately.
2.	Biased data negatively impacts AI accuracy and fairness.
3.	There is no automated system to check data balance and categorization.
4.	High-quality data improves AI model performance and reliability.

## Validation
method 1: What categories of training questions are most relevant for AI development?
method 2: How do developers currently organize and separate training questions from answers?
method 3: Do developers need predefined categories, or should they be customizable?
method 4: What challenges are faced in maintaining structured training data?
method 5:	Are there any existing tools being used for data validation?

# Preliminary tasks:

1. Developers – Training Question Categorization
Gather information on how training questions are currently managed.
Identify gaps in categorization and separation from answers.
Develop a structured format for categorizing training data.
Evaluate automation tools for data structuring.

2.Data Scientists – Bias Detection and Balancing
Collect data on how biases currently affect AI models.
Identify methods to measure and mitigate bias.
Standardize a framework for verifying balanced training data.
Implement monitoring tools for ongoing bias detection.

3. End Users/Customers – Quality Assurance and Feedback
Develop a feedback mechanism to report data quality issues.
Assess usability of structured training data for AI model training.
Refine data structuring based on user feedback.

# Functional Requirements

1. Developers – Training Question Categorization
REQ1_001: The system shall allow developers to categorize training questions separately from answers.
Task1_001: Implement a categorization system for training questions.
Task1_002: Develop an interface to manually or automatically categorize data.

REQ1_002: The system shall provide an interface for developers to search and filter categorized training data.
Task1_001: Implement a search and filter feature for training questions.
Task1_002: Allow exporting categorized data for external use.


2. Data Scientists – Bias Detection and Balancing
REQ2_001: The system shall analyze training data to detect biases.
Task2_001: Develop an algorithm to identify bias patterns in datasets.
Task2_002: Generate reports on detected biases.

REQ2_002: The system shall provide recommendations to balance training data.
Task2_001: Implement a data balancing module.
Task2_002: Provide visual insights into data distribution.

3. End Users/Customers – Quality Assurance and Feedback
REQ3_001: The system shall allow end users to provide feedback on training data quality.
Task3_001: Create a feedback form for reporting issues.
Task3_002: Implement a tracking system for reported concerns.

REQ3_002: The system shall allow users to validate the correctness of categorized data.
Task3_001: Develop a user validation process for categorized questions.
Task3_002: Provide an option to suggest category modifications.

# Non Functional Requirement

Scalability
REQ1_001: The system should be scalable to accommodate future growth in training data.
Task1_001: Design the system architecture to handle increasing volumes of training data.
Task1_002: Implement cloud-based storage solutions for scalability.

Reliability
REQ2_001: The system should ensure reliable performance with minimal downtime.
Task2_001:Implement automated backups and recovery mechanisms.
Task2_002:Monitor system health and alert on critical failures.

Compatibility
REQ3_001: The system should be compatible with a variety of data formats and external systems.
Task3_001: Support importing and exporting data in multiple formats (e.g., CSV, JSON, XML).
Task3_002: Develop APIs for integration with other AI development tools.

Maintainability
REQ4_001: The system should be easy to maintain and update over time.
Task4_001: Follow coding standards and best practices for maintainability.
Task4_002: Provide comprehensive documentation for developers and administrators.


