# Web-API-Schedule-job


各系統API介接


1


前台系統會提供 Json 格式將資料透過 Rest API 寫入中台資料庫


<img width="767" alt="Bra2" src="https://github.com/user-attachments/assets/d8ceac4e-8a25-4ef5-a77c-962aa1fa1c54">


2


中台資料庫將資料透過 Web service 寫入 ERP，ERP 回饋成功或失敗資訊回中台資料庫


![Bra5](https://github.com/user-attachments/assets/8ebce96d-af0c-4c5a-b7ef-1226cc61bd68)


3


中台資料庫透過排程(Schedule Job)將資料組成 XML 並且呼叫 Web service


<img width="802" alt="Bra3" src="https://github.com/user-attachments/assets/5c6a2626-c43d-4fbe-b3bb-944d601f7aee">


4

寫入 ERP 對應的主檔或交易單據


<img width="951" alt="Bra4" src="https://github.com/user-attachments/assets/804f2d6f-4190-44b3-a970-96eb4ba28ad1">

