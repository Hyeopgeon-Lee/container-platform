# PaaS-TA 컨테이너 플랫폼

<table>
  <tr>
    <td colspan=2 align=center>플랫폼</td>
    <td colspan=2 align=center><a href="https://github.com/PaaS-TA/paasta-deployment">어플리케이션 플랫폼</a></td>
    <td colspan=2 align=center><a href="https://github.com/PaaS-TA/paas-ta-container-platform">🚩 컨테이너 플랫폼</a></td>
  </tr>
  <tr>
    <td colspan=2 rowspan=2 align=center>포털</td>
    <td colspan=2 align=center><a href="https://github.com/PaaS-TA/portal-deployment">AP 포털</a></td>
    <td colspan=2 align=center><a href="https://github.com/PaaS-TA/container-platform-portal-release">CP 포털</a></td>
  </tr>
  <tr align=center>
    <td colspan=4><a href="https://github.com/PaaS-TA/PaaS-TA-Monitoring">모니터링 대시보드</a></td>
  </tr>
  <tr align=center>
    <td rowspan=2 colspan=2><a href="https://github.com/PaaS-TA/monitoring-deployment">모니터링</a></td>
    <td><a href="https://github.com/PaaS-TA/PaaS-TA-Monitoring-Release">Monitoring</a></td>
    <td><a href="https://github.com/PaaS-TA/paas-ta-monitoring-logsearch-release">Logsearch</a></td>
    <td><a href="https://github.com/PaaS-TA/paas-ta-monitoring-influxdb-release">InfluxDB</a></td>
    <td><a href="https://github.com/PaaS-TA/paas-ta-monitoring-redis-release">Redis</a></td>
  </tr>
  <tr align=center>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-PINPOINT-MONITORING-RELEASE">Pinpoint</td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-PINPOINT-MONITORING-BUILDPACK">Pinpoint Buildpack</td>
    <td></td>
    <td></td>
  </tr>
  </tr>
  <tr align=center>
    <td rowspan=4 colspan=2><a href="https://github.com/PaaS-TA/service-deployment">AP 서비스</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-CUBRID-RELEASE">Cubrid</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-API-GATEWAY-SERVICE-RELEASE">Gateway</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-GLUSTERFS-RELEASE">GlusterFS</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-APP-LIFECYCLE-SERVICE-RELEASE">Lifecycle</a></td>
  </tr>
  <tr align=center>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-LOGGING-SERVICE-RELEASE">Logging</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-MONGODB-SHARD-RELEASE">MongoDB</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-MYSQL-RELEASE">MySQL</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-PINPOINT-RELEASE">Pinpoint APM</a></td>
  </tr>
  <tr align=center>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-DELIVERY-PIPELINE-RELEASE">Pipeline</a></td>
    <td align=center><a href="https://github.com/PaaS-TA/rabbitmq-release">RabbitMQ</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-ON-DEMAND-REDIS-RELEASE">Redis</a></td>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-SOURCE-CONTROL-RELEASE">Source Control</a></td>
  </tr>
  <tr align=center>
    <td><a href="https://github.com/PaaS-TA/PAAS-TA-WEB-IDE-RELEASE-NEW">WEB-IDE</a></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr align=center>
    <td rowspan=1 colspan=2><a href="https://github.com/PaaS-TA/paas-ta-container-platform-deployment">CP 서비스</a></td>
    <td><a href="https://github.com/PaaS-TA/container-platform-pipeline-release">Pipeline</a></td>
    <td><a href="https://github.com/PaaS-TA/container-platform-source-control-release">Source Control</a></td>
    <td></td>
    <td></td>
  </tr>
</table>
<i>🚩 You are here.</i>

## 소개
네이티브 쿠버네티스 설치 가이드(Kubespray 설치, KubeEdge 설치) 및 쿠버네티스에 컨테이너 플랫폼을 배포하여 사용할 수 있는 방법(PaaS-TA를 통해 서비스 형태로 배포되는 CaaS 배포와 단독 배포)에 대한 설치 및 활용 가이드를 다루고 있다.

