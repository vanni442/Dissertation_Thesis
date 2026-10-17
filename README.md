# Factors Affecting Individual Customers' Decisions to Deposit Money at SHB

**Table of Contents**

- [Problem](#1-problem)
- [Data Source](#2-data-source)
- [Steps](#3-steps)
- [Result](#4-result)

## 1. Problem

Customer deposits are an important source of funding for commercial banks. Understanding how customers evaluate deposit services can help banks improve their products, communication, and customer experience.

This 2024 dissertation investigates factors associated with individual customers' decisions to deposit money at **Saigon–Hanoi Commercial Joint Stock Bank (SHB)** in Vietnam. It combines a literature review, questionnaire design, survey analysis, and statistical modelling to examine six proposed factors:

- Deposit interest rates
- Bank brand
- Bank staff and customer service
- Deposit safety
- Convenience
- Marketing

The study aims to identify which measured factors are associated with customers' reported deposit decisions and develop recommendations for SHB. It was completed by **Dinh Van Anh** under the Academy of Finance–University of Greenwich dual-degree programme.

## 2. Data Source

The project combines primary customer-survey responses with secondary literature and bank information discussed in the dissertation.

| Source | Description |
| --- | --- |
| [Survey dataset](Dataset%20dissertation_Dinh%20Van%20Anh.xlsx) | Original responses in the `Data` sheet and numerically coded responses in the `Encoding` sheet |
| [Survey questionnaire](Survey_Questions.docx) | Customer-background questions and statements measuring the proposed factors and decision construct |
| [SPSS results](SPSS%20Results.xlsx) | Exported descriptive, reliability, factor-analysis, correlation, and regression results |
| [Dissertation](Dissertation_Dinh%20Van%20Anh.pdf) | Research framework, methodology, contextual evidence, results, and recommendations |

| Dataset detail | Description |
| --- | --- |
| Survey period | 27 May–8 June 2024 |
| Analysed sample | 200 respondents |
| Population of interest | Individual customers using SHB deposit services |
| Collection method | Online questionnaire through Google Forms |
| Dataset structure | 200 response rows and 37 variables in each data sheet |
| Background variables | Gender, age, education, occupation, residence, income, and duration of deposit-service use |
| Scale items | 30 items covering six proposed predictors and the customer-decision construct |
| Response scale | Five-point Likert scale for the construct items |
| Secondary context | Prior academic research and SHB information, including deposit performance for 2020–2023 |

The dependent construct, `QDLC`, reflects reported satisfaction, willingness to recommend SHB, intention to continue depositing, and preference for SHB. It is a survey-based measure rather than a record of actual deposit amounts or subsequent transactions.

## 3. Steps

1. **Review the literature and develop the research model.**
   Use prior banking research and the Theory of Reasoned Action and Theory of Planned Behaviour to establish the conceptual background. Define hypotheses connecting the six proposed factors with customers' deposit decisions.

2. **Design the questionnaire and collect responses.**
   Develop customer-background questions and Likert-scale statements. Collect online responses and organise the 200 analysed records into original-response and encoded worksheets.

   | Code | Construct |
   | --- | --- |
   | LS | Deposit interest rates |
   | UTTH | Bank brand |
   | CSKH | Bank staff and customer service |
   | ATTG | Deposit safety |
   | STT | Convenience |
   | CLM | Marketing |
   | QDLC | Customers' deposit decisions |

3. **Describe the sample and assess scale reliability.**
   Use SPSS 23 to summarise respondent characteristics and questionnaire responses. Apply Cronbach's alpha and item-level checks to assess internal consistency. The thesis removes CSKH, ATTG, and STT because their scales do not meet its reliability criteria, retaining LS, UTTH, and CLM for subsequent analysis.

4. **Conduct exploratory factor analysis and correlation analysis.**
   Examine the retained measurement structure using exploratory factor analysis, supported by KMO and Bartlett's tests. Use Pearson correlation to examine relationships among the retained constructs and the dependent measure.

5. **Fit and examine the multiple linear regression model.**
   Regress the customer-decision measure on the retained interest-rate, brand, and marketing constructs. Examine model fit, the overall F-test, coefficients, significance levels, collinearity statistics, and residual plots.

6. **Interpret the findings and develop recommendations.**
   Compare the standardised coefficients to describe the relative strength of associations within the final model. Discuss implications for deposit-product marketing, interest-rate communication, and brand reputation, together with sampling and measurement limitations.

To review the project, open the dissertation PDF and the two Excel workbooks. The questionnaire can be read in Word or a compatible viewer. Reproducing the original statistical workflow requires importing the encoded data into SPSS and following the thesis methodology; the repository does not include native SPSS syntax or output files.

## 4. Result

The final reported model retains three predictors: **marketing, deposit interest rates, and bank brand**. Each has a positive, statistically significant association with the customer-decision measure after accounting for the other two predictors.

| Predictor | Unstandardised coefficient B | Standardised coefficient β | p-value |
| --- | ---: | ---: | ---: |
| Marketing | 0.310 | 0.367 | < .001 |
| Deposit interest rates | 0.267 | 0.308 | < .001 |
| Bank brand | 0.135 | 0.208 | .001 |

| Model statistic | Reported result |
| --- | ---: |
| Sample size | 200 |
| R² | 0.505 |
| Adjusted R² | 0.497 |
| Overall F-test | F(3, 196) = 66.594, p < .001 |
| Variance inflation factors | 1.330–1.598 |

The model accounts for approximately **50.5% of the sample variation** in the customer-decision measure, with an adjusted R² of **49.7%**. SPSS significance values displayed as `.000` are reported here as **p < .001**, rather than as zero.

**Key findings and implications:**

- **Marketing has the largest standardised coefficient among the three retained predictors.** The thesis recommends improving deposit-product communication, visibility, and information availability.
- **Deposit interest rates have the second-largest standardised coefficient.** The findings support reviewing how deposit terms and interest-rate policies are communicated to customers.
- **Bank brand has a positive association with the decision measure.** The thesis highlights maintaining reputation and customer trust as part of the deposit-service strategy.
- **Scale quality affects the final model.** Removing staff, safety, and convenience scales for insufficient reliability does not demonstrate that these factors are unimportant to customers.

These results summarise the dissertation's reported model and supporting SPSS coefficient output; they are not a newly estimated regression. The observational, self-reported survey supports associations rather than causal claims. The sample is limited to 200 customers at one bank and was collected online, so the findings should not be assumed to represent all SHB customers or the wider banking sector.

**Project outputs:**

- [Completed dissertation](Dissertation_Dinh%20Van%20Anh.pdf)
- [Survey data and encoded responses](Dataset%20dissertation_Dinh%20Van%20Anh.xlsx)
- [SPSS analysis results](SPSS%20Results.xlsx)
- [Survey questionnaire](Survey_Questions.docx)
