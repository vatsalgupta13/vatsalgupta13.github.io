---
layout: page
title: Blockchain-based Electronic Health Records (EHR) Management with OCR Assisted Summarization
description: A decentralized application built with ReactJS, Flask, Solidity, and IPFS, that allows users to store and retrieve their medical records securely. The application has built-in OCR capabilities that enable users and their trusted doctors to analyze the uploaded reports by extracting critical medical terms, including disease names and prescribed drugs.
# img: assets/img/project_1.jpeg
importance: 1
category: Major
---
<a href="https://github.com/vatsalgupta13/Health-book" target="_blank"><i class="fab fa-github"></i> Code</a> &nbsp; &nbsp;
<a href="https://github.com/vatsalgupta13/Health-book/blob/main/Reports/Major%20Project%20Report%20Vatsal%2017104060.pdf" target="_blank"><i class="fa fa-book"></i> Project Report</a>
<hr>
The advantages of having a secure, immutable and decentralized Electronic Health Record (EHR) database:
<ul>
<li>Single version of the truth verified by the consensus of the participating hospitals</li>
<li>Easy to share selective or all EHRs as consented by the patient</li>
<li>Full medical history of a patient at one single point</li>
<li>Easy verification of medical prescription</li>
<li>Redacted EHRs for research purposes</li>
<li>Increased transparency</li>
<li>No insurance fraud</li>
</ul>

This application app has 2 main users:
<ul>
<li>Patients, who can:
<ol type="a">
<li>Upload a document to the blockchain. The document is added as a node in IPFS which returns a hash. The hash is then stored on the blockchain.</li>
<li>View the uploaded documents.</li>
<li>Analyse the uploaded documents. The text from the document is extracted and NER (Named Entity Recognition) is performed on the text using BERN (Biomedical Named Entity recognition and multi-type Normalization).</li>
<li>Analyse their reports to find keywords related to Drugs or Diseases.</li>
<li>Add a trusted doctor to view their medical documents.</li>
</ol>
</li>
<li>Doctors, who can:
<ol type="a">
<li>Upload a medical document about a certain patient to the blockchain.</li>
<li>View a certain patient's uploaded document.</li>
</ol>
</li>
</ul>
<br>
{% responsive_image path: assets/img/project_1.png title: "example image" class: "img-fluid rounded z-depth-1" %}

