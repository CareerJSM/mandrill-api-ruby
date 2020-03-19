# mandrill-api-ruby
Fork of official official Mandrill API gem https://bitbucket.org/mailchimp/mandrill-api-ruby

The PR to update the `json` dependancy has been open but never merged since 2016 https://bitbucket.org/mailchimp/mandrill-api-ruby/pull-requests/8

Version 1.0.55 of this repo includes the required update to address the security advisory CVE-2020-10663 https://www.ruby-lang.org/en/news/2020/03/19/json-dos-cve-2020-10663/

```
Name: json
Version: 1.8.6
Advisory: CVE-2020-10663
Criticality: Unknown
URL: https://www.ruby-lang.org/en/news/2020/03/19/json-dos-cve-2020-10663/
Title: json Gem for Ruby Unsafe Object Creation Vulnerability (additional fix)
Solution: upgrade to >= 2.3.0
```
