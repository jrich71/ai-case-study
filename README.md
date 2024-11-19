# DataSeer: Using AI to Build a Better Open Science Publication Ecosystem <mark>DRAFT</mark>

## Overview and Origin

* Name of company

    - [DataSeer](https://dataseer.ai/) (DataSeer Research Data Services Ltd)

* When was the company incorporated?

    - [DataSeer](https://dataseer.ai/) was founded in 2019. It is incorporated in Vancouver, BC, Canada.

* Who are the founders of the company?

    - [Tim Vines, PhD](https://www.linkedin.com/in/drtimvines/), is the founder and current CEO.

* How did the idea for the company (or project) come about?

    - According to its [website](https://dataseer.ai/about/), Dr. Vines conceived DataSeer while manually checking data policy compliance for the journal [Molecular Ecology](https://onlinelibrary.wiley.com/journal/1365294x). Instead of going through each article line-by-line for 30 minutes or more, he wondered, why not have Artificial Intelligence do the same job in seconds?

* How is the company funded? How much funding have they received?

    - DataSeer was initially funded by a grant from the Sloan Foundation. Other than through business partnerships and grant funding, it's unclear yet what other funding sources support the company.

## Business Activities

* What specific problem is the company or project trying to solve?
    - DataSeer is a small AI and Research Data Services company addressing Open Science problems that are multi-faceted with factors related to policy, infrastucture, and workflows ([Iarkaeva et al., 2024](https://doi.org/10.1371/journal.pone.0302787)). In the science field more broadly, [Purgar et al., 2024](https://doi.org/10.1038/s41559-024-02433-5) argue that inefficiencies in science render "85% of medical research [to have] limited or no value to the end user." DataSeer promotes "Open Science" through [providing](https://dataseer.ai/about/):

    <!---Below I used a code block format (```) instead of block quote format (>) because block quote formatting was doing weird spacing.-->
    
    ```"low-cost, scalable solutions to measure open science, show researchers how to comply with policy, and deploy just-in-time interventions."``` 
    
    - One problem in Open Science is accurately and efficiently advising researchers when and how to comply with open data sharing policies with peer-reviewed journal articles. This not only goes against rapidly developing mandates on data sharing, but also penalizes researchers in terms of citations counts when not sharing data ([Colavizza et al., 2024](https://doi.org/10.1371/journal.pone.0311493)). A solution would reduce the time and costs associated with sharing research data as well as catalyze data and knowledge sharing to build an open science ecosystem. 
    
    - A second problem in Open Science is the time and labor required for manual peer review of scientific journal articles, which slow the scientific review process in addition to being costly. A solution would be to use tools that automate aspects of the peer-review process (see "automated screening" by [Schultz et al, 2022](https://bmcresnotes.biomedcentral.com/articles/10.1186/s13104-022-06080-6)) that highlight key missing data or poorly written narrative, for example, that could help to narrow the focus required by human reviewers. 
    
    - A third problem is that humans may forget to include key information or data along with their research publications (either as supplemental files or within the publications themselves) thereby being non-compliant with policies meant to promote sharing of any and all relevant (and permissible) data. A solution could be to use AI that more ably checks compliance for supplemental files (e.g., datasets, code and software, lab materials, and protocols) and recommends to researchers to correctly include such files prior to any research publication ([Dumanis et al., 2023](https://doi.org/10.1371/journal.pcbi.1011626)).

* Who is the company's intended customer? Is there any information about the market size of this set of customers?

    - The field is an intersection of scholarly publishing, research and development, and technology. The scholarly publishing market in 2020 was valued at $26.5 billion of which $9.5 billiion (36%) came from academic journals ([Butler et al., 2023](https://doi.org/10.1162/qss_a_00272)). Open Access (OA) alone accounted for almost $1 billion in 2020. The [top 5 OA publishers](https://doi.org/10.1162/qss_a_00272) from 2015&ndash;2018 were the following (along with estmated revenue):

        - Springer Nature ($589.7 million)
        - Elsevier ($221.4 million)
        - Wiley ($114.3 million)
        - Taylor & Francis ($76.8 million)
        - Sage ($31.6 million)

    - Individual journals as well as academic institutions could be intended customers (although they may well be secondary given their budgets and resources often don't match those of the largest publishers).

* What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)

    - DataSeer is one of [Outsell's Emerging 50 for 2023](https://blog.outsellinc.com/announcing-outsells-emerging-50-of-2023-274ffff04221) that offers three AI-driven products enabling a more data-driven Open Science ecosystem, which benefits from enhanced compliance, quality checking, and measurement tools for achieving rigor and incresed impact in research:

        - [Compliance Checks](https://dataseer.ai/compliance-checks/): Using AI to verify whether peer-review manuscripts (and data products?) are aligned with publishing policies. 

        - [Open Science Metrics](https://dataseer.ai/open-science-metrics/): Using NLP to aggregate statistics on a variety of data points that include "open access licensing, data and code sharing, repository use, preprint posting, protocol sharing and reuse, personal identifiers, and more." The statistics can be reported according to different factors (e.g., journal, funder, over time, etc.) and linked back to originating sources (i.e., article and article metadata).

        - [DataSeer SnapShot](https://dataseer.ai/snapshot/): Using AI to determine the degrees to which journal article text describes open science practices and then generate messages to authors as to how they may address any gaps in describing their practices. The results help journal editors more accurately and efficiently quality check and triage articles for publication.

    - In addition to offering products, DataSeer engages in non-profit and academic [partnerships](https://dataseer.ai/2020/06/11/coko-receives-sloan-foundation-grant-to-build-dataseer-a-missing-piece-in-the-data-sharing-puzzle/) that promote open data and knowledge sharing via improved compliance, gaining workflow efficiencies, and achieving more insightful reporting.

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing&mdash;you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)

    - Based on its [publicly available Github](https://github.com/DataSeer), DataSeer employs ML and NLP.

## Landscape

* What field is the company in?

    - The field is an intersection of scholarly publishing, research and development, and technology. Terms that are used to describe this intersection, and nascent industry include, "Research Data Management (RDM)" and "Scholarly Communication" ([Andrikopoulou, Rowley, & Walton, 2021](https://doi.org/10.1080/13614533.2021.1964549)). These fields fall within a broader global movement for Open Science. Using the [UNESCO figure below](https://doi.org/10.54677/MNMH8546), RDM and Scholarly Communication arguably fall best into the categories of "Open Scientific Knowledge" and "Open Scientific Infrastructures".

    ![4 Pillars](UNESCO-Open_science-pillars-en.png)

* What have been the major trends and innovations of this field over the last 5&ndash;10 years?

    - More broadly, Open Science is a field that has grown over the last 10 years due to interlocking factors including: [federal](https://www.whitehouse.gov/ostp/news-updates/2022/08/25/breakthroughs-for-alldelivering-equitable-access-to-americas-research/) to [global](https://doi.org/10.54677/MNMH8546) policy initiatives aimed at democratizing access to research knowledge and data; pushback to [peristent price increases for research journals](https://library.missouri.edu/news/lottes-health-sciences-library/scholarly-publishing-and-the-health-sciences-library#:~:text=The%20health%20sciences%20have%20been,of%20Missouri%20system%20pays%20now.&text=Why%20are%20journal%20prices%20increasing,bring%20journal%20prices%20under%20control.); and industry recognition that [Open Science may be good for business](https://www.weforum.org/stories/2023/11/open-science-6-reasons-businesses-should-pay-attention/). Yet less is known as to the size and scope of growth for aspects of Open Science, RDM, or Scholarly Communication.

* What are the other major companies in this field?

    - Online searches have not found direct competitors yet did find a host of AI-related companies in related spaces:
        - [Kopernio](https://ir.clarivate.com/news-events/press-releases/news-details/2018/Clarivate-Analytics-Acquires-Research-Startup-Kopernio-to-Accelerate-Pace-of-Scientific-Innovation/default.aspx) (acquired by Clarivate, 2018): AI that enables 1-click access to scholarly journals within institutional (academic) paywalls/firewalls as well as publicly available research.
        - [iNLP by integra](https://integranxt.com/inlp-ai-language-assessment/): AI/NLP for reducing the time and effort for editing scholarly journal articles.
        - [editage by Cactus](https://www.editage.com/): AI writing and editing assistants primarily directed at researchers/authors to optimize writing for paper pre-submission and post-submission.

    - It is highly likely that additional publishers, such as [Elsevier](https://www.elsevier.com/about/policies-and-standards/publishing-ethics-books/the-use-of-generative-ai-and-ai-assisted-technologies-in-the-editing-process), will either develop in-house solutions for AI to promote Open Science or partner with 3rd-party products and services, like DataSeer. DataSeer's partnerships with Taylor & Francis and IOP Publishing are examples of the latter. Select partnerships that DataSeer lists on its website, which gives a sense as to 'major' organizatons in this field, include:

        - [American Association for the Advancement of Science (AAAS)](https://www.aaas.org/): The world's largest multidisciplinary scientific society and publisher of [Science](https://www.science.org/) and its related journals.
        
        - [Coko Foundation](https://coko.foundation/): A not-for-profit dedicated to building open source solutions and community that promotes open publishing
        
        - [IOP Publishing](https://ioppublishing.org/): Publisher of leading scientific journals such as IOPscience
        
        - [KnowledgeWorks Global Ltd.](https://www.kwglobal.com/): A consulting company that provides a variety of content management services including editing and peer review
        
        - [Kriyadocs](https://www.kriyadocs.com/): Provider of solutions for publishing journals and books, which lists as its partners such leading organizations as Sage and BMJ
        
        - [Origin](https://origineditorial.com/): A technology and service consulting company that helps clients with editing and managing aspects of peer review publication

        - [PLOS](https://plos.org/): Groundbreaking publisher of open science research since 2001
        
        - [Taylor & Francis](https://taylorandfrancis.com/): A world-leading publisher with content that serves customers across a variety of subjects and industries

        - [The Royal Society](https://royalsociety.org/): A scientific academy and leading journal publisher 

## Results

* What has been the business impact of this company so far?

    - DataSeer seems to have been making inroads with, and having impact on, publishers and researchers. Funders and institutions may also be impacted. I could not find public data that indcate the degrees of business impact so far. Recently, DataSeer has [partnered with the research publisher, Taylor & Francis](https://dataseer.ai/2024/10/14/taylor-francis-and-dataseer-to-collaborate-in-data-sharing-compliance-checks-and-open-science-metrics-pilots/) and [IOP Publishing](https://dataseer.ai/2024/02/26/dataseer-ai-and-iop-publishing-collaborate-on-open-science-indicators-and-open-data-pilot/) (among others).

* What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?

    - A primary core metric is gaining access to Open Science content through partnerships with key publishers who own the copyright to the content. Toward that, DataSeer has made made an inroad via its partnership with Taylor & Francis, one of the "big 5" publishers. 

* How is your company performing relative to competitors in the same field?

    - The data are lacking, particularly since DataSeer sits in such a niche market. There seem to be few players, let alone commercial, in this space.

## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)

    - Use unsupervised AI to suggest reseach gaps that one or more journals could address via special issues and/or calls for publication.

    - Use unsupervised AI to develop new ways of measuring research impact, such as by analyzing journal/publication metadata along with social media data.

* Why do you think that offering this product or service would benefit the company?

    - Use unsupervised AI to suggest reseach gaps that one or more journals could address via special issues and/or calls for publication.
    
        - AI could identify missing, new, or understudied subject areas based on published articles (or not) and make suggestions that help editors plan for future publications that address important, but underaddressed, areas of study and better engage existing or new audiences.
    
    - Use unsupervised AI to develop new ways of measuring research impact, such as by analyzing journal/publication metadata along with social media data.

        - AI could drive a fuller yet more nuanced view about the influcences particular research may be having among more varied audiences. This in turn could inform journals about audience engagement or development strategies, as well as help authors by more accurately determining the impact their work has.

* What technologies would this additional product or service utilize?

    - <mark>I'm unclear what's being asked here. Data + NLP?</mark>

* Why are these technologies appropriate for your solution?

    - <mark>I'm still unclear what's being asked here. How would I determine what technolgy/ies the company would need to build hypothetical products?</mark>

## Additional Resources

* DataSeer Repositories on Github [here](https://github.com/DataSeer) and [here](https://github.com/kermitt2/datastet)

* [RELX Responsible Artificial Intelligence Principles](https://www.relx.com/~/media/Files/R/RELX-Group/documents/responsibility/download-center/relx-responsible-ai-principles.pdf?__hstc=126863762.5d7946ae9c81dd508daa6dbd050d4661.1731715533536.1731715533536.1731715533536.1&__hssc=126863762.1.1731715533536&__hsfp=3116597616)

* [Open Science Indicators](https://plos.figshare.com/articles/dataset/PLOS_Open_Science_Indicators/21687686) include metadata from PLOS and non-PLOS datasets that inform Open Science activities. Further background is provided [here](https://theplosblog.plos.org/2023/10/open-science-indicators-q2-2023/).

* [Charité Dashboard on Responsible Research](https://quest-dashboard.charite.de/#tabStart)

* [The French Open Science Monitor](https://frenchopensciencemonitor.esr.gouv.fr/)

## Citations

Andrikopoulou, A., Rowley, J., & Walton, G. (2022). Research Data Management (RDM) and the Evolving Identity of Academic Libraries and Librarians: A Literature Review. New Review of Academic Librarianship, 28(4), 349–365. https://doi.org/10.1080/13614533.2021.1964549

Bobrov, E., Riedel, N., & Kip, M. (2024). Operationalizing open and restricted-access data—Formulating verifiable criteria for the openness of data sets mentioned in biomedical research articles. Quantitative Science Studies, 5(2), 383–407. https://doi.org/10.1162/qss_a_00301

Butler, L.-A., Matthias, L., Simard, M.-A., Mongeon, P., & Haustein, S. (2023). The oligopoly’s shift to open access: How the big five academic publishers profit from article processing charges. Quantitative Science Studies, 1–22. https://doi.org/10.1162/qss_a_00272

Colavizza, G., Cadwallader, L., LaFlamme, M., Dozot, G., Lecorney, S., Rappo, D., & Hrynaszkiewicz, I. (2024). An analysis of the effects of sharing research data, code, and preprints on citations. PLoS ONE, 19(10 October). https://doi.org/10.1371/journal.pone.0311493

Dumanis, S. B., Ratan, K., McIntosh, S., Shah, H. V., Lewis, M., Vines, T. H., Schekman, R., & Riley, E. A. (2023). From policy to practice: Lessons learned from an open science funding initiative. PLoS Computational Biology, 19(12). https://doi.org/10.1371/journal.pcbi.1011626

Iarkaeva, A., Nachev, V., & Bobrov, E. (2024). Workflow for detecting biomedical articles with underlying open and restricted-access datasets. PLoS ONE, 19(5 May). https://doi.org/10.1371/journal.pone.0302787

Purgar, M., Glasziou, P., Klanjscek, T., Nakagawa, S., & Culina, A. (2024). Supporting study registration to reduce research waste. Nature Ecology and Evolution, 8(8), 1391–1399. https://doi.org/10.1038/s41559-024-02433-5

Schulz, R., Barnett, A., Bernard, R., Brown, N. J. L., Byrne, J. A., Eckmann, P., Gazda, M. A., Kilicoglu, H., Prager, E. M., Salholz-Hillel, M., ter Riet, G., Vines, T., Vorland, C. J., Zhuang, H., Bandrowski, A., & Weissgerber, T. L. (2022). Is the future of peer review automated? BMC Research Notes, 15(1). https://doi.org/10.1186/s13104-022-06080-6


## Parking Lot

Go to [this tutorial](https://code.visualstudio.com/docs/languages/markdown) for writing .md files in VSCode - Markdown and Visual Studio Code 




