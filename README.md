# swagger ui 데모

* https://petstore.swagger.io/

## swagger json

* GitLab : https://raw.githubusercontent.com/boajang/swagger/main/williamalvessantos-gitlab-v4-resolved.json 
* Nexus : https://raw.githubusercontent.com/boajang/swagger/main/nexus-swagger.json
* Jenkins : https://raw.githubusercontent.com/boajang/swagger/main/klauern-swaggy-jenkins-0.2.0-resolved.json

## swagger pdf 변환

```
$ npm install -g swagger-spec-to-pdf
$ swagger2pdf -j -s xxx.json
```

## 참고 
* v3에서 v4로 변경된 사항 : https://gitlab.com/gitlab-org/gitlab-foss/-/blob/11-0-stable/doc/api/v3_to_v4.md 
* swagger doc convert pdf : http://rajeevdotnet.blogspot.com/2019/02/export-swagger-api-document-to-pdf.html
* swaggerHub : https://app.swaggerhub.com/home
