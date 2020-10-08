# Money in Open-Source
### Question: How do businesses with primarily open-source codebases make money?

The words "business" and "open-source" seem to disagree with one another. On one hand, businesses are created to generate revenue. On the other, open-source software is freely available along with its code. In order to compensate for this conflict, businesses with primarily open-source codebases use certain business models to maintain growth.

### Necessities
An [article from timescale.com](https://blog.timescale.com/blog/how-open-source-software-makes-money-time-series-database-f3e4be409467/) describes two requirements for companies to create money under any model:

#### 1) Broad Adoption
The first is broad adoption, defined as a large user base. Most, if not all, of an open-source companies' users will never pay for the software. As a result, a large community is required for enough profit to be made from the low percentage of paying users. In other words, the conversion rate from users to paying customers is typically very low, so a large amount of users is necessary to compensate.

The need for broad adoption is also why most open-source companies require a large initial investment. As a result, many of them start off as projects in a larger company, research groups for universities, or VC-backed startups.

#### 2) Primary Credibility
Primary credibility means that users who need help reach out to the open-source company itself, not a third-party. Given their already low-monetization rate, the company cannot spend resources fighting over credibility and their userbase with another company.

### Business Models
With broad adoption and primary credibility, there are a number of ways open-source companies can generate revenue.

#### 1) OpenSaaS
Software as a Service (SaaS) is a model in which a third-party hosts the applications and makes them available to users (3). Netflix is an example of a SaaS company: it creates software which is available to users via a paid subscription.

The OpenSaaS model takes advantage of the benefits of SaaS: flexibility, rapid deployment, and decreased costs (2). At the same time, the open-source codebase encourages collaborative effort and growth. In order to make money, companies often offer additional subscription plans with their products. These might include storage, backup, customization, etc.

#### 2) Support ("Redhat Model")
Companies using this model sell various services, such as tech support, certification, and training, to businesses deploying the product (2). Redhat is a well-known example due to its success. In 2016, the company announced a 2.5 billion dollar profit through yearly subscriptions and technical support.

However, the paid support model has a couple notable flaws:
1) support requires costly manual work
2) scaling can be difficult
3) the company has little incentive to make their project easy to use (1).
The model is also inefficient, having an average conversion rate of 1%.

#### 3) Dual (Restrictive) Licensing
Companies may choose to release their software under a commercial license and a GNU General Public license (GPL). This means that end-users can run, redistribute, and modify the software, but they cannot create proprietary software with it and profit. Other licenses, such as AGPL and Commons Clause might be used in this model.

Its main drawback is that having these licenses often turns off potential users (1). Specifically, many large companies have policies against using software with restrictive licensing.  

#### 4) Open Core (Paid Functionality)

The idea of Open Core is that the majority of the code is open source, but a small percentage is proprietary. These features are usually the "ones needed for production deployments and/or at scale", such as monitoring, administration, and backup/restore (1). A key benefit of this model is that companies can choose which of its functionalities to open-source.

The line between core and proprietary software is important. Too much open-source software risks losing revenue, while a majority of proprietary software loses broad adoption.

Additionally, it's often difficult to cleanly separate and maintain the open-source and proprietary codebases. Engineers have to constantly make sure that they can still be used together.

## Conclusion
In summary, open-source companies create money through a variety of ways, including SaaS, support, dual licensing, and open core. In general, these models try to take advantage of open-source software while making/saving money, whether this be through additional services/functionality or legal requirements. A number of other models exist, such as hybrid licensing and paid certification, but these are the main ones which companies use to generate revenue.

References:
1. https://blog.timescale.com/blog/how-open-source-software-makes-money-time-series-database-f3e4be409467/
2. https://rubygarage.org/blog/how-make-money-with-open-source-projects
3. https://searchcloudcomputing.techtarget.com/definition/Software-as-a-Service#:~:text=Software%20as%20a%20service%20(SaaS)%20is%20a%20software%20distribution%20model,service%20(IaaS%20and%20PaaS)4) https://www.zdnet.com/article/how-do-linux-and-open-source-companies-make-money-from-free-software/
