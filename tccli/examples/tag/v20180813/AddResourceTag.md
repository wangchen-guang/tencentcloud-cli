**Example 1: 给标签关联资源**



Input: 

```
tccli tag AddResourceTag --cli-unfold-argument  \
    --TagKey testTagKey \
    --TagValue testTagValue \
    --Resource qcs::cvm:ap-beijing:uin/1234567:instance/ins-123
```

Output: 
```
{
    "Response": {
        "RequestId": "3c140219-cfe9-470e-b241-907877d6fb03"
    }
}
```

