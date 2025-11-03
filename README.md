# Integrated AI Legal Demand Letter Generator with Predictive Analysis

This application combines AI-powered legal drafting and predictive legal analysis to assist users in generating professional Letters of Demand, analysing contract formation, and estimating debt recovery outcomes.

It uses AI-powered models to produce the following:
- Pre-litigation recovery probability
- Contract validity assessments
- Customised demand letters
- Comprehensive legal analysis summaries
- AI chat function to ask legal questions specific to the claim
- Deadline and penalty interest calculations

---

## Features

- Automated Letter of Demand drafting generator including the ability to customise tone, negotiation options, or the inclusion of interest/fees specific to your state jurisdiction 
- AI Predictive Legal Analysis of claim including strengths/weaknesses and recovery potential  
- Australian contract law assessment with precedent case references  
- Downloadable Word document reports for Letter of Demand and Legal Analysis 
- AI-powered Q&A chatbot function allowing user to ask questions about the documents that have uploaded or the legal analysis 
- Integrated deadline calculator to estimate when the debtor is expected to pay the stipulated debt  

---
## Application URL




---

## Test Cases 
### Test Case One - Debt Recovery Claim (No Uploads)
Steps: 
1. Run the application and enter: 
    - Creditor: Tommy Callan
    - Debtor: Valerie Small 
    - Claim Amount: $500.00 
    - Claim Reason: Valerie has not paid me the $500 that I lended her 3 months ago when she was in financial hardship. I have tried to contact her on multiple occasions but each time I have been unsuccessful. It is believed that she is no longer in the country. 
2. Leave "Upload Evidence" empty 
3. Select: 
    - Letter Tone: Firm (Intensity 6) 
    - Response Days: 14
    - Include Interest and Legal Cost Clauses in Demand Letter
4. Check: 
    - ❌ Offer Payment Plan 
    - ✅ Suggest Mediation 
    - ✅ Demand full payment
5. Click 'Run Predictive Legal Analysis' - (May take 1-2 minutes to generate) 
6. Generate Letter of Demand Document (Check Penalty Interest Clause and Warning about legal costs) – download .docx 
7. Expected Outcome: 
    - Predictive report includes probability ("Pre-litigation Recovery Probability: 10%" and "Litigation Success Probability: 60%")
8. Click 'Generate Letter of Demand Document' - 'Download .docx'
9. Expected Outcome: 
    - Letter of Demand Word Document with specified clauses
10. Ask the AI a legal question on the matter: 
   - "If Valerie refuses to pay after 14 days, what should I do?"
   - "What is the reasoning behind the percentage rate that was provided for 'Pre-litigation Recovery Probability' in the Predictive Legal Analysis Report? What is the evidence for this estimate?" 


### Test Case Two - Negotiation and Deadline Caluculator (PDF Upload)
Steps: 
1. Run the application and enter the following: 
    - Creditor: LegalAI Design and Development Assit Pty Ltd 
    - Debtor: NewLaw Pty Ltd 
    - Claim Amount: 1,650.00
    - Claim Reason: Unpaid invoice #2876 for AI-powered legal research assistant services on 12th June 2025
2.  Select: 
    - Letter Tone: Conciliatory (Intensity 3) 
    - Response Days: 15 
3. "Upload Evidence"
    - Invoice #2876 Extract URL: https://drive.google.com/file/d/1iibditk-mIYNiH7Hss4ikP4v0HNLOTqk/view?usp=sharing 
4. Check: 
    - ✅ Offer Payment Plan 
    - ✅ Suggest Mediation 
    - ❌ Demand full payment
    - ❌ 'Penalty Interest Clause' 
    - ✅ Suggest Mediation 
 'Warning about legal costs'
5. Click Run Predictive Legal Analysis (May take 1-2 minutes to generate)
6. Click Generate Letter of Demand Document – download .docx	
7. Scroll to “Response Deadline Calculator” 
    - Start Date: today’s date 
    - Days to respond: 15 days 
    - Count weekends: ❌ 
8. Expected Outcome: 
    - Predictive report includes probability (e.g., “Pre-litigation Recovery Probability: 55%” and “Litigation Success Probability: 75%”)
    - Letter of demand document generated successfully and includes all specified clauses 
9. Ask the AI a legal question on the matter: 
   - "Is mediation enforcebale under Victorian law if a payment plan does not work?"

### Test Case Three - Demand Letter Generation and Predictive Legal Analysis (PDF & DOCX Upload)
Steps: 
1. Run the application and enter the following: 
    - Creditor: JCWebServices
    - Debtor: JewelleryCore Pty Ltd
    - Claim Amount: $5,500.00
    - Claim Reason: Unpaid invoice #INV0001 for small business eCommerce Website Development and Design on 11th Janurary 2025  
2. Select: 
    - Letter Tone: Professional (Intensity 6) 
    - Response Days: 14 
    - Include Interest and Legal Cost Clauses in Demand Letter
3. "Upload Evidence" 
    - Invoice #INV0001 Extract URL: https://drive.google.com/file/d/1XTia-VNgankUiYZeKbHIr8layhAsfd0B/view?usp=sharing 
    - Email Correspondence with Attached Invoice Extract URL (Download as Word Document): https://docs.google.com/document/d/1uxfeex_CHaas3GG8-GROU2vccor5PPGZ/edit?usp=sharing&ouid=117558834422017178239&rtpof=true&sd=true 
4.	Check: 
    - ✅ Offer Payment Plan 
    - ❌ Suggest Mediation 
    - ✅ Demand full payment
5.	Click Run Predictive Legal Analysis (May take 1-2 minutes to generate) 
6.	Generate Letter of Demand Document – download .docx
7.	Ask the AI a legal question on the matter: 
    - "What happens if the debtor ignores the demand letter or is bankrupt?"
8. Scroll to “Response Deadline Calculator” 
    - Start Date: today’s date 
    - Days to respond: 14 days 
    - Count weekends: ❌ 
9. Expected Outcome: 
    - Predictive report includes probability (e.g., “Pre-litigation Recovery Probability: 60%” and “Litigation Success Probability: 80%”) also includes likelihood of a contract being formed as a means to assess the strength of your claim.
    - Letter of demand document generated successfully and includes all specified clauses 
    - AI gives explanation of next legal steps

---
## Artifacts 
### Test Case Two - Negotiation and Deadline Caluculator (PDF Upload)
1. https://drive.google.com/file/d/1iibditk-mIYNiH7Hss4ikP4v0HNLOTqk/view?usp=sharing 

### Test Case Three - Demand Letter Generation and Predictive Legal Analysis (PDF & DOCX Upload)
1. Invoice: https://drive.google.com/file/d/1XTia-VNgankUiYZeKbHIr8layhAsfd0B/view?usp=sharing 
2. Email Correspondence (Download as Word Document): https://docs.google.com/document/d/1uxfeex_CHaas3GG8-GROU2vccor5PPGZ/edit?usp=sharing&ouid=117558834422017178239&rtpof=true&sd=true 