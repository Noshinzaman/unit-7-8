
# unit-7-8

# Project 7 - WordPress Pentesting

Time spent: **X** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

### 1. (Required) Vulnerability Name or ID
  - [x] Summary: 
    - Vulnerability types:
    - Tested in version: this exploit was tested in verion 4.2
    - Fixed in version: Fixed in the current version
  - [x] GIF Walkthrough: 
  - [x] Steps to recreate: The way to recreate is to post a comment in admin console and then after admin approved- I was able to post a _malicious_ comment
  - [x] Affected source code:  would need to log in into admin area and inject malicious code `<script>alert('XSS!');</script>`

  - ![unit7-8(3)](https://user-images.githubusercontent.com/89932088/140195220-ce466051-c9c0-46ac-9f20-c9d5c2b739d3.gif)
### 2. (Required) Vulnerability Name or ID
  - [x] Summary: 
    - Vulnerability types:
    - Tested in version:this exploit was tested in verion 4.2
    - Fixed in version: Fixed in the current version
  - [x] GIF Walkthrough: 
  - [x] Steps to recreate: you can edit it and add it
  - [x] Affected source code:
  ![unit7-8(1)](https://user-images.githubusercontent.com/89932088/140191854-7b496f1d-ee8f-4db2-8a8e-744b9105356c.gif)
### 3. (Required) Vulnerability Name or ID
  - [x] Summary: 
    - Vulnerability types:
    - Tested in version:this exploit was tested in verion 4.2
    - Fixed in version: Fixed in the current version
  - [x] GIF Walkthrough: 
  - [x] Steps to recreate: you can edit it and add it
  - [x] Affected source code:inject malicious code `<a href="[caption code=">]</a><a title=" onmouseover=alert('exploit!')".link</a>`

![unit7-8(2)](https://user-images.githubusercontent.com/89932088/140195266-c2644227-ac64-4475-9ac6-6b44645df071.gif)

### 4. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
### 5. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

For each exploit, provide the following information in the README.md:

    A small writeup indicating the steps you used to recreate
    The types / classes of vulnerabilities involved and any related CVE identifiers
    Identify affected versions and patches
    Links to the source code, where possible
    A screen cap


## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


