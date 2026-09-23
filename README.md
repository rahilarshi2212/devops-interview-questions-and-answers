# 🚀 DevOps Interview Questions & Answers

A practical, continuously growing **DevOps interview knowledge base** built from the supplied interview-question workbook.

## 🎯 What This Repository Solves

The original source is an Excel workbook containing questions collected from different companies and topic areas.

This repository converts that material into a maintainable GitHub knowledge base:

```text
Interview Question
       ↓
Canonical Question Bank
       ↓
Simple Explanation
       ↓
Interview-Ready Answer
       ↓
Follow-up Questions
       ↓
Company-wise reference
```

## ⭐ Important Design Decision: Single Source of Truth

**Answers are stored only once.**

`Company-Wise/` files are indexes that point to the canonical answer in `Question-Bank/`.

This means if the same Terraform question appears in TCS, Wipro and another interview, we do **not** maintain three copies of the answer.

Update the canonical question once → every company reference automatically points to the same answer.

## 📁 Repository Structure

```text
DevOps-Interview-Questions/
├── README.md
├── CONTRIBUTING.md
├── SOURCE-INVENTORY.md
├── Question-Bank/
│   ├── Azure.md
│   ├── Terraform.md
│   ├── CI-CD.md
│   ├── Git-GitHub.md
│   ├── Docker.md
│   ├── Kubernetes.md
│   ├── DevSecOps.md
│   ├── Monitoring-Observability.md
│   ├── Linux-Scripting.md
│   ├── AWS.md
│   ├── Scenario-Based.md
│   ├── Project-Behavioral.md
│   └── Misc.md
├── Company-Wise/
│   ├── TCS.md
│   ├── Wipro-L3.md
│   ├── Persistent.md
│   ├── NAB-Quess.md
│   ├── Impressico-Business-Solution.md
│   ├── IRIS-Software.md
│   ├── Allvy-Technology.md
│   └── All-Interview-Questions.md
├── Templates/
│   └── NEW-QUESTION.md
└── Reference-Notes/
```

## 📊 Current Workbook Coverage

- **466 unique company/interview questions** indexed.
- **8 interview/company sources** represented.
- Answers are explicitly labelled as either:
  - `Workbook source answer`
  - `Prepared interview answer`
  - `Needs personal/project-specific answer`

No answer is presented as a workbook source when the workbook did not actually provide it.

## 🧠 How to Use It

Start with the company:

```text
Company-Wise/TCS.md
```

Click the canonical answer for any question.

Or revise by technology:

```text
Question-Bank/Azure.md
Question-Bank/Terraform.md
Question-Bank/CI-CD.md
...
```

## 🔄 Future Questions — No Excel Maintenance Required

You do **not** need to maintain the original Excel workbook.

When a new interview question arrives, record:

```text
Company:
Question:
```

Then add it once to the appropriate canonical `Question-Bank` file and add a link from the company file.

Before adding it, check for an existing question so duplicates are not created.

## 🔐 Privacy

The workbook contained an `HR_Details` sheet with recruiter/contact information. That information is **not included** in this public repository.

## ⚠️ Interview Rule

For questions asking about your personal project, responsibilities, incidents, or tools you actually used, do not claim experience you did not have. Replace generic guidance with your real experience before using the answer in an interview.

