---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

<!-- STOP! Please verify that the issue you're reporting is not a security issue before you continue.

Security issues must *never* be reported on GitHub Issues because GitHub Issues are public by default. A security issue, or vulnerability, may be any bug that represents a threat to the security of the ClamAV users or any issue that a malicious person could use to cause a Denial of Service (DoS) attack on a network service running ClamAV, such as a mail filter or file upload scanner.

Read our Security Policy to find security issue reporting instructions:
  https://github.com/Cisco-Talos/clamav/security/policy 
  
If you are unsure if your bug is a security issue, please report it as a security issue. -->

### Describe the bug

A clear and concise description of the bug or feature request. Do not report an issue to ask how to use ClamAV. Instead, visit our documentation and seek help from our clamav-users mailing list or our Discord chat server.

### ClamAV version, settings, and system details

On the command line, run this and replace this text with the output. This information will help the team identify possible triggers for your bug:
```bash
clamconf -n
```

### 3rd party signatures

Please tell us if you are using any unofficial signature databases, that is anything other than `main.cvd/cld`, `daily.cvd/cld`, and `bytecode.cvd/cld`

### How to reproduce the problem

Include specific steps needed to reproduce the issue.

If the issue is reproducible only when scanning a specific file, attach it to the ticket.

*Large Files*: The maximum size for file attachments on GitHub Issues is 25MB and the maximum size for images is 10MB. If the file is too big to mail it, you can upload it to a password protected website and send us the URL and the credentials to access it.

If your file must be kept confidential you can reach out on the [ClamAV Discord chat server](https://discord.gg/6vNAqWnVgw) to exchange email addresses and to share the zipped file or to share the zip password.

> **CAUTION**: Don’t forget to encrypt it if the file may be (or should be) detected as malware!
>
> On the command line, run:
> ```bash
> zip -P virus -e file.zip file.ext
> ```

### Screenshots

If applicable, add screenshots to help explain your problem.
