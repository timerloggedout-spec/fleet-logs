# Unit 047 — Theory: How Do You Handle Security Requirements Like SSH and GPG Keys?
- URL: https://www.freecodecamp.org/learn/relational-databases-v9/lecture-introduction-to-git-and-github/how-do-you-handle-security-requirements-like-ssh-and-gpg-keys
## Questions (verbatim, signed-in capture 2026-11-01)
- Q1: What is the fundamental difference between private and public keys in SSH and GPG key pairs? — The private key is longer than the public key. / The private key stays on your local machine while the public key is shared. / The public key is used to encrypt data while the private key decrypts it. / The private key expires after a certain time period.
- Q2: Which command would you use to enable automatic signing of all commits with your GPG key? — git config --global gpg.autosign true / git config --global commit.sign always / git config --global commit.gpgsign true / git --enable-auto-signing
- Q3: What's required to set up SSH key signing for Git commits on GitHub? — Only upload your public SSH key to GitHub. / Set the signing format to SSH and configure your signing key path. / Generate a special SSH signing key separate from your regular SSH key. / Enable a special GitHub feature in your account settings.
## Expected keys (advisory)
- Q1 The private key stays on your local machine while the public key is shared. · Q2 git config --global commit.gpgsign true · Q3 Set the signing format to SSH and configure your signing key path.
