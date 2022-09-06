# Amazon-Business-Research-Analyst-Hiring-Challenge


## ABOUT CHALLENGE

**About Amazon.com:**

Amazon.com strives to be Earth's most customer-centric company where people can find and discover virtually anything they want to buy online. By giving customers more of what they want - low prices, vast selection, and convenience - Amazon.com continues to grow and evolve as a world-class e-commerce platform. Amazon's evolution from Web site to e-commerce partner to development platform is driven by the spirit of innovation that is part of the company's DNA. The world's brightest technology minds come to Amazon.com to research and develop technology that improves the lives of shoppers and sellers around the world.

## GUIDELINES

1. This is an individual-participant challenge.
2. After you have built your application, you must do the following:
   * Submit the solution in .zip format
   * At the end of the page, you must complete the following tasks:
     * Upload the following as a zip, tar, or tar.zip archive:
       * Prediction file
       * Source file
     * Submit your solution
3. The submissions are evaluated automatically. The evaluation parameters include the following:
   * Functionality of the code
   * Design aesthetics
   * Usability of the application
4. The evaluation of submissions can take up to a week's time.
5. When the challenge is live, your output will be evaluated only for 50% of the test data. After the challenge is over, your output for the remaining 50% of the test data will be evaluated and the final rank will be awarded.
6. If you do not select a submission file for the offline evaluation, your best submission will be automatically considered.
7. You will have to upload your submissions on the **Problems** page in the format specified in the problem statement.
8. In addition to your final submission, you will also have to submit your source file and other files as a .zip or .tar compressed archive.
9. The total number of submissions allowed for a participant throughout a challenge is 600. The maximum number of submissions that a participant can make in a day is 10.
10. You can use any tools or libraries to build your solution. There is no restriction on the tools that you can use.
11. The Intellectual Property (IP) of the product/code of the winners will belong to HackerEarth (only when they accept the prize). Other participants will retain the IP over their product/code. They can choose to put it in an open source domain under any license.
12. You will receive your prize after the announcement of results on the contest page in the last week of the following month. But note that if your nation does not accept PayPal payments, we will not be able to send you any cash prizes.
13. Prizes above are mentioned per individual.
14. In order to claim the prize, your leaderboard score must be reproducible from your code files.
15. Use of external dataset is prohibited for this challenge. Participants found using external dataset will be disqualified.

By participating in this challenge, you are agreeing to HackerEarth's [terms and conditions](https://www.hackerearth.com/terms-of-service/).

## Problem Solving Methodology

I solved the Problem in 2 stages.

1. Data Extraction From .txt files and save to .csv files
2. use csv files to to build a model

Here i used catboost regression with *Bayesian Search Optimization* for Hyper parameter tuning with optuna. Explore the notebook for detailed work :)
