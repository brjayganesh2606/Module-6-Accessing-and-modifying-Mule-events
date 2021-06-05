Module-6-Accessing-and-modifying-Mule-events

1)Walkthrough6-1: Vieweventdata

After deploying,

![image](https://user-images.githubusercontent.com/70746268/120813046-28b42800-c56b-11eb-90f9-05f8820bc668.png)

Event data in console,

![image](https://user-images.githubusercontent.com/70746268/120813194-4bded780-c56b-11eb-81d8-9891d5dcdef1.png)

Event data in console after sending with query parameters in request,

![image](https://user-images.githubusercontent.com/70746268/120813623-b0019b80-c56b-11eb-9f20-ac7c0e886f02.png)

2)Walkthrough6-2: Debug a Mule application  

After adding breakpoint at Hello,

![image](https://user-images.githubusercontent.com/70746268/120814823-dd027e00-c56c-11eb-9aac-1f1444d9d897.png)

Moved to next processor,

![image](https://user-images.githubusercontent.com/70746268/120815050-1affa200-c56d-11eb-802e-d0629de4b0fe.png)

After setting timeout,

![image](https://user-images.githubusercontent.com/70746268/120817457-5d29e300-c56f-11eb-8463-4f786d04986e.png)

3)Walkthrough6-3: Trackevent data as it moves in and out of a Mule application

![image](https://user-images.githubusercontent.com/70746268/120821889-792f8380-c573-11eb-95ce-2ef7578a28c4.png)

In goodbye flow,

![image](https://user-images.githubusercontent.com/70746268/120822057-a5e39b00-c573-11eb-991d-91d0044a0ed0.png)

![image](https://user-images.githubusercontent.com/70746268/120822105-b3992080-c573-11eb-8274-1313fcd13ef8.png)

4)Walkthrough 6-4: Setrequest and response data

![image](https://user-images.githubusercontent.com/70746268/120885180-2c948880-c605-11eb-8c36-f2459020905a.png)

![image](https://user-images.githubusercontent.com/70746268/120885348-0d4a2b00-c606-11eb-99bf-70b27f47c8c4.png)

5)Walkthrough6-5: Getand seteventdatausing DataWeave expressions

After using 'Goodbye jayyyy....' in set payload of goodbye flow ,

![image](https://user-images.githubusercontent.com/70746268/120885549-4767fc80-c607-11eb-940a-7b5b8a411a53.png)

After using upper('Goodbye jayyyy....') in set payload of goodbye flow ,

![image](https://user-images.githubusercontent.com/70746268/120885686-c826f880-c607-11eb-9c23-4c7675b10968.png)

After using  #[payload] in message field in logger in hello flow ,

![image](https://user-images.githubusercontent.com/70746268/120885755-2522ae80-c608-11eb-89aa-28610d1f65d1.png)

After using  Message: #[payload] in message field in logger in hello flow ,

![image](https://user-images.githubusercontent.com/70746268/120885869-c3167900-c608-11eb-91dd-2fd3e2bc4bbf.png)

After using 'Message:' ++ payload in message field in logger in hello flow ,

![image](https://user-images.githubusercontent.com/70746268/120885975-4506a200-c609-11eb-8360-06dac18c2eb5.png)

After using #[attributes.queryParams.fullName] in message field in logger in goodbye flow ,

![image](https://user-images.githubusercontent.com/70746268/120891746-d2f18580-c627-11eb-8d3c-9461910f701e.png)

After using #[upper('Goodbye') ++ ' '++ attributes.queryParams.fullName as String] in message field in logger in goodbye flow ,

![image](https://user-images.githubusercontent.com/70746268/120891809-3bd8fd80-c628-11eb-9942-9cf1ce6a1e53.png)

After using attributes.queryParams.fname in GET /goodbye request in hello flow ,

![image](https://user-images.githubusercontent.com/70746268/120891939-0b459380-c629-11eb-8066-0d4401a7ac15.png)

Removing paramenter in query,

![image](https://user-images.githubusercontent.com/70746268/120891994-6f685780-c629-11eb-84bb-2002cc153c12.png)

![image](https://user-images.githubusercontent.com/70746268/120892302-3cbf5e80-c62b-11eb-9001-34ea8f801685.png)

6)Walkthrough6-6: Set and get variables

![image](https://user-images.githubusercontent.com/70746268/120893364-8e1e1c80-c630-11eb-8c3e-94e4e72c2ee1.png)









