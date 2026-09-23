# Scenario Based — Canonical Interview Question Bank

This is the **single source of truth** for answers in this repository. Company-wise files link to these entries instead of duplicating answers.

<a id="scn-001"></a>
## SCN-001 — Deployment works in Dev but consistently fails in QA. How would you troubleshoot it?

**Asked In:** TCS Qustion
**Answer Type:** Workbook source answer

### Interview-Ready Answer
1. Initialize: Run terraform init to initialize the working directory and download necessary provider plugins. 2. Plan: Run terraform plan to generate an execution plan and review changes before applying. 3. Apply: Run terraform apply to apply the configuration and create/update resources. 4. Verify: Verify that resources are created/updated as expected using cloud provider tools. 5. Scale: Adjust configurations for scaling, and re-run terraform apply for changes.

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Workbook source answer matched from `Interview Questions-3.xlsx` (Terraform!45-49).

---

<a id="scn-002"></a>
## SCN-002 — Explain your real-time rollback strategy with an example.

**Asked In:** TCS Qustion
**Answer Type:** Workbook source answer

### Interview-Ready Answer
terraform taint aws_instance.example_instance

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Workbook source answer matched from `Interview Questions-3.xlsx` (Terraform!159-159).

---

<a id="scn-003"></a>
## SCN-003 — Have you ever rolled back a Production deployment?

**Asked In:** Wipro L3 Devops question
**Answer Type:** Prepared interview answer

### Interview-Ready Answer
A rolling deployment replaces application instances gradually so some capacity remains available during the rollout.

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Prepared from the concepts and terminology present in the supplied workbook, supplemented where necessary with standard DevOps interview wording.

---

<a id="scn-004"></a>
## SCN-004 — How did you perform the rollback?

**Asked In:** Impressico Businees Solution
**Answer Type:** Prepared interview answer

### Interview-Ready Answer
A rollback restores a known-good application or infrastructure version after a failed change. The method depends on the deployment strategy and may involve redeploying the previous artifact, switching traffic, or reverting configuration.

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Prepared from the concepts and terminology present in the supplied workbook, supplemented where necessary with standard DevOps interview wording.

---

<a id="scn-005"></a>
## SCN-005 — How did you troubleshoot it?

**Asked In:** Impressico Businees Solution, Wipro L3 Devops question
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-006"></a>
## SCN-006 — How do you promote code from Dev → QA → Production?

**Asked In:** Impressico Businees Solution
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-007"></a>
## SCN-007 — How is approval handled before production deployment?

**Asked In:** Impressico Businees Solution
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-008"></a>
## SCN-008 — How would you automate deployment validation and rollback?

**Asked In:** NAB & Quess Interview
**Answer Type:** Prepared interview answer

### Interview-Ready Answer
A rolling deployment replaces application instances gradually so some capacity remains available during the rollout.

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Prepared from the concepts and terminology present in the supplied workbook, supplemented where necessary with standard DevOps interview wording.

---

<a id="scn-009"></a>
## SCN-009 — How would you communicate with users/business during a production outage?

**Asked In:** TCS Qustion
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-010"></a>
## SCN-010 — How would you ensure secure communication between users, Bastion Hosts, and Production Servers?

**Asked In:** NAB & Quess Interview
**Answer Type:** Prepared interview answer

### Interview-Ready Answer
Azure Bastion provides managed RDP/SSH access to VMs through the Azure portal without requiring the target VM to have a public IP.

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Prepared from the concepts and terminology present in the supplied workbook, supplemented where necessary with standard DevOps interview wording.

---

<a id="scn-011"></a>
## SCN-011 — How would you perform infrastructure migration with minimal downtime?

**Asked In:** NAB & Quess Interview
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-012"></a>
## SCN-012 — How would you secure communication between a Bastion Host and a Production Server?

**Asked In:** NAB & Quess Interview
**Answer Type:** Prepared interview answer

### Interview-Ready Answer
Azure Bastion provides managed RDP/SSH access to VMs through the Azure portal without requiring the target VM to have a public IP.

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Prepared from the concepts and terminology present in the supplied workbook, supplemented where necessary with standard DevOps interview wording.

---

<a id="scn-013"></a>
## SCN-013 — How would you standardize Dev, QA, and Production environments?

**Asked In:** TCS Qustion
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-014"></a>
## SCN-014 — Is this application deployed in production?

**Asked In:** Impressico Businees Solution
**Answer Type:** Prepared interview answer

### Interview-Ready Answer
Azure Application Gateway is a Layer 7 web traffic load balancer. It supports HTTP/HTTPS routing features such as host/path-based routing, TLS termination, health probes, and WAF integration.

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Prepared from the concepts and terminology present in the supplied workbook, supplemented where necessary with standard DevOps interview wording.

---

<a id="scn-015"></a>
## SCN-015 — Production database becomes slow. What will you check?

**Asked In:** Wipro L3 Devops question
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-016"></a>
## SCN-016 — Production deployment succeeded, but the application is unavailable. How would you troubleshoot it?

**Asked In:** TCS Qustion
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-017"></a>
## SCN-017 — Production Issues

**Asked In:** Impressico Businees Solution
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-018"></a>
## SCN-018 — Production Scenarios

**Asked In:** Wipro L3 Devops question
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-019"></a>
## SCN-019 — Tell me about a Production Incident you handled.

**Asked In:** Wipro L3 Devops question
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-020"></a>
## SCN-020 — What is the most challenging production issue you have faced?

**Asked In:** Impressico Businees Solution
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-021"></a>
## SCN-021 — What networking security measures would you implement for Production workloads?

**Asked In:** NAB & Quess Interview
**Answer Type:** Needs personal/project-specific answer

### Interview-Ready Answer
This is an experience- or scenario-specific question. The workbook contains the question, but it does not contain enough source material to provide a truthful personal answer. Use your actual project details and explain the steps you personally performed.

### Simple Explanation
This question depends on your actual project, responsibilities, or incident. Do not memorize a generic story; answer with what you personally did, why you did it, and the result.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
The supplied workbook contains the question but does not provide enough source material for a truthful personal/project-specific answer.

---

<a id="scn-022"></a>
## SCN-022 — What was your rollback strategy?

**Asked In:** Impressico Businees Solution
**Answer Type:** Prepared interview answer

### Interview-Ready Answer
A rollback restores a known-good application or infrastructure version after a failed change. The method depends on the deployment strategy and may involve redeploying the previous artifact, switching traffic, or reverting configuration.

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Prepared from the concepts and terminology present in the supplied workbook, supplemented where necessary with standard DevOps interview wording.

---

<a id="scn-023"></a>
## SCN-023 — What would be your rollback strategy after a failed production deployment?

**Asked In:** TCS Qustion
**Answer Type:** Prepared interview answer

### Interview-Ready Answer
A rollback restores a known-good application or infrastructure version after a failed change. The method depends on the deployment strategy and may involve redeploying the previous artifact, switching traffic, or reverting configuration.

### Simple Explanation
Explain the concept in one or two sentences first, then connect it to how you would use or troubleshoot it in a real DevOps environment.

### Follow-up Questions
- What would you check first?
- How would you communicate the incident?
- What would you do to prevent recurrence?

### Source / Note
Prepared from the concepts and terminology present in the supplied workbook, supplemented where necessary with standard DevOps interview wording.

---
