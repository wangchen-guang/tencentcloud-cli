**Example 1: 查询服务自定义域名列表**



Input: 

```
tccli apigateway DescribeServiceSubDomains --cli-unfold-argument  \
    --ServiceId service-19c5fnhy
```

Output: 
```
{
    "Response": {
        "Result": {
            "TotalCount": 1,
            "DomainSet": [
                {
                    "DomainName": "xxxxxxxxx",
                    "Status": 1,
                    "CertificateId": "",
                    "IsDefaultMapping": false,
                    "Protocol": "http",
                    "NetType": "OUTER"
                }
            ]
        },
        "RequestId": "01c56ec2-6a40-46bc-bdf6-8b273d4bec93"
    }
}
```

