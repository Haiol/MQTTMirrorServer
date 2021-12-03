<h4>비디오:</h4>

[![MQTTMirrorServer](http://img.youtube.com/vi/t7HeZgF0mY8/0.jpg)](https://youtu.be/t7HeZgF0mY8?t=0s)

# 🎛MQTTMirrorServer
<pre>
◼ MagicMirror 모듈 과 moquitto 핸들링 서버를 통해
IOT데이터를 수집하고 다른 매개체의 쉽게 사용되도록 Json으로
가공해주는 서버입니다.
◼가공된 데이터를 그래프화하고 Mirror를 제어하는 어플리케이션도 구현했습니다. 
</pre>


<h2>🗺구상도</h2>
<div align="center">
<img    width="50%" src="https://user-images.githubusercontent.com/41848169/144437047-46997bfb-7e39-452c-8f07-6e0c760c06bc.jpg" alt="전체적인 구상도"/>
</div>
<pre>
 이 프로젝트는 한 WiFi네트워크 안에서 진행하셔야 합니다.
 이후에 WiFi관련 IOT와 같은 제품등을 테스트를 진행하기 쉽게
 환경을 조성해주는 홈 IOT네드워크시스템 입니다.
 <br/>
 Arduino <-MQTT->  RPI <-HTTP-> Android 
 서버 구성이 잘 되었는지 판단하기 위해서  DHT22 온습도 센서와 Wemos D1(와이파이 모듈)을 사용했습니다.
</pre>

<h3>이미지 사용 출저</h3>
Mobile 일러스트 : https://notefolio.net/sukwontoto/233542
