## 0.1.2 (Unreleased)

IMPROVEMENTS:

* backend: add `ssl_ca_cert` option [GH-11]
* s3_logging: Support message_type attribute [GH-14]
* gcs_logging: Optionally use env variable for credentials [GH-15]

BUG FIXES: 

* s3logging: default S3 domain to `s3.amazonaws.com` to match api default [GH-12]

## 0.1.1 (June 21, 2017)

NOTES:

Bumping the provider version to get around provider caching issues - still same functionality

## 0.1.0 (June 20, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
