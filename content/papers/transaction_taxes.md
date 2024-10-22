+++
title = 'Aggregate Consumption and Housing Transaction Taxes'
draft = false
+++

# Overview

In this project I study the English stamp duty holiday that took place between July 2020 and September 2021.
I analyze transaction level data from HM Land Registry to assess which properties were most affected and how transaction volumes and prices changed over the holiday.
Then I build a quantitative macroeconomic economic model which matches the transaction patterns identified from the data.
I use the model to evaluate the effect of the holiday on aggregate consumption.
I find that an 18 month elimination of a 3% tax increases aggregate consumption by an average of 0.5% over the duration of the holiday.

# Details

I study how temporary changes in household transaction taxes affect transaction volumes and aggregate consumption.
I focus on the English "stamp duty" holiday that took place between July 2020 and September 2021.
I use transaction-level data from England to study the effect of the policy on housing transactions using an event study model.
I then use a quantitative macroeconomic model to numerically compute the effect of the tax policy on aggregate consumption.

England levies a tax on home purchases as a percentage of the final sale price.
In early 2020, the tax rate varied from 0% to 5% depending on the house value.
Between July 2020 and September 2021, the tax rate was temporarily reduced.
For example, a buyer of a £500,000 house would pay £15,000 tax (3%) in January 2020 but paid no tax in January 2021.
Importantly, the tax reduction was temporary with a specified duration; the government announced the tax reduction with immediate effect, and simultaneously announced the date at which the taxes would revert.
Households therefore had an incentive to complete their transaction before the end of the holiday.

In the empirical section of my paper, I estimate the effect of the tax change on house transaction probabilities.
I use the Price Paid Data from HM Land Registry which records almost all full market-value sales of residential properties in England and Wales.
The tax rate reduction depends on the value of the property.
I use this variation to estimate the monthly change in transaction probability due to the tax holiday.
I find that every percentage point of tax reduction increased the probability of a house being transacted by 0.0089 over the 12 months of the holiday.
For comparison, the mean annual transaction probability in 2019 was 0.051.
The greatest increase in transaction probability occurred in the months immediately before the end of the holiday.
In the month immediately following the holiday, the transaction probability fell by 0.0015.

In the quantitative section of my paper, I study an incomplete markets model where households are subject to idiosyncratic income shocks and have access to liquid assets, housing and long-term mortgage debt.
Households face a transaction cost to adjust their housing stock, resulting in an impulse control problem.
Households are also constrained by a loan-to-value constraint on mortgages at origination.
I solve the model in steady-state and then simulate the transition dynamics of the economy over the course of the tax holiday.
The direct effect of the policy is to reduce tax payments and therefore increase the resources available for consumption.
However, the policy also incentivizes households to increase saving so they can achieve their required down payment before the end of the holiday.
The quantitative importance of this indirect effect depends on the length of the tax holiday.
An 18 month elimination of a 3% tax increases aggregate consumption by an average of 0.5\% over the duration of the holiday.
A 5 year holiday increases aggregate consumption by a similar average of 0.45\% over the entire duration of the holiday, but this is composed of a fall in consumption of 0.25\% over the first 18 months and an increase of 0.75% over the remaining 42 months.
My analysis therefore suggests that the policy maker should limit the duration of the holiday in order to maximize the short-term demand stimulation induced by the tax reduction.
