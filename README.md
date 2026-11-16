# Password Security Assessment with John the Ripper

**Course:** Week 3 Cybersecurity Lab  
**Topic:** Password auditing and hash analysis  
**Tool:** John the Ripper

## Abstract

This laboratory exercise introduces password auditing through the examination of password hashes with John the Ripper. It considers how password selection and storage practices influence credential security, and how authorized testing can inform defensive improvements. The exercise is educational and should be conducted only with data and systems for which explicit permission has been granted.

## 1. Introduction

Passwords remain a common means of authentication, but weak, reused, or predictable choices can expose accounts to risk. Password auditing provides a controlled way to evaluate credential strength and identify opportunities to improve security. This report presents a practical introduction to hash analysis and password auditing using John the Ripper, connecting the testing process with responsible security practices.

## 2. Objectives

This exercise aims to:

- Explain the role of password hashes in authentication systems.
- Introduce John the Ripper as a password-auditing tool.
- Examine how password strength affects resistance to guessing attempts.
- Interpret the results of an authorized, controlled audit.
- Identify defensive measures that reduce password-related risk.

## 3. Tools and Materials

- **John the Ripper:** Open-source software for password hash auditing.
- **Linux terminal:** Environment for running the authorized lab exercise.
- **Lab-provided sample data:** Hashes and other materials supplied for this exercise.
- **Documentation and reporting materials:** Used to record the procedure and observations.

Use only purpose-provided or explicitly authorized sample data. Do not test credentials belonging to other people or systems.

## 4. Methodology

The exercise follows a controlled assessment process:

1. **Authorization and preparation:** Confirm the scope, permissions, and source of all lab data.
2. **Data identification:** Inspect the provided sample and identify relevant hash-format information using the course materials and tool documentation.
3. **Audit:** Apply the instructor-defined, approved audit method with John the Ripper in the lab environment.
4. **Observation:** Record the test conditions and outcomes without including real or sensitive credentials in this repository.
5. **Evaluation:** Consider what the outcomes indicate about password selection and the defensive controls in scope.
6. **Reporting:** Summarize the results, limitations, and recommendations while preserving privacy and authorization boundaries.

## 5. Findings and Discussion

The exercise illustrates that password security depends on more than the presence of a hash. Predictable or commonly chosen passwords may be more susceptible to guessing, while stronger password practices can increase resistance. Hashing is an important safeguard for stored credentials, but its protective value also depends on using an appropriate password-storage scheme and sound system configuration.

Document the specific observations from the lab report here. Avoid making claims about results that were not observed in the exercise, and do not publish recovered passwords or sensitive credential data.

## 6. Recommendations

Based on the general lessons of password auditing, organizations should:

- Use long, unique passwords and discourage reuse.
- Block commonly used and known-compromised passwords where feasible.
- Store passwords with a modern, purpose-built password-hashing scheme configured appropriately.
- Enable multi-factor authentication where available.
- Limit access to credential data and protect audit results.
- Perform password audits only within a documented, authorized scope.
- Provide users with clear guidance on creating and managing credentials securely.

## 7. Limitations

Results from a classroom exercise depend on the sample data, configuration, and test conditions used. They should not be treated as a comprehensive assessment of a production system or as a guarantee of security. This README summarizes the topic and workflow; consult the accompanying report for the exercise-specific evidence and details.

## 8. Conclusion

This lab provides an introduction to password auditing with John the Ripper and demonstrates how controlled testing can support defensive security. Its central lesson is that robust password practices, secure password storage, and responsible assessment procedures work together to reduce credential-related risk.

## Appendices

Add the corresponding appendix image files to the repository at the paths below to display them. Replace the filenames if your uploaded images use different names.

### Appendix 1

![Appendix 1](images/appendix1.png)

### Appendix 2

![Appendix 2](images/appendix2.png)

### Appendix 3

![Appendix 3](images/appendix3.png)

## Ethical and Legal Use

This project is for educational purposes and authorized security assessment only. Use password-auditing tools solely with systems and data you own or are explicitly authorized to test. Handle all credentials and results as sensitive information.
