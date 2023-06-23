# Cloud Custodian

- way to automate policy
- for non programmers, declarative way

## Commands sample: 
custodian run --output-dir output .\s3-buckets.yml
custodian run --dry-run --output-dir output .\s3-buckets.yml
custodian report --output-dir output .\s3-buckets.yml
