# Contributing to Open Data Ownership License (ODOL)

Thank you for your interest in contributing to the **Open Data Ownership License (ODOL)** project. We welcome contributions from developers, researchers, and privacy advocates who share our mission to promote transparent, responsible, and user-centric AI data practices.

## 🛠️ **How to Contribute**

### 1. **Understand the Mission**
ODOL is a legal and technical framework designed to:
- Protect user-generated content in AI applications.
- Ensure compliance with international privacy standards (GDPR, CCPA, PIPL, ISO/IEC 27701).
- Foster transparent, auditable AI data practices.

Please review the [ODOL License Document](core-license/LICENSE_ODOL) before contributing.

### 2. **Types of Contributions**
We welcome various types of contributions:
- **Code**: New features, optimizations, and bug fixes.
- **Documentation**: Improvements, corrections, or translations.
- **Research**: Proposals for new privacy methods or standards.
- **Legal Insights**: Recommendations for compliance with emerging regulations.

---

## ⚙️ **Contribution Workflow**

1. **Fork the Repository**
    - Click the "Fork" button on the GitHub page to create your copy.

2. **Clone the Repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/odol-license.git
   cd odol-core-license
   ```

3. **Create a New Branch**
    - Use a descriptive name for your branch:
   ```bash
   git checkout -b feature/new-feature-name
   ```

4. **Implement Changes**
    - Make sure your code adheres to our [Coding Standards](#-coding-standards).

5. **Commit Your Changes**
    - Follow the commit message guidelines below:
   ```bash
   git add .
   git commit -m "feat: add cosine similarity threshold validation"
   ```

6. **Push Your Branch**
   ```bash
   git push origin feature/new-feature-name
   ```

7. **Open a Pull Request (PR)**
    - Navigate to the original repository and click *"New Pull Request"*.
    - Provide a clear, detailed description of your changes.

8. **PR Review Process**
    - Our core maintainers will review the PR within 5 business days.
    - PRs must adhere to the project's code style guidelines.

---

## 🧠 **Coding Standards**

To ensure consistency and readability across the codebase, please follow these guidelines:

- **Language:** Python (for analytics and privacy models), TypeScript (Node.js for backend, React for UI).
- **Testing:** Write unit tests for all new functionality.
- **Documentation:** Comment significant code blocks and public functions.

### **Commit Message Format**
Use the [Conventional Commits](https://www.conventionalcommits.org/) specification:
- `feat:` – New features
- `fix:` – Bug fixes
- `docs:` – Documentation changes
- `test:` – Adding tests
- `chore:` – Maintenance tasks

---

## 🔐 **Privacy and Security Requirements**

Since ODOL addresses sensitive privacy concerns, adhere to the following security practices:

- **Data Anonymization:** Use ε-Differential Privacy with ε ≤ 0.3 for sensitive data.
- **Encryption:** Ensure data in transit is encrypted with TLS 1.3+ and data at rest with AES-256.
- **Audit Compliance:** Confirm alignment with ISO/IEC 27552 and IEEE P7003 standards.

PRs introducing privacy or security changes must include:
- Description of the change.
- Risk assessment of potential vulnerabilities.
- Testing results using tools like [ML Privacy Meter](https://github.com/privacytrustlab/ml_privacy_meter).

---

## ⚖️ **Legal Considerations**

- Contributors retain the copyright for their contributions but agree to license them under the terms of ODOL.
- Ensure that contributions do not introduce data that violates privacy regulations or contains proprietary content from third parties.
- The ODOL project adheres to GDPR, CCPA, and other international standards. If unsure about the legal impact of your changes, consult the project maintainers.

---

## 🤝 **Community Standards**

We strive to maintain a professional, inclusive, and collaborative environment.

**Code of Conduct:**
- Be respectful and constructive in communication.
- Provide actionable, detailed feedback during code reviews.
- Report any harmful behavior or security concerns immediately.

**Dispute Resolution:**
- Technical disputes are resolved through open discussion, with the final decision made by the core maintainers.
- For legal inquiries, contact us at [raman@worktif.com](mailto:raman@worktif.com).

---

## 🎯 **Get Started Now!**

- Fork the repo → Clone it → Code → Commit → PR → Celebrate! 🎉

Thank you for contributing to the **Open Data Ownership License (ODOL)**! 🚀

