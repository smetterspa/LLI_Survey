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
See terms of use on main page

