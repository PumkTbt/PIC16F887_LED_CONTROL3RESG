# PIC16F887_LED_CONTROL3RESG

![image](https://github.com/PumkTbt/PIC16F887_LED_CONTROL3RESG/assets/124877073/549b8eae-bc43-4453-90b9-86686b69b5eb)

Bình thường : 4 led 4,5,7,10 chớp tắt với f = 1Hz. Nhấn SW4 (ngắt): 8 led (D4  D11) sáng dần, thời gian hiển thị mỗi trạng thái
là 300ms

Phân tích:
Với yêu cầu ở bình thường 4 led 4,5,7,10 sáng chớp tắt với f = 1Hz. Thì với f = 1Hz, ta suy ra được là chu kì chớp ( sáng rồi tắt) là trong vòng T = 1s. Cho nên ứng với mỗi lần sáng và tắt ta cho nó delay là 500ms.

![image](https://github.com/PumkTbt/PIC16F887_LED_CONTROL3RESG/assets/124877073/f088bf2e-af7a-44d8-b970-fd8bd89a5f8e)

![image](https://github.com/PumkTbt/PIC16F887_LED_CONTROL3RESG/assets/124877073/957767ae-8ff0-45b3-916e-c8ee7e0efbf2)


