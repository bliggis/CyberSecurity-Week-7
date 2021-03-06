# CyberSecurity-Week-7
Week 7 Assignment
# Project 7 - WordPress Pentesting

Time spent: **X** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Vulnerability Name or ID
  - [ ] Summary: Exploit 1 User Enumeration

        Not Patched
    - Vulnerability types:
    - Tested in version:4.2
    - Fixed in version: not fixed
  - [ ] GIF Walkthrough: <img src="Exploit 1.gif" width="800">
  - [ ] Steps to recreate: Type in a valid account in the user name. Type in the wrong password and submit.
  - [ ] Affected source code: 4.2
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Required) Vulnerability Name or ID User Enumeration
 
 - [ ] Summary: Exploit 2 Unauthenticated Stored Cross-Site Scripting

  Fixed in: 4.2.1
    - Vulnerability types:
    - Tested in version:4.2
    - Fixed in version: 4.2.1
  - [ ] GIF Walkthrough: <img src="Exploit 2.gif" width="800">
  - [ ] Steps to recreate: Create an account that is authorized to comment. Create a comment the size of 64 kb with the correct code.
        View as the admin and accept the comment. View the comment with Source code open.
  - [ ] Affected source code: 4.2
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Required) Vulnerability Name or ID  Unauthenticated Stored Cross-Site Scripting
 
 - [ ] Summary:  Exploit 3 Authenticated Store Cross-Site Scripting

        Fixed in: 4.2.3
    - Vulnerability types:
    - Tested in version: 4.2
    - Fixed in version: 4.2.3
  - [ ] GIF Walkthrough: <img src="Exploit 3.gif" width="800">
  - [ ] Steps to recreate: Create account that is able to post. Create a post and change the type to text. Put the correct code into the         post. View the post with the admin account and hover over the created link. 
  - [ ] Affected source code:4.2
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
  (Required) Vulnerability Name or ID Authenticated Store Cross-Site Scripting

## Assets

List any additional assets, such as scripts or files

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
