# gcloud-websecurityscanner-vpcsc-test
These system variables needs to set in order to perform positive and negative vpcsc tests.
1. GOOGLE_CLOUD_TESTS_IN_VPCSC must be set to True.
2. GOOGLE_CLOUD_TESTS_WEB_SECURITY_SCANNER_INSIDE_VPC_PROJECT must point to project that resides inside vpcsc perimeter.
3. GOOGLE_CLOUD_TESTS_WEB_SECURITY_SCANNER_INSIDE_VPC_HOSTNAME must point to weblink that resides inside vpcsc perimeter.
4. GOOGLE_CLOUD_TESTS_WEB_SECURITY_SCANNER_INSIDE_VPC_CREDENTIALS must point to credentials of service account that resides inside vpcsc perimeter.
5. GOOGLE_APPLICATION_CREDENTIALS must pont to credentials of service account that resides inside VPCSC perimeter. It can same as above.
6. GOOGLE_CLOUD_TESTS_WEB_SECURITY_SCANNER_OUTSIDE_VPC_PROJECT must point to project that resides outside vpcsc perimeter.
7. GOOGLE_CLOUD_TESTS_WEB_SECURITY_SCANNER_OUTSIDE_VPC_HOSTNAME must point to weblink that resides outside vpcsc perimeter.
8. GOOGLE_CLOUD_TESTS_WEB_SECURITY_SCANNER_OUTSIDE_VPC_CREDENTIALS must point to credentials of service account that resides outside vpcsc perimeter.
