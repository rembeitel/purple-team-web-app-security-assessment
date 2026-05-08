Purple Team Web Application Security Assessment

Objective

The Purple Team Web Application Security Assessment project aimed to demonstrate and analyze common web application vulnerabilities in a controlled lab environment. The primary focus was to perform coordinated offensive and defensive testing against an intentionally vulnerable web application, with red team activities used to identify and exploit weaknesses and blue team analysis used to understand detection opportunities, attack visibility, and remediation strategies.

This project provided hands-on experience with web application security testing, HTTP request manipulation, vulnerability assessment, and purple team collaboration. As Team Lead and Red Team Lead, I directed team efforts, provided walkthroughs and troubleshooting support, and personally executed 12 attacks across SQL injection, cross-site scripting, and broken authentication categories.

Skills Learned

- Practical understanding of web application security testing concepts.
- Hands-on experience identifying and demonstrating SQL injection vulnerabilities.
- Hands-on experience identifying and demonstrating cross-site scripting vulnerabilities.
- Improved understanding of broken authentication and account lifecycle weaknesses.
- Proficiency in using Burp Suite to intercept, inspect, modify, and replay HTTP requests.
- Experience using Browser DevTools to analyze application behavior, requests, tokens, and client-side functionality.
- Practical exposure to Wireshark for reviewing network traffic and understanding attack visibility.
- Ability to document attack paths, findings, impact, and remediation recommendations.
- Improved understanding of how offensive activity can support blue team detection and alerting.
- Development of technical leadership, mentoring, troubleshooting, and team coordination skills.

Tools Used

- Burp Suite for intercepting, modifying, and replaying HTTP requests.
- Browser DevTools for inspecting client-side behavior, API requests, tokens, and application responses.
- Wireshark for network traffic analysis and packet review.
- OWASP Juice Shop / intentionally vulnerable web application lab environment for controlled testing.
- Web browser for interacting with the application and validating attack behavior.
- Documentation tools for organizing findings, screenshots, explanations, and remediation recommendations.

Steps

Ref 1: Project Environment Setup

This screenshot shows the vulnerable web application running in a controlled lab environment. The application was used as the target for red team testing and defensive analysis. All testing was performed in a safe, intentionally vulnerable environment for educational purposes.

[Insert screenshot here]

Ref 2: Burp Suite Proxy Configuration

This screenshot shows Burp Suite configured to intercept web traffic between the browser and the vulnerable application. Burp Suite was used to capture HTTP requests, analyze parameters, modify payloads, and replay requests during testing.

[Insert screenshot here]

Ref 3: HTTP Request Interception

This screenshot shows an intercepted HTTP request captured in Burp Suite. Reviewing requests allowed the team to understand how the application handled user input, authentication data, and API communication.

[Insert screenshot here]

Ref 4: SQL Injection Testing

This screenshot shows SQL injection testing being performed against a vulnerable input field or API endpoint. The objective was to demonstrate how unsanitized user input could alter backend database queries in the controlled lab environment.

[Insert screenshot here]

Ref 5: SQL Injection Result

This screenshot shows the application response after a successful SQL injection test. The result demonstrated how vulnerable query logic could expose or manipulate application data when proper input validation and parameterized queries are not used.

[Insert screenshot here]

Ref 6: Cross-Site Scripting Payload Testing

This screenshot shows cross-site scripting testing against a vulnerable field or endpoint. The purpose was to demonstrate how unsafe handling of user-controlled input could allow script execution in the browser.

[Insert screenshot here]

Ref 7: Cross-Site Scripting Execution

This screenshot shows the result of a successful XSS test in the lab environment. The finding demonstrated the importance of output encoding, input validation, and secure rendering of user-controlled data.

[Insert screenshot here]

Ref 8: Broken Authentication Testing

This screenshot shows testing against an authentication or account management workflow. The objective was to identify weaknesses in authentication logic, session handling, account lifecycle controls, or password management behavior.

[Insert screenshot here]

Ref 9: Broken Authentication Result

This screenshot shows the result of a broken authentication test. The finding demonstrated how weak authentication logic could potentially allow unauthorized access, improper account changes, or abuse of account management functionality.

[Insert screenshot here]

Ref 10: Browser DevTools Analysis

This screenshot shows Browser DevTools being used to inspect requests, responses, application storage, or client-side behavior. DevTools helped support testing by revealing how the application handled data in the browser.

[Insert screenshot here]

Ref 11: Wireshark Traffic Review

This screenshot shows network traffic captured or reviewed in Wireshark. This step helped connect offensive activity to defensive visibility by examining how web application attacks may appear in network traffic.

[Insert screenshot here]

Ref 12: Detection and SIEM Alert Discussion

This screenshot shows sample logs, alert logic, or detection notes created from the observed attack activity. The purpose was to explain how blue team analysts could detect suspicious web requests, abnormal authentication activity, or malicious payload patterns.

[Insert screenshot here]

Ref 13: Remediation Recommendations

This screenshot shows documented remediation recommendations for the vulnerabilities identified during the assessment. Recommendations included parameterized queries, server-side validation, output encoding, secure authentication controls, improved logging, and alerting on suspicious activity.

[Insert screenshot here]

Ref 14: Final Project Documentation

This screenshot shows the final project documentation or report structure. The documentation summarized the project objective, tools used, vulnerabilities tested, attack results, defensive lessons, and key takeaways.

[Insert screenshot here]
