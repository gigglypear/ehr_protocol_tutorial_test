Overview
========

.. _inspiration:

Introduction
------------

Electronic Health Records (EHRs) are the digital versions of patients' medical histories and interactions with healthcare systems. Over the past decade, their use has seen a remarkable increase worldwide. In the U.S., a significant push came from the Health Information Technology for Economic and Clinical Health (HITECH) Act of 2009, which came with a hefty $19 billion incentive for healthcare institutions. This act aimed to enhance patient care quality, safety, and efficiency through EHR systems. Since then, EHR adoption in the U.S. has seen a dramatic rise, multiplying over four times.
 
Beyond direct patient care, EHRs have revolutionized biomedical research. Unlike traditional clinical study data, EHR data covers large and diverse populations, is collected over extended periods, and includes detailed information on diagnoses, lab tests, procedures, prescriptions, and clinical notes. This wealth of data has opened new doors for research, such as using artificial intelligence (AI) to speed up clinical trials recruitment, forming global networks for real-time studies (e.g., on COVID-19), and developing prediction models for conditions like sepsis before symptoms even appear.

.. admonition:: Advantage
   :class: advantage

   The use of EHRs brings numerous benefits in the context of biomedical research, such as detailed healthcare documentation, better data security, efficient healthcare process management, and streamlined medical billing. They also make it easier for healthcare providers to exchange information and communicate about a patient's care, thanks to interoperable systems.


.. admonition:: Challenge
   :class: disadvantage

   However, working with EHR data isn't without its challenges. EHR data wasn't originally designed for research, making it complex and sometimes unreliable due to issues like missing or incorrect data. Preparing EHR data for research also requires significant effort to ensure it's clean, complete, and ready for analysis.


EHR data can be broadly categorized into two types: structured and unstructured. Both types of data play crucial roles in healthcare analytics, patient care, and clinical decision-making. In this tutorial, we will guide you through understanding various EHR data structures and the steps needed to prepare them for research purposes. We'll also walk you through an example using the MIMIC-IV database, a rich source of intensive care EHR data available for research.


.. _StructuredData:

Structured Data
---------------

Structured EHR data encompasses information organized according to a specific schema, including a fixed set of fields and file types, which enables easy search and analysis by software applications. It can be thought as the neatly organized sections of a library, where every book and journal have its specific location and label, making it easy to find and use. Structured EHR data typically comprises patient identifiers, diagnoses, laboratory test results, imaging findings, medications, procedures performed, and patient demographics. In this section, we’ll dive into these pieces of structured data and explore how certain universal coding systems are applied to represent them, facilitating organized and efficient downstream analysis.

 
Codified EHR data pertains to four main categories: diagnosis, medications, lab measurements, and procedures. To standardize these data across different healthcare systems, health policymakers and professionals have established various coding systems. These systems use alphanumeric codes to represent complex medical information in a simplified, unified format, which aids in the uniform representation and analysis of health data.


Try Table
^^^^^^^^^^^
+------------------------+--------------------------+------------------------+
| Type of Data           | Information Included     | Coding System Involved |
+========================+==========================+========================+
| Domain 1               | XXXXXXXX                 | XXXXXXXX               |
+------------------------+--------------------------+------------------------+
| Domain 2               | XXXXXXXX                 | XXXXXXXX               |
+------------------------+--------------------------+------------------------+

Disease Codes
^^^^^^^^^^^^^

Disease codes are essential for encoding diseases, symptoms, and patient conditions into unique identifiers. Two primary examples of these codes are the International Classification of Diseases (ICD) codes and Phecodes, each serving distinct purposes within healthcare settings and research.
 
**ICD Codes**
 
The ICD codes, maintained by the World Health Organization (WHO), offer a comprehensive catalog of diseases, symptoms, abnormal findings, and injuries. These codes are a cornerstone in recording medical data within EHRs, facilitating a standardized approach to track health trends and statistics worldwide. Hospitals and countries might use different ICD versions, with the WHO regularly updating these codes to reflect new medical knowledge. In the context of EHR data, the most relevant versions are ICD-9 and ICD-10, with the United States adopting an enhanced version known as the "clinical modification" (CM), for example, ICD-9-CM and ICD-10-CM. Notably, ICD-10-CM includes significantly more diagnosis codes than its predecessor, ICD-9-CM, enhancing the detail and specificity of health data recording.
 
**Phecodes**
 
Phecodes complement ICD codes by categorizing these detailed codes into clinically meaningful phenotypes, addressing the issue of ICD codes being overly detailed for research purposes. Byrouping related ICD codes, Phecodes facilitate the analysis of health data by simplifying and structuring the vast array of diagnoses into manageable categories. The latest version of Phecodes efficiently condenses thousands of ICD-9-CM and ICD-10-CM codes into a more concise set of phenotypes, creating a hierarchical system that ranges from broad phenotypes to specific medical findings.
 
Differences between ICD Codes and Phecodes : (to be placed in a colored text box)
 
This hierarchical organization of ICD codes and Phecodes enables researchers and healthcare providers to navigate from general health conditions to specific diagnoses, providing a structured framework for analyzing patient data. The ICD-Phecode system includes detailed mappings between ICD codes, their descriptions, corresponding Phecodes, phenotypes, and the range of excluded codes for each phenotype, offering a comprehensive tool for health data analysis.


Try code-block
^^^^^^^^^^^^^^^

.. code-block:: console

   (.venv) $ pip install tensorflow




.. _UnstructuredData:

Unstructured Data
----------------------

Try note

.. note::
   This is note text. Use a note for information you want the user to
   pay particular attention to.

Try warning

.. warning::
    This is warning text. Use a warning for information the user must
    understand to avoid negative consequences.


Installation Guide
===================


.. _system-prerequisites:

Software Versions Pre-requisite
-------------------------------

For quick instalation ......


Install Steps
--------------

Step 1 XXX:
  - x
  - y
  - z

Step 2 YYY:

  - 111
     - 222
