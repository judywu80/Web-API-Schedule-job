# Web-API-Schedule-job


各系統API介接


1


前台系統提供 Json 格式將資料透過 Rest API 寫入中台資料庫


<img width="767" alt="Bra2" src="https://github.com/user-attachments/assets/d8ceac4e-8a25-4ef5-a77c-962aa1fa1c54">


2


中台資料庫將資料透過 Web service 寫入 ERP，ERP 回饋成功或失敗資訊回中台資料庫


※　另外根據不同資料狀態（新增／修改）和資料驗證（重複／必填）做處理


![Bra2](https://github.com/user-attachments/assets/4063b577-ca3a-43b6-bcbb-f19c77670d16)



3


中台資料庫透過 自動排程(Schedule Job)將資料組成 XML 並且呼叫 Web service 寫入 ERP 對應的主檔或交易單據


<img width="802" alt="Bra3" src="https://github.com/user-attachments/assets/5c6a2626-c43d-4fbe-b3bb-944d601f7aee">


4


（以其他範例示意）



<img width="941" alt="Bra3-2" src="https://github.com/user-attachments/assets/51ae3351-184b-4078-bef0-2f2196bd126c">


