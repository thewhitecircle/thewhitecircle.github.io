# TWC Official Website

<a href="https://twc1rcle.com/">Visit our website</a>

## Contribute

### How to add new resources

<a href="https://twc1rcle.com/resources/">twc1rcle/Resources</a>

* Resources can be added to the following file
    * https://github.com/thewhitecircle/thewhitecircle.github.io/blob/master/_data/resources.yml
* Valid **categories** :

```
Tools
Cheatsheets
Blogs
CTF
Vulnerabilities
Programming
Channels
Courses
```

* Each entry needs to have the following structure :

```yml
- title: TITLE HERE
  desc: SHORT DESCRIPTION
  category: CATEGORY
  tags: COMMA SEPARATED TAGS
  url: URL
```

**EXAMPLE**

```YML
- title: Server-side template injection
  desc: PortSwigger testing guide for SSTI
  category: Vulnerabilities
  tags: vuln, ssti, portswigger
  url: https://portswigger.net/web-security/server-side-template-injection
```

* Category needs to be **one** from the list above
* If your entry is not in the correct format your PR will be rejected