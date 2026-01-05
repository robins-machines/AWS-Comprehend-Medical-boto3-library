# AWS-Comprehend-Medical-boto3-library
Use of the AWS boto3 library and the detect_phi operation to remove PII and PHI from tabular health data. 
The removal of Protected Health Information and Personally Identifable Information (PHI/PII) from tabular electronic health record data in accordance with HIPAA. 
AWS provides several tools to identify and redact sensitive medical information from unstructured text:
•	Amazon Comprehend Medical: This is a HIPAA-eligible NLP service specifically trained to extract and identify medical entities like medications, procedures, and PHI from unstructured clinical notes. It can automatically detect and label PHI elements such as patient names, medical record numbers, and contact details.
•	Amazon HealthLake: A purpose-built service for storing and analyzing health data. It uses integrated medical NLP to automatically identify and tag PHI in raw medical text upon ingestion, organizing it into a V4 FHIR specification.
•	AWS Glue: Offers a "Detect PII" transform in Glue Studio that uses pattern matching and machine learning to identify and redact sensitive data at the row or column level.
