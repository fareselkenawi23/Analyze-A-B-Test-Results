# Analyze A/B Test Results
A/B tests are very commonly performed by data analysts and data scientists.

For this project, we will be working to understand the results of an A/B test run by an e-commerce website. The company has developed a new web page to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. Our goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

# What is A/B testing?

A/B testing (also known as split testing or bucket testing) is a method of comparing two versions of a webpage or app against each other to determine which one performs better. A/B testing is essentially an experiment where two or more variants of a page are shown to users at random, and statistical analysis is used to determine which variation performs better for a given conversion goal.

![image](https://user-images.githubusercontent.com/108924970/178010509-f145ca99-cbf9-4a23-a453-18386a869dfd.png)

Running an A/B test that directly compares a variation against a current experience lets you ask focused questions about changes to your website or app and then collect data about the impact of that change.

Testing takes the guesswork out of website optimization and enables data-informed decisions that shift business conversations from "we think" to "we know." By measuring the impact that changes have on your metrics, you can ensure that every change produces positive results.

# How A/B testing works
In an A/B test, you take a webpage or app screen and modify it to create a second version of the same page. This change can be as simple as a single headline, button or be a complete redesign of the page. Then, half of your traffic is shown the original version of the page (known as the control) and half are shown the modified version of the page (the variation).

![image](https://user-images.githubusercontent.com/108924970/178010574-2aa6f3db-4c3b-4a40-93a7-5d700fe60870.png)

As visitors are served either the control or variation, their engagement with each experience is measured and collected in a dashboard and analyzed through a statistical engine. You can then determine whether changing the experience had a positive, negative or neutral effect on visitor behavior.

![image](https://user-images.githubusercontent.com/108924970/178010611-05da9a75-7a97-4bbf-a791-442b38042fee.png)

# Why you should A/B test
A/B testing allows individuals, teams and companies to make careful changes to their user experiences while collecting data on the results. This allows them to construct hypotheses and to learn why certain elements of their experiences impact user behavior. In another way, they can be proven wrong—their opinion about the best experience for a given goal can be proven wrong through an A/B test.

More than just answering a one-off question or settling a disagreement, A/B testing can be used to continually improve a given experience or improve a single goal like conversion rate over time.

A B2B technology company may want to improve their sales lead quality and volume from campaign landing pages. In order to achieve that goal, the team would try A/B testing changes to the headline, visual imagery, form fields, call to action and overall layout of the page.

Testing one change at a time helps them pinpoint which changes had an effect on visitor behavior, and which ones did not. Over time, they can combine the effect of multiple winning changes from experiments to demonstrate the measurable improvement of a new experience over the old one.

![image](https://user-images.githubusercontent.com/108924970/178010666-18042af8-d239-4d6b-a9e8-3ee83bbe4df2.png)

This method of introducing changes to a user experience also allows the experience to be optimized for a desired outcome and can make crucial steps in a marketing campaign more effective.

By testing ad copy, marketers can learn which versions attract more clicks. By testing the subsequent landing page, they can learn which layout converts visitors to customers best. The overall spend on a marketing campaign can actually be decreased if the elements of each step work as efficiently as possible to acquire new customers.

![image](https://user-images.githubusercontent.com/108924970/178010700-70407ef7-e0c3-480c-b9a0-0af81b2decaa.png)

A/B testing can also be used by product developers and designers to demonstrate the impact of new features or changes to a user experience. Product onboarding, user engagement, modals and in-product experiences can all be optimized with A/B testing, as long as goals are clearly defined and you have a clear hypothesis.

# A/B testing process
The following is an A/B testing framework you can use to start running tests:

- Collect data: Your analytics will often provide insight into where you can begin optimizing. It helps to begin with high traffic areas of your site or app to allow you to gather data faster. Look for pages with low conversion rates or high drop-off rates that can be improved.

- Identify goals: Your conversion goals are the metrics that you are using to determine whether or not the variation is more successful than the original version. Goals can be anything from clicking a button or link to product purchases and e-mail signups.

- Generate hypothesis: Once you've identified a goal you can begin generating A/B testing ideas and hypotheses for why you think they will be better than the current version. Once you have a list of ideas, prioritize them in terms of expected impact and difficulty of implementation.

- Create variations: Using your A/B testing software (like Optimizely), make the desired changes to an element of your website or mobile app experience. This might be changing the color of a button, swapping the order of elements on the page, hiding navigation elements, or something entirely custom. Many leading A/B testing tools have a visual editor that will make these changes easy. Make sure to QA your experiment to make sure it works as expected.

- Run experiment: Kick off your experiment and wait for visitors to participate! At this point, visitors to your site or app will be randomly assigned to either the control or variation of your experience. Their interaction with each experience is measured, counted and compared to determine how each performs.

- Analyze results: Once your experiment is complete, it's time to analyze the results. Your A/B testing software will present the data from the experiment and show you the difference between how the two versions of your page performed and whether there is a statistically significant difference.

If your variation is a winner, congratulations! See if you can apply learnings from the experiment on other pages of your site and continue iterating on the experiment to improve your results. If your experiment generates a negative result or no result, don't worry. Use the experiment as a learning experience and generate new hypothesis that you can test.

![image](https://user-images.githubusercontent.com/108924970/178010817-8b0d3e2c-d088-4ce5-993c-4d82c76b7f48.png)
 
Whatever your experiment's outcome, use your experience to inform future tests and continually iterate on optimizing your app or site's experience.

# A/B testing & SEO
Google permits and encourages A/B testing and has stated that performing an A/B or multivariate test poses no inherent risk to your website’s search rank. However, it is possible to jeopardize your search rank by abusing an A/B testing tool for purposes such as cloaking. Google has articulated some best practices to ensure that this doesn’t happen:

- No cloaking: Cloaking is the practice of showing search engines different content than a typical visitor would see. Cloaking can result in your site being demoted or even removed from the search results. To prevent cloaking, do not abuse visitor segmentation to display different content to Googlebot based on user-agent or IP address.

- Use rel="canonical": If you run a split test with multiple URLs, you should use the rel="canonical" attribute to point the variations back to the original version of the page. Doing so will help prevent Googlebot from getting confused by multiple versions of the same page.

- Use 302 redirects instead of 301s: If you run a test that redirect the original URL to a variation URL, use a 302 (temporary) redirect vs a 301 (permanent) redirect. This tells search engines such as Google that the redirect is temporary and that they should keep the original URL indexed rather than the test URL.

- Run experiments only as long as necessary: Running tests for longer than necessary, especially if you are serving one variation of your page to a large percentage of users, can be seen as an attempt to deceive search engines. Google recommends updating your site and removing all test variations your site as soon as a test concludes and avoid running tests unnecessarily long.

For more information on A/B testing and SEO, see our Knowledge Base article on how A/B testing impacts SEO.

A media company might want to increase readership, increase the amount of time readers spend on their site, and amplify their articles with social sharing. To achieve these goals, they might test variations on:

- Email sign-up modals
- Recommended content
- Social sharing buttons

A travel company may want to increase the number of successful bookings are completed on their website or mobile app, or may want to increase revenue from ancillary purchases. To improve these metrics, they may test variations of:

- Homepage search modals
- Search results page
- Ancillary product presentation

An e-commerce company might want to increase the number of completed checkouts, the average order value, or increase holiday sales. To accomplish this, they may A/B test:

- Homepage promotions
- Navigation elements
- Checkout funnel components

A technology company might want to increase the number of high-quality leads for their sales team, increase the number of free trial users, or attract a specific type of buyer. They might test:

- Lead form components
- Free trial signup flow
- Homepage messaging and call-to-action

# A/B Testing Examples
These A/B testing examples show the types of results the world's most innovative companies have seen through A/B testing with Optimizely:

![image](https://user-images.githubusercontent.com/108924970/178011213-a41e8cfd-768c-41e0-a901-b0bb6d1d4c72.png)
