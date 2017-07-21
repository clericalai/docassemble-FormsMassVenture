[Page Description]: # (Markdown file for disclosure statement form)

| Texas Crowdfunding Disclosure Statement | This offering listed on: | 
| ------------- |:-------------:| 
| Prepared by: ${representative.name} | ![MassVenture Logo](http://rwrlegal.com/wp-content/uploads/2015/01/MV_Site_Logo1.jpg){ width=10% }  | 
|
% if issuer_logo_question is True: 
   ${ issuer_logo.show(width='100px') } 
% endif
| | 
[CENTER]
${ today() } [BR]
***Texas Crowdfunding Disclosure Statement*** [BR]
**OFFERING FOR SECURITIES IN: ${issuer.company}**

Dear Investor: [BR]
${representative.name} has prepared this disclosure statement for your review regarding the offering of securities in ${issuer.company}, (hereinafter “${issuer.companyShortName}”).  This statement is intended to comply with the provisions of Texas Administrative Code Rule 139.25. [BR]
The issuer of the stock or other securities in this offering is ${issuer.companyShortName}.  If you purchase shares in this offering, you will own equity or securities convertible to equity in ${issuer.company}, a Texas ${issuer.entity}.  The information below is true and correct to the knowledge of the preparer ${representative.name}:

**General Information About ${issuer.companyShortName}**

1. At least 80% of ${issuer.companyShortName}'s gross revenues during its most recent fiscal year prior to the offering (if any) are derived from the operation of a business in Texas; 
2. At least 80% of ${issuer.companyShortName}'s assets at the end of its most recent semiannual period prior to the offering (if any) are located in Texas; 
3. ${issuer.companyShortName} will use at least 80% of the net proceeds of this offering in connection with the operation of its business within Texas; and 
4. The principal office of ${issuer.companyShortName} is located in Texas 
5. ${issuer.companyShortName} is not, either before or because of the offering: [BR]
5.1 A company, that engaged or proposes to engage in the business of investing, reinvesting, owning, holding, or trading in securities; [BR]
5.2 Subject to the reporting requirements of the Securities and Exchange Act of 1934, §13 or §15(d), 15 U.S.C. §78m and §78o(d); or [BR]
5.3 a company that has not yet defined its business operations, has no business plan, has no stated investment goal for the funds being raised, or that plans to engage in a merger or acquisition with an unspecified business entity. 
[BR]
**Texas Crowdfunding Compliance**
6. This offering of securities is being made exclusively through MassVenture.com, a  registered Texas crowdfunding portal. You must access, discuss, and purchase all securities related to this offering through MassVenture.com. ${representative.name} and ${issuer.companyShortName} are unable to communicate with you regarding this sale except through a registered Texas crowdfunding portal. All consideration received for all sales of the securities in reliance on this exemption will not exceed $1 million in a 12-month period. ${issuer.company} will place a legend on the certificate or other document evidencing that the securities have not been registered and setting forth the limitations on resale contained in SEC Rule 147(e), including that for a period of nine months from the date of last sale by the issuer of the securities in the offering, all resales by any person, shall be made only to Texas residents. 
[BR]
**Material Information and Risk Factors**[BR]
7. ${issuer_info_description} 
% if info_pdf is True: 
   Additional information on offering description is attached at the end
% endif
8. ${issuer_general_description} 
% if general_pdf is True: 
   Additional information on company general description is attached at the end
% endif
9. ${issuer_hist_description} 
% if hist_pdf is True: 
   Additional information on company history is attached at the end
% endif
10. ${issuer_mgmt_description} 
% if mgmt_pdf is True: 
   Additional information on company management is attached at the end
% endif
11. ${issuer_proc_description}. Type of security is ${sec_type}.
% if proc_pdf is True: 
   Additional information on proceeds description is attached at the end
% endif
12. ${issuer_finc_description} 
% if finc_pdf is True: 
   Additional financial information is attached at the end
% endif
13. ${issuer_sec_description} 
% if sec_pdf is True: 
   Additional information on securities being offered is attached at the end
% endif
14. ${issuer_legal_description} 
% if legal_pdf is True: 
   Additional information on litigation and legal proceedings is attached at the end
% endif
[BR]
**Securities Disclosures**[BR]
15. This is an offering of securities under a Texas crowdfunding exemption to federal securities laws.  As such: 
[BR]
15.1 There is no ready market for the sale of the securities acquired from this offering; it may be difficult or impossible for an investor to sell or otherwise dispose of this investment. An investor may be required to hold and bear the financial risks of this investment indefinitely; 
[BR]
15.2 The securities have not been registered under federal or state securities laws and, therefore, cannot be resold unless the securities are registered or qualify for an exemption from registration under federal and state law. 
[BR]
15.3 In making an investment decision, investors must rely on their own examination of the issuer and the terms of the offering, including the merits and risks involved; and 
[BR]
15.4 No federal or state securities commission or regulatory authority has confirmed the accuracy or determined the adequacy of the disclosure statement or any other information on this Internet website. 
[BR]
**Financial Statements **
16. ${issuer.companyShortName} represents and warrants that it has, to the extent that they exist, provided current financial statements certified by the principal executive officer to be true and complete in all material respects. These statements are available for viewing by investors at https://app.MassVenture.com These statements and other investment documentation are accessible exclusively through MassVenture.com, a registered Texas crowdfunding portal. You must access, discuss, and purchase all securities related to this offering through MassVenture.com. If ${issuer.companyShortName} has audited or reviewed financial statements, prepared within the last three years, such financial statements are also provided.
[BR]**Concluding Remarks** [BR]
This disclosure statement is intended as a guide to inform your investment in ${issuer.company} and is not a contract. This disclosure statement, along with a copy of ${issuer.companyShortName}’s Form 133.17 Crowdfunding Exemption Notice, and a summary of the offering, have been filed with the Texas Securities Commissioner. 
[BR]
[CENTER]
${issuer.company}:[BR] 
${representative.signature} [BR] 
${representative.name}, its ${representative.title} 


