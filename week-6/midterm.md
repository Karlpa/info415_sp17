## Midterm
The website hw can be found at: http://midterm.r7.io/midterm/[NetID]

**You are NOT allowed to work together on this one**

### Part 1 - The Vulnerabilities
There are a number of vulnerabilities in the application including XSS, CSRF, SQLi, and business logic / tampering issues. Your job as the penetration tester is to find and document as many of these as you can. There may be more than I originally intended so I will just say that you should be able to find roughly 20 "issues" between those 4 categories.

Note: 
- The email functionality isn't hooked up so you wont receive the forgot password emails
- When counting issues:
	- Each parameter through which you can perform XSS is one issue
	- Each paramter vulnerable to SQLi is one issue
	- Each whole form vulnerable to CSRF is one issue
	- Each piece of functionality vulnerable to BL/Tampering is one issue

### Part 2 - The Report
You will write **one** report for each of the following vulnerability classes. Each report should contain all instances of that vulnerability found in the application:

- CSRF
- XSS
- SQLi
- BL/Tampering

Each report should be laid out in the following manner:

- Introduction: A paragraph describing the type of vulnerability, what it is, and why it's bad.
- Affected Areas: A one sentence description of where each instance of the vulnerability is located in the application. It should include a link to the vulnerable page and a brief description so someone could pinpoint the form/functionality/parameter quickly. Be descriptive but concise.
- Test Steps (for each instance of the vulnerability): These should be detailed step by step directions so someone could reproduce and verify each of the vulnerabilities. Include any tools needed, inputs that need to be sent, what the tester needs to do and in what order, and what the tester should see in the final result to know they proved the vulnerability. Screenshots are allowed, but necessary.
	- Note: 
		- Proving CSRF requires creating CSRF payload pages that exploit each of the forms (one page per vulnerable form)
		- Proving XSS requires a payload that will trigger an alert box
		- Proving SQLi requires more than just an error message. You have to demonstrate that user input is being parsed as SQL. So performing concatenation, math, or other SQL commands are required.
- Remediation: This should be at least a paragraph covering how the developer can mitigate the issue. It should also include a link to an external resource where they can read more or see code examples. It is a PHP application and a SQLite database - make sure the remediation is relevant.

.txt, .docx or .pdf format only. 12pt Calibri font with 1" margins (if using .docx or pdf).

### Due Date
This will be due Monday May 8th 2017 at 2:00pm (14:00)

### Note
No automated tools!!

Be careful not to corrupt your database, if you do I will have to wipe it back to the original state.

Don't mess with eachother's sites!

If you have questions please feel free to email myself or the TA.

**You are NOT allowed to work together on this one**