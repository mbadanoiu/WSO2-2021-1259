# WSO2-2021-1259: H2 RCE via Malicious JDBC Connection String in WSO2 ESB

Due to the improper input validation, a remote code execution attack could be carried out using malicious H2 JDBC Connection Strings.

### Vendor Disclosure:

The vendor's disclosure and fix for this vulnerability can be found [here](https://security.docs.wso2.com/en/latest/security-announcements/security-advisories/2022/WSO2-2021-1259/).

### Why no CVE?

Neither me nor the vendor requested a CVE for this vulnerability.

### Requirements:

This vulnerability requires:
<br/>
- Valid user credentials

### Proof Of Concept:

More details and the exploitation process can be found in this [PDF](https://github.com/mbadanoiu/WSO2-2021-1259/blob/main/WSO2%20ESB%20-%20WSO2-2021-1259.pdf).