## 단독 배포   
- [Kubespray 설치 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/install-guide/standalone/paas-ta-container-platform-standalone-deployment-guide-v1.1.md)
  + [설치 및 배포 파일](https://github.com/PaaS-TA/paas-ta-container-platform-deployment/tree/master/standalone)
- [Kubespray 용 단독 배포 설치 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/install-guide/bosh/paas-ta-container-platform-bosh-deployment-spray-guide-v1.1.md)  
  + [설치 및 배포 파일](https://github.com/PaaS-TA/paas-ta-container-platform-deployment/tree/master/bosh)  
  + [릴리즈 파일](https://github.com/PaaS-TA/paas-ta-container-platform-release/tree/master)

## Edge 배포
- [KubeEdge 설치 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/install-guide/edge/paas-ta-container-platform-edge-deployment-guide-v1.0.md)  
  + [설치 및 배포 파일](https://github.com/PaaS-TA/paas-ta-container-platform-deployment/tree/master/edge)
- [KubeEdge 용 단독 배포 설치 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/install-guide/bosh/paas-ta-container-platform-bosh-deployment-edge-guide-v1.0.md)  
  + [설치 및 배포 파일](https://github.com/PaaS-TA/paas-ta-container-platform-deployment/tree/master/bosh)  
  + [릴리즈 파일](https://github.com/PaaS-TA/paas-ta-container-platform-release/tree/master)

## 서비스형 배포 
- [Kubespray 설치 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/install-guide/standalone/paas-ta-container-platform-standalone-deployment-guide-v1.1.md)  
  + [설치 및 배포 파일](https://github.com/PaaS-TA/paas-ta-container-platform-deployment/tree/master/standalone)
- [CaaS 배포 설치 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/install-guide/bosh/paas-ta-container-platform-bosh-deployment-caas-guide-v1.1.md)
  + [설치 및 배포 파일](https://github.com/PaaS-TA/paas-ta-container-platform-deployment/tree/master/bosh)   
  + [릴리즈 파일](https://github.com/PaaS-TA/paas-ta-container-platform-release/tree/master) 

## 포털 이용 가이드
- 운영자 포털
  + [운영자 포털 사용 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/use-guide/portal/paas-ta-container-platform-admin-guide-v1.0.md)
- 사용자 포털
  + [사용자 포털 사용 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/use-guide/portal/paas-ta-container-platform-user-guide-v1.0.md)  

## 서비스 이용 가이드
- Pipeline
  + [Pipeline 사용 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/use-guide/pipeline/paas-ta-container-platform-pipeline-use-guide.md)
- Source-Control
  + [Source-Control 사용 가이드](https://github.com/PaaS-TA/paas-ta-container-platform/blob/master/use-guide/source-control/paas-ta-container-platform-source-control-use-guide.md) 

## 프로젝트
### PaaS-TA 컨테이너 플랫폼
- [API 개발 소스 파일](https://github.com/PaaS-TA/paas-ta-container-platform-api)  
- [COMMON API 개발 소스 파일](https://github.com/PaaS-TA/paas-ta-container-platform-common-api)
- [WEB ADMIN 개발 소스 파일](https://github.com/PaaS-TA/paas-ta-container-platform-webadmin)
- [WEB USER 개발 소스 파일](https://github.com/PaaS-TA/paas-ta-container-platform-webuser)
 

### PaaS-TA 컨테이너 서비스
- [API 개발 소스 파일](https://github.com/PaaS-TA/paas-ta-container-platform-caas-api)
- [COMMON API 개발 소스 파일](https://github.com/PaaS-TA/paas-ta-container-platform-caas-common-api)
- [DASHBOARD 개발 소스 파일](https://github.com/PaaS-TA/paas-ta-container-platform-caas-dashboard)
- [CONTAINER SERVICE BROKER 개발 소스 파일](https://github.com/PaaS-TA/paas-ta-container-platform-caas-service-broker)
- [JENKINS SERVICE BROKER 개발 소스 파일](https://github.com/PaaS-TA/paas-ta-container-platform-caas-jenkins-broker)

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/jinyung0101java2"><img src="https://avatars.githubusercontent.com/u/67574725?v=4?s=100" width="100px;" alt=""/><br /><sub><b>JinYoung Jang</b></sub></a><br /><a href="https://github.com/PaaS-TA/paas-ta-container-platform/commits?author=jinyung0101java2" title="Code">💻</a> <a href="https://github.com/PaaS-TA/paas-ta-container-platform/pulls?q=is&Apr+reviewed-by&jinyung0101java2" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/hoon77"><img src="https://avatars.githubusercontent.com/u/33216551?v=4?s=100" width="100px;" alt=""/><br /><sub><b>JiHoon Kang</b></sub></a><br /><a href="https://github.com/PaaS-TA/paas-ta-container-platform/commits?author=hoon77" title="Code">💻</a> <a href="https://github.com/PaaS-TA/paas-ta-container-platform/pulls?q=is&Apr+reviewed-by&hoon77" title="Reviewed Pull Requests">👀</a></td>
    <td align="center"><a href="https://github.com/suslmk-lee"><img src="https://avatars.githubusercontent.com/u/67575226?v=4?s=100" width="100px;" alt=""/><br /><sub><b>suslmk</b></sub></a><br /><a href="#maintenance-suslmk" title="Maintenance">🚧</a></td>
    <td align="center"><a href="https://github.com/dev-taewoo"><img src="https://avatars.githubusercontent.com/u/67407365?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Taewoo Kim</b></sub></a><br /><a href="https://github.com/PaaS-TA/paas-ta-container-platform/commits?author=dev-taewoo" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/rexx4314"><img src="https://avatars.githubusercontent.com/u/26153262?v=4?s=100" width="100px;" alt=""/><br /><sub><b>rexx4314</b></sub></a><br /><a href="#ideas-rexx4314" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/opdc-minsu"><img src="https://avatars.githubusercontent.com/u/67140002?v=4?s=100" width="100px;" alt=""/><br /><sub><b>MinSu Kang</b></sub></a><br /><a href="https://github.com/PaaS-TA/paas-ta-container-platform/issues?q=author&opdc-minsu" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/jhuhm135"><img src="https://avatars.githubusercontent.com/u/70005316?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Juhyun Um</b></sub></a><br /><a href="#ideas-jhuhm135" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/kyuminhan"><img src="https://avatars.githubusercontent.com/u/80228983?v=4?s=100" width="100px;" alt=""/><br /><sub><b>KyuMin Han</b></sub></a><br /><a href="#ideas-kyuminhan" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
  
## 라이선스
[Apache-2.0 License](http://www.apache.org/licenses/LICENSE-2.0)를 사용한다. 
