# Call Center data analysis using Azure AI services and Azure OpenAI 

## Overview

In this hands-on lab, you will learn how to effectively extract insights from customer conversations of audio type, within a call center using Azure AI services and Azure OpenAI Service. You'll get the opportunity to apply real-time and post-call analytics to enhance call center efficiency and elevate customer satisfaction. This immersive experience will guide you through a diverse range of topics related to data processing, audio transcription, sentiment analysis, and data visualization, allowing you to master real-time and post-call analytics.

## Architecture diagram

 ![](images/archdiag.png)

## Dataflow

 * A phone call between an agent and a customer is recorded and stored in Azure Blob Storage.
 * Azure AI Speech is used to transcribe audio files. The transcription results are persisted in Blob Storage.
 * Azure OpenAI is used to process the transcript and extract entities, summarize the conversation, and analyze sentiments. The processed output is stored in SQL Database.
 * Power BI is a software-as-a-service (SaaS) that provides visual and interactive insights for business analytics. It provides transformation capabilities and connects to data sources.

## Lab Overview

In this Hands-on-lab, you will perform the following tasks.

+ Task 1: Provision Azure resources.
+ Task 2: Upload audio files.
+ Task 3: Visualization using PowerBI Report and Dashboard.
