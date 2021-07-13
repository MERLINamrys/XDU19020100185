# pao_ma_deng

代码：

```c++
// C++ code
//
void setup()
{
  pinMode(1, OUTPUT);
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
}

void loop()
{
  for(int i=1;i<7;i++)
  {
    digitalWrite(i, HIGH);
    delay(1000); // Wait for 1000 millisecond(s)
    digitalWrite(i, LOW);
  }
}
```

电路图：
![pao_ma_deng](https://img02.sogoucdn.com/app/a/100520146/974fe2444fed220fd1d8224ce11c5275)
