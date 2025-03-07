# gcp-batch-parabricks
2025 GCP batch with Parabricks 4.4.0 code repo


Prepare a GCS bucket - in this example. The bucket is named thomashk-test2

then upload the bash files to the GCS bucket. 
parabricks-4-4-0-fq2bam-haplotypecaller-2gpus.sh
parabricks-4-4-0-fq2bam-haplotypecaller-8gpus.sh


Submiitting a Google Batch job for the processsing: 
gcloud batch jobs submit <job name> --location us-central1 --config cb-parabricks-4-4-0-fq2bam-haplotypecaller-l4-8gpus-gsutil.json


