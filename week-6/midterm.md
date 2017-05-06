## Midterm
The website hw can be found at: http://midterm.r7.io/midterm/[NetID]

*You are NOT allowed to work together on this one*

### Part 1 - The Vulnerabilities
There are a number of vulnerabilities in the application including XSS, CSRF, SQLi, and business logic or tampering issues. Your job as the penetration tester is to find and document as many of these as you can. There may be more than I originally intended so I will just say that you should be able to find roughly 20 "issues" between those categories.

Note: 
- The email functionality isn't hooked up so don't worry about it.
- When counting issues - each parameter vulnerable to XSS is one issue, each paramter vulnerable to SQLi is one issue, each whole form vulnerable to CSRF is one issue, each piece of functionality vulnerable to BL/Tampering is one issue

### Part 2 - The Report
You will write *one* report for each of the following vulnerability classes:

- CSRF
- XSS
- SQLi
- Business logic / tampering issues

Each report should be laid out in the following manner:

- Introduction: A paragraph describing the type of vulnerability, what it is, and why it's bad.
- Affected Areas: A one sentence description of where each instance of the vulnerability is located in the application. It should include a link and a brief description so someone could pinpoint the form/functionality/parameter. Be descriptive but concise.
- Test Steps: These should be detailed step by step directions so someone could reproduce and verify the vulnerability themselves. Include any tools needed, inputs that need to be sent, what the tester needs to do and in what order, and what the tester should see in the final result to know they proved the vulnerability. Screenshots are allowed.
	- Note: proving CSRF requires you to create CSRF payload pages that exploits each of the forms (one page per form)
- Remediation: This should be at least a paragraph and a link to an external resource advising the application owner on how they can mitigate the issues properly. It is a PHP application and a SQLite database - make sure the remediation is relevant.

Docx or PDF format only. 12pt Calibri font with 1" margins.

### Due Date
This will be Monday May 8th 2017 at 2:00pm (14:00)

### Note
No automated tools!!

Be careful not to corrupt your database, if you do I will have to wipe it back to the original state.

Don't mess with eachother's sites!

If you have questions please feel free to email myself or the TA.

*You are NOT allowed to work together on this one*