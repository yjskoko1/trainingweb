# 트레이닝웹 안드로이드 앱 (헬스 커넥트)

Capacitor 껍데기 앱이에요. 화면은 https://yjskoko1.github.io/trainingweb/ 을 그대로 열어서, 웹앱을 고치면 앱도 바로 바뀌어요.
APK를 다시 만들어야 하는 건 헬스 커넥트 같은 휴대폰 기능 쪽을 바꿀 때뿐이에요.

빌드: `npm install && npx cap sync android && cd android && ./gradlew assembleRelease`
결과물은 ../app/trainingweb.apk 로 복사해요. 서명 키는 trainingweb.jks (개인 설치용).
