# Project description

This is a first real mini Data Science project. As a first part, the goal is to produce the 
Basel Anti-Money Laundering (AML) index (<https://www.baselgovernance.org/basel-aml-index/methodology)>
for the year 2019!

The Basel AML Index is an independent annual ranking that assesses the risk of money laundering and
terrorist financing (ML/TF) around the world.

The data input documentation and source links can be found here:
<https://www.baselgovernance.org/basel-aml-index/methodology/indicators>

More details for the input factors:

1. The FATF MER data are accessible from here: <http://www.fatf-gafi.org/publications/mutualevaluations/?hf=10&b=0&s=desc(fatf_releasedate)>

2. For 2019, the Tax Justice Network Financial Secrecy Index of 2018 needs to be used and this can
be sourced from here: <https://en.wikipedia.org/wiki/Financial_Secrecy_Index.> File download not possible.
Either manually copy-paste date to editor or excel and convert to .csv or explore web scraping.

3. For 2019, INCSR for Money Laundering and Financial Crimes can be sourced from here: <https://www.state.gov/2019-incsr-volume-ii-money-laundering-and-financial-crimes-as-submitted-to-congress/>.

4. For CPI by Transparency International scroll down until you find "Download Data Set" from the orginal link: <https://www.transparency.org/cpi>.

5. For TRACE Matrix follow the docs link: <https://www.traceinternational.org/trace-matrix>
File download not possible. Either manually copy-paste date to editor or excel and convert to .csv or explore web scraping.

6. For Corporate Transparency Index follow the link: <https://www.doingbusiness.org/en/data/exploretopics/protecting-minority-investors> and download the available excel file.

7. WEF Global Competitiveness Report – Strength of auditing and reporting standards follow the docs link:
<http://reports.weforum.org/global-competitiveness-report-2018/competitiveness-rankings/#series=EOSQ097>. File download not possible. Either manually copy-paste date to editor or excel and convert to .csv or explore web scraping.

8. WEF Global Competitiveness Report – Regulation of securities exchanges exists only for 2017-2018 index and can be found here: <http://reports.weforum.org/global-competitiveness-index-2017-2018/competitiveness-rankings/#series=EOSQ092>. Probably they haven't updated properly the documentation. File download not possible. Either manually copy-paste date to editor or excel and convert to .csv or explore web scraping.

9. For Financial Sector regulations follow the link: <http://ida.worldbank.org/financing/resource-management/ida-resource-allocation-index> and download the available excel file and use only indicator No. 5.

10. For Political Disclosure you follow the link: <http://www.idea.int/data-tools/data/political-finance-database> and fill in the "Question" section the each of the following 4 questions and click "Search". Then you scroll down and export the data.

    a) Do political parties have to report regularly on their finances?
    b) Do political parties have to report on their finances in relation to election campaigns?
    c) Do candidates have to report on their campaign finances?
    d) Is information in reports from political parties and candidates made public?
  
11. For Budget Transparency you follow this more direct link: <http://survey.internationalbudget.org/#download> and download either excel, csv or json file. The zip contains excel and a folder with csv files, of which "summary" and "countrycodes" are of main interest.

12. For Transparency, accountability and corruption in the public sector follow the link: <http://ida.worldbank.org/financing/resource-management/ida-resource-allocation-index> and download the available excel file and use only indicator No. 16.

13. For Freedom House follow the link: <https://freedomhouse.org/countries/freedom-world/scores>. File download not possible. Either manually copy-paste date to editor or excel and convert to .csv or explore web scraping.

14. For WEF Global Competitiveness Report – the Institutions Pillar follow the link: <http://reports.weforum.org/global-competitiveness-report-2018/competitiveness-rankings/#series=GCI4.A.01>. File download not possible. Either manually copy-paste date to editor or excel and convert to .csv or explore web scraping.

15. For Rule of Law Index follow the link: <https://worldjusticeproject.org/our-work/research-and-data/wjp-rule-law-index-2019/current-historical-data> and download the data.

For the 1st part:

1) Read the data. Also, download the data and create a standarized folder and file structure.
2) Clean the data.
3) Calculate the index based on the methodology.

As a 2nd part, we could investigate Machine Learning applications.
