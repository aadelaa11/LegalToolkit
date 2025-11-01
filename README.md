# Integrated AI Legal Demand Letter Generator with Predictive Analysis

This application combines AI-powered legal drafting and predictive legal analysis to assist users in generating professional Letters of Demand, analysing contract formation, and estimating debt recovery outcomes.

It uses AI-powered models to produce the following:
- Pre-litigation recovery probability
- Contract validity assessments
- Customised demand letters
- Comprehensive legal analysis summaries
- Deadline and penalty interest calculations

---

## Features

- Automated Letter of Demand drafting generator including the ability to customise tone, negotiation options, or the inclusion of interest/fees specific to the state you are in 
- AI Predictive Legal Analysis of claim including strengths/weaknesses and recovery potential  
- Australian contract law assessment with precedent case references  
- Downloadable Word document reports for Letter of Demand and Legal Analysis  
- Integrated deadline calculator to estimate when the debtor is expected to pay the stipulated debt  


---
## Application URL







---
## Test Cases 
### Test Case One - Debt Recovery Claim (No Uploads)
Steps: 
1. Run the application and enter: 
    - Creditor: Beauty & Nails Pty Ltd 
    - Debtor: Valerie Small 
    - Claim Amount: $500.00 
    - Claim Reason: Unpaid invoice for beauty services performed on 20th October 2025
2. Leave "Upload Evidence" empty 
3. Select: 
    - Letter Tone: Firm (Intensity 6) 
    - Response Days: 14
    - Include Interest and Legal Cost Clauses in Demand Letter
4. Click 'Run Predictive Legal Analysis' 
5. Expected Outcome: 
    - Predictive report includes probability ("Pre-litigation Recovery Probability: 60%" and "Litigation Success Probability: 75%")
6. Click 'Generate Letter of Demand Document' - 'Download .docx'
7. Expected Outcome: 
    - Letter of Demand Word Document with specified clauses


### Test Case Two - Negotiation and Deadline Caluculator (PDF Upload)
Steps: 
1. Run the application and enter the following: 
    - Creditor: LegalAI Desing and Development Assit Pty Ltd 
    - Debtor: NewLaw Pty Ltd 
    - Claim Amount: 1,650.00
    - Claim Reason: Unpaid invoice #2876 for AI-powered legal research assistant services on 12th June 2025
2. "Upload Evidence"
    - Invoice Extract URL:  
3. Select: 
    - Letter Tone: Professional (Intensity 10) 
    - Response Days: 18 
4.	Check: 
    - ✅ Offer Payment Plan 
    - ✅ Suggest Mediation 
    - ❌ Demand full payment
5.	Click Generate Letter of Demand Document – download .docx
6.	Click Run Predictive Legal Analysis (May take 1-2 minutes to generate)
7.	Scroll to “Response Deadline Calculator” 
    - Start Date: today’s date 
    - Days to respond: 18 days 
    - Count weekends: ❌ 
8.	Expected Outcome: 
    - Predictive report includes probability (e.g., “Pre-litigation Recovery Probability: 60%” and “Litigation Success Probability: 75%”)
    - Letter of demand document generated successfully and includes all specified clauses 


### Test Case Three - Demand Letter Generation and Predictive Legal Analysis (PDF & DOCX Upload)
Steps: 
1. Run the application and enter the following: 
    - Creditor: JCWebServices
    - Debtor: JewelleryCore Pty Ltd
    - Claim Amount: $5,500.00
    - Claim Reason: Unpaid invoice #INV0001 for small business eCommerce Website Development and Design on 11th Janurary 2025
2. "Upload Evidence" 
    - Invoice Extract URL: 
    - Email Correspondence with Attached Invoice Extract URL:   
3. Select: 
    - Letter Tone: Professional (Intensity 10) 
    - Response Days: 14 
    - Include Interest and Legal Cost Clauses in Demand Letter
4.	Check: 
    - ❌ Offer Payment Plan 
    - ❌ Suggest Mediation 
    - ✅ Demand full payment
5.	Click Generate Letter of Demand Document – download .docx
6.	Click Run Predictive Legal Analysis (May take 1-2 minutes to generate)
7.	Scroll to “Response Deadline Calculator” 
    - Start Date: today’s date 
    - Days to respond: 14 days 
    - Count weekends: ❌ 
8.	Expected Outcome: 
    - Predictive report includes probability (e.g., “Pre-litigation Recovery Probability: 60%” and “Litigation Success Probability: 75%”) also includes likelihood of a contract being formed as a means to assess the strength of your claim.
    - Letter of demand document generated successfully and includes all specified clauses 

---
## Artifacts 
### Test Case Two - Negotiation and Deadline Caluculator (PDF Upload)
1. 

### Test Case Three - Demand Letter Generation and Predictive Legal Analysis (PDF & DOCX Upload)
1. 
2. 