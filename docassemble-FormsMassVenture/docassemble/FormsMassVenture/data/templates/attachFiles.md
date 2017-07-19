[Page Description]: # (Extension Markdown file for disclosure statement form)
[purpose]: # (attach all the pdf files from questions 7-14 at the end of the form)

[comment]: # (.show creates the file to be a whole page)
% if info_pdf is True: 
   ${issuer_info_description_pdf.show() }
% endif
% if general_pdf is True: 
   ${issuer_general_description_pdf.show() }
% endif
% if hist_pdf is True: 
   ${issuer_hist_description_pdf.show() }
% endif
% if mgmt_pdf is True: 
   ${issuer_mgmt_description_pdf.show() }
% endif
% if proc_pdf is True: 
   ${issuer_proc_description_pdf.show() }
% endif
% if finc_pdf is True: 
   ${issuer_finc_description_pdf.show() }
% endif
% if sec_pdf is True: 
   ${issuer_sec_description_pdf.show() }
% endif
% if legal_pdf is True: 
   ${issuer_legal_description_pdf.show() }
% endif