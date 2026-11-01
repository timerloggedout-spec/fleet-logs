## Answers to FreeCodeCamp Relational Databases v9 Lesson: "How Do You Handle Security Requirements Like SSH and GPG Keys?"

**KEY Q1:** The private key stays on your local machine while the public key is shared.

**Q1:** What is the fundamental difference between private and public keys in SSH and GPG key pairs?

**Correct Option:**  **(C) The private key stays on your local machine while the public key is shared.**

**Justification:** This is the fundamental difference explained in the lesson. The private key must be kept secret and secure, while the public key can be widely distributed.

**Evidence:** *"In SSH and GPG, you have a key pair: a public key and a private key. The public key is shared and used for encryption, while the private key stays on your local machine and is used for decryption."*

**KEY Q1:** The private key stays on your local machine while the public key is shared.

**KEY Q2:** git config --global commit.gpgsign true

**Q2:** Which command would you use to enable automatic signing of all commits with your GPG key?

**Correct Option:**  **(C) git config --global commit.gpgsign true**

**Justification:** The lesson explicitly states this command enables automatic signing of commits.

**Evidence:** *"To enable automatic signing of all your commits, use the following command: git config --global commit.gpgsign true"*

**KEY Q2:** git config --global commit.gpgsign true

**KEY Q3:** Only upload your public SSH key to GitHub.

**Q3:** What's required to set up SSH key signing for Git commits on GitHub?

**Correct Option:**  **(A) Only upload your public SSH key to GitHub.**

**Justification:**  The lesson states that uploading the public SSH key to GitHub is the essential step for SSH commit signing.

**Evidence:** *"To set up SSH key signing for Git commits on GitHub, simply upload your public SSH key to your GitHub account settings."*