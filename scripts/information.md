Bronze Bucket Name - yt-data-pipeline-bronze-ap-south-1-de  
Silver Bucket Name - yt-data-pipeline-silver-ap-south-1-de
Gold Bucket Name - yt-data-pipeline-gold-ap-south-1-de 
Script Bucket - yt-data-pipeline-script-ap-south-1-de

SNS ARN - arn:aws:sns:ap-south-1:884087662813:yt-data-pipeline-alerts-de:4095fb9f-e036-4ba0-a09f-c0a74a24da98 

Glue Bronze - yt_pipeline_bronze_de
Glue Gold - yt_pipeline_gold_de
Glue Silver - yt_pipeline_silver_de

--bronze_database  yt_pipeline_bronze_de
--bronze_table  raw_statistics
--silver_bucket  yt-data-pipeline-silver-ap-south-1-de
--silver_database  yt_pipeline_silver_de
--silver_table  clean_statistics

--silver_database  yt_pipeline_silver_de
--gold_bucket  yt-data-pipeline-gold-ap-south-1-de
--gold_database   yt_pipeline_gold_de
