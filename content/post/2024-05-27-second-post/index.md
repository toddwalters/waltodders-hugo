---
title: It's Been A While
date: 2024-05-27T10:56:18-04:00
tags: ["aws", "azure", "gcp", "cloud", "genai", "llm", "apple"]
---

Welp seems like I failed at actually maintaining this site once I stood it up at the end of the year last year.  I did manage to move my resume details into the [About](https://waltodders.com/page/about/) Section of this site and retire the resume site that I originally stood up as part of participating in the Cloud Resume Challenge. Outside of that update things have been totally stagnate here.

I have decided to at least start capturing the articles I have come across that have interested me and any thoughts that come to mind reflecting on the content of the articles. I tried to break these articles up into various categories, but actually they all could fit into every one of these categories.

## **Cloud Service Providers**

- [ep113 AWS Services Cheat Sheet](https://blog.bytebytego.com/p/ep113-aws-services-cheat-sheet)

    I subscribe to the free version of the [Byte Byte Go Substack Newsletter](https://blog.bytebytego.com) and it frequently delivers some great diagrams that break down various cloud developer topics. In the case of this particular instance of the newsletter, it actually delivers both an [AWS Services Cheat Sheet](https://blog.bytebytego.com/i/144946057/aws-services-cheat-sheet) and an [Azure Services Cheat Sheet](https://blog.bytebytego.com/i/144946057/azure-services-cheat-sheet).  I am sure similar cheat sheets have been developed elsewhere, but I like the way they breakdown and represent each of services within each of the clouds.  It also contains an [API Designs Cheat Sheet](https://blog.bytebytego.com/i/144946057/a-cheat-sheet-for-api-designs) and a [How do computer programs run?](https://blog.bytebytego.com/i/144946057/how-do-computer-programs-run) diagram.  
  
- [Amazon cloud boss Matt Garman inherits business under pressure to keep pace in AI](https://www.cnbc.com/2024/05/23/amazons-new-cloud-boss-inherits-a-business-at-crossroads-over-ai.html)

    This article was surfaced for me from [Techmeme Newsletter](https://techmeme.com/newsletter) and [TLDR Newsletter](https://tldr.tech/).  I thought this was a good write-up on CNBC about the current challenges that AWS is facing between retracting annual growth rates based on a shift to more conservative spending by businesses on IT and cloud services and the AI race as they try to address their increasing gap in that space as compared to Microsoft with it partnership with OpenAI and Google and its Gemni GenAI model.

- [Google Cloud Platform Blog](https://cloud.google.com/blog/products/infrastructure/details-of-google-cloud-gcve-incident)

    This was Google and GCP official response to issue associated with GCP deleting the entire GCP infrastructure of a $135 billion Australian pension fund called Unisuper affecting its 647,000 customers—many of them retirees whose life savings are tied up in the company.  The communication optics around this whole situation was very strange, Google and GCP were  silent on this issue from the time Unisuper announced the issue on May 2nd until this official response posed on May 24th.  Several days prior to this coming out, Forrest Brazeal on his [Good Tech Things Blog](https://newsletter.goodtechthings.com/) in his post titled [A tale of two clouds customer obsession vs customer obfuscation](https://newsletter.goodtechthings.com/p/a-tale-of-two-clouds), had an interesting take on the situation and the different way in which AWS handles issues like this versus how Google and GCP handled this issue.

## **AI/ML/DL/GenAI**

- [The Great AI Challenge: We Test Five Top Bots on Useful, Everyday Skills](https://www.wsj.com/tech/personal-tech/ai-chatbots-chatgpt-gemini-copilot-perplexity-claude-f9e40d26)

    This article was surfaced for me from the [Techmeme Newsletter](https://techmeme.us14.list-manage.com/track/click?u=94ccd3ae223561415b05892ab&id=cd0c767c5a&e=f6e39c3e76). It is from the *Wall Street Journal* is is *behind their paywall*, but I thought it was interesting comparison of some of the most popular model.  Most interesting to me was how bad Microsoft Copilot performed in the vast majority of these tests, however the caveat is that this comparison happened before Microsoft had incorporated ChatGPT 4o into Copilot.

- [AI Gateway is generally available: a unified interface for managing and scaling your generative AI workloads](https://blog.cloudflare.com/ai-gateway-is-generally-available)

    This article from the Cloudflare Blog came by way of the [TLDR DevOps Newsletter](https://tldr.tech/devops).  I am interested to see how this develops and who ends up being the target market for this service.  Specifically, given that each of the big three Cloud Service Providers have platforms which expose not only their own Generative AI models but an ever increasing library of other open and closed source models, why would I choose to go direct with multiple model providers.  I actually can see some benefits for enterprises to leverage this gateway as the "trusted" ingress endpoint that is allowed to access AI service endpoints exposed from each of the CSPs, so that those endpoints don't have to be exposed to the entire Internet and can only have to manage connections coming into their AI endpoints from this Cloudflare AI gateway.

## **Apple**

- [Apple M4 processor: A deep dive into features and performance](https://www.androidauthority.com/apple-m4-processor-features-performance-3445467/)

    This Android Authority article was surfaced for me from [TLDR Newsletter](https://tldr.tech). I am sure there are other articles which may be better and go into even further in breaking down the new M4 processor from Apple and how it stacks up to the previous generation, this article just happens to be the one that came my way and caught my attention based on the newsletters that hit my inbox on a daily basis.  As a side note, since Apple is essentially labeling the M4 processor their "AI processor", really interested to see how this plays into the announcements that will come out of the WWDC announcements in June, given that Microsoft and Google have both made more clear their initial roadmap to bring AI capabilities to Windows and Android respectively.

## **Development**

- [Essays on programming I think about a lot](https://www.benkuhn.net/progessays/)

    The article was surfaced to me from the [TLDR Newsletter](https://tldr.tech).  It is a 2020 blog article by Ben Kuhn.  I haven't had a chance make my way through all of the articles that Ben links to in his essay, but based on the one's I have checked out thus far, seems like a good collection of thought provoking material on the art and science of programming.

- [IBM Buying HashiCorp: What Devs, Analysts and Competitors Are Saying](https://thenewstack.io/ibm-buying-hashicorp-what-devs-analysts-and-competitors-are-saying/)

    Can't remember where I cam across this The New Stack article.  I subscribe a The New Stack Newsletter, so makes sense it might have come from there.  As someone that hasn't made the plunge into Terraform even though we manage AWS, Azure and GCP cloud infrastructure.  Very interested to see what IBM does with HashiCorp and Terraform as we consider whether OpenTofu will get us what I need or OG Terraform is the way to go.  
    
- [Generative Infrastructure from Code](https://appcd.com/)

    Found this referenced in the New Stack article on HashiCorp.  Sound interesting and want to dig a little deeper into it to learn more about it.


## **Conclusion:**

Out of all of the articles the one that is the most on my mind is the IBM Buying HashiCorp article.  Why?  Simply because I myself am currently trying to figure out whether moving to something like Terraform or OpenTofu is the right thing to do right now.  I struggle pivoting away from the native IaC offerings, at least from Azure and AWS (seems to me at least last time I check Google doesn't really like there own IaC solution and would rather folks just use Terraform).  We have dedicated cloud infrastructure teams that are focused on each of the cloud platforms each with expertise in the native IaC offering within each of the cloud platforms.  Azure Bicep is a really powerful and robust offering within Azure, which makes pivoting to a 3rd party offering in Azure difficult, even though Biceps is essentially Azure Only.  With AWS, CloudFormation is nice, but if you ever have to actually introduce logic in your CloudFormation templates it gets ugly fast, and yes I know there is the CDK and I can get the power of the programming language of my choice, but then I have try and standardize on a language, a divisive effort on its own, and then upskill everyone on CDK and a language.  Terraform bring with it the fact that most everyone that has worked with any of the CSP's deploying cloud native applications and infrastructure has had some exposure to Terraform, which make it attractive to move towards from common solution perspective.  In my mind our biggest reason to move toward a 3rd party IaC solution would be maturity and expansion of multi-cloud development and architectures in an enterprise cloud infrastructure environment where no cross-cloud centralized deployment mechanism exists. I will leave it at that for now.







