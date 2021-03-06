---
layout: post
title: Code Regulation
---

Stories about data misuse and leaks seem to occur everyday. While this has contributed to a boom in security focused services, there is very little discussion going on about the engine that allows this to happen. Code, the terms which get interpreted into software that power the websites and apps that misuse and leak your data, are written by people. Those people are not held responsible for the results of their code, [unless they steal it](https://www.bloomberg.com/news/articles/2018-05-03/ex-goldman-sachs-programmer-s-conviction-upheld-by-n-y-court). There is also very little users of the code can rely on. Outside of the terms of service that users skim, or the occasional permissions prompt, there is very little in place currently to protect misuse. How can we improve this process, and is code auditing, regulation, or permit issuance the solution?

## All These Worlds are Yours

We currently live in an expansive time for code. Computers are cheap, and getting cheaper. Many of the top frameworks and services are free, open, and unrestricted. You can access the tools, like [VSCode](https://code.visualstudio.com/) for writing, [Github](https://github.com/) for versioning, and the respective platform for publishing in a way that wouldn't have been as easy or possible before. In addition, there are numerous platforms you can use to learn, reference, and revise. We are in a computing golden age.

This golden age is not without its faults. Many open source projects are being bought up and turned into paid subscription businesses. There is nothing inherently bad in this process, until you consider dependencies. Dependencies in code are when a code relies on another code to run properly. Without free open source alternatives, developers with less resources turn to closed centralized projects, or private code bases. As the number of code projects grows, the reliance on private code bases is expected to grow exponentially. This puts a generous amount of trust over the private organization to not misuse their power. In theory, if there were an issue with the private organization's code, this would propagate through multiple different code bases without any notice to these developers. This can, of course, occur with open source code bases, but the difference is that you could fix the issue or use a different version. With a closed centralized project, you are at the whim of that authority.

## Who Watches the Watchmen

There is no authority to punish overstepping centralized projects code bases. Code is also never the targeted body. In the US, the Supreme Court [heard a case](https://www.cnbc.com/2018/10/16/supreme-court-case-could-decide-fb-twitter-power-to-regulate-speech.html) against communications companies to regulate free speech, but this is not the same. In Europe, [GDPR](https://ec.europa.eu/commission/priorities/justice-and-fundamental-rights/data-protection/2018-reform-eu-data-protection-rules_en) has made strides in data protection, but once again, this doesn't solve the root cause and has been written off as an operating cost by many tech firms. While the end result is providing communications, there is nothing to regulate the code which systemizes these platforms. The only thing that comes in the way of the user getting taken advantage of is the internal security audits and compliance officers that are employed by these tech firms.

So are they doing enough? Code is deployed a tremendous amount of times a day across the world. We do not read about security or data breaches billions or trillions of times a day (despite it feeling like that). However, when it does effect us, the effects are as far reaching. This has recently been credited with [taking ransoms on individuals in 74 countries](https://www.wired.com/2017/05/ransomware-meltdown-experts-warned/), [leaking the data of six million websites](https://www.wired.com/2017/02/crazy-cloudflare-bug-jeopardized-millions-sites/), and [access to anyone's iOS audio](https://9to5mac.com/2019/01/28/facetime-bug-hear-audio/).

In practice, this is not always so straightforward to resolve. Code is complicated, and as code bases get larger, they are harder to abstract and fix. Many parts become interconnected in ways that the coders cannot possibly be expected to account. Further, it is hard to 'future-proof' code, as demands to keep up with advancing technology make it difficult to develop timeless code.

## Make or Break

To make 'good' code, there are many things to consider. As discussed, the code itself must not be dependent on any closed system code base. Assuming it is, further review of the dependencies is required. Secondly, the code must be written with purpose, and that purpose must be generally ethical. Third, the code must be able to, the best of its abilities, account for insecure issues. Fourth, there should be an effort to assure that future usage of the code is not in breach of the previous cases. Finally, if the code is removed, the remaining system should not be in breach of the previous cases.

Does this require regulation or permit issuance? Here I think it is fair to let the reader draw their own conclusions. As outlined above, I believe this is something which can be solved by internal or external audit. I am unaware how this audit would look, but believe the audit should be conducted externally of the organization. I also believe that regulation can impede this process, and permit issuance would arbitrarily limit access. These could then work to remove people who would already have a harder time from the community.

Code regulation is bound to occur at some point in the future. We should be mindful to make this regulation as inclusive as possible. Code can be misused in a number of ways, but gatekeeping can have long lasting negative effects. Once we consider the consequences of both sides, we can draw an informed conclusion on the future of code regulation.

<div class="message">
  Thanks to Kwabena Ohemeng, Paari Kandappan, Nikita Singareddy, and Reggie James.
</div>
