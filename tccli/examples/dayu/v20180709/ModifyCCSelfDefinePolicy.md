**Example 1: 修改CC自定义策略**



Input: 

```
tccli dayu ModifyCCSelfDefinePolicy --cli-unfold-argument  \
    --Business bgp \
    --Id bgp-000000xe \
    --SetId ccPolicy-000000sd \
    --Policy.Name test \
    --Policy.Smode speedlimit \
    --Policy.Frequency 1002 \
    --Policy.IpList 1.1.1.1
```

Output: 
```
{
    "Response": {
        "RequestId": "eac6b301-a322-493a-8e36-83b295459397",
        "Success": {
            "Code": "Success",
            "Message": "Success"
        }
    }
}
```

