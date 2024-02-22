<p align="center">
Guard your services against spam and abuse with our extensive list of disposable email domains.
<br />
<a href="https://empress.eco/">Explore the Project</a>
·
<a href="https://grow.empress.eco/">Get Support</a>
·
<a href="https://github.com/empress-eco/disposable-email-domains/issues">Report a Bug</a>
·
<a href="https://github.com/empress-eco/disposable-email-domains/issues">Request a Feature</a>
</p>

## 📚 About The Project

Disposable Email Domains is a comprehensive repository that provides a list of disposable and temporary email address domains frequently used for spam or abuse. Our tool empowers service providers by allowing them to shield their platform against potential spam and abuse.

### 🌟 Key Features
- An exhaustive list of disposable and temporary email domains
- Regular updates for accuracy
- An allowlist of domains often incorrectly identified as disposable
- Easy integration into existing systems
- Sample codes in Python, PHP, Ruby on Rails, NodeJs, and C#

## 🛠️ Technical Stack and Setup Instructions

### Prerequisites
A fundamental understanding of programming and the knowledge of how to incorporate code into existing systems is required to use this project.

### Installation
This project does not require a conventional installation. However, you can clone this repository and utilize it in your project as follows:

```sh
git clone https://github.com/empress-eco/disposable-email-domains.git
```

## 🚀 Usage
The repository includes a `disposable_email_blocklist.conf` file containing the list of disposable email domains. Incorporate this file in your project to verify if a given email is disposable.

Here's a simple Python example:

```python
blocklist = ('disposable_email_blocklist.conf')
blocklist_content = [line.rstrip() for line in blocklist.readlines()]
if email.split('@')[1] in blocklist_content:
    message = "Please enter your permanent email address."
    return (False, message)
else:
    return True
```

For additional examples in other languages, kindly refer to the README in the repository.

## 🤝 Contribution Guidelines
We warmly welcome contributions! If you have a domain to add or would like to request the removal of a domain, please create a pull request. If you're adding more than one new domain, kindly provide a source where one can generate a disposable email address using that domain for verification.

## 🗒️ License and Acknowledgements

### License
This project is licensed under the MIT License. Your contributions will also be licensed under the MIT License.

### Acknowledgements
Special thanks to the Empress Community for providing the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support. 

Also, we would like to express our gratitude to [@di](https://github.com/di) for making this project available as a PyPI module and to our contributors [@txt3rob](https://github.com/txt3rob), [@deguif](https://github.com/deguif), [@pjebs](https://github.com/pjebs), and [@Wruczek](https://github.com/Wruczek) for their valuable contributions in PHP.