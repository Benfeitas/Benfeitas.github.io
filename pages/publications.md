---
layout: page
title: "publications"
redirect_from:
  - /pages/publications_backup
  - /pages/publications_backup.html
  - /pages/publications_backup/
---

<style>
.pub-intro{margin:6px 0 6px;color:#4b5563;}
.pub-meta{margin:0 0 22px;color:#6b7280;font-size:.92rem;}
.pub-meta a{font-weight:600;}
.pub-nav{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:16px;
  margin:0 0 40px;
}
@media (max-width:640px){ .pub-nav{grid-template-columns:1fr;} }
.pub-card{
  display:flex;
  align-items:center;
  gap:16px;
  padding:16px 18px;
  border:1px solid #e5e7eb;
  border-radius:14px;
  background:#fff;
  text-decoration:none;
  color:#1f2937;
  box-shadow:0 1px 2px rgba(16,24,40,.05);
  transition:transform .18s ease, box-shadow .18s ease, border-color .18s ease;
}
.pub-card:hover{
  transform:translateY(-3px);
  box-shadow:0 12px 26px rgba(16,24,40,.12);
  border-color:var(--c);
}
.pub-card:focus-visible{outline:2px solid var(--c);outline-offset:3px;}
.pub-ic{
  flex:0 0 auto;
  width:52px;height:52px;
  border-radius:50%;
  display:flex;align-items:center;justify-content:center;
  background:var(--cbg);
  color:var(--c);
}
.pub-ic svg{width:28px;height:28px;display:block;}
.pub-tx{display:flex;flex-direction:column;min-width:0;}
.pub-tt{font-weight:600;font-size:1.02rem;line-height:1.25;}
.pub-ct{font-size:.8rem;color:#6b7280;margin-top:3px;}
.pubs h2{scroll-margin-top:84px;padding-top:6px;border-top:1px solid #eef0f2;}
.pubs h2:first-of-type{border-top:none;}
html{scroll-behavior:smooth;}
@media (prefers-reduced-motion:reduce){
  html{scroll-behavior:auto;}
  .pub-card{transition:none;}
  .pub-card:hover{transform:none;}
}
</style>

<p class="pub-intro">Articles and conference presentations by theme. For the full chronological list, see <a href="/pages/publications_list">all publications &rarr;</a></p>
<p class="pub-meta">Last update: 22/07/2026</p>

<div class="pub-nav">
<a class="pub-card" href="#respiratory" style="--c:#0891b2;--cbg:#cffafe"><span class="pub-ic"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 4v7"/><path d="M12 8c-.5-1.5-1.7-2-2.6-2C8 6 7.5 7 7.5 8.5c0 1-.3 2-.9 3.2C5.8 13.2 5 14.8 5 16.7c0 1.6 1 2.3 2.3 2.3 1.6 0 2.7-.9 2.7-2.6 0-1.9 0-3.6 0-5.4"/><path d="M12 8c.5-1.5 1.7-2 2.6-2C16 6 16.5 7 16.5 8.5c0 1 .3 2 .9 3.2.8 1.5 1.6 3.1 1.6 5 0 1.6-1 2.3-2.3 2.3-1.6 0-2.7-.9-2.7-2.6 0-1.9 0-3.6 0-5.4"/></svg></span><span class="pub-tx"><span class="pub-tt">Chronic respiratory disease</span><span class="pub-ct">1 paper &middot; 2 talks</span></span></a>
<a class="pub-card" href="#immunometabolism" style="--c:#dc2626;--cbg:#fee2e2"><span class="pub-ic"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 21v-8"/><path d="M12 13 7.5 5.5"/><path d="M12 13l4.5-7.5"/><circle cx="7" cy="4.5" r="1.6" fill="currentColor" stroke="none"/><circle cx="17" cy="4.5" r="1.6" fill="currentColor" stroke="none"/></svg></span><span class="pub-tx"><span class="pub-tt">Immunometabolism, HIV &amp; immune-mediated disease</span><span class="pub-ct">7 papers</span></span></a>
<a class="pub-card" href="#viral" style="--c:#ea580c;--cbg:#ffedd5"><span class="pub-ic"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="4.2"/><path d="M12 7.8V4M12 20v-3.8M7.8 12H4M20 12h-3.8M9 9 6.3 6.3M17.7 17.7 15 15M15 9l2.7-2.7M6.3 17.7 9 15"/><circle cx="12" cy="3.4" r="1.1" fill="currentColor" stroke="none"/><circle cx="12" cy="20.6" r="1.1" fill="currentColor" stroke="none"/><circle cx="3.4" cy="12" r="1.1" fill="currentColor" stroke="none"/><circle cx="20.6" cy="12" r="1.1" fill="currentColor" stroke="none"/></svg></span><span class="pub-tx"><span class="pub-tt">Viral infection &amp; host–pathogen systems biology</span><span class="pub-ct">5 papers</span></span></a>
<a class="pub-card" href="#cancer" style="--c:#7c3aed;--cbg:#ede9fe"><span class="pub-ic"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><circle cx="9" cy="10" r="4.3"/><circle cx="15.5" cy="14.5" r="4"/><circle cx="9" cy="10" r="1.3" fill="currentColor" stroke="none"/><circle cx="15.5" cy="14.5" r="1.3" fill="currentColor" stroke="none"/></svg></span><span class="pub-tx"><span class="pub-tt">Cancer systems biology &amp; metabolism</span><span class="pub-ct">9 papers</span></span></a>
<a class="pub-card" href="#cardiometabolic" style="--c:#e11d48;--cbg:#ffe4e6"><span class="pub-ic"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20.3l-1.35-1.23C5.9 14.86 3 12.24 3 8.9 3 6.2 5.1 4.1 7.8 4.1c1.5 0 2.98.7 3.95 1.8.97-1.1 2.45-1.8 3.95-1.8 2.7 0 4.8 2.1 4.8 4.8 0 3.34-2.9 5.96-7.65 10.17L12 20.3z"/></svg></span><span class="pub-tx"><span class="pub-tt">Cardiometabolic &amp; liver disease</span><span class="pub-ct">5 papers</span></span></a>
<a class="pub-card" href="#neuro" style="--c:#4f46e5;--cbg:#e0e7ff"><span class="pub-ic"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5.5V19"/><path d="M12 6.5C11.5 5 10.3 4.2 9 4.2 7.3 4.2 6 5.5 6 7.2c-1 .3-1.7 1.2-1.7 2.3 0 .5.1.9.3 1.3-.7.5-1.1 1.3-1.1 2.2 0 1 .5 1.8 1.3 2.3-.1 1.6 1.2 3 2.9 3 1.3 0 2.4-.8 2.9-2"/><path d="M12 6.5C12.5 5 13.7 4.2 15 4.2 16.7 4.2 18 5.5 18 7.2c1 .3 1.7 1.2 1.7 2.3 0 .5-.1.9-.3 1.3.7.5 1.1 1.3 1.1 2.2 0 1-.5 1.8-1.3 2.3.1 1.6-1.2 3-2.9 3-1.3 0-2.4-.8-2.9-2"/></svg></span><span class="pub-tx"><span class="pub-tt">Neurodegeneration &amp; ageing</span><span class="pub-ct">3 papers</span></span></a>
<a class="pub-card" href="#methods" style="--c:#059669;--cbg:#d1fae5"><span class="pub-ic"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><line x1="6.6" y1="6.8" x2="17.4" y2="7.2"/><line x1="7" y1="7.8" x2="11.2" y2="15.2"/><line x1="17" y1="8.2" x2="12.8" y2="15.4"/><circle cx="5.5" cy="6.5" r="2.1"/><circle cx="18.5" cy="7.2" r="2.1"/><circle cx="12" cy="17" r="2.1"/></svg></span><span class="pub-tx"><span class="pub-tt">Computational methods, tools &amp; modeling</span><span class="pub-ct">5 papers &middot; 2 preprints</span></span></a>
<a class="pub-card" href="#infrastructure" style="--c:#475569;--cbg:#e2e8f0"><span class="pub-ic"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 4 2 9l10 5 10-5-10-5z"/><path d="M5 11v5c0 1.1 3.1 2.5 7 2.5s7-1.4 7-2.5v-5"/><path d="M22 9v5"/></svg></span><span class="pub-tx"><span class="pub-tt">Research infrastructure, training &amp; community</span><span class="pub-ct">3 papers</span></span></a>
</div>

<div class="pubs" markdown="1">

<h2 id="respiratory"><svg style="width:24px;height:24px;stroke:#0891b2;display:inline;vertical-align:middle;margin-right:8px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 4v7"/><path d="M12 8c-.5-1.5-1.7-2-2.6-2C8 6 7.5 7 7.5 8.5c0 1-.3 2-.9 3.2C5.8 13.2 5 14.8 5 16.7c0 1.6 1 2.3 2.3 2.3 1.6 0 2.7-.9 2.7-2.6 0-1.9 0-3.6 0-5.4"/><path d="M12 8c.5-1.5 1.7-2 2.6-2C16 6 16.5 7 16.5 8.5c0 1 .3 2 .9 3.2.8 1.5 1.6 3.1 1.6 5 0 1.6-1 2.3-2.3 2.3-1.6 0-2.7-.9-2.7-2.6 0-1.9 0-3.6 0-5.4"/></svg>Chronic respiratory disease</h2>

- **R. Benfeitas**, et al. 2025. "Seralutinib targets fibrotic pathways in IPF: Evidence from single-cell transcriptomics." Oral presentation, ERS Congress 2025. Eur. Respir. J. 66(Suppl. 69):OA1201. [abstract](https://publications.ersnet.org/content/erj/66/suppl69/oa1201) *(conference presentation)*
- M. Govoni, M. Bassi, L. Girardello, G. Lucci, F. Rony, R. Charretier, D. Galkin, M. L. Faietti, B. Pioselli, G. Modafferi, **R. Benfeitas**, M. Bonatti, D. Miglietta, J. Clark, F. Pedersen, A.-M. Kirsten, K.-M. Beeh, O. Kornmann, S. Korn, A. Ludwig-Sengpiel, H. Watz. 2024. "CHF6523 data suggest that the phosphoinositide 3-kinase delta isoform is not a suitable target for the management of COPD." Respiratory Research 25(1):380. [doi:10.1186/s12931-024-02999-5](https://doi.org/10.1186/s12931-024-02999-5)
- **R. Benfeitas**, F. Facchinetti, M. Govoni. 2023. "An endothelial cell subtype is linked with altered Rho-kinase (ROCK)-associated pathways in PAH." Oral communication, ERS Congress 2023. [abstract](https://www.semanticscholar.org/paper/An-endothelial-cell-subtype-is-linked-with-altered-Benfeitas-Facchinetti/4d7ae9dba51a620586c30a2e85ccc224483b2e24) *(conference presentation)*

<h2 id="immunometabolism"><svg style="width:24px;height:24px;stroke:#dc2626;display:inline;vertical-align:middle;margin-right:8px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 21v-8"/><path d="M12 13 7.5 5.5"/><path d="M12 13l4.5-7.5"/><circle cx="7" cy="4.5" r="1.6" fill="currentColor" stroke="none"/><circle cx="17" cy="4.5" r="1.6" fill="currentColor" stroke="none"/></svg>Immunometabolism, HIV & immune-mediated disease</h2>

- F. Mikaeloff, M. Gelpi, A. Escós, T. Wang, S. Gupta, A. Olofsson, S. Svensson Akusjärvi, S. Schuster, P. Naval, V. Sood, N. Nikouyan, A. D. Knudsen, B. Vestad, J. Høgh, J. R. Hov, T. Benfield, M. Trøseid, V. Pawar, M. Rucevic, **R. Benfeitas**, Á. Végvári, L. O'Mahony, R. Savai, N. K. Björkström, M. Lourda, J. P. de Magalhães, S. Weiss, A. Mardinoglu, M. K. Varshney, A. C. Karlsson, Y. A. Syed, S. D. Nielsen, U. Neogi. 2025. "Host Plasma Microenvironment in Immunometabolically Impaired HIV Infection Leads to Dysregulated Monocyte Function and Synaptic Transmission Ex Vivo." Advanced Science 12(16):2416453. [doi:10.1002/advs.202416453](https://doi.org/10.1002/advs.202416453)
- F. Mikaeloff, M. Gelpi, **R. Benfeitas**, A. D. Knudsen, B. Vestad, J. Høgh, J. R. Hov, T. Benfield, D. D. Murray, C. G. Giske, A. Mardinoglu, M. Trøseid, S. D. Nielsen, U. Neogi. 2023. "Network-based multi-omics integration reveals metabolic at-risk profile within treated HIV-infection." eLife 12:e82785. [doi:10.7554/eLife.82785](https://doi.org/10.7554/eLife.82785)
- F. Mikaeloff, S. Svensson Akusjärvi, G. M. Ikomey, S. Krishnan, M. Sperk, S. Gupta, G. D. V. Magdaleno, A. Escós, E. Lyonga, M. C. Okomo, C. T. Tagne, H. Babu, C. L. Lorson, Á. Végvári, A. C. Banerjea, J. Kele, L. E. Hanna, K. Singh, J. P. de Magalhães, **R. Benfeitas**, U. Neogi. 2022. "Trans cohort metabolic reprogramming towards glutaminolysis in long-term successfully treated HIV-infection." Communications Biology 5(1):27. [doi:10.1038/s42003-021-02985-3](https://doi.org/10.1038/s42003-021-02985-3)
- S. O. Villumsen, **R. Benfeitas**, A. D. Knudsen, M. Gelpi, J. Høgh, M. T. Thomsen, D. Murray, H. Ullum, U. Neogi, S. D. Nielsen. 2022. "Integrative lipidomics and metabolomics for system-level understanding of the metabolic syndrome in long-term treated HIV-infected individuals." Frontiers in Immunology 12:742736. [doi:10.3389/fimmu.2021.742736](https://doi.org/10.3389/fimmu.2021.742736)
- A. T. Ambikan, S. Svensson-Akusjärvi, S. Krishnan, M. Sperk, P. Nowak, J. Vesterbacka, A. Sönnerborg, **R. Benfeitas**, U. Neogi. 2022. "Genome-scale metabolic models for natural and long-term drug-induced viral control in HIV infection." Life Science Alliance 5(9):e202201405. [doi:10.26508/lsa.202201405](https://doi.org/10.26508/lsa.202201405)
- M. Gelpi, F. Mikaeloff, A. D. Knudsen, **R. Benfeitas**, S. Krishnan, J. Høgh, D. D. Murray, H. Ullum, U. Neogi, S. D. Nielsen. 2021. "The central role of the glutamate metabolism in long-term antiretroviral treated HIV-infected individuals with metabolic syndrome." Aging 13(19):22732. [doi:10.18632/aging.203622](https://doi.org/10.18632/aging.203622)
- N. Acevedo, **R. Benfeitas**, S. Katayama, S. Bruhn, A. Andersson, G. Wikberg, L. Lundeberg, J. M. Lindvall, D. Greco, J. Kere, C. Söderhäll, A. Scheynius. 2020. "Epigenetic Alterations in Skin Homing CD4+CLA+ T Cells of Atopic Dermatitis Patients." Scientific Reports 10(1):18020. [doi:10.1038/s41598-020-74798-z](https://doi.org/10.1038/s41598-020-74798-z)

<h2 id="viral"><svg style="width:24px;height:24px;stroke:#ea580c;display:inline;vertical-align:middle;margin-right:8px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="4.2"/><path d="M12 7.8V4M12 20v-3.8M7.8 12H4M20 12h-3.8M9 9 6.3 6.3M17.7 17.7 15 15M15 9l2.7-2.7M6.3 17.7 9 15"/><circle cx="12" cy="3.4" r="1.1" fill="currentColor" stroke="none"/><circle cx="12" cy="20.6" r="1.1" fill="currentColor" stroke="none"/><circle cx="3.4" cy="12" r="1.1" fill="currentColor" stroke="none"/><circle cx="20.6" cy="12" r="1.1" fill="currentColor" stroke="none"/></svg>Viral infection & host–pathogen systems biology</h2>

- A. T. Ambikan, N. Elaldi, S. Svensson-Akusjärvi, B. Bagci, A. N. Pektas, R. Hewson, … **R. Benfeitas**, … U. Neogi. 2023. "Systems-level temporal immune-metabolic profile in Crimean-Congo hemorrhagic fever virus infection." Proceedings of the National Academy of Sciences 120(37):e2304722120. [doi:10.1073/pnas.2304722120](https://doi.org/10.1073/pnas.2304722120)
- A. T. Ambikan, H. Yang, S. Krishnan, S. Svensson Akusjärvi, S. Gupta, M. Lourda, M. Sperk, M. Arif, C. Zhang, H. Nordqvist, S. M. Ponnan, A. Sönnerborg, C. J. Treutiger, L. O'Mahony, A. Mardinoglu, **R. Benfeitas**, U. Neogi. 2022. "Multi-omics personalized network analyses highlight progressive disruption of central metabolism associated with COVID-19 severity." Cell Systems 13(8):665–681.e4. [doi:10.1016/j.cels.2022.06.006](https://doi.org/10.1016/j.cels.2022.06.006)
- U. Neogi, N. Elaldi, S. Appelberg, A. T. Ambikan, E. Kennedy, S. Dowall, B. K. Bagci, S. Gupta, J. E. Rodriguez, S. Svensson-Akusjärvi, V. M. Monteil, Á. Végvári, **R. Benfeitas**, A. C. Banerjea, F. Weber, R. Hewson, A. Mirazimi. 2022. "Multi-omics insights into host-viral response and pathogenesis in Crimean-Congo hemorrhagic fever viruses for novel therapeutic target." eLife 11:e76071. [doi:10.7554/eLife.76071](https://doi.org/10.7554/eLife.76071)
- S. Krishnan, H. Nordqvist, A. T. Ambikan, S. Gupta, M. Sperk, S. Svensson-Akusjärvi, F. Mikaeloff, **R. Benfeitas**, E. Saccon, S. M. Ponnan, J. E. Rodriguez, N. Nikouyan, A. Odeh, G. Ahlen, M. Asghar, M. Sällberg, J. Vesterbacka, P. Nowak, Á. Végvári, A. Sönnerborg, C. J. Treutiger, U. Neogi. 2021. "Metabolic perturbation associated with COVID-19 disease severity and SARS-CoV-2 replication." Molecular & Cellular Proteomics 20:100159. [doi:10.1016/j.mcpro.2021.100159](https://doi.org/10.1016/j.mcpro.2021.100159)
- S. Appelberg, S. Gupta, S. S. Akusjärvi, A. T. Ambikan, F. Mikaeloff, E. Saccon, Á. Végvári, **R. Benfeitas**, M. Sperk, M. Ståhlberg, S. Krishnan, K. Singh, J. M. Penninger, A. Mirazimi, U. Neogi. 2020. "Dysregulation in Akt/MTOR/HIF-1 Signaling Identified by Proteo-Transcriptomics of SARS-CoV-2 Infected Cells." Emerging Microbes & Infections 9(1):1748–1760. [doi:10.1080/22221751.2020.1799723](https://doi.org/10.1080/22221751.2020.1799723)

<h2 id="cancer"><svg style="width:24px;height:24px;stroke:#7c3aed;display:inline;vertical-align:middle;margin-right:8px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><circle cx="9" cy="10" r="4.3"/><circle cx="15.5" cy="14.5" r="4"/><circle cx="9" cy="10" r="1.3" fill="currentColor" stroke="none"/><circle cx="15.5" cy="14.5" r="1.3" fill="currentColor" stroke="none"/></svg>Cancer systems biology & metabolism</h2>

- F. B. Gunnarsdottir, P.-O. Bendahl, A. Johansson, **R. Benfeitas**, L. Rydén, C. Bergenfelz, A.-M. Larsson. 2023. "Serum immuno-oncology markers carry independent prognostic information in patients with newly diagnosed metastatic breast cancer, from a prospective observational study." Breast Cancer Research 25(1):29. [doi:10.1186/s13058-023-01631-6](https://doi.org/10.1186/s13058-023-01631-6)
- B. S. Song, J. S. Moon, J. Tian, H. Y. Lee, B. C. Sim, S. H. Kim, S. G. Kang, J. T. Kim, H. T. Nga, **R. Benfeitas**, Y. Kim, S. Park, R. R. Wolfe, H. S. Eun, M. Shong, S. Lee, I. Y. Kim, H. S. Yi. 2022. "Mitoribosomal defects aggravate liver cancer via aberrant glycolytic flux and T cell exhaustion." Journal for ImmunoTherapy of Cancer 10(5):e004337. [doi:10.1136/jitc-2021-004337](https://doi.org/10.1136/jitc-2021-004337)
- E. Mohammadi, M. Tahmoorespur, **R. Benfeitas**, O. Altay, A. Javadmanesh, S. Lam, A. Mardinoglu, M. H. Sekhavati. 2022. "Improvement of the performance of anticancer peptides using a drug repositioning pipeline." Biotechnology Journal 17(1):2100417. [doi:10.1002/biot.202100417](https://doi.org/10.1002/biot.202100417)
- **R. Benfeitas**, G. Bidkhori, B. Mukhopadhyay, M. Klevstig, M. Arif, C. Zhang, S. Lee, R. Cinar, J. Nielsen, M. Uhlen, J. Boren, G. Kunos, A. Mardinoglu. 2019. "Characterization of Heterogeneous Redox Responses in Hepatocellular Carcinoma Patients Using Network Analysis." EBioMedicine 40:471–487. [doi:10.1016/j.ebiom.2018.12.057](https://doi.org/10.1016/j.ebiom.2018.12.057)
- B. Turanli, C. Zhang, W. Kim, **R. Benfeitas**, M. Uhlen, K. Y. Arga, A. Mardinoglu. 2019. "Discovery of Therapeutic Agents for Prostate Cancer Using Genome-Scale Metabolic Modeling and Drug Repositioning." EBioMedicine 42:386–396. [doi:10.1016/j.ebiom.2019.03.009](https://doi.org/10.1016/j.ebiom.2019.03.009)
- G. Bidkhori, **R. Benfeitas**, E. Elmas, M. N. Kararoudi, M. Arif, M. Uhlen, J. Nielsen, A. Mardinoglu. 2018. "Metabolic Network-Based Identification and Prioritization of Anticancer Targets Based on Expression Data in Hepatocellular Carcinoma." Frontiers in Physiology 9:916. [doi:10.3389/fphys.2018.00916](https://doi.org/10.3389/fphys.2018.00916)
- G. Bidkhori, **R. Benfeitas**, M. Klevstig, C. Zhang, J. Nielsen, M. Uhlen, J. Boren, A. Mardinoglu. 2018. "Metabolic Network-Based Stratification of Hepatocellular Carcinoma Reveals Three Distinct Tumor Subtypes." Proceedings of the National Academy of Sciences 115(50):E11874–E11883. [doi:10.1073/pnas.1807305115](https://doi.org/10.1073/pnas.1807305115)
- **R. Benfeitas**, M. Uhlen, J. Nielsen, A. Mardinoglu. 2017. "New Challenges to Study Heterogeneity in Cancer Redox Metabolism." Frontiers in Cell and Developmental Biology 5:65. [doi:10.3389/fcell.2017.00065](https://doi.org/10.3389/fcell.2017.00065)
- M. Uhlen, C. Zhang, S. Lee, E. Sjöstedt, L. Fagerberg, G. Bidkhori, **R. Benfeitas**, M. Arif, Z. Liu, F. Edfors, K. Sanli, K. von Feilitzen, P. Oksvold, E. Lundberg, S. Hober, P. Nilsson, J. Mattsson, J. M. Schwenk, H. Brunnström, B. Glimelius, T. Sjöblom, P.-H. Edqvist, D. Djureinovic, P. Micke, C. Lindskog, A. Mardinoglu, F. Ponten. 2017. "A Pathology Atlas of the Human Cancer Transcriptome." Science 357(6352):eaan2507. [doi:10.1126/science.aan2507](https://doi.org/10.1126/science.aan2507)

<h2 id="cardiometabolic"><svg style="width:24px;height:24px;stroke:#e11d48;display:inline;vertical-align:middle;margin-right:8px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20.3l-1.35-1.23C5.9 14.86 3 12.24 3 8.9 3 6.2 5.1 4.1 7.8 4.1c1.5 0 2.98.7 3.95 1.8.97-1.1 2.45-1.8 3.95-1.8 2.7 0 4.8 2.1 4.8 4.8 0 3.34-2.9 5.96-7.65 10.17L12 20.3z"/></svg>Cardiometabolic & liver disease</h2>

- L. E. M. Brandão, L. Zhang, A. Grip, M.-G. Hong, E. Kåks, **R. Benfeitas**, F. Sigurdardottir, K. Blennow, H. Zetterberg, D. Espes, T. Omland, P. Emami Khoonsari, C. Benedict, J. Cedernaes. 2025. "The overlooked trio: sleep duration, sampling time and physical exercise alter levels of Olink-assessed blood biomarkers of cardiovascular risk." Biomarker Research 13(1):67. [doi:10.1186/s40364-025-00776-0](https://doi.org/10.1186/s40364-025-00776-0)
- M. Arif, M. Klevstig, **R. Benfeitas**, S. Doran, H. Turkez, M. Uhlén, M. Clausen, J. Wikström, D. Etal, C. Zhang, M. Levin, A. Mardinoglu, J. Boren. 2021. "Integrative transcriptomic analysis of tissue-specific metabolic crosstalk after myocardial infarction." eLife 10:e66921. [doi:10.7554/eLife.66921](https://elifesciences.org/articles/66921) ([highlighted in eLife](https://elifesciences.org/articles/69863))
- C. Zhang, E. Bjornson, M. Arif, A. Tebani, A. Lovric, **R. Benfeitas**, M. Ozcan, K. Juszczak, W. Kim, J. T. Kim, G. Bidkhori, M. Ståhlman, P. Bergh, M. Adiels, H. Turkez, M. Taskinen, J. Bosley, H. Marschall, J. Nielsen, M. Uhlén, J. Borén, A. Mardinoglu. 2020. "The Acute Effect of Metabolic Cofactor Supplementation: A Potential Therapeutic Strategy against Non-alcoholic Fatty Liver Disease." Molecular Systems Biology 16(4):e9495. [doi:10.15252/msb.20209495](https://doi.org/10.15252/msb.20209495)
- A. Lovric, M. Granér, E. Bjornson, M. Arif, **R. Benfeitas**, K. Nyman, M. Ståhlman, M. O. Pentikäinen, J. Lundbom, A. Hakkarainen, R. Sirén, M. S. Nieminen, N. Lundbom, K. Lauerma, M. R. Taskinen, A. Mardinoglu, J. Boren. 2018. "Characterization of Different Fat Depots in NAFLD Using Inflammation-Associated Proteome, Lipidome and Metabolome." Scientific Reports 8(1):14200. [doi:10.1038/s41598-018-31865-w](https://doi.org/10.1038/s41598-018-31865-w)
- D. Rosario, **R. Benfeitas**, G. Bidkhori, C. Zhang, M. Uhlen, S. Shoaie, A. Mardinoglu. 2018. "Understanding the Representative Gut Microbiota Dysbiosis in Metformin-Treated Type 2 Diabetes Patients Using Genome-Scale Metabolic Modeling." Frontiers in Physiology 9:775. [doi:10.3389/fphys.2018.00775](https://doi.org/10.3389/fphys.2018.00775)

<h2 id="neuro"><svg style="width:24px;height:24px;stroke:#4f46e5;display:inline;vertical-align:middle;margin-right:8px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5.5V19"/><path d="M12 6.5C11.5 5 10.3 4.2 9 4.2 7.3 4.2 6 5.5 6 7.2c-1 .3-1.7 1.2-1.7 2.3 0 .5.1.9.3 1.3-.7.5-1.1 1.3-1.1 2.2 0 1 .5 1.8 1.3 2.3-.1 1.6 1.2 3 2.9 3 1.3 0 2.4-.8 2.9-2"/><path d="M12 6.5C12.5 5 13.7 4.2 15 4.2 16.7 4.2 18 5.5 18 7.2c1 .3 1.7 1.2 1.7 2.3 0 .5-.1.9-.3 1.3.7.5 1.1 1.3 1.1 2.2 0 1-.5 1.8-1.3 2.3.1 1.6-1.2 3-2.9 3-1.3 0-2.4-.8-2.9-2"/></svg>Neurodegeneration & ageing</h2>

- S. Bauer, L. Dittrich, L. Kaczmarczyk, M. Schleif, **R. Benfeitas**, W. S. Jackson. 2022. "Translatome profiling in fatal familial insomnia implicates TOR signaling in somatostatin neurons." Life Science Alliance 5(11):e202201530. [doi:10.26508/lsa.202201530](https://doi.org/10.26508/lsa.202201530)
- H. Haytural, **R. Benfeitas**, S. Schedin-Weiss, E. Bereczki, M. Rezeli, R. D. Unwin, X. Wang, E. B. Dammer, E. C. B. Johnson, N. T. Seyfried, B. Winblad, B. M. Tijms, P. J. Visser, S. Frykman, L. O. Tjernberg. 2021. "Insights into the changes in the proteome of Alzheimer disease elucidated by a meta-analysis." Scientific Data 8:312. [doi:10.1038/s41597-021-01090-8](https://doi.org/10.1038/s41597-021-01090-8)
- S. Lam, N. Hartmann, **R. Benfeitas**, C. Zhang, M. Arif, H. Turkez, M. Uhlén, C. Englert, R. Knight, A. Mardinoglu. 2021. "Systems analysis reveals ageing-related perturbations in retinoids and sex hormones in Alzheimer's and Parkinson's diseases." Biomedicines 9(10):1310. [doi:10.3390/biomedicines9101310](https://doi.org/10.3390/biomedicines9101310)

<h2 id="methods"><svg style="width:24px;height:24px;stroke:#059669;display:inline;vertical-align:middle;margin-right:8px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><line x1="6.6" y1="6.8" x2="17.4" y2="7.2"/><line x1="7" y1="7.8" x2="11.2" y2="15.2"/><line x1="17" y1="8.2" x2="12.8" y2="15.4"/><circle cx="5.5" cy="6.5" r="2.1"/><circle cx="18.5" cy="7.2" r="2.1"/><circle cx="12" cy="17" r="2.1"/></svg>Computational methods, tools & modeling</h2>

- M. Anton, E. Almaas, **R. Benfeitas**, S. Benito-Vaquerizo, L. M. Blank, A. Dräger, et al. 2023. "standard-GEM: standardization of open-source genome-scale metabolic models." bioRxiv. [bioRxiv](https://www.biorxiv.org/content/10.1101/2023.03.21.512712) *(preprint)*
- E. Mohammadi, **R. Benfeitas**, H. Turkez, J. Boren, J. Nielsen, M. Uhlen, A. Mardinoglu. 2020. "Applications of Genome-Wide Screening and Systems Biology Approaches in Drug Repositioning." Cancers 12(9):2694. [doi:10.3390/cancers12092694](https://doi.org/10.3390/cancers12092694)
- C. Zhang, S. Lee, G. Bidkhori, **R. Benfeitas**, A. Lovric, S. Chen, M. Uhlen, J. Nielsen, A. Mardinoglu. 2019. "RMetD2: A Tool for Integration of Relative Transcriptomics Data into Genome-Scale Metabolic Models." bioRxiv 663096. [bioRxiv](https://www.biorxiv.org/content/10.1101/663096v1.full) *(preprint)*
- S. Lee, C. Zhang, M. Arif, Z. Liu, **R. Benfeitas**, G. Bidkhori, S. Deshmukh, M. Al Shobky, A. Lovric, J. Boren, J. Nielsen, M. Uhlen, A. Mardinoglu. 2018. "TCSBN: A Database of Tissue and Cancer Specific Biological Networks." Nucleic Acids Research 46(D1):D595–D600. [doi:10.1093/nar/gkx994](https://doi.org/10.1093/nar/gkx994)
- C. Zhang, G. Bidkhori, **R. Benfeitas**, S. Lee, M. Arif, M. Uhlén, A. Mardinoglu. 2018. "ESS: A Tool for Genome-Scale Quantification of Essentiality Score for Reaction/Genes in Constraint-Based Modeling." Frontiers in Physiology 9:1355. [doi:10.3389/fphys.2018.01355](https://doi.org/10.3389/fphys.2018.01355)
- J. Comas, **R. Benfeitas**, E. Vilaprinyo, A. Sorribas, F. Solsona, G. Farré, J. Berman, U. Zorrilla, T. Capell, G. Sandmann, C. Zhu, P. Christou, R. Alves. 2016. "Identification of Line-Specific Strategies for Improving Carotenoid Production in Synthetic Maize through Data-Driven Mathematical Modeling." The Plant Journal 87(5):455–471. [doi:10.1111/tpj.13210](https://doi.org/10.1111/tpj.13210)
- **R. Benfeitas**, G. Selvaggio, F. Antunes, P. M. B. M. Coelho, A. Salvador. 2014. "Hydrogen Peroxide Metabolism and Sensing in Human Erythrocytes: A Validated Kinetic Model and Reappraisal of the Role of Peroxiredoxin II." Free Radical Biology & Medicine 74:35–49. [doi:10.1016/j.freeradbiomed.2014.06.007](https://doi.org/10.1016/j.freeradbiomed.2014.06.007)

<h2 id="infrastructure"><svg style="width:24px;height:24px;stroke:#475569;display:inline;vertical-align:middle;margin-right:8px" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2c5.5 0 10 4.5 10 10s-4.5 10-10 10S2 17.5 2 12 6.5 2 12 2z"/><circle cx="8" cy="12" r="1.5" fill="currentColor" stroke="none"/><circle cx="12" cy="7.5" r="1.5" fill="currentColor" stroke="none"/><circle cx="16" cy="12" r="1.5" fill="currentColor" stroke="none"/><circle cx="12" cy="16.5" r="1.5" fill="currentColor" stroke="none"/></svg>Research infrastructure, training & community</h2>

- V. Martins Dos Santos, M. Anton, B. Szomolay, M. Ostaszewski, I. Arts, **R. Benfeitas**, et al. 2024. "Systems Biology in ELIXIR: modelling in the spotlight." F1000Research 11:ELIXIR-1265. [F1000Research](https://f1000research.com/articles/11-1265)
- E. Kronander, J. Lindvall, N. Norgren, L. Vasquez, M. Anton, D. Bampalikis, **R. Benfeitas**, et al. 2024. "NBIS training report 2022–2023." F1000Research 13:900. [F1000Research](https://f1000research.com/articles/13-900)
- M. Anton, **R. Benfeitas**, J. M. Lindvall, N. Norgren, B. Persson. 2022. "NBIS Training Report 2020–2021." F1000Research 11:618. [F1000Research](https://f1000research.com/articles/11-618)

</div>
