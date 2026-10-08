# Healthcare Role-Based Access Control (RBAC) Project

## Objective
Learn how Identity and Access Management (IAM) uses job roles to determine which employees should have access to different healthcare systems.

## Scenario
I created a fictional healthcare facility called Purple Care Medical Center with three employees: a physician, a medical assistant, and a receptionist.

## Access Control Plan
| Role | Patient Charts | Scheduling | Medication Orders |
|---|---|---|---|
| Physician | Allowed | Allowed | Allowed |
| Medical Assistant | Allowed | Allowed | Not Allowed |
| Receptionist | Not Allowed | Allowed | Not Allowed |

## Security Concept
The principle of least privilege means giving users only the access necessary to perform their approved job responsibilities.

## Tools Used
- GitHub
- Markdown
- Fictional healthcare scenario

## Project Type
Conceptual IAM exercise. No live accounts or production systems were configured.

## What I Learned
- The importance of only giving users access based on necessity to complete job responsibilities.
- It's best to give least privileges versus too much access.
- Always double check myself before accepting selecting privileges to make sure there are no mistakes.

## Future Improvements
Practice implementing role-based security groups and user accounts in an authorized Windows Server lab.
