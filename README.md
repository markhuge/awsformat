# awsformat

I need to output aws things in various formats for documentation purposes.
I'm just adding things as I need them.

## Installation
Assumes [aws cli](https://aws.amazon.com/cli/) is installed and setup.

`go get github.com/markhuge/awsformat`


## Usage

`awsfortmat -o <output format> <awscli command>`

Example: `awsformat -o csv lambda list-functions`

### Supported Commands

- `aws lambda list-functions`

### Supported Output formats

- csv
- jira-table
- html-table
- markdown-table
