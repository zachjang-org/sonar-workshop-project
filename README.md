## 1. import and clone repo to local

git clone https://{user_name}:{token}@github.com/{org_name}/workshop-project.git

## 2. manual scan

mvn clean install -DskipTests=true sonar:sonar -Dsonar.host.url=https://sonarcloud.io -Dsonar.token=ab83837cf00d600234cca44e3d728504c1aade95

## 3. this is a new line for new commit trigger GitHub Action

## 4. this is a new line for new commit trigger GitHub Action
