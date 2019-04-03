# s3_pub_obj

This script will search an s3 bucket for public objects, and return the key of the public object.

# Installation
This script uses python 2.7 and the `boto3` library from the AWS SDK. To use this script:
1. Download the [installer for pip, the python package manager](https://pip.pypa.io/en/stable/installing/)
2. Install pip: `python get-pip.py --user`
3. Install dependencies: `pip install -r requirements.txt`

# Usage
`./s3_pub_obj $YOUR_BUCKET`

# Notes
This script assumes appropriate access permissions to `$YOUR_BUCKET`
