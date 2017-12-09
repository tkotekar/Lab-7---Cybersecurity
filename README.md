# Lab-7---Cybersecurity

Time spent: 7 hours spent total

User Stories
The following required problems are completed:

Required:
- Exploit 1:User Enum
- Exploit 2:XSS
- Exploit 3:XSS2

Optional:

- Bonus 1: Additional Exploit 1
- Bonus 2: Additional Exploit 2
 
## Walkthrough 
(gifs for walkthroughs are in the folder, I was unable to imbed them into the README)

Exploit 1: User Enum 
Version: WordPress 4.2
This vulnerability allows anyone the ability to enumerate a list of valid users names allowing an easier brute force attack for any hacker. This is a design issue.



Exploit 2: XSS
Version: WordPress 4.5.3
This vulnerability allows users with editor privileges to run XSS on WordPress with versions prior to 4.2.3. User can embed cross site scripting on their post. This can be used for privilege escalation if users viewed the pages


Exploit 3: XSS2
Version: WordPress 4.2
If an admin is tricked into loading a media file which goes overe the max file size then a file name will let execution of cross site scripting. This is becuase there is no file name sanitation






## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap]


## License

    Copyright [yyyy] [Tejaswi Kotekar]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
