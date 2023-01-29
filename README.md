Global Financial Markets Dashboard
================
Teal Emery

# Introduction

This GitHub repo houses the code for a simple global financial markets
dashboard used to guide discussion for the 15 minute *trading floor
meeting* at the beginning of class each week for **Sustainable Finance:
Applications and Methods** at [Johns Hopkins School of Advanced
International Studies (SAIS)](https://sais.jhu.edu/).

<img src="images/SAIS%20Course%20-%20Cover%20Art.png" width="1600" />

## Purpose

Financial markets are complex. The objective of this dashboard is to
give readers a 40,000 ft view of global financial markets in as few
indicators as possible to. It seeks to avoid cognitive overload,
illuminate big-picture trends, and inform where readers might want to
dig deeper.

The second purpose of the dashboard is to provide the class a practical
example of how R can be used to create automatable data products that
save us time and help us make better decisions.

## Indicators

This dashboard focuses on five indicators central to global financial
markets.

- **Interest Rates**:

  - Fed Funds Rate

  - US 10-Year Treasury Yield

- **Risk Assets**:

  - S&P 500

- **Commodities**:

  - Oil Prices (Brent)

- **Currencies**:

  - Broad USD Index

# Reproducibility

The dashboard is made using open source tools
([R](https://www.r-project.org/) + [Quarto](https://quarto.org/) +
[Plotly R](https://plotly.com/r/)). It uses freely available data from
the [Federal Reserve (FRED)](https://fred.stlouisfed.org/), and [Yahoo
Finance](https://finance.yahoo.com/). The charts use the freely
available [Roboto font from Google
Fonts](https://fonts.google.com/specimen/Roboto) because it looks a lot
more professional than the default fonts in Plotly.

You can fork this GitHub repository and you should be able to run &
modify the code as you please.

# Work in Progress

This is a work in progress. Over time, I’ll improve the dashboard, and
add secondary dashboards that do a deeper dive into key asset classes.

Initial To-Dos:

- **Clean up code**: I plan to clean up the code into well-annotated
  functions.

- **Automate using GitHub Actions**: Using the [blogpost written by Bea
  Milz](https://beamilz.com/posts/series-gha/2022-series-gha-2-creating-your-first-action/en/),
  I’ve had initial success automating R scripts using [GitHub
  Actions](https://github.com/features/actions). I’d like to automate
  this dashboard to update daily or weekly. Work hard to be lazy.

- **Adding secondary dashboards**: With dashboards, brevity is sacred. I
  want to keep the 40,000 ft dashboard as un-cluttered as possible. But
  I plan to add secondary dashboards that use publicly available data to
  dig in deeper on asset classes of interest.
