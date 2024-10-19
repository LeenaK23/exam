# Understanding AWS

Amazon Web Services (AWS) is an online cloud computing user-friendly platform offered by Amazon. The platform comprises a combination of:

- Infrastructure as a Service (IaaS)

- Platform as a Service (PaaS)

- Software as a Service (SaaS)

Cloud computing uses the Internet to deliver computing services. Whether a small startup or a large organization, AWS helps you innovate and save costs without compromising productivity. Customers only need to pay for the service they use.

**Key Highlights**

AWS offers a broad spectrum of services in the form of building blocks. These building blocks are used to create, deploy, operate, and manage different applications in the cloud. The services comprise,

- Computing

- Database Storage

- Programming models

- Networking

- Security tools

- Developer tools

- Management tools

With the growing digitalization, communication via email has gained prime importance. Amazon Simple Email Service (SES) is one of the cloud-based services that provides an email platform. To use this service, you must have a valid AWS account and access to AWS Management Console. Through the AWS console, you can select SES.  

## How to Use Amazon SES

Amazon SES is used to send and receive emails. You can send transactional, correspondence, and marketing emails. SES lets you send email in 3 ways,

- Using Amazon SES console: To manage the sending activity and send test emails.

- Amazon SES Simple Mail Transfer Protocol (SMTP) interface: To send bulk emails.

- Using the Amazon SES API: To send bulk emails.

**Sending emails through SES**

	! [ses](https://vscode.dev/github/LeenaK23/exam/blob/main/New%20Screenshot%202024-10-09%20222559.png)
	
	
The sender (customer application) makes an email request to SES. This email request may be for one or multiple recipients. SES accepts the request upon validation.

- If the request is successful, SES sends a successful response to the sender.

- If the request fails, SES sends an error message to the sender and drops the email.

When the sender's request to SES is successful, SES sends the message to the recipient's receiver (ISP) via the Internet within a few seconds.

- The ISP delivers the message successfully to the recipient. The recipient may either accept the message or mark it as spam. If SES has a feedback loop setup with ISP, the recipient can register a complaint if it is a spam message. SES then forwards this complaint notification to the sender.

- The ISP delivers a bounce notification to SES when the receiver’s email id is invalid. The same notification is forwarded to the sender.

AWS SES is a versatile cloud service that delivers a complete solution to increase efficiency and productivity and improve the scalability of your business.