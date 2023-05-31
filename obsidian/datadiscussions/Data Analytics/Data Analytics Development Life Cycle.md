https://towardsdatascience.com/understanding-the-analytic-development-lifecycle-2d1c9cd5692e

As discussed in one of my earlier articles, it is critical to understand the analytic development lifecycle. Your analytics will not last forever, and instead, become obsolete and need to be retired. As you collect more and newer data, you will need to continue maintaining your current analytics while creating new ones. _It is essential to understand what you will need to do at each stage of the analytic lifecycle._ As seen below, I view the analytic lifecycle as five critical components to development: R&D, Deployment, Testing & Validation, Maintenance, and Retirement. So let’s walk through each element together!

![[Pasted image 20230212144539.png]]


# Research and Development

Research and development encompass the first few steps in the analytic development lifecycle. After receiving your data, you will spend time looking it over, understanding its structure, and cleaning it. As you go about this process, you need to consider what analytic opportunities you see from the data, any business problems you are aware of, and how they overlap. As you work through developing your problem statement, you can begin to test out analytic concepts and develop your analytic.

This process varies if you are working with existing analytics. For current analytics, you will want to understand the areas that need improvement, methods you will utilize, and any subject matter expertise (SME) you have acquired to help you through these updates. Having followed up conversations with an SME will help you validate if your updates are going in the correct direction or not.

I find the research and development phase of the process to be the most interesting as it is where you can learn the most about your data. I work alongside other data scientists, data engineers, and subject matter experts daily. These individuals help in creating data sets and developing a data dictionary to understand what the data represents. I can then understand how to combine this data with other datasets to build my analyses. I want to make sure I see the larger picture and tell a compelling story before moving further down the process.

# Testing and Validation with Deployment

After validating with an SME that the analytic looks as expected and is producing reliable results that make sense, it is time to prep the analytic for deployment. The process of deployment may vary, but the concepts are the same. I have developed or updated the code for my analytic at this stage, and I incorporate a more software engineering approach.

Software engineers commonly use unit testing and validation techniques in a CI/CD pipeline to test and verify that the code works as expected. When you test and validate your analytics, it can be on a much smaller dataset to start. This testing and validation are to make sure the code you wrote is functioning as expected without any major flaws or bugs introduced. Adding unit tests will give you the satisfaction that your code is running well before deploying it to a larger dataset.

Now that you have tested and validated your code on a small scale, you can deploy your code to a testing environment to run it on large datasets. At this point, you will want to run your code against most, if not all, the data you have to verify if the results still look as expected. You can double-check with your SME to make sure nothing has changed since the conception of the analytic idea or update. If the analytic looks as expected, you can move into the maintenance phase. Otherwise, you should go back to the research and development phase to investigate the issues seen. The two-step validation of testing code at a small scale with unit testing and a large scale with most or all the data will help create a solid foundation for well tested and maintained analytic code.

I have found this process helpful as it shows code design issues through the unit testing and presents problems with the analytic when testing it at scale. The multiple steps of testing and validating the code also makes sure that it is performing as expected. I have found fewer issues and iterations of code updates when using CI/CD for analytic development.

# Maintenance

Now that you have deployed your analytic, it is time for it to transition to maintenance mode. In maintenance mode, you monitor your analytic for any bugs or deviations from the expected result. Some areas to consider for maintenance of an analytic include:

-   Has new data been introduced? Do you need to update the code with the addition of new data?
-   Has data been removed that affects your analytic? If you cannot fix this, then you may need to consider retirement.
-   Does the analytic output perform as expected, or has it begun to perform poorly? If it is performing poorly, what has changed?
-   Has the problem your analytic was trying to predict resolved itself, and now your analytic is not used? If so, you may need to consider retirement.
-   Has the problem statement changed, and if yes, how does this affect your analytic?
-   Do you need to retrain a model? Retraining may come up when the data you use for input has changed or new information is introduced.

These are just some areas you may need to consider as you maintain the analytic through its life. There are many more possibilities that could arise, and you will need to take them as they come and evaluate the possible outcomes and next steps.

# Retirement

Retirement can be the quickest phase of the process. When an analytic is no longer useful, it is time to retire the code and move on to the next project. Depending on your team, retirement may look different from removing the code, disabling a deployment, or shutting down a dashboard of results. At this point, you will want to communicate out to the users why and when the analytic will stop. This communication is necessary as you should inform users of any significant change that could affect their decision-making process. If you are replacing your analytic with something new, let them know that too. Communication is key to others’ understanding your processes, and without it, things can become a mess.

# Final Thoughts

Your analytics lifecycle may vary, including or removing different aspects that I have covered here. My thoughts were that the analytic lifecycle is very similar to a software development lifecycle in the idea that you are developing code that will be iterated upon, maintained, and eventually retired. The only main difference is how you do the validation and testing to confirm that you are getting the expected results with your work.