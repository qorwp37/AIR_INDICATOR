# AIR_INDICATOR
환경표시기 제품 또는 비슷한 제품을 만들때 레퍼런스가 될 수 있는, 신뢰성 있는 자료입니다.

- 과제수행기간: 2020.8 - 2020/10
- 기타 정보: 환경표시기 H/W를 구성하는 회로와, F/W를 이루는 코드입니다.

1. 하드웨어를 구성하는 회로도는 이 문서 아래에서 볼 수 있습니다.
2. 소프트웨어를 구현한 코드는 [환경표시기 펌웨어 코드](https://github.com/qorwp37/AIR_INDICATOR/blob/main/%ED%99%98%EA%B2%BD%ED%91%9C%EC%8B%9C%EA%B8%B0%20%ED%8E%8C%EC%9B%A8%EC%96%B4%20%EC%BD%94%EB%93%9C) 에서 볼 수 있습니다. (include 하는 C파일에 정의된 함수들은 함수 이름에서 어느정도 기능을 알 수 있기때문에 같이 올리지 않았습니다.)
3. 이렇게 만들어진 제품의 동작영상을 아래 링크에서 볼 수 있습니다.
https://blog.naver.com/PostView.nhn?blogId=qorwp37&Redirect=View&logNo=222172059215&categoryNo=1&isAfterWrite=true&isMrblogPost=false&isHappyBeanLeverage=true&contentLength=2703


[주요 사용 부품] 
1. MCU : ATmega128A
2. Humidity/Temperature Sensor : HTU21D (I2C)
3. Dust sensor : GP2Y1010AU0F (ADC) 


[환경표시기 회로도]
클릭하면 훨씬 더 잘 보입니다.
<img src="https://user-images.githubusercontent.com/58552452/102001432-8e022b80-3d35-11eb-84a0-17b4a784c70e.PNG" width="90%"></img>
