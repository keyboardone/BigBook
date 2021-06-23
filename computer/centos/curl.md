> **发送POST请求：**

`curl --request POST \    
  --url 'http://ai.hx168.com.cn:8080/newsservice/api/stockNews?scenarioId=scenario_stock_detail' \    
  --header 'content-type: application/json' \    
  --data '{    
 "deviceId": "10014476451001447645",    
 "userId": "10014476451001447645",    
 "accountId": "1001447645",    
 "stockCode": "600449",    
 "status": "1",    
 "requireNum": 20,    
 "column": "",    
 "lastItemId": ""    
}'`



> **Https免认证：**

`curl -k --insecure "`[`https://10.211.7.74:443/appWeb/sso/servlet/json?FuncID=2088012&__funcid=2088012&__action=2000&i_userid=1074143867592245248&i_dyid_fid=1588807&i_ywlx=9&i_qdlx=14&funcNo=2088012&i_type=2`](https://10.211.7.74:443/appWeb/sso/servlet/json?FuncID=2088012&__funcid=2088012&__action=2000&i_userid=1074143867592245248&i_dyid_fid=1588807&i_ywlx=9&i_qdlx=14&funcNo=2088012&i_type=2)`"`

