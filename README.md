● 要求三：SQL CRUD  
<pre>
1. 使⽤ INSERT 指令新增⼀筆資料到 member 資料表中，這筆資料的 username 和password 欄位必須是 test。接著繼續新增⾄少 4 筆隨意的資料。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/b7521cc0-d08e-47a0-bb76-85c404d911c5)
<pre>
2. 使⽤ SELECT 指令取得所有在 member 資料表中的會員資料。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/208534dc-6b96-48c4-bb14-7e7b37c64944)
<pre>
3. 使⽤ SELECT 指令取得所有在 member 資料表中的會員資料，並按照 time 欄位，由近到遠排序。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/1c983ea2-ebbd-4677-a5b2-bf22df9d4750)
<pre>
4. 使⽤ SELECT 指令取得 member 資料表中第 2 到第 4 筆共三筆資料，並按照 time 欄位，由近到遠排序。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/3d32f946-778a-47e2-a55b-3fbe3e747834)
<pre>
5. 使⽤ SELECT 指令取得欄位 username 是 test 的會員資料。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/4668d001-93b6-4b62-8b0d-7c567598a388)
<pre>
6. 使⽤ SELECT 指令取得欄位 username 是 test、且欄位 password 也是 test 的資料。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/99c6a8e3-9d1c-4a7d-b76c-e4820865188c)
<pre>
7.使⽤ UPDATE 指令更新欄位 username 是 test 的會員資料，將資料中的 name 欄位改成 test2。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/d3b9232c-57a0-4d05-92ca-1edc66a0c8f8)  
● 要求四：SQL Aggregate Functions  
<pre>
1. 取得 member 資料表中，總共有幾筆資料 ( 幾位會員 )。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/000c817d-1e6d-4d61-9f7f-6eaa94de77d9)
<pre>
2. 取得 member 資料表中，所有會員 follower_count 欄位的總和。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/9ad33ec2-af8a-4a25-9596-5ac8474354de)
<pre>
3. 取得 member 資料表中，所有會員 follower_count 欄位的平均數。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/166642c0-6e6d-4117-bd71-586e5176db41)  
● 要求五：：SQL JOIN
<pre>
1. 使⽤ SELECT 搭配 JOIN 語法，取得所有留⾔，結果須包含留⾔者的姓名。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/d1ff4a4d-fa15-40a8-af75-5c229f728a8b)
<pre>
2. 使⽤ SELECT 搭配 JOIN 語法，取得 member 資料表中欄位 username 是 test 的所有留⾔，資料中須包含留⾔者的姓名。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/d996cd2d-b213-4e7f-af4a-7013e79f1477)
<pre>
3. 使⽤ SELECT、SQL Aggregate Functions 搭配 JOIN 語法，取得 member 資料表中欄位 username 是 test 的所有留⾔平均按讚數。
</pre>
![image](https://github.com/Shiuan-Chang/RSChang_week5.github.io/assets/135259951/12a18528-9eb1-4bb4-aaa0-b57572cf9afe)
