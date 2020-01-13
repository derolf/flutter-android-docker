docker build -t flutter-android .
docker tag flutter-android:latest derolfus/flutter-android
docker push derolfus/flutter-android
