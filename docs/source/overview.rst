Overview
=====

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


.. _Structured Data:

Try Table

+------------------------+--------------------------+------------------------+
| Type of Data           | Information Included     | Coding System Involved |
+========================+==========================+========================+
| Domain 1               | XXXXXXXX                 | XXXXXXXX               |
+------------------------+--------------------------+------------------------+
| Domain 2               | XXXXXXXX                 | XXXXXXXX               |
+------------------------+--------------------------+------------------------+

Try code-block

.. code-block:: console

   (.venv) $ pip install tensorflow




.. _Unstructured Data:
----------------

Try note

.. note::
   This is note text. Use a note for information you want the user to
   pay particular attention to.

Try warning

.. warning::
    This is warning text. Use a warning for information the user must
    understand to avoid negative consequences.