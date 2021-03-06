---
title: Q & A
menu:
    main:
        weight: 99
tags:
    - test
    - exercise
    - step 1
---
#### Rank your 5 favorite, and least favorite, activities from this list: https://gist.github.com/fool/b0f254ff8c72a5765b6a9138249789d6
*Here are things a support engineer at Netlify might do in no particular order. List 5 things that are your most favorite to do and 5 things that are least favorite.*

**Favorite**
1. Respond to 60+ support requests via email or chat every day
2. Analyze thousands of support tickets to spot trends to improve our product
3. Suggest and champion improvements to the product and workflow to your colleagues in and out of support
4. Work with the development team to help design a new feature based on feedback from customers
5. Engage multiple users at once via chat to answer their questions and troubleshoot problems

##### Least Favorite
1. Work with prospective customers to explain our service and the pricing model
2. Create video tutorials to help teach users a specific feature or use case
3. Receive occasional phone calls requesting support from our highest-value customers
4. Debug a customer's build using a programming language and framework that you've never seen before
5. Deliver a talk to many people you don't know at a conference or meetup


#### What is your favorite thing about providing technical support?
I adore providing tech support because I learn new things troubleshooting and resolving customer issues every day. More importantly, I have a chance to better understand human emotions and the happiness in their tone (when I fix problems they were having) is what motivates me to go to any extent to find solutions.

I disagree with people when they say about having no growth in technical support. My career helped me improve technical skills and ability to view things from a different perspective that employees in other positions cannot :)

Moreover, when you troubleshoot technical issues, you will get to know that the world doesn’t run the way you want and you learn how to get things done and find solutions.


#### What did you think of our service during the time you used it?  Be honest!  “it sucked” isn’t a wrong answer unless you don’t elaborate and provide some constructive criticism ;)
I have hands-on experience updating knowledge bases using Cloud9 (an online code editor). During my time with Interakt, I used [C9](https://c9.io) to update knowledge bases where the lead developer would push updates to the production server, but it was not so practical to use on a regular basis. I think Netlify with its broader scope not only helps developers but solves every problem that distributed teams face in updating content on a daily basis.


#### Tell about how you made your site and why you chose the tools you did.  Briefly explain a challenge you experienced in setting up this site and how you solved it
I’ve built the website by deploying PHPoole and created three pages without any issues.

**Tools:**
- PHPoole: This lightweight website generator worked well to add a checklist and answers to your questions via Github. 
- Github: Helped me hosting all the data and all I had to do was add a few pages.


#### Could you give us a suggestion to improve this test or the job posting?
This job posting covered everything and I love the way you explained it. The linked articles were handy to learn more about the position. 

I suggest you add a Google form or [Typeform](https://typeform.com) to answer your questions directly instead of writing an email. That helps you keep track of applications and candidates can efficiently fill in.

#### Why do you think SSL/HTTPS is important?

SSL establishes an encrypted connection between a web server and a browser prefixing the URL with "HTTPS" rather than the standard but unsecure "HTTP" to safeguard sensitive information.

Search engines like Google officially recommended securing websites with HTTPS and indicated that they earn search benefits, which means that not only will this be important for companies that want their sites to perform well in search, but it builds trust and credibility with customers/visitors.

#### Explain, in a couple of paragraphs, what you think 2 major challenges around DNS configuration are for less-technical internet end-users

I am not sure if I follow the question. Normally, DNS challenges include propagation issues, DNS cache and complex DNS records.

#### Provide a link to documentation for a technical/developer-focused product, that you think are well done, and briefly explain why you think they are well done.
I believe support documentation of **Wistia** and **Interakt.co** are terrific.

**[Wistia's](http://wistia.com/support/)** support documentation covers everything on a single page rather than separate articles for each solution. They made good use of scrollspy navigation.

Also, each sub-topic in a page has a direct link which can be copied and shared by support staff over chat or email so visitors/users need not read the entire document.

For example,

- Embedding videos on your website
    - Generate an Embed Code
    - Inline Embeds
    - Popover Embeds
    - Troubleshooting Embed Issues

![WistiaImage](https://raw.githubusercontent.com/netlifytest/Netlify_TakeHome_Exercise/master/wistia_image.png "WisitaImage")

**[Interakt.co’s](http://docs.interakt.co)** interactive documentation with table of contents (linking sub-topics and FAQs) codepen snippets and widgets competes with Wistia’s elegance. I wrote all their (Interakt.co) docs :)


#### A customer writes in saying their “site won’t build”.  Compose your best short (2-paragraph) customer-facing answer without any additional data, that could be useful in the generic case but would also lead to a customer providing a more actionable response.

**Response to customer**

Hello Jane Doe,

Thank you for contacting Netlify Customer Care.

I am sorry that you are having issues deploying your website. Could you browse through our FAQ related to onboarding and see what happens when you follow necessary troubleshooting steps (as mentioned in FAQ # 7)?

If the issue persists, please reply with the deploy log so that we can investigate into the issue. For that,

   1. Login to your **Netlify account**
   2. Look for the site you are unable to finish and click on it to access deploy information
   ![Retrieve Logs](https://media.giphy.com/media/26FeXPs7gwYJouBHi/giphy.gif "retrievelogs")
   3. Go to **Deploys** and click on the recent deploy
   4. Hit the button **Copy to clipboard** and paste into a text file
   5. Respond to this email with the attachment and any other information that helps us to investigate
  
In the event, you are unable to find deploys or having a problem with your account, please send us the following details:

   1. What is the email address associated with Netlify and which Git provider are you trying to deploy from?
   2. Let us know if you see any error message and kindly attach a couple of screenshots showing the error

We’ll go ahead and try to resolve the issue as soon as we get the requested information.

Should you have any further queries, please do not hesitate to contact us.

Sincerely,
Ashok Kumar


**Internal Notes**

- It seems like they are using a different email address, so I requested them to provide their email address associated with the account
- I tried accessing their account on our end, and everything looks fine 
(@Chris I’m not sure if support engineers are allowed access customer accounts, but I want to take a chance)
- Suggested to follow necessary troubleshooting steps and will investigate into the issue after receiving error details and screenshots


#### (optional/bonus) Can you set up a redirect from “/netlify/anything” to https://www.google.com/search?q=anything ?
Done! Here is the link - https://ashokexercise.netlify.com/netlify/anything
