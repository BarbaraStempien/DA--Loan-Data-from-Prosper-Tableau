# Analyzing the Loan Data from Prosper in Tableau

_Barbara Stempien_

## Table of Contents

* [Project description](#Project-description)
* [story Links](#Story-Links)
* [Summary](#Summary)
* [Design](#Design)
* [Feedback](#Feedback)
* [Resources](#Resources)

## Project description

Prosper Marketplace, Inc. is a San Francisco, California-based company in the peer-to-peer lending industry. Prosper Funding LLC, one of its subsidiaries, operates [Prosper.com](https://www.prosper.com/), a website where individuals can either invest in personal loans or request to borrow money.

Borrowers request personal loans on Prosper and investors (individual or institutional) can fund anywhere from $2,000 to $35,000 per loan request. Investors can consider borrowers’ credit scores, ratings, and histories and the category of the loan. Prosper handles the servicing of the loan and collects and distributes borrower payments and interest back to the loan investors.

I have analyzed Prosper's loan data set, which contains 113,937 loans with 81 variables on each loan (including loan amount, borrower rate, current loan status, borrower income, and many others) to present a short story on the state of the peer-to-peer loans.

## Story Links

[Initial version of Prosper Story](https://public.tableau.com/profile/barbara.stempien#!/vizhome/ProsperLoanDatav1_15528462802050/PropserLoansv1)  
</br>
[Final version of Prosper Story](https://public.tableau.com/profile/barbara.stempien#!/vizhome/ProsperLoanDatav2_15528464193580/PropserLoansv2)

## Summary

In my story, I have done the exploration of the Prosper company and borrowers. First, I have done a time series analysis on the number of loans and the number of loans taken by the borrowers. Then, I looked closer to the reasons why loans are taken and what is a typical borrower in terms of occupation and location. Lastly, I have explored the main risk factors for Prosper's loans. 

## Design

When it comes to the design of the plots, I decided to:

* use line plot to present the number of loans over time and bar plot to present loan's amounts over time;
* mix line plot with bar plot to present relation between the number of loans and amount of loans;

* use a stacked bar chart to present loans by amount, divided by category and status, which allows to quickly see any relation between these three variables;
* use waffle plot to present the most common loan categories as it is easy to grasp;

* use geo map to present the number of borrowers per USA state and easily see from which states most of the borrowers comes from;
* use a stacked bar chart to present borrower's employment status, occupation and debt to income ratio, which allows for a quick analysis of the borrower's financial condition;

* use bar charts and stacked bar charts to present variables related to the loan risk; 

For all plots, I have tried to:

* add markers whenever possible to make it easier to see changes in the number of records;
* add forecast lines to better visualize increase in the number of loans;
* add legends to make it easy to understand what is presented on each plot;
* add filter whenever applicable;
* use descriptive plot titles;

## Feedback

After building the first version of the story, I have shared my visualizations with Udacity study group and a few of my friends. I received the following feedback:

* 'Listings Growth over Time' plot is hard to read, it would be nice to see exact numbers for each line mark;
* it would be easier to read bar plots if values would be placed on top of the bar;
* Variable names in the tooltip are incorrectly formatted - e.g 'LoanOriginalAmount' instead of 'Loan Original Amount';
* there is no way to filter/customize the plots;
* sometimes legend is placed in odd place, so it is hard to understand to which plot it belongs to;
* 'Borrowers Home State' does not provide much of information, would be more useful if we could see values per state;
* 'Borrower's Employment Status, Occupation and Debt to Income Ratio' plot is hard to use as you have to scroll a lot, and there is no way to filter it to specific values;
* titles of plots do not always make sense and are not very descriptive

## Resources

[Prosper Marketplace, Wikipedia, the free encyclopedia](https://en.wikipedia.org/wiki/Prosper_Marketplace)
