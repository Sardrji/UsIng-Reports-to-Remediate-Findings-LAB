```markdown
# Use Reports to Remediate Findings

## Objective

The **Use Reports to Remediate Findings** lab focused on identifying, analyzing, and remediating cloud security vulnerabilities using **Google Cloud Security Command Center (SCC)**. The primary objective was to evaluate security findings, remediate misconfigured Cloud Storage bucket permissions, and verify compliance through security reports. This hands-on exercise strengthened my understanding of cloud security monitoring, vulnerability management, and compliance validation within Google Cloud.

### Skills Learned

- Understanding of Security Command Center (SCC) vulnerability management.
- Experience identifying and prioritizing cloud security findings.
- Knowledge of Cloud Storage bucket permission management.
- Ability to remediate public access vulnerabilities.
- Experience enabling uniform bucket-level access for secure permission management.
- Understanding of cloud compliance reporting and security validation.

### Tools Used

- Google Cloud Platform (GCP)
- Security Command Center (SCC)
- Google Cloud Storage
- Google Cloud Console
- CIS Google Cloud Platform Foundation Compliance Report

## Steps

### Step 1: Review Security Findings

Accessed **Security Command Center** to review active security findings and identify high and medium-risk vulnerabilities affecting the Cloud Storage bucket.

---

### Step 2: Analyze Compliance Report

Generated and reviewed the **CIS Google Cloud Platform Foundation** compliance report to identify non-compliant resources and prioritize remediation activities.

---

### Step 3: Remove Public Bucket Access

Removed the **allUsers** permission from the Cloud Storage bucket, eliminating anonymous public access and reducing the risk of unauthorized data exposure.

---

### Step 4: Enable Uniform Bucket-Level Access

Configured the storage bucket to use **Uniform Bucket-Level Access**, simplifying permission management and enforcing consistent access controls across all bucket objects.

---

### Step 5: Verify Compliance

Generated an updated compliance report through Security Command Center and confirmed that the previously identified vulnerabilities had been successfully remediated.

---

### Step 6: Complete the Lab

Successfully completed all required objectives, validated the remediation process, and achieved full completion of the cloud security assessment.

## Lab Completion

**Ref 1: Google Cloud Skills Boost Lab Completion**

![Lab Completion](images/lab-completion.png)

*Assessment Score: **100%** — Successfully identified, remediated, and validated cloud security findings using Google Cloud Security Command Center.*

## Key Takeaway

This lab provided practical experience in cloud vulnerability management using Google Cloud Security Command Center. Identifying security findings, remediating misconfigured storage resources, and validating compliance are essential responsibilities for cloud security analysts and SOC professionals working in production cloud environments.
```
