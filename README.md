# **AWS Textract**
### Study of Existing System & Its Limitations
The existing system relied on manual data extraction from PDF files, which was time-consuming and
prone to errors. Lack of automation resulted in inefficient data processing and limited scalability.
The manual approach also hindered data accessibility and hindered decision-making processes. 
### Requirement of New System
The new system aimed to address the limitations of the existing manual approach by implementing
AWS Textract. The requirements for the new system were identified as follows:
### Functional Requirements
- Extract text and data from PDF files
- Convert the extracted information into CSV format
- Support asynchronous processing for handling large PDF files
- Enable efficient storage and retrieval of extracted data
### Non-functional Requirements
- Scalability: Ability to handle large volumes of PDF files
- Performance: Quick and accurate extraction of data
- Reliability: Ensure data integrity and availability
- Security: Implement appropriate access controls and data protection measures
### Hardware Requirements
As the project was implemented using AWS services, specific hardware requirements were not
applicable. The infrastructure was provisioned and managed by AWS.
### Software Requirements
The software requirements for the project included:
- Amazon Web Services (AWS) account
- AWS CLI (Command Line Interface) for configuring AWS resources
- AWS SDKs or APIs for interacting with AWS services
- Python programming language for code development
- IDE (Integrated Development Environment) for writing and testing cod
### AWS Services
- AWS Lambda
- AWS Texract
- AWS CLI
- AWS SDK
### Flowchart
![image](https://github.com/Jaylakhani37/AWS-Texract/assets/88767949/9e91acd0-5302-44b5-bec6-63c0eedd14c3)

### Data Dictionary
- PDF File: The input file containing the data to be extracted.
- CSV File: The output file format for storing the extracted data.
- S3 Bucket: Amazon Simple Storage Service bucket for storing input and output files.
- Lambda Function: AWS Lambda function responsible for triggering the extraction process.
- AWS Textract: The service used for extracting text and data from PDF files.

### Test Cases
- Case 1 :
	- Input: PDF files of 10 Pages
	- Expected output : CSV of that PDF with all the pages processed Actual output : AS Expected
- Case 2 :
	- Input: PDF files of 1000 Pages
	- Expected output : CSV of that PDF with all the pages processed Actual output : AS Expected
- Case 3 :
	- Input: 10 PDF files of different number of Pages
	- Expected output : CSV of all that PDF with all the pages processed Actual output : AS Expected
### Implementation 
- S3 Buckets for Input and Output

![image](https://github.com/Jaylakhani37/AWS-Texract/blob/main/Implementation-Images/1.png)

- Lambda Function Basic information

![image](https://github.com/Jaylakhani37/AWS-Texract/blob/main/Implementation-Images/2.png)
- Adding Triggers of S3
 
![image](https://github.com/Jaylakhani37/AWS-Texract/blob/main/Implementation-Images/3.png)
- IAM Permission For Lambda
 
![image](https://github.com/Jaylakhani37/AWS-Texract/blob/main/Implementation-Images/4.png)
- Entering Input PDF
 
![image](https://github.com/Jaylakhani37/AWS-Texract/blob/main/Implementation-Images/5.png)
- Getting Output
 
![image](https://github.com/Jaylakhani37/AWS-Texract/blob/main/Implementation-Images/6.png)
- Getting CSV as output
 
![image](https://github.com/Jaylakhani37/AWS-Texract/blob/main/Implementation-Images/7.png)
- Timeout settings

![image](https://github.com/Jaylakhani37/AWS-Texract/blob/main/Implementation-Images/8.png)

### References
- [AWS Texract](https://aws.amazon.com/textract/ "AWS Texract")
- [Stack Overflow](https://stackoverflow.com/ "Stack Overflow")
- [ChatGPT](https://chat.openai.com/ "ChatGPT")
