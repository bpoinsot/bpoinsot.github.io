### Lack of input sanitization on website.com{#top}

#### Summary{#summary}
* [Summary](#summary "Summary")
* [Introduction](#introduction "Introduction")
* [Description](#description "Description")
* [Impact](#impact "Impact")



#### Introduction{#introduction}
A security vulnerability was found on your website *sibestar.it*. Indeed, a lack of input sanitization has been found wich leads to a cross-site scripting vulnerabilitiy also known as XSS.

More details on this security issue are available below.

To keep your website safe and prevent exploitation of the vulnerability while it's unpatched, technical details are not publicly visible. Indeed, this page is only available using a special link and is protected by a password.

Despite our best efforts to make this report the more understandable as possible, feel free to get back at us for further details and assistance. In order to do so, please use this secured form. The more feedbacks we get, the clearer reports will be.



#### Description{#description}
XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user supplied data using a browser API that can create JavaScript. XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.

Here are some generic informations about likelihood and technical impact using the ratings scheme based on the OWASP informations regarding the vulnerability found on your website :

| EXPLOITABILITY | PREVALENCE | DETECTABILITY | IMPACT |
| ------------ | ------------ | ------------ | ------------ |
| Average | Very widespread | Average | Moderate |

If you want to know more about the OWASP Risk Rating Methodology used in the table below, plese check the [references section](#references "references section") of this report and specially [this one](#OWASP_Risk_Rating_Methodology "OWASP : Risk Rating Methodology"). You may also read this article regarding the threat risk modeling.



#### Impact{#impact}
Attackers send text-based attack scripts that exploit the interpreter in the browser. Almost any source of data can be an attack vector, including internal sources such as data from the database.

Attackers can execute scripts in a victim’s browser to hijack user sessions, deface web sites, insert hostile content, redirect users, hijack the user’s browser using malware, etc.

