# CS305-Artemis-Financial-Practices-for-Secure-Software-Report
Artemis Financial Practices for Secure Software Report (Project Two)
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The Client is Artemis Financial.  They are a financial consulting company that needs help implementing security for their web interface which stores client data and financial information.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I implemented an encryption algorithm to protect transmitted data, generated self signed certifactes to ensure that the client was connecting to the correct site, and checked the code against known vulnerabilities.  The importance of the code security is that it protects the clients data which is essential to the company given that the data is financial in nature.

What about the process of working through the vulnerability assessment did you find challenging or helpful?

The dependency is check is helpful because it is automated and greatly reduced any research I would have otherwise needed to perform.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

I converted the http protocol to https.I use that same strategy in the future.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

compiling the code determined it's functionality.  I then ran the dependency check again to see if any new vulnerabilities were flagged.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

the cdertificate generation was helpful, but I'm interested in finding aleternative methods of pperforming that task because I used a java tool in windows.  I prefer to do my coidng on a Mac.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

The encryption algrothim is the only portion of this assignment that I would consider showing a potential employer.
