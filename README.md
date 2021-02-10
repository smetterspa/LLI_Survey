# Description
We developed and implemented two surveys with customers of a large life insurer, LLI. As is standard in academic work using commercial data, LLI is a fictional name, as the data provider LLI wishes to remain anonymous in exchange for providing this unique data. LLI is a large U.S. life insurer that regularly receives an A.M. Best Company rating of A++. LLI life insurance is widely marketed to the general U.S. population. Over the years, LLI has developed considerable expertise in surveying its clients, including how to word questions to avoid confusion. The first survey ("New Buyers Survey") was delivered to all customers from LLI who purchased term life insurance between October 2013 and November 2017. (We only survey those who purchased term policies because LLI permanent policies include a unique type of universal life policy that is being used by LLI's wealth management group as a tax-efficient investment vehicle for people who have maxed out their tax preferred (e.g., 401(k), 403(b), or IRA) contributions.) The second survey ("Lapsers Survey") was delivered to all customers from LLI who lapsed on their life insurance policies between January 2012 and November 2017. Survey data was provided in support of the academic paper, _Gottlieb, Daniel and Kent Smetters (Forthcoming). "Lapse-Based Insurance." Conditionally Accepted, The American Economic Review._ More details, including the entire list of survey questions, is provided in Section 3 and Appendix B of that paper. Data is passcode protected until the academic paper is published, at which time the passcode will be removed. However, the passcode and computation code has been transmitted to the AER's data replication team as part of its validation exercise prior to publication.

# Codebooks

### LLI_Lapsers_Merged_032618.xlsx variable names
* Policy_Status_Description (LLI administration data): All values set to "Terminated Lapse" indicating all policies in this data have lapsed.
* Age_At_Issue (LLI administration data): Age of buyer at time of purchase
* Annual_Premium (LLI administration data): Annual premium
* Final_Conversion_Date, Termination_Date (LLI administration data): the termination date. 
  * Final_Conversion_Date is more general concept for all buyers for LLI but provides no additional information for this data pull.
* Policy_Year_Date (LLI administration data): date at which policy is sold
* TCL_Issue_Date (LLI administration data): typically equal to or a bit later than Policy_Year_Date if there is a delay in additional underwriting / processing.
* Anniversary_Date (LLI administration data): typically one year after Policy_Year_Date.
* Y_o_L (LLI administration data): a short code for year of lapse
* ProductID, Plan_Code, Product_Short_Name (LLI administration data): Type of product (e.g., 20-year term). Product_ID and Plan_Code often changed over time for same Product_Short_Name as product characteristics changed slightly, including pricing strategy.  
* Integration_ID (LLI administration data): Internal code used by LLI that provided little use for research.
* The remaining columns are related to the survey. See the survey code book. 
  * StartDate and EndDate refer to when the respondent started and completed the survey, as indicated by a Progress (%) of 100. 
  * ResponseId is internal tracking code produce by Qualtric.
  * The remainder of the columns can be directly understood from the survey.

### LLI_New_Buyers_Merged_032718.xlsx variable names
* Most of the administration data are the same as with LLI_Lapsers_Merged_032618.xlsx. If the column name is found above, the definition remains the same.
* ULTIMATEFACEAMOUNT: the face value (amount paid upon death) of the term policy
* Iss_Year: typically the same year or following full year in which the policy was purchased. Generally not useful for the survey. 
* Remainder of columns come from the survey

# Terms of Use
By accessing the data and related surveys, you agree to the following terms:
* You will not use the data for commerical purposes, as defined in 18 U.S. Code § 31(a)(10).
* You will not identify or attempt to identify the actual name of the insurer with fictional name LLI, even if the actual name is accidentially provided or accidentially easily identifiable from the data or from previous presentations of the paper.
* You will not attempt to identify or contact survey respondents or non-respondents.  
* You will not directly transmit the data to other parties or engage in any other arms-length transfer or transaction that attempts to circumvent these Terms of Use.
* If you wish to know the actual identity of LLI, you will contact Kent Smetters (or, if no longer available, Daniel Gottlieb) with an abstract of 250 or less words stating the intended non-commercial use of the data along with your full contact information (name, research affiliation, address, phone number and email). Smetters (or Gottlieb) will transmit this information to LLI who will decide whether to contact you and pursue the research.

# Installation
Upon removal of the passcode, the data can be used in other academic paper without restriction, subject to the Terms of Use above. For replication of the results in  _Gottlieb, Daniel and Kent Smetters (Forthcoming)_, the Python code, installation instructions (including environmental .yaml file), and README files are provided in the "Additional Materials" link for the published paper [provide link here when published].

# Contributors
Daniel Gottlieb, London School of Economomics, email: d.gottlieb@lse.ac.uk
Kent Smetters, The Wharton School, email: smetters@wharton.upenn.edu
We would appreciate it if you referenced the published paper as the original source of the data. [The following citation will be updated upon publication]
_Gottlieb, Daniel and Kent Smetters (Forthcoming). "Lapse-Based Insurance." Conditionally Accepted, The American Economic Review._
